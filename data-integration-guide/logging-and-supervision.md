---
description: Application log, log subscription, and supervision exports.
---

# Logging and supervision

Imports, exports, and service calls feed the application log. Each event has a type, a level, a code, and the user who initiated the action.

| Event type | Code | Use for integration |
| --- | --- | --- |
| import\_warn / import\_error / import\_summary | 300 / 330 / 360 | Warning, row-by-row error, end-of-import summary. |
| export\_warn / export\_summary / export\_error | 400 / 430 / 460 | Export monitoring. |
| communication\_warn / \_success / \_error | 500 / 530 / 550 | Exchanges with external systems. |
| process\_start / process\_end | 600 / 650 | Start and end of a process. |
| service\_call / service\_completed / service\_fail | 700 / 730 / 760 | Service calls. |
| webhook\_call / webhook\_completed / webhook\_fail | 1200 / 1230 / 1260 | Sends to a webhook (Circulation). |
| user\_api\_session | 1001 / 1002 | API session openings (1002: API session of the mobile application). |
| entity\_creation / entity\_update / entity\_disable | 100 / 150 / 200 | Object life cycle. |

Codes issued by the import for import\_error: 1 (no entity matches the header), 2 (incorrect number of fields), 3 (business error on a row), 4 (technical error), 5 (error on the first row). At the end of an import, an import\_warn with code 100 indicates a partial import and an import\_summary with code 200 indicates a complete import; both report the duration.

## Log subscription

The ApplicationLogSubscription entity subscribes a user profile (USERPROFILE) or a collection of rights (RIGHTCOLLECTIONNAME) to a type (LOGTYPE) and a level (LOGLEVEL) of events. Levels: DEBUG (10), INFO (20), ALERT (30), WARN (40), ERROR (50), SEVERE (60), FATAL (99).

## Supervision exports

The exportable entities ApplicationEvent and Journal let you extract the log to a supervision tool. The technical entity Common describes the common traceability fields (AUTHOR, CURRENT\_DATE, CONTEXT, OPERATORID, and so on).

Previous: [Data validation and error handling](data-validation-and-error-handling.md)

Next: [Integration examples](integration-examples.md)
