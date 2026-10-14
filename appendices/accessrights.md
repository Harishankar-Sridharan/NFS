# Access rights

## Overview

This appendix lists the access rights available in NFS, grouped by module and then by theme. Each table gives the identifier of the right and a description of what it allows.

<!-- REVIEW: the source descriptions were written in French and were translated to English; check the UI labels quoted in them (for example Quantities, Logicals, Fillers, Additional dates, Custom action) against the product. -->

## Portal

### Scope

| Right | Description |
| --- | --- |
| `PORTAL_SEE_OPTIMIZATION_OF_ALL_AREA` | View the optimizations for all areas. |
| `PORTAL_MANAGE_OWN_WORKSITE` | Access to the user's own worksite. |
| `PORTAL_MANAGE_OWN_TEAM` | Access to the user's own team. |
| `PORTAL_MANAGE_OWN_DOMAIN` | Access to the areas of the user's own domain. |
| `PORTAL_MANAGE_OWN_AREA` | Access to the user's own area. |
| `PORTAL_GUEST` | Access to the Portal module. |
| `PORTAL_DISPATCHER` | Allows access to the input/output files of the automatic optimizer (Dispatcher). |
| `PORTAL_ALLRESOURCES_PLANNING_UPDATE` | Allows editing the plannings of all resources. |
| `PORTAL_ALLRESOURCES_PLANNING_DETAIL` | Allows access to the planning details of all resources. |
| `PORTAL_ALLRESOURCES_PLANNING_ACCESS` | Allows displaying the plannings of all resources. |

### Schedule

| Right | Description |
| --- | --- |
| `PORTAL_WORKSITE_PLANNING_SECOND` | Includes the resources for which the worksite specified for the worksite planning is a secondary worksite. |
| `PORTAL_WORKSITE_PLANNING_FIRST` | Includes the resources whose main worksite is the worksite specified for the worksite planning. |
| `PORTAL_WORKSITE_PLANNING_EXECUTING` | Includes the resources that perform an appointment at the worksite specified for the worksite planning. |
| `PORTAL_WORKSITE_PLANNING` | Access to worksite plannings. |
| `PORTAL_WHOLEAREA_WORKSITE_PLANNING` | Access to the plannings of all worksites in the user's area. |
| `PORTAL_TEAM_PLANNING_UPDATE` | Allows modifying the planning of members of the same team. |
| `PORTAL_TEAM_PLANNING_DETAIL` | Allows access to the appointment forms of members of the same team. |
| `PORTAL_TEAM_PLANNING_ACCESS` | Read access to team data. |
| `PORTAL_NONMOBILE_RESOURCE_PLANNING` | Access to the plannings of non-mobile resources in the Portal. |
| `PORTAL_MULTIPLANNING_ACCESS` | Access to multi-resource plannings from the Portal. |
| `PORTAL_LEADED_TEAM_PLANNING_UPDATE` | Allows modifying the planning of members of the teams led by the resource. |
| `PORTAL_LEADED_TEAM_PLANNING_DETAIL` | Allows access to the planning details (activities) of members of the teams led by the resource. |
| `PORTAL_LEADED_TEAM_PLANNING_ACCESS` | Access to the plannings of the teams led by the resource. |
| `PORTAL_LEADED_TEAM_CHILD_PLANNING_UPDATE` | Allows modifying the planning of members of the child teams of the teams led by the resource. |
| `PORTAL_LEADED_TEAM_CHILD_PLANNING_DETAIL` | Allows access to the planning details (activities) of members of the child teams of the teams led by the resource. |
| `PORTAL_LEADED_TEAM_CHILD_PLANNING_ACCESS` | Allows access to the planning of the child teams of the teams led by the resource. |
| `PORTAL_AREA_PLANNING` | Access to area plannings. |

### Communication

| Right | Description |
| --- | --- |
| `PORTAL_WAYBILL_EXPORT_XML` | Access to exporting the waybill as XML. |
| `PORTAL_WAYBILL_EXPORT_TOMTOM` | Access to exporting the waybill to TomTom. |
| `PORTAL_WAYBILL_EXPORT_PDF` | Access to exporting the waybill as PDF. |
| `PORTAL_WAYBILL` | Allows access to the waybill. |
| `PORTAL_VIEW_OTMOBILE` | Allows displaying the OTmobile simulation application. |

### Optimization

| Right | Description |
| --- | --- |
| `PORTAL_STOP_MANUAL_OPTIMIZATION` | Allows manually stopping an automatic optimization. |
| `PORTAL_STOP_AUTOMATIC_OPTIMIZATION` | Allows stopping an automatic optimization. |
| `PORTAL_START_OPTIMIZATION_AT_ANY_TIME` | Allows manually starting an automatic optimization at any time. |
| `PORTAL_START_OPTIM_ON_VALIDITY_PERIOD` | Allows manually starting an automatic optimization during its validity period. |
| `PORTAL_OPTIMIZATION_SERVICE` | Access to the optimization services. |

### Unavailabilities

| Right | Description |
| --- | --- |
| `PORTAL_UNAVAILABILITY_MANAGING_ACCESS` | Access to unavailability management. |
| `PORTAL_UNAVAILABILITY_ACCESS` | Access to the unavailabilities menu. |

## Planning

### Scope

| Right | Description |
| --- | --- |
| `CALLCENTER_UPDATE_RESOURCEUSERLISTS` | Access to modifying a resource list in the interface. |
| `CALLCENTER_SHOW_RESOURCEUSERLISTS` | Access to selecting a resource list in the interface. |
| `CALLCENTER_SEE_ONLY_CURRENT_USR` | Restricts all views to those that concern only the logged-in user. |
| `CALLCENTER_MANAGE_PERIMETER` | Allows managing the scope. |
| `CALLCENTER_MANAGE_OWN_WORKSITE` | Access to the user's own worksite. |
| `CALLCENTER_MANAGE_OWN_TEAM` | Access to the user's own team. |
| `CALLCENTER_MANAGE_OWN_DOMAIN` | Allows managing the areas of the user's own domain. |
| `CALLCENTER_MANAGE_OWN_AREA` | Access to the user's own area. |
| `CALLCENTER_MANAGE_EXCEPTIONAL_LOCATION_CURRENT_AREA` | Access to managing exceptional locations for the resources of the current area. |
| `CALLCENTER_MANAGE_EXCEPTIONAL_LOCATION_ALL_AREA` | Access to managing exceptional locations for all resources of all areas. |
| `CALLCENTER_MANAGE_ALL_WORKSITES` | Access to all worksites of the user's area. |
| `CALLCENTER_MANAGE_ALL_TEAMS` | Access to all teams of the user's area. |
| `CALLCENTER_MANAGE_ALL_AREAS` | Access to all areas (all worksites and all teams). |
| `CALLCENTER_GUEST` | Access to the Planning module. |
| `CALLCENTER_DELETE_RESOURCEUSERLISTS` | Access to deleting a resource list in the interface. |
| `CALLCENTER_CRM_VIEW_ALL_AREAS` | Allows viewing the customers of all areas. |
| `CALLCENTER_CREATE_RESOURCEUSERLISTS` | Access to creating a resource list in the interface. |
| `CALLCENTER_CHANGE_AREA` | Allows changing the area of the active module. |

### Customer

