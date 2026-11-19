---
description: Appointment fields, statuses and lifecycle, actions, details, and completions.
---

# Integrate appointments

The appointment (Appointment, "intervention" in the former terminology) describes work to be performed at a customer's site. It carries a possible completion period (DATEMINBEGIN – DATEMAXEND), one or more intervention types and, once scheduled, a date and assigned resources.

| Field | Type | Req. | Reference | Description | Example / default |
| --- | --- | --- | --- | --- | --- |
| APPOINTMENTID | ID | Yes |  | Appointment identifier | e.g. ITV\_001 |
| CUSTOMERID | Ref. | Yes | Customer | Identifier of the site/customer. |  |
| TASKTYPES | Ref. list | No | Intervention type | List of the intervention types to perform | e.g. TT\_001;TT\_002 |
| DURATION | Duration | No |  | Estimated duration of this appointment, in minutes. | e.g. 120 |
| DATEMINBEGIN | Date (start) | No |  | Start date of the possible completion period of this appointment | e.g. JJ/MM/AAAAA |
| DATEMAXEND | Date (end) | No |  | End date of the possible completion period of this appointment | e.g. JJ/MM/AAAAA |
| EXPECTEDDATE | Date | No |  | The expected date is used preferentially to place this appointment | default 2013/01/15 |
| DAILYSTARTTIMEMIN | Time | No |  | Earliest time from which an appointment can be placed |  |
| PRIORITY | Integer | No |  | Priority associated with the appointment, between 0 and 100. It can be inherited from the site/customer. | e.g. 50 · default 0 (meaning no priority) |
| REQUESTEDMANPOWER | Integer | No |  | Number of field workers required to perform this appointment (min 1, max 10) | e.g. 1 |
| QUALIFICATIONS | Ref. list | No | Skill | List of the skills required to perform this appointment | e.g. QUA\_001;QUA\_002 |
| WORKSITEID | Ref. | No | Work site | Agency this appointment is attached to | e.g. WKS\_001 |
| STATUS | String | No |  | Appointment status (linked to the lifecycle. 21: requested, 2: planned, 30: booked, 31: confirmed, 10: abandoned, 6: suspended, 3: completed. The following statuses are available only on export: 12: unscheduled, 33: moved, 35: unplanned) |  |
| PROGRESSIONSTEP | String | No |  | Progression step in the scheduling lifecycle. Possible values (code or string accepted): 0:scheduling [to be scheduled] (default), 5:back\_scheduling [scheduled by the back office], 10:ongoing [in progress], 15:partially\_done [partially done], 20:done [done], 50:completed [completed], 100:closed [closed] | e.g. 10 or ONGOING or ongoing (to indicate that the appointment is already in progress) · default 0 or null, meaning scheduling |
| DATEAPPOINTMENT | Date | No |  | Date of the visit as known in Nomadia Field Service | e.g. JJ/MM/AAAA |
| ASSIGNEDRESOURCES | Ref. list | No | Human resource | List of the field workers assigned to this appointment once scheduling is done | e.g. TECH\_001;TECH\_002 |
| ACTION | String | No |  | Technical field used to trigger an action after the appointment is imported ("SCHEDULE": triggers an optimized slot search for this appointment after its import, "CLEAR\_NOTIFICATIONS": clears the appointment notifications, "OUTSOURCE": to outsource to a subcontractor, "INSOURCE": to remove the reference to a subcontractor, "SEARCH\_PERIODIC": to search for a periodic appointment with an unknown id, by providing its customer id as well as the date and status, "DELETE": to physically delete an appointment, "CLEAR\_ACHIEVEMENTS": to clear the completions of an appointment, "CLEAR\_ACHIEVEMENTS\_BY\_DAY": to clear and replace the completions of the same day as the start date of the new completion) |  |

