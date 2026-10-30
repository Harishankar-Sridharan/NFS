---
description: Define intervention groups and types.
---

# Configure interventions

An **intervention type** corresponds to the task completed during an appointment. Types are organized into **intervention groups**, which represent the company's main activities.

## Access the feature

**Navigation:** `Administration > Company data > Intervention > Intervention groups`

**Navigation:** `Administration > Company data > Intervention > Intervention type`

* Filter the group list by **Region**.
* Filter the type list by **Intervention group**. Select a group to display its types.

## Create an intervention group

1. Select **Create an intervention group**.
2. Enter **Name** and **Region**.
3. If needed, complete **Abbreviation**, **Color**, and **Description**.
4. Select **Save**.

![Intervention group record](/broken/files/MKI7pMIcrMHv9sjSTzD1)

## Create an intervention type

1. In the type list, select the relevant **Intervention group**.
2. Select **Create an intervention type**.
3. Enter **Name**, then, if needed, **Abbreviation**, **Intervention region**, and **Description**.
4. Enter the **Average intervention duration** in `HH:mm` format and, if needed, the **Delay** value in days.
5. Set the scheduling fields described below.
6. Select the required **Skills**.
7. Select **Save**.

![Intervention type record, Information tab](/broken/files/xrZ15n2LOBoqsGvoZ9GE)

| Field                           | Values                                                                                                                                                          |
| ------------------------------- | --------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| **Default number of resources** | 1 to 9                                                                                                                                                          |
| **Minimum number of resources** | 1 to 9                                                                                                                                                          |
| **Maximum number of resources** | 1 to 9                                                                                                                                                          |
| **Priority**                    | Undefined priority; to be scheduled (0), Non-priority (5), Desirable scheduling (25), To be scheduled (50), Priority scheduling (80), Required scheduling (100) |
| **Favorite days**               | One value per day, from **Mon** to **Sun**                                                                                                                      |
| **Required skills**             | List of skills to select                                                                                                                                        |

The **Resources** tab lists resources assigned to the type. It includes their **Region**, **Worksite**, and **Type**.

## Things to note

* The **Name** field is required.
* Available skills are created in [Manage skills and authorizations](manage-skills-and-authorizations.md).
* Permission to schedule each intervention type is configured by resource type, in the **Priorities** tab. See [Manage resource and job types](manage-resource-and-job-types.md).
