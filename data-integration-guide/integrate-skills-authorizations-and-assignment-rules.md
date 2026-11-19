---
description: Skills, priorities, authorizations, and preferences that determine which resources can perform an appointment.
---

# Integrate skills, authorizations, and assignment rules

Nomadia Field Service selects the resources able to perform an appointment based on three complementary mechanisms.

| Mechanism | Entities | Effect |
| --- | --- | --- |
| Skills | `Qualification`, `ResourceQualification`, `QUALIFICATIONS` field of the intervention type, the resource, and the appointment | A resource must hold the required skills. `ResourceQualification` lets you date a skill (`STARTDATE`, `ENDDATE`). |
| Priorities by intervention type | `TaskPriorities` (resource × type), `ResourcePriority` (resource × group), priorities by field worker type or job type | Value from 0 (impossible) to 100 for automatic and assisted planning; 0 or 1 for manual placement. |
| Authorizations | `Authorization`, `AUTHORIZATIONS` field of the customer and the resource | Authorizations to access a customer site. |
| Customer preferences | `REQUIREDRESOURCES`, `WISHEDRESOURCES`, `REFUSEDRESOURCES` fields of the customer, the requester, the project, and the appointment | Required, preferred, or refused resources. |
| Secondary sites and sectors | `ResourceWorksite`, `ResourceDutySector` | A resource can work at sites other than its main site, optionally over a period. |

<!-- REVIEW: the French text says "three mechanisms" but the table lists five rows; kept as is -->

| Field | Type | Required | Reference | Description | Example / default |
| --- | --- | --- | --- | --- | --- |
| `QUALIFICATIONID` | Identifier | Yes |  | Skill identifier | e.g. QUA_001 |
| `QUALIFICATIONNAME` | String | Yes |  | Skill name as it appears to the user |  |
| `ALWAYSMANDATORY` | Boolean | No |  | The skill is mandatory to be assigned to this appointment. The appointment cannot be forced onto a technician who does not have this skill (for dangerous assignments, for example) |  |
| `AREAID` | Ref. | No | Region | Region this authorization belongs to | e.g. REG_001 |
| `ACTIVE` | Boolean | No |  | Activation (1,"O",true) / deactivation of the site/customer (0,"N",false) | e.g. 1 · default 1 |

<!-- REVIEW: AREAID and ACTIVE descriptions in the French source refer to "authorization" and "site/customer" although the table describes a skill (Qualification); kept as is -->

| Field | Type | Required | Reference | Description | Example / default |
| --- | --- | --- | --- | --- | --- |
| `RESOURCEID` | Ref. | Yes | Human resource | Identifier of the resource that has this skill | e.g. TECH_001 |
| `QUALIFICATIONID` | Ref. | Yes | Skill | Skill identifier | e.g. QUA_001 |
| `STARTDATE` | Date (start) | No |  | Start date of the period during which the resource has this skill. If there is no date, the skill was already acquired. | e.g. DD/MM/YYYY |
| `ENDDATE` | Date (end) | No |  | End date of the period during which the resource has this skill. If there is no date, the skill is never lost. | e.g. DD/MM/YYYY |
| `ACTION` | String | No |  | Action verb to delete the record (`DELETE`) |  |

| Field | Type | Required | Reference | Description | Example / default |
| --- | --- | --- | --- | --- | --- |
| `PRIORITY_RESOURCEID` | Ref. | Yes | Human resource | Identifier of the resource whose assignment priorities must be updated for each intervention type group |  |
| `PRIORITY_TASK_TYPEID` | Ref. | Yes | Intervention type | Intervention type identifier |  |
| `PRIORITYMANUALOPTIM` | Boolean | Yes |  | Value to apply for manual placement of the appointment (0 or 1) | e.g. 1 |
| `PRIORITYREALTIMEOPTIM` | Integer | Yes |  | Value to apply for real-time assisted placement of the appointment (0 to 100. 0: cannot perform the intervention types of this group, 100: all the intervention types of this group are the main assignments of this resource) | e.g. 100 |
| `PRIORITYBATCHOPTIM` | Integer | Yes |  | Value to apply for automatic placement of the appointment (0 to 100. 0: cannot perform the intervention types of this group, 100: all the intervention types of this group are the main assignments of this resource) | e.g. 100 |
| `ACTION` | String | No |  | Action verb to delete the record (`DELETE`) |  |
