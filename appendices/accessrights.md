# Access rights

## Overview

This appendix lists the access rights available in NFS, grouped by module and then by theme. Each table gives the identifier of the right and a description of what it allows.

<!-- REVIEW: the source descriptions were written in French and were translated to English; check the UI labels quoted in them (for example Quantities, Logicals, Fillers, Additional dates, Custom action) against the product. -->

## Portal

### Scope

<table data-full-width="true"><thead><tr><th width="460">Right</th><th>Description</th></tr></thead><tbody>
<tr><td><code>PORTAL_SEE_OPTIMIZATION_OF_ALL_AREA</code></td><td>View the optimizations for all areas.</td></tr>
<tr><td><code>PORTAL_MANAGE_OWN_WORKSITE</code></td><td>Access to the user's own worksite.</td></tr>
<tr><td><code>PORTAL_MANAGE_OWN_TEAM</code></td><td>Access to the user's own team.</td></tr>
<tr><td><code>PORTAL_MANAGE_OWN_DOMAIN</code></td><td>Access to the areas of the user's own domain.</td></tr>
<tr><td><code>PORTAL_MANAGE_OWN_AREA</code></td><td>Access to the user's own area.</td></tr>
<tr><td><code>PORTAL_GUEST</code></td><td>Access to the Portal module.</td></tr>
<tr><td><code>PORTAL_DISPATCHER</code></td><td>Allows access to the input/output files of the automatic optimizer (Dispatcher).</td></tr>
<tr><td><code>PORTAL_ALLRESOURCES_PLANNING_UPDATE</code></td><td>Allows editing the plannings of all resources.</td></tr>
<tr><td><code>PORTAL_ALLRESOURCES_PLANNING_DETAIL</code></td><td>Allows access to the planning details of all resources.</td></tr>
<tr><td><code>PORTAL_ALLRESOURCES_PLANNING_ACCESS</code></td><td>Allows displaying the plannings of all resources.</td></tr>
</tbody></table>

### Schedule

<table data-full-width="true"><thead><tr><th width="460">Right</th><th>Description</th></tr></thead><tbody>
<tr><td><code>PORTAL_WORKSITE_PLANNING_SECOND</code></td><td>Includes the resources for which the worksite specified for the worksite planning is a secondary worksite.</td></tr>
<tr><td><code>PORTAL_WORKSITE_PLANNING_FIRST</code></td><td>Includes the resources whose main worksite is the worksite specified for the worksite planning.</td></tr>
<tr><td><code>PORTAL_WORKSITE_PLANNING_EXECUTING</code></td><td>Includes the resources that perform an appointment at the worksite specified for the worksite planning.</td></tr>
<tr><td><code>PORTAL_WORKSITE_PLANNING</code></td><td>Access to worksite plannings.</td></tr>
<tr><td><code>PORTAL_WHOLEAREA_WORKSITE_PLANNING</code></td><td>Access to the plannings of all worksites in the user's area.</td></tr>
<tr><td><code>PORTAL_TEAM_PLANNING_UPDATE</code></td><td>Allows modifying the planning of members of the same team.</td></tr>
<tr><td><code>PORTAL_TEAM_PLANNING_DETAIL</code></td><td>Allows access to the appointment forms of members of the same team.</td></tr>
<tr><td><code>PORTAL_TEAM_PLANNING_ACCESS</code></td><td>Read access to team data.</td></tr>
<tr><td><code>PORTAL_NONMOBILE_RESOURCE_PLANNING</code></td><td>Access to the plannings of non-mobile resources in the Portal.</td></tr>
<tr><td><code>PORTAL_MULTIPLANNING_ACCESS</code></td><td>Access to multi-resource plannings from the Portal.</td></tr>
<tr><td><code>PORTAL_LEADED_TEAM_PLANNING_UPDATE</code></td><td>Allows modifying the planning of members of the teams led by the resource.</td></tr>
<tr><td><code>PORTAL_LEADED_TEAM_PLANNING_DETAIL</code></td><td>Allows access to the planning details (activities) of members of the teams led by the resource.</td></tr>
<tr><td><code>PORTAL_LEADED_TEAM_PLANNING_ACCESS</code></td><td>Access to the plannings of the teams led by the resource.</td></tr>
<tr><td><code>PORTAL_LEADED_TEAM_CHILD_PLANNING_UPDATE</code></td><td>Allows modifying the planning of members of the child teams of the teams led by the resource.</td></tr>
<tr><td><code>PORTAL_LEADED_TEAM_CHILD_PLANNING_DETAIL</code></td><td>Allows access to the planning details (activities) of members of the child teams of the teams led by the resource.</td></tr>
<tr><td><code>PORTAL_LEADED_TEAM_CHILD_PLANNING_ACCESS</code></td><td>Allows access to the planning of the child teams of the teams led by the resource.</td></tr>
<tr><td><code>PORTAL_AREA_PLANNING</code></td><td>Access to area plannings.</td></tr>
</tbody></table>

### Communication

<table data-full-width="true"><thead><tr><th width="460">Right</th><th>Description</th></tr></thead><tbody>
<tr><td><code>PORTAL_WAYBILL_EXPORT_XML</code></td><td>Access to exporting the waybill as XML.</td></tr>
<tr><td><code>PORTAL_WAYBILL_EXPORT_TOMTOM</code></td><td>Access to exporting the waybill to TomTom.</td></tr>
<tr><td><code>PORTAL_WAYBILL_EXPORT_PDF</code></td><td>Access to exporting the waybill as PDF.</td></tr>
<tr><td><code>PORTAL_WAYBILL</code></td><td>Allows access to the waybill.</td></tr>
<tr><td><code>PORTAL_VIEW_OTMOBILE</code></td><td>Allows displaying the OTmobile simulation application.</td></tr>
</tbody></table>

### Optimization

<table data-full-width="true"><thead><tr><th width="460">Right</th><th>Description</th></tr></thead><tbody>
<tr><td><code>PORTAL_STOP_MANUAL_OPTIMIZATION</code></td><td>Allows manually stopping an automatic optimization.</td></tr>
<tr><td><code>PORTAL_STOP_AUTOMATIC_OPTIMIZATION</code></td><td>Allows stopping an automatic optimization.</td></tr>
<tr><td><code>PORTAL_START_OPTIMIZATION_AT_ANY_TIME</code></td><td>Allows manually starting an automatic optimization at any time.</td></tr>
<tr><td><code>PORTAL_START_OPTIM_ON_VALIDITY_PERIOD</code></td><td>Allows manually starting an automatic optimization during its validity period.</td></tr>
<tr><td><code>PORTAL_OPTIMIZATION_SERVICE</code></td><td>Access to the optimization services.</td></tr>
</tbody></table>

### Unavailabilities

<table data-full-width="true"><thead><tr><th width="460">Right</th><th>Description</th></tr></thead><tbody>
<tr><td><code>PORTAL_UNAVAILABILITY_MANAGING_ACCESS</code></td><td>Access to unavailability management.</td></tr>
<tr><td><code>PORTAL_UNAVAILABILITY_ACCESS</code></td><td>Access to the unavailabilities menu.</td></tr>
</tbody></table>

## Planning

### Scope

<table data-full-width="true"><thead><tr><th width="460">Right</th><th>Description</th></tr></thead><tbody>
<tr><td><code>CALLCENTER_UPDATE_RESOURCEUSERLISTS</code></td><td>Access to modifying a resource list in the interface.</td></tr>
<tr><td><code>CALLCENTER_SHOW_RESOURCEUSERLISTS</code></td><td>Access to selecting a resource list in the interface.</td></tr>
<tr><td><code>CALLCENTER_SEE_ONLY_CURRENT_USR</code></td><td>Restricts all views to those that concern only the logged-in user.</td></tr>
<tr><td><code>CALLCENTER_MANAGE_PERIMETER</code></td><td>Allows managing the scope.</td></tr>
<tr><td><code>CALLCENTER_MANAGE_OWN_WORKSITE</code></td><td>Access to the user's own worksite.</td></tr>
<tr><td><code>CALLCENTER_MANAGE_OWN_TEAM</code></td><td>Access to the user's own team.</td></tr>
<tr><td><code>CALLCENTER_MANAGE_OWN_DOMAIN</code></td><td>Allows managing the areas of the user's own domain.</td></tr>
<tr><td><code>CALLCENTER_MANAGE_OWN_AREA</code></td><td>Access to the user's own area.</td></tr>
<tr><td><code>CALLCENTER_MANAGE_EXCEPTIONAL_LOCATION_CURRENT_AREA</code></td><td>Access to managing exceptional locations for the resources of the current area.</td></tr>
<tr><td><code>CALLCENTER_MANAGE_EXCEPTIONAL_LOCATION_ALL_AREA</code></td><td>Access to managing exceptional locations for all resources of all areas.</td></tr>
<tr><td><code>CALLCENTER_MANAGE_ALL_WORKSITES</code></td><td>Access to all worksites of the user's area.</td></tr>
<tr><td><code>CALLCENTER_MANAGE_ALL_TEAMS</code></td><td>Access to all teams of the user's area.</td></tr>
<tr><td><code>CALLCENTER_MANAGE_ALL_AREAS</code></td><td>Access to all areas (all worksites and all teams).</td></tr>
<tr><td><code>CALLCENTER_GUEST</code></td><td>Access to the Planning module.</td></tr>
<tr><td><code>CALLCENTER_DELETE_RESOURCEUSERLISTS</code></td><td>Access to deleting a resource list in the interface.</td></tr>
<tr><td><code>CALLCENTER_CRM_VIEW_ALL_AREAS</code></td><td>Allows viewing the customers of all areas.</td></tr>
<tr><td><code>CALLCENTER_CREATE_RESOURCEUSERLISTS</code></td><td>Access to creating a resource list in the interface.</td></tr>
<tr><td><code>CALLCENTER_CHANGE_AREA</code></td><td>Allows changing the area of the active module.</td></tr>
</tbody></table>

### Customer

