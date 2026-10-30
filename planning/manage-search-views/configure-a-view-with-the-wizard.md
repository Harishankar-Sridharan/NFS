---
description: >-
  Configure the filters, columns, actions, and display options for a MySearch
  view.
---

# Configure a view with the wizard

Administrator and user views use the same **Edit MySearch** window. The wizard has five steps: **Filters**, **Columns**, **Optional actions**, **Bulk actions**, and **Proceed**.

Move between steps with **Next** and **Previous**, or select the step name directly.

## Step 1: Filters

Choose the criteria that select appointments for the view.

1. In the category tree (**Identifiers**, **Address**, **Appointment**, **Customer**, **Dates/Times**, **Resources**, and more), select the fields to filter. Use the **Filter** field above the tree to search by field name.
2. Each selected field is added to the **Field / !NOT / Operator / Value / Hidden** table.
3. Select a row’s pencil icon to open the **Edit criterion** window.
4. Select the **Operator**, enter the **Value**, then select **OK**.
5. If needed, select **Hidden** to apply the criterion without showing it in results. Select **!NOT** to invert the criterion.

![Edit criterion window for the Status field, with Planned and Confirmed values](/broken/files/RvCgG8KhZ1EBT6z5KLEI)

Available operators depend on the field: equals, between, less than, greater than, in, like, contains, is null, and not null. Some fields accept only one operator. For some fields, **!NOT** is marked as unsupported.

| Field type                     | Value entry                                                                                                                                                                                                                                                                             |
| ------------------------------ | --------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Date                           | Relative value from today: days, for example **5** for five days from now, **-4** for four days ago, or **0** for today; weeks, for example **We1**; or weeks and days, for example **W1D2**. You can also enter a fixed date in **dd/mm/yyyy** format. The window provides input help. |
| Time, duration                 | Use **HH:mm** format.                                                                                                                                                                                                                                                                   |
| Value list, such as Status     | Select one or more values. Remove **--All--** to keep only the selected values.                                                                                                                                                                                                         |
| List without predefined values | Separate values with **commas**.                                                                                                                                                                                                                                                        |

![Edit criterion window for a date, with relative-value input help](/broken/files/uWZ6AiT5K1DhqPOktGpC)

Use the arrows on each row to change the criterion order. Use the bin to remove a criterion.

![Filters step with two criteria: Status and From](/broken/files/utluzJVdurSYO6djWDRZ)

{% hint style="warning" %}
At least one criterion is required. Otherwise, the message “There must be at least one criterion” appears.
{% endhint %}

## Step 2: Columns

Choose the fields shown in the results table.

1. In the tree, select the fields to display. They are added to the **Selected columns** list.
2. Select a column and use the buttons below the list to move it: first, up, down, last, or remove.

![Columns step with five selected columns](/broken/files/09k7xfqR08AVsD4oyscW)

The column order also defines the CSV export order.

{% hint style="warning" %}
At least one column is required: “There must be at least one column.”
{% endhint %}

## Step 3: Optional actions

Enable the actions available on each results row: **Selection list**, **Appointment basket**, **Map**, **Calendar**, **Schedule appointment**, and **Tracking**. All actions are enabled by default except **Tracking**.

![Optional actions step with result-row action toggles](/broken/files/m6w2RbgvWLyx3PyyincL)

## Step 4: Bulk actions

Enable the bulk actions available below the results list. They are grouped into three categories:

* **Edit** actions, enabled by default: **Move dates**, **Edit arrival times**, **Edit resources**, **Edit skills**, **Edit priority**, **Change requested manpower**, **Edit work site**, **Edit additional data**, and **Edit duration**. Only **Edit with appointment** is disabled by default.
* **Status change** actions, disabled by default: unschedule, unconfirm, revive cancelled appointments, or set the status to **Requested**, **Suspended**, **Cancelled**, **Accepted**, **Reserved**, **Confirmed**, or **Completed**.
* **Other actions**: **Schedule** is enabled by default. **Subcontract** and **Announce** are disabled.

![Bulk actions step, Edit category](/broken/files/PH9p5gAOIs7B7gDyNegV)

![Bulk actions step, Status change and Other actions categories](/broken/files/gYoLJQdkqkDxI8NUvVD8)

{% hint style="info" %}
A user can use a bulk action only when it is enabled here and they have the required permission.
{% endhint %}

## Step 5: Proceed (display options)

| Field                    | Purpose                                                                                                                  |
| ------------------------ | ------------------------------------------------------------------------------------------------------------------------ |
| **Name**                 | View name, shown in the menu and as the list title. Required for a user view.                                            |
| **Result list max size** | Maximum number of rows displayed. The default is **300**.                                                                |
| **Sort list**            | Initial list sort order. Keep the default value, **0,0**, unless needed.                                                 |
| **Tooltip**              | Help text shown on hover.                                                                                                |
| **Show counter**         | Shows the view as a counter card on the home screen. It displays the **Counter name** and **Counter icon** fields.       |
| **Hide counter value**   | For user views only. Shows the card without the appointment count. It is enabled by default when you enable the counter. |

![Proceed step with a view name and the counter enabled](/broken/files/hAhd8YMFi7CwLIiXLbgc)

**Counter icon** offers seven icons: **counter**, **account**, **alert**, **chart\_pie**, **flag**, **format\_list\_bulleted**, and **message\_alert**.

![List of available counter icons](/broken/files/xVXIgpwqcCOfYdEUQRE9)

## Save and close

1. Select **Save changes**. When creating a view, this button appears only on the **Proceed** step. When editing, it is available on every step.
2. The **MySearch was created successfully.** or **MySearch was saved successfully.** message confirms the operation.
3. Close the window with the cross in the upper-right corner.

![Confirmation message after saving a view](/broken/files/pHqNB3oGA8sc9BY9P8Yu)

* If a criterion, column, or name is missing, the wizard returns to the step that needs correction.
* If you close the window without saving, the application asks you to confirm.

## Points to note

* When editing a view for the first time, entering a **Tooltip** can clear the **Name** and **Counter name**. Check both fields before saving. This is a known issue.
* When creating a view, the window title shows “Edit MySearch - undefined” until you save the view.
* **Result list max size** limits the number of rows. An exclamation mark next to pagination means that the limit is reached.
