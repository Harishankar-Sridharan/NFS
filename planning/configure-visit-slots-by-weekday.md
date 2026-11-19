---
description: Define different visit slots on an appointment for each day of the week.
---

# Configure visit slots by day of the week

Visit slots by day of the week let you define, on an appointment, the hours when the intervention is possible, day by day. For example: Monday from 8:00 to 12:00 and Thursday from 14:00 to 17:00.

These slots form the appointment's own week. They replace the project's and the customer's opening hours, and both real-time optimization and batch optimization take them into account.

{% hint style="info" %}
A day without a slot is a closed day: the appointment is not scheduled on that day. An appointment without its own slots keeps using the project's hours, then the customer's hours.
{% endhint %}

## Before you begin

* The **Customer availability** field and the **Opening hours by day** section must be displayed. See [Set the display](#set-the-display).
* To edit the slots, you need the right to edit appointments. Without it, the edit button does not appear and the slots are read-only.

## Understand which hours apply

For each appointment, Nomadia Field Service uses a single source of hours, in this order:

| Priority | Source                              | How to recognize it                          |
| -------- | ----------------------------------- | -------------------------------------------- |
| 1        | The appointment's own slots         | No icon                                      |
| 2        | The project's opening hours         | Folder icon, tooltip **Project opening hours**  |
| 3        | The customer's opening hours        | Person icon, tooltip **Customer opening hours** |

The sources are not combined: as soon as the appointment has its own slots, the project's and the customer's slots are ignored, even if the customer is not available during that slot.

**Example:** an appointment has the slots Monday 08:00–10:00, Tuesday 16:00–18:00, and Friday 14:00–16:00. The customer is available in the morning only.

| Day                      | Result                                                                              |
| ------------------------ | ----------------------------------------------------------------------------------- |
| Monday                   | Can be scheduled between 08:00 and 10:00                                            |
| Tuesday                  | Can be scheduled between 16:00 and 18:00, even outside the customer's availability  |
| Friday                   | Can be scheduled between 14:00 and 16:00                                            |
| Wednesday (no slot)      | Closed day: no scheduling on that day                                               |

## Access the slots

| Where                                                                | What you see                                                             | Can you edit? |
| -------------------------------------------------------------------- | ------------------------------------------------------------------------ | ------------- |
| Appointment record, **Opening hours by day** section                 | The slots of each day. When closed, the section shows a one-line summary | No            |
| Edit form (**Edit...**)                                              | **Customer availability** field: summary of the slots and an edit button | Yes           |
| Appointment booking: request and optimized scheduling                | **Customer availability** field with the edit button                     | Yes           |
| Manual scheduling                                                    | Summary of the slots, without a button                                   | No            |

**Navigation:** `Appointment record > Edit... > Customer availability`

## Enter the slots

1. Open the appointment record, then select **Edit...**. For more information, see [Edit an appointment](../appointments/edit-an-appointment.md).
2. Next to **Customer availability**, select the edit button. The **Opening hours by day** window opens. It is prefilled with the current hours: the appointment's own, or otherwise those inherited from the project or the customer.
3. Choose the entry mode:
   * **Continuous day**: one slot per day;
   * **Morning / afternoon**: two ranges per day. The gap between them is the break.
4. Select a day's marker (M, T, W, T, F, S, S) to open or close that day.
5. Enter the start time and the end time. If you enter only the start time, the end time is suggested automatically 2 hours later.
6. To repeat a day's slot, select the **Copy to other days** icon at the right of the row, choose the days (shortcuts **Mon-Fri**, **All**, **None**), then select **Apply** in the bubble.
7. Select **Apply**. The summary of the **Customer availability** field is updated.
8. Select **Save** to keep the slots on the appointment.

In **Morning / afternoon** mode, empty break fields display **no break**.

### Input checks

A message appears under the day concerned when the entry is incomplete or inconsistent:

| Message                                              | Meaning                                              |
| ---------------------------------------------------- | ---------------------------------------------------- |
| Start and end times are required                     | An open day does not have both times.                |
| The start time must be before the end time           | The end time is before the start time.               |
| The morning must end before the afternoon starts     | In **Morning / afternoon** mode, the two ranges overlap. |

### Other actions in the window

* **Undo** cancels the last change.
* **Clear all** closes all days.
* **Cancel**, or the close cross, restores the starting hours.

## View the slots

In the edit form, hover over the summary of the **Customer availability** field to display the day-by-day detail. Days without a slot show **Closed**.

In the appointment record, the **Opening hours by day** section shows the slots of each day. When the section is closed, a summary appears next to its title.

When the appointment has no slots of its own, the summary shows the inherited hours, preceded by the project's or the customer's icon.

## Return to the project's or customer's hours

1. In the **Opening hours by day** window, select **Clear all**.
2. Select **Apply**, then **Confirm** in the message.
3. Save the appointment.

| Message                                                | Result                                              |
| ------------------------------------------------------ | --------------------------------------------------- |
| No own hours: the project's hours will apply.          | The appointment takes the project's hours.          |
| No own hours: the customer's hours will apply.         | The appointment takes the customer's hours.         |
| No hours: the appointment will have none.              | Neither the project nor the customer has hours.     |

{% hint style="info" %}
If you validate the window without changing the inherited hours, no slot of its own is created: the appointment keeps following the project or the customer, including if they are modified later.
{% endhint %}

## Import and export the slots

The slots are in the appointment CSV file, with the same columns as the customer's opening hours.

| Column                                                         | Content                                                                                           |
| -------------------------------------------------------------- | ------------------------------------------------------------------------------------------------- |
| `DAYnBEGINTIME` / `DAYnENDTIME`                                | Start and end of the slot of day n (1 = Monday, 7 = Sunday), in HH:MM format. 00:00 = closed day. |
| `DAYnBEGINLUNCHPERIOD` / `DAYnENDLUNCHPERIOD`                  | Start and end of the break of day n. 00:00 = no break.                                            |
| `DAYBEGINTIME`, `DAYENDTIME`, `DAYBEGINLUNCHPERIOD`, `DAYENDLUNCHPERIOD` | Values applied to all days. Import only.                                                |

Times are expressed in the customer's time zone. Enter all 7 days: an incomplete week is ignored.

## Set the display

**Navigation:** `Administration > Customization > Application configuration`

Filter on `openingHours` to display the settings concerned.

| Setting                                                                          | Default | Effect                                                              |
| -------------------------------------------------------------------------------- | ------- | ------------------------------------------------------------------- |
| `page.callcenter.ignore.fields` > `openingHours`                                 | `false` | `false`: slots displayed. `true`: slots hidden on all screens.      |
| `page.callcenter.appointment.sheet.fieldGroups` > `openingHours_isByDefaultOpened` | `false` | The appointment record section is open or closed when displayed.    |
| `page.callcenter.appointment.sheet.fieldGroups` > `openingHours_whenClosedShowSummaryInfo` | `true`  | The summary is displayed next to the title of the closed section.   |

For more information, see [Customize the application](../administration/customize-the-application.md).

## Notes

* The appointment's daily slot (daily start and end times) still applies in addition to the slots by day: the optimization uses the part common to both.
* The customer's closures and the break entered in a slot are always respected.
* The slots entered in the window are kept only after you save the appointment.

<!-- REVIEW: this topic has no screenshots. The labels Opening hours by day, Customer availability, Continuous day, Morning / afternoon, Copy to other days, Mon-Fri, All, None, Apply, Undo, Clear all, Cancel, Confirm, the tooltips, and the input-check and confirmation messages are translated from the French topic and were not verified in the application. Capture the Opening hours by day window (continuous day, morning / afternoon, copy bubble, input check, confirmation) and the appointment record section. -->