<table data-full-width="true"><thead><tr><th width="460">Right</th><th>Description</th></tr></thead><tbody>
<tr><td><code>CALLCENTER_CRM_VIEW_PROJECT_MAININFO</code></td><td>Allows displaying the main project information.</td></tr>
<tr><td><code>CALLCENTER_CRM_VIEW_PROJECT_EXTRAFIELDS</code></td><td>Allows displaying the additional project fields.</td></tr>
<tr><td><code>CALLCENTER_CRM_VIEW_PROJECT_DETAILS</code></td><td>Allows displaying the project details.</td></tr>
<tr><td><code>CALLCENTER_CRM_VIEW_PROJECT_DAYS</code></td><td>Allows displaying the project days.</td></tr>
<tr><td><code>CALLCENTER_CRM_VIEW_PROJECT_ASSIGNMENTS</code></td><td>Allows viewing the project assignments.</td></tr>
<tr><td><code>CALLCENTER_CRM_VIEW_ORDERER_REQUIREMENTS</code></td><td>Allows displaying the orderer's preferences.</td></tr>
<tr><td><code>CALLCENTER_CRM_VIEW_ORDERER</code></td><td>Allows access to the orderer.</td></tr>
<tr><td><code>CALLCENTER_CRM_VIEW_CUSTOMER_TYPE</code></td><td>Allows viewing the customer type.</td></tr>
<tr><td><code>CALLCENTER_CRM_VIEW_CUSTOMER_REQUIREMENTS</code></td><td>Allows viewing the customer preferences.</td></tr>
<tr><td><code>CALLCENTER_CRM_VIEW_CUSTOMER_PROJECT</code></td><td>Allows viewing the customer project.</td></tr>
<tr><td><code>CALLCENTER_CRM_VIEW_CUSTOMER_PLANNING_WEEK</code></td><td>Allows viewing the customer weekly planning.</td></tr>
<tr><td><code>CALLCENTER_CRM_VIEW_CUSTOMER_PLANNING_MONTH</code></td><td>Allows viewing the customer monthly planning.</td></tr>
<tr><td><code>CALLCENTER_CRM_VIEW_CUSTOMER_KIND</code></td><td>Allows viewing the customer kinds.</td></tr>
<tr><td><code>CALLCENTER_CRM_VIEW_CUSTOMER_DAYS</code></td><td>Allows viewing the customer days.</td></tr>
<tr><td><code>CALLCENTER_CRM_VIEW_CUSTOMER_CONTACTS</code></td><td>Allows viewing the customer contacts.</td></tr>
<tr><td><code>CALLCENTER_CRM_VIEW_CUSTOMER_AUTHORIZATION</code></td><td>Access to the authorizations on the customer page.</td></tr>
<tr><td><code>CALLCENTER_CRM_VIEW_CUSTOMER_ASSIGNMENTS</code></td><td>Allows viewing the customer assignments.</td></tr>
<tr><td><code>CALLCENTER_CRM_VIEW_CUSTOMER_APPOINTMENTS</code></td><td>Allows viewing the customer's appointments.</td></tr>
<tr><td><code>CALLCENTER_CRM_VIEW_CUSTOMER_ADDRESS</code></td><td>Allows viewing the customer address.</td></tr>
<tr><td><code>CALLCENTER_CRM_VIEW_CUSTOMER</code></td><td>Allows viewing the customer.</td></tr>
<tr><td><code>CALLCENTER_CRM_VIEW_ADDRESSES_STREETVIEW</code></td><td>Allows access to the Google Street View of an address.</td></tr>
<tr><td><code>CALLCENTER_CRM_UPDATE_PROJECT_MAININFO</code></td><td>Allows modifying the main project information.</td></tr>
<tr><td><code>CALLCENTER_CRM_UPDATE_PROJECT_EXTRAFIELDS</code></td><td>Allows modifying the additional project fields.</td></tr>
<tr><td><code>CALLCENTER_CRM_UPDATE_PROJECT_DETAILS</code></td><td>Allows modifying the project details.</td></tr>
<tr><td><code>CALLCENTER_CRM_UPDATE_PROJECT_DAYS</code></td><td>Allows modifying the project days.</td></tr>
<tr><td><code>CALLCENTER_CRM_UPDATE_PROJECT_ASSIGNMENTS</code></td><td>Allows modifying the project assignments.</td></tr>
<tr><td><code>CALLCENTER_CRM_UPDATE_ORDERER_REQUIREMENTS</code></td><td>Allows modifying the orderer's preferences.</td></tr>
<tr><td><code>CALLCENTER_CRM_UPDATE_ORDERER</code></td><td>Allows editing the orderer.</td></tr>
<tr><td><code>CALLCENTER_CRM_UPDATE_CUSTOMER_TYPE</code></td><td>Allows editing the customer type.</td></tr>
<tr><td><code>CALLCENTER_CRM_UPDATE_CUSTOMER_REQUIREMENTS</code></td><td>Allows editing the customer preferences.</td></tr>
<tr><td><code>CALLCENTER_CRM_UPDATE_CUSTOMER_PROJECT</code></td><td>Allows editing the customer project.</td></tr>
<tr><td><code>CALLCENTER_CRM_UPDATE_CUSTOMER_KIND</code></td><td>Allows modifying the customer kinds.</td></tr>
<tr><td><code>CALLCENTER_CRM_UPDATE_CUSTOMER_DETAILS</code></td><td>Allows editing the customer preferences.</td></tr>
<tr><td><code>CALLCENTER_CRM_UPDATE_CUSTOMER_DAYS</code></td><td>Allows editing the customer days.</td></tr>
<tr><td><code>CALLCENTER_CRM_UPDATE_CUSTOMER_CONTACTS</code></td><td>Allows editing the customer contacts.</td></tr>
<tr><td><code>CALLCENTER_CRM_UPDATE_CUSTOMER_AUTHORIZATION</code></td><td>Allows modifying the authorizations on the customer page.</td></tr>
<tr><td><code>CALLCENTER_CRM_UPDATE_CUSTOMER_ASSIGNMENTS</code></td><td>Allows editing the customer assignments.</td></tr>
<tr><td><code>CALLCENTER_CRM_UPDATE_CUSTOMER_ADDRESS</code></td><td>Allows editing the customer address.</td></tr>
<tr><td><code>CALLCENTER_CRM_UPDATE_CUSTOMER</code></td><td>Allows editing the customer.</td></tr>
<tr><td><code>CALLCENTER_CRM_TOURS_PLAN</code></td><td>Access to the tour templates.</td></tr>
<tr><td><code>CALLCENTER_CRM_SET_MAIN_CUSTOMER_CONTACTS</code></td><td>Allows editing the main customer contact.</td></tr>
<tr><td><code>CALLCENTER_CRM_REMOVE_CUSTOMER_CONTACTS</code></td><td>Allows deleting a customer contact.</td></tr>
<tr><td><code>CALLCENTER_CRM_LIST_REPLACE_WISHED_HR_LIST</code></td><td>Allows replacing the list of preferred resources for a list of customers.</td></tr>
<tr><td><code>CALLCENTER_CRM_LIST_REPLACE_REQUIRED_HR_LIST</code></td><td>Allows replacing the list of required resources for a list of customers.</td></tr>
<tr><td><code>CALLCENTER_CRM_LIST_REPLACE_REFUSED_HR_LIST</code></td><td>Allows replacing the list of refused resources for a list of customers.</td></tr>
<tr><td><code>CALLCENTER_CRM_LIST_REMOVE_FROM_WISHED_HR_LIST</code></td><td>Allows removing resources from the list of preferred resources for a list of customers.</td></tr>
<tr><td><code>CALLCENTER_CRM_LIST_REMOVE_FROM_REQUIRED_HR_LIST</code></td><td>Allows removing resources from the list of required resources for a list of customers.</td></tr>
<tr><td><code>CALLCENTER_CRM_LIST_REMOVE_FROM_REFUSED_HR_LIST</code></td><td>Allows removing resources from the list of refused resources for a list of customers.</td></tr>
<tr><td><code>CALLCENTER_CRM_LIST_EMPTY_WISHED_HR_LIST</code></td><td>Allows emptying the list of preferred resources for a list of customers.</td></tr>
<tr><td><code>CALLCENTER_CRM_LIST_EMPTY_REQUIRED_HR_LIST</code></td><td>Allows emptying the list of required resources for a list of customers.</td></tr>
<tr><td><code>CALLCENTER_CRM_LIST_EMPTY_REFUSED_HR_LIST</code></td><td>Allows emptying the list of refused resources for a list of customers.</td></tr>
<tr><td><code>CALLCENTER_CRM_LIST_CHANGE_WORKSITE</code></td><td>Allows changing the worksite for a list of customers.</td></tr>
<tr><td><code>CALLCENTER_CRM_LIST_CHANGE_TYPE</code></td><td>Allows changing the type for a list of customers.</td></tr>
<tr><td><code>CALLCENTER_CRM_LIST_CHANGE_QUANTITIES</code></td><td>Allows changing the Quantities fields for a list of customers.</td></tr>
<tr><td><code>CALLCENTER_CRM_LIST_CHANGE_NEXT_SCHEDULED_DATE</code></td><td>Allows changing the next visit date for a list of customers.</td></tr>
<tr><td><code>CALLCENTER_CRM_LIST_CHANGE_LOGICALS</code></td><td>Allows changing the Logicals fields for a list of customers.</td></tr>
<tr><td><code>CALLCENTER_CRM_LIST_CHANGE_LAST_VISIT_DATE</code></td><td>Allows changing the last visit date for a list of customers.</td></tr>
<tr><td><code>CALLCENTER_CRM_LIST_CHANGE_KIND</code></td><td>Allows changing the kind for a list of customers.</td></tr>
<tr><td><code>CALLCENTER_CRM_LIST_CHANGE_ISFOCUS</code></td><td>Allows changing the focus for a list of customers.</td></tr>
<tr><td><code>CALLCENTER_CRM_LIST_CHANGE_FILLERS</code></td><td>Allows changing the Fillers fields for a list of customers.</td></tr>
<tr><td><code>CALLCENTER_CRM_LIST_CHANGE_DATES</code></td><td>Allows changing the dates for a list of customers.</td></tr>
<tr><td><code>CALLCENTER_CRM_LIST_ADD_TO_WISHED_HR_LIST</code></td><td>Allows adding resources to the list of preferred resources for a list of customers.</td></tr>
<tr><td><code>CALLCENTER_CRM_LIST_ADD_TO_REQUIRED_HR_LIST</code></td><td>Allows adding resources to the list of required resources for a list of customers.</td></tr>
<tr><td><code>CALLCENTER_CRM_LIST_ADD_TO_REFUSED_HR_LIST</code></td><td>Allows adding resources to the list of refused resources for a list of customers.</td></tr>
<tr><td><code>CALLCENTER_CRM_GENERATE_PERIODIC_APPT</code></td><td>Access to the page for generating requests for recurring customers.</td></tr>
<tr><td><code>CALLCENTER_CRM_CUSTOMER_SEARCH_RESET_FORM</code></td><td>Allows resetting a customer search.</td></tr>
<tr><td><code>CALLCENTER_CRM_CUSTOMER_SEARCH_CHECK_POSTADDRESS</code></td><td>Allows checking a customer's postal address during a search.</td></tr>
<tr><td><code>CALLCENTER_CRM_CUSTOMER_EXPORT_CSV</code></td><td>Allows exporting a customer in CSV format during a search.</td></tr>
<tr><td><code>CALLCENTER_CRM_CUSTOMER_ALERT_LIST</code></td><td>Access right to the list of customer alerts.</td></tr>
<tr><td><code>CALLCENTER_CRM_CREATE_ORDERER</code></td><td>Allows creating the orderer.</td></tr>
<tr><td><code>CALLCENTER_CRM_CREATE_CUSTOMER_TYPE</code></td><td>Allows creating the customer type.</td></tr>
<tr><td><code>CALLCENTER_CRM_CREATE_CUSTOMER_KIND</code></td><td>Allows creating the customer kinds.</td></tr>
<tr><td><code>CALLCENTER_CRM_CREATE_CUSTOMER_CONTACTS</code></td><td>Allows creating a customer contact.</td></tr>
<tr><td><code>CALLCENTER_CRM_CREATE_CUSTOMER</code></td><td>Allows creating the customer.</td></tr>
<tr><td><code>CALLCENTER_CRM_APPLY_UPDATES_TO_APP</code></td><td>Allows propagating customer updates to the appointment requests.</td></tr>
</tbody></table>

### Appointment

<table data-full-width="true"><thead><tr><th width="460">Right</th><th>Description</th></tr></thead><tbody>
<tr><td><code>CALLCENTER_UNPLAN_REALIZED_APPT</code></td><td>Allows unplanning fully or partially realized appointments.</td></tr>
<tr><td><code>CALLCENTER_UNPLAN_APPT</code></td><td>Unplan an appointment.</td></tr>
<tr><td><code>CALLCENTER_UNDONE_APPT</code></td><td>Access to undoing the realization of an appointment.</td></tr>
<tr><td><code>CALLCENTER_UNCONFIRM_APPT</code></td><td>Allows unconfirming an appointment.</td></tr>
<tr><td><code>CALLCENTER_TRANSFORM_REQUEST</code></td><td>Access to the <strong>Transform</strong> button in the appointment form. This button opens a dedicated edit page to easily apply predefined changes according to a customized business process.</td></tr>
<tr><td><code>CALLCENTER_TAKE_APPT</code></td><td>Allows access to appointment booking.</td></tr>
<tr><td><code>CALLCENTER_SUSPEND_APPT</code></td><td>Suspend an appointment.</td></tr>
<tr><td><code>CALLCENTER_SPLIT_APPT</code></td><td>Access to the <strong>Split</strong> button in the appointment page.</td></tr>
<tr><td><code>CALLCENTER_SHEET_APPT</code></td><td>Allows access to the appointment form.</td></tr>
<tr><td><code>CALLCENTER_SAVE_APPT</code></td><td>Save an appointment.</td></tr>
<tr><td><code>CALLCENTER_RESERVE_APPT</code></td><td>Reserve an appointment.</td></tr>
<tr><td><code>CALLCENTER_REQUEST_CONFIRMED_APPT</code></td><td>Re-activate a reserved or confirmed appointment.</td></tr>
<tr><td><code>CALLCENTER_REQUEST_APPT</code></td><td>Request an appointment.</td></tr>
<tr><td><code>CALLCENTER_REPLAN_APPT</code></td><td>Replan an appointment.</td></tr>
<tr><td><code>CALLCENTER_PHONE_COUNTER</code></td><td>Display and increment the call counter.</td></tr>
<tr><td><code>CALLCENTER_MODIFY_APPT</code></td><td>Allows modifying appointments.</td></tr>
<tr><td><code>CALLCENTER_FULLREQUEST_MODIFY</code></td><td>Full access to modifying an appointment request.</td></tr>
<tr><td><code>CALLCENTER_EDIT_CHAIN_CONSTRAINT</code></td><td>Create and modify a chaining constraint.</td></tr>
<tr><td><code>CALLCENTER_DONE_APPT_ANYSTATUS</code></td><td>Allows switching an appointment to the realized status, regardless of its current status.</td></tr>
<tr><td><code>CALLCENTER_DONE_APPT</code></td><td>Access to the realization of the appointment.</td></tr>
<tr><td><code>CALLCENTER_DECLARE_ACHIEVED</code></td><td>Allows declaring and modifying realized appointments.</td></tr>
<tr><td><code>CALLCENTER_COPY_APPT</code></td><td>Copy an appointment.</td></tr>
<tr><td><code>CALLCENTER_CONFIRM_APPT</code></td><td>Confirm an appointment.</td></tr>
<tr><td><code>CALLCENTER_CHANGE_APPT_ADDRESS</code></td><td>Allows changing the appointment address.</td></tr>
<tr><td><code>CALLCENTER_CANCEL_APPT</code></td><td>Cancel an appointment.</td></tr>
<tr><td><code>CALLCENTER_ACCEPT_APPOINTMENT</code></td><td>Accept an appointment.</td></tr>
</tbody></table>

### Appointment list

