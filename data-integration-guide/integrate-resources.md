---
description: Human resources, specific actions, field worker types, and job types.
---

# Integrate resources

The human resource (`HumanResource`) represents both the scheduled field workers and the application users. The `OPTIMIZABLE` field indicates whether the resource goes into the field and must be taken into account by planning.

| Field | Type | Required | Reference | Description | Example / default |
| --- | --- | --- | --- | --- | --- |
| `RESOURCEID` | Identifier | Yes |  | Resource identifier | e.g. TECH_001 |
| `RESOURCELASTNAME` | String | Yes |  | Resource last name | e.g. MARTIN |
| `RESOURCEFIRSTNAME` | String | No |  | Resource first name | e.g. Pierre |
| `AREAID` | Ref. | No | Region | Region this resource belongs to | e.g. REG_001 |
| `WORKSITEID` | Ref. | No | Work site | Identifier of the main branch this resource is attached to | e.g. WKS_001 |
| `TEAMID` | Ref. | No | Team | Identifier of the team this resource is attached to |  |
| `OPTIMIZABLE` | Boolean | No |  | Defines whether the resource is optimizable / goes into the field | e.g. 1 (optimizable), 0 (not optimizable) |
| `MANPOWER` | Integer | No |  | Indicates whether this resource is considered a single person or a group of several resources (subcontractors whose individual schedules are not managed) (min 1, max 10) | e.g. 1 |
| `QUALIFICATIONS` | List of refs | No | Skill | List of skills this resource permanently holds | e.g. QUA_001;QUA_002 |
| `ADDRESS` | Address | No |  | Starting postal address of the resource (street + street number) | e.g. 66 avenue du Maine |
| `CODEZONE` | Address | No |  | Postal code of the resource's starting address | e.g. 75014 |
| `CITY` | Address | No |  | City of the resource's starting address | e.g. PARIS |
| `WORKEMAIL` | String | No |  | Resource email (work) |  |
| `ACTION` | String | No |  | Action verb that triggers a specific import behavior (RETRIEVE_JOB_PRIORITIES_LIMITS: retrieve all the priorities and limits defined on a resource type and apply them to the current resource) |  |

The entity has more than 300 fields: hours for each day of the week (`DAY1…` to `DAY7…`, 1 = Monday), working-time and travel-time limits, starting and return locations, and custom fields. The complete list is in the [exchange model reference](exchange-model-reference.md).

## Specific actions

The `ACTION` column of the resource accepts values that copy the settings of its job type onto the resource: `RETRIEVE_JOB_WORKWEEK`, `RETRIEVE_JOB_LIMITS`, `RETRIEVE_JOB_PRIORITIES`, `RETRIEVE_JOB_PRIORITIES_LIMITS`.

## Field worker types and job types

Depending on the modeling option of the instance (`showFunctionsInJobtypes` or `showJobtypesInFunctions` in the `COMPANY_MODELING_OPTION` configuration), the model offers either the entities `ResourceType`, `ResourcetypePriority`, and `ResourcetypeGroupPriority`, or the entities `ResourceJobType`, `JobTypePriority`, `JobTypeGroupPriority`, `ResourceFunction`, `FunctionPriority`, and `FunctionGroupPriority`. Check the list of entities of the instance in `Administration > CSV files > CSV import/export model` or with the `ListEntities` operation.
<!-- REVIEW: English UI path "CSV files > CSV import/export model" translated from the French menu names; verify against the English application -->
