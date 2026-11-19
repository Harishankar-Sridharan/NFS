---
description: Day and week templates, public holidays, unavailabilities, and other calendars.
---

# Integrate calendars, schedules, and unavailabilities

## Day and week templates

Standard schedules are described by workday types (`WorkdayType`: start and end times, lunch break) assembled into work week types (`WorkWeekType`). A resource follows a standard week; dated exceptions are imported with `ResourceWorkWeek` (standard week over a period) and `ResourceWorkday` (specific day).

| Field | Type | Required | Reference | Description | Example / default |
| --- | --- | --- | --- | --- | --- |
| `WORKDAYTYPEID` | Identifier | Yes |  | Day template identifier in the company information system | e.g. MON_MODELE_DE_LUNDI |
| `WORKDAYTYPENAME` | String | Yes |  | Day template identifier in the company information system |  |
| `DAYBEGINTIME` | Time | No |  | Start time of the day (HH:MM) | e.g. 08:00 |
| `DAYENDTIME` | Time | No |  | End time of the day (HH:MM) | e.g. 18:00 |
| `DAYBEGINLUNCHPERIOD` | Time | No |  | Start time of the floating lunch break (HH:MM) | e.g. 12:00 |
| `DAYENDLUNCHPERIOD` | Time | No |  | End time of the floating lunch break (HH:MM) | e.g. 14:00 |
| `DAYLUNCHDURATION` | Time | No |  | Duration of the lunch break (in minutes) | e.g. 60 |
| `DAYISWORKED` | Boolean | No |  | Defines whether this day is considered worked (1: yes, 0: no) | e.g. 1 |

<!-- REVIEW: WORKDAYTYPENAME description is identical to WORKDAYTYPEID in the French source (probably should be the day template name) -->

| Field | Type | Required | Reference | Description | Example / default |
| --- | --- | --- | --- | --- | --- |
| `WORKWEEKTYPEID` | Identifier | Yes |  | Work week type identifier | e.g. SPECIAL_WEEK01 |
| `WORKWEEKTYPENAME` | String | Yes |  | Work week type name |  |
| `WORKDAYTYPES` | List of refs | Yes | Workday type | External identifier of the day types | e.g. MY_MONDAY_TEMPLATE,MY_TUESDAY_TEMPLATE,etc. |
| `STARTDAY` | Integer | No |  | Start day of the week | e.g. 0=ANY DAY,1=MONDAY,2=TUESDAY,3=WEDNESDAY,4=THURSDAY,5=FRIDAY,6=SATURDAY,7=SUNDAY · default 0 |

The `STDWORKDAY` day template is the default template of the instance (according to the exchange model description). Change it with care.

## Public holidays

| Field | Type | Required | Reference | Description | Example / default |
| --- | --- | --- | --- | --- | --- |
| `HOLIDAYID` | Identifier | No |  | Public holiday identifier in the company information system | e.g. FERIE_01012012 |
| `HOLIDAYDATE` | Date | Yes |  | Date of the public holiday | e.g. 01/01/2012 |
| `HOLIDAYNAME` | String | Yes |  | Name of the public holiday as it appears to the user | e.g. Jour de l'an 2012 |
| `AREAID` | Ref. | No | Region | Region this public holiday belongs to | e.g. REG_001 |
| `WORKSITEID` | Ref. | No | Work site | Work site this day belongs to | e.g. WS001 |
| `ACTION` | String | No |  | Action verb to delete the record (`DELETE`) |  |

## Unavailabilities

An unavailability (`Unavailability`) blocks a resource over a period (training, leave, meeting). Its type (`UnavailabilityType`) indicates, among other things, whether the time is considered worked (`ISWORKTIME`). Unavailabilities can be periodic (`PERIODICITY_*`) and located (address or coordinates).

| Field | Type | Required | Reference | Description | Example / default |
| --- | --- | --- | --- | --- | --- |
| `UNAVAILABILITYTYPEID` | Identifier | Yes |  | Unavailability type identifier |  |
| `UNAVAILABILITYTYPENAME` | String | Yes |  | Name of this unavailability type as it appears to the user |  |
| `ISWORKTIME` | Boolean | No |  | Is this unavailability type considered worked? (e.g. meeting) | e.g. 0 |
| `DEFAULT_DURATION` | Duration | No |  | Default duration of the unavailability (in minutes) |  |
| `ISREQUIREDVALIDATION` | Boolean | No |  | Does this unavailability require validation? | e.g. 0 · default 0 |

| Field | Type | Required | Reference | Description | Example / default |
| --- | --- | --- | --- | --- | --- |
| `UNAVAILABILITYID` | Identifier | Yes |  | Unavailability identifier |  |
| `RESOURCEID` | Ref. | Yes | Human resource | Name of the field worker who is not available | e.g. TECH_001 |
| `UNAVAILABILITY_TYPEID` | Ref. | Yes | Unavailability type | Unavailability type |  |
| `DATEBEGIN` | Date (start) | No |  | Start date of the unavailability (DD/MM/YYYY) | e.g. 25/12/2012 |
| `TIMEBEGIN` | Time | No |  | Start time of the unavailability (HH:MM) | e.g. 00:00 |
| `DATEEND` | Date (end) | No |  | End date of the unavailability (DD/MM/YYYY) | e.g. 25/12/2012 |
| `TIMEEND` | Time | No |  | End time of the unavailability (HH:MM) | e.g. 23:59 |
| `DATETIMEBEGIN` | Date-time | No |  | Start date and time of the unavailability (DD/MM/YYYY HH:MM) | e.g. 25/12/2012 08:00 |
| `DATETIMEEND` | Date-time | No |  | End date and time of the unavailability (DD/MM/YYYY HH:MM) | e.g. 25/12/2012 20:00 |
| `STATUS` | Integer | No |  | Status | e.g. { 0=UNKNOWN ,10 = CANCELED,21 = REQUESTED, 29=ACCEPTED; |
| `ACTION` | String | No |  | Action verb to delete the record (`DELETE`) |  |

<!-- REVIEW: STATUS example in the French source is malformed ("{ 0=INCONNUE ,10 = ANNULÉE,21 = DEMANDÉE, 29=ACCEPTÉE;" with no closing brace); status labels translated, structure kept as is -->

## Other calendars

* Exceptional locations (`ExceptLocation`): period during which a resource starts from another place or at another time.
* Locked days (`AgendaControlledDate`): days in a resource's agenda that are protected from changes.
* On-call duties (`DutyType`, `DutyWeekType`, `Duty`, `DutyWeek`, `DutyReplacement`) and on-call sectors (`DutySectorType`, `DutySector`).
* Business locations (`BusinessLocation`, hotels) and depots (`DepotBusinessLocation`) with their closure periods.