| Right | Description |
| --- | --- |
| `CALLCENTER_CRM_VIEW_PROJECT_MAININFO` | Allows displaying the main project information. |
| `CALLCENTER_CRM_VIEW_PROJECT_EXTRAFIELDS` | Allows displaying the additional project fields. |
| `CALLCENTER_CRM_VIEW_PROJECT_DETAILS` | Allows displaying the project details. |
| `CALLCENTER_CRM_VIEW_PROJECT_DAYS` | Allows displaying the project days. |
| `CALLCENTER_CRM_VIEW_PROJECT_ASSIGNMENTS` | Allows viewing the project assignments. |
| `CALLCENTER_CRM_VIEW_ORDERER_REQUIREMENTS` | Allows displaying the orderer's preferences. |
| `CALLCENTER_CRM_VIEW_ORDERER` | Allows access to the orderer. |
| `CALLCENTER_CRM_VIEW_CUSTOMER_TYPE` | Allows viewing the customer type. |
| `CALLCENTER_CRM_VIEW_CUSTOMER_REQUIREMENTS` | Allows viewing the customer preferences. |
| `CALLCENTER_CRM_VIEW_CUSTOMER_PROJECT` | Allows viewing the customer project. |
| `CALLCENTER_CRM_VIEW_CUSTOMER_PLANNING_WEEK` | Allows viewing the customer weekly planning. |
| `CALLCENTER_CRM_VIEW_CUSTOMER_PLANNING_MONTH` | Allows viewing the customer monthly planning. |
| `CALLCENTER_CRM_VIEW_CUSTOMER_KIND` | Allows viewing the customer kinds. |
| `CALLCENTER_CRM_VIEW_CUSTOMER_DAYS` | Allows viewing the customer days. |
| `CALLCENTER_CRM_VIEW_CUSTOMER_CONTACTS` | Allows viewing the customer contacts. |
| `CALLCENTER_CRM_VIEW_CUSTOMER_AUTHORIZATION` | Access to the authorizations on the customer page. |
| `CALLCENTER_CRM_VIEW_CUSTOMER_ASSIGNMENTS` | Allows viewing the customer assignments. |
| `CALLCENTER_CRM_VIEW_CUSTOMER_APPOINTMENTS` | Allows viewing the customer's appointments. |
| `CALLCENTER_CRM_VIEW_CUSTOMER_ADDRESS` | Allows viewing the customer address. |
| `CALLCENTER_CRM_VIEW_CUSTOMER` | Allows viewing the customer. |
| `CALLCENTER_CRM_VIEW_ADDRESSES_STREETVIEW` | Allows access to the Google Street View of an address. |
| `CALLCENTER_CRM_UPDATE_PROJECT_MAININFO` | Allows modifying the main project information. |
| `CALLCENTER_CRM_UPDATE_PROJECT_EXTRAFIELDS` | Allows modifying the additional project fields. |
| `CALLCENTER_CRM_UPDATE_PROJECT_DETAILS` | Allows modifying the project details. |
| `CALLCENTER_CRM_UPDATE_PROJECT_DAYS` | Allows modifying the project days. |
| `CALLCENTER_CRM_UPDATE_PROJECT_ASSIGNMENTS` | Allows modifying the project assignments. |
| `CALLCENTER_CRM_UPDATE_ORDERER_REQUIREMENTS` | Allows modifying the orderer's preferences. |
| `CALLCENTER_CRM_UPDATE_ORDERER` | Allows editing the orderer. |
| `CALLCENTER_CRM_UPDATE_CUSTOMER_TYPE` | Allows editing the customer type. |
| `CALLCENTER_CRM_UPDATE_CUSTOMER_REQUIREMENTS` | Allows editing the customer preferences. |
| `CALLCENTER_CRM_UPDATE_CUSTOMER_PROJECT` | Allows editing the customer project. |
| `CALLCENTER_CRM_UPDATE_CUSTOMER_KIND` | Allows modifying the customer kinds. |
| `CALLCENTER_CRM_UPDATE_CUSTOMER_DETAILS` | Allows editing the customer preferences. |
| `CALLCENTER_CRM_UPDATE_CUSTOMER_DAYS` | Allows editing the customer days. |
| `CALLCENTER_CRM_UPDATE_CUSTOMER_CONTACTS` | Allows editing the customer contacts. |
| `CALLCENTER_CRM_UPDATE_CUSTOMER_AUTHORIZATION` | Allows modifying the authorizations on the customer page. |
| `CALLCENTER_CRM_UPDATE_CUSTOMER_ASSIGNMENTS` | Allows editing the customer assignments. |
| `CALLCENTER_CRM_UPDATE_CUSTOMER_ADDRESS` | Allows editing the customer address. |
| `CALLCENTER_CRM_UPDATE_CUSTOMER` | Allows editing the customer. |
| `CALLCENTER_CRM_TOURS_PLAN` | Access to the tour templates. |
| `CALLCENTER_CRM_SET_MAIN_CUSTOMER_CONTACTS` | Allows editing the main customer contact. |
| `CALLCENTER_CRM_REMOVE_CUSTOMER_CONTACTS` | Allows deleting a customer contact. |
| `CALLCENTER_CRM_LIST_REPLACE_WISHED_HR_LIST` | Allows replacing the list of preferred resources for a list of customers. |
| `CALLCENTER_CRM_LIST_REPLACE_REQUIRED_HR_LIST` | Allows replacing the list of required resources for a list of customers. |
| `CALLCENTER_CRM_LIST_REPLACE_REFUSED_HR_LIST` | Allows replacing the list of refused resources for a list of customers. |
| `CALLCENTER_CRM_LIST_REMOVE_FROM_WISHED_HR_LIST` | Allows removing resources from the list of preferred resources for a list of customers. |
| `CALLCENTER_CRM_LIST_REMOVE_FROM_REQUIRED_HR_LIST` | Allows removing resources from the list of required resources for a list of customers. |
| `CALLCENTER_CRM_LIST_REMOVE_FROM_REFUSED_HR_LIST` | Allows removing resources from the list of refused resources for a list of customers. |
| `CALLCENTER_CRM_LIST_EMPTY_WISHED_HR_LIST` | Allows emptying the list of preferred resources for a list of customers. |
| `CALLCENTER_CRM_LIST_EMPTY_REQUIRED_HR_LIST` | Allows emptying the list of required resources for a list of customers. |
| `CALLCENTER_CRM_LIST_EMPTY_REFUSED_HR_LIST` | Allows emptying the list of refused resources for a list of customers. |
| `CALLCENTER_CRM_LIST_CHANGE_WORKSITE` | Allows changing the worksite for a list of customers. |
| `CALLCENTER_CRM_LIST_CHANGE_TYPE` | Allows changing the type for a list of customers. |
| `CALLCENTER_CRM_LIST_CHANGE_QUANTITIES` | Allows changing the Quantities fields for a list of customers. |
| `CALLCENTER_CRM_LIST_CHANGE_NEXT_SCHEDULED_DATE` | Allows changing the next visit date for a list of customers. |
| `CALLCENTER_CRM_LIST_CHANGE_LOGICALS` | Allows changing the Logicals fields for a list of customers. |
| `CALLCENTER_CRM_LIST_CHANGE_LAST_VISIT_DATE` | Allows changing the last visit date for a list of customers. |
| `CALLCENTER_CRM_LIST_CHANGE_KIND` | Allows changing the kind for a list of customers. |
| `CALLCENTER_CRM_LIST_CHANGE_ISFOCUS` | Allows changing the focus for a list of customers. |
| `CALLCENTER_CRM_LIST_CHANGE_FILLERS` | Allows changing the Fillers fields for a list of customers. |
| `CALLCENTER_CRM_LIST_CHANGE_DATES` | Allows changing the dates for a list of customers. |
| `CALLCENTER_CRM_LIST_ADD_TO_WISHED_HR_LIST` | Allows adding resources to the list of preferred resources for a list of customers. |
| `CALLCENTER_CRM_LIST_ADD_TO_REQUIRED_HR_LIST` | Allows adding resources to the list of required resources for a list of customers. |
| `CALLCENTER_CRM_LIST_ADD_TO_REFUSED_HR_LIST` | Allows adding resources to the list of refused resources for a list of customers. |
| `CALLCENTER_CRM_GENERATE_PERIODIC_APPT` | Access to the page for generating requests for recurring customers. |
| `CALLCENTER_CRM_CUSTOMER_SEARCH_RESET_FORM` | Allows resetting a customer search. |
| `CALLCENTER_CRM_CUSTOMER_SEARCH_CHECK_POSTADDRESS` | Allows checking a customer's postal address during a search. |
| `CALLCENTER_CRM_CUSTOMER_EXPORT_CSV` | Allows exporting a customer in CSV format during a search. |
| `CALLCENTER_CRM_CUSTOMER_ALERT_LIST` | Access right to the list of customer alerts. |
| `CALLCENTER_CRM_CREATE_ORDERER` | Allows creating the orderer. |
| `CALLCENTER_CRM_CREATE_CUSTOMER_TYPE` | Allows creating the customer type. |
| `CALLCENTER_CRM_CREATE_CUSTOMER_KIND` | Allows creating the customer kinds. |
| `CALLCENTER_CRM_CREATE_CUSTOMER_CONTACTS` | Allows creating a customer contact. |
| `CALLCENTER_CRM_CREATE_CUSTOMER` | Allows creating the customer. |
| `CALLCENTER_CRM_APPLY_UPDATES_TO_APP` | Allows propagating customer updates to the appointment requests. |

### Appointment

| Right | Description |
| --- | --- |
| `CALLCENTER_UNPLAN_REALIZED_APPT` | Allows unplanning fully or partially realized appointments. |
| `CALLCENTER_UNPLAN_APPT` | Unplan an appointment. |
| `CALLCENTER_UNDONE_APPT` | Access to undoing the realization of an appointment. |
| `CALLCENTER_UNCONFIRM_APPT` | Allows unconfirming an appointment. |
| `CALLCENTER_TRANSFORM_REQUEST` | Access to the **Transform** button in the appointment form. This button opens a dedicated edit page to easily apply predefined changes according to a customized business process. |
| `CALLCENTER_TAKE_APPT` | Allows access to appointment booking. |
| `CALLCENTER_SUSPEND_APPT` | Suspend an appointment. |
| `CALLCENTER_SPLIT_APPT` | Access to the **Split** button in the appointment page. |
| `CALLCENTER_SHEET_APPT` | Allows access to the appointment form. |
| `CALLCENTER_SAVE_APPT` | Save an appointment. |
| `CALLCENTER_RESERVE_APPT` | Reserve an appointment. |
| `CALLCENTER_REQUEST_CONFIRMED_APPT` | Re-activate a reserved or confirmed appointment. |
| `CALLCENTER_REQUEST_APPT` | Request an appointment. |
| `CALLCENTER_REPLAN_APPT` | Replan an appointment. |
| `CALLCENTER_PHONE_COUNTER` | Display and increment the call counter. |
| `CALLCENTER_MODIFY_APPT` | Allows modifying appointments. |
| `CALLCENTER_FULLREQUEST_MODIFY` | Full access to modifying an appointment request. |
| `CALLCENTER_EDIT_CHAIN_CONSTRAINT` | Create and modify a chaining constraint. |
| `CALLCENTER_DONE_APPT_ANYSTATUS` | Allows switching an appointment to the realized status, regardless of its current status. |
| `CALLCENTER_DONE_APPT` | Access to the realization of the appointment. |
| `CALLCENTER_DECLARE_ACHIEVED` | Allows declaring and modifying realized appointments. |
| `CALLCENTER_COPY_APPT` | Copy an appointment. |
| `CALLCENTER_CONFIRM_APPT` | Confirm an appointment. |
| `CALLCENTER_CHANGE_APPT_ADDRESS` | Allows changing the appointment address. |
| `CALLCENTER_CANCEL_APPT` | Cancel an appointment. |
| `CALLCENTER_ACCEPT_APPOINTMENT` | Accept an appointment. |

### Appointment list