<table data-full-width="true"><thead><tr><th width="460">Right</th><th>Description</th></tr></thead><tbody>
<tr><td><code>CALLCENTER_UNPLAN_LIST</code></td><td>Allows switching a list of appointments to the suspended status.</td></tr>
<tr><td><code>CALLCENTER_UNCANCEL_LIST</code></td><td>Allows switching a list of appointments to the requested status.</td></tr>
<tr><td><code>CALLCENTER_SUSPEND_LIST</code></td><td>Allows switching a list of appointments to the suspended status.</td></tr>
<tr><td><code>CALLCENTER_SEARCH_UNPLANNED_APPT</code></td><td>Access to searching for unplanned appointments.</td></tr>
<tr><td><code>CALLCENTER_SEARCH_RESERVED_APPT</code></td><td>Access to searching for reserved appointments.</td></tr>
<tr><td><code>CALLCENTER_SEARCH_REQUESTED_APPT</code></td><td>Access to searching for requested appointments.</td></tr>
<tr><td><code>CALLCENTER_SEARCH_PLANNED_APPT</code></td><td>Access to searching for planned appointments.</td></tr>
<tr><td><code>CALLCENTER_SEARCH_EXTERNALIZED_APPT</code></td><td>Subcontracted appointment.</td></tr>
<tr><td><code>CALLCENTER_SEARCH_CONFIRMED_APPT</code></td><td>Access to searching for confirmed appointments.</td></tr>
<tr><td><code>CALLCENTER_SEARCH_CHAIN_CONSTRAINT</code></td><td>Access to searching for chaining constraints.</td></tr>
<tr><td><code>CALLCENTER_SEARCH_APPT</code></td><td>Access to searching for appointments.</td></tr>
<tr><td><code>CALLCENTER_SEARCH_ACCEPTED_APPT</code></td><td>Access to searching for accepted appointments.</td></tr>
<tr><td><code>CALLCENTER_RESERV_LIST</code></td><td>Allows switching a list of appointments to the reserved status.</td></tr>
<tr><td><code>CALLCENTER_REALIZE_LIST</code></td><td>Allows switching a list of appointments to the realized status.</td></tr>
<tr><td><code>CALLCENTER_REACTIVATE_LIST</code></td><td>Allows switching a list of appointments to the requested status.</td></tr>
<tr><td><code>CALLCENTER_PLANSUGGEST_LIST</code></td><td>Allows switching a list of appointments to the planned status.</td></tr>
<tr><td><code>CALLCENTER_PLAN_LIST</code></td><td>Allows planning a list of appointments.</td></tr>
<tr><td><code>CALLCENTER_INCREASE_PLANNED_DATE_LIST</code></td><td>Allows postponing the planned date for a list of appointments.</td></tr>
<tr><td><code>CALLCENTER_INCREASE_DATE_MIN_BEGIN_LIST</code></td><td>Allows postponing the earliest date for a list of appointments.</td></tr>
<tr><td><code>CALLCENTER_INCREASE_DATE_MAX_END_LIST</code></td><td>Allows postponing the latest date for a list of appointments.</td></tr>
<tr><td><code>CALLCENTER_DECREASE_PLANNED_DATE_LIST</code></td><td>Allows bringing forward the planned date for a list of appointments.</td></tr>
<tr><td><code>CALLCENTER_DECREASE_DATE_MIN_BEGIN_LIST</code></td><td>Allows bringing forward the earliest date for a list of appointments.</td></tr>
<tr><td><code>CALLCENTER_DECREASE_DATE_MAX_END_LIST</code></td><td>Allows bringing forward the latest date for a list of appointments.</td></tr>
<tr><td><code>CALLCENTER_CONFIRM_LIST</code></td><td>Allows switching a list of appointments to the confirmed status.</td></tr>
<tr><td><code>CALLCENTER_CHANGE_WORKSITE_LIST</code></td><td>Allows changing the worksite for a list of appointments.</td></tr>
<tr><td><code>CALLCENTER_CHANGE_RESOURCES_LIST</code></td><td>Allows changing the resources for a list of appointments.</td></tr>
<tr><td><code>CALLCENTER_CHANGE_QUANTITIES_LIST</code></td><td>Allows changing the Quantities fields for a list of appointments.</td></tr>
<tr><td><code>CALLCENTER_CHANGE_PRIORITY_LIST</code></td><td>Allows changing the priority for a list of appointments.</td></tr>
<tr><td><code>CALLCENTER_CHANGE_LOGICALS_LIST</code></td><td>Allows changing the Logicals fields for a list of appointments.</td></tr>
<tr><td><code>CALLCENTER_CHANGE_FILLERS_LIST</code></td><td>Allows changing the Fillers fields for a list of appointments.</td></tr>
<tr><td><code>CALLCENTER_CHANGE_DATES_TIMES_LIST</code></td><td>Allows changing the latest and earliest date and time for a list of appointments.</td></tr>
<tr><td><code>CALLCENTER_CHANGE_DATE_MIN_BEGIN_LIST</code></td><td>Allows changing the earliest date for a list of appointments.</td></tr>
<tr><td><code>CALLCENTER_CHANGE_DATE_MAX_END_LIST</code></td><td>Allows changing the latest date for a list of appointments.</td></tr>
<tr><td><code>CALLCENTER_CHANGE_ADDITIONALDATES_LIST</code></td><td>Allows changing the Additional dates fields for a list of appointments.</td></tr>
<tr><td><code>CALLCENTER_CANCEL_LIST</code></td><td>Allows switching a list of appointments to the cancelled status.</td></tr>
<tr><td><code>CALLCENTER_APPOINTMENT_LIST_MYSEARCH9</code></td><td>Access to the appointment list mySearch 9.</td></tr>
<tr><td><code>CALLCENTER_APPOINTMENT_LIST_MYSEARCH8</code></td><td>Access to the appointment list mySearch 8.</td></tr>
<tr><td><code>CALLCENTER_APPOINTMENT_LIST_MYSEARCH7</code></td><td>Access to the appointment list mySearch 7.</td></tr>
<tr><td><code>CALLCENTER_APPOINTMENT_LIST_MYSEARCH6</code></td><td>Access to the appointment list mySearch 6.</td></tr>
<tr><td><code>CALLCENTER_APPOINTMENT_LIST_MYSEARCH5</code></td><td>Access to the appointment list mySearch 5.</td></tr>
<tr><td><code>CALLCENTER_APPOINTMENT_LIST_MYSEARCH4</code></td><td>Access to the appointment list mySearch 4.</td></tr>
<tr><td><code>CALLCENTER_APPOINTMENT_LIST_MYSEARCH3</code></td><td>Access to the appointment list mySearch 3.</td></tr>
<tr><td><code>CALLCENTER_APPOINTMENT_LIST_MYSEARCH2</code></td><td>Access to the appointment list mySearch 2.</td></tr>
<tr><td><code>CALLCENTER_APPOINTMENT_LIST_MYSEARCH15</code></td><td>Access to the appointment list mySearch 15.</td></tr>
<tr><td><code>CALLCENTER_APPOINTMENT_LIST_MYSEARCH14</code></td><td>Access to the appointment list mySearch 14.</td></tr>
<tr><td><code>CALLCENTER_APPOINTMENT_LIST_MYSEARCH13</code></td><td>Access to the appointment list mySearch 13.</td></tr>
<tr><td><code>CALLCENTER_APPOINTMENT_LIST_MYSEARCH12</code></td><td>Access to the appointment list mySearch 12.</td></tr>
<tr><td><code>CALLCENTER_APPOINTMENT_LIST_MYSEARCH11</code></td><td>Access to the appointment list mySearch 11.</td></tr>
<tr><td><code>CALLCENTER_APPOINTMENT_LIST_MYSEARCH10</code></td><td>Access to the appointment list mySearch 10.</td></tr>
<tr><td><code>CALLCENTER_APPOINTMENT_LIST_MYSEARCH1</code></td><td>Access to the appointment list mySearch 1.</td></tr>
<tr><td><code>CALLCENTER_APPOINTMENT_ALERT_LIST_TROUBLESHOOTING</code></td><td>Access right to the list of troubleshooting task alerts.</td></tr>
<tr><td><code>CALLCENTER_APPOINTMENT_ALERT_LIST_CUSTOMER_GAP</code></td><td>Access right to the list of customer gap alerts.</td></tr>
<tr><td><code>CALLCENTER_APPOINTMENT_ALERT_LIST_BIG_ROUTE_DURATION</code></td><td>Access right to the list of travel duration alerts.</td></tr>
<tr><td><code>CALLCENTER_APPOINTMENT_ALERT_LIST_APPOINTMENT_TO_REPLAN</code></td><td>Access right to the list of alerts for appointments to replan.</td></tr>
<tr><td><code>CALLCENTER_APPOINTMENT_ALERT_LIST</code></td><td>Access right to the list of task alerts.</td></tr>
<tr><td><code>CALLCENTER_ADD_CONSTRAINT_LIST</code></td><td>Allows creating a chaining constraint for a list of appointments.</td></tr>
<tr><td><code>CALLCENTER_ACCEPT_LIST</code></td><td>Allows changing the status to accepted for a list of appointments.</td></tr>
</tbody></table>

### Planning

<table data-full-width="true"><thead><tr><th width="460">Right</th><th>Description</th></tr></thead><tbody>
<tr><td><code>CALLCENTER_VISITS_TOO_FREQUENT</code></td><td>Allows visits that are too frequent.</td></tr>
<tr><td><code>CALLCENTER_SCHEDULE_APPT_AS_PLANNED</code></td><td>Allows placing an appointment in the planned status.</td></tr>
<tr><td><code>CALLCENTER_RESCHEDULE_COLLECTION_OF_APPOINTMENT</code></td><td>Allows resuming the planning of one or more days.</td></tr>
<tr><td><code>CALLCENTER_REOPTIM_WEEK</code></td><td>Allows optimizing a week.</td></tr>
<tr><td><code>CALLCENTER_REOPTIM_DAY</code></td><td>Allows optimizing a day.</td></tr>
<tr><td><code>CALLCENTER_REALTIME_TIMEGRID_MODE</code></td><td>Allows displaying the real-time optimization solutions in grid mode.</td></tr>
<tr><td><code>CALLCENTER_REALTIME_OPTIM_IGNORE_HR_CONSTRAINTS</code></td><td>Allows real-time optimization of visits by resources that are neither required nor preferred.</td></tr>
<tr><td><code>CALLCENTER_POST_OPTIM_SUSPEND_APP</code></td><td>Allows switching to the suspended status an appointment for which the real-time optimization found no solution.</td></tr>
<tr><td><code>CALLCENTER_POST_OPTIM_IMPOSE_APP</code></td><td>Manual appointment booking after an optimization.</td></tr>
<tr><td><code>CALLCENTER_PLAN_APPT</code></td><td>Plan an appointment.</td></tr>
<tr><td><code>CALLCENTER_OPTIM_APP</code></td><td>Allows planning appointments with real-time optimization.</td></tr>
<tr><td><code>CALLCENTER_MODIFY_AGENDA_CONTROLLED_DATES_VALIDATION</code></td><td>Allows modifying the validation data for locked days.</td></tr>
<tr><td><code>CALLCENTER_MODIFY_AGENDA_CONTROLLED_DATES_ENTRY</code></td><td>Allows modifying the validation request data for locked days.</td></tr>
<tr><td><code>CALLCENTER_MANUAL_OPTIM_IGNORE_HR_WORKSITE</code></td><td>Allows manual planning of visits by resources that are not assigned to the worksite of the visit.</td></tr>
<tr><td><code>CALLCENTER_MANUAL_OPTIM_IGNORE_HR_CONSTRAINTS</code></td><td>Allows manual planning of visits by resources that are neither required nor preferred.</td></tr>
<tr><td><code>CALLCENTER_MANAGE_AGENDA_MARKERS</code></td><td>Access to markers.</td></tr>
<tr><td><code>CALLCENTER_MANAGE_AGENDA_CONTROLLED_DATES</code></td><td>Access to managing locked days.</td></tr>
<tr><td><code>CALLCENTER_IMPOSE_APP_IGNORE_SKILLS</code></td><td>Allows manually booking an appointment for a resource who does not have the required skills.</td></tr>
<tr><td><code>CALLCENTER_IMPOSE_APP</code></td><td>Plan an appointment manually.</td></tr>
<tr><td><code>CALLCENTER_FORCE_IMPOSE_APP</code></td><td>Plan an appointment manually, violating constraints.</td></tr>
<tr><td><code>CALLCENTER_FILL_PLANNING</code></td><td>Fill a resource's planning with requested or unplanned appointments.</td></tr>
<tr><td><code>CALLCENTER_CAN_VALIDATE_AGENDA_CONTROLLED_DATE</code></td><td>Allows setting locked days to the VALIDATED status.</td></tr>
<tr><td><code>CALLCENTER_CAN_TAKE_APPOINTMENT_WITH_OPTIM_PARAMETERS_NAMED</code></td><td>Allows booking appointments with the named optimization parameter configurations.</td></tr>
<tr><td><code>CALLCENTER_CAN_REQUEST_AGENDA_CONTROLLED_DATE</code></td><td>Allows setting locked days to the REQUESTED status.</td></tr>
<tr><td><code>CALLCENTER_CAN_REFUSE_AGENDA_CONTROLLED_DATE</code></td><td>Allows setting locked days to the REFUSED status.</td></tr>
<tr><td><code>CALLCENTER_CAN_PLACEONDISABLED_DATES</code></td><td>Allows planning during time outside the constrained dates.</td></tr>
<tr><td><code>CALLCENTER_CAN_FORCE_MAX_WORK_TIME_OF_WEEK</code></td><td>Allows exceeding the maximum working time of a week.</td></tr>
<tr><td><code>CALLCENTER_CAN_FORCE_MAX_WORK_TIME_OF_DAY</code></td><td>Allows exceeding the maximum working time of a day.</td></tr>
<tr><td><code>CALLCENTER_CAN_FORCE_MAX_MOVE_TIME_OF_WEEK</code></td><td>Allows exceeding the maximum travel distance of a week.</td></tr>
<tr><td><code>CALLCENTER_CAN_FORCE_MAX_MOVE_TIME_OF_DAY</code></td><td>Allows exceeding the maximum travel distance of a day.</td></tr>
</tbody></table>

### Interactions with the schedule

<table data-full-width="true"><thead><tr><th width="460">Right</th><th>Description</th></tr></thead><tbody>
<tr><td><code>CALLCENTER_INPLANNING_UNPLAN_REALIZED_APPT</code></td><td>Allows unplanning fully or partially realized appointments from the planning view.</td></tr>
<tr><td><code>CALLCENTER_INPLANNING_UNPLAN_APPT</code></td><td>Allows suspending appointments (switching to the suspended status) from the plannings.</td></tr>
<tr><td><code>CALLCENTER_INPLANNING_UNDO_APP</code></td><td>Allows undoing the realization of a realized appointment.</td></tr>
<tr><td><code>CALLCENTER_INPLANNING_UNCONFIRM_EXCEPTIONAL_LOCATIONS</code></td><td>Allows unconfirming exceptional locations in the planning view.</td></tr>
<tr><td><code>CALLCENTER_INPLANNING_UNCONFIRM_APPT</code></td><td>Allows unconfirming appointments (switching to the planned status) in the plannings.</td></tr>
<tr><td><code>CALLCENTER_INPLANNING_SUSPEND_APPT</code></td><td>Allows suspending appointments (switching to the suspended status) from the plannings.</td></tr>
<tr><td><code>CALLCENTER_INPLANNING_RESET_STANDARD_DAY</code></td><td>Allows resetting a day to its standard value when a specific type is applied to it.</td></tr>
<tr><td><code>CALLCENTER_INPLANNING_RESERV_APPT</code></td><td>Allows reserving appointments (switching to the reserved status) from the plannings.</td></tr>
<tr><td><code>CALLCENTER_INPLANNING_REMOVE_UNAVAILABILITY</code></td><td>Allows deleting unavailabilities from the plannings.</td></tr>
<tr><td><code>CALLCENTER_INPLANNING_REMOVE_EXCEPTIONAL_LOCATION</code></td><td>Allows deleting exceptional locations in the plannings.</td></tr>
<tr><td><code>CALLCENTER_INPLANNING_REMOVE_APPT</code></td><td>Allows deleting appointments (switching to the cancelled status) from the plannings.</td></tr>
<tr><td><code>CALLCENTER_INPLANNING_REACTIV_APPT</code></td><td>Re-activation of appointments from the plannings (return to the requested status).</td></tr>
<tr><td><code>CALLCENTER_INPLANNING_MOVE_UNAVAILABILITY</code></td><td>Allows moving unavailabilities from the plannings.</td></tr>
<tr><td><code>CALLCENTER_INPLANNING_MOVE_MARKER</code></td><td>Allows moving markers in the plannings.</td></tr>
<tr><td><code>CALLCENTER_INPLANNING_MOVE_APPT</code></td><td>Allows moving appointments from the plannings.</td></tr>
<tr><td><code>CALLCENTER_INPLANNING_MODIFY_UNAVAILABILITY_DURATION</code></td><td>Allows modifying the duration of unavailabilities in the plannings.</td></tr>
<tr><td><code>CALLCENTER_INPLANNING_MODIFY_MARKER_DURATION</code></td><td>Allows modifying the duration of markers in the plannings.</td></tr>
<tr><td><code>CALLCENTER_INPLANNING_MODIFY_EXCEPTIONAL_LOCATION</code></td><td>Allows modifying the duration of exceptional locations in the plannings.</td></tr>
<tr><td><code>CALLCENTER_INPLANNING_MODIFY_APPT_DURATION</code></td><td>Allows modifying the duration of appointments from the plannings.</td></tr>
<tr><td><code>CALLCENTER_INPLANNING_CREATE_EXCEPTIONAL_LOCATION</code></td><td>Allows creating exceptional locations in the planning view.</td></tr>
<tr><td><code>CALLCENTER_INPLANNING_CONFIRM_EXCEPTIONAL_LOCATIONS</code></td><td>Allows confirming exceptional locations in the planning view.</td></tr>
<tr><td><code>CALLCENTER_INPLANNING_CONFIRM_APPT</code></td><td>Allows confirming appointments (switching to the confirmed status) from the plannings.</td></tr>
<tr><td><code>CALLCENTER_INPLANNING_APP_PANEL</code></td><td>Access to the appointment basket in the plannings.</td></tr>
<tr><td><code>CALLCENTER_INPLANNING_ADD_BY_DRAG_EXCEPTIONAL_LOCATION</code></td><td>Allows creating an exceptional location by drag and drop in the plannings.</td></tr>
<tr><td><code>CALLCENTER_INPLANNING_ACCEPT_APPT</code></td><td>Accept appointments in the plannings.</td></tr>
</tbody></table>

