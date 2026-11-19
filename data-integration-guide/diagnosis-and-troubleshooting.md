---
description: Common errors, probable causes, resolutions, and the diagnosis procedure.
---

# Diagnosis and troubleshooting

| Symptom | Probable cause | Resolution |
| --- | --- | --- |
| The file is not imported, no row is processed | Header not recognized: a required field is missing or misspelled. | Compare the header with the exchange model; add the required fields. |
| A different entity than expected is imported | The columns match the required fields of several entities. | Check the entity shown on the "Header" row of the report; complete the header. |
| A value is not taken into account, with no error | Unknown column name (column ignored) or field reserved for export. | Correct the name; check the I/E column in the [exchange model reference](exchange-model-reference.md). |
| Values were erased | Columns present with empty cells. | Remove the columns you do not want to change. |
| "Object not found for field X with value Y" | Reference to an object that is missing or not yet imported. | Import the referenced entity first; check the identifier. |
| "Invalid Location, cannot geocode" | Address that cannot be geocoded with the chosen tolerance. | Correct the address, supply XGEO/YGEO, lower the tolerance, or define a fallback site. |
| "can't convert provided date" | Date format different from the import format. | Align the format (dd/MM/yyyy in the interface, yyyy/MM/dd on the server side by default). |
| Accented characters corrupted | File encoding different from the one chosen. | Choose the correct encoding, or convert the file. |
| Appointment status not changed | Change forbidden or converted by the lifecycle rules. | See [Integrate appointments](integrate-appointments.md). |
| Row rejected: too many fields | Separator present in a value that is not delimited. | Delimit the values (") or change the separator. |
| Web service: code 10 | Session expired or unknown. | Authenticate again with CommonInfo. |
| Web service: code 20 | Incorrect key, identifier, or password. | Check the instance key and the integration account. |
| Web service: code 11 | Concurrent call on the same session. | Sequence the calls or use one session per thread. |

## Diagnosis procedure

1. Check the import report (ErrResult\_… file) or the web service response.
2. Check the application log, filtered on the types import\_error, service\_fail, or communication\_error.
3. Reproduce with a single-row file in the test environment.
4. Send the file, the report, the timestamp, and the user to support.
