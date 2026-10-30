---
description: Configure unavailability types and exceptional location types.
---

# Configure unavailability and exceptional location types

**Unavailability types** classify resource absences and activities outside appointments: leave, meetings and training. They are available when [creating an unavailability](../unavailabilities/create-an-unavailability.md).

**Exceptional location types** describe a temporary workplace, including its hours and address.

## Access the feature

**Navigation:** `Administration > Company data > Unavailability type`

**Navigation:** `Administration > Company data > Exceptional location type`

The unavailability-type list displays **Name**, **Region**, **Group name** and **Description**. Filter it by **Region** and **Group name**.

## Configure an unavailability type

1. Select **Create an unavailability type**, or select a list row.
2. Enter **Name** and **Region**. Optionally enter **Abbreviation**, **Group name**, **Color** and **Description**.
3. Configure the options below.
4. Select **Save**.

![Unavailability-type record](/broken/files/2iOQJUkuQ3Tm7FGkeVYZ)

| Field                                                            | Values                  |
| ---------------------------------------------------------------- | ----------------------- |
| **Working time**                                                 | Yes / No                |
| **Multi-resource**                                               | Yes / No                |
| **Report conflicts with lunch breaks**                           | Checkbox                |
| **Reload step**                                                  | Checkbox                |
| **Validation required**                                          | Checkbox                |
| **Conflicts allowed before validation**                          | Checkbox                |
| **Default location**                                             | See the following table |
| **Default duration**, **Minimum duration**, **Maximum duration** | Numeric values          |
| **Duration unit**                                                | Minutes, Hours or Days  |

The **Default location** values are explained by tooltips:

| Value                               | Tooltip                                                                                                                            |
| ----------------------------------- | ---------------------------------------------------------------------------------------------------------------------------------- |
| **At home**                         | By default, the unavailability is located at the resource's home.                                                                  |
| **At the work site**                | By default, the unavailability is located at the resource's main work site.                                                        |
| **In the sector**                   | The unavailability is located in the resource's sector.                                                                            |
| **Not specified but required**      | No default location, but the unavailability must have a location.                                                                  |
| **No position required**            | No default location, and a location is not required.                                                                               |
| **At the route start/end location** | By default, the unavailability is located at the resource's route start, or at their arrival location when it ends in the evening. |

{% hint style="info" %}
According to the **Color** tooltip, colour applies correctly only to items with an external reference.
{% endhint %}

## Configure an exceptional location type

1. Select **Create an exceptional location type**.
2. Enter **Name** and **Region**. Optionally enter **Abbreviation** and **Description**.
3. Configure the hours:
   * **Allow overruns**;
   * **Work start time** and **Work end time**;
   * **Maximum morning overrun to justify an overnight stay**;
   * **Maximum evening overrun to justify an overnight stay**.
4. Complete the **Address** section. **Postcode** and **City** are required. Then select **Validate address**.
5. Select **Save**.

![Create an exceptional location type](/broken/files/adLc5Vy0pIHvzRNvGs5R)
