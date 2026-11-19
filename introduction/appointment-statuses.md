---
description: Understand appointment statuses and the actions that change them.
---

# Understand appointment statuses

Each appointment has a status. The status indicates its progress: waiting for scheduling, scheduled, completed, or cancelled.

The status lets you search for, count, and filter appointments, and it determines what can still be changed.

For example, an appointment confirmed by phone with the customer commits your organization: set it to **Confirmed**. It stays in the schedule, and neither the field worker, nor the date, nor the time can change any more.

## Available statuses

Statuses are grouped by family. This grouping is visible in the **Status** field when searching for appointments.

| Family            | Statuses                    |
| ----------------- | --------------------------- |
| **Candidate**     | Requested, Suspended        |
| **Scheduled**     | Planned, Booked, Confirmed  |
| **Completed**     | Completed, Moved, Unplanned |
| **Cancelled**     | Abandoned, Unscheduled      |
| **Subcontracted** | Subcontracted               |

While booking an appointment, the **Scheduling in progress** status appears until the selected time slot is confirmed.

### What each status allows

| Status            | Scheduled | What can still change                                                                                                                                       |
| ----------------- | --------- | ----------------------------------------------------------------------------------------------------------------------------------------------------------- |
| **Requested**     | No        | Everything: the appointment can be placed by any means, including global optimization.                                                                      |
| **Suspended**     | No        | The appointment can be rescheduled, but not by global optimization. It waits for an action from you, for example a call back to the customer.              |
| **Planned**       | Yes       | The field worker, the date, and the time.                                                                                                                   |
| **Booked**        | Yes       | The field worker. The date and time are fixed.                                                                                                              |
| **Confirmed**     | Yes       | Nothing: the field worker, the date, and the time are fixed.                                                                                                |
| **Completed**     | -         | Completed on the planned date, by the assigned field worker.                                                                                                |
| **Moved**         | -         | Completed, but not on the planned date or not by the assigned field worker.                                                                                 |
| **Unplanned**     | -         | Completed although it was not scheduled.                                                                                                                    |
| **Abandoned**     | No        | Cancelled while it was not yet scheduled.                                                                                                                   |
| **Unscheduled**   | No        | Cancelled while it was scheduled.                                                                                                                           |
| **Subcontracted** | No        | Entrusted to a subcontractor.                                                                                                                               |

{% hint style="info" %}
The **Accept** action fixes the assignment of a planned appointment: the date and time can still change, but the field worker can no longer change.
{% endhint %}

## How an appointment changes status

An appointment changes status during an optimization, a manual scheduling, an action on a selection of appointments, a report, or a data import. The following rules apply:

* a candidate appointment becomes scheduled when it is placed in a schedule;
* a scheduled appointment can become a candidate again: it is then unplanned (**Requested** status) or suspended (**Suspended** status);
* a scheduled appointment becomes completed when its completion is declared: it becomes **Completed** if the completion takes place on the planned day, by the assigned field worker, and **Moved** otherwise;
* a candidate appointment whose completion is declared becomes **Unplanned**;
* an appointment can be cancelled at any time: it becomes **Abandoned** if it was a candidate, **Unscheduled** if it was scheduled;
* a cancelled appointment can be reactivated: it becomes a candidate again.

{% hint style="info" %}
When a scheduled appointment is removed from the schedule to make room for another appointment or because of an unavailability, it becomes a candidate again. Depending on your environment's configuration, it becomes **Requested** or **Suspended**.
{% endhint %}

## Actions that change the status

The following actions are available in an appointment record. Their descriptions use the application tooltips.

| Action          | Effect                                                                                                                                        |
| --------------- | --------------------------------------------------------------------------------------------------------------------------------------------- |
| **Plan**        | Schedule the appointment as planned                                                                                                           |
| **Book**        | Book the appointment: the appointment time is defined                                                                                         |
| **Accept**      | Accept the appointment: its assignment must no longer change                                                                                  |
| **Confirm**     | Confirm the appointment                                                                                                                       |
| **Suspend**     | The customer must be called back and the appointment rescheduled in real time. No batch optimization rescheduling occurs for this appointment |
| **Reactivate**  | Set the appointment to Requested so that batch optimization can schedule it                                                                   |
| **Unplan**      | Return the appointment to its status before scheduling: Requested or Suspended                                                                |
| **Replan**      | Reschedule the appointment by running real-time optimization or setting a date and field worker                                               |
| **Subcontract** | Send the appointment to the subcontractor                                                                                                     |

Available actions depend on the current appointment status. For more information, see the appointment record.

## Track the progress of an appointment

In addition to the status, the **Completion status** section of the appointment record shows the **Progress** field. It indicates whether the appointment was carried out: **Undetermined state**, **Not performed**, **Performed**, or **Unsuccessful**.

For more information, see [View an appointment record](../appointments/view-an-appointment-record.md).

## Colors in the schedule

In the schedule, an appointment's color changes with its status. For example, a confirmed appointment appears in dark green.

<!-- REVIEW: the "What each status allows" table, the status-change rules and the Progress values (Undetermined state, Not performed, Performed, Unsuccessful) are translated from the updated French topic. The status names follow the existing table on this page. Check the Progress labels against the Completion status section of the appointment record. -->
