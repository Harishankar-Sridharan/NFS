---
description: Loading order of reference data and data in Nomadia Field Service.
---

# Reference data and integration order

An entity can only reference an object that already exists in Nomadia Field Service. Reference data must therefore be loaded before the entities that use it.

![Recommended import order in five steps: 1. Organization (region, site type, work site, sector type, sector, team), 2. Reference data (public holidays, day and week templates, intervention groups and types, skills, unavailability types, completion statuses), 3. Resources (human resource, vehicle, skills, priorities, secondary work sites, unavailabilities, specific calendars), 4. Customers (requester, customer / site, contact, project), 5. Activity (appointment, appointment detail, completion slot, parcel)](../.gitbook/assets/en_integration_import_order.png)

## Detailed order

Nomadia Field Service ranks entities by dependency level. The global export applies this ranking to number the files in the archive. It starts with a resources file reduced to RESOURCEID and RESOURCELASTNAME, which lets reference data point to a resource (team leader, region manager) before the full import of resources. The complete order (93 steps) is in the [Detailed integration order](detailed-integration-order.md) page.

For an initial data load, import the files in the order given in the [Detailed integration order](detailed-integration-order.md) page, and check the report of each file before moving on to the next one.

## In this section

| Page | Content |
| --- | --- |
| [Integrate the organization and activity](integrate-organization-and-activity.md) | Regions, work sites, teams, intervention groups and types |
| [Integrate resources](integrate-resources.md) | Human resources, specific actions, field-worker and job types |
| [Integrate calendars, schedules, and unavailabilities](integrate-calendars-schedules-and-unavailabilities.md) | Day and week templates, public holidays, unavailabilities |
| [Integrate skills, authorizations, and assignment rules](integrate-skills-authorizations-and-assignment-rules.md) | Skills, priorities, authorizations, preferences |
| [Integrate customers and sites](integrate-customers-and-sites.md) | Customers, contacts, projects, geolocation |
| [Integrate appointments](integrate-appointments.md) | Fields, statuses and lifecycle, actions, details and completions |

Previous: [Concepts and exchange model](concepts-and-exchange-model.md)

Next: [Integrate the organization and activity](integrate-organization-and-activity.md)