<!-- REVIEW: example date formats "JJ/MM/AAAAA" (five A's, DATEMINBEGIN and DATEMAXEND) and "JJ/MM/AAAA" are French placeholders kept as in the source; the five-letter form looks like a typo. -->

The AppointmentCustomer field (an entity of the same name) is a shared identifier that makes it possible to import an appointment and its customer in the same row.

## Statuses and lifecycle

The status of an appointment (STATUS) is a numeric code. Each status belongs to a macro-status.

| Code | Status (internal code) | Label | Macro-status | Meaning |
| --- | --- | --- | --- | --- |
| 21 | REQUESTED | Requested | Candidate | To be scheduled by any means. |
| 6 | SUSPENDED | Suspended | Candidate | To be scheduled, but excluded from global optimization. |
| 2 | PLANNED | Planned | Scheduled | Scheduled; can be moved and reassigned. |
| 28 | ACCEPTED | Accepted | Scheduled | Scheduled; can be moved but not reassigned to another resource. |
| 30 | RESERVED | Booked | Scheduled | Scheduled; can no longer be moved but can be reassigned. |
| 31 | CONFIRMED | Confirmed | Scheduled | Scheduled; neither movable nor reassignable. |
| 3 | REALIZED | Completed | Achieved | Completed on the planned day by the assigned resource. |
| 33 | SHIFTED | Moved | Achieved | Completed, but not on the planned day or not by the assigned resource. |
| 35 | HAPPENED | Unplanned | Achieved | Completed without having been scheduled. |
| 12 | REMOVED | Unscheduled | Cancelled | Will not be performed; had been scheduled. |
| 10 | ABANDONED | Abandoned | Cancelled | Will not be performed; had not been scheduled. |
| 9 | IGNORED | Ignored | Aside | Set apart from the system; ignored by all processing until it is restored. |
| 32 | EXTERNALIZED | Subcontracted | Aside | Entrusted to a subcontractor. |

![Appointment status lifecycle: the macro-statuses Candidate (Requested 21, Suspended 6), Scheduled (Planned 2, Accepted 28, Booked 30, Confirmed 31), Achieved (Completed 3, Moved 33, Unplanned 35), Cancelled (Unscheduled 12, Abandoned 10), and Aside (Ignored 9, Subcontracted 32), with the transitions scheduling, unplanning, completion, unscheduling, and abandonment.](../.gitbook/assets/en_integration_appointment_lifecycle.png)

*Appointment lifecycle*

### Status change rules on import

Nomadia Field Service rejects or converts some of the changes requested by import:

* a scheduled appointment (Scheduled macro-status) cannot change to Abandoned (10) or Unplanned (35); a request to abandon an appointment that is already scheduled is converted to Unscheduled (12);
* an appointment to be scheduled (Candidate) cannot change directly to Unscheduled (12), Completed (3), or Moved (33). A "Completed" request on an appointment that was never scheduled is converted to Unplanned (35), provided the completion dates are supplied; otherwise it is rejected;
* a completed appointment cannot change status within the Achieved macro-status;
* requesting a scheduled status for an appointment that is not scheduled triggers scheduling;
* for an appointment with several resources, the change to Completed can wait until each resource has finished (parameter eachResourceMustTerminate, enabled by default); the progression step then changes to PARTIALLY\_DONE.

The code 0 (UNKNOWN) or the current status does not change the status. The code 40 (HISTORIZED) is not a business status: it is used to hide historized copies.

### Progression steps

In addition to the status, the PROGRESSIONSTEP field (code or label) tracks progress: SCHEDULING (0, to be scheduled), IN\_PREPARATION (-10), BACK\_SCHEDULING (2), MERGED (3), REFUSED (4), SUPPORTED (5), PINNED (7), ONGOING\_TRIP\_TO\_APPT (8), ONGOING (10), PARTIALLY\_DONE (15), DONE (20), COMPLETED (50), CLOSED (100).

## Actions on appointments

The ACTION column accepts one or more values, separated by the list separator.

| Value | Effect |
| --- | --- |
| SCHEDULE | Starts an optimized slot search after the appointment is imported. |
| DELETE | Physically deletes the appointment. |
| UNEXPECT | Cancels an expected date and restores the customer. |
| CLEAR\_NOTIFICATIONS | Clears the appointment notifications. |
| CLEAR\_ACHIEVEMENTS / CLEAR\_ACHIEVEMENTS\_BY\_DAY | Clears the completions (all of them, or those of the day of the new completion start date). |
| OUTSOURCE / INSOURCE | Assigns a subcontractor / removes the subcontractor and sets the appointment back to the Requested status. |
| SEARCH, SEARCH\_PERIODIC | Searches for a periodic appointment to perform or reactivate (SEARCH is going to be removed). |
| DELETEMULTIMEDIA | Purges the attached multimedia files (photos, documents, reports). |

## Details, completions, and parcels

* Appointment detail (AppointmentDetail): detail lines (product, equipment, quantities) attached by APPOINTMENTID.
* Completion slot (AchievementSlot): completion declared per resource (dates, resources, status).
* Parcel (Parcel) and grouped pickup and delivery (GroupedPickupDelivery) for delivery activities.

Previous: [Integrate customers and sites](integrate-customers-and-sites.md)

Next: [Import data](import-data.md)
