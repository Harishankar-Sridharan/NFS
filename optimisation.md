# Optimization

In the definition section, we introduced the notion of real time optimization and global batch optimization. In this dialogue, it is possible to define optimization parameters that will be taken into account by the optimization engines in [real time](https://mynomadia.com/privatedoc/9LLcWh7j74sENa54/optitime-doc/docs/en/otgs-reference-book/optimisation.html) and [batch](https://mynomadia.com/privatedoc/9LLcWh7j74sENa54/optitime-doc/docs/en/otgs-reference-book/_glossary.html#batch) modes.

### Optimisation parameters

The optimization parameters can be accessed by clicking on the Optimisation parameters link in the menu.

The optimization of appointments in Opti-Time depends on a group of parameters that allow you to express the cost of a solution and particular constraints. The configuration is applied by means of an interface available in the Administration module of Opti-Time. The parameters enable the user to express preferences or constraints. For example, the enterprise does not accept that the resource spends a night in a hotel if the distance is below a given threshold. This threshold is defined in the optimization parameters.

Preview of some of the optimization parameters

![](.gitbook/assets/optim-param.png)

|                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                   |         |
| --------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ------- |
| \[Warning]                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                        | Warning |
| **Types of parameter values** Certain values have clear units (for example, the maximum n number of nights away from the site) but this is not always the case. In effect, the different values of parameters can be classified into 4 types: - a value with a unit: the units for the value will be written between brackets. For example, _Confirmation time (in days)_; - a cost value: a comparative value (this is not a real value) that represents the preference. For example, the value of the parameter _Cost per night away from the site_ is comparative. In general, it will be 5 times higher than an hourly rate; - a rate. for example, the _Increase in appointment cost for each late day_; - options: the user chooses the value from a limited series of values. For example, the _Night used_ parameter that indicates whether a resource can sleep away from the site. Only Yes or No are possible answers. |         |

#### Management of optimization profiles

Opti-Time is supplied with a default optimization profile that is valid for all areas defined in the application. The administrator can create other optimization profiles in order to harmonise the optimization parameters with the characteristics of an area.

If no association has been created between an optimization profile and an area, it is the **Default Optimisation Profile** that prevails.

**List of optimization profiles**

The [list](https://mynomadia.com/privatedoc/9LLcWh7j74sENa54/optitime-doc/docs/en/otgs-reference-book/generalites.html#generalite-liste) of optimization profiles is available when you click on the Modify parameter profiles link.

It is possible to [create](https://mynomadia.com/privatedoc/9LLcWh7j74sENa54/optitime-doc/docs/en/otgs-reference-book/generalites.html#creation), [consult](https://mynomadia.com/privatedoc/9LLcWh7j74sENa54/optitime-doc/docs/en/otgs-reference-book/generalites.html#modification) or [delete](https://mynomadia.com/privatedoc/9LLcWh7j74sENa54/optitime-doc/docs/en/otgs-reference-book/generalites.html#suppression) optimization profiles.

List of optimization profiles

![](.gitbook/assets/optim-profils.png)

**Optimisation profile form**

Setting up a new optimization profile

![](.gitbook/assets/optim-profil-modif.png)

The [form](https://mynomadia.com/privatedoc/9LLcWh7j74sENa54/optitime-doc/docs/en/otgs-reference-book/generalites.html#generalite-fiche) for an optimization profile includes the following fields:

* The internal **Identifier** for the optimization profile.
* The **Name** field allows you to enter an optimization profile name.
* The **Description** field allows you to enter a few words of description of the optimization profile
* The **Colour** field allows you to define a colour for the optimization profile.

You can [add](https://mynomadia.com/privatedoc/9LLcWh7j74sENa54/optitime-doc/docs/en/otgs-reference-book/generalites.html#ajout) and [delete](https://mynomadia.com/privatedoc/9LLcWh7j74sENa54/optitime-doc/docs/en/otgs-reference-book/generalites.html#suppression) [Areas](https://mynomadia.com/privatedoc/9LLcWh7j74sENa54/optitime-doc/docs/en/otgs-reference-book/donnees.html#region) and [Intervention groups](https://mynomadia.com/privatedoc/9LLcWh7j74sENa54/optitime-doc/docs/en/otgs-reference-book/donnees.html#groupe-intervention).

#### Description of optimization parameters

|                                                                                                                                                                       |         |
| --------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ------- |
| \[Warning]                                                                                                                                                            | Warning |
| The optimization parameters allow you to steer or orientate the results of optimizations. Great care and/or expertise is required when manipulating these parameters. |         |

|                                                                                                                                                                                                                                                                                                                                                                                                                                                             |      |
| ----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ---- |
| \[Note]                                                                                                                                                                                                                                                                                                                                                                                                                                                     | Note |
| Each cost enters into the calculation of a solution to the optimization problem submitted to the optimization engine. This problem may result in the insertion of an appointment in a route (Real time optimization) or the optimization of a series of appointments on a given number of days and resources. Different solutions are generated and the global cost is used to classify the suggestions (real time) or to choose the best (batch) solution. |      |

The full list of optimization parameters is available in the [appendices](https://mynomadia.com/privatedoc/9LLcWh7j74sENa54/optitime-doc/docs/en/otgs-reference-book/annexes-parametres.html).

#### Parameters that are common to both optimization modes

* **Hourly cost**: Cost of one hour of travel or intervention in a route.
*   **Kilometer cost**: Cost of a kilometre travelled by a resource on a route.

    |                                                                                                                                                                                                                                            |     |
    | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ | --- |
    | \[Tip]                                                                                                                                                                                                                                     | Tip |
    | Ratio between hourly cost and kilometer cost: 1 hour corresponds to 50 kms for an average speed of 50km/h. To give priority to the distance as compared to the duration, the kilometer cost must be 50 times greater than the hourly cost. |     |
* **Initial day rate**: This allows you to add a per-day cost for days elapsed between the earliest date for the appointment and the first day of the optimization.
* **Parameters linked to late penalties**. Below is an example summarising the complete range of parameters in a table of penalties and costs as a function of days elapsed.
  * **Rate of increase in daily cost (before late penalties)**: multiplication factor increasing the cost for each day elapsed before the **First day of application of the late penalty**. In the example below, the value of this parameter is defined at 1.05, the cost increases by 5% each day preceding the day of application of the late penalty.
  * **Late penalty**: Numeric constant that represents an additional weighting to the three parameters above influencing the general score in this way. The higher this value, the more the score will be adversely affected. In our example below, the value of this parameter is set to 10.
  * **First day of application of late penalty**: Number of days after which the late penalty is applied. In the example below, the value of this number of days is equal to 5.
  * **Rate of increase in the daily cost after a late penalty**: Multiplication factor increasing the cost for each day spent after the **First day of application of the late penalty**. In the example below, the value of this parameter is defined as 1.06. The cost therefore increases by 6% each day after the first day of application of the late penalty.
  *   **Radius around expected date**: Number of days possible around the expected date. If the parameter is equal to 0, the expected date is exclusive; if it is equal to -1, all days are accepted. In any event, the expected date minimises the late cost function.

      **Example:** for a resource who has an empty planning (each day is equivalent from the point of view of travel, the total cost is equal to c), we therefore obtain the following costs:

      Example of a table of penalties and costs as a function of days elapsed.

      | Day     | 0  | 1     | 2        | 3          | 4          | 5                    | 6                     |
      | ------- | -- | ----- | -------- | ---------- | ---------- | -------------------- | --------------------- |
      | Formula | c  | 1.05c | (1.05)²c | (1.05)^3.c | (1.05)^4.c | 1.1((1.06)^4.c + 10) | 1.1²((1.06)^4.c + 10) |
      | Cost    | 10 | 10.5  | 11       | 11.5       | 12         | 19                   | 20.5                  |

      In this example, day 0 corresponds to the first day of the optimization.

      |                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                        |         |
      | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ | ------- |
      | \[Warning]                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                             | Warning |
      | If the values of the parameters **Coefficient before application of late penalties** and/or **Coefficient after the application of late penalties** are set to zero, the calculation of the cost on these parameters is equal to zero (see the formula above). To avoid taking these parameters into account, you have to declare them as 1. To ensure the cost increases as a function of time, give a value that is higher than 1 to these parameters. To ensure the cost reduces over time, you need to give them a value included between 0 and 1. |         |
  * **Confirmation delay (in days)**: Number of days before a reserved appointment passes automatically into a status of confirmed.
  * **Reservation period (in days)**: Number of days before a planned appointment passes automatically into reserved status.
  *   The **Snap to grid for appointment start times** option forces the application to suggest start times for the appointment according to a regular time interval in minutes. For example, for an appointment that is possible from 8.23am onwards, the application will propose the appointment for 8.25am for a 5-minute step or 8.30am if the step is configured at 10 minutes. The steps available are none, 5m, 10m, 15m, 20m, 30m and 60m.

      |                                                                                                                       |         |
      | --------------------------------------------------------------------------------------------------------------------- | ------- |
      | \[Warning]                                                                                                            | Warning |
      | This parameter can add a gap between appointments in the agenda. It reduces the optimization performance as a result. |         |
  * **Cost of not using a favourite day**: Added cost when the day is a non-favourite day, that is, not preferred by the customer. Favourite days are configured in the handling of known customers (cf. [Planning](https://mynomadia.com/privatedoc/9LLcWh7j74sENa54/optitime-doc/docs/en/otgs-reference-book/optimisation.html) module). For example, a customer prefers to be visited on Mondays. The possible suggestions for appointments for the other days will be penalised with an additional cost applied.
  * The **Cost of not using a preferred resource** is the cost added for the utilisation of a non-preferred resource as compared with utilisation of a preferred resource. A client can be assigned to resources referred to as preferred. But the application is capable of proposing non-preferred resources in the case where there would be no other choice, and this allows you to retain a certain flexibility. This cost allows you to penalise the choice of a non-preferred resource.
  * **Access time (in minutes)**: this duration defines the sum of two durations:
    * the time spent between the stopping of the vehicle and the arrival itself at the customer’s premises;
    *   the time spent between the end of the visit to the customer and the departure of the vehicle.

        This field handles accessibility to a site by measuring it.\
        This time can therefore vary according to which customers are to be visited. The content of this field is duplicated on route stops.
  *   **Add the fixed duration between two appointments with the same location**: _Yes_, adds the **access time** to two appointments of the same geographic location. _No_, when two appointments are situated at the same place, the additional access time is not added between the two appointments, the travel times and access times are therefore null.

      |                                                               |         |
      | ------------------------------------------------------------- | ------- |
      | \[Warning]                                                    | Warning |
      | This parameter adds a gap between appointments in the agenda. |         |
* **Parameters linked to the handling of nights away**
  * The **Cost of a night away from home**, if this cost is lower than the cost incurred by returning to the address registered for the end of the working day, a night away from home is suggested.
  * **Minimum journey duration to justify a night away**: This permits definition of a minimum travel time above which a night away may be suggested. Reducing this time increases the suggestions for nights away. It is overdefined by the parameters for the resource ([Limits tab](https://mynomadia.com/privatedoc/9LLcWh7j74sENa54/optitime-doc/docs/en/otgs-reference-book/donnees.html#RH-limite)).
  * **Maximum number of nights away per week**: Defines a maximum number of nights away suggested. It is overdefined by the parameters for the resource ([Limits tab](https://mynomadia.com/privatedoc/9LLcWh7j74sENa54/optitime-doc/docs/en/otgs-reference-book/donnees.html#RH-limite)).
  * **Overrun ratio for journey overlap on overnight morning**: Percentage of overrun on the authorised time to cause an overlap on the days after nights away.
  * **Overrun ratio for journey overlap on overnight morning**: Percentage of overrun of the authorised time to enable overlap on the evenings of nights away.
  * **Journey gain factor expected for overnight away**: Factor (as a percentage) of the gain in travel time gained by the deployment of nights away. Increasing this value reduces the number of nights away.

#### Parameters relating to a real time optimization

* **Number of solutions found**: Maximum number of slots suggested for an appointment by the optimization.
  * **Maximum number per day**: Maximum number of timeslots suggested per day. The best timeslots are suggested. (If the value is 0, the setting is not used)
  * **Only one day per resource**: If Yes, then a timeslot will only be suggested per day and per resource. If No, there is no limit.
  * **Time grid step (in minutes)**: Step (in minutes) defining a time grid according to the following parameters: (if the value is 0, the parameter is not used)
    * **Time start of grid**: application source for the grid step. By default, the step is applied from midnight (00:00).
    * **Step extended to all days**: If Yes, the step is extended to all the days being sought (the time grid covers all days). If No, then the grid is the same for all days (the time grid is independent of the day)
    * **Maximum number per cell**: Maximum number of slots presented in each cell of the grid. The best slots are suggested. (If the value is 0, the parameter is not used.)
    * **Maximum number per resource and per cell**: Maximum number of slots suggested per resource in each cell of the grid. The best slots are suggested. (If the value is 0, the parameter is not used.)
    * **Solutions suggested at each step**: If Yes, then the slots are suggested at each step of the grid to fill in the maximum number of cells. The parameter limiting the number of slots suggested is not used in this case.
  * **Presentation of solutions with the same cost**: Solutions with the same cost can be sorted chronologically, or in reverse chronological order, or by limiting the time spent with other activities in the planning
  * **Position of suggested timeslots**: Position of timeslots suggested other than at the start or end of the day on days that are filled or on empty days. The timeslots are suggested between two locations L1 and L2. Several choices are possible: either, exclusively close to the time of L1, or exclusively close to the time L2, or both close to the time of L1 and the time of L2, or exclusively close to the geolocation the shortest journey time away from the appointment to be scheduled.
    * **First timeslots in a filled day**: Position suggested timeslots at the start of a day already containing geolocated activities. The timeslots are suggested between two geolocations L1 and L2. Several choices are possible: either exclusively close to the time of L1, or exclusively close to the time of L2, or both close to the time of L1 and close to the time of L2, or exclusively close to the geolocation with the shortest journey time from the appointment to schedule.
    * **Last timeslots for a filled day**: Position of timeslots suggested at the end of a day already containing geolocated activities. Timeslots are suggested between two geolocations L1 and L2. Several choices are possible: either exclusively close to the time of L1, or exclusively close to the time of L2, or both close to the time of L1, and close to the time of L2, or exclusively close to the geolocation with the shortest journey time in relation to the appointment to be scheduled.
    * **After a non-worked unavailability**: Position of timeslots suggested after a non-worked unavailability. The timeslots are suggested between two geolocations L1 and L2. Several choices are possible: either exclusively close to the time of L1, or exclusively close to the time of L2, or both close to the time of L1 and close to the time of L2, or exclusively close to the geolocation with the shortest journey time to the appointment to schedule.
    * **Before a non-worked unavailability**: Position of suggested timeslots before a non-worked unavailability. The timeslots are suggested between two geolocations L1 and L2. Several choices are possible: either exclusively close to the time of L1, or exclusively close to the time of L2, or both close to the time of L1 and close to the time of L2, or exclusively close to the location with the shortes journey time to the appointment to be scheduled.
  * **Maximum cost of the suggested timeslot**: Maximum cost authorised for the suggested timeslot. (If this value is exceeded and greater than 0 the timeslot is not suggested.)
  * **Maximum number of minutes for the outward journey**: Maximum number of minutes of travel authorised for the outward journey to the appointment. (If this value is exceeded, and greater than 0, then the timeslot is not suggested.)
  * **Maximum number of minutes for the return journey**: Maximum number of minutes of authorised journey time for the return journey from the appointment. (If this value is exceeded and greater than 0 then the timeslot is not suggested.)
  * **Maximum number for the total minutes (Outward/Return)**: Maximum number of minutes of authorised travel for the sum of the outward and return journey times to and from the appointment. (If this value is exceeded and greater than 0, the timeslot is not suggested.)
  * **Maximum number of minutes journey time per day**: Maximum number of authorised travel time per day. (If this value is exceeded and greater than 0, the timeslot is not suggested).
  * **Maximum number of kms for the outward journey**: Maximum number of kilometers authorised for the outward journey to the appointment. (If this value is exceeded and greater than 0, the timeslot is not suggested.)
  * **Maximum number of kms for the return journey**: Maximum number of kilometers authorised for the return journey from the appointment. (If this value is exceeded and greater than 0 the timeslot is not suggested.)
  * **Maximum number of kms total (Outward/Return)**: Maximum number of kilometers authorised for the sum of the outward and return journeys to and from the appointment. (If this value is exceeded and greater than 0, the timeslot is not suggested.)
  * **Maximum number of kms per day**: Maximum number of authorised travel kms per day. (If this value is exceeded, and greater than 0, the timeslot is not suggested.)
  * **Maximum cost of the timeslot suggested without any alert**: Maximum cost authorised without alert for the suggested timeslot. (If this value is exceeded and is greater than 0, the timeslot is suggested with an alert.)
  * **Maximum number of minutes for the outward journey without alert**: Maximum authorised cost without alert for the suggested timeslot. (If this value is exceeded and is greater than 0, the timeslot is suggested with an alert.)
  * **Maximum number of minutes for the return journey without an alert**: Maximum number of minutes authorised journey time without an alert for the return journey from the appointment. (If this value is exceeded and greater than 0 the timeslot is suggested with an alert.)
  * **Maximum number of minutes in total (Outward/Return) without alert**: Maximum number of minutes of authorised journey time without alert for the sum of outward and return journey time to and from the appointment. (If this value is exceeded or greater than 0 the timeslot is suggested with an alert.)
  * **Maximum number of journey minutes per day without alert**: Maximum number of authorised journey time in minutes without alert, per day. (If this value is exceeded and greater than 0, the timeslot is suggested with an alert.)
  * **Maximum number of kms for the outward journey without alert**: Maximum number of kilometers authorised without alert for the outward journey to the appointment. (If this value is exceeded and greater than 0, the timeslot is suggested with an alert).
  * **Maximum number of kms for the return journey without an alert**: Maximum number of kilometers authorised without an alert for the return journey from the appointment. (If this value is exceeded and greater than 0, the timeslot is suggested with an alert.)
  * **Maximum number of kms in total (Outward/Return) without alert**: Maximum number of kilometers authorised without alert for the sum of the outward and return journeys to and from the appointment. (If this value is exceeded and greater than 0 the timeslot is suggested with an alert.)
  * **Maximum number of kms per day without alert**: Maximum number of kms of authorised travel per day without alert. (If this value is exceeded and greater than 0, the timeslot is suggested with an alert.)
*   **Method to set slipping time interval for confirmed appointments (only for confirmed or reserved appointments)**: Enables definition of how the theoretical time of passage is communicated.

    |                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                      |     |
    | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ | --- |
    | \[Tip]                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                               | Tip |
    | There are several possibilities: - _None_: no information is given; - _On the day_: the appointment takes place during the day in question; - _On the half day_: the appointment takes place during the morning or the afternoon; - _Maximum delay_: the appointment must take place at the latest at a given time; - _Maximum advance_: the appointment must take place at the earliest at a given time; - _More or less_: the indicated visit time will be at more or less a time defined according to the following parameter (_Slipping time interval for communicated appointments_). For example, the application calculates a theoretical visit time of 11.30am; the timeslot communicated is a probable visit time between 10.30am and 12.30pm if the duration of the interval has been defined at 60 minutes. - _By timeslot_: the indicated visit time takes the parameter into account (Slipping time interval for communicated appointments, and _Reference times_ for the calculation of the arrival time interval of communicated appointments). This makes it possible to communicate to the client rounded up visiting times. For example, if the theoretical visit time is set at 10.23am, the _Reference time of slipping interval_ parameter for the calculation of the arrival time interval for communicated appointments is set at 00.00 and if the parameter for the _Slipping time interval_ duration for communicated appointments is set to 120 minutes, the timeslot to communicate to the client is a probable visit time of between 10am and 12 midday. |     |

    * **Slipping time interval duration (confirmed appointments)**: Duration in minutes of the time interval used in the parameter seen above (_Method to set slipping time interval for communicated appointment_). This parameter is taken into account only in the following modes: _More or less_, _Maximum advance_, _Maximum delay_ and _By slot_.
    *   **Reference time of slipping intervals (confirmed appointments)**: Reference time from which the slots are calculated. If a value of 00:00 is indicated, the slots are calculated from 00:00.

        For example: If the _By timeslot_ parameter is chosen in the calculation mode with a duration of 2h, the slots calculated will be 00:00-02:00 ; 02:00-04:00 ; 04:00-06:00, etc. If a visit is planned for 10.16h, the slot to communicate will therefore be 10.00-12.00.
* **Method to set slipping time interval for planned appointments**: this parameter is only applied to appointments with a planned status.
  * **Slipping time interval duration (planned appointments)**: Parameter applied only to appointments with a planned status.
  * **Reference time of slipping interval (planned appointments)**: parameter applied only to appointments with a planned status.
* **Method to set slipping time interval for planned appointments**: delay to apply in minutes (with an offset of 5 minutes, 14.55 is considered as belonging to the time interval 15.00-15.15h if the timespan is set to 15 minutes;
* **Appointment duration taken into account in the baseline time**:
  * _Yes_: the time slot suggested covers the whole of the appointment. For a _Slipping time interval duration_ of 60 minutes and an appointment defined at 10.30h for a duration of 2 hours, the application will suggest a timeslot 10.00-13.00.
  * _No_: the timeslot suggested contains the start time for the appointment. For a _Slipping time interval_ of 60 minutes and an appointment defined at 10.30h for a duration of 2 hours, the application will suggest a timeslot of 10.00-11.00.

|                                                                                                                   |     |
| ----------------------------------------------------------------------------------------------------------------- | --- |
| \[Tip]                                                                                                            | Tip |
| The 4 following parameters enable prefilling of the search interface for a timeslot (planning of an appointment). |     |

* **Earliest appointment time**: earliest time of the start of planned appointments.
* **Latest appointment time**: Latest start time for planned appointments.
* **Alternative earliest appointment time**: Another default value for the earliest appointment start time.
* **Alternative latest appointment time**: Another default value for the latest appointment start time.
* **Search start day**: Number of days (counting from today) from which the search for free timeslots will start in a real time optimization.
* **Search last day**: number of days (counting from today) from which the search for free timeslots will terminate in a real time optimization.
* **Search day**: Default value for the search day in relation to the current day, for an appointment optimised on a chosen day.
* **Factor applied to prioritise the type of intervention**: added cost for a difference of 1% between the priorities of 2 resources for a same type of task (cf. [priority of resources](https://mynomadia.com/privatedoc/9LLcWh7j74sENa54/optitime-doc/docs/en/otgs-reference-book/donnees.html#RH-priorite)).
* **Out of sector surcharge**: cost associated to an appointment located out of sector.
*   **Split appointment surcharge**: cost added per split appointment (divided up into several parts in the day).

    |                                                                                                                                                           |         |
    | --------------------------------------------------------------------------------------------------------------------------------------------------------- | ------- |
    | \[Warning]                                                                                                                                                | Warning |
    | A high value will prevent the engine from splitting an appointment in order to place it in the schedule. This can reduce the quality of the optimization. |         |
* **Parameters linked to the handling of multi-day appointments**
  * **Minimum duration of a multi-day appointment**: Minimum duration that an appointment must take to be splittable at the end of a working day.
  * **Minimum duration placed on first/last day for a multi-day appointment**: when an appointment must be split to be performed over several days, the parts of this appointment placed on the first and last days may not exceed the value defined in this field.
  * **Add free time before fist slot** (case of an appointment, at least 2 days): enables a multi-slot appointment to be offset (by at least 2 days) in such a way as to have a significant time to apply for an appointment that would have started at least the day before. This offset is applied on the morning of the start of the appointment, and therefore frees up some free time. The application will try to offset the appointment in order to respect the minimum duration of a split timeslot. The possible values for this parameter are _yes_ (to accept the addition of a free time interval) or _no_ (to not accept the addition of a free time interval).
  * **A single activity performed on the first day of a multi-day appointment**: prevents the scheduling of another appointment on the first day of an appointment scheduled over several days.
  * **Maximum duration of appointment on last day to force it back to previous day** (case of an appointment lasting at least 2 days): maximum duration of the appointment (on the last day) that can be brought back into the previous day while increasing the working day of the day before. If this value is set to zero, forcing it to the day before will be impossible.
* **Cost of days discontinuity**: cost added to an appointment scheduled over several days. If a solution is possible without splitting the appointment over several days, it will be given priority.
  * **An appointment on several days can be interrupted by a full-day unavailability**: Option to stagger an appointment over several days so it can be finished after one or several daily unavailabilities.
  * **An appointment on several days can be interrupted by another**: an option exists to staggeer an appointment over several days, in between other appointments.
  * **An appointment on several days can be interrupted**: Possibility of interrupting an appointment that takes place over several days to insert another appointment. The time lost on that appointment is replaced as a priority on the last day of the intervention, and then if this is insufficient, by forcing the appointment each evening using the value of the Maximum duration for last timeslot, that can be forced the day before.
    * **Possible interruption possible for a whole day**: The option to interrupt an appointment and to not fulfill the appointment for a full day, to enable another appointment to be inserted in its place.
    * **Ability to complete the appointment one day later**: The option to terminate an appointment lasting several days a day late, to enable another appointment to be inserted during the period.
  * **An appointment on several days can continue the next day before the client opens**: option to start the appointment earlier, before the customer opens, every day, and excluding the first day of the appointment. In effect, on the first day of the appointment, the resource will have to always arrive in the customer’s opening hours time window.
  * **An appointment on several days can continue after the customer closes**: option to pursue an appointment over several days after the customer closes, and this is possible every day the ongoing appointment continues.
  * **An appointment on one day can continue after the customer closes**: option to pursue an appointment on one day after the customer closes.
* **Minimum slot duration (split appointment)**: when an appointment must be split in order to be performed over several times within a single day (for example: on either side of the lunch break) the sections of this appointment have as a minimum duration, the value defined in this field.
*   **Mobilisation cost for a resource (common override)**: a fixed cost added for each new route. When a value is present in the [batch optimization parameter](https://mynomadia.com/privatedoc/9LLcWh7j74sENa54/optitime-doc/docs/en/otgs-reference-book/optimisation.html#param-batch) _Cost of mobilisation of a resource_, while it is the value defined in this last field that counts.

    |                                                                                                                                                                                  |     |
    | -------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | --- |
    | \[Tip]                                                                                                                                                                           | Tip |
    | A high value for this field will favour the filling of routes (with less resources mobilised). Conversely, a low value for this field will favour the mobilisation of resources. |     |
* **Cost of mobilising the resource at D0**: cost added to the first appointment of the resource’s day today (Working Day) in real time optimization.
* **Cost of an appointment not placed today**: added cost for an appointment that has not been suggested for the day, today (Working Day). This cost is used to give priority to possible whole Working Day appointments.
* **Costs linked to unplanning an appointment**
  * **Cost of unplanning a planned appointment**: Fixed cost added for each unplanned appointment for planning another appointment in its place. This parameter therefore specifies the cost of unplanning an appointment to make room for another appointment.
  * **Cost per hour of unplanning a planned appointment**: added cost for each hour of appointment with planned status unplanned so another appointment can be scheduled in its place.
  * **Cost of unplanning a reserved appointment**: added fixed cost for each reserved appointment that is unplanned for the purpose of scheduling another appointment in its place.
  * **Cost per hour of unplanning a reserved appointment**: the added cost for each hour of reserved appointment being unplanned in order to schedule another appointment in its place.
  * **Cost of unplanning a confirmed appointment**: additional fixed cost for each confirmed appointment being unplanned in order to schedule another appointment in its place.
  * **Cost per hour of unplanning a confirmed appointment**: Additional fixed cost for each hour of confirmed appointment being unplanned in order to schedule another appointment in its place.
  * **Possible unplanning of reserved appointments on RTO&#x20;**_**search +**_: this parameter allows you to choose to make it possible to take reserved appointments out of the planning to schedule another appointment in real time optimization mode.
  * **Possible unplanning of confirmed appointments on RTO "search +"**: this parameter allows you to choose to make it possible to take confirmed appointments out of the planning to schedule another appointment in real time optimization mode.
  * **Possible unplanning of appointments with meeting on RTO "search +"**: this parameter allows you to choose to make it possible to take interventions out of the planning with appointments in order to schedule another appointment in real time optimization mode.
  * **Possible unplanning of marked appointments on RTO "search +"**: this parameter allows you to choose to make it possible to take marked appointments out of the planning to schedule another appointment in its place, in real time optimization mode.
  * **Cost of unplanning a work-related unavailability**: cost above which a worked unavailability can be unplanned (by scheduling an appointment in real time).
  * **Cost per hour of unplanning a work-related unavailability**: added fixed cost per hour of worked unavailability. The total cost for this unavailability defines the cost above which this unavailability can be unplanned (by scheduling an appointment in real time).
  * **Cost of unplanning a non-work related unavailability**: the cost above which a non-worked unavailability can be unplanned (by planning an appointment in real time).
  * **Cost per hour of unplanning a non-worked unavailability**: added fixed cost per hour of non-worked unavailability. The total cost for this unavailability defines the cost above which this unavailability can be unplanned (by the scheduling of an appointment in real time).
* **Cost for non-delivery**: cost above which an appointment is not planned. This is the cost of an unfulfilled intervention with a 50% priority. By default, this cost has a value of 0 and the cost of non-delivery is unaffected by the duration of the intervention.
*   **Hourly rate for non-delivery**: added cost per hour of appointment. It is therefore proportional to the duration of the appointment. The total cost constitutes a threshold over and above which the appointment is not planned. It is the hourly cost of an unfulfilled standard priority intervention. By default, this cost has a value of 0 and the cost of non-delivery is unaffected by the appointment duration.

    |                                                                                                                                                                                                                                    |     |
    | ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | --- |
    | \[Tip]                                                                                                                                                                                                                             | Tip |
    | If this value is too low, it can happen that certain appointments are not scheduled in [batch optimization](https://mynomadia.com/privatedoc/9LLcWh7j74sENa54/optitime-doc/docs/en/otgs-reference-book/_glossary.html#batch) mode. |     |
* **Maximum cost of a journey without alert**: cost above which an alert is displayed when the appointment is suggested. The parameter is not used if set to zero.
* **Maximum radius (in km)**: maximum radius (in kilometers) of the circle that has as its centre the departure point for the day. It defines the circle in which appointments are possible. The parameter is not used when the value is set to 0.
  * **Radius calculated by the road**: if Yes, then the radius is calculated by the road network route, if No, then it is calculated as a straight line (as the crow flies).
* **Minimum time between two appointments considered too far apart**: limiting value (in minutes) above which two appointments are considered as being too far apart, as this results in the application of the associated cost. The parameter is not used if set to zero.
  * **Time overcost for two appointments considered too far apart**: added hourly surcharge when two appointments are considered as being too far apart (cf. previous parameter).
* **Minimum distance between two appointments considered too far apart**: Limit value (in kilometers) above which two appointments are considered too far apart, and this results in the application of the associated cost. The parameter is not used if set to zero.
  * **Kilometer overcost for two appointments considered too far**: Kilometer overcost added when two appointments are considered to be too far apart (cf. previous parameters).
* **Cost of not using a mission type favorite weekday (real-time context)**: added cost for an appointment scheduled on a non-favorite day in relation to the [intervention type](https://mynomadia.com/privatedoc/9LLcWh7j74sENa54/optitime-doc/docs/en/otgs-reference-book/donnees.html#type-intervention).
* **Favorite first days**: days of the week numbered from 1 to 7 (Monday = 1, Sunday = 7) favorite first day of a multi-day appointment (separated by semi-colons). To the non-favorite days will be added an additional cost (cf. the next parameter).
  *   **Cost of not using a favorite first day**: cost added when a multi-day appointment starts with an unidentified day in the previous parameter.

      |                                                                                                                                                                                                                                             |     |
      | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | --- |
      | \[Tip]                                                                                                                                                                                                                                      | Tip |
      | To prevent a multi-day appointment from being scheduled on a Friday and so being split by a weekend, enter the value 1;2;3;4 in the _Favorite first days_ parameter and enter a high value in the _Cost of not using a favorite first day_. |     |
* **Favorite last days**: same procedure as for _Favorite first days_ for the last day of a multi-day appointment
  *   **Cost of not using a favorite last day**: same procedure as for _Cost of not using a favorite first day_ for the last day of a multi-day appointment

      |                                                                                                                                                                                                                                                      |     |
      | ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | --- |
      | \[Tip]                                                                                                                                                                                                                                               | Tip |
      | To prevent a multi-day appointment from finishing on a Monday, and so from being split by a weekend, enter a value of 2;3;4;5 in the _Favorite last days_ parameter and enter a high value in the _Cost of not using a last favorite day_ parameter. |     |
* **Night away used**: this allows you to activate, or not, the scheduling of nights away with real time optimization.
  * **Non-favorite night away used**: this allows you to activate or not the scheduling of a non-defined night away in the resource form and the [Limits tab](https://mynomadia.com/privatedoc/9LLcWh7j74sENa54/optitime-doc/docs/en/otgs-reference-book/donnees.html#RH-limite). This parameter therefore enables the optimising staff member to suggest a night away when it was initially not authorised.
    * **Cost of non-favorite night away**: added cost for scheduling an appointment on an evening not defined in the resource form and the [Limits tab](https://mynomadia.com/privatedoc/9LLcWh7j74sENa54/optitime-doc/docs/en/otgs-reference-book/donnees.html#RH-limite)
* **Scheduling with compressed journey time (Utilisation subject to certain limitations!)**: Scheduling with the possibility of reducing journey times. Care must be taken, as this type of utilisation limits, or even prohibits, a global optimization subsequently.
  * **Maximum number of compressed minutes**: Maximum number of minutes allowed for reducing a journey time
  * **Maximum percentage of compression**: Maximum percentage of a journey duration that can be used to reduce a journey
  * **Minimum number of minutes**: Minimum number of minutes for the journey following compression.
  * **Cost of the compression of journeys**: Fixed added cost for scheduling an appointment with compressed journey time
  * **Cost per minute of compression of journeys**: Added cost per minute of journey compression, that is, per minute of reduced journey time.
* **Scheduling with compressed duration (Utilisation subject to certain limitations!)**: Scheduling with the option to reduce the appointment duration. Care is needed! This utilisation limits, or even prohibits, a global optimization subsequently.
  * **Maximum number of compressed minutes**: Maximum number of minutes authorised for reduction of the appointment duration
  * **Maximum compression percentage**: Maximum percentage of minutes authorised for reducing the appointment duration as a function of the initial appointment duration
  * **Minimum number of minutes**: Minimum number of minutes for the appointment after compression. (1 minute will be the smallest authorised value for an appointment)
  * **Compression cost for an appointment**; Fixed added cost for scheduling an appointment with reduced intervention duration
  * **Cost per minute for compression of an appointment**: Added cost per minute for compression of an appointment, that is per minute of reduced appointment.
* **Alert for an already scheduled client**: an alert given when an appointment it taken on a chosen day, when either the resource has already visited the customer, or they will be visiting this customer soon over the next few days.
  * **Number of days before**: Maximum number of days before a chosen day for making an appointment, raising an alert if the resource has already visited this customer, or if they will be visiting this customer shortly in this interval preceding the chosen day.
  * **Number of days maximum after**: maximum number of days after a chosen day for making an appointment, raising an alert if the resource has already visited this customer, or if they will be visiting the customer soon within this interval following the chosen day.
* **Display solution cost as a chart**: this enables display of gross costs in the suggestions during a real time optimization (the value must be set to _no_) or to assign stars (the value must be set to _yes_). A suggestion with five stars is the most effective (low cost solution) and a suggestion with one star is least effective (i.e. very costly). If a graphical representation is chosen, the following parameter will have to be configured.
  * **Intervals used to display the solution cost on chart**: allows you to define the ranges of costs corresponding to the different stars (graphical display mode for costs). For example, a cost falling between 0 and 100 corresponds to a 4-star graphical representation and so on. The user can redefine the delimiters themselves, to reflect company policy.
* **Second customer availability slots**: if Yes, then an input zone for a second time window for customer availability is suggested in the real time appointment making page.
* **Search for a staggered appointment solution**: this parameter, often called "Push through" allows the application, if it is set to _Yes_ to "force" appointments that have already been planned, in order to suggest more solutions.

#### Parameters relating to batch optimization

* **Earliest time for batch**: corresponds to the earliest time a planned batch appointment can start.
* **Latest time for batch**: corresponds to the latest time a planned batch appointment can start.
* **Hourly rate for non-delivery**: added cost per hour of appointment. It is therefore proportional to the duration of the appointment. The total cost constitutes a threshold over and above which the appointment is not planned. It is the hourly cost of an unfulfilled standard priority intervention. By default, this cost has a value of 0 and the cost of non-delivery is unaffected by the appointment duration.
* **Priority cost for type of intervention (overdefined for a batch optimization)**: added cost for a 1% difference between the priorities of 2 resources for a same type of task (cf. [resource priority](https://mynomadia.com/privatedoc/9LLcWh7j74sENa54/optitime-doc/docs/en/otgs-reference-book/donnees.html#RH-priorite)).
* **Cost of mobilising the resource**: this is the special cost for the first appointment for a resource in the day. It is a multiplication factor. It is set to less than 1 to favour filling of empty days, or higher than 1 to favour filling of days that have already started.
* **Grade cost**: Multiplication factor increasing the cost in relation to the experience of the resource (junior, confirmed, expert) (cf. [Skills tab in the resource form](https://mynomadia.com/privatedoc/9LLcWh7j74sENa54/optitime-doc/docs/en/otgs-reference-book/donnees.html#RH-comp)). The more experienced the resource, the lower the cost. With a high cost, the optimization engine will give more priority to experienced resources to perform interventions.
* **Cost of not using a mission type favorite weekday (overdefined for a batch optimization)**: added cost for an appointment scheduled on a non-favorite day in relation to the [intervention type](https://mynomadia.com/privatedoc/9LLcWh7j74sENa54/optitime-doc/docs/en/otgs-reference-book/donnees.html#type-intervention).
* **Overcost per kilometer on first or last journey**: kilometer cost added to the first and last journey. If negative, favours long journeys towards a group of distant visit points. This cost is assigned through the sensitivity of the resource to the first and last journeys, and must be set sufficiently high to be taken into account.
* **Start-up time (in minutes)**: duration before departure to get to the next appointment (example: the end of the appointment is set to 14.30pm, but the resource will really depart for their next visit at 14.40pm, in time to arrive at their vehicle and to perform jobs such as putting away equipment or tools…).
* **Origin of delay cost curve**: specifies the position of the minimum late cost during the period of fulfilling the appointment.
* **Day bonus rate for overdue appointments**: method for calculating the bonus lowering the daily cost of past or late appointments in relation to the search period.
  * **Bonus for outdated cancellation time**: day from which the bonus for an outdated appointment has a value of 0. Expressed in % of the search period (0.5 of a period of 30 days signifies the 15th day).
* **Lead/lag ratio**: the lead/lag ratio used in the stagger templates. If set to 1, a day in advance is equivalent to a day behind, if set to 0, only late days are taken into account.
* **Assignment to sites ignored if the appointment has a required resource**: if an appointment has a required resource, the worksite assignment constraint is no longer verified (true by default).
* **Skills ignored if the appointment has a required resource**: if an appointment has a required resource, the requirement for skills are no longer verified (true by default).
* **Ignore task types if visit has a required resource**: if an appointment has a required resource, the preferences for task types are not taken into account (true by default).

### Optimisation planning

Optimisation management is performed by clicking on the Optimisation planning link in the menu.

The interface has six tabs: [service](https://mynomadia.com/privatedoc/9LLcWh7j74sENa54/optitime-doc/docs/en/otgs-reference-book/optimisation.html#optim-service), [optimisation](https://mynomadia.com/privatedoc/9LLcWh7j74sENa54/optitime-doc/docs/en/otgs-reference-book/optimisation.html#optim-optim), [trigger event](https://mynomadia.com/privatedoc/9LLcWh7j74sENa54/optitime-doc/docs/en/otgs-reference-book/optimisation.html#planif-event), [period of activation](https://mynomadia.com/privatedoc/9LLcWh7j74sENa54/optitime-doc/docs/en/otgs-reference-book/optimisation.html#planif-periode), [remote server](https://mynomadia.com/privatedoc/9LLcWh7j74sENa54/optitime-doc/docs/en/otgs-reference-book/optimisation.html#optim-serveur), and [journal](https://mynomadia.com/privatedoc/9LLcWh7j74sENa54/optitime-doc/docs/en/otgs-reference-book/optimisation.html#optim-journal), described below.

#### Service tab

This section allows the user to stop or restart the service. It is also possible to run optimisations manually.

The ![images/ref/buttons/recyclage.png](.gitbook/assets/recyclage.png) button allows the user to refresh the page content.

Management of the optimisation service

![](.gitbook/assets/optim-service.png)

(1) Optimization services

This part indicates whether the service is started or stopped.

Click on **Start the service** to activate the automated optimisation.\
Click on **Stop the service** to deactivate an automated optimisation.

When the modifications have been applied, it is necessary to **Restart the service** for them to be taken into account:

Restarting the optimisation service

![images/ref/admin/optim-service-redemarrer.png](.gitbook/assets/optim-service-redemarrer.png)

|                                                                   |         |
| ----------------------------------------------------------------- | ------- |
| \[Warning]                                                        | Warning |
| In this case, all optimisations in progress are stopped and lost. |         |

(2) **Optimisations in progress**

In this part, the application lists all optimisations that are in the course of being optimised.

Optimisation in progress

![](.gitbook/assets/optim-en-cours.png)

You can view the names of all optimisations currently in progress, the area they apply to, the optimisations' programmed start and end times, the triggering event (automated or user triggered event) as well as the optimisation server.

The Stop button interrupts the optimisation currently in progress. A certain time elapses before the optimisation stops. A result is imported following this action.

The ![images/ref/buttons/bouton-supprimer.png](.gitbook/assets/bouton-supprimer.png) button allows you to cancel the optimisation. No result will be imported.

(3) **Planned optimisations**

Lists all optimisations likely to be run automatically.

(4) **Possible manual optimisations**

Lists all the optimisations likely to be triggered manually. It is possible to filter resources that will be used for the optimisation as well as the dates between which the agendas of resources will be able to be modified by the optimisation.

It is also possible to redefine the optimisation duration as well as the [heuristic](https://mynomadia.com/privatedoc/9LLcWh7j74sENa54/optitime-doc/docs/en/otgs-reference-book/optimisation.html).

The ![images/ref/buttons/play.png](.gitbook/assets/play.png) button allows you to start the optimisation.

|                                                                                                                                                                                                                                                                                                                                                                                                              |      |
| ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ | ---- |
| \[Note]                                                                                                                                                                                                                                                                                                                                                                                                      | Note |
| If no filter is defined, it is the options defined in the [Optimisation](https://mynomadia.com/privatedoc/9LLcWh7j74sENa54/optitime-doc/docs/en/otgs-reference-book/optimisation.html#optim-optim) tab that will be used. The list of heuristics is defined in the [next chapter](https://mynomadia.com/privatedoc/9LLcWh7j74sENa54/optitime-doc/docs/en/otgs-reference-book/optimisation.html#optim-optim). |      |

#### Optimisation tab

This section allows you to define which optimisations to apply, either automatically, or manually (cf. [previous chapter](https://mynomadia.com/privatedoc/9LLcWh7j74sENa54/optitime-doc/docs/en/otgs-reference-book/optimisation.html#optim-service)).

An optimisation can be created, consulted, or modified following the standard procedure ([Cf. General points](https://mynomadia.com/privatedoc/9LLcWh7j74sENa54/optitime-doc/docs/en/otgs-reference-book/generalites.html)).

**List of saved optimisations**

The interface displays the [list](https://mynomadia.com/privatedoc/9LLcWh7j74sENa54/optitime-doc/docs/en/otgs-reference-book/generalites.html#generalite-liste) of saved optimisations

List of optimisations

![](.gitbook/assets/optim-planif-optim.png)

**Form for an optimisation**

Optimisation form

![](.gitbook/assets/optim-planif-optim-modif.png)

The optimisation [form](https://mynomadia.com/privatedoc/9LLcWh7j74sENa54/optitime-doc/docs/en/otgs-reference-book/generalites.html#generalite-fiche) comprises the following information:

* **Name**: this field serves to give a name to the optimisation created;
* **Area**: the user indicates an area to optimise;
* **Optimisation period**: two values must be supplied: the first value corresponds to the offset of the optimisation period as compared with the date of its triggering and the second corresponds to the number of days in the calendar taken into account in the optimisation from the first value;
* **Optimisation duration**: this field indicates the duration of the optimisation by the optimisation engine in minutes. This is the maximum optimisation duration granted;
* **Exchange directory**: this field indicates the filepath for the exchange directory of files generated by the optimisation engine on the server on which Opti-Time is installed;
* **Active**: _yes_ the optimisation is functional; _no_, the optimisation is in standby mode;
* **Type of optimisation**: _Rapid_, only requested appointments are processed, and the other appointments already present in the plannings are not modified. _Total_, all appointments (except confirmed appointments) are re-optimised;
* **Generation of recurring appointments before optimisation**: _Yes_, the appointments of regular customers (cf. [Management of known clients](https://mynomadia.com/privatedoc/9LLcWh7j74sENa54/optitime-doc/docs/en/otgs-reference-book/optimisation.html)) are automatically generated in the optimisation period defined above. _No_, no appointment with regular clients is generated in the optimisation period;
* **Generation of nights away before optimisation**: _Yes_, the nights away will be added during the optimisation as a function of the parameters defined in the [resource form](https://mynomadia.com/privatedoc/9LLcWh7j74sENa54/optitime-doc/docs/en/otgs-reference-book/donnees.html#RH-limite) and [optimisation parameters](https://mynomadia.com/privatedoc/9LLcWh7j74sENa54/optitime-doc/docs/en/otgs-reference-book/optimisation.html#param-optim); _No_, no night away will be generated during the optimisation.
* **Utilisation of sales periods**: _Yes_ (the creation of a sales period is required), the sales periods are respected in the optimisation period defined above. _No_, the sales periods are not taken into account;
* **Status of optimisation period results**: this defines the number of days after the start of the optimisation period for appointments to automatically progress to a confirmed status. It will be possible to define a delay on the following days in terms of the number of days during which appointments have reserved status. For example, all appointments at D-2 must be confirmed (the time and the resource are known) and between D-2 and D-5 all appointments are reserved (the time is known, but not the resource). In this case, values 2 and 3 respectively must be entered.

Clicking on **Advanced parameters**, the following additional information display:

Advanced parameters

![](.gitbook/assets/optim-planif-param-avance.png)

* [**Heuristic**](https://mynomadia.com/privatedoc/9LLcWh7j74sENa54/optitime-doc/docs/en/otgs-reference-book/optimisation.html):
  * _High (Default)_
  * _Fill with routes (H5)_
  * _Improvement (H4)_
  * _Insert by visit (H1)_
  * _Add visit (H2)_
  * _Fill with visits (H6)_
  * _Addition by sector (H9)_
  * _Low_: utilisation of the [real time optimisation](https://mynomadia.com/privatedoc/9LLcWh7j74sENa54/optitime-doc/docs/en/otgs-reference-book/optimisation.html) engine
* **Subset**:
  * _None_: by default, the optimisation is not split up into sections
  * _Resource_: the optimisation is divided up into several packets (one per resource)
  * _Worksite_: the optimisation is split up into several packets (one per work site)

|                                                                                                                                                                                                                                 |     |
| ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | --- |
| \[Tip]                                                                                                                                                                                                                          | Tip |
| Breaking the optimisation down into sub-sets is recommended in the following cases: customers always visited by the same resource (sub-set: resource) or resources don’t have a worksite or secondary sector (subset: worksite) |     |

* **Pre-optimisation of rounds (circuit routes)**: adds a phase before the optimisation enabling positioning/placement of linked appointments or circuits
* **Pre-optimisation of appointments having a duration of at least**: adds a phase before the optimisation enabling the scheduling of long appointments
* **Duration of the pre-optimisation**: duration of the scheduling phase for long appointments (as a percentage in relation to the duration of the optimisation)
* **Appointments with requested status are not optimised**: The optimisation will not take into account appointments with a requested [status](https://mynomadia.com/privatedoc/9LLcWh7j74sENa54/optitime-doc/docs/en/otgs-reference-book/_the_different_statuses_for_appointments_in_opti_time.html#statuts).
* **Appointments with a planned status cannot change day**: appointments with a planned [status](https://mynomadia.com/privatedoc/9LLcWh7j74sENa54/optitime-doc/docs/en/otgs-reference-book/_the_different_statuses_for_appointments_in_opti_time.html#statuts) cannot change day during the optimisation
* **Appointments with a planned status cannot change resource**: you will not be able to change resource for an appointment with a planned [status](https://mynomadia.com/privatedoc/9LLcWh7j74sENa54/optitime-doc/docs/en/otgs-reference-book/_the_different_statuses_for_appointments_in_opti_time.html#statuts) during the optimisation
* **Appointments with planned status will remain scheduled**: you will not be able to unplan appointments with a planned [status](https://mynomadia.com/privatedoc/9LLcWh7j74sENa54/optitime-doc/docs/en/otgs-reference-book/_the_different_statuses_for_appointments_in_opti_time.html#statuts) during the optimisation
* **Optimisation of appointments with a planned status before, and up to T1 -**: enables reoptimisation of appointments with planned status dating from before the optimisation period. The value in Days enables determination of the date from which the planned appointments will remain in the planning (from T1)
* **Appointments with an optimised planned status before T1 will not be reactivated if they have not been scheduled**: appointments with a planned [status](https://mynomadia.com/privatedoc/9LLcWh7j74sENa54/optitime-doc/docs/en/otgs-reference-book/_the_different_statuses_for_appointments_in_opti_time.html#statuts) scheduled before and up to T1 will not be unplanned during an optimisation if it is not possible to replan them.
* **Post-optimisation of appointments having a duration of at least**: Adds a phase after the optimisation enabling the scheduling of long appointments
* **Status of results over the optimisation period**:
  * _first days in confirmed status_
  * _subsequent days with reserved status_

|                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                          |      |
| ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ | ---- |
| \[Note]                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                  | Note |
| The minimum duration for an appointment to be considered as long is defined by the [optimisation parameter](https://mynomadia.com/privatedoc/9LLcWh7j74sENa54/optitime-doc/docs/en/otgs-reference-book/optimisation.html#param-optim) _Minimum duration for a multi-day appointment_ If neither the _Pre-optimisation of appointments with duration of at least_ parameter nor the _Post-optimisation of appointments with duration of at least_ parameter is checked, the multi-day appointments will not be optimised. |      |

**Trigger event** and **Activation period**

In this part, the application lists all optimisations that are in the course of being optimised.

Association of a trigger event to an optimisation

![](.gitbook/assets/optim-planif-optim-event.png)

The optimisation will be launched by the chosen trigger event.

The optimisation will only be visible in the [Service](https://mynomadia.com/privatedoc/9LLcWh7j74sENa54/optitime-doc/docs/en/otgs-reference-book/optimisation.html) tab during the chosen period of activation.

#### Trigger event tab

The user must define trigger events to run a series of optimisations automatically. A trigger event can be shared by several optimisations if one wants them all to start automatically at the same time.

It is possible to [create](https://mynomadia.com/privatedoc/9LLcWh7j74sENa54/optitime-doc/docs/en/otgs-reference-book/generalites.html#creation), [consult](https://mynomadia.com/privatedoc/9LLcWh7j74sENa54/optitime-doc/docs/en/otgs-reference-book/generalites.html#modification) or [delete](https://mynomadia.com/privatedoc/9LLcWh7j74sENa54/optitime-doc/docs/en/otgs-reference-book/generalites.html#suppression) a trigger event.

**List of trigger events**

The interface displays the [list](https://mynomadia.com/privatedoc/9LLcWh7j74sENa54/optitime-doc/docs/en/otgs-reference-book/generalites.html#generalite-liste) of trigger events:

List of trigger events

![](.gitbook/assets/optim-planif-event.png)

**Trigger event form**

Trigger event

![](.gitbook/assets/optim-planif-event-modif.png)

The [form](https://mynomadia.com/privatedoc/9LLcWh7j74sENa54/optitime-doc/docs/en/otgs-reference-book/generalites.html#generalite-fiche) for trigger events regroups the following fields:

* **Name**: this field serves to give a name to a trigger event; this name is chosen by the user, but it must not include any special characters (space, etc..);
* **Day of the week**: this field determines the days the optimisation is to be run;
* **Time in hours and minutes**: these fields serve to determine at which moment of the day the optimisation is run.
* **Triggered optimisation**: In this section, it is possible to [add](https://mynomadia.com/privatedoc/9LLcWh7j74sENa54/optitime-doc/docs/en/otgs-reference-book/generalites.html#ajout) to this trigger event one or several optimisations and to [delete](https://mynomadia.com/privatedoc/9LLcWh7j74sENa54/optitime-doc/docs/en/otgs-reference-book/generalites.html#suppression) one or several associated optimisations.

|                                                                                                                                                                                                                                  |      |
| -------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ---- |
| \[Note]                                                                                                                                                                                                                          | Note |
| It is also possible to define a trigger for optimisation in the optimisation form ([Optimisation tab](https://mynomadia.com/privatedoc/9LLcWh7j74sENa54/optitime-doc/docs/en/otgs-reference-book/optimisation.html#optim-optim)) |      |

#### Activation period tab

This section enables declaration to the application of possible automated optimisation periods available for the different optimisations (Cf. [Optimisation tab](https://mynomadia.com/privatedoc/9LLcWh7j74sENa54/optitime-doc/docs/en/otgs-reference-book/optimisation.html#optim-optim))

You can [create](https://mynomadia.com/privatedoc/9LLcWh7j74sENa54/optitime-doc/docs/en/otgs-reference-book/generalites.html#creation), [consult](https://mynomadia.com/privatedoc/9LLcWh7j74sENa54/optitime-doc/docs/en/otgs-reference-book/generalites.html#modification) or [delete](https://mynomadia.com/privatedoc/9LLcWh7j74sENa54/optitime-doc/docs/en/otgs-reference-book/generalites.html#suppression) a period of activation.

**List of activation periods**

The interface displays the [list](https://mynomadia.com/privatedoc/9LLcWh7j74sENa54/optitime-doc/docs/en/otgs-reference-book/generalites.html#generalite-liste) of periods of activation:

List of periods of activation

![](.gitbook/assets/optim-planif-activ.png)

**Form for an activation period**

The [form](https://mynomadia.com/privatedoc/9LLcWh7j74sENa54/optitime-doc/docs/en/otgs-reference-book/generalites.html#generalite-fiche) for a period of activation regroups the following fields:

Activation period

![](.gitbook/assets/optim-planif-activ-modif.png)

* **Name**: this field enables a name to be given to the activation period created;
* **Period of activation**: two values must be supplied; the first value corresponds to the offset of the optimisation period in relation to its trigger date, and the second corresponds to the number of calendar days taken into account in the optimisation from the first value;
* **Triggered optimisation**: In this section you can [add](https://mynomadia.com/privatedoc/9LLcWh7j74sENa54/optitime-doc/docs/en/otgs-reference-book/generalites.html#ajout) to this activation period one or several optimisations and [delete](https://mynomadia.com/privatedoc/9LLcWh7j74sENa54/optitime-doc/docs/en/otgs-reference-book/generalites.html#suppression) one or several associated optimisations.

|                                                                                                                                                                                                                                                    |      |
| -------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ---- |
| \[Note]                                                                                                                                                                                                                                            | Note |
| It is also possible to define the period of activation for n optimisations in the optimisation form ([Optimisation tab](https://mynomadia.com/privatedoc/9LLcWh7j74sENa54/optitime-doc/docs/en/otgs-reference-book/optimisation.html#optim-optim)) |      |

#### Remote server tab

This section requests you indicate to Opti-Time the locations of all servers from which batch optimisations are performed.

It is possible to have several remote servers to enable several optimisations to run simultaneously.

It is possible to [create](https://mynomadia.com/privatedoc/9LLcWh7j74sENa54/optitime-doc/docs/en/otgs-reference-book/generalites.html#creation), [consult](https://mynomadia.com/privatedoc/9LLcWh7j74sENa54/optitime-doc/docs/en/otgs-reference-book/generalites.html#modification) or [delete](https://mynomadia.com/privatedoc/9LLcWh7j74sENa54/optitime-doc/docs/en/otgs-reference-book/generalites.html#suppression) an access to a remote server.

**List of remote servers**

The interface displays the [list](https://mynomadia.com/privatedoc/9LLcWh7j74sENa54/optitime-doc/docs/en/otgs-reference-book/generalites.html#generalite-liste) of remote servers:

List of remote optimisation servers

![](.gitbook/assets/optim-planif-serveur.png)

**Form for a remote optimisation server**

Remote server form

![](.gitbook/assets/optim-planif-serveur-modif.png)

The [form](https://mynomadia.com/privatedoc/9LLcWh7j74sENa54/optitime-doc/docs/en/otgs-reference-book/generalites.html#generalite-fiche) for a remote server regroups the following fields:

* **Name**: this field requests the name of the remote optimisation server; this name is chosen by the user, but must not include any special characters (space..);
* **Priority level**: Priority of the remote server in relation to the other remote servers handling the same area;
* **Active**: _Yes_: the optimisation server is available for handling optimisations; _No_: it is not available.
* **URL**: this field must indicate the filepath to access GCIS (for example: http://monserveur:port/Scripts/gcis.exe);
* **Page Name**: this field indicates the name of the GCIS page; this page is the one that has been saved in the GCIS administration at the time of installation;
* **Delay**: this field corresponds to the period between 2 requests from Opti-Time to the optimisation engine on the progress status for the optimisation. The default time is 5,000 milliseconds.
* **Local access**: this field contains the local filepath for files generated by the optimisation engine at the end of the optimisation (for example, C:\OptimisationFiles);
* **Remote access**: this field contains the filepath enabling Opti-Time to go and search for the files generated by the optimisation engine on the remote server (for example, c).
* **Map and areas handled**

A remote server stores one or several areas to optimise. The user assigns one priority to each area, on each remote server.

An area can be stored several times on different remote servers with a different priority. When the optimisation is launched, the system examines each of the areas to optimise, and triggers the work after having examined the priority.

|                                                                                                                                   |     |
| --------------------------------------------------------------------------------------------------------------------------------- | --- |
| \[Tip]                                                                                                                            | Tip |
| If an area is stored on different remote servers, it is strongly recommended different periods are optimised without any overlap. |     |

It is possible to [add](https://mynomadia.com/privatedoc/9LLcWh7j74sENa54/optitime-doc/docs/en/otgs-reference-book/generalites.html#ajout), [consult](https://mynomadia.com/privatedoc/9LLcWh7j74sENa54/optitime-doc/docs/en/otgs-reference-book/generalites.html#modification) or [delete](https://mynomadia.com/privatedoc/9LLcWh7j74sENa54/optitime-doc/docs/en/otgs-reference-book/generalites.html#suppression) a managed map.

The map must be added before associating an area to it subsequently.

The [form](https://mynomadia.com/privatedoc/9LLcWh7j74sENa54/optitime-doc/docs/en/otgs-reference-book/generalites.html#generalite-fiche) of a managed map comprises the following fields:

Add a Geoconcept map

![](.gitbook/assets/optim-planif-carte.png)

* **Access path**: directory of cartographic files (.GCM/.GCR)
* **Description**; Free field
* **Active**: _Yes_: this map is used for the optimisation; _No_: this map is not utilised
* **Areas managed**

This section allows you to [associate](https://mynomadia.com/privatedoc/9LLcWh7j74sENa54/optitime-doc/docs/en/otgs-reference-book/generalites.html#ajout) areas to this map and to [delete](https://mynomadia.com/privatedoc/9LLcWh7j74sENa54/optitime-doc/docs/en/otgs-reference-book/generalites.html#suppression) associations.

|                                                                             |     |
| --------------------------------------------------------------------------- | --- |
| \[Tip]                                                                      | Tip |
| It is at this moment that you can assign a priority to areas to be treated. |     |

Form for an associated area

![](.gitbook/assets/optim-planif-carte-region.png)

The [form](https://mynomadia.com/privatedoc/9LLcWh7j74sENa54/optitime-doc/docs/en/otgs-reference-book/generalites.html#generalite-fiche) for an associated area regroups the following fields:

* **Area**: Name of the [area](https://mynomadia.com/privatedoc/9LLcWh7j74sENa54/optitime-doc/docs/en/otgs-reference-book/donnees.html#region) to assign
* **Priority level**: Level of priority for the area in relation to other managed areas

|                                                              |      |
| ------------------------------------------------------------ | ---- |
| \[Note]                                                      | Note |
| A priority level 1 takes precedence over a priority level 2. |      |

#### Journal tab

The results of preceding optimisations are stored on the server and it is possible to consult them from this screen.

It is possible to filter the [list](https://mynomadia.com/privatedoc/9LLcWh7j74sENa54/optitime-doc/docs/en/otgs-reference-book/generalites.html#generalite-liste) of optimisation results:

Journal filter

![](.gitbook/assets/optim-journal-conf.png)

* **Result**:
  * _All_: displays all optimisation journals
  * _In error_: only displays the optimisation journals in error (for which the result has not been imported)
  * _OK_: displays the optimisation journals for which the result has been imported
* **Area**: enables limitation of the display to the optimisations for a [area](https://mynomadia.com/privatedoc/9LLcWh7j74sENa54/optitime-doc/docs/en/otgs-reference-book/donnees.html#region)
* **Period**: allows filtering on optimisation date
* **Limits the display to the n last actions**: displays the number of lines defined in the corresponding check-box.

Clicking on Validate, the reports display:

List of optimisation results

![](.gitbook/assets/optim-journal-liste.png)

Clicking on the report of an optimisation result, a new window appears with the report on the optimisation:

Optimisation report

![](.gitbook/assets/optim-journal-info.png)

The optimisation report comprises the following items:

* **Optimisation** gives the name of the optimisation, of the optimised area, and of the trigger event;
* **Server** gives the name and URL of the server where the optimisation is run;
* **Time** indicates the start and the end of the optimisation;
* **Error** displays the code and error messages in the case of an error during the optimisation;
* **GssXmlOut.xml** Source file for the optimisation before it is treated by the optimisation engine;
* **GssXmlIn.xml**: result file, before its import into the application;
* **GssErrorWarning.txt** : Text file describing all error and warning messages that could take place during optimisation;
* **GssLog.txt**: journal file describing all actions from the time of export to the optimisation engine to the importation of appointments into Opti-Time as well as the whole of the optimisation process via the optimisation engine.

Download files: this enables download of all files in the form of a compressed archive.

Download the summary: summary file for the optimisation. Includes general information concerning the optimisation (duration, number of scheduled appointments, non-scheduled appointments…)

### Activate/Deactivate an area

**Activate/Deactivate an area** lists the areas and gives their status. The administrator can manually deactivate an area, or re-activate it. It is also possible to know whether an area is deactivated by an automated process of optimisation for example.

Access the function by clicking on the Activate/Deactivate an area link in the menu.

List of the statuses of areas

![](.gitbook/assets/optim-region.png)

The **Status** column can take the following statuses;

* **V** signifies that the area is activated;
* **X** signifies that the area is deactivated;
* **X with a panel** The area is temporarily deactivated via an automated optimisation process.

To activate/deactivate an area, check/uncheck the check-boxes for areas to activate/deactivate and then click on Validate.

|                                                                                                                                                                         |         |
| ----------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ------- |
| \[Warning]                                                                                                                                                              | Warning |
| The deactivation of an area prevents users from acting on all functions linked to the plannings (confirm, plan, unplan, appointments or add, modify unavailabilities…). |         |

A message also warns the user the area is locked. Nevertheless, users can continue to input requested appointments since there is no notion, at this stage, of scheduling or planning.

### Import/Export optim

In this function, you will be presented with the option to create [optimizations](https://mynomadia.com/privatedoc/9LLcWh7j74sENa54/optitime-doc/docs/en/otgs-reference-book/portail-optim-glob.html) by file.
