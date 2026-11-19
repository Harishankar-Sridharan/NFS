---
description: Complete reference of the entities and fields of the Nomadia Field Service exchange model.
---

# Exchange model reference

This appendix reproduces the complete exchange model and the field descriptions of the application. Series of numbered fields (for example FILLER1 … FILLER5) are grouped on one line.

| Column | Meaning |
| --- | --- |
| Field | Technical name to use in files and web services; accepted synonyms in parentheses. |
| Type | Data type (see the type dictionary); "Ref.": identifier of another entity. |
| Req. | "Yes" if the field is required. |
| I/E | I: import only; E: export only; I/E: both. |
| Ref. | Referenced entity. |
| Example / default | Example and default value from the model (when they exist). |

The descriptions come from the exchange model of the application. Some historical wording has been kept as is; only the product terminology has been updated.

## Domains

| Domain | Entities |
| --- | --- |
| Organization<!-- TODO-LINK: guide-dintegration-des-donnees/reference-modele/organisation --> | Area, WorkSiteType, Worksite, SectorType, Sector, City, Team, DutySectorType, DutySector, WorksiteDutyDayType, WorksiteDutyWeekType, WorkSiteClosing, SectorWorkSiteClosing, DutySectorClosing, RestrictedArea |
| Activity and skills<!-- TODO-LINK: guide-dintegration-des-donnees/reference-modele/activite-et-competences --> | TaskTypeGroup, TaskType, TaskTypeDetail, Qualification, Authorization, CompletionType, ToDoNextType, Objective, SellingPeriod, PeriodicityType |
| Resources<!-- TODO-LINK: guide-dintegration-des-donnees/reference-modele/ressources --> | HumanResource, SubContractor, ResourceType, ResourceFunction, ResourcetypePriority, ResourcetypeGroupPriority, ResourceJobType, JobTypePriority, JobTypeGroupPriority, FunctionPriority, FunctionGroupPriority, ResourceQualification, TaskPriorities, ResourcePriority, ResourceWorksite, ResourceDutySector, ResourceJobProfile, Crew, UserPerimeter, UserPreference |
| Calendars, unavailabilities, and on-call duties<!-- TODO-LINK: guide-dintegration-des-donnees/reference-modele/calendriers-indisponibilites-et-astreintes --> | WorkdayType, WorkWeekType, ResourceWorkday, ResourceWorkWeek, PublicHoliday, UnavailabilityType, Unavailability, ExpressUnavailability, ExceptLocationType, ExceptLocation, AgendaControlledDate, DutyType, DutyWeekType, Duty, DutyWeek, DutyReplacement, BusinessLocation, DepotBusinessLocation, BusinessClosingPeriod, DepotClosingPeriod |
| Customers<!-- TODO-LINK: guide-dintegration-des-donnees/reference-modele/clients --> | Orderer, CustomerType, CustomerKind, Customer, Contact, CustomerWorkday, ClosingPeriod, Project, ProjectDetail, ToursPlan, TourPlanCustomer, VisitCustomer |
| Appointments<!-- TODO-LINK: guide-dintegration-des-donnees/reference-modele/interventions --> | Appointment, AppointmentCustomer, AppointmentDetail, AchievementSlot, Parcel, GroupedPickupDelivery, AgendaMarker |
| Vehicles, equipment, materials, and stock<!-- TODO-LINK: guide-dintegration-des-donnees/reference-modele/vehicules-equipements-materiel-et-stock --> | Vehicle, Equipment, EquipmentPosition, HrVehicleEquipment, Supply, SupplyResource, Product, ProductFamily, Stock, StockMovement, Supplier |
| Security and configuration<!-- TODO-LINK: guide-dintegration-des-donnees/reference-modele/securite-et-parametrage --> | RightCollection, RightCollectioncontent, Group, ApplicationLogSubscription, CustomConfiguration, Appearance, Typology, Common |
| Exports only<!-- TODO-LINK: guide-dintegration-des-donnees/reference-modele/exports-uniquement --> | AgendaEvent, ApplicationEvent, AgendaDaySummary, AgendaWeekSummary, Journal, ReportResult |
