---
description: >-
  Show a field worker’s route, quota, and vehicle-capacity indicators in the
  resource mini-card.
---

# Display route indicators in the resource mini-card

The resource mini-card can show additional workload indicators for the period displayed in the schedule: available time, time reserve, route ratios, quantities to deliver, and vehicle capacity. This lets schedulers quickly assess whether a field worker’s route is balanced.

## Before you start

* Configure these settings in Administration with an account allowed to edit **Application configuration**.
* The settings apply to every application user.
* Quantity and quota indicators require appointments with quantities and a field worker with a vehicle that has a maximum quantity.

To open a field worker’s mini-card, see [View the schedule](../view-the-schedule.md).

## Access the settings

**Navigation:** `Administration > Customization > Application configuration`

1. Enter `hrInfo` in the **Filter** field at the top of the tree.
2. Expand `Display > Human resource planning information sheet`.

Four settings control these indicators:

| Setting                         | Purpose                                                      |
| ------------------------------- | ------------------------------------------------------------ |
| **hrInfo**                      | Shows or hides each mini-card tab.                           |
| **hrInfo.userfield.stats**      | Adds a quantity sum to the **ROUTES** tab.                   |
| **hrInfo.vehicleQuantityQuota** | Adds a quantity quota to the **QUOTA** tab.                  |
| **hrInfo.vehicle**              | Selects the maximum quantities shown in the **VEHICLE** tab. |

## Display the Routes, Quota, and Vehicle tabs

1. Select **hrInfo**.
2. Enable these switches:
   * **showRoutes** for the **ROUTES** tab;
   * **showQuota** for the **QUOTA** tab, disabled by default;
   * **showVehicle** for the **VEHICLE** tab.
3. Select **Save**.

![hrInfo setting with mini-card tab display switches](/broken/files/3p3DJ3DYSSD7pzEjZnhB)

## Read the Routes tab

The **ROUTES** tab summarizes field-worker activity for the period displayed in the schedule:

* **Number of appointments**;
* **Total kilometres** and **total travel time**, including daily maximum, minimum, and average;
* **Average speed**, in km/h;
* **Total appointment duration**, including the daily breakdown;
* **Average route per appointment**;
* **Available time**;
* **Time reserve**.

![Routes mini-card tab with available time and time reserve](/broken/files/Mxcmc1P2A7EwyNS33uUJ)

## Add a quantity sum to the Routes tab

You can show the sum of a quantity from scheduled appointments in the **ROUTES** tab. For example, show the number of items to deliver.

1. Select **hrInfo.userfield.stats**.
2. Complete a statistics block, such as `sumOfQuantity1`, or add one with the **+** icon:
   * **summaryLabel**: label shown in the tab;
   * **userField**: field type to add, such as `QUANTITY`;
   * **userFieldIndex**: field number, such as `1` for quantity 1;
   * **userFieldFilter** and **userFieldFilterValues**, optional: appointment field and a semicolon-separated list of values. They retain only selected appointments;
   * **summarizeOperator**: operation to apply. The default is `SUM`;
   * **enabled**: enable the switch to show the statistic.
3. Select **Save**.

![hrInfo.userfield.stats setting with a sum block for quantity 1](/broken/files/TUMPqaV1Jrf326b7fDRp)

A row with your selected label is added at the bottom of the **ROUTES** tab. It shows the sum for the period.

## Read the Quota tab

The **QUOTA** tab shows ratios calculated for the period:

* **Route ratio**: travel time / (service time + travel time);
* **Fill rate**: (service time + travel time) / available time;
* One or more quantity quotas, when configured.

## Add a quantity quota to the Quota tab

A quantity quota compares the quantity of scheduled appointments with the field worker’s vehicle maximum capacity, as a percentage.

1. Select **hrInfo.vehicleQuantityQuota**.
2. Complete a quota block, such as `quantityQuota1`, or add one with the **+** icon:
   * **enable**: enable the switch to show this quota;
   * **quotaLabel**: label shown in the tab;
   * **quantityField** and **quantityFieldIndex**: appointment quantity to use, such as `QUANTITY` and `1`;
   * **vehicleMaxQuantityField**: vehicle maximum quantity to use, such as `maxQuantity1`.
3. Select **Save**.

![hrInfo.vehicleQuantityQuota setting with a quota block for quantity 1](/broken/files/1MYv5QziwkgHaVMH2Ou2)

**Example:** A field worker has two appointments, each with quantity 1 equal to `1`. Their vehicle has maximum quantity 1 equal to `3`. The displayed quota is `66.67%`.

## Display maximum quantities in the Vehicle tab

The **VEHICLE** tab displays information about the vehicle assigned to the field worker, including maximum quantities. If no vehicle is assigned, the tab shows “No vehicle assigned.”

1. Select **hrInfo.vehicle**.
2. Enable **showMaxQuantity1** through **showMaxQuantity5** for the maximum quantities to show. Only the first two are displayed by default.
3. Select **Save**.

![hrInfo.vehicle setting with maximum-quantity switches](/broken/files/TKPH7Jsdhx8dD0t7Aj9D)

## Points to note

{% hint style="info" %}
Indicators are calculated for the period displayed in the schedule: day or week.
{% endhint %}