### Schedule

<table data-full-width="true"><thead><tr><th width="460">Right</th><th>Description</th></tr></thead><tbody>
<tr><td><code>CALLCENTER_WORKSITE_PLANNING_SECOND</code></td><td>Includes the resources for which the worksite specified for the worksite planning is a secondary worksite.</td></tr>
<tr><td><code>CALLCENTER_WORKSITE_PLANNING_FIRST</code></td><td>Includes the resources whose main worksite is the worksite specified for the worksite planning.</td></tr>
<tr><td><code>CALLCENTER_WORKSITE_PLANNING_EXECUTING</code></td><td>Includes the resources that perform an appointment at the worksite specified for the worksite planning.</td></tr>
<tr><td><code>CALLCENTER_WORKSITE_PLANNING</code></td><td>Access to the worksite planning.</td></tr>
<tr><td><code>CALLCENTER_WEEK_PLANNING</code></td><td>Access to the week planning.</td></tr>
<tr><td><code>CALLCENTER_VIEW_CHARGE_PLANNING</code></td><td>Access to the workload plannings.</td></tr>
<tr><td><code>CALLCENTER_VIEW_AREA_BY_WORKSITE_PLANNING</code></td><td>Access to the area plannings by worksite.</td></tr>
<tr><td><code>CALLCENTER_VEHICLE_PLANNING</code></td><td>Access to the display of tracked vehicles.</td></tr>
<tr><td><code>CALLCENTER_TEAM_PLANNING</code></td><td>Access to the team planning.</td></tr>
<tr><td><code>CALLCENTER_ROTATE_PLANNING</code></td><td>Access to the button that switches the schedule between horizontal and vertical display.</td></tr>
<tr><td><code>CALLCENTER_PLANNING_NO_HOURS</code></td><td>Displays the plannings without showing the hours.</td></tr>
<tr><td><code>CALLCENTER_PLANNING_DISPLAY_MARKERS</code></td><td>Display markers in the Planning module schedule.</td></tr>
<tr><td><code>CALLCENTER_PLANNING</code></td><td>Access to the plannings.</td></tr>
<tr><td><code>CALLCENTER_NONMOBILE_RESOURCE_PLANNING</code></td><td>Access to the planning of non-mobile resources in the Planning module.</td></tr>
<tr><td><code>CALLCENTER_MULTI_PLANNING</code></td><td>Access to multi-resource plannings.</td></tr>
<tr><td><code>CALLCENTER_MONTH_PLANNING</code></td><td>Access to the month planning.</td></tr>
<tr><td><code>CALLCENTER_HIDE_PERSONAL_ADDRESS</code></td><td>Hide the personal addresses of resources in the map, the planning and the forms.</td></tr>
<tr><td><code>CALLCENTER_AREA_PLANNING</code></td><td>Access to the area planning.</td></tr>
</tbody></table>

### Communication

<table data-full-width="true"><thead><tr><th width="460">Right</th><th>Description</th></tr></thead><tbody>
<tr><td><code>CALLCENTER_VIEW_WAYBILL</code></td><td>Allows access to the waybill.</td></tr>
<tr><td><code>CALLCENTER_VIEW_MESSAGE</code></td><td>Allows displaying messages.</td></tr>
<tr><td><code>CALLCENTER_TEAMS_WAYBILL</code></td><td>Access to the waybill of the teams.</td></tr>
<tr><td><code>CALLCENTER_SHOW_CUSTOM_EXPORT</code></td><td>Access to the custom exports page.</td></tr>
<tr><td><code>CALLCENTER_SEND_WEEK_NOTIFICATIONS</code></td><td>Allows sending notifications of the weekly appointments.</td></tr>
<tr><td><code>CALLCENTER_SEND_APPOINTMENT_NOTIFICATION</code></td><td>Allows sending the notification of an appointment.</td></tr>
<tr><td><code>CALLCENTER_SEND_APPOINTMENT_ANNOUNCE</code></td><td>Allows sending an appointment announcement.</td></tr>
<tr><td><code>CALLCENTER_MANAGE_NOTIFIABLES</code></td><td>Allows displaying and updating the Notifiable property of resources.</td></tr>
<tr><td><code>CALLCENTER_EXPORT_CSV</code></td><td>Allows exporting tables in CSV format.</td></tr>
<tr><td><code>CALLCENTER_CREATE_MESSAGE</code></td><td>Allows creating messages.</td></tr>
</tbody></table>

### Mapping

<table data-full-width="true"><thead><tr><th width="460">Right</th><th>Description</th></tr></thead><tbody>
<tr><td><code>CALLCENTER_VIEW_MAP_ACTIVITIES</code></td><td>Access to the activities map.</td></tr>
<tr><td><code>CALLCENTER_VIEW_MAP</code></td><td>Gives access to the map view.</td></tr>
<tr><td><code>CALLCENTER_SHOW_SEARCHAROUNDPAGE</code></td><td>Access to the nearby search page.</td></tr>
<tr><td><code>CALLCENTER_SHOW_ITIPAGE</code></td><td>Access to the itinerary calculation page.</td></tr>
<tr><td><code>CALLCENTER_PICK_COORDINATES</code></td><td>Access to the coordinate conversion page.</td></tr>
</tbody></table>

### Overnight stay

<table data-full-width="true"><thead><tr><th width="460">Right</th><th>Description</th></tr></thead><tbody>
<tr><td><code>CALLCENTER_VIEW_BUSINESS_LOCATIONS_PREFERENCES</code></td><td>Allows viewing the business location preferences.</td></tr>
<tr><td><code>CALLCENTER_UNCONFIRM_EXCEPTIONAL_LOCATIONS</code></td><td>Allows unconfirming exceptional locations.</td></tr>
<tr><td><code>CALLCENTER_SUGGEST_EXCEPTIONAL_LOCATIONS</code></td><td>Right to display the button that suggests overnight stays.</td></tr>
<tr><td><code>CALLCENTER_REMOVE_EXCEPTIONAL_LOCATION</code></td><td>Allows deleting exceptional locations.</td></tr>
<tr><td><code>CALLCENTER_MODIFY_EXCEPTIONAL_LOCATION</code></td><td>Allows updating exceptional locations.</td></tr>
<tr><td><code>CALLCENTER_MANAGE_EXCEPTIONAL_LOCATION</code></td><td>Access to managing exceptional locations.</td></tr>
<tr><td><code>CALLCENTER_MANAGE_BUSINESS_LOCATIONS</code></td><td>Access to managing business locations (hotels, and so on).</td></tr>
<tr><td><code>CALLCENTER_FORCE_EXCEPTIONAL_LOCATIONS</code></td><td>Right to force the creation or deletion of overnight stays.</td></tr>
<tr><td><code>CALLCENTER_CREATE_EXCEPTIONAL_LOCATION</code></td><td>Allows creating exceptional locations.</td></tr>
<tr><td><code>CALLCENTER_CONFIRM_EXCEPTIONAL_LOCATIONS</code></td><td>Allows confirming exceptional locations.</td></tr>
</tbody></table>

### Real-time tracking

<table data-full-width="true"><thead><tr><th width="460">Right</th><th>Description</th></tr></thead><tbody>
<tr><td><code>CALLCENTER_VEHICLE_TRACKING_ANALYZE</code></td><td>Access to the vehicle tracking analysis page.</td></tr>
<tr><td><code>CALLCENTER_VEHICLE_TRACKING</code></td><td>Access to vehicle tracking.</td></tr>
<tr><td><code>CALLCENTER_SHOW_TRAFFIC_PATTERN</code></td><td>Makes the road traffic statistics page accessible.</td></tr>
</tbody></table>

### Resource management

<table data-full-width="true"><thead><tr><th width="460">Right</th><th>Description</th></tr></thead><tbody>
<tr><td><code>CALLCENTER_VIEW_SECONDARY_WORKSITE_ASSIGNMENTS</code></td><td>Allows viewing the assignments to a secondary worksite.</td></tr>
<tr><td><code>CALLCENTER_VIEW_RESOURCE_CUSTOMERS</code></td><td>Allows displaying the customers and assignments (required, preferred, and so on) of a resource.</td></tr>
<tr><td><code>CALLCENTER_VIEW_JOBS</code></td><td>Allows displaying the job types.</td></tr>
<tr><td><code>CALLCENTER_VIEW_DUTIES</code></td><td>Allows access to on-call duties.</td></tr>
<tr><td><code>CALLCENTER_UPDATE_SECONDARY_WORKSITE_ASSIGNMENTS</code></td><td>Allows updating the assignments to a secondary worksite.</td></tr>
<tr><td><code>CALLCENTER_UPDATE_JOBS</code></td><td>Allows modifying jobs.</td></tr>
<tr><td><code>CALLCENTER_UPDATE_DUTIES</code></td><td>Allows modifying on-call duties.</td></tr>
<tr><td><code>CALLCENTER_MANAGE_SUPPLIES</code></td><td>Allows listing supplies and assigning them to resources for a specific period.</td></tr>
<tr><td><code>CALLCENTER_MANAGE_SECTORS</code></td><td>Allows managing sectors.</td></tr>
</tbody></table>

### Unavailabilities

<table data-full-width="true"><thead><tr><th width="460">Right</th><th>Description</th></tr></thead><tbody>
<tr><td><code>CALLCENTER_VIEW_UNAVAILABILITY_PREFERENCES</code></td><td>Allows viewing the unavailability preferences.</td></tr>
<tr><td><code>CALLCENTER_UNAVAILABILITY_ADD_FORCE</code></td><td>Forces unavailabilities to overlap with other unavailabilities.</td></tr>
<tr><td><code>CALLCENTER_TAKE_UNAVAILABILITY</code></td><td>Allows managing unavailabilities.</td></tr>
<tr><td><code>CALLCENTER_SEARCH_UNAVAILABILITY</code></td><td>Access to searching for unavailabilities.</td></tr>
<tr><td><code>CALLCENTER_REFUSE_LIST_UNAVAILABILITY</code></td><td>Allows switching a list of unavailabilities to the refused status.</td></tr>
<tr><td><code>CALLCENTER_EXPRESS_UNAVAILABILITY</code></td><td>Access to express unavailability entry.</td></tr>
<tr><td><code>CALLCENTER_EDIT_ALL_UNAVAILABILITY</code></td><td>Allows editing all types of unavailabilities.</td></tr>
<tr><td><code>CALLCENTER_ACCEPT_LIST_UNAVAILABILITY</code></td><td>Allows switching a list of unavailabilities to the accepted status.</td></tr>
</tbody></table>

### Custom action