| Right | Description |
| --- | --- |
| `CALLCENTER_UNPLAN_LIST` | Allows switching a list of appointments to the suspended status. |
| `CALLCENTER_UNCANCEL_LIST` | Allows switching a list of appointments to the requested status. |
| `CALLCENTER_SUSPEND_LIST` | Allows switching a list of appointments to the suspended status. |
| `CALLCENTER_SEARCH_UNPLANNED_APPT` | Access to searching for unplanned appointments. |
| `CALLCENTER_SEARCH_RESERVED_APPT` | Access to searching for reserved appointments. |
| `CALLCENTER_SEARCH_REQUESTED_APPT` | Access to searching for requested appointments. |
| `CALLCENTER_SEARCH_PLANNED_APPT` | Access to searching for planned appointments. |
| `CALLCENTER_SEARCH_EXTERNALIZED_APPT` | Subcontracted appointment. |
| `CALLCENTER_SEARCH_CONFIRMED_APPT` | Access to searching for confirmed appointments. |
| `CALLCENTER_SEARCH_CHAIN_CONSTRAINT` | Access to searching for chaining constraints. |
| `CALLCENTER_SEARCH_APPT` | Access to searching for appointments. |
| `CALLCENTER_SEARCH_ACCEPTED_APPT` | Access to searching for accepted appointments. |
| `CALLCENTER_RESERV_LIST` | Allows switching a list of appointments to the reserved status. |
| `CALLCENTER_REALIZE_LIST` | Allows switching a list of appointments to the realized status. |
| `CALLCENTER_REACTIVATE_LIST` | Allows switching a list of appointments to the requested status. |
| `CALLCENTER_PLANSUGGEST_LIST` | Allows switching a list of appointments to the planned status. |
| `CALLCENTER_PLAN_LIST` | Allows planning a list of appointments. |
| `CALLCENTER_INCREASE_PLANNED_DATE_LIST` | Allows postponing the planned date for a list of appointments. |
| `CALLCENTER_INCREASE_DATE_MIN_BEGIN_LIST` | Allows postponing the earliest date for a list of appointments. |
| `CALLCENTER_INCREASE_DATE_MAX_END_LIST` | Allows postponing the latest date for a list of appointments. |
| `CALLCENTER_DECREASE_PLANNED_DATE_LIST` | Allows bringing forward the planned date for a list of appointments. |
| `CALLCENTER_DECREASE_DATE_MIN_BEGIN_LIST` | Allows bringing forward the earliest date for a list of appointments. |
| `CALLCENTER_DECREASE_DATE_MAX_END_LIST` | Allows bringing forward the latest date for a list of appointments. |
| `CALLCENTER_CONFIRM_LIST` | Allows switching a list of appointments to the confirmed status. |
| `CALLCENTER_CHANGE_WORKSITE_LIST` | Allows changing the worksite for a list of appointments. |
| `CALLCENTER_CHANGE_RESOURCES_LIST` | Allows changing the resources for a list of appointments. |
| `CALLCENTER_CHANGE_QUANTITIES_LIST` | Allows changing the Quantities fields for a list of appointments. |
| `CALLCENTER_CHANGE_PRIORITY_LIST` | Allows changing the priority for a list of appointments. |
| `CALLCENTER_CHANGE_LOGICALS_LIST` | Allows changing the Logicals fields for a list of appointments. |
| `CALLCENTER_CHANGE_FILLERS_LIST` | Allows changing the Fillers fields for a list of appointments. |
| `CALLCENTER_CHANGE_DATES_TIMES_LIST` | Allows changing the latest and earliest date and time for a list of appointments. |
| `CALLCENTER_CHANGE_DATE_MIN_BEGIN_LIST` | Allows changing the earliest date for a list of appointments. |
| `CALLCENTER_CHANGE_DATE_MAX_END_LIST` | Allows changing the latest date for a list of appointments. |
| `CALLCENTER_CHANGE_ADDITIONALDATES_LIST` | Allows changing the Additional dates fields for a list of appointments. |
| `CALLCENTER_CANCEL_LIST` | Allows switching a list of appointments to the cancelled status. |
| `CALLCENTER_APPOINTMENT_LIST_MYSEARCH9` | Access to the appointment list mySearch 9. |
| `CALLCENTER_APPOINTMENT_LIST_MYSEARCH8` | Access to the appointment list mySearch 8. |
| `CALLCENTER_APPOINTMENT_LIST_MYSEARCH7` | Access to the appointment list mySearch 7. |
| `CALLCENTER_APPOINTMENT_LIST_MYSEARCH6` | Access to the appointment list mySearch 6. |
| `CALLCENTER_APPOINTMENT_LIST_MYSEARCH5` | Access to the appointment list mySearch 5. |
| `CALLCENTER_APPOINTMENT_LIST_MYSEARCH4` | Access to the appointment list mySearch 4. |
| `CALLCENTER_APPOINTMENT_LIST_MYSEARCH3` | Access to the appointment list mySearch 3. |
| `CALLCENTER_APPOINTMENT_LIST_MYSEARCH2` | Access to the appointment list mySearch 2. |
| `CALLCENTER_APPOINTMENT_LIST_MYSEARCH15` | Access to the appointment list mySearch 15. |
| `CALLCENTER_APPOINTMENT_LIST_MYSEARCH14` | Access to the appointment list mySearch 14. |
| `CALLCENTER_APPOINTMENT_LIST_MYSEARCH13` | Access to the appointment list mySearch 13. |
| `CALLCENTER_APPOINTMENT_LIST_MYSEARCH12` | Access to the appointment list mySearch 12. |
| `CALLCENTER_APPOINTMENT_LIST_MYSEARCH11` | Access to the appointment list mySearch 11. |
| `CALLCENTER_APPOINTMENT_LIST_MYSEARCH10` | Access to the appointment list mySearch 10. |
| `CALLCENTER_APPOINTMENT_LIST_MYSEARCH1` | Access to the appointment list mySearch 1. |
| `CALLCENTER_APPOINTMENT_ALERT_LIST_TROUBLESHOOTING` | Access right to the list of troubleshooting task alerts. |
| `CALLCENTER_APPOINTMENT_ALERT_LIST_CUSTOMER_GAP` | Access right to the list of customer gap alerts. |
| `CALLCENTER_APPOINTMENT_ALERT_LIST_BIG_ROUTE_DURATION` | Access right to the list of travel duration alerts. |
| `CALLCENTER_APPOINTMENT_ALERT_LIST_APPOINTMENT_TO_REPLAN` | Access right to the list of alerts for appointments to replan. |
| `CALLCENTER_APPOINTMENT_ALERT_LIST` | Access right to the list of task alerts. |
| `CALLCENTER_ADD_CONSTRAINT_LIST` | Allows creating a chaining constraint for a list of appointments. |
| `CALLCENTER_ACCEPT_LIST` | Allows changing the status to accepted for a list of appointments. |

### Planning

| Right | Description |
| --- | --- |
| `CALLCENTER_VISITS_TOO_FREQUENT` | Allows visits that are too frequent. |
| `CALLCENTER_SCHEDULE_APPT_AS_PLANNED` | Allows placing an appointment in the planned status. |
| `CALLCENTER_RESCHEDULE_COLLECTION_OF_APPOINTMENT` | Allows resuming the planning of one or more days. |
| `CALLCENTER_REOPTIM_WEEK` | Allows optimizing a week. |
| `CALLCENTER_REOPTIM_DAY` | Allows optimizing a day. |
| `CALLCENTER_REALTIME_TIMEGRID_MODE` | Allows displaying the real-time optimization solutions in grid mode. |
| `CALLCENTER_REALTIME_OPTIM_IGNORE_HR_CONSTRAINTS` | Allows real-time optimization of visits by resources that are neither required nor preferred. |
| `CALLCENTER_POST_OPTIM_SUSPEND_APP` | Allows switching to the suspended status an appointment for which the real-time optimization found no solution. |
| `CALLCENTER_POST_OPTIM_IMPOSE_APP` | Manual appointment booking after an optimization. |
| `CALLCENTER_PLAN_APPT` | Plan an appointment. |
| `CALLCENTER_OPTIM_APP` | Allows planning appointments with real-time optimization. |
| `CALLCENTER_MODIFY_AGENDA_CONTROLLED_DATES_VALIDATION` | Allows modifying the validation data for locked days. |
| `CALLCENTER_MODIFY_AGENDA_CONTROLLED_DATES_ENTRY` | Allows modifying the validation request data for locked days. |
| `CALLCENTER_MANUAL_OPTIM_IGNORE_HR_WORKSITE` | Allows manual planning of visits by resources that are not assigned to the worksite of the visit. |
| `CALLCENTER_MANUAL_OPTIM_IGNORE_HR_CONSTRAINTS` | Allows manual planning of visits by resources that are neither required nor preferred. |
| `CALLCENTER_MANAGE_AGENDA_MARKERS` | Access to markers. |
| `CALLCENTER_MANAGE_AGENDA_CONTROLLED_DATES` | Access to managing locked days. |
| `CALLCENTER_IMPOSE_APP_IGNORE_SKILLS` | Allows manually booking an appointment for a resource who does not have the required skills. |
| `CALLCENTER_IMPOSE_APP` | Plan an appointment manually. |
| `CALLCENTER_FORCE_IMPOSE_APP` | Plan an appointment manually, violating constraints. |
| `CALLCENTER_FILL_PLANNING` | Fill a resource's planning with requested or unplanned appointments. |
| `CALLCENTER_CAN_VALIDATE_AGENDA_CONTROLLED_DATE` | Allows setting locked days to the VALIDATED status. |
| `CALLCENTER_CAN_TAKE_APPOINTMENT_WITH_OPTIM_PARAMETERS_NAMED` | Allows booking appointments with the named optimization parameter configurations. |
| `CALLCENTER_CAN_REQUEST_AGENDA_CONTROLLED_DATE` | Allows setting locked days to the REQUESTED status. |
| `CALLCENTER_CAN_REFUSE_AGENDA_CONTROLLED_DATE` | Allows setting locked days to the REFUSED status. |
| `CALLCENTER_CAN_PLACEONDISABLED_DATES` | Allows planning during time outside the constrained dates. |
| `CALLCENTER_CAN_FORCE_MAX_WORK_TIME_OF_WEEK` | Allows exceeding the maximum working time of a week. |
| `CALLCENTER_CAN_FORCE_MAX_WORK_TIME_OF_DAY` | Allows exceeding the maximum working time of a day. |
| `CALLCENTER_CAN_FORCE_MAX_MOVE_TIME_OF_WEEK` | Allows exceeding the maximum travel distance of a week. |
| `CALLCENTER_CAN_FORCE_MAX_MOVE_TIME_OF_DAY` | Allows exceeding the maximum travel distance of a day. |

### Interactions with the schedule

