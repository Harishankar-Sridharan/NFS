---
description: Best practices for preparation, loading, and performance.
---

# Best practices

## Preparation

* Define a stable external identifier convention (a prefix per entity: CLI\_, TECH\_, ITV\_…).
* Supply XGEO/YGEO coordinates when they are known: the import is faster and more reliable.
* Use UTF-8 for the global import; for a single-file import, choose the encoding explicitly in the form.
* Keep the same format configuration (separators, dates) in all your flows and document it.

## Loading

* Follow the integration order (see the detailed integration order<!-- TODO-LINK: guide-dintegration-des-donnees/annexes/ordre-integration-detaille -->); check the report of each file.
* Test each file on a sample of a few rows before the full load.
* For updates, send only the columns to change and use the UPDATEONLY mode (…$ID) to avoid accidental creations.
* Deactivate (ACTIVE = 0) rather than delete the reference data used by the history.

## Performance

* An import through the interface is synchronous and commits one transaction per row: split very large volumes into several files and prefer Circulation for recurring flows.
* Avoid mass geocoding during import: supply the coordinates or geocode beforehand.
* For web services, reuse the session and group records (setEntities, SetEntitiesFromCsv) instead of calling the service for each object.
* Limit exports to the useful fields and records (FieldNames, LASTUPDATED).
