---
description: Web service families, data exchange services, business services, and error codes.
---

# Integration APIs and web services

## Service families

| Family | URL | Format | Use |
| --- | --- | --- | --- |
| SOAP services | /ws/<service>Service/ (WSDL: /ws/[vN/]<service>Service/<service>.wsdl) | XML | Data exchange and business services. |
| Legacy REST services | /rest/[vN/]<service>/json/<method> or /xml/<method> | JSON or XML | Same operations as SOAP; JSONP with GET (?data=). |
| REST API v1 | /ws-api/v1/<service>/<operation> | JSON (XML for some services) | Recent services: availability and slot booking, stock, restricted zones, notifications, and so on. |

The online documentation of the instance (API help pages) provides, for each service, the description of the methods and examples of JSON requests and responses. Only versions n and n-1 of each service are guaranteed.

## Data exchange services

| Service | Operations | Role |
| --- | --- | --- |
| entities | SetEntitiesFromCsv, SetEntityFromProperties, setEntities (REST) | Import of exchange model records. |
| exportEntities | GetEntitiesProperties, getEntities (REST v2), GetAppointmentsByResources | Export of records. |
| exchangeModel | ListEntities, GetExchangeModel | Model discovery: entities, fields, types, required fields. |
| disabledEntities | RetrieveDisabledEntities, DisableEntities, RestoreDisabledEntities | Disabling and restoring objects. |
| extref | IsExtrefAvailable, GetNewExtref, UpdateExtref | Management of external identifiers. |

### SetEntitiesFromCsv

Imports CSV content sent in the request. As with file import, the entity is deduced from the header row: the request contains neither an entity name nor an action.

| Element | Default | Description |
| --- | --- | --- |
| CsvData | — | CSV content: header row followed by data rows. |
| DataSeparator | ; | Field separator. |
| TextDelimiter | " | Text delimiter. |
| DateFormat | dd/MM/yyyy | Date format. |
| SeparatorInListOfValues | , | List separator. |
| GeocodingOptions | AT\_STREET\_NUMBER, 0,8 | Tolerance (GeocodingType), minimum score (MinScore), and fallback site (DefaultWorkSiteId). |
| CommonInfo | — | Authentication (see [Authentication and security](authentication-and-security.md)). |

The response contains IsSuccessful, NbSuccess, NbFailure, HtmlSummary (row-by-row report), and ErrorMessage.

### setEntities (REST)

JSON variant: each record is an object whose keys are the field names. The response details the records in error (Errors[] with the record and the message). The UseSingleTransaction option is available.

### GetEntitiesProperties

Exports an entity: EntityName, FieldNames (comma-separated list of fields), DateFormat, TimeFormat, ExtractionKind (default ALL), ExtractionParam, ExtractionAreaParam, EntityId/EntityIds, ValueListSeparator, DurationAsTimeFormat. The response contains rows (Rows) of name/value properties.

### GetExchangeModel

Returns, for an entity, the list of its fields with description, example, default value, whether it is required, type, and restriction to import or export. ListEntities returns the list of entities and their description.

## Business services

| Service | Main operations |
| --- | --- |
| scheduling | GetResourcePlanning, ReserveAppointment, ConfirmAppointment, SuspendAppointment, ReactivateAppointment, RealizeAppointment, CancelAppointment |
| optimization, realTimeOptimization, manualOptimization, fillPlanning, routeSolver | Launching and monitoring optimizations; searching for, validating, and abandoning slot proposals. |
| geocode, route, searchAround | Geocoding, reverse geocoding, coordinate conversion, route calculation, proximity search. |
| otprocess | Process control (start, data submission, status, result, stop). |
| messages, multimedia, tracking, mission, lock | Messaging, attached files, resource positions, missions, locks. |
| REST API v1 availableTime | Search for available slots, booking, and cancellation (search, reserve, cancel). |

## Result and error codes

Responses contain a Result block (Success, ErrorCode, Detail) and, where applicable, the session identifier.

| Code | Name | Meaning |
| --- | --- | --- |
| 0 | UNKNOWN\_ERROR | Unqualified error; see Detail. |
| 10 | SESSION\_NOT\_FOUND | Unknown or expired session. |
| 11 | SESSION\_ALREADY\_RUNNING\_METHOD | A concurrent call is in progress on the same session. |
| 20 | WRONG\_LOGIN\_PASSWORD | Authentication refused. |
| 30 | IMPORT\_ERROR | Import error. |
| 40 | CONFIG\_ERROR | Server configuration error. |
| 50 | WS\_SCHEMA\_ERROR | Request does not comply with the schema. |
| 500 and above | Service-specific codes | For example ENTITYNAME\_NOT\_FOUND (500) for exchangeModel, EXTREF\_ALREADY\_EXISTS (501) for extref. |

Previous: [Export data](export-data.md)

Next: [Custom fields](custom-fields.md)