| Right | Description |
| --- | --- |
| `CALLCENTER_INPLANNING_UNPLAN_REALIZED_APPT` | Allows unplanning fully or partially realized appointments from the planning view. |
| `CALLCENTER_INPLANNING_UNPLAN_APPT` | Allows suspending appointments (switching to the suspended status) from the plannings. |
| `CALLCENTER_INPLANNING_UNDO_APP` | Allows undoing the realization of a realized appointment. |
| `CALLCENTER_INPLANNING_UNCONFIRM_EXCEPTIONAL_LOCATIONS` | Allows unconfirming exceptional locations in the planning view. |
| `CALLCENTER_INPLANNING_UNCONFIRM_APPT` | Allows unconfirming appointments (switching to the planned status) in the plannings. |
| `CALLCENTER_INPLANNING_SUSPEND_APPT` | Allows suspending appointments (switching to the suspended status) from the plannings. |
| `CALLCENTER_INPLANNING_RESET_STANDARD_DAY` | Allows resetting a day to its standard value when a specific type is applied to it. |
| `CALLCENTER_INPLANNING_RESERV_APPT` | Allows reserving appointments (switching to the reserved status) from the plannings. |
| `CALLCENTER_INPLANNING_REMOVE_UNAVAILABILITY` | Allows deleting unavailabilities from the plannings. |
| `CALLCENTER_INPLANNING_REMOVE_EXCEPTIONAL_LOCATION` | Allows deleting exceptional locations in the plannings. |
| `CALLCENTER_INPLANNING_REMOVE_APPT` | Allows deleting appointments (switching to the cancelled status) from the plannings. |
| `CALLCENTER_INPLANNING_REACTIV_APPT` | Re-activation of appointments from the plannings (return to the requested status). |
| `CALLCENTER_INPLANNING_MOVE_UNAVAILABILITY` | Allows moving unavailabilities from the plannings. |
| `CALLCENTER_INPLANNING_MOVE_MARKER` | Allows moving markers in the plannings. |
| `CALLCENTER_INPLANNING_MOVE_APPT` | Allows moving appointments from the plannings. |
| `CALLCENTER_INPLANNING_MODIFY_UNAVAILABILITY_DURATION` | Allows modifying the duration of unavailabilities in the plannings. |
| `CALLCENTER_INPLANNING_MODIFY_MARKER_DURATION` | Allows modifying the duration of markers in the plannings. |
| `CALLCENTER_INPLANNING_MODIFY_EXCEPTIONAL_LOCATION` | Allows modifying the duration of exceptional locations in the plannings. |
| `CALLCENTER_INPLANNING_MODIFY_APPT_DURATION` | Allows modifying the duration of appointments from the plannings. |
| `CALLCENTER_INPLANNING_CREATE_EXCEPTIONAL_LOCATION` | Allows creating exceptional locations in the planning view. |
| `CALLCENTER_INPLANNING_CONFIRM_EXCEPTIONAL_LOCATIONS` | Allows confirming exceptional locations in the planning view. |
| `CALLCENTER_INPLANNING_CONFIRM_APPT` | Allows confirming appointments (switching to the confirmed status) from the plannings. |
| `CALLCENTER_INPLANNING_APP_PANEL` | Access to the appointment basket in the plannings. |
| `CALLCENTER_INPLANNING_ADD_BY_DRAG_EXCEPTIONAL_LOCATION` | Allows creating an exceptional location by drag and drop in the plannings. |
| `CALLCENTER_INPLANNING_ACCEPT_APPT` | Accept appointments in the plannings. |

### Schedule

| Right | Description |
| --- | --- |
| `CALLCENTER_WORKSITE_PLANNING_SECOND` | Includes the resources for which the worksite specified for the worksite planning is a secondary worksite. |
| `CALLCENTER_WORKSITE_PLANNING_FIRST` | Includes the resources whose main worksite is the worksite specified for the worksite planning. |
| `CALLCENTER_WORKSITE_PLANNING_EXECUTING` | Includes the resources that perform an appointment at the worksite specified for the worksite planning. |
| `CALLCENTER_WORKSITE_PLANNING` | Access to the worksite planning. |
| `CALLCENTER_WEEK_PLANNING` | Access to the week planning. |
| `CALLCENTER_VIEW_CHARGE_PLANNING` | Access to the workload plannings. |
| `CALLCENTER_VIEW_AREA_BY_WORKSITE_PLANNING` | Access to the area plannings by worksite. |
| `CALLCENTER_VEHICLE_PLANNING` | Access to the display of tracked vehicles. |
| `CALLCENTER_TEAM_PLANNING` | Access to the team planning. |
| `CALLCENTER_ROTATE_PLANNING` | Access to the button that switches the schedule between horizontal and vertical display. |
| `CALLCENTER_PLANNING_NO_HOURS` | Displays the plannings without showing the hours. |
| `CALLCENTER_PLANNING_DISPLAY_MARKERS` | Display markers in the Planning module schedule. |
| `CALLCENTER_PLANNING` | Access to the plannings. |
| `CALLCENTER_NONMOBILE_RESOURCE_PLANNING` | Access to the planning of non-mobile resources in the Planning module. |
| `CALLCENTER_MULTI_PLANNING` | Access to multi-resource plannings. |
| `CALLCENTER_MONTH_PLANNING` | Access to the month planning. |
| `CALLCENTER_HIDE_PERSONAL_ADDRESS` | Hide the personal addresses of resources in the map, the planning and the forms. |
| `CALLCENTER_AREA_PLANNING` | Access to the area planning. |

### Communication

| Right | Description |
| --- | --- |
| `CALLCENTER_VIEW_WAYBILL` | Allows access to the waybill. |
| `CALLCENTER_VIEW_MESSAGE` | Allows displaying messages. |
| `CALLCENTER_TEAMS_WAYBILL` | Access to the waybill of the teams. |
| `CALLCENTER_SHOW_CUSTOM_EXPORT` | Access to the custom exports page. |
| `CALLCENTER_SEND_WEEK_NOTIFICATIONS` | Allows sending notifications of the weekly appointments. |
| `CALLCENTER_SEND_APPOINTMENT_NOTIFICATION` | Allows sending the notification of an appointment. |
| `CALLCENTER_SEND_APPOINTMENT_ANNOUNCE` | Allows sending an appointment announcement. |
| `CALLCENTER_MANAGE_NOTIFIABLES` | Allows displaying and updating the Notifiable property of resources. |
| `CALLCENTER_EXPORT_CSV` | Allows exporting tables in CSV format. |
| `CALLCENTER_CREATE_MESSAGE` | Allows creating messages. |

### Mapping

| Right | Description |
| --- | --- |
| `CALLCENTER_VIEW_MAP_ACTIVITIES` | Access to the activities map. |
| `CALLCENTER_VIEW_MAP` | Gives access to the map view. |
| `CALLCENTER_SHOW_SEARCHAROUNDPAGE` | Access to the nearby search page. |
| `CALLCENTER_SHOW_ITIPAGE` | Access to the itinerary calculation page. |
| `CALLCENTER_PICK_COORDINATES` | Access to the coordinate conversion page. |

### Overnight stay

| Right | Description |
| --- | --- |
| `CALLCENTER_VIEW_BUSINESS_LOCATIONS_PREFERENCES` | Allows viewing the business location preferences. |
| `CALLCENTER_UNCONFIRM_EXCEPTIONAL_LOCATIONS` | Allows unconfirming exceptional locations. |
| `CALLCENTER_SUGGEST_EXCEPTIONAL_LOCATIONS` | Right to display the button that suggests overnight stays. |
| `CALLCENTER_REMOVE_EXCEPTIONAL_LOCATION` | Allows deleting exceptional locations. |
| `CALLCENTER_MODIFY_EXCEPTIONAL_LOCATION` | Allows updating exceptional locations. |
| `CALLCENTER_MANAGE_EXCEPTIONAL_LOCATION` | Access to managing exceptional locations. |
| `CALLCENTER_MANAGE_BUSINESS_LOCATIONS` | Access to managing business locations (hotels, and so on). |
| `CALLCENTER_FORCE_EXCEPTIONAL_LOCATIONS` | Right to force the creation or deletion of overnight stays. |
| `CALLCENTER_CREATE_EXCEPTIONAL_LOCATION` | Allows creating exceptional locations. |
| `CALLCENTER_CONFIRM_EXCEPTIONAL_LOCATIONS` | Allows confirming exceptional locations. |

### Real-time tracking

| Right | Description |
| --- | --- |
| `CALLCENTER_VEHICLE_TRACKING_ANALYZE` | Access to the vehicle tracking analysis page. |
| `CALLCENTER_VEHICLE_TRACKING` | Access to vehicle tracking. |
| `CALLCENTER_SHOW_TRAFFIC_PATTERN` | Makes the road traffic statistics page accessible. |

### Resource management

| Right | Description |
| --- | --- |
| `CALLCENTER_VIEW_SECONDARY_WORKSITE_ASSIGNMENTS` | Allows viewing the assignments to a secondary worksite. |
| `CALLCENTER_VIEW_RESOURCE_CUSTOMERS` | Allows displaying the customers and assignments (required, preferred, and so on) of a resource. |
| `CALLCENTER_VIEW_JOBS` | Allows displaying the job types. |
| `CALLCENTER_VIEW_DUTIES` | Allows access to on-call duties. |
| `CALLCENTER_UPDATE_SECONDARY_WORKSITE_ASSIGNMENTS` | Allows updating the assignments to a secondary worksite. |
| `CALLCENTER_UPDATE_JOBS` | Allows modifying jobs. |
| `CALLCENTER_UPDATE_DUTIES` | Allows modifying on-call duties. |
| `CALLCENTER_MANAGE_SUPPLIES` | Allows listing supplies and assigning them to resources for a specific period. |
| `CALLCENTER_MANAGE_SECTORS` | Allows managing sectors. |

### Unavailabilities

| Right | Description |
| --- | --- |
| `CALLCENTER_VIEW_UNAVAILABILITY_PREFERENCES` | Allows viewing the unavailability preferences. |
| `CALLCENTER_UNAVAILABILITY_ADD_FORCE` | Forces unavailabilities to overlap with other unavailabilities. |
| `CALLCENTER_TAKE_UNAVAILABILITY` | Allows managing unavailabilities. |
| `CALLCENTER_SEARCH_UNAVAILABILITY` | Access to searching for unavailabilities. |
| `CALLCENTER_REFUSE_LIST_UNAVAILABILITY` | Allows switching a list of unavailabilities to the refused status. |
| `CALLCENTER_EXPRESS_UNAVAILABILITY` | Access to express unavailability entry. |
| `CALLCENTER_EDIT_ALL_UNAVAILABILITY` | Allows editing all types of unavailabilities. |
| `CALLCENTER_ACCEPT_LIST_UNAVAILABILITY` | Allows switching a list of unavailabilities to the accepted status. |

### Custom action