<table data-full-width="true"><thead><tr><th width="460">Right</th><th>Description</th></tr></thead><tbody>
<tr><td><code>CALLCENTER_MYACTION_CUSTOMER_SHEET_5</code></td><td>Allows seeing the <strong>Custom action 5</strong> button in the customer forms.</td></tr>
<tr><td><code>CALLCENTER_MYACTION_CUSTOMER_SHEET_4</code></td><td>Allows seeing the <strong>Custom action 4</strong> button in the customer forms.</td></tr>
<tr><td><code>CALLCENTER_MYACTION_CUSTOMER_SHEET_3</code></td><td>Allows seeing the <strong>Custom action 3</strong> button in the customer forms.</td></tr>
<tr><td><code>CALLCENTER_MYACTION_CUSTOMER_SHEET_2</code></td><td>Allows seeing the <strong>Custom action 2</strong> button in the customer forms.</td></tr>
<tr><td><code>CALLCENTER_MYACTION_CUSTOMER_SHEET_1</code></td><td>Allows seeing the <strong>Custom action 1</strong> button in the customer forms.</td></tr>
<tr><td><code>CALLCENTER_MYACTION_CUSTOMER_MAP_5</code></td><td>Allows seeing the <strong>Custom action 5</strong> button in the customer map tooltips.</td></tr>
<tr><td><code>CALLCENTER_MYACTION_CUSTOMER_MAP_4</code></td><td>Allows seeing the <strong>Custom action 4</strong> button in the customer map tooltips.</td></tr>
<tr><td><code>CALLCENTER_MYACTION_CUSTOMER_MAP_3</code></td><td>Allows seeing the <strong>Custom action 3</strong> button in the customer map tooltips.</td></tr>
<tr><td><code>CALLCENTER_MYACTION_CUSTOMER_MAP_2</code></td><td>Allows seeing the <strong>Custom action 2</strong> button in the customer map tooltips.</td></tr>
<tr><td><code>CALLCENTER_MYACTION_CUSTOMER_MAP_1</code></td><td>Allows seeing the <strong>Custom action 1</strong> button in the customer map tooltips.</td></tr>
<tr><td><code>CALLCENTER_MYACTION_CUSTOMER_LIST_COLUMN_5</code></td><td>Allows seeing the <strong>Custom action 5</strong> button in the customer lists.</td></tr>
<tr><td><code>CALLCENTER_MYACTION_CUSTOMER_LIST_COLUMN_4</code></td><td>Allows seeing the <strong>Custom action 4</strong> button in the customer lists.</td></tr>
<tr><td><code>CALLCENTER_MYACTION_CUSTOMER_LIST_COLUMN_3</code></td><td>Allows seeing the <strong>Custom action 3</strong> button in the customer lists.</td></tr>
<tr><td><code>CALLCENTER_MYACTION_CUSTOMER_LIST_COLUMN_2</code></td><td>Allows seeing the <strong>Custom action 2</strong> button in the customer lists.</td></tr>
<tr><td><code>CALLCENTER_MYACTION_CUSTOMER_LIST_COLUMN_1</code></td><td>Allows seeing the <strong>Custom action 1</strong> button in the customer lists.</td></tr>
<tr><td><code>CALLCENTER_MYACTION_CUSTOMER_LIST_5</code></td><td>Allows seeing the <strong>Custom action 5</strong> button in the action buttons of the customer lists.</td></tr>
<tr><td><code>CALLCENTER_MYACTION_CUSTOMER_LIST_4</code></td><td>Allows seeing the <strong>Custom action 4</strong> button in the action buttons of the customer lists.</td></tr>
<tr><td><code>CALLCENTER_MYACTION_CUSTOMER_LIST_3</code></td><td>Allows seeing the <strong>Custom action 3</strong> button in the action buttons of the customer lists.</td></tr>
<tr><td><code>CALLCENTER_MYACTION_CUSTOMER_LIST_2</code></td><td>Allows seeing the <strong>Custom action 2</strong> button in the action buttons of the customer lists.</td></tr>
<tr><td><code>CALLCENTER_MYACTION_CUSTOMER_LIST_1</code></td><td>Allows seeing the <strong>Custom action 1</strong> button in the action buttons of the customer lists.</td></tr>
<tr><td><code>CALLCENTER_MYACTION_APPOINTMENT_SHEET_5</code></td><td>Allows seeing the <strong>Custom action 5</strong> button in the appointment forms.</td></tr>
<tr><td><code>CALLCENTER_MYACTION_APPOINTMENT_SHEET_4</code></td><td>Allows seeing the <strong>Custom action 4</strong> button in the appointment forms.</td></tr>
<tr><td><code>CALLCENTER_MYACTION_APPOINTMENT_SHEET_3</code></td><td>Allows seeing the <strong>Custom action 3</strong> button in the appointment forms.</td></tr>
<tr><td><code>CALLCENTER_MYACTION_APPOINTMENT_SHEET_2</code></td><td>Allows seeing the <strong>Custom action 2</strong> button in the appointment forms.</td></tr>
<tr><td><code>CALLCENTER_MYACTION_APPOINTMENT_SHEET_1</code></td><td>Allows seeing the <strong>Custom action 1</strong> button in the appointment forms.</td></tr>
<tr><td><code>CALLCENTER_MYACTION_APPOINTMENT_PLANNING_TOOLTIP_5</code></td><td>Allows seeing the <strong>Custom action 5</strong> button in the planning tooltips.</td></tr>
<tr><td><code>CALLCENTER_MYACTION_APPOINTMENT_PLANNING_TOOLTIP_4</code></td><td>Allows seeing the <strong>Custom action 4</strong> button in the planning tooltips.</td></tr>
<tr><td><code>CALLCENTER_MYACTION_APPOINTMENT_PLANNING_TOOLTIP_3</code></td><td>Allows seeing the <strong>Custom action 3</strong> button in the planning tooltips.</td></tr>
<tr><td><code>CALLCENTER_MYACTION_APPOINTMENT_PLANNING_TOOLTIP_2</code></td><td>Allows seeing the <strong>Custom action 2</strong> button in the planning tooltips.</td></tr>
<tr><td><code>CALLCENTER_MYACTION_APPOINTMENT_PLANNING_TOOLTIP_1</code></td><td>Allows seeing the <strong>Custom action 1</strong> button in the planning tooltips.</td></tr>
<tr><td><code>CALLCENTER_MYACTION_APPOINTMENT_MAP_5</code></td><td>Allows seeing the <strong>Custom action 5</strong> button in the map tooltips.</td></tr>
<tr><td><code>CALLCENTER_MYACTION_APPOINTMENT_MAP_4</code></td><td>Allows seeing the <strong>Custom action 4</strong> button in the map tooltips.</td></tr>
<tr><td><code>CALLCENTER_MYACTION_APPOINTMENT_MAP_3</code></td><td>Allows seeing the <strong>Custom action 3</strong> button in the map tooltips.</td></tr>
<tr><td><code>CALLCENTER_MYACTION_APPOINTMENT_MAP_2</code></td><td>Allows seeing the <strong>Custom action 2</strong> button in the map tooltips.</td></tr>
<tr><td><code>CALLCENTER_MYACTION_APPOINTMENT_MAP_1</code></td><td>Allows seeing the <strong>Custom action 1</strong> button in the map tooltips.</td></tr>
<tr><td><code>CALLCENTER_MYACTION_APPOINTMENT_LIST_COLUMN_5</code></td><td>Allows seeing the <strong>Custom action 5</strong> button in the appointment lists.</td></tr>
<tr><td><code>CALLCENTER_MYACTION_APPOINTMENT_LIST_COLUMN_4</code></td><td>Allows seeing the <strong>Custom action 4</strong> button in the appointment lists.</td></tr>
<tr><td><code>CALLCENTER_MYACTION_APPOINTMENT_LIST_COLUMN_3</code></td><td>Allows seeing the <strong>Custom action 3</strong> button in the appointment lists.</td></tr>
<tr><td><code>CALLCENTER_MYACTION_APPOINTMENT_LIST_COLUMN_2</code></td><td>Allows seeing the <strong>Custom action 2</strong> button in the appointment lists.</td></tr>
<tr><td><code>CALLCENTER_MYACTION_APPOINTMENT_LIST_COLUMN_1</code></td><td>Allows seeing the <strong>Custom action 1</strong> button in the appointment lists.</td></tr>
<tr><td><code>CALLCENTER_MYACTION_APPOINTMENT_LIST_5</code></td><td>Allows seeing the <strong>Custom action 5</strong> button in the action buttons of the appointment lists.</td></tr>
<tr><td><code>CALLCENTER_MYACTION_APPOINTMENT_LIST_4</code></td><td>Allows seeing the <strong>Custom action 4</strong> button in the action buttons of the appointment lists.</td></tr>
<tr><td><code>CALLCENTER_MYACTION_APPOINTMENT_LIST_3</code></td><td>Allows seeing the <strong>Custom action 3</strong> button in the action buttons of the appointment lists.</td></tr>
<tr><td><code>CALLCENTER_MYACTION_APPOINTMENT_LIST_2</code></td><td>Allows seeing the <strong>Custom action 2</strong> button in the action buttons of the appointment lists.</td></tr>
<tr><td><code>CALLCENTER_MYACTION_APPOINTMENT_LIST_1</code></td><td>Allows seeing the <strong>Custom action 1</strong> button in the action buttons of the appointment lists.</td></tr>
</tbody></table>

### Other

<table data-full-width="true"><thead><tr><th width="460">Right</th><th>Description</th></tr></thead><tbody>
<tr><td><code>CALLCENTER_VIEW_APPLICATION_LOG</code></td><td>Allows access to the list of application events.</td></tr>
<tr><td><code>CALLCENTER_SQL_QUERY_TOOL</code></td><td>Allows using predefined SQL query files.</td></tr>
<tr><td><code>CALLCENTER_SEND_TO_SUBCONTRACTOR</code></td><td>Allows sending an appointment to a subcontractor.</td></tr>
<tr><td><code>CALLCENTER_SEND_LIST_TO_SUBCONTRACTOR</code></td><td>Allows sending a list of appointments to a subcontractor.</td></tr>
<tr><td><code>CALLCENTER_PASSWORD_CHANGE</code></td><td>Allows the current user to change their password.</td></tr>
<tr><td><code>CALLCENTER_MESSAGE_ALERT_LIST</code></td><td>Access to the list of alert messages.</td></tr>
<tr><td><code>CALLCENTER_HIDE_APPOINTMENT_MODIFY_PAGE</code></td><td>Prevents access to the appointment edit page or wizard when the <code>APPOINTMENT_MODIFY</code> right is enabled, to restrict editing to the fields of the main form.</td></tr>
</tbody></table>

## Supervisor

### Scope

<table data-full-width="true"><thead><tr><th width="460">Right</th><th>Description</th></tr></thead><tbody>
<tr><td><code>SUPERVISOR_MANAGE_OWN_TEAM</code></td><td>Allows managing the resources of the user's own team.</td></tr>
<tr><td><code>SUPERVISOR_MANAGE_OWN_DOMAIN</code></td><td>Allows managing the areas of the user's own domain.</td></tr>
<tr><td><code>SUPERVISOR_MANAGE_OWN_AREA</code></td><td>Right to manage the user's own area.</td></tr>
<tr><td><code>SUPERVISOR_MANAGE_ALL_AREAS</code></td><td>Access to all areas.</td></tr>
<tr><td><code>SUPERVISOR_GUEST</code></td><td>Access to the Supervisor module.</td></tr>
<tr><td><code>SUPERVISOR_CHANGE_AREA</code></td><td>Allows changing the area of the active module.</td></tr>
</tbody></table>

### Control

<table data-full-width="true"><thead><tr><th width="460">Right</th><th>Description</th></tr></thead><tbody>
<tr><td><code>SUPERVISOR_OVERTIMES</code></td><td>Access to the overtime dashboard.</td></tr>
<tr><td><code>SUPERVISOR_JOURNAL</code></td><td>Access to viewing the appointment modification journal.</td></tr>
<tr><td><code>SUPERVISOR_GLOBAL_PLANNING_UNAVAILABILITIES</code></td><td>Access to the global unavailability planning.</td></tr>
<tr><td><code>SUPERVISOR_ACHIEVEMENT_DATES</code></td><td>Access to the fulfilment dates dashboard.</td></tr>
</tbody></table>

### Statistics

<table data-full-width="true"><thead><tr><th width="460">Right</th><th>Description</th></tr></thead><tbody>
<tr><td><code>SUPERVISOR_QUANTITY</code></td><td>Access to the dashboard of appointment booking quantities.</td></tr>
<tr><td><code>SUPERVISOR_QUALITY</code></td><td>Access to the dashboard of appointment booking quality.</td></tr>
<tr><td><code>SUPERVISOR_OBJECTIVE</code></td><td>Access to the objectives dashboard.</td></tr>
<tr><td><code>SUPERVISOR_INTERVENTIONS</code></td><td>Access to the tasks dashboard.</td></tr>
<tr><td><code>SUPERVISOR_AVAILABILITY</code></td><td>Access to the availability dashboard.</td></tr>
</tbody></table>

### Other

<table data-full-width="true"><thead><tr><th width="460">Right</th><th>Description</th></tr></thead><tbody>
<tr><td><code>SUPERVISOR_INTER_CUSTOMER_DISTANCES</code></td><td>Access to the inter-customer proximity dashboard.</td></tr>
<tr><td><code>SUPERVISOR_CUSTOMER_DISTANCES</code></td><td>Access to the customer distance matrix dashboard.</td></tr>
<tr><td><code>SUPERVISOR_CUSTOMER_BARYCENTERS</code></td><td>Access to the customer barycenter dashboard.</td></tr>
</tbody></table>

## Attendance

### Scope

<table data-full-width="true"><thead><tr><th width="460">Right</th><th>Description</th></tr></thead><tbody>
<tr><td><code>ATTENDANCEMANAGER_UPDATE_RESOURCEUSERLISTS</code></td><td>Access to modifying a resource list in the interface.</td></tr>
<tr><td><code>ATTENDANCEMANAGER_SHOW_WORKSITES</code></td><td>Allows selecting a worksite in the interface.</td></tr>
<tr><td><code>ATTENDANCEMANAGER_SHOW_TEAMS</code></td><td>Allows selecting a team in the interface.</td></tr>
<tr><td><code>ATTENDANCEMANAGER_SHOW_RESOURCEUSERLISTS</code></td><td>Access to selecting a resource list in the interface.</td></tr>
<tr><td><code>ATTENDANCEMANAGER_SHOW_AREA</code></td><td>Allows selecting the current area in the interface. All or some of the <code>ATTENDANCEMANAGER_SHOW_WORKSITES</code> and <code>ATTENDANCEMANAGER_SHOW_TEAMS</code> rights must also be granted to access the module.</td></tr>
<tr><td><code>ATTENDANCEMANAGER_MANAGE_PERIMETER</code></td><td>Allows managing the scope.</td></tr>
<tr><td><code>ATTENDANCEMANAGER_MANAGE_OWN_WORKSITE</code></td><td>Access to the user's own worksite.</td></tr>
<tr><td><code>ATTENDANCEMANAGER_MANAGE_OWN_TEAM</code></td><td>Access to the user's own team.</td></tr>
<tr><td><code>ATTENDANCEMANAGER_MANAGE_OWN_DOMAIN</code></td><td>Access to the areas of the user's own domain.</td></tr>
<tr><td><code>ATTENDANCEMANAGER_MANAGE_OWN_AREA</code></td><td>Access to the user's own area.</td></tr>
<tr><td><code>ATTENDANCEMANAGER_GUEST</code></td><td>Access to the Attendance module. All or some of the <code>ATTENDANCEMANAGER_SHOW_WORKSITES</code> and <code>ATTENDANCEMANAGER_SHOW_TEAMS</code> rights must also be granted to access the module.</td></tr>
<tr><td><code>ATTENDANCEMANAGER_DELETE_RESOURCEUSERLISTS</code></td><td>Access to deleting a resource list in the interface.</td></tr>
<tr><td><code>ATTENDANCEMANAGER_CREATE_RESOURCEUSERLISTS</code></td><td>Access to creating a resource list in the interface.</td></tr>
</tbody></table>

### Job

<table data-full-width="true"><thead><tr><th width="460">Right</th><th>Description</th></tr></thead><tbody>
<tr><td><code>ATTENDANCEMANAGER_VIEW_JOBTYPE</code></td><td>Allows displaying the job types.</td></tr>
<tr><td><code>ATTENDANCEMANAGER_VIEW_JOB</code></td><td>Allows displaying the job types.</td></tr>
<tr><td><code>ATTENDANCEMANAGER_UPDATE_JOB</code></td><td>Allows modifying jobs.</td></tr>
<tr><td><code>ATTENDANCEMANAGER_DELETE_JOB</code></td><td>Allows deleting jobs.</td></tr>
<tr><td><code>ATTENDANCEMANAGER_CREATE_JOB</code></td><td>Allows creating jobs.</td></tr>
</tbody></table>

