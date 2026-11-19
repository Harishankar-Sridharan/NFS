---
description: Overview of the Nomadia Field Service Circulation module, which moves data between the application and external systems.
---

# Circulation module

Circulation is an exchange engine built into Nomadia Field Service. It moves data between Nomadia Field Service and external systems (files, SFTP servers, databases, web services, messaging, and more) and automates some internal processing.

Circulation has no data-entry screen. Its behavior is described in an XML file, `circulation_config.xml`, which is loaded when the server starts and can be replaced from Administration. This file describes processing chains: an incoming event or message is captured, optionally filtered, then processed in Nomadia Field Service or sent to an external system.

This documentation describes version 2027.1.1 of Nomadia Field Service. Some screens or objects may be missing from earlier versions.

<!-- REVIEW: the French source says version 2027.1.1, while the test environment runs version 2026.3.3. Confirm the version number. -->

## Who this documentation is for

* Functional administrators of Nomadia Field Service.
* Consultants and integrators in charge of setting up exchanges with the customer information system (IS).
* Support and project teams.

The configuration is done in an XML file, so you need a basic knowledge of this format.

## Usage examples

| Need | Components used (examples) |
| --- | --- |
| Import customers, unavailabilities, and appointments dropped as CSV files every night | `directory-input-medium`, `exchange-records-csv-processor` |
| Retrieve files from an SFTP server or drop exports on it | `url-input-medium`, `url-output-medium` |
| Run a batch optimization after an import or at a fixed time | `batch-optim-processor`, `instant-trigger` |
| Export as CSV the appointments that change status | `appointment-listener`, `csv-record-export-processor` |
| Feed an external database or import from it | `sql-exporter-processor`, `sql-importer-processor` |
| Send an email, an SMS, or an application message | `appointment-notifier`, `mail-output-medium`, `sms-output-medium`, `message-output-medium` |
| Call a REST or HTTP web service | `rest-output-medium`, `http-output-medium`, `send-entities-processor` |
| Receive messages over HTTP (Circulation URL) | `http-input-medium` |

## Conventions used

* `outside-listener`: name of a tag or a value to enter as is in the Circulation file.
* **Circulation file**: label of a menu, screen, or button in the application.
* `Administration > XML Files`: navigation path in the Administration module.
* **Appointment**: an appointment that can be scheduled in Nomadia Field Service (`appointment` tags in the file).

## In this section

| Page | Content |
| --- | --- |
| Understand how Circulation works<!-- TODO-LINK: module-circulation/principe-fonctionnement --> | Key concepts, processing chain, file structure |
| [Prerequisites and access](prerequisites-and-access.md) | Required rights and Administration screens |
| Load a Circulation file<!-- TODO-LINK: module-circulation/charger-fichier-circulation --> | Loading at startup, importing a new file, report messages |
| Monitor and manage Circulation<!-- TODO-LINK: module-circulation/suivre-piloter-circulation --> | Current configuration, listeners, delivered examples, HTTP listeners, export links |
| [Secure credentials with the vault](secure-credentials-with-the-vault.md) | Vault, references, and migration |
| Configuration examples<!-- TODO-LINK: module-circulation/exemples --> | Three complete, commented use cases |
| [Circulation file reference](circulation-file-reference.md) | All objects and their parameters |
| Appendices<!-- TODO-LINK: module-circulation/annexes --> | Cron expressions, appointment statuses, mapping to the former documentation |