| Right | Description |
| --- | --- |
| `CALLCENTER_MYACTION_CUSTOMER_SHEET_5` | Allows seeing the **Custom action 5** button in the customer forms. |
| `CALLCENTER_MYACTION_CUSTOMER_SHEET_4` | Allows seeing the **Custom action 4** button in the customer forms. |
| `CALLCENTER_MYACTION_CUSTOMER_SHEET_3` | Allows seeing the **Custom action 3** button in the customer forms. |
| `CALLCENTER_MYACTION_CUSTOMER_SHEET_2` | Allows seeing the **Custom action 2** button in the customer forms. |
| `CALLCENTER_MYACTION_CUSTOMER_SHEET_1` | Allows seeing the **Custom action 1** button in the customer forms. |
| `CALLCENTER_MYACTION_CUSTOMER_MAP_5` | Allows seeing the **Custom action 5** button in the customer map tooltips. |
| `CALLCENTER_MYACTION_CUSTOMER_MAP_4` | Allows seeing the **Custom action 4** button in the customer map tooltips. |
| `CALLCENTER_MYACTION_CUSTOMER_MAP_3` | Allows seeing the **Custom action 3** button in the customer map tooltips. |
| `CALLCENTER_MYACTION_CUSTOMER_MAP_2` | Allows seeing the **Custom action 2** button in the customer map tooltips. |
| `CALLCENTER_MYACTION_CUSTOMER_MAP_1` | Allows seeing the **Custom action 1** button in the customer map tooltips. |
| `CALLCENTER_MYACTION_CUSTOMER_LIST_COLUMN_5` | Allows seeing the **Custom action 5** button in the customer lists. |
| `CALLCENTER_MYACTION_CUSTOMER_LIST_COLUMN_4` | Allows seeing the **Custom action 4** button in the customer lists. |
| `CALLCENTER_MYACTION_CUSTOMER_LIST_COLUMN_3` | Allows seeing the **Custom action 3** button in the customer lists. |
| `CALLCENTER_MYACTION_CUSTOMER_LIST_COLUMN_2` | Allows seeing the **Custom action 2** button in the customer lists. |
| `CALLCENTER_MYACTION_CUSTOMER_LIST_COLUMN_1` | Allows seeing the **Custom action 1** button in the customer lists. |
| `CALLCENTER_MYACTION_CUSTOMER_LIST_5` | Allows seeing the **Custom action 5** button in the action buttons of the customer lists. |
| `CALLCENTER_MYACTION_CUSTOMER_LIST_4` | Allows seeing the **Custom action 4** button in the action buttons of the customer lists. |
| `CALLCENTER_MYACTION_CUSTOMER_LIST_3` | Allows seeing the **Custom action 3** button in the action buttons of the customer lists. |
| `CALLCENTER_MYACTION_CUSTOMER_LIST_2` | Allows seeing the **Custom action 2** button in the action buttons of the customer lists. |
| `CALLCENTER_MYACTION_CUSTOMER_LIST_1` | Allows seeing the **Custom action 1** button in the action buttons of the customer lists. |
| `CALLCENTER_MYACTION_APPOINTMENT_SHEET_5` | Allows seeing the **Custom action 5** button in the appointment forms. |
| `CALLCENTER_MYACTION_APPOINTMENT_SHEET_4` | Allows seeing the **Custom action 4** button in the appointment forms. |
| `CALLCENTER_MYACTION_APPOINTMENT_SHEET_3` | Allows seeing the **Custom action 3** button in the appointment forms. |
| `CALLCENTER_MYACTION_APPOINTMENT_SHEET_2` | Allows seeing the **Custom action 2** button in the appointment forms. |
| `CALLCENTER_MYACTION_APPOINTMENT_SHEET_1` | Allows seeing the **Custom action 1** button in the appointment forms. |
| `CALLCENTER_MYACTION_APPOINTMENT_PLANNING_TOOLTIP_5` | Allows seeing the **Custom action 5** button in the planning tooltips. |
| `CALLCENTER_MYACTION_APPOINTMENT_PLANNING_TOOLTIP_4` | Allows seeing the **Custom action 4** button in the planning tooltips. |
| `CALLCENTER_MYACTION_APPOINTMENT_PLANNING_TOOLTIP_3` | Allows seeing the **Custom action 3** button in the planning tooltips. |
| `CALLCENTER_MYACTION_APPOINTMENT_PLANNING_TOOLTIP_2` | Allows seeing the **Custom action 2** button in the planning tooltips. |
| `CALLCENTER_MYACTION_APPOINTMENT_PLANNING_TOOLTIP_1` | Allows seeing the **Custom action 1** button in the planning tooltips. |
| `CALLCENTER_MYACTION_APPOINTMENT_MAP_5` | Allows seeing the **Custom action 5** button in the map tooltips. |
| `CALLCENTER_MYACTION_APPOINTMENT_MAP_4` | Allows seeing the **Custom action 4** button in the map tooltips. |
| `CALLCENTER_MYACTION_APPOINTMENT_MAP_3` | Allows seeing the **Custom action 3** button in the map tooltips. |
| `CALLCENTER_MYACTION_APPOINTMENT_MAP_2` | Allows seeing the **Custom action 2** button in the map tooltips. |
| `CALLCENTER_MYACTION_APPOINTMENT_MAP_1` | Allows seeing the **Custom action 1** button in the map tooltips. |
| `CALLCENTER_MYACTION_APPOINTMENT_LIST_COLUMN_5` | Allows seeing the **Custom action 5** button in the appointment lists. |
| `CALLCENTER_MYACTION_APPOINTMENT_LIST_COLUMN_4` | Allows seeing the **Custom action 4** button in the appointment lists. |
| `CALLCENTER_MYACTION_APPOINTMENT_LIST_COLUMN_3` | Allows seeing the **Custom action 3** button in the appointment lists. |
| `CALLCENTER_MYACTION_APPOINTMENT_LIST_COLUMN_2` | Allows seeing the **Custom action 2** button in the appointment lists. |
| `CALLCENTER_MYACTION_APPOINTMENT_LIST_COLUMN_1` | Allows seeing the **Custom action 1** button in the appointment lists. |
| `CALLCENTER_MYACTION_APPOINTMENT_LIST_5` | Allows seeing the **Custom action 5** button in the action buttons of the appointment lists. |
| `CALLCENTER_MYACTION_APPOINTMENT_LIST_4` | Allows seeing the **Custom action 4** button in the action buttons of the appointment lists. |
| `CALLCENTER_MYACTION_APPOINTMENT_LIST_3` | Allows seeing the **Custom action 3** button in the action buttons of the appointment lists. |
| `CALLCENTER_MYACTION_APPOINTMENT_LIST_2` | Allows seeing the **Custom action 2** button in the action buttons of the appointment lists. |
| `CALLCENTER_MYACTION_APPOINTMENT_LIST_1` | Allows seeing the **Custom action 1** button in the action buttons of the appointment lists. |

### Other

| Right | Description |
| --- | --- |
| `CALLCENTER_VIEW_APPLICATION_LOG` | Allows access to the list of application events. |
| `CALLCENTER_SQL_QUERY_TOOL` | Allows using predefined SQL query files. |
| `CALLCENTER_SEND_TO_SUBCONTRACTOR` | Allows sending an appointment to a subcontractor. |
| `CALLCENTER_SEND_LIST_TO_SUBCONTRACTOR` | Allows sending a list of appointments to a subcontractor. |
| `CALLCENTER_PASSWORD_CHANGE` | Allows the current user to change their password. |
| `CALLCENTER_MESSAGE_ALERT_LIST` | Access to the list of alert messages. |
| `CALLCENTER_HIDE_APPOINTMENT_MODIFY_PAGE` | Prevents access to the appointment edit page or wizard when the `APPOINTMENT_MODIFY` right is enabled, to restrict editing to the fields of the main form. |

## Supervisor

### Scope

| Right | Description |
| --- | --- |
| `SUPERVISOR_MANAGE_OWN_TEAM` | Allows managing the resources of the user's own team. |
| `SUPERVISOR_MANAGE_OWN_DOMAIN` | Allows managing the areas of the user's own domain. |
| `SUPERVISOR_MANAGE_OWN_AREA` | Right to manage the user's own area. |
| `SUPERVISOR_MANAGE_ALL_AREAS` | Access to all areas. |
| `SUPERVISOR_GUEST` | Access to the Supervisor module. |
| `SUPERVISOR_CHANGE_AREA` | Allows changing the area of the active module. |

### Control

| Right | Description |
| --- | --- |
| `SUPERVISOR_OVERTIMES` | Access to the overtime dashboard. |
| `SUPERVISOR_JOURNAL` | Access to viewing the appointment modification journal. |
| `SUPERVISOR_GLOBAL_PLANNING_UNAVAILABILITIES` | Access to the global unavailability planning. |
| `SUPERVISOR_ACHIEVEMENT_DATES` | Access to the fulfilment dates dashboard. |

### Statistics

| Right | Description |
| --- | --- |
| `SUPERVISOR_QUANTITY` | Access to the dashboard of appointment booking quantities. |
| `SUPERVISOR_QUALITY` | Access to the dashboard of appointment booking quality. |
| `SUPERVISOR_OBJECTIVE` | Access to the objectives dashboard. |
| `SUPERVISOR_INTERVENTIONS` | Access to the tasks dashboard. |
| `SUPERVISOR_AVAILABILITY` | Access to the availability dashboard. |

### Other

| Right | Description |
| --- | --- |
| `SUPERVISOR_INTER_CUSTOMER_DISTANCES` | Access to the inter-customer proximity dashboard. |
| `SUPERVISOR_CUSTOMER_DISTANCES` | Access to the customer distance matrix dashboard. |
| `SUPERVISOR_CUSTOMER_BARYCENTERS` | Access to the customer barycenter dashboard. |

## Attendance

### Scope

