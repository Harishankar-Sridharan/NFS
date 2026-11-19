---
description: Complete reference of the Circulation file and general writing rules.
---

# Circulation file reference

This section describes all the objects available in the Circulation file and their main parameters.

## General rules

* The format is defined by the `circulation-config.xsd` schema, delivered with the application. Validate your files with an XML editor that uses it.
* Follow the tag order imposed by the schema.
* Tags common to most objects: `id` (required, unique), `description` (optional), `alert-application-log-enabled` (optional, `true` to record the start and end of processing in the application event log).
* Boolean values are written `true` or `false`.

The tables in this section present all the objects available in the documented version. Objects marked with ◆ are described from the configuration schema only: validate their behavior in a test environment before any production use.

## In this section

| Page | Objects described |
| --- | --- |
| Listeners<!-- TODO-LINK: module-circulation/reference/ecouteurs --> | Internal and external listeners, status filters, JMS connection listener |
| Filtering routers<!-- TODO-LINK: module-circulation/reference/routeurs-filtrage --> | `filter-routers`, `forward-router`, `routers-distributor` |
| Processors<!-- TODO-LINK: module-circulation/reference/processeurs --> | Internal and external processors, SQL parameters, CSV export options, notification recipients |
| Media<!-- TODO-LINK: module-circulation/reference/mediums --> | Input and output media, names of the files produced |
| Transformers and connections<!-- TODO-LINK: module-circulation/reference/transformateurs-connexions --> | `transformers`, `connections` |
| Triggers and switches<!-- TODO-LINK: module-circulation/reference/declencheurs-interrupteurs --> | `triggers`, `interruptors` |
| circulation-result return format<!-- TODO-LINK: module-circulation/reference/format-circulation-result --> | HTTP responses and XML diagnostic outputs |
