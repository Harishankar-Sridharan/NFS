---
description: Discover the Administration module and shared data management.
---

# Administration overview

The Administration module manages company data: human resources, teams, worksites, intervention types, skills, calendars, and more. It also provides access to optimization, mobility, users and permissions, customization, exchange files, and tools.

## Access the module

**Navigation:** `Application launcher > Administration`

The **About Nomadia Field Service** page opens. It shows the application name, version, and edition, along with license information.

## Module menu

The left menu is organized into groups.

| Group                         | Entries                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                | Guide pages                                                                                                                      |
| ----------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ | -------------------------------------------------------------------------------------------------------------------------------- |
| **Company data**              | Human resource, Resource type, Job type, Subcontractor, Equipment, Product family (Product family, Product), Team, Domain, Region, Worksite, Sector, On-call sector, Unavailability type, Exceptional location type, On-call duties (Day template, Week template), Skill, Authorization, Intervention (Intervention group, Intervention type), Objectives, Activity monitoring (Completion status, Follow-up action), Typology, Calendars (Public holidays, Day template, Week template, Sales period) | See the list below                                                                                                               |
| **Optimization**              | Optimization parameters, Optimization scheduling, Activate/Deactivate an area, Import/export an optimization                                                                                                                                                                                                                                                                                                                                                                                           | [Configure optimization](configure-optimization.md)                                                                              |
| **Mobility**                  | Vehicles, Tracking equipment, Assignments, Tracking utilities, Settings                                                                                                                                                                                                                                                                                                                                                                                                                                | [Manage mobility](manage-mobility.md)                                                                                            |
| **Users**                     | Profile, Permission collection, Access rights, Alert subscription                                                                                                                                                                                                                                                                                                                                                                                                                                      | [Manage profiles and permissions](manage-profiles-and-permissions.md)                                                            |
| **Customization**             | Application configuration, Labels, Themes, Colors (Reference colors, Application colors)                                                                                                                                                                                                                                                                                                                                                                                                               | [Customize the application](customize-the-application.md)                                                                        |
| **CSV files**                 | Import a CSV file, Export a CSV file, Semi-automatic import, Global CSV import/export, CSV import/export template, Traffic listeners, Predefined export links                                                                                                                                                                                                                                                                                                                                          | [Imports and exports](../imports-and-exports/imports-and-exports-overview.md), [Manage exchange files](manage-exchange-files.md) |
| **Specific files**            | Export TomTom POIs, Export Masternaut POIs, Export Garmin POIs, Export POIs to KML, Import a GTM simulation                                                                                                                                                                                                                                                                                                                                                                                            | [Manage exchange files](manage-exchange-files.md)                                                                                |
| **XML files**                 | Optimization file, Traffic file, Traffic examples, Logs                                                                                                                                                                                                                                                                                                                                                                                                                                                | [Manage exchange files](manage-exchange-files.md)                                                                                |
| **Tools**                     | Advanced tools, Recalculate distance, Check server status, Logs, JVM thread dump, Mapping services                                                                                                                                                                                                                                                                                                                                                                                                     | [Use administration tools](use-administration-tools.md)                                                                          |
| **Nomadia Field Service API** | Documentation, CSV import/export template                                                                                                                                                                                                                                                                                                                                                                                                                                                              | [Use administration tools](use-administration-tools.md)                                                                          |

{% hint style="info" %}
The actions allowed in this module depend on the user's access rights, for example `ADMIN_CREATE_AREA` to create an area. See [Manage profiles and permissions](manage-profiles-and-permissions.md).
{% endhint %}

## Manage data: shared principles

Most **Company data** entries work the same way.

### Search and list

1. Select the entry from the left menu.
2. If needed, enter the available filters, such as **Region**.
3. Depending on the entry, the list displays directly or after selecting **Search**.

The list displays existing items, or the **No results found.** message. Set the number of rows per page above the list when it has several pages.

### Create an item

1. Select the **Create…** button in the upper right, for example **Create a team**.
2. Complete the fields. Required fields are marked with an asterisk.
3. Select **Save**. For some entries, creation uses several pages: use **Next page** and **Previous page**, then **Save**.

After saving, the **Record saved** notification displays and additional tabs may appear.

### Open and edit an item

1. In the list, select the item's row.
2. The item record opens with its tabs and the **Save** button.

The **Return to list** button returns to the item list. The **Deactivate** and **Duplicate** buttons are available in a saved item record.

For a complete example, see [Manage teams](manage-teams.md).

## In this section

### Company data

* [Manage human resources](manage-human-resources.md)
* [Manage resource and job types](manage-resource-and-job-types.md)
* [Manage subcontractors, equipment, and products](manage-subcontractors-equipment-and-products.md)
* [Manage teams](manage-teams.md)
* [Manage geographic organization](manage-geographic-organization.md)
* [Configure unavailability and exceptional location types](configure-unavailability-and-exceptional-location-types.md)
* [Configure on-call duties](configure-on-call-duties.md)
* [Manage skills and authorizations](manage-skills-and-authorizations.md)
* [Configure interventions](configure-interventions.md)
* [Manage objectives, activity monitoring, and typologies](manage-objectives-activity-monitoring-and-typologies.md)
* [Manage calendars](manage-calendars.md)

### Application configuration

* [Configure optimization](configure-optimization.md)
* [Manage mobility](manage-mobility.md)
* [Manage profiles and permissions](manage-profiles-and-permissions.md)
* [Customize the application](customize-the-application.md)
* [Manage exchange files](manage-exchange-files.md)
* [Use administration tools](use-administration-tools.md)
