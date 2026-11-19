---
description: Nomadia Field Service (NFS) data integration guide: exchange model, imports and exports, web services, appointment lifecycle.
---

# Data integration guide

This guide explains how to feed Nomadia Field Service (NFS) with a customer's data and how to extract the results. It describes the exchange channels, the exchange model (entities and fields), the format and validation rules, the integration order, error handling, and the available web services.

Application configuration (profiles and rights, optimization tasks, vocabulary, logo) is part of functional administration and is not covered here. See the [User guide](../README.md).

## Who this guide is for

* Integration consultants and project managers who prepare a data migration or a recurring flow.
* Support teams who diagnose an import or an export that fails.
* Technical partners and customer IT teams who develop a connector.
* R&D teams who need a functional reference for the exchange model.

Readers must know how to handle a CSV file and read a JSON or XML document. Technical terms are defined in the glossary<!-- TODO-LINK: guide-dintegration-des-donnees/annexes/glossaire -->.

## Scope

| Included in this guide | Out of scope |
| --- | --- |
| Exchange model: 109 entities that can be imported or exported, fields, types, references | Functional configuration (profiles, right collections, optimization, vocabulary) |
| CSV import and export from the administration interface, global import and export (ZIP) | Detailed Circulation configuration (see the Circulation module<!-- TODO-LINK: module-circulation/module-circulation -->) |
| Data exchange web services (SOAP and REST) and appointment-booking services | Mobile application, mobility, and field forms |
| Appointment statuses and lifecycle, validation rules, errors, logging | Operations, hosting, backup, and infrastructure security |

## In this section

| Page | Content |
| --- | --- |
| [Integration overview](integration-overview.md) | Principle, exchange channels, architecture, and typical sequence |
| [Prerequisites](prerequisites.md) | Data to prepare, external identifiers, access |
| [Authentication and security](authentication-and-security.md) | Web service authentication modes, best practices |
| [Concepts and exchange model](concepts-and-exchange-model.md) | Entities, data types, import and export columns, synonyms |
| [Reference data and integration order](reference-data-and-integration-order.md) | Loading order, then integration of each domain: organization, resources, calendars, skills, customers, appointments |
| Importing data<!-- TODO-LINK: guide-dintegration-des-donnees/imports --> | Entry points, CSV format, creation, update, deletion, geocoding, global import |
| Exporting data<!-- TODO-LINK: guide-dintegration-des-donnees/exports --> | Entry points, extraction types, formats, global export |
| Integration APIs and web services<!-- TODO-LINK: guide-dintegration-des-donnees/api-services-web --> | Data exchange services, business services, error codes |
| Custom fields<!-- TODO-LINK: guide-dintegration-des-donnees/champs-personnalises --> | Free fields, typologies, labels |
| Data validation and error handling<!-- TODO-LINK: guide-dintegration-des-donnees/validation-erreurs --> | Checks, error codes, import report |
| Logging and supervision<!-- TODO-LINK: guide-dintegration-des-donnees/journalisation-supervision --> | Application log, subscriptions, supervision exports |
| Integration examples<!-- TODO-LINK: guide-dintegration-des-donnees/exemples --> | Complete fictitious data set and web service calls |
| Best practices<!-- TODO-LINK: guide-dintegration-des-donnees/bonnes-pratiques --> | Preparation, loading, performance |
| Diagnosis and troubleshooting<!-- TODO-LINK: guide-dintegration-des-donnees/diagnostic --> | Common errors and diagnostic approach |
| Exchange model reference<!-- TODO-LINK: guide-dintegration-des-donnees/reference-modele --> | All entities and all fields, by domain |
| Appendices<!-- TODO-LINK: guide-dintegration-des-donnees/annexes --> | Detailed integration order, mapping to the former guide, glossary |
