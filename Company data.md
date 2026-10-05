Company data
-
Opti-Time Reference Guide

[![ Documentation](./images/logo_geoconcept_3.png)](https://mynomadia.com/privatedoc/9LLcWh7j74sENa54/optitime-doc/docs/en/otgs-reference-book/index.html)

# Opti-Time Reference Guide Administration

|  |  |
| --- | --- |
| [Sidebar](https://mynomadia.com/privatedoc/9LLcWh7j74sENa54/optitime-doc/docs/en/otgs-reference-book/donnees.html# "Hide TOC tree") | [Prev](https://mynomadia.com/privatedoc/9LLcWh7j74sENa54/optitime-doc/docs/en/otgs-reference-book/generalites.html) | [Up](https://mynomadia.com/privatedoc/9LLcWh7j74sENa54/optitime-doc/docs/en/otgs-reference-book/module-administration.html) | [Next](https://mynomadia.com/privatedoc/9LLcWh7j74sENa54/optitime-doc/docs/en/otgs-reference-book/optimisation.html) |

### Company data

The day-to-day organisation and planning for a mobile resource is saved in the application, so appointments can be allocated
as a function of availability and logistical considerations.
Data such as the resource identities themselves, the composition of teams, geographic location and so on, are assembled here
in a kind of information hub.

#### Human resource

This is the representation in the application of each resource (or mobile consultant) who might be called upon to deliver
a service or attend an appointment. You can, of course, save details of non-skilled resources who would nevertheless be able
to fulfill appointments, for example, tele-operators, administrators, or department managers. In this case, all the information
items are not completely necessary (usual location, journey duration, etc).

You can create, [create](https://mynomadia.com/privatedoc/9LLcWh7j74sENa54/optitime-doc/docs/en/otgs-reference-book/generalites.html#creation "Create a new data item"), [consult or edit](https://mynomadia.com/privatedoc/9LLcWh7j74sENa54/optitime-doc/docs/en/otgs-reference-book/generalites.html#modification "Consult or edit an existing data item") a human resource.

|  |  |
| --- | --- |
| [Note] | Note |
| To de-activate a resource, an end-of-activity date needs to be declared for the resource, in the [Information](https://mynomadia.com/privatedoc/9LLcWh7j74sENa54/optitime-doc/docs/en/otgs-reference-book/donnees.html#RH-info "Information tab") tab. |

##### List of human resources

Access to the interface for managing human resources is via a click on the link in the Human resource link in the "[Company data](https://mynomadia.com/privatedoc/9LLcWh7j74sENa54/optitime-doc/docs/en/otgs-reference-book/donnees.html "Company data")" dialogue item.

Before accessing the [list](https://mynomadia.com/privatedoc/9LLcWh7j74sENa54/optitime-doc/docs/en/otgs-reference-book/generalites.html#generalite-liste "Data home page") of human resources, you should run a search on the database.

Human Resource menu interface:

![images/ref/admin/RH-recherche.png](./images/RH-recherche.png)

The search interface proposes the following filters:

- The first letters of, or a sequence within, the **Name** or **Forename**, without taking upper and lower case into account. For example, so your search will find «MARC» as well as «Matthew»;
- The dates (**From**, **To**) allow you to filter on resources who no longer work for the company ([**Length of time in company**](https://mynomadia.com/privatedoc/9LLcWh7j74sENa54/optitime-doc/docs/en/otgs-reference-book/donnees.html#RH-info "Information tab") field);
- The other fields correspond to fields in the [resource form](https://mynomadia.com/privatedoc/9LLcWh7j74sENa54/optitime-doc/docs/en/otgs-reference-book/donnees.html#fiche-ressource "Resource form").

|  |  |
| --- | --- |
| [Tip] | Tip |
| Put an empty string to display the full list of resources. |

If the result of the search returns more than 20 lines, then a Next link allows you to navigate in the search.

The ![images/ref/buttons/bouton-exporter-resultat.png](./images/bouton-exporter-resultat.png) button enables export of the result of the search in .csv format, with the following information being exported: Name, First name, Login, Profile, Area, Identifier and Badge number.

##### Resource form

The [form](https://mynomadia.com/privatedoc/9LLcWh7j74sENa54/optitime-doc/docs/en/otgs-reference-book/generalites.html#generalite-fiche "Data form") "Human resource" is made up of the following tabs:  
[Information](https://mynomadia.com/privatedoc/9LLcWh7j74sENa54/optitime-doc/docs/en/otgs-reference-book/donnees.html#RH-info "Information tab"), [Affiliation](https://mynomadia.com/privatedoc/9LLcWh7j74sENa54/optitime-doc/docs/en/otgs-reference-book/donnees.html#RH-affectation "Assignment tab"), [Address](https://mynomadia.com/privatedoc/9LLcWh7j74sENa54/optitime-doc/docs/en/otgs-reference-book/donnees.html#RH-adresse "Address tab"), [User](https://mynomadia.com/privatedoc/9LLcWh7j74sENa54/optitime-doc/docs/en/otgs-reference-book/donnees.html#RH-utilisateur "User tab"), [Perimeter](https://mynomadia.com/privatedoc/9LLcWh7j74sENa54/optitime-doc/docs/en/otgs-reference-book/donnees.html#RH-perimetre "Perimeter tab"), [Standard week](https://mynomadia.com/privatedoc/9LLcWh7j74sENa54/optitime-doc/docs/en/otgs-reference-book/donnees.html#RH-semaine "Typical week tab"), [Limits](https://mynomadia.com/privatedoc/9LLcWh7j74sENa54/optitime-doc/docs/en/otgs-reference-book/donnees.html#RH-limite "Limits tab"), [Stop points](https://mynomadia.com/privatedoc/9LLcWh7j74sENa54/optitime-doc/docs/en/otgs-reference-book/donnees.html#RH-passage-depot "Stop points tab"), [Skills](https://mynomadia.com/privatedoc/9LLcWh7j74sENa54/optitime-doc/docs/en/otgs-reference-book/donnees.html#RH-comp "Skills tab"), [Authorizations](https://mynomadia.com/privatedoc/9LLcWh7j74sENa54/optitime-doc/docs/en/otgs-reference-book/donnees.html#RH-autorisation "Authorisations tab"), [Priorities](https://mynomadia.com/privatedoc/9LLcWh7j74sENa54/optitime-doc/docs/en/otgs-reference-book/donnees.html#RH-priorite "Priorities tab"), [Posts](https://mynomadia.com/privatedoc/9LLcWh7j74sENa54/optitime-doc/docs/en/otgs-reference-book/donnees.html#RH-poste "Posts tab") and [Vehicle](https://mynomadia.com/privatedoc/9LLcWh7j74sENa54/optitime-doc/docs/en/otgs-reference-book/donnees.html#RH-vehicule "Vehicle tab").

##### Information tab

Information tab

![images/ref/admin/RH-infos.png](./images/RH-infos.png)

- On the left of the screen, you can import a photo of the resource. Moving the mouse cursor over the resource’s photo, two
  icons appear: the ![images/ref/buttons/photo.png](./images/photo.png) button allows you to import this photo, and the ![images/ref/buttons/poubelle.png](./images/poubelle.png) button can be used to delete it.
- **External reference** for the mobile resource
- Identification: **Name, First name, Company ID** (the company ID corresponds to the [external identifier](https://mynomadia.com/privatedoc/9LLcWh7j74sENa54/optitime-doc/docs/en/otgs-reference-book/_glossary.html#Extref) of the resource), **Badge number**, **Description**.
- **Job held**: specifies the [function](https://mynomadia.com/privatedoc/9LLcWh7j74sENa54/optitime-doc/docs/en/otgs-reference-book/donnees.html#type-expertise "Function") corresponding to the resource. This information conditions the type of intervention (or offering) that the resource can offer
  when making an appointment. Remember that an intervention type will depend on two criteria: the type of post occupied and
  the competencies the resource possesses. The competencies of the resource are described in the sub-section [Skills](https://mynomadia.com/privatedoc/9LLcWh7j74sENa54/optitime-doc/docs/en/otgs-reference-book/donnees.html#RH-comp "Skills tab").

  |  |  |
  | --- | --- |
  | [Tip] | Tip |
  | Clicking on the images/ref/buttons/bouton-prendre-rdv.png check-box, information about the [function](https://mynomadia.com/privatedoc/9LLcWh7j74sENa54/optitime-doc/docs/en/otgs-reference-book/donnees.html#type-expertise "Function") are retrieved in the resource’s form. |
- **Mobile resource**: declares the resource to be mobile. This check-box should be checked to authorise the taking of an appointment for the resource
  in the knowledge that he/she is mobile. This parameter serves mainly to distinguish mobile resources (or advisors in the field)
  from other people (managers, supervisors, on-line advisors) who are never called upon to fulfill appointments.
- **Length of time in company**: start and finish date of the work contract. This information serves for handling of the work contract life cycle: arrival
  in the company, and departure (resignation, retirement, etc.). Company transfers are handled in particular by the «stop» date
  for a mobile resource on a given date (for a given area, for example) and its re-creation in the context of another assignment
  (another area, for example).
- **Period of availability**: the start and finish date for taking the resource into account in the planning process. This information means you can include
  a time delay between the start of the work contract and making the resource available for appointments made by the application.
  If no date is supplied, the resource is considered to be available from the start of their work contract, and so it follows
  that an appointment may be taken for this resource from day 1 of their employment.
- **Number of employees**: specifies the number of employees associated to this resource. This feature is useful as it means the application authorises
  creation of multi-employee resources. A team (binome or pair) is a resource made up of two employees.
- Resource’s contact details at home: **Personal email**, **Personal fax** and **Home telephone number**;
- Professional contact details for the resource: **Professional email**, **Professional fax** and **Professional telephone number**;
- Mobile phone contact details: **mobile email address** (some operators offer email addresses that are readable on a mobile phone, and **telephone** **mobile** as a text message).

##### Assignment tab

Affiliation tab

![images/ref/admin/RH-affectation.png](./images/RH-affectation.png)

Part (1): each resource can be affiliated to two defined entities globally in the application.

- Name of the **Team** of affiliation: this will be the hierarchical affiliation within the overall structure (*Note*: remember that this information does not feature in the optimization constraints). This information will tell you the **Area** of affiliation, where it is the case that each [team](https://mynomadia.com/privatedoc/9LLcWh7j74sENa54/optitime-doc/docs/en/otgs-reference-book/donnees.html#equipe "Team") is affiliated to a particular [area](https://mynomadia.com/privatedoc/9LLcWh7j74sENa54/optitime-doc/docs/en/otgs-reference-book/donnees.html#region "Area").
- Name of the main **Worksite**: a resource has a site of affiliation. They can intervene at each of the other worksites. This will allow the user to define
  their position in the case of tasks to accomplish on one of these Worksites. This could be an office, a branch office, an
  agency, a depot, etc.

Part (2): affiliation of a resource to one or several secondary worksites.  
You can [add](https://mynomadia.com/privatedoc/9LLcWh7j74sENa54/optitime-doc/docs/en/otgs-reference-book/generalites.html#ajout "Adding data") or [delete](https://mynomadia.com/privatedoc/9LLcWh7j74sENa54/optitime-doc/docs/en/otgs-reference-book/generalites.html#suppression "De-activating / Deleting a data item") additional worksites to the resource.  
This function allows you to assign one or several secondary worksites to the resource with a [function](https://mynomadia.com/privatedoc/9LLcWh7j74sENa54/optitime-doc/docs/en/otgs-reference-book/donnees.html#type-expertise "Function") and a preference.  
Resources that possess a secondary worksite will be able to perform an intervention situated on this same site even if it
is not their main site of affiliation.

Affiliation of a resource to one or several secondary worksites

![images/ref/admin/RH-secteurs-1.png](./images/RH-secteurs-1.png)

- The **Intervention sector** field; name of the secondary worksite. This may correspond either to a [worksite](https://mynomadia.com/privatedoc/9LLcWh7j74sENa54/optitime-doc/docs/en/otgs-reference-book/donnees.html#site-travail "Worksite"), or to a [sector](https://mynomadia.com/privatedoc/9LLcWh7j74sENa54/optitime-doc/docs/en/otgs-reference-book/donnees.html#secteur "Sector (or Intervention sector)").
- The **From** and **To** fields serve to define the start and finish dates for taking the resource into account in the plannings of the secondary
  worksite.
  If no date has been entered, the sector is assigned in a permanent way to the resource.
- The **Period** field serves to define a customised period of time. To create a period, click on the ![images/ref/buttons/bouton-add.png](./images/bouton-add.png) button located to the right of the drop-down list.
- The **Function** serves to choose the [the profile](https://mynomadia.com/privatedoc/9LLcWh7j74sENa54/optitime-doc/docs/en/otgs-reference-book/donnees.html#type-expertise "Function") that will be assigned to the resource during this period, in other words, the different priorities with which the intervention
  types can be scheduled for him or her.
- In **merge mode** you can define whether the resource type selected will replace the other types of resource assigned during this period (*exclusive* mode) or whether it will be added to the other types assigned (*default* mode).
- The **preference** item serves to assign a lesser or greater weight (from 0 to 100) with which to take into account this secondary worksite
  at the time the appointment for this resource is scheduled.

The list of intervention sectors displays at the bottom of the screen.

Secondary intervention sectors

![images/ref/admin/RH-secteurs-2.png](./images/RH-secteurs-2.png)

##### Address tab

This data item serves in general to define the start and arrival points for each daily itinerary. For example, it could be
the home address of the resource(s).

Address tab

![images/ref/admin/RH-adresse.png](./images/RH-adresse.png)

To fill in the start address, refer to the section of this guide, [Address](https://mynomadia.com/privatedoc/9LLcWh7j74sENa54/optitime-doc/docs/en/otgs-reference-book/intro-geocodage.html "The geocoding").

|  |  |
| --- | --- |
| [Warning] | Warning |
| If this information is not entered, it is the worksite address that is taken into account. |

|  |  |
| --- | --- |
| [Tip] | Tip |
| To verify that the address has been validated correctly, the X and Y coordinates should not be 0. |

Clicking on Access Plan, a map is displayed and localises the geocoded addresses.

Checking **Use a Return from work address**, it is possible to declare an address for the return from work to the application that is different to that of the start
point.
For example, the resource may commence their route leaving from their home, and finish it at the depot.

##### User tab

Defining a resource as user

User tab

![images/ref/admin/RH-utilisateur.png](./images/RH-utilisateur.png)

- **Identifier**: this provides the resource’s internal identifier (non-modifiable).
- **Profile**: a profile corresponds to the sum total of Access rights granted to the user. See the chapter on [Managing user accounts](https://mynomadia.com/privatedoc/9LLcWh7j74sENa54/optitime-doc/docs/en/otgs-reference-book/utilisateurs.html "User handling")
- **Identification mode**: declares if the user is handled by an external provider (LDAP, SSO, other). The **Password** field is not used in this instance.
- **User**: this is a login that enables the resource to connect to the application, and so to become a user. To bind user to a Single
  Sign-On (SSO) provider account, login must be the e-mail address declared for this third-party account, in lowercase.
- **Password**: each user can have a password that is specific to that user. This field is not used in the case of a connection through
  an external identification provider (see above).
- **Point of entry to the application**: depending on the resource’s profile, the administrator can define on which home page the resource will work in Opti-Time
  (the portal, call centre, supervision module, attendance module, etc…). You will need to have chosen a profile to be able
  to select an entry point.

|  |  |
| --- | --- |
| [Note] | Note |
| See also:  - EXPLOITATION > Configuring SSO access in Opti-Time - REFERENCE GUIDE > Introduction > Running the application > [Authenticating through Single Sign-On (SSO)](https://mynomadia.com/privatedoc/9LLcWh7j74sENa54/optitime-doc/docs/en/otgs-reference-book/otgs-connexion.html#sso) |

##### Perimeter tab

According to which user rights are assigned, this tab allows you to select any possible favourites for the area, the team
and the site, for the purpose of drawing up a perimeter for this resource.

Perimeter tab

![images/ref/admin/RH-perimetre.png](./images/RH-perimetre.png)

This perimeter can be applied in the Planning and Attendance modules so only objects belonging to this perimeter are displayed, independently of the area of affiliation for the resource
as defined under [Affiliation tab](https://mynomadia.com/privatedoc/9LLcWh7j74sENa54/optitime-doc/docs/en/otgs-reference-book/donnees.html#RH-affectation "Assignment tab").

##### Typical week tab

Typical week tab

![images/ref/admin/RH-semaine-type.png](./images/RH-semaine-type.png)

This consists of saving **Working hours** for each resource, as a function of the **Day of Week**. Each resource has their own Standard Working Week. This data item stores working hours for Monday, Tuesday, etc.

|  |  |
| --- | --- |
| [Note] | Note |
| There is only one Typical Monday per Resource, only one Tuesday, etc. The variations are handled by unavailabilities that are entered by the resource themselves, or by team leaders via the application’s general portal. |

First, select the **local time zone** to which the resource is affiliated.

Part (1) "Typical working week":

- **Day of the Week** (Monday, Tuesday, etc…);
- **Working hours**: this is the maximum length of the working day, for example 08:00-20:00;
- **Lunch break** and **Length of break**: the start and end times of the lunch break represent the length of the period during which the break must be taken (Example:
  one-hour break to be taken between 12.00 and 14.00);

  |  |  |
  | --- | --- |
  | [Note] | Note |
  | A value of 00:00 signifies that the parameter is not taken into account in the optimization. |

+
\* **Worked day**: indicates whether the resource can perform interventions that day or not;
\* **Night away possible**: indicates whether the optimization engine can schedule a night away for that particular day;

|  |  |
| --- | --- |
| [Warning] | Warning |
| To use nights away, you will need to define the number of nights away possible in the [Limits](https://mynomadia.com/privatedoc/9LLcWh7j74sENa54/optitime-doc/docs/en/otgs-reference-book/donnees.html#RH-limite "Limits tab") tab. |

Part (2) "Custom hours":

It is possible to [add](https://mynomadia.com/privatedoc/9LLcWh7j74sENa54/optitime-doc/docs/en/otgs-reference-book/generalites.html#ajout "Adding data") specific work days or specific weeks.

Custom days are days where the hours worked do not correspond to the usual working hours of the resource.

- **Custom day**: link to the [day template](https://mynomadia.com/privatedoc/9LLcWh7j74sENa54/optitime-doc/docs/en/otgs-reference-book/donnees.html#modele-jour "Day template") to use.
- **Custom week**: link to the [week template](https://mynomadia.com/privatedoc/9LLcWh7j74sENa54/optitime-doc/docs/en/otgs-reference-book/donnees.html#modele-semaine "Week template") to use.
- **From**, **To**: start and end date for application of the custom day or week.
- **During**: allows you to define a duration for utilisation of the custom day or week.
- **Every X weeks**: allows you to define a periodicity (for example: **every** 1 **week** will apply the chosen template each week during the defined period).

##### Limits tab

|  |  |
| --- | --- |
| [Note] | Note |
| This tab can be pre-filled if a function has been associated to the resource at the level of the [Information](https://mynomadia.com/privatedoc/9LLcWh7j74sENa54/optitime-doc/docs/en/otgs-reference-book/donnees.html#RH-info "Information tab") tab. |

Defining maximum quantities

![images/ref/admin/RH-limites.png](./images/RH-limites.png)

**Overall time limit**:

- Sum of intervention times:

  - **Day**: this is the maximum number of hours, for example 7 hours, to be worked between the start and finish time of the day;
  - **Week**: this is the maximum number of hours per week;
  - **Month**: this is the maximum number of hours per month.
- Sum of all driving times:

  - Maximum **daily** travel time allows you to define a limited timespan for travelling between home and the workplace in one day;
  - Maximum **weekly** travel time defines a time limit for travel between home and the work place in one week;
  - Maximum **per month** travel time defines a time limit for travel between home and the work place in one month.
- The drop-down list enables selection of the mode of calculation for the cumulated total:

  |  |  |
  | --- | --- |
  | [Tip] | Tip |
  | This field changes, in reality, in the application settings.  To modify it, go into the [application settings](https://mynomadia.com/privatedoc/9LLcWh7j74sENa54/optitime-doc/docs/en/otgs-reference-book/perso.html#config-appli "Application settings") menu and replace the **Optimization tab > Batch > OPTIM\_DISPATCHER > MAX\_WORK\_TIME\_TYPE** setting with the desired value. |

  - Intervention: only the duration of interventions is included in the calculation;
  - Journey time + intervention: the travel times are counted also (as a function of the options checked beneath the item).
- **first workway included** in the work time if the check-box has been checked. If the check-box has not been checked, you must fill the **Max overrun allowed** field;
- **last workway included** in the work time if the check-box has been checked. If the check-box has not been checked, you must fill the **Max overrun allowed** field.

  |  |  |
  | --- | --- |
  | [Warning] | Warning |
  | If the first (and respectively, the last) journey is counted, and the morning (or evening) **Max overrun allowed** field is checked, then it is taken that the resource departure point is the first intervention location (or respectively, that the resource finishes their working day at the location of the last intervention). The first (or last) journey is not taken into account in the optimization. |

**Daily journey constraints**

- **Max duration**

  - Gives the maximum time for the **first journey** of the day to arrive as planned at the first appointment;
  - Gives the maximum time for the **last journey** of the day to arrive as planned at the point of return.
- **Max overrun allowed**

  - Gives an additional authorised time for the **first journey (morning)**;
  - Gives an additional authorised time for the **last journey (evening)**.
- **Sensitivity to travel costs**: this enables extra weight to be given to the kilometers travelled (increase if the resource must only perform interventions
  close by, reduce if the resource must perform interventions further away).
- **First and last journey sensitivity**: this enables extra weight to be given to the first and last journeys in such a way that journeys have minimum duration for
  first and last journeys.
- **Move speed weighting**: this allows you to artificially increase or reduce travel speed (as a percentage).

**Configuring nights away**

This part allows you to define, for the resource, the **maximum number of nights away (overnight stops) authorised per week**, as well as the **Minimum journey duration to stay away**.

|  |  |
| --- | --- |
| [Note] | Note |
| A value of 00:00 signifies that the parameter is not taken into account in the optimization. |

##### Stop points tab

This tab allows you to configure an express unavailability that will be available in the [unavailabilities tool-tip](https://mynomadia.com/privatedoc/9LLcWh7j74sENa54/optitime-doc/docs/en/otgs-reference-book/call-center-agenda.html#tool-tip-indispo "Manage unavailabilities in the agenda") in the Planning module.

Stop points tab

![images/ref/admin/admin-stop-point.png](./images/admin-stop-point.png)

This is in two parts:

- A first part "**Stop points**":

  - The **Default duration** field defines the duration of the express unavailability.
  - The default **Unavailability type** contains the list of [presaved unavailability types](https://mynomadia.com/privatedoc/9LLcWh7j74sENa54/optitime-doc/docs/en/otgs-reference-book/donnees.html#type-indispo "Unavailability type"). It allows you to define the type of express unavailability.
- A second part "**Stop point address**" including the [address](https://mynomadia.com/privatedoc/9LLcWh7j74sENa54/optitime-doc/docs/en/otgs-reference-book/intro-geocodage.html "The geocoding") of the unavailability to enter.

|  |  |
| --- | --- |
| [Tip] | Tip |
| In earlier versions of the application, this tab is called "**Call in at depot**". |

##### Skills tab

The **Skills** tab allows you to associate a level of experience to a resource, a weighting for the fulfilment speed, plus the skills they
have as a function of their training and experience.

Skills tab

![images/ref/admin/RH-comp.png](./images/RH-comp.png)

- **Experience level**: Choose one of three: junior, confirmed or expert. This parameter is taken into account in the optimization of the taking
  of an appointment. When two resources are possible for a single appointment, the one with the highest level of experience
  is chosen.
- **Execution speed weighting**: serves to artificially increase or reduce the appointment fulfilment speed (as a percentage %).
- **Sel:**: this function is a quick way to add or delete skills.
- **Skill**: field corresponding to presaved [skills](https://mynomadia.com/privatedoc/9LLcWh7j74sENa54/optitime-doc/docs/en/otgs-reference-book/donnees.html#competence "Skill").
- **External reference**: external reference for the skill.
- **Length of time worked in sector**: start and finish date for the acquisition of the skill. These dates may correspond to an apprenticeship (in this case, a
  start date) or to a period of availability for a specific item of equipment or tooling.  
  You can [add](https://mynomadia.com/privatedoc/9LLcWh7j74sENa54/optitime-doc/docs/en/otgs-reference-book/generalites.html#ajout "Adding data") and [delete](https://mynomadia.com/privatedoc/9LLcWh7j74sENa54/optitime-doc/docs/en/otgs-reference-book/generalites.html#suppression "De-activating / Deleting a data item") periods by clicking on the ![images/ref/buttons/bouton-add.png](./images/bouton-add_2.png) and ![images/ref/buttons/bouton-delete.png](./images/bouton-delete.png) buttons.

|  |  |
| --- | --- |
| [Note] | Note |
| If a skill is required to perform an intervention, and the resource does not possess this skill, the intervention cannot be planned on the resource in [batch optimization](https://mynomadia.com/privatedoc/9LLcWh7j74sENa54/optitime-doc/docs/en/otgs-reference-book/_glossary.html#batch) and [optimised](https://mynomadia.com/privatedoc/9LLcWh7j74sENa54/optitime-doc/docs/en/otgs-reference-book/donnees.html) modes. |

##### Authorisations tab

Authorisations correspond to the characteristics of a client (for example: Password or key to access a block of flats, or
nationality). This item is not a skill.

Authorizations tab

![images/ref/admin/RH-autorisation-ajouter.png](./images/RH-autorisation-ajouter.png)

- **Sel:**: this function is a quick way to add or delete an authorization.
- **Authorisation**: this field corresponds to presaved [authorisations](https://mynomadia.com/privatedoc/9LLcWh7j74sENa54/optitime-doc/docs/en/otgs-reference-book/donnees.html#autorisation "Authorisation").
- **External reference**: external reference for the authorisation.
- **Length of time worked in sector**: start and finish date for the acquisition of the authorisation. These dates may represent the period of availability for
  a particular entitlement, skill or authorisation.  
  You can [add](https://mynomadia.com/privatedoc/9LLcWh7j74sENa54/optitime-doc/docs/en/otgs-reference-book/generalites.html#ajout "Adding data") and [delete](https://mynomadia.com/privatedoc/9LLcWh7j74sENa54/optitime-doc/docs/en/otgs-reference-book/generalites.html#suppression "De-activating / Deleting a data item") periods by clicking on the ![images/ref/buttons/bouton-add.png](./images/bouton-add_3.png) andt ![images/ref/buttons/bouton-delete.png](./images/bouton-delete_2.png) buttons.

|  |  |
| --- | --- |
| [Note] | Note |
| If an authorisation is required to perform an intervention, and the resource does not hold this skill, the intervention cannot be planned on the resource in [batch optimization](https://mynomadia.com/privatedoc/9LLcWh7j74sENa54/optitime-doc/docs/en/otgs-reference-book/_glossary.html#batch) and [optimised](https://mynomadia.com/privatedoc/9LLcWh7j74sENa54/optitime-doc/docs/en/otgs-reference-book/donnees.html) modes. |

##### Priorities tab

|  |  |
| --- | --- |
| [Note] | Note |
| This tab can be pre-filled if a function has been associated to the resource at the level of the [Information](https://mynomadia.com/privatedoc/9LLcWh7j74sENa54/optitime-doc/docs/en/otgs-reference-book/donnees.html#RH-info "Information tab") tab. |

Priorities tab

![images/ref/admin/RH-priorite.png](./images/RH-priorite.png)

- **Intervention type**: name of the type of intervention corresponding to the pre-saved [intervention types](https://mynomadia.com/privatedoc/9LLcWh7j74sENa54/optitime-doc/docs/en/otgs-reference-book/donnees.html#type-intervention "Intervention type (Intervention group)").
- **Manual planning**: authorises or not the planning of an appointment in manual mode for a type of intervention.
- **Real Time Optimisation**: parameter determining the priority of the optimization treatment in real time (from 0, minimum priority, to 100, maximum
  priority).
- **Global optimization** (in batch mode): parameter determining the priority to be given to the treatment of the global optimization by the optimization
  engine (from 0, minimum priority, to 100, maximum priority).

It is possible in the header to:

- Filter on intervention type by selecting it in the header.
- Filter on the priority in manual mode, real or global time by selecting it in the list in the header.
- Modify the priorities for all lines in the table by moving the cursor in the table header.
- Reset priorities by clicking on the Reset button in the header.
- Authorise all planning modes for a given line in the table by clicking on the Allow button that displays when you move the mouse cursor over the last column in the table.

##### Posts tab

The **Jobs** tab serves to define temporary or periodic posts for a resource.
The posts are associated to a list of intervention types, and this enables definition of a set of types of temporary or periodic
intervention types for a resource (see [Job type section](https://mynomadia.com/privatedoc/9LLcWh7j74sENa54/optitime-doc/docs/en/otgs-reference-book/donnees.html#type-poste "Job type") and [Function](https://mynomadia.com/privatedoc/9LLcWh7j74sENa54/optitime-doc/docs/en/otgs-reference-book/donnees.html#type-expertise "Function")).

You can [add](https://mynomadia.com/privatedoc/9LLcWh7j74sENa54/optitime-doc/docs/en/otgs-reference-book/generalites.html#ajout "Adding data") and [delete](https://mynomadia.com/privatedoc/9LLcWh7j74sENa54/optitime-doc/docs/en/otgs-reference-book/generalites.html#suppression "De-activating / Deleting a data item") temporary posts by clicking on the ![images/ref/buttons/bouton-ajouter.png](./images/bouton-ajouter.png) and ![images/ref/buttons/bouton-supprimer.png](./images/bouton-supprimer.png) buttons.

Posts tab

![images/ref/admin/RH-poste.png](./images/RH-poste.png)

The line at the top summarises the post occupied by the resource.

You can [add](https://mynomadia.com/privatedoc/9LLcWh7j74sENa54/optitime-doc/docs/en/otgs-reference-book/generalites.html#ajout "Adding data") and [delete](https://mynomadia.com/privatedoc/9LLcWh7j74sENa54/optitime-doc/docs/en/otgs-reference-book/generalites.html#suppression "De-activating / Deleting a data item") the types of post associated to a resource.

Description of fields:

- **Post**: [job type](https://mynomadia.com/privatedoc/9LLcWh7j74sENa54/optitime-doc/docs/en/otgs-reference-book/donnees.html#type-poste "Job type") or [function](https://mynomadia.com/privatedoc/9LLcWh7j74sENa54/optitime-doc/docs/en/otgs-reference-book/donnees.html#type-expertise "Function") to assign to the resource on the specified period.
- **From**: start date for the type of secondary post
- **To**: finish date for the type of a secondary post

To add a cyclical type of post, check the **Cyclical task** check-box.

The following fields then appear:

Cyclic jobs

![images/ref/admin/RH-poste-cycle.png](./images/RH-poste-cycle.png)

- **Cycle**: period of repetition for the post type;
- **Duration**: duration, in days, of the type of post in the defined period;
- **Depth**: duration of the period of repetition.

At the bottom of the page is the list of temporary posts with their period of validity.

##### Vehicle tab

This part allows you to choose the [vehicle](https://mynomadia.com/privatedoc/9LLcWh7j74sENa54/optitime-doc/docs/en/otgs-reference-book/mob.html#mob-vehicules "Vehicles") associated to the resource.

Vehicles tab

![images/ref/admin/admin-rh-veh.png](./images/admin-rh-veh.png)

The information relating to the vehicle are displayed on screen.

|  |  |
| --- | --- |
| [Tip] | Tip |
| At least one vehicle must be entered in the [Vehicles](https://mynomadia.com/privatedoc/9LLcWh7j74sENa54/optitime-doc/docs/en/otgs-reference-book/mob.html#mob-vehicules "Vehicles") menu in the Administration module. |

#### Function

Resource types allows you to presave information relating to the resource such as the intervention types that may be performed.
These information items allow you, for example, to add temporary posts to the resource.

You can [create](https://mynomadia.com/privatedoc/9LLcWh7j74sENa54/optitime-doc/docs/en/otgs-reference-book/generalites.html#creation "Create a new data item"), [consult](https://mynomadia.com/privatedoc/9LLcWh7j74sENa54/optitime-doc/docs/en/otgs-reference-book/generalites.html#modification "Consult or edit an existing data item"), [duplicate](https://mynomadia.com/privatedoc/9LLcWh7j74sENa54/optitime-doc/docs/en/otgs-reference-book/generalites.html#duplication "Duplicating a data item") or [deactivate](https://mynomadia.com/privatedoc/9LLcWh7j74sENa54/optitime-doc/docs/en/otgs-reference-book/generalites.html#suppression "De-activating / Deleting a data item") a function.

##### List of functions

Access the [list](https://mynomadia.com/privatedoc/9LLcWh7j74sENa54/optitime-doc/docs/en/otgs-reference-book/generalites.html#generalite-liste "Data home page") of functions by clicking on the Function link in the menu, in the "[Company data](https://mynomadia.com/privatedoc/9LLcWh7j74sENa54/optitime-doc/docs/en/otgs-reference-book/donnees.html "Company data")" dialogue.

The interface allows you to filter the list of resource types in relation to their area of affiliation.

##### Form for the function

The [form](https://mynomadia.com/privatedoc/9LLcWh7j74sENa54/optitime-doc/docs/en/otgs-reference-book/generalites.html#generalite-fiche "Data form") of a function comprises the **Information**, **Work week**, **Limits** and **Priorities** tabs described below.

##### Information tab

Information tab

![images/ref/admin/type-expert-infos.png](./images/type-expert-infos.png)

The interface shows, for each function, the following data:

- **Name** for the function: it is unique;
- An **abbreviation** for the function;
- The **color** for the function;
- The **area** in which the resource type will be available. This field is mandatory;
- A **description** of the function.
- The **default location** for the resource type that will overwrite the technician’s address defined in the resource’s "[Address](https://mynomadia.com/privatedoc/9LLcWh7j74sENa54/optitime-doc/docs/en/otgs-reference-book/donnees.html#RH-adresse "Address tab")" tab.

##### Work week tab

This involves selecting the week template that will apply to this type of resource in the list of [week templates](https://mynomadia.com/privatedoc/9LLcWh7j74sENa54/optitime-doc/docs/en/otgs-reference-book/donnees.html#modele-semaine "Week template").

The fields are described in the resource’s "[Week type](https://mynomadia.com/privatedoc/9LLcWh7j74sENa54/optitime-doc/docs/en/otgs-reference-book/donnees.html#RH-semaine "Typical week tab")" tab.

##### Limits tab

Refer to the "[Limits](https://mynomadia.com/privatedoc/9LLcWh7j74sENa54/optitime-doc/docs/en/otgs-reference-book/donnees.html#RH-limite "Limits tab")" tab for the resource.

##### Priorities tab

Refer to the "[Priorities](https://mynomadia.com/privatedoc/9LLcWh7j74sENa54/optitime-doc/docs/en/otgs-reference-book/donnees.html#RH-priorite "Priorities tab")" tab for the resource.

#### Job type

The types of posts enable presaving of information relating to the resource such as the types of intervention they can fulfill.
This facilitates input for fields in the [Priorities](https://mynomadia.com/privatedoc/9LLcWh7j74sENa54/optitime-doc/docs/en/otgs-reference-book/donnees.html#RH-priorite "Priorities tab") tab in the resource’s form.

You can [create](https://mynomadia.com/privatedoc/9LLcWh7j74sENa54/optitime-doc/docs/en/otgs-reference-book/generalites.html#creation "Create a new data item"), [consult or edit](https://mynomadia.com/privatedoc/9LLcWh7j74sENa54/optitime-doc/docs/en/otgs-reference-book/generalites.html#modification "Consult or edit an existing data item"), [duplicate](https://mynomadia.com/privatedoc/9LLcWh7j74sENa54/optitime-doc/docs/en/otgs-reference-book/generalites.html#duplication "Duplicating a data item") or [deactivate](https://mynomadia.com/privatedoc/9LLcWh7j74sENa54/optitime-doc/docs/en/otgs-reference-book/generalites.html#suppression "De-activating / Deleting a data item") a job type.

|  |  |
| --- | --- |
| [Tip] | Tip |
| We can consider the post type as a human resource template. |

##### List of job types

Access the [list](https://mynomadia.com/privatedoc/9LLcWh7j74sENa54/optitime-doc/docs/en/otgs-reference-book/generalites.html#generalite-liste "Data home page") of job types by clicking on the Job type link in the menu, in the "[Company data](https://mynomadia.com/privatedoc/9LLcWh7j74sENa54/optitime-doc/docs/en/otgs-reference-book/donnees.html "Company data")" dialogue.

The interface allows you to filter the list of role types in relation to their area of affiliation.

##### Form for the job type

The [form](https://mynomadia.com/privatedoc/9LLcWh7j74sENa54/optitime-doc/docs/en/otgs-reference-book/generalites.html#generalite-fiche "Data form") of a job type comprises the **Information**, **Work week** and **Priorities** tabs described below.

##### Information tab

Information tab

![images/ref/admin/type-poste-infos.png](./images/type-poste-infos.png)

The interface shows, for each type of post, the following data:

- **Identifier** for the Type of post: it is unique;
- **External reference** for the Type of post: this must be entered in any project of data exchange with an external system;
- **Name** of the post type;
- **Colour**: serves to give a type of role a custom colour in the plannings;
- **Area**: the reference area for the type of role. This field is required.
- A concise **description** of the post;
- The **default location** for the post type will overwrite the address of the technical as defined in the "[Address](https://mynomadia.com/privatedoc/9LLcWh7j74sENa54/optitime-doc/docs/en/otgs-reference-book/donnees.html#RH-adresse "Address tab")" tab for the resource.

##### Work week tab

Refer to the Resource "[Standard week](https://mynomadia.com/privatedoc/9LLcWh7j74sENa54/optitime-doc/docs/en/otgs-reference-book/donnees.html#RH-semaine "Typical week tab")" tab.

##### Priorities tab

Refer to the "[Priorities](https://mynomadia.com/privatedoc/9LLcWh7j74sENa54/optitime-doc/docs/en/otgs-reference-book/donnees.html#RH-priorite "Priorities tab")" tab for the resource.

#### Subcontractor

Defining subcontractors allows you to assign an intervention to a subcontractor.

This can be useful for keeping a trace of an appointment without having to manage its [life cycle](https://mynomadia.com/privatedoc/9LLcWh7j74sENa54/optitime-doc/docs/en/otgs-reference-book/_the_different_statuses_for_appointments_in_opti_time.html#cycle-rdv "Life cycle of an appointment").

It is possible to [create](https://mynomadia.com/privatedoc/9LLcWh7j74sENa54/optitime-doc/docs/en/otgs-reference-book/generalites.html#creation "Create a new data item"), [consult](https://mynomadia.com/privatedoc/9LLcWh7j74sENa54/optitime-doc/docs/en/otgs-reference-book/generalites.html#modification "Consult or edit an existing data item"), [duplicate](https://mynomadia.com/privatedoc/9LLcWh7j74sENa54/optitime-doc/docs/en/otgs-reference-book/generalites.html#duplication "Duplicating a data item") or [deactivate](https://mynomadia.com/privatedoc/9LLcWh7j74sENa54/optitime-doc/docs/en/otgs-reference-book/generalites.html#suppression "De-activating / Deleting a data item") a subcontractor.

##### List of subcontractors

Access the [list](https://mynomadia.com/privatedoc/9LLcWh7j74sENa54/optitime-doc/docs/en/otgs-reference-book/generalites.html#generalite-liste "Data home page") of subcontractors by clicking on the Subcontractor link in the menu.

The interface allows you to filter the list of subcontractors in relation to their area of affiliation.

##### Form for the subcontractor

The [form](https://mynomadia.com/privatedoc/9LLcWh7j74sENa54/optitime-doc/docs/en/otgs-reference-book/generalites.html#generalite-fiche "Data form") of the subcontractor has just one tab.

The interface shows the following for each subcontractor:

- **Name** of the subcontractor: it is unique;
- **Abbreviation** for the subcontractor;
- **Area**: the area in which the subcontractor will be available. This field is mandatory;
- **Worksite** for the subcontractor;
- A concise **description** of the subcontractor.

#### Equipment

This is the equipment needed to fulfill an intervention: for example, a tool or a spare part.

It is possible to [create](https://mynomadia.com/privatedoc/9LLcWh7j74sENa54/optitime-doc/docs/en/otgs-reference-book/generalites.html#creation "Create a new data item"), [consult](https://mynomadia.com/privatedoc/9LLcWh7j74sENa54/optitime-doc/docs/en/otgs-reference-book/generalites.html#modification "Consult or edit an existing data item"), [duplicate](https://mynomadia.com/privatedoc/9LLcWh7j74sENa54/optitime-doc/docs/en/otgs-reference-book/generalites.html#duplication "Duplicating a data item") or [deactivate](https://mynomadia.com/privatedoc/9LLcWh7j74sENa54/optitime-doc/docs/en/otgs-reference-book/generalites.html#suppression "De-activating / Deleting a data item") an equipment.

##### List of equipments

Access the [list](https://mynomadia.com/privatedoc/9LLcWh7j74sENa54/optitime-doc/docs/en/otgs-reference-book/generalites.html#generalite-liste "Data home page") of equipments by clicking on the Equipment link in the menu.

The interface allows you to filter the list of equipment items in relation to their area of affiliation and worksite.

##### Form for the equipment

The equipment [form](https://mynomadia.com/privatedoc/9LLcWh7j74sENa54/optitime-doc/docs/en/otgs-reference-book/generalites.html#generalite-fiche "Data form") has just one tab.

The interface shows, for each equipment item, the following data:

- **Name**: it is unique;
- **Abbreviation**;
- **Area**: the area in which the equipment is available. This field is mandatory;
- **Worksite** at which the equipment will be available;
- A **description**;
- A **Duration**;
- **Stock**: shows available spare parts;
- **Loading**;
- **Number of staff**: the number of employees needed to use the equipment;
- **Priority**;
- **Attached files**: associated multimedia file(s), according to the rights assigned to the user. To access this function, you need to have the
  corresponding [rights](https://mynomadia.com/privatedoc/9LLcWh7j74sENa54/optitime-doc/docs/en/otgs-reference-book/utilisateurs.html#coll-droits "Collection of rights") assigned by the Opti-Time administrator: Administration > Others > ADMIN\_ADD\_DOCUMENTS and ADMIN\_DELETE\_DOCUMENTS.

|  |  |
| --- | --- |
| [Warning] | Warning |
| At the time of writing, these data are not used for planning calculations. |

#### Product family

Family of products to deliver.

It is possible to [create](https://mynomadia.com/privatedoc/9LLcWh7j74sENa54/optitime-doc/docs/en/otgs-reference-book/generalites.html#creation "Create a new data item"), [consult](https://mynomadia.com/privatedoc/9LLcWh7j74sENa54/optitime-doc/docs/en/otgs-reference-book/generalites.html#modification "Consult or edit an existing data item"), [duplicate](https://mynomadia.com/privatedoc/9LLcWh7j74sENa54/optitime-doc/docs/en/otgs-reference-book/generalites.html#duplication "Duplicating a data item") or [deactivate](https://mynomadia.com/privatedoc/9LLcWh7j74sENa54/optitime-doc/docs/en/otgs-reference-book/generalites.html#suppression "De-activating / Deleting a data item") a product family.

##### List of product families

Access the [list](https://mynomadia.com/privatedoc/9LLcWh7j74sENa54/optitime-doc/docs/en/otgs-reference-book/generalites.html#generalite-liste "Data home page") of products families by clicking on the Product family link in the menu.

The interface enables filtering of the list of product families on area of affiliation.

##### Form for the product family

The [form](https://mynomadia.com/privatedoc/9LLcWh7j74sENa54/optitime-doc/docs/en/otgs-reference-book/generalites.html#generalite-fiche "Data form") of the product family has just one tab.

The interface shows, for each family, the following data:

- **Name**: it is unique;
- **Abbreviation**;
- **Area**: the area in which the product family will be available. This field is mandatory;
- A **description**.

#### Product (Product family)

It may consist of a product to deliver, or the product used to fulfill the intervention.

It is possible to [create](https://mynomadia.com/privatedoc/9LLcWh7j74sENa54/optitime-doc/docs/en/otgs-reference-book/generalites.html#creation "Create a new data item"), [consult](https://mynomadia.com/privatedoc/9LLcWh7j74sENa54/optitime-doc/docs/en/otgs-reference-book/generalites.html#modification "Consult or edit an existing data item"), [duplicate](https://mynomadia.com/privatedoc/9LLcWh7j74sENa54/optitime-doc/docs/en/otgs-reference-book/generalites.html#duplication "Duplicating a data item") or [deactivate](https://mynomadia.com/privatedoc/9LLcWh7j74sENa54/optitime-doc/docs/en/otgs-reference-book/generalites.html#suppression "De-activating / Deleting a data item") a product.

##### List of products

Access the [list](https://mynomadia.com/privatedoc/9LLcWh7j74sENa54/optitime-doc/docs/en/otgs-reference-book/generalites.html#generalite-liste "Data home page") of products by clicking on the Product link located beneath the **[Product family](https://mynomadia.com/privatedoc/9LLcWh7j74sENa54/optitime-doc/docs/en/otgs-reference-book/donnees.html#famille-produit "Product family")** item in the menu.

The interface enables filtering of the list of products on area of affiliation.

##### Form for the product

The [form](https://mynomadia.com/privatedoc/9LLcWh7j74sENa54/optitime-doc/docs/en/otgs-reference-book/generalites.html#generalite-fiche "Data form") of the product has just one tab.

The interface shows, for each product, the following data:

- The **external reference** of the product;
- **Name**: it is unique;
- **Abbreviation**;
- **Area**: the area in which the equipment is available. This field is mandatory;
- A **worksite**: link to the associated [worksite](https://mynomadia.com/privatedoc/9LLcWh7j74sENa54/optitime-doc/docs/en/otgs-reference-book/donnees.html#site-travail "Worksite");
- A **family**: link to the associated [product family](https://mynomadia.com/privatedoc/9LLcWh7j74sENa54/optitime-doc/docs/en/otgs-reference-book/donnees.html#famille-produit "Product family");
- A **description**;
- A **Duration**;
- **Stock**: shows available spare parts;
- **Loading**;
- **Number of staff**; the number of staff needed to use the product;
- **Priority**;
- **Attached files**: associated multimedia file(s), according to the rights assigned to the user. To access this function, you need to have the
  corresponding [rights](https://mynomadia.com/privatedoc/9LLcWh7j74sENa54/optitime-doc/docs/en/otgs-reference-book/utilisateurs.html#coll-droits "Collection of rights") assigned by the Opti-Time administrator: Administration > Others > ADMIN\_ADD\_DOCUMENTS and ADMIN\_DELETE\_DOCUMENTS.

|  |  |
| --- | --- |
| [Warning] | Warning |
| At the time of writing, these data are not used for planning calculations. |

#### Team

This is the hierarchical representation of resources. A team is made up of resources, or sub-teams. A team is managed by a
Team Leader.

You can [create](https://mynomadia.com/privatedoc/9LLcWh7j74sENa54/optitime-doc/docs/en/otgs-reference-book/generalites.html#creation "Create a new data item"), [consult](https://mynomadia.com/privatedoc/9LLcWh7j74sENa54/optitime-doc/docs/en/otgs-reference-book/generalites.html#modification "Consult or edit an existing data item") [duplicate](https://mynomadia.com/privatedoc/9LLcWh7j74sENa54/optitime-doc/docs/en/otgs-reference-book/generalites.html#duplication "Duplicating a data item") or [deactivate](https://mynomadia.com/privatedoc/9LLcWh7j74sENa54/optitime-doc/docs/en/otgs-reference-book/generalites.html#suppression "De-activating / Deleting a data item") a team.

|  |  |
| --- | --- |
| [Tip] | Tip |
| The team does not come into consideration in the optimization constraints. It serves to define particular user profiles (where the user can only see data relating to their team), for the display in the agenda and for the purpose of statistical calculation. |

By way of example, the resources are regrouped into teams under the responsibility of a [team leader](https://mynomadia.com/privatedoc/9LLcWh7j74sENa54/optitime-doc/docs/en/otgs-reference-book/donnees.html#equipe-chef "Team leader tab"). The teams are regrouped in the framework of the sales force in the terrain for the area (or regional sales team). The regional
sales teams are regrouped into a National Sales Team ([parent team](https://mynomadia.com/privatedoc/9LLcWh7j74sENa54/optitime-doc/docs/en/otgs-reference-book/donnees.html#equipe-mere "Parent team tab")).

##### List of teams

Access the [list](https://mynomadia.com/privatedoc/9LLcWh7j74sENa54/optitime-doc/docs/en/otgs-reference-book/generalites.html#generalite-liste "Data home page") of teams by clicking on the Team link in the menu, in the "[Company data](https://mynomadia.com/privatedoc/9LLcWh7j74sENa54/optitime-doc/docs/en/otgs-reference-book/donnees.html "Company data")" dialogue.

The interface first proposes to consult teams belonging to a single area. Choose an area in the drop-down list to display
the list of associated teams.

##### Form for the team

The team [form](https://mynomadia.com/privatedoc/9LLcWh7j74sENa54/optitime-doc/docs/en/otgs-reference-book/generalites.html#generalite-fiche "Data form") has the following tabs: **Information**, **Members**, **Team Leader**, **Parent team**. These sections are described below.

##### Information tab

Information tab

![images/ref/admin/equipe-info.png](./images/equipe-info.png)

Description of fields present in the interface:

- An **Identifier** provides a unique reference for the team: it is in read-only mode and is assigned automatically by the application when the
  Team is created.
- An [**External reference**](https://mynomadia.com/privatedoc/9LLcWh7j74sENa54/optitime-doc/docs/en/otgs-reference-book/_glossary.html#Extref);
- **Name** of the team: this name is used each time the application mentions a team. It is therefore important to choose a representative
  Team name. By extension, an empty character string is not permitted.
- Name of the **Team Leader**: this displays when a team leader is designated in the [Team leader tab](https://mynomadia.com/privatedoc/9LLcWh7j74sENa54/optitime-doc/docs/en/otgs-reference-book/donnees.html#equipe-chef "Team leader tab");
- Name of the **Parent team**: displays when a parent team is designated in the [Parent team tab](https://mynomadia.com/privatedoc/9LLcWh7j74sENa54/optitime-doc/docs/en/otgs-reference-book/donnees.html#equipe-mere "Parent team tab");
- An **Area of intervention**: the value can be *Non-assigned* or a pre-saved [area](https://mynomadia.com/privatedoc/9LLcWh7j74sENa54/optitime-doc/docs/en/otgs-reference-book/donnees.html#region "Area");
- A **Description** of the Team: this text is free;
- The **local time zone** to which it is affiliated.

|  |  |
| --- | --- |
| [Tip] | Tip |
| To be able to choose members belonging to different areas, choose *Non-assigned* in the *Area of intervention*. |

##### Members tab

The list of members displays the **Last name**, **First name** and **Mission sector** of team members.

You can [add](https://mynomadia.com/privatedoc/9LLcWh7j74sENa54/optitime-doc/docs/en/otgs-reference-book/generalites.html#ajout "Adding data") and [delete](https://mynomadia.com/privatedoc/9LLcWh7j74sENa54/optitime-doc/docs/en/otgs-reference-book/generalites.html#suppression "De-activating / Deleting a data item") members by clicking on the ![images/ref/buttons/bouton-ajouter.png](./images/bouton-ajouter_2.png) and ![images/ref/buttons/bouton-supprimer.png](./images/bouton-supprimer_2.png) buttons.

Click on ![images/ref/buttons/bouton-ajouter.png](./images/bouton-ajouter_3.png) to display the list of resources that have not yet been assigned to the team, who are working in the area to which the team
is affiliated.

Add Team members

![images/ref/admin/equipe-ajout-membre.png](./images/equipe-ajout-membre.png)

##### Team leader tab

The assignment of a team leader is not mandatory.

To add a team leader, select a member in the drop-down list and click on Save.

Team leader tab

![images/ref/admin/equipe-chef.png](./images/equipe-chef.png)

##### Parent team tab

The assignment of a parent team is not mandatory

To add a parent team, select a team in the drop-down list and click on Save.

By way of example, a Regional Team type of Team plays the role of Mother team with respect to «simple» teams, and itself has
its own parent team, this being the National Team.

#### Domain

The domain is a regrouping of areas.
It is possible to [create](https://mynomadia.com/privatedoc/9LLcWh7j74sENa54/optitime-doc/docs/en/otgs-reference-book/generalites.html#creation "Create a new data item"), [consult or edit](https://mynomadia.com/privatedoc/9LLcWh7j74sENa54/optitime-doc/docs/en/otgs-reference-book/generalites.html#modification "Consult or edit an existing data item") a domain.

##### List of domains

Access to the [list](https://mynomadia.com/privatedoc/9LLcWh7j74sENa54/optitime-doc/docs/en/otgs-reference-book/generalites.html#generalite-liste "Data home page") of domains is by clicking on the Domain link in the menu under the "[Company data](https://mynomadia.com/privatedoc/9LLcWh7j74sENa54/optitime-doc/docs/en/otgs-reference-book/donnees.html "Company data")" dialogue.

List of domains

![images/ref/admin/domaine-liste.png](./images/domaine-liste.png)

##### Domain form

Domain form

![images/ref/admin/domaine-modif.png](./images/domaine-modif.png)

The [form](https://mynomadia.com/privatedoc/9LLcWh7j74sENa54/optitime-doc/docs/en/otgs-reference-book/generalites.html#generalite-fiche "Data form") of the domain is made up of two blocks.

To associate an area to a domain, simply select **Other areas** in the block and click on > or click on >> to move all the areas.
To withdraw an area from a domain, simply select **Areas of the domain** from the block and click on < or << to move all the areas.

#### Area

This is the representation in the application of the geographic zone or zones on which each team resource intervenes to perform
their appointments. The areas of intervention are established from a list of towns. Nonetheless, the assignment of towns to
this area passes via the intermediary of one sector and this is performed via the Geoconcept mapping tool.
A resource cannot perform an appointment outside their area.

|  |  |
| --- | --- |
| [Tip] | Tip |
| An area can be linked to several teams. Under normal circumstances, it includes at least one team.  An area is broken down into sectors. A sector cannot depend on just one area.  The areas are disparate entities. |

You can [create](https://mynomadia.com/privatedoc/9LLcWh7j74sENa54/optitime-doc/docs/en/otgs-reference-book/generalites.html#creation "Create a new data item"), [consult](https://mynomadia.com/privatedoc/9LLcWh7j74sENa54/optitime-doc/docs/en/otgs-reference-book/generalites.html#modification "Consult or edit an existing data item") [duplicate](https://mynomadia.com/privatedoc/9LLcWh7j74sENa54/optitime-doc/docs/en/otgs-reference-book/generalites.html#duplication "Duplicating a data item") or [deactivate](https://mynomadia.com/privatedoc/9LLcWh7j74sENa54/optitime-doc/docs/en/otgs-reference-book/generalites.html#suppression "De-activating / Deleting a data item") an area.

##### List of Areas

Access to the [list](https://mynomadia.com/privatedoc/9LLcWh7j74sENa54/optitime-doc/docs/en/otgs-reference-book/generalites.html#generalite-liste "Data home page") of areas by clicking on the Area link in the menu.

The interface allows you to filter the list of areas in relation to their domain.

##### Form for an Area

The Area [form](https://mynomadia.com/privatedoc/9LLcWh7j74sENa54/optitime-doc/docs/en/otgs-reference-book/generalites.html#generalite-fiche "Data form") comprises the following tabs: **Information**, **Teams**, **District**, **Town**, **Worksites** and **Resources**. These sections are described below.

##### Information tab

Information tab

![images/ref/admin/region-info.png](./images/region-info.png)

- Identification of the area: this is a unique **identifier** in read-only mode determined automatically by the application when the area is created.
- [**External reference**](https://mynomadia.com/privatedoc/9LLcWh7j74sENa54/optitime-doc/docs/en/otgs-reference-book/_glossary.html#Extref) for the area;
- **Name** of the area: entering an area name is mandatory;
- **Description** of the area: free text;
- **Domain** name of the [domain](https://mynomadia.com/privatedoc/9LLcWh7j74sENa54/optitime-doc/docs/en/otgs-reference-book/donnees.html#domaine "Domain") affiliation for the area;
- The **local time zone** to which it is affiliated.

##### Teams tab

It is possible to [add](https://mynomadia.com/privatedoc/9LLcWh7j74sENa54/optitime-doc/docs/en/otgs-reference-book/donnees.html) and to [delete](https://mynomadia.com/privatedoc/9LLcWh7j74sENa54/optitime-doc/docs/en/otgs-reference-book/generalites.html#suppression "De-activating / Deleting a data item") teams by clicking on the ![images/ref/buttons/bouton-ajouter.png](./images/bouton-ajouter_4.png) and ![images/ref/buttons/bouton-supprimer.png](./images/bouton-supprimer_3.png) buttons.

Click on the ![images/ref/buttons/bouton-ajouter.png](./images/bouton-ajouter_5.png) button to display the list of all Teams who are not already assigned to an Area.

Adding Teams to an Area

![images/ref/admin/region-equipe.png](./images/region-equipe.png)

The teams can be unassigned from the Area by checking these in the list and selecting the **Delete** command.

##### District tab

List of administrative departments making up the area. Each administrative department can only belong to a single area.

This section is purely for information purposes, and is automatically determined by the existing joins in the application
database.
Towns are assigned to a sector, and several sectors are assigned to an Area of intervention.
The list of Sectors attached to a given area is returned when you establish the list of sectors from the area of intervention
link in the Sector entity.

##### Town tab

This is the List of towns making up the Area.
Each town can only belong to a single Area.
This list is obtained from the Geoconcept cartographic application, and is described in the relevant documentation concerning
sectorisation.

#### Worksite

This is the representation of the worksites shared by several resources; an agency, a depot, a retail outlet, etc.
It is not the same thing as a [sector](https://mynomadia.com/privatedoc/9LLcWh7j74sENa54/optitime-doc/docs/en/otgs-reference-book/donnees.html#secteur "Sector (or Intervention sector)"), this being a domain of intervention that can be either geographic, or a business domain.

You can [create](https://mynomadia.com/privatedoc/9LLcWh7j74sENa54/optitime-doc/docs/en/otgs-reference-book/generalites.html#creation "Create a new data item"), [consult](https://mynomadia.com/privatedoc/9LLcWh7j74sENa54/optitime-doc/docs/en/otgs-reference-book/generalites.html#modification "Consult or edit an existing data item") or [duplicate](https://mynomadia.com/privatedoc/9LLcWh7j74sENa54/optitime-doc/docs/en/otgs-reference-book/generalites.html#duplication "Duplicating a data item") a worksite.

|  |  |
| --- | --- |
| [Note] | Note |
| The customer must be affiliated to the same worksite as the resource for the resource to be able to perform the intervention for this customer. |

##### List of worksites

Access to worksites is via a click on the Worksite link in the menu, in the "[Company Data](https://mynomadia.com/privatedoc/9LLcWh7j74sENa54/optitime-doc/docs/en/otgs-reference-book/donnees.html "Company data")" dialogue.

List of worksites

![images/ref/admin/site-travail.png](./images/site-travail.png)

Worksites can be filtered on:

- **Area**: this is the area of affiliation of the worksite;
- **Type**: this is the type of worksite (agency, standard or sector).

##### Worksite form

A worksite form

![images/ref/admin/site-travail-modif.png](./images/site-travail-modif.png)

The [form](https://mynomadia.com/privatedoc/9LLcWh7j74sENa54/optitime-doc/docs/en/otgs-reference-book/generalites.html#generalite-fiche "Data form") contains the following information:

- **Identifier** for the Worksite; this is a unique identifier, in read-only mode, generated automatically by the application.
- The [**External reference**](https://mynomadia.com/privatedoc/9LLcWh7j74sENa54/optitime-doc/docs/en/otgs-reference-book/_glossary.html#Extref) for the worksite.
- **Name** of the Worksite: mandatory information.
- **Type** of Worksite: the type can be *Agency* or *Standard*
- **Description** of the Worksite: free text.
- **Area**: this information can be deduced from the post code of the Worksite. In the case of a creation of a Worksite, it is possible
  to choose the area of affiliation by selecting it in the list.
- **Local time zone** for the worksite.
- **Address**: refer to the chapter on [address fields](https://mynomadia.com/privatedoc/9LLcWh7j74sENa54/optitime-doc/docs/en/otgs-reference-book/intro-geocodage.html "The geocoding").
- Geocoding information: the result of geocoding the Worksite is displayed in the format **X Coordinate** and **Y coordinate**.
  These information items are in read-only mode.

|  |  |
| --- | --- |
| [Tip] | Tip |
| When resources do not possess any start address, it is the address of the worksite to which they are affiliated that is taken into account as a start point for routes. |

#### Sector (or Intervention sector)

This is the representation in the application of the geographic zone(s) on which each resource must intervene as a priority
to fulfill an appointment.

You can [create](https://mynomadia.com/privatedoc/9LLcWh7j74sENa54/optitime-doc/docs/en/otgs-reference-book/generalites.html#creation "Create a new data item"), [consult](https://mynomadia.com/privatedoc/9LLcWh7j74sENa54/optitime-doc/docs/en/otgs-reference-book/generalites.html#modification "Consult or edit an existing data item"), [duplicate](https://mynomadia.com/privatedoc/9LLcWh7j74sENa54/optitime-doc/docs/en/otgs-reference-book/generalites.html#duplication "Duplicating a data item") or [deactivate](https://mynomadia.com/privatedoc/9LLcWh7j74sENa54/optitime-doc/docs/en/otgs-reference-book/generalites.html#suppression "De-activating / Deleting a data item") a sector.

##### List of sectors

Access to the [list](https://mynomadia.com/privatedoc/9LLcWh7j74sENa54/optitime-doc/docs/en/otgs-reference-book/generalites.html#generalite-liste "Data home page") of sectors is by clicking on the Sector link in the menu.

The interface first suggests consulting sectors belonging to a single area. Choose an area in the drop-down list to display
the list of associated sectors.

##### Form for a Sector

The [form](https://mynomadia.com/privatedoc/9LLcWh7j74sENa54/optitime-doc/docs/en/otgs-reference-book/generalites.html#generalite-fiche "Data form") for sectors contains the following tabs: **Information**, **Address**, **Towns**, **Resources**, described below.

##### Information tab

Information tab

![images/ref/admin/secteur-info.png](./images/secteur-info.png)

- **Identifier**: unique number attributed to each sector;
- [**External reference**](https://mynomadia.com/privatedoc/9LLcWh7j74sENa54/optitime-doc/docs/en/otgs-reference-book/donnees.html) for the sector;
- **Name**: name of the sector;
- **Colour**: allows you to give the sector a custom colour in the plannings;
- **Area**: defines the area to which the sector belongs. A sector is necessarily included in a given area;
- **Function**: the function in this sector;
- **Description**: this is a free text item concerning the sector.

##### Address tab

Refer to the [address fields](https://mynomadia.com/privatedoc/9LLcWh7j74sENa54/optitime-doc/docs/en/otgs-reference-book/intro-geocodage.html "The geocoding") section of the documentation.

##### Towns tab

Towns tab

![images/ref/admin/secteur-comm.png](./images/secteur-comm.png)

It is possible to [add](https://mynomadia.com/privatedoc/9LLcWh7j74sENa54/optitime-doc/docs/en/otgs-reference-book/generalites.html#ajout "Adding data") a town by clicking on ![images/ref/buttons/bouton-ajouter.png](./images/bouton-ajouter_6.png) after having clicked on Validate address and [delete](https://mynomadia.com/privatedoc/9LLcWh7j74sENa54/optitime-doc/docs/en/otgs-reference-book/generalites.html#suppression "De-activating / Deleting a data item") a town by clicking on ![images/ref/buttons/bouton-supprimer.png](./images/bouton-supprimer_4.png).

This is the list of towns making up the sector.

|  |  |
| --- | --- |
| [Tip] | Tip |
| In France, some towns have the same post code and some towns will have several post codes. To be certain to add the right town, use the government assigned one (which contains the INSEE code). |

|  |  |
| --- | --- |
| [Warning] | Warning |
| Each town can only belong to a single Sector. |

##### Resources tab

This tab allows you to view resources using the sector as their main or secondary sector (see [resource form](https://mynomadia.com/privatedoc/9LLcWh7j74sENa54/optitime-doc/docs/en/otgs-reference-book/donnees.html#RH-affectation "Assignment tab")).

Resources tab

![images/ref/admin/secteur-ress.png](./images/secteur-ress.png)

- The **Resource** column displays the first name and surname of the resource
- The **Start date** and **End date** columns display the dates for the start and end of the assignment of the resource to this sector
- The **Preference** column displays the preference on 100 of the resources for the sector.

#### Unavailability type

The interface proposes the full list of types of unavailability known to the system. An unavailability allows the application
to take into account in the plannings of the human resources events such as holidays, a prolonged business trip, a meeting,
etc. When a resource is unavailable the application may not propose any meeting for this resource during this period of time.

It is possible to [create](https://mynomadia.com/privatedoc/9LLcWh7j74sENa54/optitime-doc/docs/en/otgs-reference-book/generalites.html#creation "Create a new data item"), [consult or edit](https://mynomadia.com/privatedoc/9LLcWh7j74sENa54/optitime-doc/docs/en/otgs-reference-book/generalites.html#modification "Consult or edit an existing data item"), [duplicate](https://mynomadia.com/privatedoc/9LLcWh7j74sENa54/optitime-doc/docs/en/otgs-reference-book/generalites.html#duplication "Duplicating a data item") ou [deactivate](https://mynomadia.com/privatedoc/9LLcWh7j74sENa54/optitime-doc/docs/en/otgs-reference-book/generalites.html#suppression "De-activating / Deleting a data item") a type of unavailability.

##### List of unavailability types

You can access the [list](https://mynomadia.com/privatedoc/9LLcWh7j74sENa54/optitime-doc/docs/en/otgs-reference-book/generalites.html#generalite-liste "Data home page") of unavailability types by clicking on the Unavailability type link in the menu.

The interface allows you to filter the list of unavailability types in relation to their area of affiliation.

##### Unavailability type form

The [form](https://mynomadia.com/privatedoc/9LLcWh7j74sENa54/optitime-doc/docs/en/otgs-reference-book/generalites.html#generalite-fiche "Data form") for each type of unavailability only has one tab.

Unavailability type

![images/ref/admin/type-indispo.png](./images/type-indispo.png)

The interface shows, for each type of unavailability, the following data:

- **Identifier** of the type of unavailability: it is unique;
- **External reference**: [external reference](https://mynomadia.com/privatedoc/9LLcWh7j74sENa54/optitime-doc/docs/en/otgs-reference-book/_glossary.html#Extref) for the type of unavailability;
- **Name** of the type of unavailability;
- **Colour**: allows you to give the unavailability type a custom [colour](https://mynomadia.com/privatedoc/9LLcWh7j74sENa54/optitime-doc/docs/en/otgs-reference-book/perso.html#couleurs "Colors") in the plannings.
- The **area** in which the unavailability type will be available. This field is required;
- A concise **description** of the type of unavailability;
- **Effective work**: this shows whether the unavailability is accounted for in the working hours or not;
- **Multi-resources** indicates whether this unavailability concerns several resources;
- **Localisation by default** indicates the location where the resource is sited during his/her unavailability. There are four possibilities:

  - *Blank, but mandatory* (the address must be entered);
  - *At home* (the default address is that of the resource’s home);
  - *On the worksite* (the default address is that of the main worksite).
- **Default duration** lets you pre-fill the duration when creating an unavailability of this type;
- **Minimum duration** enables definition of a minimum duration below which the planning manager cannot enter an unavailability of this type;
- **Maximum duration** allows you to define a maximum duration above which the planning manager cannot enter any unavailability of this type;
- **Units of duration**: *minutes*, *hours*, *days*: units in which the durations above are defined

#### Exceptional location type

It is possible to [create](https://mynomadia.com/privatedoc/9LLcWh7j74sENa54/optitime-doc/docs/en/otgs-reference-book/generalites.html#creation "Create a new data item"), [consult](https://mynomadia.com/privatedoc/9LLcWh7j74sENa54/optitime-doc/docs/en/otgs-reference-book/generalites.html#modification "Consult or edit an existing data item"), [duplicate](https://mynomadia.com/privatedoc/9LLcWh7j74sENa54/optitime-doc/docs/en/otgs-reference-book/generalites.html#duplication "Duplicating a data item") or [deactivate](https://mynomadia.com/privatedoc/9LLcWh7j74sENa54/optitime-doc/docs/en/otgs-reference-book/generalites.html#suppression "De-activating / Deleting a data item") an [type of exceptional localisation](https://mynomadia.com/privatedoc/9LLcWh7j74sENa54/optitime-doc/docs/en/otgs-reference-book/call-center-objets.html#localisations-exceptionnelles "Exceptional locations").

##### List of exceptional location types

Access the [list](https://mynomadia.com/privatedoc/9LLcWh7j74sENa54/optitime-doc/docs/en/otgs-reference-book/generalites.html#generalite-liste "Data home page") of exceptional location types by clicking on the Exceptional location type link in the menu.

The interface allows you to filter the list of exceptional location types in relation to their area of affiliation.

##### Form for the exceptional location type

The [form](https://mynomadia.com/privatedoc/9LLcWh7j74sENa54/optitime-doc/docs/en/otgs-reference-book/generalites.html#generalite-fiche "Data form") for the exceptional location type is made up of a first part, and an address part.

Exceptional location type

![images/ref/admin/type-except-loc.png](./images/type-except-loc.png)

The interface shows, for each type of exceptional location, the following data:

- **Name**: it is unique;
- **Abbreviation**;
- **Area**: the area in which the equipment will be available. This is a mandatory field.
- A **description**;
- **Allow overrun**: this allows, or not, the journey time to impinge on the exceptional location;
- **Work start time**: defines a default time for the end of the exceptional location;
- **Work start time**: defines a default time for the end of the exceptional location.

The address part is described in the "[Geocoding](https://mynomadia.com/privatedoc/9LLcWh7j74sENa54/optitime-doc/docs/en/otgs-reference-book/intro-geocodage.html "The geocoding")" chapter.

#### On-call duties

An on-call duty allows you to define a time window assigned for the fulfilment of one or several given intervention types.
For example, a morning assigned to fulfilling emergency interventions.

For these on-call duty time windows, the application will therefore not schedule any other interventions than those corresponding
to the authorised intervention types.

Access to the [list](https://mynomadia.com/privatedoc/9LLcWh7j74sENa54/optitime-doc/docs/en/otgs-reference-book/generalites.html#generalite-liste "Data home page") of on-call duties is by clicking on the On-call duties link in the menu. A choice is offered for managing [on-call duty day templates](https://mynomadia.com/privatedoc/9LLcWh7j74sENa54/optitime-doc/docs/en/otgs-reference-book/donnees.html#modele-jour-astreinte "On-call duty template") or [on-call duty week templates](https://mynomadia.com/privatedoc/9LLcWh7j74sENa54/optitime-doc/docs/en/otgs-reference-book/donnees.html#modele-semaine-astreinte "On-call duties, week template").

##### On-call duty template

It is possible to [create](https://mynomadia.com/privatedoc/9LLcWh7j74sENa54/optitime-doc/docs/en/otgs-reference-book/generalites.html#creation "Create a new data item"), [consult](https://mynomadia.com/privatedoc/9LLcWh7j74sENa54/optitime-doc/docs/en/otgs-reference-book/generalites.html#modification "Consult or edit an existing data item"), [duplicate](https://mynomadia.com/privatedoc/9LLcWh7j74sENa54/optitime-doc/docs/en/otgs-reference-book/generalites.html#duplication "Duplicating a data item") or [deactivate](https://mynomadia.com/privatedoc/9LLcWh7j74sENa54/optitime-doc/docs/en/otgs-reference-book/generalites.html#suppression "De-activating / Deleting a data item") an on-call duty day template.

**List of on-call duty days**

Access the [list](https://mynomadia.com/privatedoc/9LLcWh7j74sENa54/optitime-doc/docs/en/otgs-reference-book/generalites.html#generalite-liste "Data home page") of day on-call duties by clicking on the On-call duties > Day template link in the menu.

The interface allows you to filter the list of templates in relation to the area of affiliation and worksite. Click on ![images/ref/buttons/bouton-prendre-rdv.png](./images/bouton-prendre-rdv_2.png) to apply your choice.

**On-call duty form**

The [form](https://mynomadia.com/privatedoc/9LLcWh7j74sENa54/optitime-doc/docs/en/otgs-reference-book/generalites.html#generalite-fiche "Data form") of the on-call duty has just one tab.

Daily on-call duty

![images/ref/admin/astreinte-jour.png](./images/astreinte-jour.png)

The interface shows, for each on-call duty, the following data:

- **Name**: it is unique;
- **Abbreviation**;
- **Colour**: offers options to customise the colour of an on-call duty in the plannings;
- **Area**: the reference area for the on-call duty. This field is mandatory.
- **Worksite**: the worksite to which the resource will provide the on-call service.
- **Function**: the function with which the resource will be on duty.
- A **description**;
- A **Level** allowing you to define a priority level for the on-call duty (information field);
- **Begin time**: the start time for the on-call duty
- **End time**: the end time for the on-call duty
- **Beginning of the day**: indicates whether the on-call duty must be scheduled at the start of the day;
- **Middle of the day**: indicates whether the on-call duty must be scheduled in the middle of the day;
- **End of the day**: indicates whether the on-call duty must be scheduled at the end of the day;
- **Apply custom times**: if this is checked, you will be able to define the on-call duty hours more precisely:

Custom hours

![images/ref/admin/astreinte-jour-perso.png](./images/astreinte-jour-perso.png)

##### On-call duties, week template

It is possible to [create](https://mynomadia.com/privatedoc/9LLcWh7j74sENa54/optitime-doc/docs/en/otgs-reference-book/generalites.html#creation "Create a new data item"), [consult](https://mynomadia.com/privatedoc/9LLcWh7j74sENa54/optitime-doc/docs/en/otgs-reference-book/generalites.html#modification "Consult or edit an existing data item"), [duplicate](https://mynomadia.com/privatedoc/9LLcWh7j74sENa54/optitime-doc/docs/en/otgs-reference-book/generalites.html#duplication "Duplicating a data item") or [deactivate](https://mynomadia.com/privatedoc/9LLcWh7j74sENa54/optitime-doc/docs/en/otgs-reference-book/generalites.html#suppression "De-activating / Deleting a data item") a week template of an on-call duty.

**List of on-call duty weeks**

Access the [list](https://mynomadia.com/privatedoc/9LLcWh7j74sENa54/optitime-doc/docs/en/otgs-reference-book/generalites.html#generalite-liste "Data home page") of week on-call duties by clicking on the On-call duties > Week template link in the menu.

The interface allows you to filter the list of templates in relation to the area of affiliation and worksite. Click on ![images/ref/buttons/bouton-prendre-rdv.png](./images/bouton-prendre-rdv_3.png) to apply your choice.

**On-call duties week form**

The [form](https://mynomadia.com/privatedoc/9LLcWh7j74sENa54/optitime-doc/docs/en/otgs-reference-book/generalites.html#generalite-fiche "Data form") of the on-call duty has just one tab.

On-call duties week

![images/ref/admin/astreinte-semaine.png](./images/astreinte-semaine.png)

The interface shows, for each on-call duty, the following data:

- **Name**: it is unique;
- **Abbreviation**;
- **Colour**: allows you to assign a custom colour to the on-call duty in the plannings
- **Area**: the reference area for the on-call duty. This field is mandatory.
- **Worksite**: the worksite to which the resource will provide the on-call service.
- A **description**;
- An **on-call duty start day**: allows you to define the first day the on-call duty will be applied;
- A calendar, in which each day of the week is associated with an [on-call duty day template](https://mynomadia.com/privatedoc/9LLcWh7j74sENa54/optitime-doc/docs/en/otgs-reference-book/donnees.html#modele-jour-astreinte "On-call duty template").

#### Skill

Skills allow declaration to the application of the different tasks that a human resource in the enterprise can perform (for
example, TV repairs, white goods repairs, computer repairs…).
The confirmation of skills is performed in the human resource form, [Skills tab](https://mynomadia.com/privatedoc/9LLcWh7j74sENa54/optitime-doc/docs/en/otgs-reference-book/donnees.html#RH-comp "Skills tab")).

You can [create](https://mynomadia.com/privatedoc/9LLcWh7j74sENa54/optitime-doc/docs/en/otgs-reference-book/generalites.html#creation "Create a new data item"), [consult or edit](https://mynomadia.com/privatedoc/9LLcWh7j74sENa54/optitime-doc/docs/en/otgs-reference-book/generalites.html#modification "Consult or edit an existing data item"), [duplicate](https://mynomadia.com/privatedoc/9LLcWh7j74sENa54/optitime-doc/docs/en/otgs-reference-book/generalites.html#duplication "Duplicating a data item") or [deactivate](https://mynomadia.com/privatedoc/9LLcWh7j74sENa54/optitime-doc/docs/en/otgs-reference-book/generalites.html#suppression "De-activating / Deleting a data item") a skill.

##### List of skills

Access the [list](https://mynomadia.com/privatedoc/9LLcWh7j74sENa54/optitime-doc/docs/en/otgs-reference-book/generalites.html#generalite-liste "Data home page") of skills by clicking on the Skills link in the menu.

The interface allows you to filter the list of competencies in relation to their area of affiliation.

##### Skill form

The [form](https://mynomadia.com/privatedoc/9LLcWh7j74sENa54/optitime-doc/docs/en/otgs-reference-book/generalites.html#generalite-fiche "Data form") of the skill has just one tab.

Skill form

![images/ref/admin/comp.png](./images/comp.png)

The interface shows, for each skill, the following data:

- **Identifier** for the skill: it is unique;
- [**External reference**](https://mynomadia.com/privatedoc/9LLcWh7j74sENa54/optitime-doc/docs/en/otgs-reference-book/_glossary.html#Extref) for the skill;
- **Name** of the skill;
- A concise **description** of the skill;
- **Mandatory**: if checked, an appointment requiring this skill cannot be placed on the agenda of a resource, even in manual planning mode.
  When unchecked, the appointment cannot be placed in [batch](https://mynomadia.com/privatedoc/9LLcWh7j74sENa54/optitime-doc/docs/en/otgs-reference-book/_glossary.html#batch) or [real time](https://mynomadia.com/privatedoc/9LLcWh7j74sENa54/optitime-doc/docs/en/otgs-reference-book/donnees.html) optimization mode, but it can be inserted in manual planning mode.
- **In a team**: For multi-resource appointments, resources can share the necessary skills to perform an appointment.

#### Authorisation

Authorisations declare to the application the different skills a human resource in the enterprise can hold (for example, key
to the premises, passport, …).
The authorisations description of these is entered in the Human resource form,[Authorizations tab](https://mynomadia.com/privatedoc/9LLcWh7j74sENa54/optitime-doc/docs/en/otgs-reference-book/donnees.html#RH-autorisation "Authorisations tab").

It is possible to [create](https://mynomadia.com/privatedoc/9LLcWh7j74sENa54/optitime-doc/docs/en/otgs-reference-book/generalites.html#creation "Create a new data item"), [consult or edit](https://mynomadia.com/privatedoc/9LLcWh7j74sENa54/optitime-doc/docs/en/otgs-reference-book/generalites.html#modification "Consult or edit an existing data item"), [duplicate](https://mynomadia.com/privatedoc/9LLcWh7j74sENa54/optitime-doc/docs/en/otgs-reference-book/generalites.html#duplication "Duplicating a data item") or [deactivate](https://mynomadia.com/privatedoc/9LLcWh7j74sENa54/optitime-doc/docs/en/otgs-reference-book/generalites.html#suppression "De-activating / Deleting a data item") an authorisation.

##### List of authorisations

Access the [list](https://mynomadia.com/privatedoc/9LLcWh7j74sENa54/optitime-doc/docs/en/otgs-reference-book/generalites.html#generalite-liste "Data home page") of authorisations by clicking on the Authorisation link in the menu.

The interface allows you to filter the list of authorisations in relation to their area of affiliation.

##### Authorisation form

The authorisation [form](https://mynomadia.com/privatedoc/9LLcWh7j74sENa54/optitime-doc/docs/en/otgs-reference-book/generalites.html#generalite-fiche "Data form") consists of just one tab.

Authorisation form

![images/ref/admin/autorisation-modif.png](./images/autorisation-modif.png)

The interface shows, for each authorisation, the following data:

- **Identifier** for the authorisation: it is unique;
- **External reference**; this is a reference to the corresponding authorisation described in an external application;
- **Name** of the authorisation;
- A concise **description** of the authorisation;
- **Mandatory**: if the check-box is **checked**, an appointment requiring authorisation cannot be placed on a resource if it does not possess this authorisation, even in
  manual planning mode; if the check-box is **unchecked**, it will be possible to assign an appointment to a resource not possessing the necessary authorisation in manual mode.

#### Interventions group

The Intervention group declares to the application the different business activities of the enterprise (for example, after-sales
service, installation, quotation…). An intervention group is an association of several [types of intervention](https://mynomadia.com/privatedoc/9LLcWh7j74sENa54/optitime-doc/docs/en/otgs-reference-book/donnees.html#type-intervention "Intervention type (Intervention group)").

|  |  |
| --- | --- |
| [Tip] | Tip |
| The intervention group allows you to improve the legibility of the call centre interface during the taking of the appointment. |

Interventions group in the appointment taking interface, in the call centre

![images/ref/admin/groupe-interv-rdv.png](./images/groupe-interv-rdv.png)

You can [create](https://mynomadia.com/privatedoc/9LLcWh7j74sENa54/optitime-doc/docs/en/otgs-reference-book/generalites.html#creation "Create a new data item"), [consult](https://mynomadia.com/privatedoc/9LLcWh7j74sENa54/optitime-doc/docs/en/otgs-reference-book/generalites.html#modification "Consult or edit an existing data item"), [duplicate](https://mynomadia.com/privatedoc/9LLcWh7j74sENa54/optitime-doc/docs/en/otgs-reference-book/generalites.html#duplication "Duplicating a data item") or [deactivate](https://mynomadia.com/privatedoc/9LLcWh7j74sENa54/optitime-doc/docs/en/otgs-reference-book/generalites.html#suppression "De-activating / Deleting a data item") a interventions group.

##### List of intervention groups

Access the [list](https://mynomadia.com/privatedoc/9LLcWh7j74sENa54/optitime-doc/docs/en/otgs-reference-book/generalites.html#generalite-liste "Data home page") of intervention groups by clicking on the Intervention group link in the menu.

The interface enables filtering of the list of Intervention groups on area of affiliation.

##### Interventions group form

Interventions group form

![images/ref/admin/groupe-interv.png](./images/groupe-interv.png)

The [form](https://mynomadia.com/privatedoc/9LLcWh7j74sENa54/optitime-doc/docs/en/otgs-reference-book/generalites.html#generalite-fiche "Data form") comprises the following fields:

- **Identifier** for the intervention group: it is unique;
- **External reference**: this is a reference to the corresponding interventions group as described in an external application;
- **Name** of the intervention group;
- **Colour**: allows you to give a custom colour to the group of interventions in the plannings;
- **Area**: allows you to associate an intervention group to an area. This group - as well as all the types of intervention associated
  to it - will not be visible in the other areas.
  *All areas*: The group and types of intervention associated to it are available whatever the area.
- A concise **description** of the group.

#### Intervention type (Intervention group)

The types of intervention corresponding to the task to be accomplished during the appointment (for example: repairs, quotation).
For each type of intervention, certain skills are necessary for a resource to be assignable to this appointment.

You can [create](https://mynomadia.com/privatedoc/9LLcWh7j74sENa54/optitime-doc/docs/en/otgs-reference-book/generalites.html#creation "Create a new data item"), [consult](https://mynomadia.com/privatedoc/9LLcWh7j74sENa54/optitime-doc/docs/en/otgs-reference-book/generalites.html#modification "Consult or edit an existing data item"), [duplicate](https://mynomadia.com/privatedoc/9LLcWh7j74sENa54/optitime-doc/docs/en/otgs-reference-book/generalites.html#duplication "Duplicating a data item") or [deactivate](https://mynomadia.com/privatedoc/9LLcWh7j74sENa54/optitime-doc/docs/en/otgs-reference-book/generalites.html#suppression "De-activating / Deleting a data item") an intervention type.

##### List of intervention types

Access the [list](https://mynomadia.com/privatedoc/9LLcWh7j74sENa54/optitime-doc/docs/en/otgs-reference-book/generalites.html#generalite-liste "Data home page") of intervention types by clicking on the Mission type link located beneath the **[Intervention group](https://mynomadia.com/privatedoc/9LLcWh7j74sENa54/optitime-doc/docs/en/otgs-reference-book/donnees.html#groupe-intervention "Interventions group")** item in the menu.

The interface enables filtering of intervention types in relation to their [group of affiliation](https://mynomadia.com/privatedoc/9LLcWh7j74sENa54/optitime-doc/docs/en/otgs-reference-book/donnees.html#groupe-intervention "Interventions group").

##### Intervention type form

Intervention type form

![images/ref/admin/type-interv.png](./images/type-interv.png)

The [form](https://mynomadia.com/privatedoc/9LLcWh7j74sENa54/optitime-doc/docs/en/otgs-reference-book/generalites.html#generalite-fiche "Data form") comprises the following fields:

- **Identifier** for the Intervention type: it is unique;
- The [**External reference**](https://mynomadia.com/privatedoc/9LLcWh7j74sENa54/optitime-doc/docs/en/otgs-reference-book/_glossary.html#Extref) of the Intervention type;
- **Name** of the intervention type;
- **Area of intervention**: allows you to associate an intervention group to an area. This group - as well as all the types of intervention associated
  to it - will not be visible in the other areas.
  *All areas*: The group and types of intervention associated to it are available whatever the area.
- A concise **description** of the type of intervention;
- The **Average intervention duration**: this makes it possible to prefill the duration for an appointment of this type when taking the appointment.
- **Favourite days**: allows you to favour the placing of an appointment of this type on days for which the value is 1.
- **Skills required**: specification of the [skills](https://mynomadia.com/privatedoc/9LLcWh7j74sENa54/optitime-doc/docs/en/otgs-reference-book/donnees.html#competence "Skill") needed for each type of intervention.

The intervention type is modified or created with the **Save** command. The **Back to the list** action cancels any modifications made.

#### Targets

It is possible to define, by worksite, by resource, or by function, an objective in terms of, for example, appointments taken,
fulfilled, or income forecast for a given [type](https://mynomadia.com/privatedoc/9LLcWh7j74sENa54/optitime-doc/docs/en/otgs-reference-book/donnees.html#type-intervention "Intervention type (Intervention group)") or [group](https://mynomadia.com/privatedoc/9LLcWh7j74sENa54/optitime-doc/docs/en/otgs-reference-book/donnees.html#groupe-intervention "Interventions group") of interventions.

You can [create](https://mynomadia.com/privatedoc/9LLcWh7j74sENa54/optitime-doc/docs/en/otgs-reference-book/generalites.html#creation "Create a new data item"), [consult](https://mynomadia.com/privatedoc/9LLcWh7j74sENa54/optitime-doc/docs/en/otgs-reference-book/generalites.html#modification "Consult or edit an existing data item"), [duplicate](https://mynomadia.com/privatedoc/9LLcWh7j74sENa54/optitime-doc/docs/en/otgs-reference-book/generalites.html#duplication "Duplicating a data item") or [deactivate](https://mynomadia.com/privatedoc/9LLcWh7j74sENa54/optitime-doc/docs/en/otgs-reference-book/generalites.html#suppression "De-activating / Deleting a data item") a target.

##### List of targets

Access the [list](https://mynomadia.com/privatedoc/9LLcWh7j74sENa54/optitime-doc/docs/en/otgs-reference-book/generalites.html#generalite-liste "Data home page") of targets by clicking on the Targets link in the menu.

Filtering on targets

![images/ref/admin/objectifs-acces.png](./images/objectifs-acces.png)

Before consulting or creating a target, you must define several filters:

- **Area**: the area on which the target depends;
- Select a **worksite**, a **human resource** or a **function** in the corresponding drop-down list.

The list of targets appears with the following information:

- The **start** and **end** dates for the period of the target;
- The **type** of target;
- The [**intervention group**](https://mynomadia.com/privatedoc/9LLcWh7j74sENa54/optitime-doc/docs/en/otgs-reference-book/donnees.html#groupe-intervention "Interventions group") associated to the target;
- The [**type of intervention**](https://mynomadia.com/privatedoc/9LLcWh7j74sENa54/optitime-doc/docs/en/otgs-reference-book/donnees.html#type-intervention "Intervention type (Intervention group)") associated to the target;
- The **value** of the target.

List of targets

![images/ref/admin/objectifs.png](./images/objectifs.png)

##### Form for a target

Form for a target

![images/ref/admin/objectifs-nouveau.png](./images/objectifs-nouveau.png)

The [form](https://mynomadia.com/privatedoc/9LLcWh7j74sENa54/optitime-doc/docs/en/otgs-reference-book/generalites.html#generalite-fiche "Data form") comprises the following fields:

- **Type** of target: indicates the type of objective to be targeted. The drop-down list contains the following values:

  - *Revenue or Turnover*
  - *Number of appointments taken*
  - *Number of appointments*
  - *Daily turnover*
  - *Daily number of appointments*
  - *Daily number of appointments made*
  - *Number of weekly meetings*
- The [**interventions group**](https://mynomadia.com/privatedoc/9LLcWh7j74sENa54/optitime-doc/docs/en/otgs-reference-book/donnees.html#groupe-intervention "Interventions group");
- The [**interventions type**](https://mynomadia.com/privatedoc/9LLcWh7j74sENa54/optitime-doc/docs/en/otgs-reference-book/donnees.html#type-intervention "Intervention type (Intervention group)");
- **From**, **To** allow you to define the start and finish date for the period;
- The value of the target.

|  |  |
| --- | --- |
| [Tip] | Tip |
| - The turnover is then visible in the weekly planning by depot, in the form of a gauge. The appointments with a status of *Fulfilled* and *Confirmed* are used to compare the turnover achieved in relation to the target. - When a target in terms of the number of appointments, for example, has been reached, it will no longer be possible, in [batch](https://mynomadia.com/privatedoc/9LLcWh7j74sENa54/optitime-doc/docs/en/otgs-reference-book/_glossary.html#batch) or [real time](https://mynomadia.com/privatedoc/9LLcWh7j74sENa54/optitime-doc/docs/en/otgs-reference-book/donnees.html) optimization mode to plan appointments of this type. |

#### Follow-up

Access to the activity tracking [list](https://mynomadia.com/privatedoc/9LLcWh7j74sENa54/optitime-doc/docs/en/otgs-reference-book/generalites.html#generalite-liste "Data home page") is by clicking on the Follow-up link in the menu. At this point, you have the option to manage the [completion status](https://mynomadia.com/privatedoc/9LLcWh7j74sENa54/optitime-doc/docs/en/otgs-reference-book/donnees.html#etat-realisation "Completion status") or the [follow-up action required](https://mynomadia.com/privatedoc/9LLcWh7j74sENa54/optitime-doc/docs/en/otgs-reference-book/donnees.html#suite "Follow-up").

##### Completion status

The completion statuses are customisable statuses for the appointments used in the [appointment form](https://mynomadia.com/privatedoc/9LLcWh7j74sENa54/optitime-doc/docs/en/otgs-reference-book/call-center-objets.html#fiche-rdv "Appointment form").

|  |  |
| --- | --- |
| [Tip] | Tip |
| They may serve to communicate the state of progress on the operation by the resource. |

**List of completion statuses**

Access the [list](https://mynomadia.com/privatedoc/9LLcWh7j74sENa54/optitime-doc/docs/en/otgs-reference-book/generalites.html#generalite-liste "Data home page") of completion statuses by clicking on the Completion status link in the menu.

It is possible to [create](https://mynomadia.com/privatedoc/9LLcWh7j74sENa54/optitime-doc/docs/en/otgs-reference-book/generalites.html#creation "Create a new data item") or [deactivate](https://mynomadia.com/privatedoc/9LLcWh7j74sENa54/optitime-doc/docs/en/otgs-reference-book/generalites.html#suppression "De-activating / Deleting a data item") a completion status.

**Completion status form**

Completion status form

![images/ref/admin/etat-realisation.png](./images/etat-realisation.png)

The [form](https://mynomadia.com/privatedoc/9LLcWh7j74sENa54/optitime-doc/docs/en/otgs-reference-book/generalites.html#generalite-fiche "Data form") comprises the following fields:

- **External reference**: this is a reference described in an external application;
- **Name** (mandatory);
- **Abbreviation**;
- **Area**: associates a completion status to an area
- A concise **description**.

##### Follow-up

Follow-up actions are customisable statuses for an appointment used in the [appointment form](https://mynomadia.com/privatedoc/9LLcWh7j74sENa54/optitime-doc/docs/en/otgs-reference-book/call-center-objets.html#fiche-rdv "Appointment form").

Access the [list](https://mynomadia.com/privatedoc/9LLcWh7j74sENa54/optitime-doc/docs/en/otgs-reference-book/generalites.html#generalite-liste "Data home page") of follow-ups by clicking on the Activity tracking > Follow-up link in the menu.

The principle is the same as for the [completion statuses](https://mynomadia.com/privatedoc/9LLcWh7j74sENa54/optitime-doc/docs/en/otgs-reference-book/donnees.html#etat-realisation "Completion status").

|  |  |
| --- | --- |
| [Tip] | Tip |
| These can serve as a reminder to know which follow-up to assign to the appointment. For example, remind the customer or send a document. |

#### Typology

#### Calendars

##### Public holidays

You can [create](https://mynomadia.com/privatedoc/9LLcWh7j74sENa54/optitime-doc/docs/en/otgs-reference-book/generalites.html#creation "Create a new data item"), [consult](https://mynomadia.com/privatedoc/9LLcWh7j74sENa54/optitime-doc/docs/en/otgs-reference-book/generalites.html#modification "Consult or edit an existing data item"), [duplicate](https://mynomadia.com/privatedoc/9LLcWh7j74sENa54/optitime-doc/docs/en/otgs-reference-book/generalites.html#duplication "Duplicating a data item") or [deactivate](https://mynomadia.com/privatedoc/9LLcWh7j74sENa54/optitime-doc/docs/en/otgs-reference-book/generalites.html#suppression "De-activating / Deleting a data item") a public holiday.

|  |  |
| --- | --- |
| [Tip] | Tip |
| The application will never suggest putting an appointment on a public holiday unless the action is forced by the user (Cf. [Managing rights](https://mynomadia.com/privatedoc/9LLcWh7j74sENa54/optitime-doc/docs/en/otgs-reference-book/utilisateurs.html "User handling"))to take appointments on a public holiday. |

**List of public holidays**

Access to the [list](https://mynomadia.com/privatedoc/9LLcWh7j74sENa54/optitime-doc/docs/en/otgs-reference-book/generalites.html#generalite-liste "Data home page") of public holidays is by clicking on the Public holidays link, under the Calendars item, in the menu.

List of Public holidays

![images/ref/admin/jours-feries-acces.png](./images/jours-feries-acces.png)

The interface allows you to filter the list of bank holidays in relation to the area of affiliation, and this for the whole
year.

**Form for a public holiday**

Public holiday form

![images/ref/admin/jours-feries.png](./images/jours-feries.png)

The [form](https://mynomadia.com/privatedoc/9LLcWh7j74sENa54/optitime-doc/docs/en/otgs-reference-book/generalites.html#generalite-fiche "Data form") comprises the following fields:

- Unique **Identifier** for a Public holiday, in read-only mode, attributed by the application on creation of the Public holiday;
- **Name** of the Public Holiday. This information is mandatory;
- **Area**: this is the area of affiliation for the bank holiday;
- **Worksite** for which the bank holiday is defined;
- Corresponding **Date**. This information is mandatory and must be in the format DD/MM/YYYY (for example, 02/03/2014 for the 2 March 2014).

##### Day template

The Day template enables definition of typical days for:

- creating standard weeks utilisable in the form of the resource [Cf. Next chapter](https://mynomadia.com/privatedoc/9LLcWh7j74sENa54/optitime-doc/docs/en/otgs-reference-book/donnees.html#modele-semaine "Week template")
- assign days for which the working hours differ from the usual hours in the resource’s form, [Typical week tab](https://mynomadia.com/privatedoc/9LLcWh7j74sENa54/optitime-doc/docs/en/otgs-reference-book/donnees.html#RH-semaine "Typical week tab")

It is possible to [create](https://mynomadia.com/privatedoc/9LLcWh7j74sENa54/optitime-doc/docs/en/otgs-reference-book/generalites.html#creation "Create a new data item"), [consult](https://mynomadia.com/privatedoc/9LLcWh7j74sENa54/optitime-doc/docs/en/otgs-reference-book/generalites.html#modification "Consult or edit an existing data item"), [duplicate](https://mynomadia.com/privatedoc/9LLcWh7j74sENa54/optitime-doc/docs/en/otgs-reference-book/generalites.html#duplication "Duplicating a data item") or [delete](https://mynomadia.com/privatedoc/9LLcWh7j74sENa54/optitime-doc/docs/en/otgs-reference-book/generalites.html#suppression "De-activating / Deleting a data item") a day template.

**List of days templates**

Access the [list](https://mynomadia.com/privatedoc/9LLcWh7j74sENa54/optitime-doc/docs/en/otgs-reference-book/generalites.html#generalite-liste "Data home page") of day templates by clicking on the Day template link, under the calendar item, in the menu.

List of day templates

![images/ref/admin/modele-jour-liste.png](./images/modele-jour-liste.png)

The interface allows you to filter the list of templates in relation to the area of affiliation and worksite. Click on ![images/ref/buttons/bouton-prendre-rdv.png](./images/bouton-prendre-rdv_4.png) to apply your choice.

**Day template form**

Day template form

![images/ref/admin/modele-jour.png](./images/modele-jour.png)

The [form](https://mynomadia.com/privatedoc/9LLcWh7j74sENa54/optitime-doc/docs/en/otgs-reference-book/generalites.html#generalite-fiche "Data form") comprises the following fields:

- Unique **Identifier** for the day template, in read-only mode, attributed by the application to the creation of the day template;
- **Day of the week**: day on which the day template can be based. If *All* is selected, this template can be applied to any day of the week;
- **External reference**: [external reference](https://mynomadia.com/privatedoc/9LLcWh7j74sENa54/optitime-doc/docs/en/otgs-reference-book/_glossary.html#Extref) for the day template;
- **Name**: this is required;
- **Area**: the area in which the template will be available. This field is required;
- **Worksite**
- **Working hours**: mandatory, this defines start and finish times for the working day;
- **Lunch break**: mandatory, this defines the earliest start time for the lunch break, and the latest possible time for the end of the break;
- Mandatory **Lunch break duration**;
- **Worked day**: check if the resource is working on this day;
- **Possible night away**: check if the resource can fulfill a night away on this day.

|  |  |
| --- | --- |
| [Tip] | Tip |
| The external reference is notably used to assign a [particular type of working day](https://mynomadia.com/privatedoc/9LLcWh7j74sENa54/optitime-doc/docs/en/otgs-reference-book/donnees.html#RH-semaine "Typical week tab") to a resource. |

##### Week template

The week template enables definition of typical weeks for:

- assign the same typical week to several resources without having to configure each day one by one, in the resource’s form
  [Typical Week tab](https://mynomadia.com/privatedoc/9LLcWh7j74sENa54/optitime-doc/docs/en/otgs-reference-book/donnees.html#RH-semaine "Typical week tab")
- assign weeks for which the working hours differ from the usual hours in the resource’s form, [Typical week tab](https://mynomadia.com/privatedoc/9LLcWh7j74sENa54/optitime-doc/docs/en/otgs-reference-book/donnees.html#RH-semaine "Typical week tab")

It is possible to [create](https://mynomadia.com/privatedoc/9LLcWh7j74sENa54/optitime-doc/docs/en/otgs-reference-book/generalites.html#creation "Create a new data item"), [consult](https://mynomadia.com/privatedoc/9LLcWh7j74sENa54/optitime-doc/docs/en/otgs-reference-book/generalites.html#modification "Consult or edit an existing data item"), [duplicate](https://mynomadia.com/privatedoc/9LLcWh7j74sENa54/optitime-doc/docs/en/otgs-reference-book/generalites.html#duplication "Duplicating a data item") or [delete](https://mynomadia.com/privatedoc/9LLcWh7j74sENa54/optitime-doc/docs/en/otgs-reference-book/generalites.html#suppression "De-activating / Deleting a data item") a week template.

**List of week templates**

Access to the [list](https://mynomadia.com/privatedoc/9LLcWh7j74sENa54/optitime-doc/docs/en/otgs-reference-book/generalites.html#generalite-liste "Data home page") of week templates is by clicking on the Week template link under the Calendars item, in the menu.

List of week templates

![images/ref/admin/modele-semaine-liste.png](./images/modele-semaine-liste.png)

The interface allows you to filter the list of templates in relation to the area of affiliation and worksite. Click on ![images/ref/buttons/bouton-prendre-rdv.png](./images/bouton-prendre-rdv_5.png) to apply your choice.

**Week template form**

Week template form

![images/ref/admin/modele-semaine.png](./images/modele-semaine.png)

The drop-down lists enable selection of a day template for each day of the week, to select from the presaved day templates
([Cf. Day template chapter](https://mynomadia.com/privatedoc/9LLcWh7j74sENa54/optitime-doc/docs/en/otgs-reference-book/donnees.html#modele-jour "Day template")).

The other fields cannot be modified. They are described in the [previous chapter](https://mynomadia.com/privatedoc/9LLcWh7j74sENa54/optitime-doc/docs/en/otgs-reference-book/donnees.html#modele-jour "Day template").

##### Sales period

A sales period enables declaration to Opti-Time of the timespans during which [batch optimization](https://mynomadia.com/privatedoc/9LLcWh7j74sENa54/optitime-doc/docs/en/otgs-reference-book/_glossary.html#batch) is possible in the [configuration of the optimization](https://mynomadia.com/privatedoc/9LLcWh7j74sENa54/optitime-doc/docs/en/otgs-reference-book/optimisation.html#optim-optim "Optimisation tab").

|  |  |
| --- | --- |
| [Tip] | Tip |
| This function can be used, for example for a company wishing to configure a regular batch optimization from the first Monday of the month through to the last Friday of the month. |

You can [create](https://mynomadia.com/privatedoc/9LLcWh7j74sENa54/optitime-doc/docs/en/otgs-reference-book/generalites.html#creation "Create a new data item"), [consult](https://mynomadia.com/privatedoc/9LLcWh7j74sENa54/optitime-doc/docs/en/otgs-reference-book/generalites.html#modification "Consult or edit an existing data item"), or [duplicate](https://mynomadia.com/privatedoc/9LLcWh7j74sENa54/optitime-doc/docs/en/otgs-reference-book/generalites.html#duplication "Duplicating a data item") a sales period.

**List of sales periods**

Access to the [list](https://mynomadia.com/privatedoc/9LLcWh7j74sENa54/optitime-doc/docs/en/otgs-reference-book/generalites.html#generalite-liste "Data home page") of sales periods is by clicking on the Period of sale link in the menu.

List of sales periods

![images/ref/admin/periode-acces.png](./images/periode-acces.png)

The list can be filtered by area.

**Form for a sales period**

Sales period form

![images/ref/admin/periode-nouveau.png](./images/periode-nouveau.png)

The [form](https://mynomadia.com/privatedoc/9LLcWh7j74sENa54/optitime-doc/docs/en/otgs-reference-book/generalites.html#generalite-fiche "Data form") for the sales period is made up of the following information:

- **Identifier** for the sales period: this is unique (automatically attributed to the creation of a new sales period);
- La [**External reference**](https://mynomadia.com/privatedoc/9LLcWh7j74sENa54/optitime-doc/docs/en/otgs-reference-book/_glossary.html#Extref) for the sales period;
- **Name** (mandatory field): name of the sales period;
- **Area** (mandatory field): defines the area to which the sales period must be applied;
- **Description**: concise description of the sales period;
- **Start date** (mandatory field): defines the start date for the sales period;
- **Finish date** (mandatory field): defines the end date of the sales period.

---

|  |  |  |
| --- | --- | --- |
| [Prev](https://mynomadia.com/privatedoc/9LLcWh7j74sENa54/optitime-doc/docs/en/otgs-reference-book/generalites.html) | [Up](https://mynomadia.com/privatedoc/9LLcWh7j74sENa54/optitime-doc/docs/en/otgs-reference-book/module-administration.html) | [Next](https://mynomadia.com/privatedoc/9LLcWh7j74sENa54/optitime-doc/docs/en/otgs-reference-book/optimisation.html) |
|  | [Home](https://mynomadia.com/privatedoc/9LLcWh7j74sENa54/optitime-doc/docs/en/otgs-reference-book/index.html) |  |

- [Contents](https://mynomadia.com/privatedoc/9LLcWh7j74sENa54/optitime-doc/docs/en/otgs-reference-book/donnees.html#treeDiv)
- [Search](https://mynomadia.com/privatedoc/9LLcWh7j74sENa54/optitime-doc/docs/en/otgs-reference-book/donnees.html#searchDiv)

![loading table of contents...](./images/loading_3.gif)

- [Introduction](https://mynomadia.com/privatedoc/9LLcWh7j74sENa54/optitime-doc/docs/en/otgs-reference-book/_introduction.html)
  - [Defining terms](https://mynomadia.com/privatedoc/9LLcWh7j74sENa54/optitime-doc/docs/en/otgs-reference-book/_defining_terms.html)
  - [Presentation of the Reference Guide](https://mynomadia.com/privatedoc/9LLcWh7j74sENa54/optitime-doc/docs/en/otgs-reference-book/_presentation_of_the_reference_guide.html)
  - [Running the application](https://mynomadia.com/privatedoc/9LLcWh7j74sENa54/optitime-doc/docs/en/otgs-reference-book/otgs-connexion.html)
  - [The different statuses for appointments in Opti-time](https://mynomadia.com/privatedoc/9LLcWh7j74sENa54/optitime-doc/docs/en/otgs-reference-book/_the_different_statuses_for_appointments_in_opti_time.html)
    - [Status macros](https://mynomadia.com/privatedoc/9LLcWh7j74sENa54/optitime-doc/docs/en/otgs-reference-book/_the_different_statuses_for_appointments_in_opti_time.html#_status_macros)
    - [Statuses](https://mynomadia.com/privatedoc/9LLcWh7j74sENa54/optitime-doc/docs/en/otgs-reference-book/_the_different_statuses_for_appointments_in_opti_time.html#statuts)
    - [Progression steps](https://mynomadia.com/privatedoc/9LLcWh7j74sENa54/optitime-doc/docs/en/otgs-reference-book/_the_different_statuses_for_appointments_in_opti_time.html#etats-avancement)
    - [Fulfilment statuses](https://mynomadia.com/privatedoc/9LLcWh7j74sENa54/optitime-doc/docs/en/otgs-reference-book/_the_different_statuses_for_appointments_in_opti_time.html#etats-realisation)
    - [Notification statuses](https://mynomadia.com/privatedoc/9LLcWh7j74sENa54/optitime-doc/docs/en/otgs-reference-book/_the_different_statuses_for_appointments_in_opti_time.html#etats-notification)
    - [Life cycle of an appointment](https://mynomadia.com/privatedoc/9LLcWh7j74sENa54/optitime-doc/docs/en/otgs-reference-book/_the_different_statuses_for_appointments_in_opti_time.html#cycle-rdv)
  - [The geocoding](https://mynomadia.com/privatedoc/9LLcWh7j74sENa54/optitime-doc/docs/en/otgs-reference-book/intro-geocodage.html)
- [Guided Help](https://mynomadia.com/privatedoc/9LLcWh7j74sENa54/optitime-doc/docs/en/otgs-reference-book/WM.html)
- [The header bar](https://mynomadia.com/privatedoc/9LLcWh7j74sENa54/optitime-doc/docs/en/otgs-reference-book/bandeau.html)
  - [Change area](https://mynomadia.com/privatedoc/9LLcWh7j74sENa54/optitime-doc/docs/en/otgs-reference-book/bandeau-changer-region.html)
  - [Change the password](https://mynomadia.com/privatedoc/9LLcWh7j74sENa54/optitime-doc/docs/en/otgs-reference-book/bandeau-changer-mdp.html)
  - [Disconnection](https://mynomadia.com/privatedoc/9LLcWh7j74sENa54/optitime-doc/docs/en/otgs-reference-book/deco.html)
- [Portal](https://mynomadia.com/privatedoc/9LLcWh7j74sENa54/optitime-doc/docs/en/otgs-reference-book/module-portail.html)
  - [Home page](https://mynomadia.com/privatedoc/9LLcWh7j74sENa54/optitime-doc/docs/en/otgs-reference-book/_home_page.html)
  - [Planning](https://mynomadia.com/privatedoc/9LLcWh7j74sENa54/optitime-doc/docs/en/otgs-reference-book/portail-planning.html)
  - [Appointment form](https://mynomadia.com/privatedoc/9LLcWh7j74sENa54/optitime-doc/docs/en/otgs-reference-book/rendezvous.html)
  - [Tasks to be performed](https://mynomadia.com/privatedoc/9LLcWh7j74sENa54/optitime-doc/docs/en/otgs-reference-book/Tacheafaire.html)
    - [Visit reports pending](https://mynomadia.com/privatedoc/9LLcWh7j74sENa54/optitime-doc/docs/en/otgs-reference-book/Tacheafaire.html#tacheafaire1)
    - [Appointments to reschedule](https://mynomadia.com/privatedoc/9LLcWh7j74sENa54/optitime-doc/docs/en/otgs-reference-book/Tacheafaire.html#rdv-a-replanifier)
  - [Team alerts](https://mynomadia.com/privatedoc/9LLcWh7j74sENa54/optitime-doc/docs/en/otgs-reference-book/alert-equip.html)
  - [Week](https://mynomadia.com/privatedoc/9LLcWh7j74sENa54/optitime-doc/docs/en/otgs-reference-book/portail-semaine.html)
  - [Month](https://mynomadia.com/privatedoc/9LLcWh7j74sENa54/optitime-doc/docs/en/otgs-reference-book/portail-mois.html)
  - [Team schedule](https://mynomadia.com/privatedoc/9LLcWh7j74sENa54/optitime-doc/docs/en/otgs-reference-book/portail-plan-equipe.html)
  - [Area schedule](https://mynomadia.com/privatedoc/9LLcWh7j74sENa54/optitime-doc/docs/en/otgs-reference-book/portail-plan-reg.html)
  - [Worksite schedule](https://mynomadia.com/privatedoc/9LLcWh7j74sENa54/optitime-doc/docs/en/otgs-reference-book/portail-site-trav.html)
  - [Multi-Resource schedule](https://mynomadia.com/privatedoc/9LLcWh7j74sENa54/optitime-doc/docs/en/otgs-reference-book/portail-multi-res.html)
  - [Unavailabilities](https://mynomadia.com/privatedoc/9LLcWh7j74sENa54/optitime-doc/docs/en/otgs-reference-book/indisponibilite.html)
    - [One-off unavailabilities](https://mynomadia.com/privatedoc/9LLcWh7j74sENa54/optitime-doc/docs/en/otgs-reference-book/indisponibilite.html#_one_off_unavailabilities)
    - [Regular unavailabilities](https://mynomadia.com/privatedoc/9LLcWh7j74sENa54/optitime-doc/docs/en/otgs-reference-book/indisponibilite.html#_regular_unavailabilities)
    - [Handling unavailabilities](https://mynomadia.com/privatedoc/9LLcWh7j74sENa54/optitime-doc/docs/en/otgs-reference-book/indisponibilite.html#_handling_unavailabilities)
      - [Adding an unavailability](https://mynomadia.com/privatedoc/9LLcWh7j74sENa54/optitime-doc/docs/en/otgs-reference-book/indisponibilite.html#_adding_an_unavailability)
      - [Adding a multi-resource unavailability](https://mynomadia.com/privatedoc/9LLcWh7j74sENa54/optitime-doc/docs/en/otgs-reference-book/indisponibilite.html#indisponibilitesmultiressource)
      - [Unavailability form](https://mynomadia.com/privatedoc/9LLcWh7j74sENa54/optitime-doc/docs/en/otgs-reference-book/indisponibilite.html#_unavailability_form)
      - [Unplanning or reassigning appointments](https://mynomadia.com/privatedoc/9LLcWh7j74sENa54/optitime-doc/docs/en/otgs-reference-book/indisponibilite.html#_unplanning_or_reassigning_appointments)
  - [Visit reports](https://mynomadia.com/privatedoc/9LLcWh7j74sENa54/optitime-doc/docs/en/otgs-reference-book/compterendus.html)
  - [Roadbook](https://mynomadia.com/privatedoc/9LLcWh7j74sENa54/optitime-doc/docs/en/otgs-reference-book/portail-feuille-de-route.html)
  - [Global optimization](https://mynomadia.com/privatedoc/9LLcWh7j74sENa54/optitime-doc/docs/en/otgs-reference-book/portail-optim-glob.html)
    - [Export tab](https://mynomadia.com/privatedoc/9LLcWh7j74sENa54/optitime-doc/docs/en/otgs-reference-book/portail-optim-glob.html#_export_tab)
    - [Import tab](https://mynomadia.com/privatedoc/9LLcWh7j74sENa54/optitime-doc/docs/en/otgs-reference-book/portail-optim-glob.html#_import_tab)
    - [Automatic tab](https://mynomadia.com/privatedoc/9LLcWh7j74sENa54/optitime-doc/docs/en/otgs-reference-book/portail-optim-glob.html#_automatic_tab)
    - [Journal tab](https://mynomadia.com/privatedoc/9LLcWh7j74sENa54/optitime-doc/docs/en/otgs-reference-book/portail-optim-glob.html#_journal_tab)
  - [Legend](https://mynomadia.com/privatedoc/9LLcWh7j74sENa54/optitime-doc/docs/en/otgs-reference-book/portail-legende.html)
  - [Opti-Time Mobile Application](https://mynomadia.com/privatedoc/9LLcWh7j74sENa54/optitime-doc/docs/en/otgs-reference-book/portail-otm.html)
- [Planning](https://mynomadia.com/privatedoc/9LLcWh7j74sENa54/optitime-doc/docs/en/otgs-reference-book/module-planification.html)
  - [Objects in the Planning module](https://mynomadia.com/privatedoc/9LLcWh7j74sENa54/optitime-doc/docs/en/otgs-reference-book/call-center-objets.html)
    - [Forms](https://mynomadia.com/privatedoc/9LLcWh7j74sENa54/optitime-doc/docs/en/otgs-reference-book/call-center-objets.html#call-center-fiche-gral)
    - [Customer types](https://mynomadia.com/privatedoc/9LLcWh7j74sENa54/optitime-doc/docs/en/otgs-reference-book/call-center-objets.html#objets-types-client)
      - [Customer type form](https://mynomadia.com/privatedoc/9LLcWh7j74sENa54/optitime-doc/docs/en/otgs-reference-book/call-center-objets.html#type-client-fiche)
    - [Customer kinds](https://mynomadia.com/privatedoc/9LLcWh7j74sENa54/optitime-doc/docs/en/otgs-reference-book/call-center-objets.html#objets-nature-client)
      - [Customer kind form](https://mynomadia.com/privatedoc/9LLcWh7j74sENa54/optitime-doc/docs/en/otgs-reference-book/call-center-objets.html#nature-client-fiche)
    - [Customers](https://mynomadia.com/privatedoc/9LLcWh7j74sENa54/optitime-doc/docs/en/otgs-reference-book/call-center-objets.html#objets-clients)
      - [Customer form](https://mynomadia.com/privatedoc/9LLcWh7j74sENa54/optitime-doc/docs/en/otgs-reference-book/call-center-objets.html#fiche-client)
    - [Orderers](https://mynomadia.com/privatedoc/9LLcWh7j74sENa54/optitime-doc/docs/en/otgs-reference-book/call-center-objets.html#commanditaire)
      - [Orderer form](https://mynomadia.com/privatedoc/9LLcWh7j74sENa54/optitime-doc/docs/en/otgs-reference-book/call-center-objets.html#fiche-commanditaire)
    - [Appointments](https://mynomadia.com/privatedoc/9LLcWh7j74sENa54/optitime-doc/docs/en/otgs-reference-book/call-center-objets.html#objets-rdv)
      - [Appointment form](https://mynomadia.com/privatedoc/9LLcWh7j74sENa54/optitime-doc/docs/en/otgs-reference-book/call-center-objets.html#fiche-rdv)
    - [Steps in the scheduling process](https://mynomadia.com/privatedoc/9LLcWh7j74sENa54/optitime-doc/docs/en/otgs-reference-book/call-center-objets.html#_steps_in_the_scheduling_process)
      - [Qualification of the appointment](https://mynomadia.com/privatedoc/9LLcWh7j74sENa54/optitime-doc/docs/en/otgs-reference-book/call-center-objets.html#creation-rdv-demande)
      - [Appointment request](https://mynomadia.com/privatedoc/9LLcWh7j74sENa54/optitime-doc/docs/en/otgs-reference-book/call-center-objets.html#demande-rdv)
      - [Optimised appointment (real time)](https://mynomadia.com/privatedoc/9LLcWh7j74sENa54/optitime-doc/docs/en/otgs-reference-book/call-center-objets.html#planification-optimisee-rdv)
      - [Manual appointment](https://mynomadia.com/privatedoc/9LLcWh7j74sENa54/optitime-doc/docs/en/otgs-reference-book/call-center-objets.html#planification-manuelle-rdv)
    - [Setting up liaisons between appointments](https://mynomadia.com/privatedoc/9LLcWh7j74sENa54/optitime-doc/docs/en/otgs-reference-book/call-center-objets.html#contrainte-chainage)
      - [Types of liaison (chaining constraints)](https://mynomadia.com/privatedoc/9LLcWh7j74sENa54/optitime-doc/docs/en/otgs-reference-book/call-center-objets.html#Type-liaison)
      - [Linking two appointments in the interface](https://mynomadia.com/privatedoc/9LLcWh7j74sENa54/optitime-doc/docs/en/otgs-reference-book/call-center-objets.html#liaison-GUI)
    - [Unavailabilities](https://mynomadia.com/privatedoc/9LLcWh7j74sENa54/optitime-doc/docs/en/otgs-reference-book/call-center-objets.html#centre-d-appel-indisponibilite)
      - [Unavailability form](https://mynomadia.com/privatedoc/9LLcWh7j74sENa54/optitime-doc/docs/en/otgs-reference-book/call-center-objets.html#fiche-indispo)
      - [Repeated unavailability form](https://mynomadia.com/privatedoc/9LLcWh7j74sENa54/optitime-doc/docs/en/otgs-reference-book/call-center-objets.html#fiche-reduite-indispo)
    - [Exceptional locations](https://mynomadia.com/privatedoc/9LLcWh7j74sENa54/optitime-doc/docs/en/otgs-reference-book/call-center-objets.html#localisations-exceptionnelles)
      - [Exceptional location form](https://mynomadia.com/privatedoc/9LLcWh7j74sENa54/optitime-doc/docs/en/otgs-reference-book/call-center-objets.html#fiche-loc-exceptionnelle)
    - [Temporary posts](https://mynomadia.com/privatedoc/9LLcWh7j74sENa54/optitime-doc/docs/en/otgs-reference-book/call-center-objets.html#objets-postes-temp)
      - [Temporary post form](https://mynomadia.com/privatedoc/9LLcWh7j74sENa54/optitime-doc/docs/en/otgs-reference-book/call-center-objets.html#fiche-poste-temporaire)
    - [Secondary worksites](https://mynomadia.com/privatedoc/9LLcWh7j74sENa54/optitime-doc/docs/en/otgs-reference-book/call-center-objets.html#objets-sites-second)
      - [Secondary worksite form](https://mynomadia.com/privatedoc/9LLcWh7j74sENa54/optitime-doc/docs/en/otgs-reference-book/call-center-objets.html#fiche-site-second)
    - [Hotel locations](https://mynomadia.com/privatedoc/9LLcWh7j74sENa54/optitime-doc/docs/en/otgs-reference-book/call-center-objets.html#objets-hotel)
      - [Hotel location form](https://mynomadia.com/privatedoc/9LLcWh7j74sENa54/optitime-doc/docs/en/otgs-reference-book/call-center-objets.html#fiche-hotel)
    - [Agenda markers](https://mynomadia.com/privatedoc/9LLcWh7j74sENa54/optitime-doc/docs/en/otgs-reference-book/call-center-objets.html#objets-jalons)
      - [Agenda marker form](https://mynomadia.com/privatedoc/9LLcWh7j74sENa54/optitime-doc/docs/en/otgs-reference-book/call-center-objets.html#fiche-jalon)
    - [On-call duty](https://mynomadia.com/privatedoc/9LLcWh7j74sENa54/optitime-doc/docs/en/otgs-reference-book/call-center-objets.html#objets-astreinte)
      - [On-call duty form](https://mynomadia.com/privatedoc/9LLcWh7j74sENa54/optitime-doc/docs/en/otgs-reference-book/call-center-objets.html#fiche-astreinte)
    - [Locked days in the agenda](https://mynomadia.com/privatedoc/9LLcWh7j74sENa54/optitime-doc/docs/en/otgs-reference-book/call-center-objets.html#objets-journees-verr)
      - [Locked day in the agenda](https://mynomadia.com/privatedoc/9LLcWh7j74sENa54/optitime-doc/docs/en/otgs-reference-book/call-center-objets.html#fiche-journee-verrouillee)
    - [Search in the Planning module](https://mynomadia.com/privatedoc/9LLcWh7j74sENa54/optitime-doc/docs/en/otgs-reference-book/call-center-objets.html#call-center-recherche)
      - [Search filters](https://mynomadia.com/privatedoc/9LLcWh7j74sENa54/optitime-doc/docs/en/otgs-reference-book/call-center-objets.html#recherche-generique-filtre)
      - [Search result](https://mynomadia.com/privatedoc/9LLcWh7j74sENa54/optitime-doc/docs/en/otgs-reference-book/call-center-objets.html#call-center-resultat)
    - [Create an object in the Planning module](https://mynomadia.com/privatedoc/9LLcWh7j74sENa54/optitime-doc/docs/en/otgs-reference-book/call-center-objets.html#call-center-creer)
    - [Delete an object in the Planning module](https://mynomadia.com/privatedoc/9LLcWh7j74sENa54/optitime-doc/docs/en/otgs-reference-book/call-center-objets.html#call-center-supprimer)
  - [The header bar](https://mynomadia.com/privatedoc/9LLcWh7j74sENa54/optitime-doc/docs/en/otgs-reference-book/_the_header_bar.html)
    - [Favourites for the area](https://mynomadia.com/privatedoc/9LLcWh7j74sENa54/optitime-doc/docs/en/otgs-reference-book/_the_header_bar.html#_favourites_for_the_area)
    - [Recent appointments](https://mynomadia.com/privatedoc/9LLcWh7j74sENa54/optitime-doc/docs/en/otgs-reference-book/_the_header_bar.html#_recent_appointments)
    - [List of urgent appointments](https://mynomadia.com/privatedoc/9LLcWh7j74sENa54/optitime-doc/docs/en/otgs-reference-book/_the_header_bar.html#liste-rdv-urgent)
    - [List of customers on alert](https://mynomadia.com/privatedoc/9LLcWh7j74sENa54/optitime-doc/docs/en/otgs-reference-book/_the_header_bar.html#liste-clients-urgent)
    - [Unread messages](https://mynomadia.com/privatedoc/9LLcWh7j74sENa54/optitime-doc/docs/en/otgs-reference-book/_the_header_bar.html#_unread_messages)
  - [Map](https://mynomadia.com/privatedoc/9LLcWh7j74sENa54/optitime-doc/docs/en/otgs-reference-book/call-center-carte.html)
    - [Navigation](https://mynomadia.com/privatedoc/9LLcWh7j74sENa54/optitime-doc/docs/en/otgs-reference-book/call-center-carte.html#_navigation)
    - [Display](https://mynomadia.com/privatedoc/9LLcWh7j74sENa54/optitime-doc/docs/en/otgs-reference-book/call-center-carte.html#_display)
  - [The information pane](https://mynomadia.com/privatedoc/9LLcWh7j74sENa54/optitime-doc/docs/en/otgs-reference-book/call-center-cadre-info.html)
    - [Replanning appointments](https://mynomadia.com/privatedoc/9LLcWh7j74sENa54/optitime-doc/docs/en/otgs-reference-book/call-center-cadre-info.html#replanifier)
    - [Appointment counters](https://mynomadia.com/privatedoc/9LLcWh7j74sENa54/optitime-doc/docs/en/otgs-reference-book/call-center-cadre-info.html#compteurs-rdv)
  - [Menu](https://mynomadia.com/privatedoc/9LLcWh7j74sENa54/optitime-doc/docs/en/otgs-reference-book/call-center-menu.html)
    - [Change area](https://mynomadia.com/privatedoc/9LLcWh7j74sENa54/optitime-doc/docs/en/otgs-reference-book/call-center-menu.html#changer-region)
    - [Making a new appointment](https://mynomadia.com/privatedoc/9LLcWh7j74sENa54/optitime-doc/docs/en/otgs-reference-book/call-center-menu.html#prendre-nouveau-rdv)
    - [Customers](https://mynomadia.com/privatedoc/9LLcWh7j74sENa54/optitime-doc/docs/en/otgs-reference-book/call-center-menu.html#menu-clients)
      - [Customer search](https://mynomadia.com/privatedoc/9LLcWh7j74sENa54/optitime-doc/docs/en/otgs-reference-book/call-center-menu.html#menu-clients-rechercher)
      - [Searching for the company orderer](https://mynomadia.com/privatedoc/9LLcWh7j74sENa54/optitime-doc/docs/en/otgs-reference-book/call-center-menu.html#rechercher-commanditaire)
      - [Search on a customer type](https://mynomadia.com/privatedoc/9LLcWh7j74sENa54/optitime-doc/docs/en/otgs-reference-book/call-center-menu.html#rechercher-type-client)
      - [Search on customer kind](https://mynomadia.com/privatedoc/9LLcWh7j74sENa54/optitime-doc/docs/en/otgs-reference-book/call-center-menu.html#rechercher-nature-client)
      - [Create customer](https://mynomadia.com/privatedoc/9LLcWh7j74sENa54/optitime-doc/docs/en/otgs-reference-book/call-center-menu.html#menu-clients-creation)
      - [Customers panel](https://mynomadia.com/privatedoc/9LLcWh7j74sENa54/optitime-doc/docs/en/otgs-reference-book/call-center-menu.html#panier-des-clients)
      - [Making appointments for several customers](https://mynomadia.com/privatedoc/9LLcWh7j74sENa54/optitime-doc/docs/en/otgs-reference-book/call-center-menu.html#prise-rdv-clients-multiple)
      - [List of customers on alert](https://mynomadia.com/privatedoc/9LLcWh7j74sENa54/optitime-doc/docs/en/otgs-reference-book/call-center-menu.html#liste-clients-alerte)
      - [Generate periodic requests](https://mynomadia.com/privatedoc/9LLcWh7j74sENa54/optitime-doc/docs/en/otgs-reference-book/call-center-menu.html#generer-clients-recurr)
    - [Managing resources](https://mynomadia.com/privatedoc/9LLcWh7j74sENa54/optitime-doc/docs/en/otgs-reference-book/call-center-menu.html#gestion-intervenants)
      - [Handling of temporary posts](https://mynomadia.com/privatedoc/9LLcWh7j74sENa54/optitime-doc/docs/en/otgs-reference-book/call-center-menu.html#gestion-postes-temp)
      - [Assignment of secondary worksites](https://mynomadia.com/privatedoc/9LLcWh7j74sENa54/optitime-doc/docs/en/otgs-reference-book/call-center-menu.html#affectation-sites-second)
      - [View customers](https://mynomadia.com/privatedoc/9LLcWh7j74sENa54/optitime-doc/docs/en/otgs-reference-book/call-center-menu.html#visualiser-clients)
      - [On-call duty management](https://mynomadia.com/privatedoc/9LLcWh7j74sENa54/optitime-doc/docs/en/otgs-reference-book/call-center-menu.html#gestion-astreintes)
      - [Equipment assignments](https://mynomadia.com/privatedoc/9LLcWh7j74sENa54/optitime-doc/docs/en/otgs-reference-book/call-center-menu.html#affectation-materiel)
    - [Sector management](https://mynomadia.com/privatedoc/9LLcWh7j74sENa54/optitime-doc/docs/en/otgs-reference-book/call-center-menu.html#gestion-secteurs)
    - [Searching for an appointment](https://mynomadia.com/privatedoc/9LLcWh7j74sENa54/optitime-doc/docs/en/otgs-reference-book/call-center-menu.html#rechercher-rdv)
    - [List selected appointments](https://mynomadia.com/privatedoc/9LLcWh7j74sENa54/optitime-doc/docs/en/otgs-reference-book/call-center-menu.html#lister-rdv-select)
    - [Search for appointments (requested, planned, reserved, confirmed, unplanned, subcontracted)](https://mynomadia.com/privatedoc/9LLcWh7j74sENa54/optitime-doc/docs/en/otgs-reference-book/call-center-menu.html#chercher-rdv-etats)
    - [My searches](https://mynomadia.com/privatedoc/9LLcWh7j74sENa54/optitime-doc/docs/en/otgs-reference-book/call-center-menu.html#mysearch)
    - [Links between interventions](https://mynomadia.com/privatedoc/9LLcWh7j74sENa54/optitime-doc/docs/en/otgs-reference-book/call-center-menu.html#liaison-intervention)
    - [Appointment alerts](https://mynomadia.com/privatedoc/9LLcWh7j74sENa54/optitime-doc/docs/en/otgs-reference-book/call-center-menu.html#alertes-rdv)
    - [Customer gap](https://mynomadia.com/privatedoc/9LLcWh7j74sENa54/optitime-doc/docs/en/otgs-reference-book/call-center-menu.html#ecart-client)
    - [Alerts on route duration](https://mynomadia.com/privatedoc/9LLcWh7j74sENa54/optitime-doc/docs/en/otgs-reference-book/call-center-menu.html#alertes-duree-trajet)
    - [Application warning messages](https://mynomadia.com/privatedoc/9LLcWh7j74sENa54/optitime-doc/docs/en/otgs-reference-book/call-center-menu.html#alertes)
    - [Messaging service](https://mynomadia.com/privatedoc/9LLcWh7j74sENa54/optitime-doc/docs/en/otgs-reference-book/call-center-menu.html#messages)
    - [Modify the appointments of the past](https://mynomadia.com/privatedoc/9LLcWh7j74sENa54/optitime-doc/docs/en/otgs-reference-book/call-center-menu.html#modifier-rdv-passe)
      - [Modify the current status of past plannings](https://mynomadia.com/privatedoc/9LLcWh7j74sENa54/optitime-doc/docs/en/otgs-reference-book/call-center-menu.html#_modify_the_current_status_of_past_plannings)
      - [Adding an appointment to a past planning](https://mynomadia.com/privatedoc/9LLcWh7j74sENa54/optitime-doc/docs/en/otgs-reference-book/call-center-menu.html#_adding_an_appointment_to_a_past_planning)
    - [Display agendas](https://mynomadia.com/privatedoc/9LLcWh7j74sENa54/optitime-doc/docs/en/otgs-reference-book/call-center-menu.html#afficher-agendas)
    - [Handling unavailabilities](https://mynomadia.com/privatedoc/9LLcWh7j74sENa54/optitime-doc/docs/en/otgs-reference-book/call-center-menu.html#gerer-indispos)
    - [Unavailability search](https://mynomadia.com/privatedoc/9LLcWh7j74sENa54/optitime-doc/docs/en/otgs-reference-book/call-center-menu.html#rechercher-indispo)
    - [Editing the roadbook](https://mynomadia.com/privatedoc/9LLcWh7j74sENa54/optitime-doc/docs/en/otgs-reference-book/call-center-menu.html#feuille-de-route)
    - [Exceptional locations](https://mynomadia.com/privatedoc/9LLcWh7j74sENa54/optitime-doc/docs/en/otgs-reference-book/call-center-menu.html#rechercher-loc-exceptionnelles)
    - [Hotel locations](https://mynomadia.com/privatedoc/9LLcWh7j74sENa54/optitime-doc/docs/en/otgs-reference-book/call-center-menu.html#emplacement-hotel)
    - [Locked day](https://mynomadia.com/privatedoc/9LLcWh7j74sENa54/optitime-doc/docs/en/otgs-reference-book/call-center-menu.html#journee-verrouilee)
    - [Manage agenda markers](https://mynomadia.com/privatedoc/9LLcWh7j74sENa54/optitime-doc/docs/en/otgs-reference-book/call-center-menu.html#gerer-jalons)
    - [Vehicles tracking](https://mynomadia.com/privatedoc/9LLcWh7j74sENa54/optitime-doc/docs/en/otgs-reference-book/call-center-menu.html#suivi-vehicule)
    - [Compute a route](https://mynomadia.com/privatedoc/9LLcWh7j74sENa54/optitime-doc/docs/en/otgs-reference-book/call-center-menu.html#calc-iti)
    - [Convert coordinates into Lat/Lon](https://mynomadia.com/privatedoc/9LLcWh7j74sENa54/optitime-doc/docs/en/otgs-reference-book/call-center-menu.html#convertir-lat-lon)
    - [Search around](https://mynomadia.com/privatedoc/9LLcWh7j74sENa54/optitime-doc/docs/en/otgs-reference-book/call-center-menu.html#rechercher-environs)
    - [Verify circulation for the planning](https://mynomadia.com/privatedoc/9LLcWh7j74sENa54/optitime-doc/docs/en/otgs-reference-book/call-center-menu.html#circulation-planning)
    - [Predefined exports list](https://mynomadia.com/privatedoc/9LLcWh7j74sENa54/optitime-doc/docs/en/otgs-reference-book/call-center-menu.html#liste-exports-predef)
    - [Custom reports](https://mynomadia.com/privatedoc/9LLcWh7j74sENa54/optitime-doc/docs/en/otgs-reference-book/call-center-menu.html#liste-rapports-predef)
  - [The planning](https://mynomadia.com/privatedoc/9LLcWh7j74sENa54/optitime-doc/docs/en/otgs-reference-book/call-center-agenda.html)
    - [Planning views](https://mynomadia.com/privatedoc/9LLcWh7j74sENa54/optitime-doc/docs/en/otgs-reference-book/call-center-agenda.html#selection-vues)
      - [Agenda kind](https://mynomadia.com/privatedoc/9LLcWh7j74sENa54/optitime-doc/docs/en/otgs-reference-book/call-center-agenda.html#_agenda_kind)
      - [Period](https://mynomadia.com/privatedoc/9LLcWh7j74sENa54/optitime-doc/docs/en/otgs-reference-book/call-center-agenda.html#_period)
      - [Hierarchical level](https://mynomadia.com/privatedoc/9LLcWh7j74sENa54/optitime-doc/docs/en/otgs-reference-book/call-center-agenda.html#_hierarchical_level)
      - [Route info](https://mynomadia.com/privatedoc/9LLcWh7j74sENa54/optitime-doc/docs/en/otgs-reference-book/call-center-agenda.html#info-bulle-tournee)
    - [Navigation bar](https://mynomadia.com/privatedoc/9LLcWh7j74sENa54/optitime-doc/docs/en/otgs-reference-book/call-center-agenda.html#planning-navigation)
      - [The panel](https://mynomadia.com/privatedoc/9LLcWh7j74sENa54/optitime-doc/docs/en/otgs-reference-book/call-center-agenda.html#manipuler-une-intervention-a-partir-du-panier)
      - [Navigating from one date to another](https://mynomadia.com/privatedoc/9LLcWh7j74sENa54/optitime-doc/docs/en/otgs-reference-book/call-center-agenda.html#agenda-navig)
      - [Previous or next agenda](https://mynomadia.com/privatedoc/9LLcWh7j74sENa54/optitime-doc/docs/en/otgs-reference-book/call-center-agenda.html#agenda-navig-recent)
      - [Switching the agenda](https://mynomadia.com/privatedoc/9LLcWh7j74sENa54/optitime-doc/docs/en/otgs-reference-book/call-center-agenda.html#agenda-bascule)
      - [Display the location of the resource in the map](https://mynomadia.com/privatedoc/9LLcWh7j74sENa54/optitime-doc/docs/en/otgs-reference-book/call-center-agenda.html#agenda-suivi)
      - [Display on the map](https://mynomadia.com/privatedoc/9LLcWh7j74sENa54/optitime-doc/docs/en/otgs-reference-book/call-center-agenda.html#agenda-tournees)
      - [Display the legend](https://mynomadia.com/privatedoc/9LLcWh7j74sENa54/optitime-doc/docs/en/otgs-reference-book/call-center-agenda.html#agenda-legende)
      - [Map pin](https://mynomadia.com/privatedoc/9LLcWh7j74sENa54/optitime-doc/docs/en/otgs-reference-book/call-center-agenda.html#agenda-punaise)
    - [The agenda](https://mynomadia.com/privatedoc/9LLcWh7j74sENa54/optitime-doc/docs/en/otgs-reference-book/call-center-agenda.html#call-center-agenda-rdv)
      - [Reoptimising the day](https://mynomadia.com/privatedoc/9LLcWh7j74sENa54/optitime-doc/docs/en/otgs-reference-book/call-center-agenda.html#reoptim)
      - [Move / extend objects](https://mynomadia.com/privatedoc/9LLcWh7j74sENa54/optitime-doc/docs/en/otgs-reference-book/call-center-agenda.html#deplacer-etirer)
      - [Managing appointments in the agenda](https://mynomadia.com/privatedoc/9LLcWh7j74sENa54/optitime-doc/docs/en/otgs-reference-book/call-center-agenda.html#tool-tip-rdv)
      - [Manage unavailabilities in the agenda](https://mynomadia.com/privatedoc/9LLcWh7j74sENa54/optitime-doc/docs/en/otgs-reference-book/call-center-agenda.html#tool-tip-indispo)
      - [Manage non-worked hours in the agenda](https://mynomadia.com/privatedoc/9LLcWh7j74sENa54/optitime-doc/docs/en/otgs-reference-book/call-center-agenda.html#tool-tip-horaire)
      - [Manage exceptional locations in the agenda](https://mynomadia.com/privatedoc/9LLcWh7j74sENa54/optitime-doc/docs/en/otgs-reference-book/call-center-agenda.html#tool-tip-loc-except)
      - [Managing locked agendas](https://mynomadia.com/privatedoc/9LLcWh7j74sENa54/optitime-doc/docs/en/otgs-reference-book/call-center-agenda.html#tool-tip-verr)
      - [Handling temporary posts in the agenda](https://mynomadia.com/privatedoc/9LLcWh7j74sENa54/optitime-doc/docs/en/otgs-reference-book/call-center-agenda.html#tool-tip-postes)
      - [Fill an empty agenda](https://mynomadia.com/privatedoc/9LLcWh7j74sENa54/optitime-doc/docs/en/otgs-reference-book/call-center-agenda.html#tool-tip-planning-vide)
      - [Journey time infobox](https://mynomadia.com/privatedoc/9LLcWh7j74sENa54/optitime-doc/docs/en/otgs-reference-book/call-center-agenda.html#tool-tip-trajet)
      - [The lunch break infobox](https://mynomadia.com/privatedoc/9LLcWh7j74sENa54/optitime-doc/docs/en/otgs-reference-book/call-center-agenda.html#tool-tip-pause-dej)
- [Supervisor](https://mynomadia.com/privatedoc/9LLcWh7j74sENa54/optitime-doc/docs/en/otgs-reference-book/module-supervision.html)
  - [Home page](https://mynomadia.com/privatedoc/9LLcWh7j74sENa54/optitime-doc/docs/en/otgs-reference-book/supervision-accueil.html)
    - [Menu](https://mynomadia.com/privatedoc/9LLcWh7j74sENa54/optitime-doc/docs/en/otgs-reference-book/supervision-accueil.html#_menu)
    - [Table](https://mynomadia.com/privatedoc/9LLcWh7j74sENa54/optitime-doc/docs/en/otgs-reference-book/supervision-accueil.html#_table)
  - [Journal](https://mynomadia.com/privatedoc/9LLcWh7j74sENa54/optitime-doc/docs/en/otgs-reference-book/journal.html)
    - [Journal home page](https://mynomadia.com/privatedoc/9LLcWh7j74sENa54/optitime-doc/docs/en/otgs-reference-book/journal.html#_journal_home_page)
      - [Choice of company data type](https://mynomadia.com/privatedoc/9LLcWh7j74sENa54/optitime-doc/docs/en/otgs-reference-book/journal.html#_choice_of_company_data_type)
      - [Human resource](https://mynomadia.com/privatedoc/9LLcWh7j74sENa54/optitime-doc/docs/en/otgs-reference-book/journal.html#_human_resource)
      - [Enter a customer](https://mynomadia.com/privatedoc/9LLcWh7j74sENa54/optitime-doc/docs/en/otgs-reference-book/journal.html#_enter_a_customer)
      - [Enter an identifier](https://mynomadia.com/privatedoc/9LLcWh7j74sENa54/optitime-doc/docs/en/otgs-reference-book/journal.html#_enter_an_identifier)
      - [Choice of the period](https://mynomadia.com/privatedoc/9LLcWh7j74sENa54/optitime-doc/docs/en/otgs-reference-book/journal.html#_choice_of_the_period)
      - [Validation](https://mynomadia.com/privatedoc/9LLcWh7j74sENa54/optitime-doc/docs/en/otgs-reference-book/journal.html#_validation)
    - [Result of the search](https://mynomadia.com/privatedoc/9LLcWh7j74sENa54/optitime-doc/docs/en/otgs-reference-book/journal.html#journal-resultat)
    - [Visualisation of the action](https://mynomadia.com/privatedoc/9LLcWh7j74sENa54/optitime-doc/docs/en/otgs-reference-book/journal.html#_visualisation_of_the_action)
  - [Control panel](https://mynomadia.com/privatedoc/9LLcWh7j74sENa54/optitime-doc/docs/en/otgs-reference-book/TDB.html)
    - [Role](https://mynomadia.com/privatedoc/9LLcWh7j74sENa54/optitime-doc/docs/en/otgs-reference-book/TDB.html#_role)
    - [Basic principles](https://mynomadia.com/privatedoc/9LLcWh7j74sENa54/optitime-doc/docs/en/otgs-reference-book/TDB.html#_basic_principles)
    - [Application](https://mynomadia.com/privatedoc/9LLcWh7j74sENa54/optitime-doc/docs/en/otgs-reference-book/TDB.html#_application)
  - [Control panel - Configure](https://mynomadia.com/privatedoc/9LLcWh7j74sENa54/optitime-doc/docs/en/otgs-reference-book/config.html)
    - [Role](https://mynomadia.com/privatedoc/9LLcWh7j74sENa54/optitime-doc/docs/en/otgs-reference-book/config.html#_role_2)
    - [Application](https://mynomadia.com/privatedoc/9LLcWh7j74sENa54/optitime-doc/docs/en/otgs-reference-book/config.html#_application_2)
      - [Human resources](https://mynomadia.com/privatedoc/9LLcWh7j74sENa54/optitime-doc/docs/en/otgs-reference-book/config.html#_human_resources)
      - [Period](https://mynomadia.com/privatedoc/9LLcWh7j74sENa54/optitime-doc/docs/en/otgs-reference-book/config.html#_period_2)
      - [Activities | Intervention type (optional)](https://mynomadia.com/privatedoc/9LLcWh7j74sENa54/optitime-doc/docs/en/otgs-reference-book/config.html#_activities_intervention_type_optional)
      - [Activities | Unavailability (optional)](https://mynomadia.com/privatedoc/9LLcWh7j74sENa54/optitime-doc/docs/en/otgs-reference-book/config.html#_activities_unavailability_optional)
      - [Other](https://mynomadia.com/privatedoc/9LLcWh7j74sENa54/optitime-doc/docs/en/otgs-reference-book/config.html#_other)
  - [control panel - Interventions](https://mynomadia.com/privatedoc/9LLcWh7j74sENa54/optitime-doc/docs/en/otgs-reference-book/intervention.html)
    - [Role](https://mynomadia.com/privatedoc/9LLcWh7j74sENa54/optitime-doc/docs/en/otgs-reference-book/intervention.html#_role_3)
    - [Application](https://mynomadia.com/privatedoc/9LLcWh7j74sENa54/optitime-doc/docs/en/otgs-reference-book/intervention.html#_application_3)
  - [Control panel - Scheduling summary by day](https://mynomadia.com/privatedoc/9LLcWh7j74sENa54/optitime-doc/docs/en/otgs-reference-book/resume-jour.html)
    - [Role](https://mynomadia.com/privatedoc/9LLcWh7j74sENa54/optitime-doc/docs/en/otgs-reference-book/resume-jour.html#_role_4)
    - [Application](https://mynomadia.com/privatedoc/9LLcWh7j74sENa54/optitime-doc/docs/en/otgs-reference-book/resume-jour.html#_application_4)
  - [Control panel - Scheduling summary by week](https://mynomadia.com/privatedoc/9LLcWh7j74sENa54/optitime-doc/docs/en/otgs-reference-book/resume-semaine.html)
    - [Role](https://mynomadia.com/privatedoc/9LLcWh7j74sENa54/optitime-doc/docs/en/otgs-reference-book/resume-semaine.html#_role_5)
    - [Application](https://mynomadia.com/privatedoc/9LLcWh7j74sENa54/optitime-doc/docs/en/otgs-reference-book/resume-semaine.html#_application_5)
  - [Control panel - Availabilities](https://mynomadia.com/privatedoc/9LLcWh7j74sENa54/optitime-doc/docs/en/otgs-reference-book/dispo.html)
    - [Role](https://mynomadia.com/privatedoc/9LLcWh7j74sENa54/optitime-doc/docs/en/otgs-reference-book/dispo.html#_role_6)
    - [Application](https://mynomadia.com/privatedoc/9LLcWh7j74sENa54/optitime-doc/docs/en/otgs-reference-book/dispo.html#_application_6)
  - [Control panel - Appointment taking quantity](https://mynomadia.com/privatedoc/9LLcWh7j74sENa54/optitime-doc/docs/en/otgs-reference-book/rdv-quantite.html)
    - [Role](https://mynomadia.com/privatedoc/9LLcWh7j74sENa54/optitime-doc/docs/en/otgs-reference-book/rdv-quantite.html#_role_7)
    - [Application](https://mynomadia.com/privatedoc/9LLcWh7j74sENa54/optitime-doc/docs/en/otgs-reference-book/rdv-quantite.html#_application_7)
  - [Control panel - Appointment taking quality](https://mynomadia.com/privatedoc/9LLcWh7j74sENa54/optitime-doc/docs/en/otgs-reference-book/rdv-qualite.html)
    - [Role](https://mynomadia.com/privatedoc/9LLcWh7j74sENa54/optitime-doc/docs/en/otgs-reference-book/rdv-qualite.html#_role_8)
    - [Application](https://mynomadia.com/privatedoc/9LLcWh7j74sENa54/optitime-doc/docs/en/otgs-reference-book/rdv-qualite.html#_application_8)
  - [Control panel - Targets](https://mynomadia.com/privatedoc/9LLcWh7j74sENa54/optitime-doc/docs/en/otgs-reference-book/objectif.html)
    - [Role](https://mynomadia.com/privatedoc/9LLcWh7j74sENa54/optitime-doc/docs/en/otgs-reference-book/objectif.html#_role_9)
    - [Application](https://mynomadia.com/privatedoc/9LLcWh7j74sENa54/optitime-doc/docs/en/otgs-reference-book/objectif.html#_application_9)
  - [Analyses - Customer distance matrix](https://mynomadia.com/privatedoc/9LLcWh7j74sENa54/optitime-doc/docs/en/otgs-reference-book/distancier.html)
    - [Role](https://mynomadia.com/privatedoc/9LLcWh7j74sENa54/optitime-doc/docs/en/otgs-reference-book/distancier.html#_role_10)
    - [Application](https://mynomadia.com/privatedoc/9LLcWh7j74sENa54/optitime-doc/docs/en/otgs-reference-book/distancier.html#_application_10)
  - [Analyses - Customer centre of gravity matrix](https://mynomadia.com/privatedoc/9LLcWh7j74sENa54/optitime-doc/docs/en/otgs-reference-book/centre-gravite.html)
    - [Role](https://mynomadia.com/privatedoc/9LLcWh7j74sENa54/optitime-doc/docs/en/otgs-reference-book/centre-gravite.html#_role_11)
    - [Application](https://mynomadia.com/privatedoc/9LLcWh7j74sENa54/optitime-doc/docs/en/otgs-reference-book/centre-gravite.html#_application_11)
  - [Analyses- Unavailabilities global planning](https://mynomadia.com/privatedoc/9LLcWh7j74sENa54/optitime-doc/docs/en/otgs-reference-book/planing-glob-indispo.html)
    - [Role](https://mynomadia.com/privatedoc/9LLcWh7j74sENa54/optitime-doc/docs/en/otgs-reference-book/planing-glob-indispo.html#_role_12)
    - [Application](https://mynomadia.com/privatedoc/9LLcWh7j74sENa54/optitime-doc/docs/en/otgs-reference-book/planing-glob-indispo.html#_application_12)
  - [Analyses - Scheduling compliance](https://mynomadia.com/privatedoc/9LLcWh7j74sENa54/optitime-doc/docs/en/otgs-reference-book/conformite.html)
    - [Role](https://mynomadia.com/privatedoc/9LLcWh7j74sENa54/optitime-doc/docs/en/otgs-reference-book/conformite.html#_role_13)
    - [Application](https://mynomadia.com/privatedoc/9LLcWh7j74sENa54/optitime-doc/docs/en/otgs-reference-book/conformite.html#_application_13)
  - [Analyses - Overtimes](https://mynomadia.com/privatedoc/9LLcWh7j74sENa54/optitime-doc/docs/en/otgs-reference-book/heures-sup.html)
    - [Role](https://mynomadia.com/privatedoc/9LLcWh7j74sENa54/optitime-doc/docs/en/otgs-reference-book/heures-sup.html#_role_14)
    - [Application](https://mynomadia.com/privatedoc/9LLcWh7j74sENa54/optitime-doc/docs/en/otgs-reference-book/heures-sup.html#_application_14)
- [Attendance](https://mynomadia.com/privatedoc/9LLcWh7j74sENa54/optitime-doc/docs/en/otgs-reference-book/module-dispo.html)
  - [Home page](https://mynomadia.com/privatedoc/9LLcWh7j74sENa54/optitime-doc/docs/en/otgs-reference-book/_home_page_2.html)
  - [Modifying a planning manually](https://mynomadia.com/privatedoc/9LLcWh7j74sENa54/optitime-doc/docs/en/otgs-reference-book/_modifying_a_planning_manually.html)
    - [Add](https://mynomadia.com/privatedoc/9LLcWh7j74sENa54/optitime-doc/docs/en/otgs-reference-book/_modifying_a_planning_manually.html#_add)
    - [Deletion](https://mynomadia.com/privatedoc/9LLcWh7j74sENa54/optitime-doc/docs/en/otgs-reference-book/_modifying_a_planning_manually.html#_deletion)
- [Strategic](https://mynomadia.com/privatedoc/9LLcWh7j74sENa54/optitime-doc/docs/en/otgs-reference-book/module-strategic.html)
  - [Creating a study](https://mynomadia.com/privatedoc/9LLcWh7j74sENa54/optitime-doc/docs/en/otgs-reference-book/new_simul.html)
  - [Study of a simulation](https://mynomadia.com/privatedoc/9LLcWh7j74sENa54/optitime-doc/docs/en/otgs-reference-book/_study_of_a_simulation.html)
- [Sectorization](https://mynomadia.com/privatedoc/9LLcWh7j74sENa54/optitime-doc/docs/en/otgs-reference-book/module-sectorisation.html)
- [Fulfilment](https://mynomadia.com/privatedoc/9LLcWh7j74sENa54/optitime-doc/docs/en/otgs-reference-book/module-fulfilment.html)
- [Tracking](https://mynomadia.com/privatedoc/9LLcWh7j74sENa54/optitime-doc/docs/en/otgs-reference-book/module-tracking.html)
- [Administration](https://mynomadia.com/privatedoc/9LLcWh7j74sENa54/optitime-doc/docs/en/otgs-reference-book/module-administration.html)
  - [Home page](https://mynomadia.com/privatedoc/9LLcWh7j74sENa54/optitime-doc/docs/en/otgs-reference-book/_home_page_3.html)
  - [General principles](https://mynomadia.com/privatedoc/9LLcWh7j74sENa54/optitime-doc/docs/en/otgs-reference-book/generalites.html)
    - [Data home page](https://mynomadia.com/privatedoc/9LLcWh7j74sENa54/optitime-doc/docs/en/otgs-reference-book/generalites.html#generalite-liste)
    - [Data form](https://mynomadia.com/privatedoc/9LLcWh7j74sENa54/optitime-doc/docs/en/otgs-reference-book/generalites.html#generalite-fiche)
    - [Create a new data item](https://mynomadia.com/privatedoc/9LLcWh7j74sENa54/optitime-doc/docs/en/otgs-reference-book/generalites.html#creation)
    - [Consult or edit an existing data item](https://mynomadia.com/privatedoc/9LLcWh7j74sENa54/optitime-doc/docs/en/otgs-reference-book/generalites.html#modification)
    - [Adding data](https://mynomadia.com/privatedoc/9LLcWh7j74sENa54/optitime-doc/docs/en/otgs-reference-book/generalites.html#ajout)
    - [Duplicating a data item](https://mynomadia.com/privatedoc/9LLcWh7j74sENa54/optitime-doc/docs/en/otgs-reference-book/generalites.html#duplication)
    - [De-activating / Deleting a data item](https://mynomadia.com/privatedoc/9LLcWh7j74sENa54/optitime-doc/docs/en/otgs-reference-book/generalites.html#suppression)
    - [Navigation](https://mynomadia.com/privatedoc/9LLcWh7j74sENa54/optitime-doc/docs/en/otgs-reference-book/generalites.html#navigation)
  - [Company data](https://mynomadia.com/privatedoc/9LLcWh7j74sENa54/optitime-doc/docs/en/otgs-reference-book/donnees.html)
    - [Human resource](https://mynomadia.com/privatedoc/9LLcWh7j74sENa54/optitime-doc/docs/en/otgs-reference-book/donnees.html#RH)
      - [List of human resources](https://mynomadia.com/privatedoc/9LLcWh7j74sENa54/optitime-doc/docs/en/otgs-reference-book/donnees.html#_list_of_human_resources)
      - [Resource form](https://mynomadia.com/privatedoc/9LLcWh7j74sENa54/optitime-doc/docs/en/otgs-reference-book/donnees.html#fiche-ressource)
      - [Information tab](https://mynomadia.com/privatedoc/9LLcWh7j74sENa54/optitime-doc/docs/en/otgs-reference-book/donnees.html#RH-info)
      - [Assignment tab](https://mynomadia.com/privatedoc/9LLcWh7j74sENa54/optitime-doc/docs/en/otgs-reference-book/donnees.html#RH-affectation)
      - [Address tab](https://mynomadia.com/privatedoc/9LLcWh7j74sENa54/optitime-doc/docs/en/otgs-reference-book/donnees.html#RH-adresse)
      - [User tab](https://mynomadia.com/privatedoc/9LLcWh7j74sENa54/optitime-doc/docs/en/otgs-reference-book/donnees.html#RH-utilisateur)
      - [Perimeter tab](https://mynomadia.com/privatedoc/9LLcWh7j74sENa54/optitime-doc/docs/en/otgs-reference-book/donnees.html#RH-perimetre)
      - [Typical week tab](https://mynomadia.com/privatedoc/9LLcWh7j74sENa54/optitime-doc/docs/en/otgs-reference-book/donnees.html#RH-semaine)
      - [Limits tab](https://mynomadia.com/privatedoc/9LLcWh7j74sENa54/optitime-doc/docs/en/otgs-reference-book/donnees.html#RH-limite)
      - [Stop points tab](https://mynomadia.com/privatedoc/9LLcWh7j74sENa54/optitime-doc/docs/en/otgs-reference-book/donnees.html#RH-passage-depot)
      - [Skills tab](https://mynomadia.com/privatedoc/9LLcWh7j74sENa54/optitime-doc/docs/en/otgs-reference-book/donnees.html#RH-comp)
      - [Authorisations tab](https://mynomadia.com/privatedoc/9LLcWh7j74sENa54/optitime-doc/docs/en/otgs-reference-book/donnees.html#RH-autorisation)
      - [Priorities tab](https://mynomadia.com/privatedoc/9LLcWh7j74sENa54/optitime-doc/docs/en/otgs-reference-book/donnees.html#RH-priorite)
      - [Posts tab](https://mynomadia.com/privatedoc/9LLcWh7j74sENa54/optitime-doc/docs/en/otgs-reference-book/donnees.html#RH-poste)
      - [Vehicle tab](https://mynomadia.com/privatedoc/9LLcWh7j74sENa54/optitime-doc/docs/en/otgs-reference-book/donnees.html#RH-vehicule)
    - [Function](https://mynomadia.com/privatedoc/9LLcWh7j74sENa54/optitime-doc/docs/en/otgs-reference-book/donnees.html#type-expertise)
      - [List of functions](https://mynomadia.com/privatedoc/9LLcWh7j74sENa54/optitime-doc/docs/en/otgs-reference-book/donnees.html#_list_of_functions)
      - [Form for the function](https://mynomadia.com/privatedoc/9LLcWh7j74sENa54/optitime-doc/docs/en/otgs-reference-book/donnees.html#_form_for_the_function)
      - [Information tab](https://mynomadia.com/privatedoc/9LLcWh7j74sENa54/optitime-doc/docs/en/otgs-reference-book/donnees.html#_information_tab)
      - [Work week tab](https://mynomadia.com/privatedoc/9LLcWh7j74sENa54/optitime-doc/docs/en/otgs-reference-book/donnees.html#_work_week_tab)
      - [Limits tab](https://mynomadia.com/privatedoc/9LLcWh7j74sENa54/optitime-doc/docs/en/otgs-reference-book/donnees.html#_limits_tab)
      - [Priorities tab](https://mynomadia.com/privatedoc/9LLcWh7j74sENa54/optitime-doc/docs/en/otgs-reference-book/donnees.html#_priorities_tab)
    - [Job type](https://mynomadia.com/privatedoc/9LLcWh7j74sENa54/optitime-doc/docs/en/otgs-reference-book/donnees.html#type-poste)
      - [List of job types](https://mynomadia.com/privatedoc/9LLcWh7j74sENa54/optitime-doc/docs/en/otgs-reference-book/donnees.html#_list_of_job_types)
      - [Form for the job type](https://mynomadia.com/privatedoc/9LLcWh7j74sENa54/optitime-doc/docs/en/otgs-reference-book/donnees.html#_form_for_the_job_type)
      - [Information tab](https://mynomadia.com/privatedoc/9LLcWh7j74sENa54/optitime-doc/docs/en/otgs-reference-book/donnees.html#_information_tab_2)
      - [Work week tab](https://mynomadia.com/privatedoc/9LLcWh7j74sENa54/optitime-doc/docs/en/otgs-reference-book/donnees.html#_work_week_tab_2)
      - [Priorities tab](https://mynomadia.com/privatedoc/9LLcWh7j74sENa54/optitime-doc/docs/en/otgs-reference-book/donnees.html#_priorities_tab_2)
    - [Subcontractor](https://mynomadia.com/privatedoc/9LLcWh7j74sENa54/optitime-doc/docs/en/otgs-reference-book/donnees.html#sous-traitants)
      - [List of subcontractors](https://mynomadia.com/privatedoc/9LLcWh7j74sENa54/optitime-doc/docs/en/otgs-reference-book/donnees.html#_list_of_subcontractors)
      - [Form for the subcontractor](https://mynomadia.com/privatedoc/9LLcWh7j74sENa54/optitime-doc/docs/en/otgs-reference-book/donnees.html#_form_for_the_subcontractor)
    - [Equipment](https://mynomadia.com/privatedoc/9LLcWh7j74sENa54/optitime-doc/docs/en/otgs-reference-book/donnees.html#materiel)
      - [List of equipments](https://mynomadia.com/privatedoc/9LLcWh7j74sENa54/optitime-doc/docs/en/otgs-reference-book/donnees.html#_list_of_equipments)
      - [Form for the equipment](https://mynomadia.com/privatedoc/9LLcWh7j74sENa54/optitime-doc/docs/en/otgs-reference-book/donnees.html#_form_for_the_equipment)
    - [Product family](https://mynomadia.com/privatedoc/9LLcWh7j74sENa54/optitime-doc/docs/en/otgs-reference-book/donnees.html#famille-produit)
      - [List of product families](https://mynomadia.com/privatedoc/9LLcWh7j74sENa54/optitime-doc/docs/en/otgs-reference-book/donnees.html#_list_of_product_families)
      - [Form for the product family](https://mynomadia.com/privatedoc/9LLcWh7j74sENa54/optitime-doc/docs/en/otgs-reference-book/donnees.html#_form_for_the_product_family)
    - [Product (Product family)](https://mynomadia.com/privatedoc/9LLcWh7j74sENa54/optitime-doc/docs/en/otgs-reference-book/donnees.html#produit)
      - [List of products](https://mynomadia.com/privatedoc/9LLcWh7j74sENa54/optitime-doc/docs/en/otgs-reference-book/donnees.html#_list_of_products)
      - [Form for the product](https://mynomadia.com/privatedoc/9LLcWh7j74sENa54/optitime-doc/docs/en/otgs-reference-book/donnees.html#_form_for_the_product)
    - [Team](https://mynomadia.com/privatedoc/9LLcWh7j74sENa54/optitime-doc/docs/en/otgs-reference-book/donnees.html#equipe)
      - [List of teams](https://mynomadia.com/privatedoc/9LLcWh7j74sENa54/optitime-doc/docs/en/otgs-reference-book/donnees.html#_list_of_teams)
      - [Form for the team](https://mynomadia.com/privatedoc/9LLcWh7j74sENa54/optitime-doc/docs/en/otgs-reference-book/donnees.html#_form_for_the_team)
      - [Information tab](https://mynomadia.com/privatedoc/9LLcWh7j74sENa54/optitime-doc/docs/en/otgs-reference-book/donnees.html#_information_tab_3)
      - [Members tab](https://mynomadia.com/privatedoc/9LLcWh7j74sENa54/optitime-doc/docs/en/otgs-reference-book/donnees.html#_members_tab)
      - [Team leader tab](https://mynomadia.com/privatedoc/9LLcWh7j74sENa54/optitime-doc/docs/en/otgs-reference-book/donnees.html#equipe-chef)
      - [Parent team tab](https://mynomadia.com/privatedoc/9LLcWh7j74sENa54/optitime-doc/docs/en/otgs-reference-book/donnees.html#equipe-mere)
    - [Domain](https://mynomadia.com/privatedoc/9LLcWh7j74sENa54/optitime-doc/docs/en/otgs-reference-book/donnees.html#domaine)
      - [List of domains](https://mynomadia.com/privatedoc/9LLcWh7j74sENa54/optitime-doc/docs/en/otgs-reference-book/donnees.html#_list_of_domains)
      - [Domain form](https://mynomadia.com/privatedoc/9LLcWh7j74sENa54/optitime-doc/docs/en/otgs-reference-book/donnees.html#_domain_form)
    - [Area](https://mynomadia.com/privatedoc/9LLcWh7j74sENa54/optitime-doc/docs/en/otgs-reference-book/donnees.html#region)
      - [List of Areas](https://mynomadia.com/privatedoc/9LLcWh7j74sENa54/optitime-doc/docs/en/otgs-reference-book/donnees.html#_list_of_areas)
      - [Form for an Area](https://mynomadia.com/privatedoc/9LLcWh7j74sENa54/optitime-doc/docs/en/otgs-reference-book/donnees.html#_form_for_an_area)
      - [Information tab](https://mynomadia.com/privatedoc/9LLcWh7j74sENa54/optitime-doc/docs/en/otgs-reference-book/donnees.html#_information_tab_4)
      - [Teams tab](https://mynomadia.com/privatedoc/9LLcWh7j74sENa54/optitime-doc/docs/en/otgs-reference-book/donnees.html#_teams_tab)
      - [District tab](https://mynomadia.com/privatedoc/9LLcWh7j74sENa54/optitime-doc/docs/en/otgs-reference-book/donnees.html#_district_tab)
      - [Town tab](https://mynomadia.com/privatedoc/9LLcWh7j74sENa54/optitime-doc/docs/en/otgs-reference-book/donnees.html#_town_tab)
    - [Worksite](https://mynomadia.com/privatedoc/9LLcWh7j74sENa54/optitime-doc/docs/en/otgs-reference-book/donnees.html#site-travail)
      - [List of worksites](https://mynomadia.com/privatedoc/9LLcWh7j74sENa54/optitime-doc/docs/en/otgs-reference-book/donnees.html#_list_of_worksites)
      - [Worksite form](https://mynomadia.com/privatedoc/9LLcWh7j74sENa54/optitime-doc/docs/en/otgs-reference-book/donnees.html#_worksite_form)
    - [Sector (or Intervention sector)](https://mynomadia.com/privatedoc/9LLcWh7j74sENa54/optitime-doc/docs/en/otgs-reference-book/donnees.html#secteur)
      - [List of sectors](https://mynomadia.com/privatedoc/9LLcWh7j74sENa54/optitime-doc/docs/en/otgs-reference-book/donnees.html#_list_of_sectors)
      - [Form for a Sector](https://mynomadia.com/privatedoc/9LLcWh7j74sENa54/optitime-doc/docs/en/otgs-reference-book/donnees.html#_form_for_a_sector)
      - [Information tab](https://mynomadia.com/privatedoc/9LLcWh7j74sENa54/optitime-doc/docs/en/otgs-reference-book/donnees.html#_information_tab_5)
      - [Address tab](https://mynomadia.com/privatedoc/9LLcWh7j74sENa54/optitime-doc/docs/en/otgs-reference-book/donnees.html#_address_tab)
      - [Towns tab](https://mynomadia.com/privatedoc/9LLcWh7j74sENa54/optitime-doc/docs/en/otgs-reference-book/donnees.html#_towns_tab)
      - [Resources tab](https://mynomadia.com/privatedoc/9LLcWh7j74sENa54/optitime-doc/docs/en/otgs-reference-book/donnees.html#_resources_tab)
    - [Unavailability type](https://mynomadia.com/privatedoc/9LLcWh7j74sENa54/optitime-doc/docs/en/otgs-reference-book/donnees.html#type-indispo)
      - [List of unavailability types](https://mynomadia.com/privatedoc/9LLcWh7j74sENa54/optitime-doc/docs/en/otgs-reference-book/donnees.html#_list_of_unavailability_types)
      - [Unavailability type form](https://mynomadia.com/privatedoc/9LLcWh7j74sENa54/optitime-doc/docs/en/otgs-reference-book/donnees.html#_unavailability_type_form)
    - [Exceptional location type](https://mynomadia.com/privatedoc/9LLcWh7j74sENa54/optitime-doc/docs/en/otgs-reference-book/donnees.html#type-except-loc)
      - [List of exceptional location types](https://mynomadia.com/privatedoc/9LLcWh7j74sENa54/optitime-doc/docs/en/otgs-reference-book/donnees.html#_list_of_exceptional_location_types)
      - [Form for the exceptional location type](https://mynomadia.com/privatedoc/9LLcWh7j74sENa54/optitime-doc/docs/en/otgs-reference-book/donnees.html#_form_for_the_exceptional_location_type)
    - [On-call duties](https://mynomadia.com/privatedoc/9LLcWh7j74sENa54/optitime-doc/docs/en/otgs-reference-book/donnees.html#astreintes)
      - [On-call duty template](https://mynomadia.com/privatedoc/9LLcWh7j74sENa54/optitime-doc/docs/en/otgs-reference-book/donnees.html#modele-jour-astreinte)
      - [On-call duties, week template](https://mynomadia.com/privatedoc/9LLcWh7j74sENa54/optitime-doc/docs/en/otgs-reference-book/donnees.html#modele-semaine-astreinte)
    - [Skill](https://mynomadia.com/privatedoc/9LLcWh7j74sENa54/optitime-doc/docs/en/otgs-reference-book/donnees.html#competence)
      - [List of skills](https://mynomadia.com/privatedoc/9LLcWh7j74sENa54/optitime-doc/docs/en/otgs-reference-book/donnees.html#_list_of_skills)
      - [Skill form](https://mynomadia.com/privatedoc/9LLcWh7j74sENa54/optitime-doc/docs/en/otgs-reference-book/donnees.html#_skill_form)
    - [Authorisation](https://mynomadia.com/privatedoc/9LLcWh7j74sENa54/optitime-doc/docs/en/otgs-reference-book/donnees.html#autorisation)
      - [List of authorisations](https://mynomadia.com/privatedoc/9LLcWh7j74sENa54/optitime-doc/docs/en/otgs-reference-book/donnees.html#_list_of_authorisations)
      - [Authorisation form](https://mynomadia.com/privatedoc/9LLcWh7j74sENa54/optitime-doc/docs/en/otgs-reference-book/donnees.html#_authorisation_form)
    - [Interventions group](https://mynomadia.com/privatedoc/9LLcWh7j74sENa54/optitime-doc/docs/en/otgs-reference-book/donnees.html#groupe-intervention)
      - [List of intervention groups](https://mynomadia.com/privatedoc/9LLcWh7j74sENa54/optitime-doc/docs/en/otgs-reference-book/donnees.html#_list_of_intervention_groups)
      - [Interventions group form](https://mynomadia.com/privatedoc/9LLcWh7j74sENa54/optitime-doc/docs/en/otgs-reference-book/donnees.html#_interventions_group_form)
    - [Intervention type (Intervention group)](https://mynomadia.com/privatedoc/9LLcWh7j74sENa54/optitime-doc/docs/en/otgs-reference-book/donnees.html#type-intervention)
      - [List of intervention types](https://mynomadia.com/privatedoc/9LLcWh7j74sENa54/optitime-doc/docs/en/otgs-reference-book/donnees.html#_list_of_intervention_types)
      - [Intervention type form](https://mynomadia.com/privatedoc/9LLcWh7j74sENa54/optitime-doc/docs/en/otgs-reference-book/donnees.html#_intervention_type_form)
    - [Targets](https://mynomadia.com/privatedoc/9LLcWh7j74sENa54/optitime-doc/docs/en/otgs-reference-book/donnees.html#objectifs)
      - [List of targets](https://mynomadia.com/privatedoc/9LLcWh7j74sENa54/optitime-doc/docs/en/otgs-reference-book/donnees.html#_list_of_targets)
      - [Form for a target](https://mynomadia.com/privatedoc/9LLcWh7j74sENa54/optitime-doc/docs/en/otgs-reference-book/donnees.html#_form_for_a_target)
    - [Follow-up](https://mynomadia.com/privatedoc/9LLcWh7j74sENa54/optitime-doc/docs/en/otgs-reference-book/donnees.html#suivi-activite)
      - [Completion status](https://mynomadia.com/privatedoc/9LLcWh7j74sENa54/optitime-doc/docs/en/otgs-reference-book/donnees.html#etat-realisation)
      - [Follow-up](https://mynomadia.com/privatedoc/9LLcWh7j74sENa54/optitime-doc/docs/en/otgs-reference-book/donnees.html#suite)
    - [Typology](https://mynomadia.com/privatedoc/9LLcWh7j74sENa54/optitime-doc/docs/en/otgs-reference-book/donnees.html#typogoly)
    - [Calendars](https://mynomadia.com/privatedoc/9LLcWh7j74sENa54/optitime-doc/docs/en/otgs-reference-book/donnees.html#_calendars)
      - [Public holidays](https://mynomadia.com/privatedoc/9LLcWh7j74sENa54/optitime-doc/docs/en/otgs-reference-book/donnees.html#jour-ferie)
      - [Day template](https://mynomadia.com/privatedoc/9LLcWh7j74sENa54/optitime-doc/docs/en/otgs-reference-book/donnees.html#modele-jour)
      - [Week template](https://mynomadia.com/privatedoc/9LLcWh7j74sENa54/optitime-doc/docs/en/otgs-reference-book/donnees.html#modele-semaine)
      - [Sales period](https://mynomadia.com/privatedoc/9LLcWh7j74sENa54/optitime-doc/docs/en/otgs-reference-book/donnees.html#periode-vente)
  - [Optimisation](https://mynomadia.com/privatedoc/9LLcWh7j74sENa54/optitime-doc/docs/en/otgs-reference-book/optimisation.html)
    - [Optimisation parameters](https://mynomadia.com/privatedoc/9LLcWh7j74sENa54/optitime-doc/docs/en/otgs-reference-book/optimisation.html#param-optim)
      - [Management of optimization profiles](https://mynomadia.com/privatedoc/9LLcWh7j74sENa54/optitime-doc/docs/en/otgs-reference-book/optimisation.html#profil-optim)
      - [Description of optimization parameters](https://mynomadia.com/privatedoc/9LLcWh7j74sENa54/optitime-doc/docs/en/otgs-reference-book/optimisation.html#_description_of_optimization_parameters)
      - [Parameters that are common to both optimization modes](https://mynomadia.com/privatedoc/9LLcWh7j74sENa54/optitime-doc/docs/en/otgs-reference-book/optimisation.html#_parameters_that_are_common_to_both_optimization_modes)
      - [Parameters relating to a real time optimization](https://mynomadia.com/privatedoc/9LLcWh7j74sENa54/optitime-doc/docs/en/otgs-reference-book/optimisation.html#_parameters_relating_to_a_real_time_optimization)
      - [Parameters relating to batch optimization](https://mynomadia.com/privatedoc/9LLcWh7j74sENa54/optitime-doc/docs/en/otgs-reference-book/optimisation.html#param-batch)
    - [Optimisation planning](https://mynomadia.com/privatedoc/9LLcWh7j74sENa54/optitime-doc/docs/en/otgs-reference-book/optimisation.html#planif-optim)
      - [Service tab](https://mynomadia.com/privatedoc/9LLcWh7j74sENa54/optitime-doc/docs/en/otgs-reference-book/optimisation.html#optim-service)
      - [Optimisation tab](https://mynomadia.com/privatedoc/9LLcWh7j74sENa54/optitime-doc/docs/en/otgs-reference-book/optimisation.html#optim-optim)
      - [Trigger event tab](https://mynomadia.com/privatedoc/9LLcWh7j74sENa54/optitime-doc/docs/en/otgs-reference-book/optimisation.html#planif-event)
      - [Activation period tab](https://mynomadia.com/privatedoc/9LLcWh7j74sENa54/optitime-doc/docs/en/otgs-reference-book/optimisation.html#planif-periode)
      - [Remote server tab](https://mynomadia.com/privatedoc/9LLcWh7j74sENa54/optitime-doc/docs/en/otgs-reference-book/optimisation.html#optim-serveur)
      - [Journal tab](https://mynomadia.com/privatedoc/9LLcWh7j74sENa54/optitime-doc/docs/en/otgs-reference-book/optimisation.html#optim-journal)
    - [Activate/Deactivate an area](https://mynomadia.com/privatedoc/9LLcWh7j74sENa54/optitime-doc/docs/en/otgs-reference-book/optimisation.html#activ-region)
    - [Import/Export optim](https://mynomadia.com/privatedoc/9LLcWh7j74sENa54/optitime-doc/docs/en/otgs-reference-book/optimisation.html#impexp-optim)
  - [Mobility](https://mynomadia.com/privatedoc/9LLcWh7j74sENa54/optitime-doc/docs/en/otgs-reference-book/mob.html)
    - [Vehicles](https://mynomadia.com/privatedoc/9LLcWh7j74sENa54/optitime-doc/docs/en/otgs-reference-book/mob.html#mob-vehicules)
      - [List of vehicles](https://mynomadia.com/privatedoc/9LLcWh7j74sENa54/optitime-doc/docs/en/otgs-reference-book/mob.html#_list_of_vehicles)
      - [Form for the vehicle](https://mynomadia.com/privatedoc/9LLcWh7j74sENa54/optitime-doc/docs/en/otgs-reference-book/mob.html#_form_for_the_vehicle)
    - [Tracking device](https://mynomadia.com/privatedoc/9LLcWh7j74sENa54/optitime-doc/docs/en/otgs-reference-book/mob.html#mob-equip-suivi)
      - [List of tracking devices](https://mynomadia.com/privatedoc/9LLcWh7j74sENa54/optitime-doc/docs/en/otgs-reference-book/mob.html#_list_of_tracking_devices)
      - [Tracking device form](https://mynomadia.com/privatedoc/9LLcWh7j74sENa54/optitime-doc/docs/en/otgs-reference-book/mob.html#_tracking_device_form)
    - [Assignments](https://mynomadia.com/privatedoc/9LLcWh7j74sENa54/optitime-doc/docs/en/otgs-reference-book/mob.html#mob-affectation)
      - [List of assignments](https://mynomadia.com/privatedoc/9LLcWh7j74sENa54/optitime-doc/docs/en/otgs-reference-book/mob.html#_list_of_assignments)
      - [Assignment form](https://mynomadia.com/privatedoc/9LLcWh7j74sENa54/optitime-doc/docs/en/otgs-reference-book/mob.html#_assignment_form)
    - [Tracking utils](https://mynomadia.com/privatedoc/9LLcWh7j74sENa54/optitime-doc/docs/en/otgs-reference-book/mob.html#util-suivi)
    - [Settings](https://mynomadia.com/privatedoc/9LLcWh7j74sENa54/optitime-doc/docs/en/otgs-reference-book/mob.html#mob-parametres)
  - [User handling](https://mynomadia.com/privatedoc/9LLcWh7j74sENa54/optitime-doc/docs/en/otgs-reference-book/utilisateurs.html)
    - [Profile](https://mynomadia.com/privatedoc/9LLcWh7j74sENa54/optitime-doc/docs/en/otgs-reference-book/utilisateurs.html#profil)
      - [List of profiles](https://mynomadia.com/privatedoc/9LLcWh7j74sENa54/optitime-doc/docs/en/otgs-reference-book/utilisateurs.html#_list_of_profiles)
      - [Form for a profile](https://mynomadia.com/privatedoc/9LLcWh7j74sENa54/optitime-doc/docs/en/otgs-reference-book/utilisateurs.html#_form_for_a_profile)
    - [Collection of rights](https://mynomadia.com/privatedoc/9LLcWh7j74sENa54/optitime-doc/docs/en/otgs-reference-book/utilisateurs.html#coll-droits)
      - [List of collections of rights](https://mynomadia.com/privatedoc/9LLcWh7j74sENa54/optitime-doc/docs/en/otgs-reference-book/utilisateurs.html#_list_of_collections_of_rights)
      - [Form for a collection of rights](https://mynomadia.com/privatedoc/9LLcWh7j74sENa54/optitime-doc/docs/en/otgs-reference-book/utilisateurs.html#_form_for_a_collection_of_rights)
    - [Access rights](https://mynomadia.com/privatedoc/9LLcWh7j74sENa54/optitime-doc/docs/en/otgs-reference-book/utilisateurs.html#droits)
      - [List of access rights](https://mynomadia.com/privatedoc/9LLcWh7j74sENa54/optitime-doc/docs/en/otgs-reference-book/utilisateurs.html#_list_of_access_rights)
      - [Access right form](https://mynomadia.com/privatedoc/9LLcWh7j74sENa54/optitime-doc/docs/en/otgs-reference-book/utilisateurs.html#_access_right_form)
    - [Subscription to alerts](https://mynomadia.com/privatedoc/9LLcWh7j74sENa54/optitime-doc/docs/en/otgs-reference-book/utilisateurs.html#abo)
  - [Customization](https://mynomadia.com/privatedoc/9LLcWh7j74sENa54/optitime-doc/docs/en/otgs-reference-book/perso.html)
    - [Application settings](https://mynomadia.com/privatedoc/9LLcWh7j74sENa54/optitime-doc/docs/en/otgs-reference-book/perso.html#config-appli)
    - [Colors](https://mynomadia.com/privatedoc/9LLcWh7j74sENa54/optitime-doc/docs/en/otgs-reference-book/perso.html#couleurs)
  - [CSV files](https://mynomadia.com/privatedoc/9LLcWh7j74sENa54/optitime-doc/docs/en/otgs-reference-book/CSV.html)
    - [Importing a CSV File](https://mynomadia.com/privatedoc/9LLcWh7j74sENa54/optitime-doc/docs/en/otgs-reference-book/CSV.html#CSV-importer)
    - [Exporting a CSV file](https://mynomadia.com/privatedoc/9LLcWh7j74sENa54/optitime-doc/docs/en/otgs-reference-book/CSV.html#CSV-exporter)
      - [Entities to export](https://mynomadia.com/privatedoc/9LLcWh7j74sENa54/optitime-doc/docs/en/otgs-reference-book/CSV.html#_entities_to_export)
      - [CSV formatting](https://mynomadia.com/privatedoc/9LLcWh7j74sENa54/optitime-doc/docs/en/otgs-reference-book/CSV.html#_csv_formatting)
      - [Filtering](https://mynomadia.com/privatedoc/9LLcWh7j74sENa54/optitime-doc/docs/en/otgs-reference-book/CSV.html#_filtering)
    - [Global CSV import/export](https://mynomadia.com/privatedoc/9LLcWh7j74sENa54/optitime-doc/docs/en/otgs-reference-book/CSV.html#CSV-global)
    - [Import/export CSV template](https://mynomadia.com/privatedoc/9LLcWh7j74sENa54/optitime-doc/docs/en/otgs-reference-book/CSV.html#CSV-modele)
    - [Circulation listeners](https://mynomadia.com/privatedoc/9LLcWh7j74sENa54/optitime-doc/docs/en/otgs-reference-book/CSV.html#listener)
    - [Predefined export links](https://mynomadia.com/privatedoc/9LLcWh7j74sENa54/optitime-doc/docs/en/otgs-reference-book/CSV.html#export-predefini)
    - [Specific files](https://mynomadia.com/privatedoc/9LLcWh7j74sENa54/optitime-doc/docs/en/otgs-reference-book/CSV.html#fichiers-spec)
      - [Export of TomTom POI](https://mynomadia.com/privatedoc/9LLcWh7j74sENa54/optitime-doc/docs/en/otgs-reference-book/CSV.html#fichiers-spec-tom-tom)
      - [Export of Masternaut POI](https://mynomadia.com/privatedoc/9LLcWh7j74sENa54/optitime-doc/docs/en/otgs-reference-book/CSV.html#fichiers-spec-master)
      - [Export of Garmin POI](https://mynomadia.com/privatedoc/9LLcWh7j74sENa54/optitime-doc/docs/en/otgs-reference-book/CSV.html#fichiers-spec-garmin)
      - [Export of KML POI](https://mynomadia.com/privatedoc/9LLcWh7j74sENa54/optitime-doc/docs/en/otgs-reference-book/CSV.html#fichiers-spec-kml)
    - [Export to OT Strategic](https://mynomadia.com/privatedoc/9LLcWh7j74sENa54/optitime-doc/docs/en/otgs-reference-book/CSV.html#fichiers-spec-strategic)
    - [XML files](https://mynomadia.com/privatedoc/9LLcWh7j74sENa54/optitime-doc/docs/en/otgs-reference-book/CSV.html#XML)
      - [Basic principles](https://mynomadia.com/privatedoc/9LLcWh7j74sENa54/optitime-doc/docs/en/otgs-reference-book/CSV.html#XML-principe)
      - [Optimisation file](https://mynomadia.com/privatedoc/9LLcWh7j74sENa54/optitime-doc/docs/en/otgs-reference-book/CSV.html#XML-optim)
      - [Flows file](https://mynomadia.com/privatedoc/9LLcWh7j74sENa54/optitime-doc/docs/en/otgs-reference-book/CSV.html#XML-circulation)
      - [XML customisation file](https://mynomadia.com/privatedoc/9LLcWh7j74sENa54/optitime-doc/docs/en/otgs-reference-book/CSV.html#XML-perso)
  - [Tools](https://mynomadia.com/privatedoc/9LLcWh7j74sENa54/optitime-doc/docs/en/otgs-reference-book/outils.html)
    - [Advanced tools](https://mynomadia.com/privatedoc/9LLcWh7j74sENa54/optitime-doc/docs/en/otgs-reference-book/outils.html#MAJ-BDD)
      - [Stagger dates](https://mynomadia.com/privatedoc/9LLcWh7j74sENa54/optitime-doc/docs/en/otgs-reference-book/outils.html#_stagger_dates)
      - [Update journey distances and times](https://mynomadia.com/privatedoc/9LLcWh7j74sENa54/optitime-doc/docs/en/otgs-reference-book/outils.html#_update_journey_distances_and_times)
      - [List of journeys that are impossible with the distance server used](https://mynomadia.com/privatedoc/9LLcWh7j74sENa54/optitime-doc/docs/en/otgs-reference-book/outils.html#_list_of_journeys_that_are_impossible_with_the_distance_server_used)
      - [Renew the repository cache.](https://mynomadia.com/privatedoc/9LLcWh7j74sENa54/optitime-doc/docs/en/otgs-reference-book/outils.html#_renew_the_repository_cache)
    - [Recompute distance and time](https://mynomadia.com/privatedoc/9LLcWh7j74sENa54/optitime-doc/docs/en/otgs-reference-book/outils.html#recalcul-dist)
    - [Verify server status](https://mynomadia.com/privatedoc/9LLcWh7j74sENa54/optitime-doc/docs/en/otgs-reference-book/outils.html#etat-serveurs)
    - [SQL query](https://mynomadia.com/privatedoc/9LLcWh7j74sENa54/optitime-doc/docs/en/otgs-reference-book/outils.html#requete-SQL)
    - [Journals](https://mynomadia.com/privatedoc/9LLcWh7j74sENa54/optitime-doc/docs/en/otgs-reference-book/outils.html#journaux)
    - [JVM thread dump](https://mynomadia.com/privatedoc/9LLcWh7j74sENa54/optitime-doc/docs/en/otgs-reference-book/outils.html#thread-jvm)
  - [Opti-Time API](https://mynomadia.com/privatedoc/9LLcWh7j74sENa54/optitime-doc/docs/en/otgs-reference-book/api.html)
    - [Documentation](https://mynomadia.com/privatedoc/9LLcWh7j74sENa54/optitime-doc/docs/en/otgs-reference-book/api.html#_documentation)
    - [Import/export CSV template](https://mynomadia.com/privatedoc/9LLcWh7j74sENa54/optitime-doc/docs/en/otgs-reference-book/api.html#_import_export_csv_template)
  - [MyGeoconcept](https://mynomadia.com/privatedoc/9LLcWh7j74sENa54/optitime-doc/docs/en/otgs-reference-book/mygc.html)
- [Appendices](https://mynomadia.com/privatedoc/9LLcWh7j74sENa54/optitime-doc/docs/en/otgs-reference-book/_appendices.html)
  - [Access rights](https://mynomadia.com/privatedoc/9LLcWh7j74sENa54/optitime-doc/docs/en/otgs-reference-book/annexes-droits.html)
    - [(fr) Portail](https://mynomadia.com/privatedoc/9LLcWh7j74sENa54/optitime-doc/docs/en/otgs-reference-book/annexes-droits.html#_fr_portail)
      - [(fr) Périmètre](https://mynomadia.com/privatedoc/9LLcWh7j74sENa54/optitime-doc/docs/en/otgs-reference-book/annexes-droits.html#_fr_perimetre)
      - [(fr) Agenda](https://mynomadia.com/privatedoc/9LLcWh7j74sENa54/optitime-doc/docs/en/otgs-reference-book/annexes-droits.html#_fr_agenda)
      - [(fr) Communication](https://mynomadia.com/privatedoc/9LLcWh7j74sENa54/optitime-doc/docs/en/otgs-reference-book/annexes-droits.html#_fr_communication)
      - [(fr) Optimisation](https://mynomadia.com/privatedoc/9LLcWh7j74sENa54/optitime-doc/docs/en/otgs-reference-book/annexes-droits.html#_fr_optimisation)
      - [(fr) Indisponibilités](https://mynomadia.com/privatedoc/9LLcWh7j74sENa54/optitime-doc/docs/en/otgs-reference-book/annexes-droits.html#_fr_indisponibilites)
    - [(fr) Planification](https://mynomadia.com/privatedoc/9LLcWh7j74sENa54/optitime-doc/docs/en/otgs-reference-book/annexes-droits.html#_fr_planification)
      - [(fr) Périmètre](https://mynomadia.com/privatedoc/9LLcWh7j74sENa54/optitime-doc/docs/en/otgs-reference-book/annexes-droits.html#_fr_perimetre_2)
      - [(fr) Client](https://mynomadia.com/privatedoc/9LLcWh7j74sENa54/optitime-doc/docs/en/otgs-reference-book/annexes-droits.html#_fr_client)
      - [(fr) Rendez-vous](https://mynomadia.com/privatedoc/9LLcWh7j74sENa54/optitime-doc/docs/en/otgs-reference-book/annexes-droits.html#_fr_rendez_vous)
      - [(fr) Liste de rendez-vous](https://mynomadia.com/privatedoc/9LLcWh7j74sENa54/optitime-doc/docs/en/otgs-reference-book/annexes-droits.html#_fr_liste_de_rendez_vous)
      - [Planification](https://mynomadia.com/privatedoc/9LLcWh7j74sENa54/optitime-doc/docs/en/otgs-reference-book/annexes-droits.html#_planification)
      - [(fr) Interactions avec l’agenda](https://mynomadia.com/privatedoc/9LLcWh7j74sENa54/optitime-doc/docs/en/otgs-reference-book/annexes-droits.html#_fr_interactions_avec_l_8217_agenda)
      - [(fr) Agenda](https://mynomadia.com/privatedoc/9LLcWh7j74sENa54/optitime-doc/docs/en/otgs-reference-book/annexes-droits.html#_fr_agenda_2)
      - [(fr) Communication](https://mynomadia.com/privatedoc/9LLcWh7j74sENa54/optitime-doc/docs/en/otgs-reference-book/annexes-droits.html#_fr_communication_2)
      - [(fr) Cartographie](https://mynomadia.com/privatedoc/9LLcWh7j74sENa54/optitime-doc/docs/en/otgs-reference-book/annexes-droits.html#_fr_cartographie)
      - [(fr) Nuitée](https://mynomadia.com/privatedoc/9LLcWh7j74sENa54/optitime-doc/docs/en/otgs-reference-book/annexes-droits.html#_fr_nuitee)
      - [(fr) Suivi temps réel](https://mynomadia.com/privatedoc/9LLcWh7j74sENa54/optitime-doc/docs/en/otgs-reference-book/annexes-droits.html#_fr_suivi_temps_reel)
      - [(fr) Gestion de ressource](https://mynomadia.com/privatedoc/9LLcWh7j74sENa54/optitime-doc/docs/en/otgs-reference-book/annexes-droits.html#_fr_gestion_de_ressource)
      - [(fr) Indisponibilités](https://mynomadia.com/privatedoc/9LLcWh7j74sENa54/optitime-doc/docs/en/otgs-reference-book/annexes-droits.html#_fr_indisponibilites_2)
      - [(fr) Action personnalisée](https://mynomadia.com/privatedoc/9LLcWh7j74sENa54/optitime-doc/docs/en/otgs-reference-book/annexes-droits.html#_fr_action_personnalisee)
      - [(fr) Autres](https://mynomadia.com/privatedoc/9LLcWh7j74sENa54/optitime-doc/docs/en/otgs-reference-book/annexes-droits.html#_fr_autres)
    - [(fr) Supervision](https://mynomadia.com/privatedoc/9LLcWh7j74sENa54/optitime-doc/docs/en/otgs-reference-book/annexes-droits.html#_fr_supervision)
      - [(fr) Périmètre](https://mynomadia.com/privatedoc/9LLcWh7j74sENa54/optitime-doc/docs/en/otgs-reference-book/annexes-droits.html#_fr_perimetre_3)
      - [(fr) Contrôle](https://mynomadia.com/privatedoc/9LLcWh7j74sENa54/optitime-doc/docs/en/otgs-reference-book/annexes-droits.html#_fr_controle)
      - [(fr) Statistiques](https://mynomadia.com/privatedoc/9LLcWh7j74sENa54/optitime-doc/docs/en/otgs-reference-book/annexes-droits.html#_fr_statistiques)
      - [(fr) Autres](https://mynomadia.com/privatedoc/9LLcWh7j74sENa54/optitime-doc/docs/en/otgs-reference-book/annexes-droits.html#_fr_autres_2)
    - [(fr) Disponibilités](https://mynomadia.com/privatedoc/9LLcWh7j74sENa54/optitime-doc/docs/en/otgs-reference-book/annexes-droits.html#_fr_disponibilites)
      - [(fr) Périmètre](https://mynomadia.com/privatedoc/9LLcWh7j74sENa54/optitime-doc/docs/en/otgs-reference-book/annexes-droits.html#_fr_perimetre_4)
      - [(fr) Poste](https://mynomadia.com/privatedoc/9LLcWh7j74sENa54/optitime-doc/docs/en/otgs-reference-book/annexes-droits.html#_fr_poste)
      - [(fr) Jour d’astreinte](https://mynomadia.com/privatedoc/9LLcWh7j74sENa54/optitime-doc/docs/en/otgs-reference-book/annexes-droits.html#_fr_jour_d_8217_astreinte)
      - [(fr) Semaine d’astreinte](https://mynomadia.com/privatedoc/9LLcWh7j74sENa54/optitime-doc/docs/en/otgs-reference-book/annexes-droits.html#_fr_semaine_d_8217_astreinte)
      - [(fr) Indisponibilité](https://mynomadia.com/privatedoc/9LLcWh7j74sENa54/optitime-doc/docs/en/otgs-reference-book/annexes-droits.html#_fr_indisponibilite)
      - [(fr) Jalon](https://mynomadia.com/privatedoc/9LLcWh7j74sENa54/optitime-doc/docs/en/otgs-reference-book/annexes-droits.html#_fr_jalon)
      - [(fr) Jour de travail](https://mynomadia.com/privatedoc/9LLcWh7j74sENa54/optitime-doc/docs/en/otgs-reference-book/annexes-droits.html#_fr_jour_de_travail)
      - [(fr) Semaine de travail](https://mynomadia.com/privatedoc/9LLcWh7j74sENa54/optitime-doc/docs/en/otgs-reference-book/annexes-droits.html#_fr_semaine_de_travail)
      - [(fr) Rapports](https://mynomadia.com/privatedoc/9LLcWh7j74sENa54/optitime-doc/docs/en/otgs-reference-book/annexes-droits.html#_fr_rapports)
      - [(fr) Impression](https://mynomadia.com/privatedoc/9LLcWh7j74sENa54/optitime-doc/docs/en/otgs-reference-book/annexes-droits.html#_fr_impression)
      - [(fr) Communication](https://mynomadia.com/privatedoc/9LLcWh7j74sENa54/optitime-doc/docs/en/otgs-reference-book/annexes-droits.html#_fr_communication_3)
    - [(fr) Strategic](https://mynomadia.com/privatedoc/9LLcWh7j74sENa54/optitime-doc/docs/en/otgs-reference-book/annexes-droits.html#_fr_strategic)
      - [(fr) Périmètre](https://mynomadia.com/privatedoc/9LLcWh7j74sENa54/optitime-doc/docs/en/otgs-reference-book/annexes-droits.html#_fr_perimetre_5)
    - [(fr) Mon application 1](https://mynomadia.com/privatedoc/9LLcWh7j74sENa54/optitime-doc/docs/en/otgs-reference-book/annexes-droits.html#_fr_mon_application_1)
      - [(fr) Périmètre](https://mynomadia.com/privatedoc/9LLcWh7j74sENa54/optitime-doc/docs/en/otgs-reference-book/annexes-droits.html#_fr_perimetre_6)
    - [(fr) Sectorisation](https://mynomadia.com/privatedoc/9LLcWh7j74sENa54/optitime-doc/docs/en/otgs-reference-book/annexes-droits.html#_fr_sectorisation)
      - [(fr) Périmètre](https://mynomadia.com/privatedoc/9LLcWh7j74sENa54/optitime-doc/docs/en/otgs-reference-book/annexes-droits.html#_fr_perimetre_7)
    - [(fr) Réalisation](https://mynomadia.com/privatedoc/9LLcWh7j74sENa54/optitime-doc/docs/en/otgs-reference-book/annexes-droits.html#_fr_realisation)
      - [(fr) Périmètre](https://mynomadia.com/privatedoc/9LLcWh7j74sENa54/optitime-doc/docs/en/otgs-reference-book/annexes-droits.html#_fr_perimetre_8)
    - [(fr) Tracking](https://mynomadia.com/privatedoc/9LLcWh7j74sENa54/optitime-doc/docs/en/otgs-reference-book/annexes-droits.html#_fr_tracking)
      - [(fr) Périmètre](https://mynomadia.com/privatedoc/9LLcWh7j74sENa54/optitime-doc/docs/en/otgs-reference-book/annexes-droits.html#_fr_perimetre_9)
    - [(fr) Administration](https://mynomadia.com/privatedoc/9LLcWh7j74sENa54/optitime-doc/docs/en/otgs-reference-book/annexes-droits.html#_fr_administration)
      - [(fr) Périmètre](https://mynomadia.com/privatedoc/9LLcWh7j74sENa54/optitime-doc/docs/en/otgs-reference-book/annexes-droits.html#_fr_perimetre_10)
      - [(fr) Accès global](https://mynomadia.com/privatedoc/9LLcWh7j74sENa54/optitime-doc/docs/en/otgs-reference-book/annexes-droits.html#_fr_acces_global)
      - [(fr) Intervenant](https://mynomadia.com/privatedoc/9LLcWh7j74sENa54/optitime-doc/docs/en/otgs-reference-book/annexes-droits.html#_fr_intervenant)
      - [(fr) Poste](https://mynomadia.com/privatedoc/9LLcWh7j74sENa54/optitime-doc/docs/en/otgs-reference-book/annexes-droits.html#_fr_poste_2)
      - [(fr) Equipe](https://mynomadia.com/privatedoc/9LLcWh7j74sENa54/optitime-doc/docs/en/otgs-reference-book/annexes-droits.html#_fr_equipe)
      - [(fr) Site de travail](https://mynomadia.com/privatedoc/9LLcWh7j74sENa54/optitime-doc/docs/en/otgs-reference-book/annexes-droits.html#_fr_site_de_travail)
      - [(fr) Domaine](https://mynomadia.com/privatedoc/9LLcWh7j74sENa54/optitime-doc/docs/en/otgs-reference-book/annexes-droits.html#_fr_domaine)
      - [(fr) Sous-traitant](https://mynomadia.com/privatedoc/9LLcWh7j74sENa54/optitime-doc/docs/en/otgs-reference-book/annexes-droits.html#_fr_sous_traitant)
      - [(fr) Matériel](https://mynomadia.com/privatedoc/9LLcWh7j74sENa54/optitime-doc/docs/en/otgs-reference-book/annexes-droits.html#_fr_materiel)
      - [(fr) Région](https://mynomadia.com/privatedoc/9LLcWh7j74sENa54/optitime-doc/docs/en/otgs-reference-book/annexes-droits.html#_fr_region)
      - [(fr) Secteur](https://mynomadia.com/privatedoc/9LLcWh7j74sENa54/optitime-doc/docs/en/otgs-reference-book/annexes-droits.html#_fr_secteur)
      - [(fr) Type d’indisponibilité](https://mynomadia.com/privatedoc/9LLcWh7j74sENa54/optitime-doc/docs/en/otgs-reference-book/annexes-droits.html#_fr_type_d_8217_indisponibilite)
      - [(fr) Modèle d’astreinte](https://mynomadia.com/privatedoc/9LLcWh7j74sENa54/optitime-doc/docs/en/otgs-reference-book/annexes-droits.html#_fr_modele_d_8217_astreinte)
      - [(fr) Produit](https://mynomadia.com/privatedoc/9LLcWh7j74sENa54/optitime-doc/docs/en/otgs-reference-book/annexes-droits.html#_fr_produit)
      - [(fr) Famille de produits](https://mynomadia.com/privatedoc/9LLcWh7j74sENa54/optitime-doc/docs/en/otgs-reference-book/annexes-droits.html#_fr_famille_de_produits)
      - [(fr) Véhicule](https://mynomadia.com/privatedoc/9LLcWh7j74sENa54/optitime-doc/docs/en/otgs-reference-book/annexes-droits.html#_fr_vehicule)
      - [(fr) Equipement de suivi](https://mynomadia.com/privatedoc/9LLcWh7j74sENa54/optitime-doc/docs/en/otgs-reference-book/annexes-droits.html#_fr_equipement_de_suivi)
      - [(fr) Affectation RH véhicule](https://mynomadia.com/privatedoc/9LLcWh7j74sENa54/optitime-doc/docs/en/otgs-reference-book/annexes-droits.html#_fr_affectation_rh_vehicule)
      - [(fr) Compétence](https://mynomadia.com/privatedoc/9LLcWh7j74sENa54/optitime-doc/docs/en/otgs-reference-book/annexes-droits.html#_fr_competence)
      - [(fr) Autorisation](https://mynomadia.com/privatedoc/9LLcWh7j74sENa54/optitime-doc/docs/en/otgs-reference-book/annexes-droits.html#_fr_autorisation)
      - [(fr) Type d’intervention](https://mynomadia.com/privatedoc/9LLcWh7j74sENa54/optitime-doc/docs/en/otgs-reference-book/annexes-droits.html#_fr_type_d_8217_intervention)
      - [(fr) Objectif](https://mynomadia.com/privatedoc/9LLcWh7j74sENa54/optitime-doc/docs/en/otgs-reference-book/annexes-droits.html#_fr_objectif)
      - [(fr) Suivi de l’activité](https://mynomadia.com/privatedoc/9LLcWh7j74sENa54/optitime-doc/docs/en/otgs-reference-book/annexes-droits.html#_fr_suivi_de_l_8217_activite)
      - [(fr) Calendrier](https://mynomadia.com/privatedoc/9LLcWh7j74sENa54/optitime-doc/docs/en/otgs-reference-book/annexes-droits.html#_fr_calendrier)
      - [(fr) Configuration](https://mynomadia.com/privatedoc/9LLcWh7j74sENa54/optitime-doc/docs/en/otgs-reference-book/annexes-droits.html#_fr_configuration)
      - [(fr) Optimisation](https://mynomadia.com/privatedoc/9LLcWh7j74sENa54/optitime-doc/docs/en/otgs-reference-book/annexes-droits.html#_fr_optimisation_2)
      - [(fr) Echanges techniques](https://mynomadia.com/privatedoc/9LLcWh7j74sENa54/optitime-doc/docs/en/otgs-reference-book/annexes-droits.html#_fr_echanges_techniques)
      - [(fr) Type de localisation exceptionnelle](https://mynomadia.com/privatedoc/9LLcWh7j74sENa54/optitime-doc/docs/en/otgs-reference-book/annexes-droits.html#_fr_type_de_localisation_exceptionnelle)
      - [(fr) Typologie](https://mynomadia.com/privatedoc/9LLcWh7j74sENa54/optitime-doc/docs/en/otgs-reference-book/annexes-droits.html#_fr_typologie)
      - [(fr) Autres](https://mynomadia.com/privatedoc/9LLcWh7j74sENa54/optitime-doc/docs/en/otgs-reference-book/annexes-droits.html#_fr_autres_3)
    - [(fr) Documentation](https://mynomadia.com/privatedoc/9LLcWh7j74sENa54/optitime-doc/docs/en/otgs-reference-book/annexes-droits.html#_fr_documentation)
      - [(fr) Périmètre](https://mynomadia.com/privatedoc/9LLcWh7j74sENa54/optitime-doc/docs/en/otgs-reference-book/annexes-droits.html#_fr_perimetre_11)
  - [Optimization parameters](https://mynomadia.com/privatedoc/9LLcWh7j74sENa54/optitime-doc/docs/en/otgs-reference-book/annexes-parametres.html)
    - [(fr) Common parameters](https://mynomadia.com/privatedoc/9LLcWh7j74sENa54/optitime-doc/docs/en/otgs-reference-book/annexes-parametres.html#_fr_common_parameters)
    - [(fr) Realtime parameters](https://mynomadia.com/privatedoc/9LLcWh7j74sENa54/optitime-doc/docs/en/otgs-reference-book/annexes-parametres.html#_fr_realtime_parameters)
    - [(fr) Batch parameters](https://mynomadia.com/privatedoc/9LLcWh7j74sENa54/optitime-doc/docs/en/otgs-reference-book/annexes-parametres.html#_fr_batch_parameters)
  - [Customizable parameters](https://mynomadia.com/privatedoc/9LLcWh7j74sENa54/optitime-doc/docs/en/otgs-reference-book/annexes-custom.html)
    - [(fr) MY\_ACTIONS](https://mynomadia.com/privatedoc/9LLcWh7j74sENa54/optitime-doc/docs/en/otgs-reference-book/annexes-custom.html#_fr_my_actions)
      - [(fr) APPOINTMENT](https://mynomadia.com/privatedoc/9LLcWh7j74sENa54/optitime-doc/docs/en/otgs-reference-book/annexes-custom.html#_fr_appointment)
      - [(fr) CUSTOMER](https://mynomadia.com/privatedoc/9LLcWh7j74sENa54/optitime-doc/docs/en/otgs-reference-book/annexes-custom.html#_fr_customer)
      - [(fr) PROJECT](https://mynomadia.com/privatedoc/9LLcWh7j74sENa54/optitime-doc/docs/en/otgs-reference-book/annexes-custom.html#_fr_project)
      - [(fr) UNAVAILABILITY](https://mynomadia.com/privatedoc/9LLcWh7j74sENa54/optitime-doc/docs/en/otgs-reference-book/annexes-custom.html#_fr_unavailability)
    - [(fr) OTHERS](https://mynomadia.com/privatedoc/9LLcWh7j74sENa54/optitime-doc/docs/en/otgs-reference-book/annexes-custom.html#_fr_others)
      - [OTHERS](https://mynomadia.com/privatedoc/9LLcWh7j74sENa54/optitime-doc/docs/en/otgs-reference-book/annexes-custom.html#_others)
- [Glossary](https://mynomadia.com/privatedoc/9LLcWh7j74sENa54/optitime-doc/docs/en/otgs-reference-book/_glossary.html)

[Search Highlighter (On/Off)](https://mynomadia.com/privatedoc/9LLcWh7j74sENa54/optitime-doc/docs/en/otgs-reference-book/donnees.html#)
