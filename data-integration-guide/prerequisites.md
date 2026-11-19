---
description: Data to prepare, external identifiers, and access required before an integration project.
---

# Prerequisites

## Data to prepare

| Data | Minimum requirement | Nomadia Field Service entities |
| --- | --- | --- |
| Organization | At least one region; one work site (branch) to which resources and customers are attached | `Area`, `Worksite` |
| Activity reference data | Intervention groups and types with a default duration | `TaskTypeGroup`, `TaskType` |
| Resources | Unique identifier and name for each resource; start and return address for optimized resources | `HumanResource` |
| Customers and sites | Unique identifier and name; geocodable address or coordinates | `Customer` |
| Appointments | Unique identifier, customer, intervention type, completion period | `Appointment` |
| Calendars | Day and week templates, public holidays | `WorkdayType`, `WorkWeekType`, `PublicHoliday` |

## External identifiers

Each entity is identified by an external identifier: the value of the identifier field (for example `CUSTOMERID`) supplied by the customer information system. Nomadia Field Service uses it to find an existing object and to resolve references between entities. This identifier must be unique and stable over time.

Never reuse an identifier for another object. An import that finds an existing identifier updates the existing object instead of creating a new one.

## Access and environment

* A Nomadia Field Service user account authorized to access the administration module for manual imports and exports.
* For web services: the instance URL, the API protection key if it is enabled, and a user account dedicated to the integration (see [Authentication and security](authentication-and-security.md)).
* A test environment loaded with data before any data migration to production.
