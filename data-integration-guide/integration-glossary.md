---
description: Definitions of the terms used in the data integration guide.
---

# Integration glossary

| Term | Definition |
| --- | --- |
| Entity | Type of object exchanged (customer, resource, appointment, and so on), described by a list of fields. |
| Exchange model | Set of entities and fields you can use to import and export Nomadia Field Service data. |
| External identifier | Identifier of an object in the customer information system (IS) (field …ID), which Nomadia Field Service uses to find the object. |
| Reference | Field that contains the external identifier of an object of another entity (type ID\_FOREIGN or IDS\_LIST). |
| Header | First row of a CSV file, containing the field names. |
| List separator | Character that separates several values in a single field. |
| Text delimiter | Character that surrounds a value (usually "). |
| BOM | Byte order mark placed at the start of some UTF-8 files. |
| Geocoding | Calculation of geographic coordinates from an address. |
| Region | Area entity: scope of data planned together (territory or activity). |
| Work site / branch | Worksite entity: place to which resources and customers are attached. |
| Appointment | Appointment entity: work to perform at a customer's site. The mobile app calls it an intervention. |
| Macro-status | Grouping of appointment statuses: Candidate, Scheduled, Achieved, Cancelled, Aside. |
| Circulation | Nomadia Field Service engine for automated flows (files, SFTP, HTTP, SQL, JMS). |
| Webhook | URL of an external system that Nomadia Field Service calls to send it data. |
| Session | Authentication context of a web service client, identified by a SessionId. |
| Bearer token | Access token sent in the HTTP Authorization header. |
| SOAP / REST | Web service styles: SOAP exchanges XML messages described by a WSDL; REST uses URLs and JSON or XML formats. |
| Typology | List of codes and labels associated with a custom field. |