### On-call day

<table data-full-width="true"><thead><tr><th width="460">Right</th><th>Description</th></tr></thead><tbody>
<tr><td><code>ATTENDANCEMANAGER_VIEW_DUTYTYPE</code></td><td>Allows displaying the on-call templates.</td></tr>
<tr><td><code>ATTENDANCEMANAGER_VIEW_DUTY</code></td><td>Allows displaying on-call duties.</td></tr>
<tr><td><code>ATTENDANCEMANAGER_UPDATE_DUTY</code></td><td>Allows modifying on-call duties.</td></tr>
<tr><td><code>ATTENDANCEMANAGER_DELETE_DUTY</code></td><td>Allows deleting on-call duties.</td></tr>
<tr><td><code>ATTENDANCEMANAGER_CREATE_DUTY</code></td><td>Allows creating on-call duties.</td></tr>
</tbody></table>

### On-call week

<table data-full-width="true"><thead><tr><th width="460">Right</th><th>Description</th></tr></thead><tbody>
<tr><td><code>ATTENDANCEMANAGER_VIEW_DUTYWEEKTYPE</code></td><td>Allows displaying the on-call week templates.</td></tr>
<tr><td><code>ATTENDANCEMANAGER_VIEW_DUTYWEEK</code></td><td>Allows displaying on-call weeks.</td></tr>
<tr><td><code>ATTENDANCEMANAGER_UPDATE_DUTYWEEK</code></td><td>Allows modifying on-call weeks.</td></tr>
<tr><td><code>ATTENDANCEMANAGER_DELETE_DUTYWEEK</code></td><td>Allows deleting on-call weeks.</td></tr>
<tr><td><code>ATTENDANCEMANAGER_CREATE_DUTYWEEK</code></td><td>Allows creating on-call weeks.</td></tr>
</tbody></table>

### Unavailability

<table data-full-width="true"><thead><tr><th width="460">Right</th><th>Description</th></tr></thead><tbody>
<tr><td><code>ATTENDANCEMANAGER_VIEW_UNAVAILABILITYTYPE</code></td><td>Allows displaying the unavailability types.</td></tr>
<tr><td><code>ATTENDANCEMANAGER_VIEW_UNAVAILABILITY</code></td><td>Allows displaying unavailabilities.</td></tr>
<tr><td><code>ATTENDANCEMANAGER_UPDATE_UNAVAILABILITY</code></td><td>Allows modifying unavailabilities.</td></tr>
<tr><td><code>ATTENDANCEMANAGER_DELETE_UNAVAILABILITY</code></td><td>Allows deleting unavailabilities.</td></tr>
<tr><td><code>ATTENDANCEMANAGER_CREATE_UNAVAILABILITY</code></td><td>Allows creating unavailabilities.</td></tr>
</tbody></table>

### Marker

<table data-full-width="true"><thead><tr><th width="460">Right</th><th>Description</th></tr></thead><tbody>
<tr><td><code>ATTENDANCEMANAGER_VIEW_AGENDAMARKERKIND</code></td><td>Allows displaying the marker kinds.</td></tr>
<tr><td><code>ATTENDANCEMANAGER_VIEW_AGENDAMARKER</code></td><td>Allows displaying markers.</td></tr>
<tr><td><code>ATTENDANCEMANAGER_UPDATE_AGENDAMARKER</code></td><td>Allows modifying markers.</td></tr>
<tr><td><code>ATTENDANCEMANAGER_PLANNING_DISPLAY_MARKERS</code></td><td>Do not display the markers in the planning.</td></tr>
<tr><td><code>ATTENDANCEMANAGER_DELETE_AGENDAMARKER</code></td><td>Allows deleting markers.</td></tr>
<tr><td><code>ATTENDANCEMANAGER_CREATE_AGENDAMARKER</code></td><td>Allows creating markers.</td></tr>
</tbody></table>

### Worked day

<table data-full-width="true"><thead><tr><th width="460">Right</th><th>Description</th></tr></thead><tbody>
<tr><td><code>ATTENDANCEMANAGER_VIEW_WORKEDDAYTYPE</code></td><td>Allows displaying the worked day templates.</td></tr>
<tr><td><code>ATTENDANCEMANAGER_VIEW_WORKEDDAY</code></td><td>Allows displaying worked days.</td></tr>
<tr><td><code>ATTENDANCEMANAGER_UPDATE_WORKEDDAY</code></td><td>Allows modifying worked days.</td></tr>
<tr><td><code>ATTENDANCEMANAGER_DELETE_WORKEDDAY</code></td><td>Allows deleting worked days.</td></tr>
<tr><td><code>ATTENDANCEMANAGER_CREATE_WORKEDDAY</code></td><td>Allows creating worked days.</td></tr>
</tbody></table>

### Worked week

<table data-full-width="true"><thead><tr><th width="460">Right</th><th>Description</th></tr></thead><tbody>
<tr><td><code>ATTENDANCEMANAGER_VIEW_WORKEDWEEKTYPE</code></td><td>Allows displaying the worked week templates.</td></tr>
<tr><td><code>ATTENDANCEMANAGER_VIEW_WORKEDWEEK</code></td><td>Allows displaying worked weeks.</td></tr>
<tr><td><code>ATTENDANCEMANAGER_UPDATE_WORKEDWEEK</code></td><td>Allows modifying worked weeks.</td></tr>
<tr><td><code>ATTENDANCEMANAGER_DELETE_WORKEDWEEK</code></td><td>Allows deleting worked weeks.</td></tr>
<tr><td><code>ATTENDANCEMANAGER_CREATE_WORKEDWEEK</code></td><td>Allows creating worked weeks.</td></tr>
</tbody></table>

### Reports

<table data-full-width="true"><thead><tr><th width="460">Right</th><th>Description</th></tr></thead><tbody>
<tr><td><code>ATTENDANCEMANAGER_REPORTS_EXPORTCSV</code></td><td>Allows exporting the reports as CSV.</td></tr>
<tr><td><code>ATTENDANCEMANAGER_REPORTS</code></td><td>Access to the Reports submodule.</td></tr>
</tbody></table>

### Printing

<table data-full-width="true"><thead><tr><th width="460">Right</th><th>Description</th></tr></thead><tbody>
<tr><td><code>ATTENDANCEMANAGER_PRINTSUMMARYPLANNING</code></td><td>Allows printing the custom report.</td></tr>
<tr><td><code>ATTENDANCEMANAGER_PRINTAGENDA</code></td><td>Allows printing a schedule.</td></tr>
</tbody></table>

### Communication

<table data-full-width="true"><thead><tr><th width="460">Right</th><th>Description</th></tr></thead><tbody>
<tr><td><code>ATTENDANCEMANAGER_VIEW_MESSAGE</code></td><td>Allows displaying messages.</td></tr>
<tr><td><code>ATTENDANCEMANAGER_CREATE_MESSAGE</code></td><td>Allows creating messages.</td></tr>
</tbody></table>

## Strategic

### Scope

<table data-full-width="true"><thead><tr><th width="460">Right</th><th>Description</th></tr></thead><tbody>
<tr><td><code>STRATEGIC_PLANNING_GUEST</code></td><td>Access to the Strategic planning module.</td></tr>
<tr><td><code>STRATEGIC_MANAGE_OWN_DOMAIN</code></td><td>Access to the areas of the user's own domain.</td></tr>
<tr><td><code>STRATEGIC_MANAGE_OWN_AREA</code></td><td>Access to the user's own area.</td></tr>
<tr><td><code>STRATEGIC_MANAGE_OWN_WORKSITE</code></td><td>Access to the user's own worksite.</td></tr>
<tr><td><code>STRATEGIC_MANAGE_OWN_TEAM</code></td><td>Access to the user's own team.</td></tr>
</tbody></table>

## My application 1

### Scope

<table data-full-width="true"><thead><tr><th width="460">Right</th><th>Description</th></tr></thead><tbody>
<tr><td><code>MYAPP1_MANAGE_OWN_DOMAIN</code></td><td>Access to the areas of the user's own domain.</td></tr>
<tr><td><code>MYAPP1_MANAGE_OWN_AREA</code></td><td>Access to the user's own area.</td></tr>
<tr><td><code>MYAPP1_GUEST</code></td><td>Access to the first custom module.</td></tr>
</tbody></table>

## Sectorization

### Scope

<table data-full-width="true"><thead><tr><th width="460">Right</th><th>Description</th></tr></thead><tbody>
<tr><td><code>DISTRICTING_GUEST</code></td><td>Access to the Sectorization module.</td></tr>
</tbody></table>

## Fulfilment

### Scope

<table data-full-width="true"><thead><tr><th width="460">Right</th><th>Description</th></tr></thead><tbody>
<tr><td><code>FULFILMENT_GUEST</code></td><td>Access to the live tracking of fulfilments.</td></tr>
</tbody></table>

## Tracking

### Scope

<table data-full-width="true"><thead><tr><th width="460">Right</th><th>Description</th></tr></thead><tbody>
<tr><td><code>TRACKFLEET_GUEST</code></td><td>Access to the GC_Location fleet tracking application (Tracking) in OTGS.</td></tr>
</tbody></table>

## Administration

### Scope

<table data-full-width="true"><thead><tr><th width="460">Right</th><th>Description</th></tr></thead><tbody>
<tr><td><code>ADMIN_GUEST</code></td><td>Access to the Administration module.</td></tr>
<tr><td><code>ADMIN_SEE_OPTIMIZATION_OF_ALL_AREAS</code></td><td>View the optimizations for all areas.</td></tr>
<tr><td><code>ADMIN_MANAGE_OWN_AREA</code></td><td>Right to manage the user's own area.</td></tr>
<tr><td><code>ADMIN_MANAGE_OWN_DOMAIN</code></td><td>Allows managing the areas of the user's own domain.</td></tr>
<tr><td><code>ADMIN_MANAGE_ALL_AREAS</code></td><td>Allows managing all areas.</td></tr>
<tr><td><code>ADMIN_MANAGE_OWN_TEAM</code></td><td>Allows managing the user's own team.</td></tr>
<tr><td><code>ADMIN_MANAGE_OWN_WORKSITE</code></td><td>Allows managing the user's own worksite.</td></tr>
</tbody></table>

### Global access

<table data-full-width="true"><thead><tr><th width="460">Right</th><th>Description</th></tr></thead><tbody>
<tr><td><code>ADMIN_UPDATE</code></td><td>Allows modification in Administration.</td></tr>
<tr><td><code>ADMIN_INSERT</code></td><td>Allows inserting data in Administration.</td></tr>
<tr><td><code>ADMIN_DELETE</code></td><td>Allows deleting data in Administration.</td></tr>
<tr><td><code>ADMIN_RESTRICTED_PROFILE_GRANT</code></td><td>Allows assigning a restricted profile to any user.</td></tr>
<tr><td><code>ADMIN_TOOLS</code></td><td>Access to the administration tools. <strong>Warning:</strong> do not use this right in production.</td></tr>
<tr><td><code>ADMIN_MOBILITY</code></td><td>Access to managing mobility devices.</td></tr>
<tr><td><code>ADMIN_VIEW_REFERENTIAL</code></td><td>Allows access to the reference data.</td></tr>
<tr><td><code>ADMIN_DEACTIVATE</code></td><td>Allows deactivating data in Administration.</td></tr>
<tr><td><code>ADMIN_VIEW_RIGHTS</code></td><td>Show the rights.</td></tr>
<tr><td><code>ADMIN_VIEW_ADDRESSES_STREETVIEW</code></td><td>Allows access to the Google Street View of an address.</td></tr>
<tr><td><code>ADMIN_HIDE_INTERNAL_ID</code></td><td>Hide the internal identifier of entities.</td></tr>
<tr><td><code>ADMIN_HIDE_EXTREF</code></td><td>Hide the external reference of entities (usually combined with the automatic assignment of external references).</td></tr>
<tr><td><code>ADMIN_ADMIN_TOOLS_MAP</code></td><td>Allows modifying the map coordinates.</td></tr>
</tbody></table>

### Human resource

