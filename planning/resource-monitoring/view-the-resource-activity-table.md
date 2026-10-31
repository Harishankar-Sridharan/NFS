---
description: Compare statistics for field workers displayed in the schedule in one table.
---

# View the resource activity table

The activity table brings together statistics for field workers displayed in the schedule: visit count and duration, kilometres, travel time, fill rate, route ratio, and quotas. Schedulers can compare several field workers’ workloads without opening each mini-card.

## Before you start

Two permissions control this feature. They are in the permissions collection under the **Planning** tab, **Calendar** section:

| Permission                                         | Description                                        |
| -------------------------------------------------- | -------------------------------------------------- |
| `CALLCENTER_PLANNING_ACTIVITY_BOARD`               | Allows displaying the activity table in schedules. |
| `CALLCENTER_PLANNING_ACTIVITY_BOARD_CONFIGURATION` | Allows configuring activity-table columns.         |

**Navigation:** `Administration > Users > Permissions collection`

1. Open the permissions collection for the relevant profile.
2. On the **Planning** tab, select the required permissions.
3. Select **Save**.

## Open the activity table

**Navigation:** `Planning`, schedule panel.

1. Display the required schedule. Choose the period, **Day** or **Week**, and level, such as **Team**, **Field worker**, or **Multi-resources**.
2. In the schedule toolbar, select the chart icon, **Activity table**. If the icon is hidden, select the arrow to the left of the icons to show hidden buttons.The **Activity table** window opens. Its header shows the displayed item, team or field worker, and the period.

## Read the table

### Team schedule

Each row represents a field worker displayed in the schedule. The **Total** row adds the team’s counts, durations, and distances.

### Field-worker schedule

Each row represents a day in the displayed period, shown in the **Date** column. This lets you track the field worker’s daily activity.

### Available columns

| Column               | Content                                        |
| -------------------- | ---------------------------------------------- |
| **Number of visits** | Number of appointments in the period.          |
| **Visit duration**   | Cumulative appointment duration.               |
| **Kilometres**       | Distance travelled.                            |
| **Travel duration**  | Cumulative travel time.                        |
| **Fill rate**        | (service time + travel time) / available time. |
| **Route ratio**      | travel time / (service time + travel time).    |
| **Vehicle**          | Vehicle assigned to the field worker.          |

Quantity quotas configured for the resource mini-card are added as extra columns, such as **Quantity quota 1**. To configure them, see [Display route indicators in the resource mini-card](display-route-indicators-in-the-resource-mini-card.md).

### Sort the table

Select a column header to sort rows by that column. An arrow identifies the sort column.

## Configure columns

This configuration requires the `CALLCENTER_PLANNING_ACTIVITY_BOARD_CONFIGURATION` permission.

1. In the **Activity table** window, select the **Column configuration** icon in the upper-right corner.
2. Clear columns to hide them, or select columns to display. A cleared column moves to the bottom of the list.
3. To change column order, drag a row by the handle on its left.
4. Select **Save**, or **Cancel** to close without changing anything.

The table immediately reflects your selection and order. The configuration is retained the next time you open it.

## Points to note

{% hint style="info" %}
The table shows statistics for the displayed schedule. Change the period, team, field worker, or display level, then reopen the table to view the corresponding statistics.
{% endhint %}

* The **Vehicle** column and quota columns stay empty for a field worker without an assigned vehicle.
