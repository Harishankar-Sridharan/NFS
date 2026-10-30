---
description: Create the skills and authorizations required to perform interventions.
---

# Manage skills and authorizations

**Skills** describe resource capabilities. **Authorizations** describe their permissions, such as a key or access badge. They are assigned in each human resource record, and intervention types require skills.

## Access the feature

**Navigation:** `Administration > Company data > Skill`

**Navigation:** `Administration > Company data > Authorization`

Each list displays **Name**, **Region**, and **Description**. The **Region** filter narrows the list.

## Create a skill

1. Select **Create a skill**.
2. Enter **Name** and **Region**, then, if needed, **Abbreviation** and **Description**.
3. Set the options:
   * **Required — In all cases, even if forced**;
   * **In a team**: **at least one resource must have it** or **all must have it**.
4. Select **Save**.

![Skill record, Information tab](/broken/files/l9kBzqWnJ44Vctgvgeu7)

Tooltips explain the options:

| Option                                 | Tooltip                                                                                                                                     |
| -------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------- |
| **In all cases, even if forced**       | When selected, a task requiring this skill cannot be assigned to someone who lacks it, even by forcing the assignment with extended rights. |
| **at least one resource must have it** | For appointments with multiple resources, only one resource needs the skill.                                                                |
| **all must have it**                   | For appointments with multiple resources, every resource needs the skill.                                                                   |

## View a skill's resources

The **Resources** tab in the record lists resources with the skill. It includes their **Type**, **Region**, **Worksite**, and period (**Start date**, **End date**).

![Skill Resources tab](/broken/files/yBoqkIoPk9aPmiGw9alK)

## Create an authorization

1. Select **Create an authorization**.
2. Enter **Name** and **Region**, then, if needed, **Abbreviation** and **Description**.
3. If needed, select **Required — In all cases, even if forced**. Its tooltip matches the skill tooltip.
4. Select **Save**.

## Things to note

* To assign a skill to a resource, use the **Skills** tab in its record. See [Manage human resources](manage-human-resources.md).
* To require a skill for an intervention type, see [Configure interventions](configure-interventions.md).
