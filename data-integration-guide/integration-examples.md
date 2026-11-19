---
description: Complete fictitious data set: CSV files, updates, deletion, and web service calls.
---

# Integration examples

The following examples form a single fictitious data set: the maintenance company "Démo Services" integrates a region, an agency, a team, an intervention type, two technicians, a customer, and an appointment. The files use the default parameters of the import from the interface: separator `;`, list separator `,`, dates dd/MM/yyyy.

## 1. Organization

01\_Area.csv

```
AREAID;AREANAME;DESCRIPTION
REG_IDF;Île-de-France;Région de démonstration
```

02\_Worksite.csv

```
WORKSITEID;WORKSITENAME;AREAID;ADDRESS;CODEZONE;CITY;COUNTRY;XGEO;YGEO
AG_PARIS_N;Agence Paris Nord;REG_IDF;10 rue de l'Exemple;75018;Paris;France;2.3522;48.8925
```

03\_Team.csv

```
TEAMID;TEAMNAME;AREAID;ACTIVE
EQ_NORD;Équipe Nord;REG_IDF;1
```

## 2. Activity reference data

04\_Qualification.csv

```
QUALIFICATIONID;QUALIFICATIONNAME;AREAID
QUAL_GAZ;Habilitation gaz;REG_IDF
```

05\_TaskTypeGroup.csv

```
TASKTYPEGROUPID;TASKTYPEGROUPNAME;AREAID
TTG_MAINT;Maintenance;REG_IDF
```

06\_TaskType.csv

```
TASKTYPEID;TASKTYPENAME;TASKTYPEGROUPID;DURATION;QUALIFICATIONS
TT_ENTRETIEN;Entretien annuel chaudière;TTG_MAINT;60;QUAL_GAZ
TT_DEPANNAGE;Dépannage;TTG_MAINT;90;
```

07\_UnavailabilityType.csv

```
UNAVAILABILITYTYPEID;UNAVAILABILITYTYPENAME;ISWORKTIME
IND_FORM;Formation;1
```

## 3. Resources
<!-- REVIEW: this section is empty in the French source (examples missing) -->

## 4. Customers
<!-- REVIEW: this section is empty in the French source (examples missing) -->

## 5. Appointments

The appointment is created with the Requested status (21), then Nomadia Field Service looks for a slot (SCHEDULE). Only Julie MARTIN has the skill QUAL\_GAZ required by the type TT\_ENTRETIEN; she is unavailable on the morning of 16/11/2026 (dd/MM/yyyy).
<!-- REVIEW: the CSV examples for this section are missing in the French source -->

## 6. Updates

A "Completed" (3) declaration on an appointment that was never scheduled is converted to Unplanned (35); it is refused if no completion date is provided.
<!-- REVIEW: the CSV examples for this section are missing in the French source. The status labels "Réalisé" and "Imprévu" are translated as "Completed" (3) and "Unplanned" (35), as in the appointment lifecycle diagram. -->

## 7. Deletion and deactivation
<!-- REVIEW: this section is empty in the French source (examples missing) -->

## 8. Calling the setEntities web service (REST, JSON)
<!-- REVIEW: this section is empty in the French source (examples missing) -->

## 9. Export through a web service (GetEntitiesProperties)
<!-- REVIEW: this section is empty in the French source (examples missing) -->

## 10. Error example
<!-- REVIEW: this section is empty in the French source (examples missing) -->

Previous: [Logging and supervision](logging-and-supervision.md)

Next: [Best practices](best-practices.md)