<table data-full-width="true"><thead><tr><th width="460">Right</th><th>Description</th></tr></thead><tbody>
<tr><td><code>ADMIN_PARTICULAR_DAYS_CREATE</code></td><td>Allows creating particular days.</td></tr>
<tr><td><code>ADMIN_VIEW_RESOURCE</code></td><td>Show the human resources.</td></tr>
<tr><td><code>ADMIN_CREATE_RESOURCE</code></td><td>Allows creating a human resource.</td></tr>
<tr><td><code>ADMIN_UPDATE_RESOURCE</code></td><td>Allows updating a human resource.</td></tr>
<tr><td><code>ADMIN_DISABLE_RESOURCE</code></td><td>Allows deactivating a human resource.</td></tr>
<tr><td><code>ADMIN_UPDATE_RESOURCE_ADDRESS</code></td><td>Allows modifying the address of a resource.</td></tr>
<tr><td><code>ADMIN_UPDATE_RESOURCE_AUTHORIZATION</code></td><td>Allows modifying the authorizations of resources.</td></tr>
<tr><td><code>ADMIN_UPDATE_RESOURCE_EXPRESSUNAVAILABILITY</code></td><td>Allows modifying the express unavailabilities of resources.</td></tr>
<tr><td><code>ADMIN_UPDATE_RESOURCE_INFO</code></td><td>Allows modifying the information of resources.</td></tr>
<tr><td><code>ADMIN_UPDATE_RESOURCE_JOB</code></td><td>Allows modifying the jobs of resources.</td></tr>
<tr><td><code>ADMIN_UPDATE_RESOURCE_LIMIT</code></td><td>Allows modifying the limits of resources.</td></tr>
<tr><td><code>ADMIN_UPDATE_RESOURCE_PRIORITY</code></td><td>Allows modifying the priorities of resources.</td></tr>
<tr><td><code>ADMIN_UPDATE_RESOURCE_SKILL</code></td><td>Allows modifying the skills of resources.</td></tr>
<tr><td><code>ADMIN_UPDATE_RESOURCE_USER</code></td><td>Allows modifying the users of resources.</td></tr>
<tr><td><code>ADMIN_UPDATE_RESOURCE_WORKEDWEEK</code></td><td>Allows modifying the standard weeks of resources.</td></tr>
<tr><td><code>ADMIN_RESOURCE_ASSIGNMENT_UPDATE</code></td><td>Allows modifying the assignments of a human resource.</td></tr>
<tr><td><code>ADMIN_VIEW_RESOURCE_ASSIGNMENT</code></td><td>Allows access to the assignments of resources.</td></tr>
<tr><td><code>ADMIN_VIEW_RESOURCE_AUTHORIZATIONS</code></td><td>Allows managing the authorizations of a resource.</td></tr>
<tr><td><code>ADMIN_VIEW_RESOURCE_EXPRESSUNAVAILABILITY</code></td><td>Allows managing the express unavailabilities for resources.</td></tr>
<tr><td><code>ADMIN_VIEW_RESOURCE_JOB</code></td><td>Allows access to the jobs of resources.</td></tr>
<tr><td><code>ADMIN_VIEW_RESOURCE_LIMIT</code></td><td>Allows access to the limits of human resources.</td></tr>
<tr><td><code>ADMIN_VIEW_RESOURCE_LOCATION</code></td><td>Allows access to the addresses of resources.</td></tr>
<tr><td><code>ADMIN_VIEW_RESOURCE_PRIORITIES</code></td><td>Allows managing the priorities of a resource.</td></tr>
<tr><td><code>ADMIN_VIEW_RESOURCE_SKILL</code></td><td>Allows access to the skills of resources.</td></tr>
<tr><td><code>ADMIN_VIEW_RESOURCE_WORKEDWEEK</code></td><td>Allows access to the standard weeks of resources.</td></tr>
<tr><td><code>ADMIN_VIEW_RESOURCE_USERPERIMETER</code></td><td>Allows managing the scope of a resource.</td></tr>
<tr><td><code>ADMIN_UPDATE_RESOURCE_USERPERIMETER</code></td><td>Allows modifying the scope of a resource.</td></tr>
<tr><td><code>ADMIN_VIEW_RESOURCE_USERS</code></td><td>Show the user tab of resources.</td></tr>
<tr><td><code>ADMIN_VIEW_RESOURCE_PREFERENCES</code></td><td>Allows access to the preferences of resources.</td></tr>
<tr><td><code>ADMIN_UPDATE_RESOURCE_PREFERENCES</code></td><td>Allows modifying the preferences of resources.</td></tr>
<tr><td><code>ADMIN_VIEW_RESOURCE_VEHICLETYPE</code></td><td>Allows access to the vehicle types of resources.</td></tr>
<tr><td><code>ADMIN_UPDATE_RESOURCE_VEHICLETYPE</code></td><td>Allows updating the vehicle type of resources.</td></tr>
<tr><td><code>ADMIN_ACTIVATE_RESSOURCE</code></td><td>Allows activating human resources through Administration.</td></tr>
</tbody></table>

### Job

<table data-full-width="true"><thead><tr><th width="460">Right</th><th>Description</th></tr></thead><tbody>
<tr><td><code>ADMIN_VIEW_FUNCTION</code></td><td>Allows displaying the resource types.</td></tr>
<tr><td><code>ADMIN_CREATE_FUNCTION</code></td><td>Allows creating resource types.</td></tr>
<tr><td><code>ADMIN_UPDATE_FUNCTION</code></td><td>Allows updating resource types.</td></tr>
<tr><td><code>ADMIN_DISABLE_FUNCTION</code></td><td>Allows deactivating resource types.</td></tr>
<tr><td><code>ADMIN_VIEW_JOB</code></td><td>Allows displaying the job types.</td></tr>
<tr><td><code>ADMIN_CREATE_JOB</code></td><td>Allows creating jobs.</td></tr>
<tr><td><code>ADMIN_UPDATE_JOB</code></td><td>Allows modifying jobs.</td></tr>
<tr><td><code>ADMIN_DISABLE_JOB</code></td><td>Allows deactivating job types.</td></tr>
</tbody></table>

### Team

<table data-full-width="true"><thead><tr><th width="460">Right</th><th>Description</th></tr></thead><tbody>
<tr><td><code>ADMIN_MANAGE_TEAM_MEMBERS</code></td><td>Allows managing the composition of teams.</td></tr>
<tr><td><code>ADMIN_TEAM_LEADER</code></td><td>Allows managing the team leader.</td></tr>
<tr><td><code>ADMIN_TEAM_PARENT</code></td><td>Allows managing the parent team.</td></tr>
<tr><td><code>ADMIN_VIEW_TEAM</code></td><td>Show the teams.</td></tr>
<tr><td><code>ADMIN_CREATE_TEAM</code></td><td>Allows creating a team.</td></tr>
<tr><td><code>ADMIN_UPDATE_TEAM</code></td><td>Allows updating a team.</td></tr>
<tr><td><code>ADMIN_DISABLE_TEAM</code></td><td>Allows deactivating a team.</td></tr>
</tbody></table>

### Worksite

<table data-full-width="true"><thead><tr><th width="460">Right</th><th>Description</th></tr></thead><tbody>
<tr><td><code>ADMIN_VIEW_WORKSITE</code></td><td>Allows access to the worksites.</td></tr>
<tr><td><code>ADMIN_CREATE_WORKSITE</code></td><td>Allows creating a worksite.</td></tr>
<tr><td><code>ADMIN_UPDATE_WORKSITE</code></td><td>Allows updating a worksite.</td></tr>
<tr><td><code>ADMIN_DISABLE_WORKSITE</code></td><td>Allows deactivating a worksite.</td></tr>
</tbody></table>

### Domain

<table data-full-width="true"><thead><tr><th width="460">Right</th><th>Description</th></tr></thead><tbody>
<tr><td><code>ADMIN_VIEW_DOMAIN</code></td><td>Allows access to the domains.</td></tr>
<tr><td><code>ADMIN_CREATE_DOMAIN</code></td><td>Allows creating a domain.</td></tr>
<tr><td><code>ADMIN_UPDATE_DOMAIN</code></td><td>Allows updating a domain.</td></tr>
<tr><td><code>ADMIN_DISABLE_DOMAIN</code></td><td>Allows deactivating a domain.</td></tr>
</tbody></table>

### Subcontractor

<table data-full-width="true"><thead><tr><th width="460">Right</th><th>Description</th></tr></thead><tbody>
<tr><td><code>ADMIN_VIEW_SUBCONTRACTOR</code></td><td>Allows displaying subcontractors.</td></tr>
<tr><td><code>ADMIN_CREATE_SUBCONTRACTOR</code></td><td>Allows creating subcontractors.</td></tr>
<tr><td><code>ADMIN_UPDATE_SUBCONTRACTOR</code></td><td>Allows updating subcontractors.</td></tr>
<tr><td><code>ADMIN_DISABLE_SUBCONTRACTOR</code></td><td>Allows deactivating subcontractors.</td></tr>
</tbody></table>

### Supplies

<table data-full-width="true"><thead><tr><th width="460">Right</th><th>Description</th></tr></thead><tbody>
<tr><td><code>ADMIN_VIEW_SUPPLY</code></td><td>Allows displaying supplies.</td></tr>
<tr><td><code>ADMIN_CREATE_SUPPLY</code></td><td>Allows creating supplies.</td></tr>
<tr><td><code>ADMIN_UPDATE_SUPPLY</code></td><td>Allows updating supplies.</td></tr>
<tr><td><code>ADMIN_DISABLE_SUPPLY</code></td><td>Allows deactivating supplies.</td></tr>
<tr><td><code>ADMIN_VIEW_SUPPLY_PREFERENCES</code></td><td>Allows displaying the supply preferences.</td></tr>
<tr><td><code>ADMIN_UPDATE_SUPPLY_PREFERENCES</code></td><td>Allows updating the supply preferences.</td></tr>
</tbody></table>

### Area

<table data-full-width="true"><thead><tr><th width="460">Right</th><th>Description</th></tr></thead><tbody>
<tr><td><code>ADMIN_VIEW_AREA</code></td><td>Allows access to the areas.</td></tr>
<tr><td><code>ADMIN_CREATE_AREA</code></td><td>Allows creating an area.</td></tr>
<tr><td><code>ADMIN_UPDATE_AREA</code></td><td>Allows updating an area.</td></tr>
<tr><td><code>ADMIN_DISABLE_AREA</code></td><td>Allows deactivating an area.</td></tr>
<tr><td><code>ADMIN_ENABLE_DISABLE_AREA</code></td><td>Activate or deactivate an area.</td></tr>
</tbody></table>

### Sector

<table data-full-width="true"><thead><tr><th width="460">Right</th><th>Description</th></tr></thead><tbody>
<tr><td><code>ADMIN_VIEW_SECTOR</code></td><td>Allows access to the sectors.</td></tr>
<tr><td><code>ADMIN_CREATE_SECTOR</code></td><td>Allows creating sectors.</td></tr>
<tr><td><code>ADMIN_UPDATE_SECTOR</code></td><td>Allows updating sectors.</td></tr>
<tr><td><code>ADMIN_DISABLE_SECTOR</code></td><td>Allows deactivating sectors.</td></tr>
</tbody></table>

### Unavailability type

<table data-full-width="true"><thead><tr><th width="460">Right</th><th>Description</th></tr></thead><tbody>
<tr><td><code>ADMIN_VIEW_UNAVAILABILITY_TYPE</code></td><td>Allows access to the unavailability types.</td></tr>
<tr><td><code>ADMIN_CREATE_UNAVAILABILITY_TYPE</code></td><td>Allows creating unavailability types.</td></tr>
<tr><td><code>ADMIN_UPDATE_UNAVAILABILITY_TYPE</code></td><td>Allows updating unavailability types.</td></tr>
<tr><td><code>ADMIN_DISABLE_UNAVAILABILITY_TYPE</code></td><td>Allows deactivating unavailability types.</td></tr>
<tr><td><code>ADMIN_VIEW_UNAVAILABILITYTYPE_PREFERENCES</code></td><td>Allows viewing the unavailability type preferences.</td></tr>
<tr><td><code>ADMIN_UPDATE_UNAVAILABILITYTYPE_PREFERENCES</code></td><td>Allows updating the unavailability type preferences.</td></tr>
</tbody></table>

### On-call template

<table data-full-width="true"><thead><tr><th width="460">Right</th><th>Description</th></tr></thead><tbody>
<tr><td><code>ADMIN_VIEW_DUTY_TYPE</code></td><td>Allows displaying the on-call templates.</td></tr>
<tr><td><code>ADMIN_CREATE_DUTY_TYPE</code></td><td>Allows creating on-call templates.</td></tr>
<tr><td><code>ADMIN_UPDATE_DUTY_TYPE</code></td><td>Allows updating on-call templates.</td></tr>
<tr><td><code>ADMIN_DISABLE_DUTY_TYPE</code></td><td>Allows deactivating on-call templates.</td></tr>
<tr><td><code>ADMIN_VIEW_DUTYWEEK_TYPE</code></td><td>Allows displaying the on-call week templates.</td></tr>
<tr><td><code>ADMIN_CREATE_DUTYWEEK_TYPE</code></td><td>Allows creating on-call week templates.</td></tr>
<tr><td><code>ADMIN_UPDATE_DUTYWEEK_TYPE</code></td><td>Allows updating on-call week templates.</td></tr>
<tr><td><code>ADMIN_DISABLE_DUTYWEEK_TYPE</code></td><td>Allows deactivating on-call week templates.</td></tr>
</tbody></table>

### Product

<table data-full-width="true"><thead><tr><th width="460">Right</th><th>Description</th></tr></thead><tbody>
<tr><td><code>ADMIN_VIEW_PRODUCT</code></td><td>Allows displaying products.</td></tr>
<tr><td><code>ADMIN_CREATE_PRODUCT</code></td><td>Allows creating products.</td></tr>
<tr><td><code>ADMIN_UPDATE_PRODUCT</code></td><td>Allows updating products.</td></tr>
<tr><td><code>ADMIN_DISABLE_PRODUCT</code></td><td>Allows deactivating products.</td></tr>
<tr><td><code>ADMIN_VIEW_PRODUCT_PREFERENCES</code></td><td>Allows viewing the product preferences.</td></tr>
<tr><td><code>ADMIN_UPDATE_PRODUCT_PREFERENCES</code></td><td>Allows updating the product preferences.</td></tr>
</tbody></table>

### Product family

<table data-full-width="true"><thead><tr><th width="460">Right</th><th>Description</th></tr></thead><tbody>
<tr><td><code>ADMIN_VIEW_PRODUCT_FAMILY</code></td><td>Allows displaying product families.</td></tr>
<tr><td><code>ADMIN_CREATE_PRODUCT_FAMILY</code></td><td>Allows creating product families.</td></tr>
<tr><td><code>ADMIN_UPDATE_PRODUCT_FAMILY</code></td><td>Allows updating product families.</td></tr>
<tr><td><code>ADMIN_DISABLE_PRODUCT_FAMILY</code></td><td>Allows deactivating product families.</td></tr>
</tbody></table>

### Vehicle

<table data-full-width="true"><thead><tr><th width="460">Right</th><th>Description</th></tr></thead><tbody>
<tr><td><code>ADMIN_VIEW_VEHICLE</code></td><td>Allows displaying vehicles.</td></tr>
<tr><td><code>ADMIN_CREATE_VEHICLE</code></td><td>Allows creating vehicles.</td></tr>
<tr><td><code>ADMIN_UPDATE_VEHICLE</code></td><td>Allows updating vehicles.</td></tr>
<tr><td><code>ADMIN_DISABLE_VEHICLE</code></td><td>Allows deactivating vehicles.</td></tr>
</tbody></table>

### Tracking device

<table data-full-width="true"><thead><tr><th width="460">Right</th><th>Description</th></tr></thead><tbody>
<tr><td><code>ADMIN_VIEW_TRACKINGDEVICE</code></td><td>Allows displaying tracking devices.</td></tr>
<tr><td><code>ADMIN_CREATE_TRACKINGDEVICE</code></td><td>Allows creating tracking devices.</td></tr>
<tr><td><code>ADMIN_UPDATE_TRACKINGDEVICE</code></td><td>Allows updating tracking devices.</td></tr>
<tr><td><code>ADMIN_DISABLE_TRACKINGDEVICE</code></td><td>Allows deactivating tracking devices.</td></tr>
</tbody></table>

### Vehicle assignment to human resources

