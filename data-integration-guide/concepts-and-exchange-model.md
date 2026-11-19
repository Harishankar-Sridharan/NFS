---
description: Exchange model, main entities, data types, import and export columns, synonyms.
---

# Concepts and exchange model

## The exchange model

The exchange model describes each entity and each of its fields by its name, type, whether it is required, any restriction to import or export, and the entity it references. You can view the model:

* in the application, from `Administration > CSV files > CSV import/export model`;
* through the web service, with the ListEntities and GetExchangeModel operations (see [Integration APIs and web services](integration-apis-and-web-services.md));
* in the [exchange model reference](exchange-model-reference.md).

## Main entities and relationships

![Main entities of the exchange model and their reference fields: Region, Work site, Sector, Team, Human resource, Skill, Resource skills, Appointment priority, Intervention group, Intervention type, Unavailability, Unavailability type, Requester, Customer / site, Contact, Project, Appointment, Appointment detail, and Completion slot, linked by their technical identifiers](../.gitbook/assets/en_integration_entities.png)

## Data types

| Type (kind) | Meaning | Format | Example |
| --- | --- | --- | --- |
| ID | External identifier of the entity | Text | CLI\_1001 |
| ID\_FOREIGN | External identifier of a referenced entity (must exist) | Text | AG\_PARIS\_N |
| IDS\_LIST | List of external identifiers separated by the list separator | Text | TT\_ENTRETIEN,TT\_DEPANNAGE |
| STRING / TEXT | Character string / free text | Text | Boulangerie des Lilas |
| BOOLEAN | Logical value | See [Import data](import-data.md) | 1 |
| INTEGER / REAL | Whole number / decimal number | Number | 60 / 12.5 |
| DATE, PERIOD\_STARTDATE, PERIOD\_ENDDATE | Date; the last two set the bounds of a period | Import date format | 16/11/2026 |
| DATETIME | Date and time | date + space + time | 16/11/2026 08:30 |
| TIME | Time of day | HH:mm or minutes | 08:30 |
| DURATION | Duration | Minutes (or HH:mm) | 60 |
| LOCATION\_\* | Address elements: ADDRESS, CITY, CODEZONE, COUNTRY, ADDRESSINFO, BUILDING, DISTRICT, INITIALINPUT | Text | 12 rue des Lilas |
| LOCATION\_X / \_Y | Map coordinates in the map projection | Number | — |
| LOCATION\_XGEO / \_YGEO | Longitude / latitude in decimal degrees (WGS 84) | Number | 2.3912 / 48.8786 |
| LOCATION\_XYNMEA | Position in GPS NMEA format | Text | — |
| GEOCODING\_TYPE / \_SCORE | Geocoding quality (filled in by Nomadia Field Service) | Number | 5 / 1.0 |
| CSVSET | Set of linked records (details) contained in a cell | Structured text | — |

## Import and export columns

In the reference tables, the I/E column shows whether a field is accepted on import (I), produced on export (E), or both (I/E). A field marked E is ignored on import. Six entities can only be exported: agenda events (AgendaEvent), application events (ApplicationEvent), daily and weekly agenda summaries (AgendaDaySummary, AgendaWeekSummary), log (Journal), and report results (ReportResult).

## Synonyms

Some entities accept former column names, called synonyms, to stay compatible with existing files. For example, the Customer entity accepts CUSTOMERTYPE for CUSTOMERTYPEID. The synonyms are listed in the [exchange model reference](exchange-model-reference.md); use the current name whenever possible.

Previous: [Authentication and security](authentication-and-security.md)

Next: [Reference data and integration order](reference-data-and-integration-order.md)
