---
description: Regions, work sites, teams, intervention groups and types.
---

# Integrate the organization and activity

## Organization

The region (Area) groups a set of data to be scheduled together; it corresponds to a territory or an activity. The work site (Worksite), also called an agency, links resources, customers, and appointments. The sector (Sector) divides a site into geographic zones. The team (Team) groups resources hierarchically.

**Region (Area)**

| Field | Type | Req. | Reference | Description | Example / default |
| --- | --- | --- | --- | --- | --- |
| AREAID | ID | Yes |  | Region identifier (geographic entity or activity/trade) | e.g. REG\_001 or ACTIV\_AUTO or ZONE\_SO or 1 |
| AREANAME | String | Yes |  | Name of the region as it appears to the user | e.g. SUD-OUEST or AUTOMOBILE |
| DESCRIPTION | String | No |  | Comment describing this region | e.g. Zone Sud-Ouest or Activité automobile |
| ACTIVE | Boolean | No |  | Activation (1, "O", true) / Deactivation of the site/customer (0, "N", false) | e.g. 1 · default 1 |

**Work site (Worksite)**

| Field | Type | Req. | Reference | Description | Example / default |
| --- | --- | --- | --- | --- | --- |
| WORKSITEID | ID | Yes |  | Agency identifier | e.g. WKS\_001 |
| WORKSITENAME | String | Yes |  | Name of the agency as it appears to the user | e.g. Agence de PARIS |
| AREAID | Ref. | No | Region | Region the agency belongs to | e.g. REG\_001 · default: the default region (id=1) is used if none is given |
| PARENTWORKSITEID | Ref. | No | Work site | Parent agency | e.g. PWS\_001 |
| ADDRESS | Address | No |  | Postal address of the agency (street + street number) | e.g. 66 avenue du Maine |
| CODEZONE | Address | No |  | Postcode of the agency address | e.g. 75014 |
| CITY | Address | No |  | City of the agency address | e.g. PARIS |
| ACTIVE | Boolean | No |  | Activation (1, "O", true) / Deactivation of the site/customer (0, "N", false) | e.g. 1 · default 1 |

**Team (Team)**

| Field | Type | Req. | Reference | Description | Example / default |
| --- | --- | --- | --- | --- | --- |
| TEAMID | ID | Yes |  | Team identifier | e.g. EQU\_002 |
| TEAMNAME | String | Yes |  | Name of the team as it appears to the user |  |
| AREAID | Ref. | No | Region | Region the team belongs to | e.g. REG\_001 |
| LEADERID | Ref. | No | Human resource | Team leader identifier | e.g. TECH\_001 |
| PARENTID | Ref. | No | Team | Parent team identifier | e.g. EQU\_001 |
| ACTIVE | Boolean | No |  | Activation (1, "O", true) / Deactivation of the site/customer (0, "N", false) | e.g. 1 · default 1 |

Create at least one team, even if the resources are not organized into teams: several planning views filter by team.

## Activity: intervention groups and types

Nomadia Field Service manages two levels: the intervention group (TaskTypeGroup) and the intervention type (TaskType). If the customer's reference data has more levels, concatenate the lower levels into the intervention type (for example "Entretien – Chaudière gaz").

**Intervention group (TaskTypeGroup)**

| Field | Type | Req. | Reference | Description | Example / default |
| --- | --- | --- | --- | --- | --- |
| TASKTYPEGROUPID | ID | Yes |  | Identifier of the intervention type group | e.g. TTG\_001 |
| TASKTYPEGROUPNAME | String | Yes |  | Name of the intervention type group as it appears to the user | e.g. Maintenance |
| AREAID | Ref. | No | Region | Region the intervention type group belongs to. This group is visible in all regions if this field is empty. | e.g. REG\_001 |
| ACTIVE | Boolean | No |  | Activation (1, "O", true) / Deactivation of the site/customer (0, "N", false) | e.g. 1 · default 1 |

**Intervention type (TaskType)**

| Field | Type | Req. | Reference | Description | Example / default |
| --- | --- | --- | --- | --- | --- |
| TASKTYPEID | ID | Yes |  | Intervention type identifier | e.g. TT\_001 |
| TASKTYPENAME | String | Yes |  | Name of the intervention type as it appears to the user |  |
| TASKTYPEGROUPID | Ref. | Yes | Intervention group | Group the intervention type belongs to | e.g. TTG\_001 |
| DURATION | Duration | Yes |  | Default duration for an appointment of this intervention type (in minutes) | e.g. 90 |
| QUALIFICATIONS | Ref. list | No |  | List of the skills required to perform this intervention type | e.g. QUA\_001;QUA\_002 |
| DEFAULT\_MANPOWER | Integer | No |  | Default number of resources required to perform this intervention type | e.g. 1 · default 1 |
| MIN\_MANPOWER | Integer | No |  | Minimum number of resources required to perform this intervention type (min 1) | e.g. 1 · default 1 |
| MAX\_MANPOWER | Integer | No |  | Maximum number of resources required to perform this intervention type (max 10) | e.g. 1 · default 1 |
| ACTIVE | Boolean | No |  | Activation (1, "O", true) / Deactivation of the site/customer (0, "N", false) | e.g. 1 · default 1 |

The duration (DURATION) is required for an intervention type. It is expressed in minutes.

<!-- REVIEW: the ACTIVE description says "site/client" in every table (including region, team, and intervention tables); kept as in the source, probably a copy-paste. -->
<!-- REVIEW: the source has no titles above the tables; the bold labels (Region, Work site, Team, Intervention group, Intervention type) were added only to tell the tables apart. -->

Previous: [Reference data and integration order](reference-data-and-integration-order.md)

Next: [Integrate resources](integrate-resources.md)