| Right | Description |
| --- | --- |
| `ATTENDANCEMANAGER_UPDATE_RESOURCEUSERLISTS` | Access to modifying a resource list in the interface. |
| `ATTENDANCEMANAGER_SHOW_WORKSITES` | Allows selecting a worksite in the interface. |
| `ATTENDANCEMANAGER_SHOW_TEAMS` | Allows selecting a team in the interface. |
| `ATTENDANCEMANAGER_SHOW_RESOURCEUSERLISTS` | Access to selecting a resource list in the interface. |
| `ATTENDANCEMANAGER_SHOW_AREA` | Allows selecting the current area in the interface. All or some of the `ATTENDANCEMANAGER_SHOW_WORKSITES` and `ATTENDANCEMANAGER_SHOW_TEAMS` rights must also be granted to access the module. |
| `ATTENDANCEMANAGER_MANAGE_PERIMETER` | Allows managing the scope. |
| `ATTENDANCEMANAGER_MANAGE_OWN_WORKSITE` | Access to the user's own worksite. |
| `ATTENDANCEMANAGER_MANAGE_OWN_TEAM` | Access to the user's own team. |
| `ATTENDANCEMANAGER_MANAGE_OWN_DOMAIN` | Access to the areas of the user's own domain. |
| `ATTENDANCEMANAGER_MANAGE_OWN_AREA` | Access to the user's own area. |
| `ATTENDANCEMANAGER_GUEST` | Access to the Attendance module. All or some of the `ATTENDANCEMANAGER_SHOW_WORKSITES` and `ATTENDANCEMANAGER_SHOW_TEAMS` rights must also be granted to access the module. |
| `ATTENDANCEMANAGER_DELETE_RESOURCEUSERLISTS` | Access to deleting a resource list in the interface. |
| `ATTENDANCEMANAGER_CREATE_RESOURCEUSERLISTS` | Access to creating a resource list in the interface. |

### Job

| Right | Description |
| --- | --- |
| `ATTENDANCEMANAGER_VIEW_JOBTYPE` | Allows displaying the job types. |
| `ATTENDANCEMANAGER_VIEW_JOB` | Allows displaying the job types. |
| `ATTENDANCEMANAGER_UPDATE_JOB` | Allows modifying jobs. |
| `ATTENDANCEMANAGER_DELETE_JOB` | Allows deleting jobs. |
| `ATTENDANCEMANAGER_CREATE_JOB` | Allows creating jobs. |

### On-call day

| Right | Description |
| --- | --- |
| `ATTENDANCEMANAGER_VIEW_DUTYTYPE` | Allows displaying the on-call templates. |
| `ATTENDANCEMANAGER_VIEW_DUTY` | Allows displaying on-call duties. |
| `ATTENDANCEMANAGER_UPDATE_DUTY` | Allows modifying on-call duties. |
| `ATTENDANCEMANAGER_DELETE_DUTY` | Allows deleting on-call duties. |
| `ATTENDANCEMANAGER_CREATE_DUTY` | Allows creating on-call duties. |

### On-call week

| Right | Description |
| --- | --- |
| `ATTENDANCEMANAGER_VIEW_DUTYWEEKTYPE` | Allows displaying the on-call week templates. |
| `ATTENDANCEMANAGER_VIEW_DUTYWEEK` | Allows displaying on-call weeks. |
| `ATTENDANCEMANAGER_UPDATE_DUTYWEEK` | Allows modifying on-call weeks. |
| `ATTENDANCEMANAGER_DELETE_DUTYWEEK` | Allows deleting on-call weeks. |
| `ATTENDANCEMANAGER_CREATE_DUTYWEEK` | Allows creating on-call weeks. |

### Unavailability

| Right | Description |
| --- | --- |
| `ATTENDANCEMANAGER_VIEW_UNAVAILABILITYTYPE` | Allows displaying the unavailability types. |
| `ATTENDANCEMANAGER_VIEW_UNAVAILABILITY` | Allows displaying unavailabilities. |
| `ATTENDANCEMANAGER_UPDATE_UNAVAILABILITY` | Allows modifying unavailabilities. |
| `ATTENDANCEMANAGER_DELETE_UNAVAILABILITY` | Allows deleting unavailabilities. |
| `ATTENDANCEMANAGER_CREATE_UNAVAILABILITY` | Allows creating unavailabilities. |

### Marker

| Right | Description |
| --- | --- |
| `ATTENDANCEMANAGER_VIEW_AGENDAMARKERKIND` | Allows displaying the marker kinds. |
| `ATTENDANCEMANAGER_VIEW_AGENDAMARKER` | Allows displaying markers. |
| `ATTENDANCEMANAGER_UPDATE_AGENDAMARKER` | Allows modifying markers. |
| `ATTENDANCEMANAGER_PLANNING_DISPLAY_MARKERS` | Do not display the markers in the planning. |
| `ATTENDANCEMANAGER_DELETE_AGENDAMARKER` | Allows deleting markers. |
| `ATTENDANCEMANAGER_CREATE_AGENDAMARKER` | Allows creating markers. |

### Worked day

| Right | Description |
| --- | --- |
| `ATTENDANCEMANAGER_VIEW_WORKEDDAYTYPE` | Allows displaying the worked day templates. |
| `ATTENDANCEMANAGER_VIEW_WORKEDDAY` | Allows displaying worked days. |
| `ATTENDANCEMANAGER_UPDATE_WORKEDDAY` | Allows modifying worked days. |
| `ATTENDANCEMANAGER_DELETE_WORKEDDAY` | Allows deleting worked days. |
| `ATTENDANCEMANAGER_CREATE_WORKEDDAY` | Allows creating worked days. |

### Worked week

| Right | Description |
| --- | --- |
| `ATTENDANCEMANAGER_VIEW_WORKEDWEEKTYPE` | Allows displaying the worked week templates. |
| `ATTENDANCEMANAGER_VIEW_WORKEDWEEK` | Allows displaying worked weeks. |
| `ATTENDANCEMANAGER_UPDATE_WORKEDWEEK` | Allows modifying worked weeks. |
| `ATTENDANCEMANAGER_DELETE_WORKEDWEEK` | Allows deleting worked weeks. |
| `ATTENDANCEMANAGER_CREATE_WORKEDWEEK` | Allows creating worked weeks. |

### Reports

| Right | Description |
| --- | --- |
| `ATTENDANCEMANAGER_REPORTS_EXPORTCSV` | Allows exporting the reports as CSV. |
| `ATTENDANCEMANAGER_REPORTS` | Access to the Reports submodule. |

### Printing

| Right | Description |
| --- | --- |
| `ATTENDANCEMANAGER_PRINTSUMMARYPLANNING` | Allows printing the custom report. |
| `ATTENDANCEMANAGER_PRINTAGENDA` | Allows printing a schedule. |

### Communication

| Right | Description |
| --- | --- |
| `ATTENDANCEMANAGER_VIEW_MESSAGE` | Allows displaying messages. |
| `ATTENDANCEMANAGER_CREATE_MESSAGE` | Allows creating messages. |

## Strategic

### Scope

| Right | Description |
| --- | --- |
| `STRATEGIC_PLANNING_GUEST` | Access to the Strategic planning module. |
| `STRATEGIC_MANAGE_OWN_DOMAIN` | Access to the areas of the user's own domain. |
| `STRATEGIC_MANAGE_OWN_AREA` | Access to the user's own area. |
| `STRATEGIC_MANAGE_OWN_WORKSITE` | Access to the user's own worksite. |
| `STRATEGIC_MANAGE_OWN_TEAM` | Access to the user's own team. |

## My application 1

### Scope

| Right | Description |
| --- | --- |
| `MYAPP1_MANAGE_OWN_DOMAIN` | Access to the areas of the user's own domain. |
| `MYAPP1_MANAGE_OWN_AREA` | Access to the user's own area. |
| `MYAPP1_GUEST` | Access to the first custom module. |

## Sectorization

### Scope

| Right | Description |
| --- | --- |
| `DISTRICTING_GUEST` | Access to the Sectorization module. |

## Fulfilment

### Scope

| Right | Description |
| --- | --- |
| `FULFILMENT_GUEST` | Access to the live tracking of fulfilments. |

## Tracking

### Scope

| Right | Description |
| --- | --- |
| `TRACKFLEET_GUEST` | Access to the GC_Location fleet tracking application (Tracking) in OTGS. |

## Administration

### Scope

| Right | Description |
| --- | --- |
| `ADMIN_GUEST` | Access to the Administration module. |
| `ADMIN_SEE_OPTIMIZATION_OF_ALL_AREAS` | View the optimizations for all areas. |
| `ADMIN_MANAGE_OWN_AREA` | Right to manage the user's own area. |
| `ADMIN_MANAGE_OWN_DOMAIN` | Allows managing the areas of the user's own domain. |
| `ADMIN_MANAGE_ALL_AREAS` | Allows managing all areas. |
| `ADMIN_MANAGE_OWN_TEAM` | Allows managing the user's own team. |
| `ADMIN_MANAGE_OWN_WORKSITE` | Allows managing the user's own worksite. |

### Global access

| Right | Description |
| --- | --- |
| `ADMIN_UPDATE` | Allows modification in Administration. |
| `ADMIN_INSERT` | Allows inserting data in Administration. |
| `ADMIN_DELETE` | Allows deleting data in Administration. |
| `ADMIN_RESTRICTED_PROFILE_GRANT` | Allows assigning a restricted profile to any user. |
| `ADMIN_TOOLS` | Access to the administration tools. **Warning:** do not use this right in production. |
| `ADMIN_MOBILITY` | Access to managing mobility devices. |
| `ADMIN_VIEW_REFERENTIAL` | Allows access to the reference data. |
| `ADMIN_DEACTIVATE` | Allows deactivating data in Administration. |
| `ADMIN_VIEW_RIGHTS` | Show the rights. |
| `ADMIN_VIEW_ADDRESSES_STREETVIEW` | Allows access to the Google Street View of an address. |
| `ADMIN_HIDE_INTERNAL_ID` | Hide the internal identifier of entities. |
| `ADMIN_HIDE_EXTREF` | Hide the external reference of entities (usually combined with the automatic assignment of external references). |
| `ADMIN_ADMIN_TOOLS_MAP` | Allows modifying the map coordinates. |

### Human resource

