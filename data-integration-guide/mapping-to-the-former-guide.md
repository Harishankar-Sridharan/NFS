---
description: Changes compared with the former data integration guide.
---

# Mapping to the former guide

This appendix helps teams that have integrations written with the former data integration guide.

| Topic in the former guide | Current situation |
| --- | --- |
| Import-export model (57 entities) | All the historical entities still exist (the UGC processing, which is internal, is no longer documented). About fifty new entities: on-call duties, materials and stock, products, parcels, completion slots, site and sector types, typologies, restricted areas, crews, user preferences and perimeters, and so on. |
| Appointment statuses (21, 2, 30, 31, 10, 6, 3; 12, 33, 35 on export) | New statuses: Accepted (28), Ignored (9), Subcontracted (32). Macro-statuses and transition rules are documented. |
| Intervention type: main fields | DURATION is required (with TASKTYPEID, TASKTYPENAME, TASKTYPEGROUPID). |
| "Resource type" | Replaced, depending on the modeling option, by field worker types or by job types and functions. |
| Channels: CSV, web services, Circulation | Still valid; added REST services (JSON/XML), the REST API v1, bearer token authentication, and sending to a webhook. |
| Configuration (profiles and rights, optimization, vocabulary, logo) | Out of the scope of this guide; the lists of rights and the file paths of the former guide are not carried over. |
| Administrator account created at installation | Information removed (security). |
| Import examples (shifted tables, inconsistent data) | Replaced by a consistent fictitious data set checked against the current model. |
