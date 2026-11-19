---
description: Export entry points, extraction types, linked fields, output formats, and global export.
---

# Export data

## Entry points

| Entry point | Result |
| --- | --- |
| `Administration > CSV files > Export a CSV file` | File export<Entity>.csv for one entity, with a choice of fields, filters, separators, formats, and encoding. Option for headers as labels. |
| `Administration > CSV files > Global CSV import/export` | Archive allExportFiles.zip: one NN\_<Entity>.csv file per importable entity, numbered in dependency order. |
| exportEntities web service | Operations GetEntitiesProperties (SOAP/REST), getEntities (REST v2, JSON), and GetAppointmentsByResources. |
| Circulation | Exports scheduled or triggered by an event (file, SQL, HTTP, webhook). |

<!-- REVIEW: menu labels are translated from the French menu names; check them against the English UI. -->

## Extraction types

The extraction type (ExtractionKind) selects the records; its parameter (ExtractionParam) refines it. You can combine several types by separating them with a comma, with the parameters in the same order.

| Type | Selection | Parameter |
| --- | --- | --- |
| ALL | All records (default). | — |
| LASTUPDATED | Recently modified records. | 1: since yesterday 0:00; 2: since 7 days; n > 2: since n minutes. |
| DATEINTERVAL | Absolute period. | yyyy/MM/dd;yyyy/MM/dd |
| DATEDIFFINTERVAL | Period relative to today. | a;b: from D+a to D+a+b days. |
| AREA, WORKSITE, TEAM, RESOURCE | Filter on a region, a site, a team, a resource. | External identifier. |
| Entity-specific types | For example, for the customer: CUSTOMERPHONE, CONTACTWORKPHONE, PARENTWORKSITE, CUSTOMERTYPE, CUSTOMERKIND, DUTYCONTRACT. | Depends on the type. |

## Linked fields

A column of the form `ENTITY.FIELD` exports a field of the referenced entity, for example Customer.CUSTOMERNAME in an appointment export. For a list of references, the suffix (n) selects the nth element and () exports all of them.

## Output formats

Besides CSV, the export engine can produce: JSON (list of objects or array), HTML table, Excel (HTML table), XML of records, and ECMAScript script. The available format depends on the entry point.

## Global export

The global export produces all the importable entities, sorted by dependency level. The first file contains only RESOURCEID and RESOURCELASTNAME. The resulting archive can be reimported directly by the global import (for example, to copy one test environment to another).