<table data-full-width="true"><thead><tr><th width="460">Right</th><th>Description</th></tr></thead><tbody>
<tr><td><code>ADMIN_VIEW_HR_VEHICLE_ASSIGNMENT</code></td><td>Allows displaying the assignments of vehicles to resources.</td></tr>
<tr><td><code>ADMIN_CREATE_HR_VEHICLE_ASSIGNMENT</code></td><td>Allows creating assignments of vehicles to resources.</td></tr>
<tr><td><code>ADMIN_UPDATE_HR_VEHICLE_ASSIGNMENT</code></td><td>Allows updating assignments of vehicles to resources.</td></tr>
<tr><td><code>ADMIN_DISABLE_HR_VEHICLE_ASSIGNMENT</code></td><td>Allows unassigning vehicles from resources.</td></tr>
<tr><td><code>ADMIN_SWAP_HR_VEHICLE_ASSIGNMENT</code></td><td>Allows swapping the assignments of vehicles to resources.</td></tr>
</tbody></table>

### Skill

<table data-full-width="true"><thead><tr><th width="460">Right</th><th>Description</th></tr></thead><tbody>
<tr><td><code>ADMIN_VIEW_QUALIFICATION</code></td><td>Allows displaying skills.</td></tr>
<tr><td><code>ADMIN_CREATE_QUALIFICATION</code></td><td>Allows creating skills.</td></tr>
<tr><td><code>ADMIN_UPDATE_QUALIFICATION</code></td><td>Allows updating skills.</td></tr>
<tr><td><code>ADMIN_DISABLE_QUALIFICATION</code></td><td>Allows deactivating skills.</td></tr>
</tbody></table>

### Authorization

<table data-full-width="true"><thead><tr><th width="460">Right</th><th>Description</th></tr></thead><tbody>
<tr><td><code>ADMIN_VIEW_AUTHORIZATION</code></td><td>Allows access to the authorizations.</td></tr>
<tr><td><code>ADMIN_CREATE_AUTHORIZATION</code></td><td>Allows creating authorizations.</td></tr>
<tr><td><code>ADMIN_UPDATE_AUTHORIZATION</code></td><td>Allows updating authorizations.</td></tr>
<tr><td><code>ADMIN_DISABLE_AUTHORIZATION</code></td><td>Allows deactivating authorizations.</td></tr>
</tbody></table>

### Task type

<table data-full-width="true"><thead><tr><th width="460">Right</th><th>Description</th></tr></thead><tbody>
<tr><td><code>ADMIN_VIEW_TASK_TYPE_GROUP</code></td><td>Allows access to the task type groups.</td></tr>
<tr><td><code>ADMIN_CREATE_TASK_TYPE_GROUP</code></td><td>Allows creating task type groups.</td></tr>
<tr><td><code>ADMIN_UPDATE_TASK_TYPE_GROUP</code></td><td>Allows updating task type groups.</td></tr>
<tr><td><code>ADMIN_DISABLE_TASK_TYPE_GROUP</code></td><td>Allows deactivating task type groups.</td></tr>
<tr><td><code>ADMIN_VIEW_TASKTYPE</code></td><td>Allows displaying the task types and their groups.</td></tr>
<tr><td><code>ADMIN_CREATE_TASKTYPE</code></td><td>Allows creating task types.</td></tr>
<tr><td><code>ADMIN_UPDATE_TASKTYPE</code></td><td>Allows updating task types.</td></tr>
<tr><td><code>ADMIN_DISABLE_TASKTYPE</code></td><td>Allows deactivating task types.</td></tr>
<tr><td><code>ADMIN_VIEW_TASKTYPE_DETAIL</code></td><td>Allows access to the task type details.</td></tr>
<tr><td><code>ADMIN_CREATE_TASKTYPE_DETAIL</code></td><td>Allows creating task type details.</td></tr>
<tr><td><code>ADMIN_UPDATE_TASKTYPE_DETAIL</code></td><td>Allows updating task type details.</td></tr>
<tr><td><code>ADMIN_DISABLE_TASKTYPE_DETAIL</code></td><td>Allows deactivating task type details.</td></tr>
</tbody></table>

### Objective

<table data-full-width="true"><thead><tr><th width="460">Right</th><th>Description</th></tr></thead><tbody>
<tr><td><code>ADMIN_VIEW_OBJECTIVE</code></td><td>Allows access to the objectives.</td></tr>
<tr><td><code>ADMIN_CREATE_OBJECTIVE</code></td><td>Allows creating objectives.</td></tr>
<tr><td><code>ADMIN_UPDATE_OBJECTIVE</code></td><td>Allows updating objectives.</td></tr>
<tr><td><code>ADMIN_DISABLE_OBJECTIVE</code></td><td>Allows deactivating objectives.</td></tr>
</tbody></table>

### Activity tracking

<table data-full-width="true"><thead><tr><th width="460">Right</th><th>Description</th></tr></thead><tbody>
<tr><td><code>ADMIN_VIEW_COMPLETION_TYPE</code></td><td>Allows access to the fulfilment statuses.</td></tr>
<tr><td><code>ADMIN_CREATE_COMPLETION_TYPE</code></td><td>Allows creating fulfilment statuses.</td></tr>
<tr><td><code>ADMIN_UPDATE_COMPLETION_TYPE</code></td><td>Allows updating fulfilment statuses.</td></tr>
<tr><td><code>ADMIN_DISABLE_COMPLETION_TYPE</code></td><td>Allows deactivating fulfilment statuses.</td></tr>
<tr><td><code>ADMIN_VIEW_TO_DO_NEXT_TYPE</code></td><td>Allows access to the follow-up action types.</td></tr>
<tr><td><code>ADMIN_CREATE_TO_DO_NEXT_TYPE</code></td><td>Allows creating follow-up action types.</td></tr>
<tr><td><code>ADMIN_UPDATE_TO_DO_NEXT_TYPE</code></td><td>Allows updating follow-up action types.</td></tr>
<tr><td><code>ADMIN_DISABLE_TO_DO_NEXT_TYPE</code></td><td>Allows deactivating follow-up action types.</td></tr>
</tbody></table>

### Calendar

<table data-full-width="true"><thead><tr><th width="460">Right</th><th>Description</th></tr></thead><tbody>
<tr><td><code>ADMIN_VIEW_OFFDAY_CALENDAR</code></td><td>Allows displaying the public holiday calendars.</td></tr>
<tr><td><code>ADMIN_CREATE_OFFDAY_CALENDAR</code></td><td>Allows creating public holidays.</td></tr>
<tr><td><code>ADMIN_UPDATE_OFFDAY_CALENDAR</code></td><td>Allows updating public holidays.</td></tr>
<tr><td><code>ADMIN_DISABLE_OFFDAY_CALENDAR</code></td><td>Allows deactivating public holidays.</td></tr>
<tr><td><code>ADMIN_VIEW_WORKEDDAYTYPE_CALENDAR</code></td><td>Allows displaying the calendar of day templates.</td></tr>
<tr><td><code>ADMIN_CREATE_WORKEDDAYTYPE_CALENDAR</code></td><td>Allows creating standard days.</td></tr>
<tr><td><code>ADMIN_UPDATE_WORKEDDAYTYPE_CALENDAR</code></td><td>Allows updating standard days.</td></tr>
<tr><td><code>ADMIN_DISABLE_WORKEDDAYTYPE_CALENDAR</code></td><td>Allows deactivating standard days.</td></tr>
<tr><td><code>ADMIN_VIEW_WORKEDWEEKTYPE_CALENDAR</code></td><td>Allows displaying the calendar of week templates.</td></tr>
<tr><td><code>ADMIN_CREATE_WORKEDWEEKTYPE_CALENDAR</code></td><td>Allows creating standard weeks.</td></tr>
<tr><td><code>ADMIN_UPDATE_WORKEDWEEKTYPE_CALENDAR</code></td><td>Allows updating standard weeks.</td></tr>
<tr><td><code>ADMIN_DISABLE_WORKEDWEEKTYPE_CALENDAR</code></td><td>Allows deactivating standard weeks.</td></tr>
<tr><td><code>ADMIN_VIEW_SELLING_PERIOD</code></td><td>Allows access to the selling periods.</td></tr>
<tr><td><code>ADMIN_CREATE_SELLING_PERIOD</code></td><td>Allows creating selling periods.</td></tr>
<tr><td><code>ADMIN_UPDATE_SELLING_PERIOD</code></td><td>Allows updating selling periods.</td></tr>
<tr><td><code>ADMIN_DISABLE_SELLING_PERIOD</code></td><td>Allows deactivating selling periods.</td></tr>
</tbody></table>

### Configuration

<table data-full-width="true"><thead><tr><th width="460">Right</th><th>Description</th></tr></thead><tbody>
<tr><td><code>ADMIN_CUSTOMIZATION</code></td><td>Access customization.</td></tr>
<tr><td><code>ADMIN_XMLFILE_PARAMDEF</code></td><td>Allows access to importing and exporting the configuration XML file.</td></tr>
<tr><td><code>ADMIN_XMLFILE_REFERENTIAL</code></td><td>Allows access to importing the reference data XML files.</td></tr>
<tr><td><code>ADMIN_XMLFILE_APPT</code></td><td>Allows access to importing the XML files that create, modify and delete appointments.</td></tr>
<tr><td><code>ADMIN_XMLFILE_LOG</code></td><td>Change the logging level.</td></tr>
<tr><td><code>ADMIN_SYSTEM_INFO</code></td><td>Allows managing the system information.</td></tr>
<tr><td><code>ADMIN_PROPERTIES_UPDATE</code></td><td>Allows updating the properties of resources.</td></tr>
<tr><td><code>ADMIN_LOGOS_UPDATE</code></td><td>Allows updating the logos.</td></tr>
</tbody></table>

### Optimization

<table data-full-width="true"><thead><tr><th width="460">Right</th><th>Description</th></tr></thead><tbody>
<tr><td><code>ADMIN_OPTIMIZATION_SERVICE</code></td><td>Access to the optimization service.</td></tr>
<tr><td><code>ADMIN_UPDATE_OPTIMIZATION_SERVICE</code></td><td>Update, stop and start the optimization service.</td></tr>
<tr><td><code>ADMIN_START_OPTIM_DURING_VALIDITY_PERIOD</code></td><td>Start a manual optimization during its validity period.</td></tr>
<tr><td><code>ADMIN_START_OPTIMIZATION_AT_ANY_TIME</code></td><td>Start a manual optimization at any time.</td></tr>
<tr><td><code>ADMIN_STOP_AUTOMATIC_OPTIMIZATION</code></td><td>Stop an automatic optimization.</td></tr>
<tr><td><code>ADMIN_STOP_MANUAL_OPTIMIZATION</code></td><td>Stop a manual optimization.</td></tr>
<tr><td><code>ADMIN_OPTIM_PARAM</code></td><td>Access to the page for modifying the optimization parameters.</td></tr>
<tr><td><code>ADMIN_MANAGE_OPTIMIZATION_ON_IDLE</code></td><td>Allows managing continuous optimization.</td></tr>
<tr><td><code>ADMIN_MANAGE_PLANNING_FILLER_EMERGENCY</code></td><td>Allows managing the emergency filling of the planning.</td></tr>
</tbody></table>

### Technical exchanges

<table data-full-width="true"><thead><tr><th width="460">Right</th><th>Description</th></tr></thead><tbody>
<tr><td><code>ADMIN_EXPORT_TOMTOM_OV2_POI</code></td><td>Allows access to exporting POIs (ov2) to TomTom.</td></tr>
<tr><td><code>ADMIN_IMPORT_CSV</code></td><td>Access to the CSV import.</td></tr>
<tr><td><code>ADMIN_EXPORT_CSV</code></td><td>Access to the CSV export.</td></tr>
<tr><td><code>ADMIN_EXTERN_APPLI</code></td><td>Allows access to the OTGS API documentation pages.</td></tr>
<tr><td><code>ADMIN_EXTERN_APPLI_TESTMODE</code></td><td>Allows testing the OTGS API.</td></tr>
</tbody></table>

### Exceptional location type

<table data-full-width="true"><thead><tr><th width="460">Right</th><th>Description</th></tr></thead><tbody>
<tr><td><code>ADMIN_VIEW_EXCEPTLOCATION_TYPE</code></td><td>Allows displaying the exceptional location types.</td></tr>
<tr><td><code>ADMIN_CREATE_EXCEPTLOCATION_TYPE</code></td><td>Allows creating exceptional location types.</td></tr>
<tr><td><code>ADMIN_UPDATE_EXCEPTLOCATION_TYPE</code></td><td>Allows updating exceptional location types.</td></tr>
<tr><td><code>ADMIN_DISABLE_EXCEPTLOCATION_TYPE</code></td><td>Allows deactivating exceptional location types.</td></tr>
</tbody></table>

### Typology

<table data-full-width="true"><thead><tr><th width="460">Right</th><th>Description</th></tr></thead><tbody>
<tr><td><code>ADMIN_VIEW_TYPOLOGY</code></td><td>Allows displaying typologies.</td></tr>
<tr><td><code>ADMIN_CREATE_TYPOLOGY</code></td><td>Allows creating typologies.</td></tr>
<tr><td><code>ADMIN_UPDATE_TYPOLOGY</code></td><td>Allows updating typologies.</td></tr>
<tr><td><code>ADMIN_DISABLE_TYPOLOGY</code></td><td>Allows deactivating typologies.</td></tr>
</tbody></table>

### Other

<table data-full-width="true"><thead><tr><th width="460">Right</th><th>Description</th></tr></thead><tbody>
<tr><td><code>ADMIN_UPDATE_LICENSE</code></td><td>Allows updating the application license.</td></tr>
<tr><td><code>ADMIN_SHOW_SQL_TOOL</code></td><td>Allows viewing the SQL queries page.</td></tr>
<tr><td><code>ADMIN_CAN_DEFINE_COLOR</code></td><td>Allows updating the colors.</td></tr>
<tr><td><code>ADMIN_DELETE_DOCUMENTS</code></td><td>Allows deleting documents.</td></tr>
<tr><td><code>ADMIN_ADD_DOCUMENTS</code></td><td>Allows adding documents.</td></tr>
<tr><td><code>ADMIN_CAN_DEFINE_ENTITYCOLOR</code></td><td>Allows updating the colors of entities.</td></tr>
</tbody></table>

## Documentation

### Scope

<table data-full-width="true"><thead><tr><th width="460">Right</th><th>Description</th></tr></thead><tbody>
<tr><td><code>DOC_GUEST</code></td><td>Access to the Documentation module.</td></tr>
</tbody></table>
