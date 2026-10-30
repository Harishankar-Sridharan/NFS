---
description: Create on-call day and week templates.
---

# Configure on-call duties

An on-call duty reserves time slots for certain activities, such as a morning dedicated to emergencies. Configure it at two levels:

* the **on-call day template** defines a time slot;
* the **on-call week template** assigns a day template to each day of the week.

## Access the feature

**Navigation:** `Administration > Company data > On-call duties > Day template`

**Navigation:** `Administration > Company data > On-call duties > Week template`

Filter both lists by **Region** and **Work site**.

## Create an on-call day template

1. Select **Create an on-call day template**.
2. Enter **Name** and **Region**.
3. Optionally complete **Abbreviation**, **Group name**, **Color**, **Work site**, **Resource type** and **Description**.
4. Select the **Level**.
5. Define the slot using **Start time** and **End time**.
6. If needed, select **Start of day**, **Middle of day**, **End of day**, or **Apply custom hours**.
7. Select **Save**.

![Create an on-call day template](/broken/files/GEGUpimoMExdFR7O5QuC)

## Create an on-call week template

1. Select **Create an on-call week template**.
2. Enter **Name** and **Region**. Optionally complete **Abbreviation**, **Group name**, **Color**, **Work site** and **Description**.
3. Select the **Start day**: `Any day` or a specific day.
4. Select the **Transfer time**: **Undefined**, **At the start of the day**, **After lunch** or **Until the end of the evening**.
5. If needed, enter the **Transfer schedule**.
6. In the table, select a day template for each day. The table displays **Level** and the **Start of day**, **Middle of day** and **End of day** slots.
7. Select **Save**.

![Create an on-call week template](/broken/files/4FiKEyXNUfEMshJmbrGD)

{% hint style="info" %}
The **Transfer schedule** tooltip states that it specifies an exact time. It is ignored when set to `00:00`, because selecting a **Transfer time** is usually sufficient.
{% endhint %}

## Things to note

* Create day templates before creating a week template. A week uses existing day templates.
* **Name** and **Region** are required.