| Right | Description |
| --- | --- |
| `ADMIN_PARTICULAR_DAYS_CREATE` | Allows creating particular days. |
| `ADMIN_VIEW_RESOURCE` | Show the human resources. |
| `ADMIN_CREATE_RESOURCE` | Allows creating a human resource. |
| `ADMIN_UPDATE_RESOURCE` | Allows updating a human resource. |
| `ADMIN_DISABLE_RESOURCE` | Allows deactivating a human resource. |
| `ADMIN_UPDATE_RESOURCE_ADDRESS` | Allows modifying the address of a resource. |
| `ADMIN_UPDATE_RESOURCE_AUTHORIZATION` | Allows modifying the authorizations of resources. |
| `ADMIN_UPDATE_RESOURCE_EXPRESSUNAVAILABILITY` | Allows modifying the express unavailabilities of resources. |
| `ADMIN_UPDATE_RESOURCE_INFO` | Allows modifying the information of resources. |
| `ADMIN_UPDATE_RESOURCE_JOB` | Allows modifying the jobs of resources. |
| `ADMIN_UPDATE_RESOURCE_LIMIT` | Allows modifying the limits of resources. |
| `ADMIN_UPDATE_RESOURCE_PRIORITY` | Allows modifying the priorities of resources. |
| `ADMIN_UPDATE_RESOURCE_SKILL` | Allows modifying the skills of resources. |
| `ADMIN_UPDATE_RESOURCE_USER` | Allows modifying the users of resources. |
| `ADMIN_UPDATE_RESOURCE_WORKEDWEEK` | Allows modifying the standard weeks of resources. |
| `ADMIN_RESOURCE_ASSIGNMENT_UPDATE` | Allows modifying the assignments of a human resource. |
| `ADMIN_VIEW_RESOURCE_ASSIGNMENT` | Allows access to the assignments of resources. |
| `ADMIN_VIEW_RESOURCE_AUTHORIZATIONS` | Allows managing the authorizations of a resource. |
| `ADMIN_VIEW_RESOURCE_EXPRESSUNAVAILABILITY` | Allows managing the express unavailabilities for resources. |
| `ADMIN_VIEW_RESOURCE_JOB` | Allows access to the jobs of resources. |
| `ADMIN_VIEW_RESOURCE_LIMIT` | Allows access to the limits of human resources. |
| `ADMIN_VIEW_RESOURCE_LOCATION` | Allows access to the addresses of resources. |
| `ADMIN_VIEW_RESOURCE_PRIORITIES` | Allows managing the priorities of a resource. |
| `ADMIN_VIEW_RESOURCE_SKILL` | Allows access to the skills of resources. |
| `ADMIN_VIEW_RESOURCE_WORKEDWEEK` | Allows access to the standard weeks of resources. |
| `ADMIN_VIEW_RESOURCE_USERPERIMETER` | Allows managing the scope of a resource. |
| `ADMIN_UPDATE_RESOURCE_USERPERIMETER` | Allows modifying the scope of a resource. |
| `ADMIN_VIEW_RESOURCE_USERS` | Show the user tab of resources. |
| `ADMIN_VIEW_RESOURCE_PREFERENCES` | Allows access to the preferences of resources. |
| `ADMIN_UPDATE_RESOURCE_PREFERENCES` | Allows modifying the preferences of resources. |
| `ADMIN_VIEW_RESOURCE_VEHICLETYPE` | Allows access to the vehicle types of resources. |
| `ADMIN_UPDATE_RESOURCE_VEHICLETYPE` | Allows updating the vehicle type of resources. |
| `ADMIN_ACTIVATE_RESSOURCE` | Allows activating human resources through Administration. |

### Job

| Right | Description |
| --- | --- |
| `ADMIN_VIEW_FUNCTION` | Allows displaying the resource types. |
| `ADMIN_CREATE_FUNCTION` | Allows creating resource types. |
| `ADMIN_UPDATE_FUNCTION` | Allows updating resource types. |
| `ADMIN_DISABLE_FUNCTION` | Allows deactivating resource types. |
| `ADMIN_VIEW_JOB` | Allows displaying the job types. |
| `ADMIN_CREATE_JOB` | Allows creating jobs. |
| `ADMIN_UPDATE_JOB` | Allows modifying jobs. |
| `ADMIN_DISABLE_JOB` | Allows deactivating job types. |

### Team

| Right | Description |
| --- | --- |
| `ADMIN_MANAGE_TEAM_MEMBERS` | Allows managing the composition of teams. |
| `ADMIN_TEAM_LEADER` | Allows managing the team leader. |
| `ADMIN_TEAM_PARENT` | Allows managing the parent team. |
| `ADMIN_VIEW_TEAM` | Show the teams. |
| `ADMIN_CREATE_TEAM` | Allows creating a team. |
| `ADMIN_UPDATE_TEAM` | Allows updating a team. |
| `ADMIN_DISABLE_TEAM` | Allows deactivating a team. |

### Worksite

| Right | Description |
| --- | --- |
| `ADMIN_VIEW_WORKSITE` | Allows access to the worksites. |
| `ADMIN_CREATE_WORKSITE` | Allows creating a worksite. |
| `ADMIN_UPDATE_WORKSITE` | Allows updating a worksite. |
| `ADMIN_DISABLE_WORKSITE` | Allows deactivating a worksite. |

### Domain

| Right | Description |
| --- | --- |
| `ADMIN_VIEW_DOMAIN` | Allows access to the domains. |
| `ADMIN_CREATE_DOMAIN` | Allows creating a domain. |
| `ADMIN_UPDATE_DOMAIN` | Allows updating a domain. |
| `ADMIN_DISABLE_DOMAIN` | Allows deactivating a domain. |

### Subcontractor

| Right | Description |
| --- | --- |
| `ADMIN_VIEW_SUBCONTRACTOR` | Allows displaying subcontractors. |
| `ADMIN_CREATE_SUBCONTRACTOR` | Allows creating subcontractors. |
| `ADMIN_UPDATE_SUBCONTRACTOR` | Allows updating subcontractors. |
| `ADMIN_DISABLE_SUBCONTRACTOR` | Allows deactivating subcontractors. |

### Supplies

| Right | Description |
| --- | --- |
| `ADMIN_VIEW_SUPPLY` | Allows displaying supplies. |
| `ADMIN_CREATE_SUPPLY` | Allows creating supplies. |
| `ADMIN_UPDATE_SUPPLY` | Allows updating supplies. |
| `ADMIN_DISABLE_SUPPLY` | Allows deactivating supplies. |
| `ADMIN_VIEW_SUPPLY_PREFERENCES` | Allows displaying the supply preferences. |
| `ADMIN_UPDATE_SUPPLY_PREFERENCES` | Allows updating the supply preferences. |

### Area

| Right | Description |
| --- | --- |
| `ADMIN_VIEW_AREA` | Allows access to the areas. |
| `ADMIN_CREATE_AREA` | Allows creating an area. |
| `ADMIN_UPDATE_AREA` | Allows updating an area. |
| `ADMIN_DISABLE_AREA` | Allows deactivating an area. |
| `ADMIN_ENABLE_DISABLE_AREA` | Activate or deactivate an area. |

### Sector

| Right | Description |
| --- | --- |
| `ADMIN_VIEW_SECTOR` | Allows access to the sectors. |
| `ADMIN_CREATE_SECTOR` | Allows creating sectors. |
| `ADMIN_UPDATE_SECTOR` | Allows updating sectors. |
| `ADMIN_DISABLE_SECTOR` | Allows deactivating sectors. |

### Unavailability type

| Right | Description |
| --- | --- |
| `ADMIN_VIEW_UNAVAILABILITY_TYPE` | Allows access to the unavailability types. |
| `ADMIN_CREATE_UNAVAILABILITY_TYPE` | Allows creating unavailability types. |
| `ADMIN_UPDATE_UNAVAILABILITY_TYPE` | Allows updating unavailability types. |
| `ADMIN_DISABLE_UNAVAILABILITY_TYPE` | Allows deactivating unavailability types. |
| `ADMIN_VIEW_UNAVAILABILITYTYPE_PREFERENCES` | Allows viewing the unavailability type preferences. |
| `ADMIN_UPDATE_UNAVAILABILITYTYPE_PREFERENCES` | Allows updating the unavailability type preferences. |

### On-call template

| Right | Description |
| --- | --- |
| `ADMIN_VIEW_DUTY_TYPE` | Allows displaying the on-call templates. |
| `ADMIN_CREATE_DUTY_TYPE` | Allows creating on-call templates. |
| `ADMIN_UPDATE_DUTY_TYPE` | Allows updating on-call templates. |
| `ADMIN_DISABLE_DUTY_TYPE` | Allows deactivating on-call templates. |
| `ADMIN_VIEW_DUTYWEEK_TYPE` | Allows displaying the on-call week templates. |
| `ADMIN_CREATE_DUTYWEEK_TYPE` | Allows creating on-call week templates. |
| `ADMIN_UPDATE_DUTYWEEK_TYPE` | Allows updating on-call week templates. |
| `ADMIN_DISABLE_DUTYWEEK_TYPE` | Allows deactivating on-call week templates. |

### Product

| Right | Description |
| --- | --- |
| `ADMIN_VIEW_PRODUCT` | Allows displaying products. |
| `ADMIN_CREATE_PRODUCT` | Allows creating products. |
| `ADMIN_UPDATE_PRODUCT` | Allows updating products. |
| `ADMIN_DISABLE_PRODUCT` | Allows deactivating products. |
| `ADMIN_VIEW_PRODUCT_PREFERENCES` | Allows viewing the product preferences. |
| `ADMIN_UPDATE_PRODUCT_PREFERENCES` | Allows updating the product preferences. |

### Product family

| Right | Description |
| --- | --- |
| `ADMIN_VIEW_PRODUCT_FAMILY` | Allows displaying product families. |
| `ADMIN_CREATE_PRODUCT_FAMILY` | Allows creating product families. |
| `ADMIN_UPDATE_PRODUCT_FAMILY` | Allows updating product families. |
| `ADMIN_DISABLE_PRODUCT_FAMILY` | Allows deactivating product families. |

### Vehicle

| Right | Description |
| --- | --- |
| `ADMIN_VIEW_VEHICLE` | Allows displaying vehicles. |
| `ADMIN_CREATE_VEHICLE` | Allows creating vehicles. |
| `ADMIN_UPDATE_VEHICLE` | Allows updating vehicles. |
| `ADMIN_DISABLE_VEHICLE` | Allows deactivating vehicles. |

### Tracking device

