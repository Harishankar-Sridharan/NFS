---
description: Checks performed at import, error codes, and the import report.
---

# Data validation and error handling

![Import file processing: a CSV file (one file = one entity, header row) goes through entity recognition (header compared with required fields), line-by-line reading (separator, dates, value lists), and checks (required fields, references, formats), then create, update, or delete (lookup by external identifier), and finally the report (summary, warnings, rejected rows). A row that fails a check is rejected and recorded in the report.](../.gitbook/assets/en_integration_import_processing.png)

## Checks performed

| Check | Level | Consequence |
| --- | --- | --- |
| Recognized header (required fields present, or a column …$ID) | File | The file import stops if no entity matches. |
| Number of values in the row | Row | Rejection if the row has more values than the header. |
| Required field filled in | Row | Rejection (code REQUIREDFIELDNOTPROVIDED). |
| Existing reference (ID\_FOREIGN, IDS\_LIST) | Row | Rejection: "Object not found for field X with value Y". |
| Date, time, and number format | Row | Rejection (date); warning or rejection depending on parsing.rigorous (numbers, booleans). |
| Import mode (INSERTONLY, UPDATEONLY) | Row | Rejection: "Not allowed to create new record" / "Not allowed to update the existing record". |
| Geocoding | Row | Rejection if the address cannot be located and no fallback site is defined. |
| Appointment status change | Row | Change refused or converted (see [Integrate appointments](integrate-appointments.md)). |

Reminder: a rejected row is recorded and the import continues
<!-- REVIEW: this sentence is incomplete in the French source (no final period or continuation); translated as is -->

## Import error codes

| Code | Name | Meaning |
| --- | --- | --- |
| 0 | SUCCESS | Row imported. |
| 1 | UNKNOWNERROR | Unqualified error. |
| 2 | REFENTENTENITYNOTFOUND | Referenced entity not found. |
| 3 | TARGETENTITYNOTFOUND | Object to update not found. |
| 4 | REQUIREDFIELDNOTPROVIDED | Required field not filled in. |
| 6 | SAVEINDATABASEERROR | Database save error. |

## Import report

An import from the interface produces two text files, available from the administration: Result\_<file><timestamp>.txt (imported rows) and ErrResult\_<file><timestamp>.txt (rejected rows). Each row has the form number;true|false;message, and the header row is labeled Header. These files are purged after the delay set by import.setting.delayBeforeDeleteReports (1 day by default).

Previous: [Custom fields](custom-fields.md)

Next: [Logging and supervision](logging-and-supervision.md)
