---
description: Understand appointment statuses and the actions that change them.
---

# Understand appointment statuses

Each appointment has a status. The status indicates its progress: waiting for scheduling, scheduled, completed, or cancelled.

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

## Colors in the schedule

In the schedule, an appointment's color changes with its status. For example, a confirmed appointment appears in dark green.