| Right | Description |
| --- | --- |
| `ADMIN_VIEW_TRACKINGDEVICE` | Allows displaying tracking devices. |
| `ADMIN_CREATE_TRACKINGDEVICE` | Allows creating tracking devices. |
| `ADMIN_UPDATE_TRACKINGDEVICE` | Allows updating tracking devices. |
| `ADMIN_DISABLE_TRACKINGDEVICE` | Allows deactivating tracking devices. |

### Vehicle assignment to human resources

| Right | Description |
| --- | --- |
| `ADMIN_VIEW_HR_VEHICLE_ASSIGNMENT` | Allows displaying the assignments of vehicles to resources. |
| `ADMIN_CREATE_HR_VEHICLE_ASSIGNMENT` | Allows creating assignments of vehicles to resources. |
| `ADMIN_UPDATE_HR_VEHICLE_ASSIGNMENT` | Allows updating assignments of vehicles to resources. |
| `ADMIN_DISABLE_HR_VEHICLE_ASSIGNMENT` | Allows unassigning vehicles from resources. |
| `ADMIN_SWAP_HR_VEHICLE_ASSIGNMENT` | Allows swapping the assignments of vehicles to resources. |

### Skill

| Right | Description |
| --- | --- |
| `ADMIN_VIEW_QUALIFICATION` | Allows displaying skills. |
| `ADMIN_CREATE_QUALIFICATION` | Allows creating skills. |
| `ADMIN_UPDATE_QUALIFICATION` | Allows updating skills. |
| `ADMIN_DISABLE_QUALIFICATION` | Allows deactivating skills. |

### Authorization

| Right | Description |
| --- | --- |
| `ADMIN_VIEW_AUTHORIZATION` | Allows access to the authorizations. |
| `ADMIN_CREATE_AUTHORIZATION` | Allows creating authorizations. |
| `ADMIN_UPDATE_AUTHORIZATION` | Allows updating authorizations. |
| `ADMIN_DISABLE_AUTHORIZATION` | Allows deactivating authorizations. |

### Task type

| Right | Description |
| --- | --- |
| `ADMIN_VIEW_TASK_TYPE_GROUP` | Allows access to the task type groups. |
| `ADMIN_CREATE_TASK_TYPE_GROUP` | Allows creating task type groups. |
| `ADMIN_UPDATE_TASK_TYPE_GROUP` | Allows updating task type groups. |
| `ADMIN_DISABLE_TASK_TYPE_GROUP` | Allows deactivating task type groups. |
| `ADMIN_VIEW_TASKTYPE` | Allows displaying the task types and their groups. |
| `ADMIN_CREATE_TASKTYPE` | Allows creating task types. |
| `ADMIN_UPDATE_TASKTYPE` | Allows updating task types. |
| `ADMIN_DISABLE_TASKTYPE` | Allows deactivating task types. |
| `ADMIN_VIEW_TASKTYPE_DETAIL` | Allows access to the task type details. |
| `ADMIN_CREATE_TASKTYPE_DETAIL` | Allows creating task type details. |
| `ADMIN_UPDATE_TASKTYPE_DETAIL` | Allows updating task type details. |
| `ADMIN_DISABLE_TASKTYPE_DETAIL` | Allows deactivating task type details. |

### Objective

| Right | Description |
| --- | --- |
| `ADMIN_VIEW_OBJECTIVE` | Allows access to the objectives. |
| `ADMIN_CREATE_OBJECTIVE` | Allows creating objectives. |
| `ADMIN_UPDATE_OBJECTIVE` | Allows updating objectives. |
| `ADMIN_DISABLE_OBJECTIVE` | Allows deactivating objectives. |

### Activity tracking

| Right | Description |
| --- | --- |
| `ADMIN_VIEW_COMPLETION_TYPE` | Allows access to the fulfilment statuses. |
| `ADMIN_CREATE_COMPLETION_TYPE` | Allows creating fulfilment statuses. |
| `ADMIN_UPDATE_COMPLETION_TYPE` | Allows updating fulfilment statuses. |
| `ADMIN_DISABLE_COMPLETION_TYPE` | Allows deactivating fulfilment statuses. |
| `ADMIN_VIEW_TO_DO_NEXT_TYPE` | Allows access to the follow-up action types. |
| `ADMIN_CREATE_TO_DO_NEXT_TYPE` | Allows creating follow-up action types. |
| `ADMIN_UPDATE_TO_DO_NEXT_TYPE` | Allows updating follow-up action types. |
| `ADMIN_DISABLE_TO_DO_NEXT_TYPE` | Allows deactivating follow-up action types. |

### Calendar

| Right | Description |
| --- | --- |
| `ADMIN_VIEW_OFFDAY_CALENDAR` | Allows displaying the public holiday calendars. |
| `ADMIN_CREATE_OFFDAY_CALENDAR` | Allows creating public holidays. |
| `ADMIN_UPDATE_OFFDAY_CALENDAR` | Allows updating public holidays. |
| `ADMIN_DISABLE_OFFDAY_CALENDAR` | Allows deactivating public holidays. |
| `ADMIN_VIEW_WORKEDDAYTYPE_CALENDAR` | Allows displaying the calendar of day templates. |
| `ADMIN_CREATE_WORKEDDAYTYPE_CALENDAR` | Allows creating standard days. |
| `ADMIN_UPDATE_WORKEDDAYTYPE_CALENDAR` | Allows updating standard days. |
| `ADMIN_DISABLE_WORKEDDAYTYPE_CALENDAR` | Allows deactivating standard days. |
| `ADMIN_VIEW_WORKEDWEEKTYPE_CALENDAR` | Allows displaying the calendar of week templates. |
| `ADMIN_CREATE_WORKEDWEEKTYPE_CALENDAR` | Allows creating standard weeks. |
| `ADMIN_UPDATE_WORKEDWEEKTYPE_CALENDAR` | Allows updating standard weeks. |
| `ADMIN_DISABLE_WORKEDWEEKTYPE_CALENDAR` | Allows deactivating standard weeks. |
| `ADMIN_VIEW_SELLING_PERIOD` | Allows access to the selling periods. |
| `ADMIN_CREATE_SELLING_PERIOD` | Allows creating selling periods. |
| `ADMIN_UPDATE_SELLING_PERIOD` | Allows updating selling periods. |
| `ADMIN_DISABLE_SELLING_PERIOD` | Allows deactivating selling periods. |

### Configuration

| Right | Description |
| --- | --- |
| `ADMIN_CUSTOMIZATION` | Access customization. |
| `ADMIN_XMLFILE_PARAMDEF` | Allows access to importing and exporting the configuration XML file. |
| `ADMIN_XMLFILE_REFERENTIAL` | Allows access to importing the reference data XML files. |
| `ADMIN_XMLFILE_APPT` | Allows access to importing the XML files that create, modify and delete appointments. |
| `ADMIN_XMLFILE_LOG` | Change the logging level. |
| `ADMIN_SYSTEM_INFO` | Allows managing the system information. |
| `ADMIN_PROPERTIES_UPDATE` | Allows updating the properties of resources. |
| `ADMIN_LOGOS_UPDATE` | Allows updating the logos. |

### Optimization

| Right | Description |
| --- | --- |
| `ADMIN_OPTIMIZATION_SERVICE` | Access to the optimization service. |
| `ADMIN_UPDATE_OPTIMIZATION_SERVICE` | Update, stop and start the optimization service. |
| `ADMIN_START_OPTIM_DURING_VALIDITY_PERIOD` | Start a manual optimization during its validity period. |
| `ADMIN_START_OPTIMIZATION_AT_ANY_TIME` | Start a manual optimization at any time. |
| `ADMIN_STOP_AUTOMATIC_OPTIMIZATION` | Stop an automatic optimization. |
| `ADMIN_STOP_MANUAL_OPTIMIZATION` | Stop a manual optimization. |
| `ADMIN_OPTIM_PARAM` | Access to the page for modifying the optimization parameters. |
| `ADMIN_MANAGE_OPTIMIZATION_ON_IDLE` | Allows managing continuous optimization. |
| `ADMIN_MANAGE_PLANNING_FILLER_EMERGENCY` | Allows managing the emergency filling of the planning. |

### Technical exchanges

| Right | Description |
| --- | --- |
| `ADMIN_EXPORT_TOMTOM_OV2_POI` | Allows access to exporting POIs (ov2) to TomTom. |
| `ADMIN_IMPORT_CSV` | Access to the CSV import. |
| `ADMIN_EXPORT_CSV` | Access to the CSV export. |
| `ADMIN_EXTERN_APPLI` | Allows access to the OTGS API documentation pages. |
| `ADMIN_EXTERN_APPLI_TESTMODE` | Allows testing the OTGS API. |

### Exceptional location type

| Right | Description |
| --- | --- |
| `ADMIN_VIEW_EXCEPTLOCATION_TYPE` | Allows displaying the exceptional location types. |
| `ADMIN_CREATE_EXCEPTLOCATION_TYPE` | Allows creating exceptional location types. |
| `ADMIN_UPDATE_EXCEPTLOCATION_TYPE` | Allows updating exceptional location types. |
| `ADMIN_DISABLE_EXCEPTLOCATION_TYPE` | Allows deactivating exceptional location types. |

### Typology

| Right | Description |
| --- | --- |
| `ADMIN_VIEW_TYPOLOGY` | Allows displaying typologies. |
| `ADMIN_CREATE_TYPOLOGY` | Allows creating typologies. |
| `ADMIN_UPDATE_TYPOLOGY` | Allows updating typologies. |
| `ADMIN_DISABLE_TYPOLOGY` | Allows deactivating typologies. |

### Other

| Right | Description |
| --- | --- |
| `ADMIN_UPDATE_LICENSE` | Allows updating the application license. |
| `ADMIN_SHOW_SQL_TOOL` | Allows viewing the SQL queries page. |
| `ADMIN_CAN_DEFINE_COLOR` | Allows updating the colors. |
| `ADMIN_DELETE_DOCUMENTS` | Allows deleting documents. |
| `ADMIN_ADD_DOCUMENTS` | Allows adding documents. |
| `ADMIN_CAN_DEFINE_ENTITYCOLOR` | Allows updating the colors of entities. |

## Documentation

### Scope

| Right | Description |
| --- | --- |
| `DOC_GUEST` | Access to the Documentation module. |
