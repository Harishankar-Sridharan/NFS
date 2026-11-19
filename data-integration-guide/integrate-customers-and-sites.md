---
description: Customers, contacts, projects, and customer geolocation.
---

# Integrate customers and sites

The customer (Customer) represents the place where the appointment takes place: a site, an establishment, or an individual. A requester (Orderer) groups several sites of the same ordering party. Contacts (Contact) and projects (Project) are attached to the customer.

| Field | Type | Req. | Reference | Description | Example / default |
| --- | --- | --- | --- | --- | --- |
| CUSTOMERID | ID | Yes |  | Identifier of the site/customer in the company's information system | e.g. CLI\_001 |
| CUSTOMERNAME | String | Yes |  | Name of the site/customer |  |
| CUSTOMERTYPEID | Ref. | No | Customer type | Site/customer type. Refers to customertype.customer\_type\_id | e.g. Boulangerie, Restaurant, Hôtel, Usine, etc |
| AREAID | Ref. | No | Region | Region the site/customer belongs to | e.g. REG\_001 |
| WORKSITEID | Ref. | No | Work site | Agency the site/customer belongs to. Can be used as an alternative to the sector, because the sector is a subclass of the work site. However, if the customer is linked to a sector whose parent work site is the imported work site, the current assignment to the child of the work site remains unchanged | e.g. WKS\_001 |
| ORDERERID | Ref. | No | Requester | Requester managing this site/customer |  |
| ADDRESS | Address | No |  | Postal address of the site/customer (street + street number) | e.g. 66 avenue du Maine |
| CODEZONE | Address | No |  | Postcode of the site/customer address | e.g. 75014 |
| CITY | Address | No |  | City of the site/customer address | e.g. PARIS |
| COUNTRY | Address | No |  | ISO country code | e.g. FR, UK, DE, SP, CH etc |
| XGEO | Longitude | No |  | Geographic longitude of the site/customer (GPS position) | e.g. 2.32168 |
| YGEO | Latitude | No |  | Geographic latitude of the site/customer (GPS position) | e.g. 48.83928 |
| ACTIVE | Boolean | No |  | Activation (1, "O", true) / Deactivation of the site/customer (0, "N", false) | e.g. 1 · default 1 |
| PRIORITY | Integer | No |  | Priority given to this site/customer (between 0 and 100). The value 0 means "not defined" and is equivalent to the average value 50. This priority can be passed down to the appointments that take place at this site/customer. | e.g. 0 · default 0 |
| ACTION | String | No |  | Action verb to delete the record | e.g. DELETE |

The entity also includes the opening hours by day (DAY1BEGINTIME to DAY7ENDLUNCHPERIOD), the data of the main contact (CONTACT…), the visit recurrence (LASTVISITDATE, TIMEBETWEENVISIT…), and the custom fields.

**Contact (Contact)**

| Field | Type | Req. | Reference | Description | Example / default |
| --- | --- | --- | --- | --- | --- |
| CONTACTID | ID | Yes |  | Identifier of a contact of a site/customer | e.g. CON\_001 |
| CUSTOMERID | Ref. | Yes | Customer | Identifier of the site/customer for which this contact is declared | e.g. CLI\_001 |
| CONTACTLASTNAME | String | Yes |  | Contact last name | e.g. MARTIN |
| CONTACTFIRSTNAME | String | No |  | Contact first name | e.g. Pierre |
| ISMAIN | Boolean | Yes |  | Main contact at this site/customer (1/Y/O: yes, 0/N: no) | e.g. 1 |
| CONTACTWORKPHONE | String | No |  | Contact phone number (work) | e.g. 0101010101 |
| CONTACTCELLULARPHONE | String | No |  | Contact phone number (mobile) | e.g. 0606060606 |
| CONTACTWORKEMAIL | String | No |  | Contact email (work) | e.g. pierre.martin@societe.com |
| ACTION | String | No |  | Action verb to delete the record (DELETE) |  |

**Project (Project)**

| Field | Type | Req. | Reference | Description | Example / default |
| --- | --- | --- | --- | --- | --- |
| PROJECTID | ID | Yes |  | Project identifier | e.g. P001 |
| CUSTOMERID | Ref. | Yes | Customer | Customer identifier | e.g. CUST01 |
| DEFAULTTASKTYPEID | Ref. | No | Intervention type | Intervention type associated with the project, managed by default at this site/customer | e.g. TT\_001 |
| WORKSITEID | Ref. | No | Work site | Work site identifier | e.g. WS01 |

The main contact can be imported directly in the customer file (CONTACT… columns) or separately with the Contact entity, which allows several contacts per customer (ISMAIN designates the main one).

<!-- REVIEW: the source has no titles above the contact and project tables; the bold labels (Contact, Project) were added only to tell the tables apart. -->

## Customer geolocation

Preferably provide XGEO (longitude) and YGEO (latitude) coordinates: the address is then not geocoded. Otherwise, Nomadia Field Service geocodes the address at import (see [Import data](import-data.md)).

Previous: [Integrate skills, authorizations, and assignment rules](integrate-skills-authorizations-and-assignment-rules.md)

Next: [Integrate appointments](integrate-appointments.md)
