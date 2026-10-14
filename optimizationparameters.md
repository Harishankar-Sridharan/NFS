# Optimization Parameters

### (fr) Common parameters

(fr) Hourly rate: Hourly rate\
Initial value: 20.0

(fr) Kilometric rate: Kilometric rate\
Initial value: 0.25

(fr) Initial day rate: Cost of the earliest possible day for an appointment. Provides the lowest value of the day rate curve\
Initial value: 10.0

(fr) Day rate increment slope before penalty: Factor applied to the day rate if later than the earliest day, before penalty day is reached\
Initial value: 1.05

(fr) Day rate late penalty: Extra cost added to the day rate when appointment is delayed\
Initial value: 5.0

(fr) First day late penalty applicable: Earliest day after which the delay penalty is considered applicable\
Initial value: 5

(fr) Day rate increment slope after penalty: Factor applied to the day rate if the appointment is scheduled later than the penalty day\
Initial value: 1.1

(fr) Radius around expected Date: Number of days enabled around expected date. If 0, the expected Date is exclusive, if -1, all days are accepted. In all cases, the expected date receives the minimum of the delay cost function\
Initial value: 0

(fr) Confirmation period (in days): Minimum number of days to scheduled date by which appointment becomes automatically confirmed\
Initial value: -1

(fr) Reservation period (in days): Minimum number of days to the scheduled date by which planned appointment can be reserved\
Initial value: 4

(fr) Snap to grid for appointment start times: Snap to a grid of a given hour step for the appointment start times. For example if an appointment is possible at 8h23: with a 5 minute-step value this appointment would be suggested at 8h25, and with a 10 minute-step value it would be suggested at 8h30.\
Initial value: none

(fr) Cost of not using a favorite day: Cost added when an appointment is not scheduled on the customer favorite(s) day(s) of week\
Initial value: 2000

(fr) Cost of not using a preferred resource: Cost added in case of the resource used is not the most appropriate\
Initial value: 100

(fr) Access time (in minutes): Fixed additional access time added to park for example (in minutes)\
Initial value: 5

(fr) Add access time between sites at the same location: Add or not the additional access time between two appointments at the same location\
Initial value: Yes

(fr) Cost per night away: If this cost is less than the cost to come back to the end work address then a night away will be preferred\
Initial value: 100.0

(fr) Minimum journey time to stay overnight: An overnight stay can be used to reach a visit which requires more than this time of travel\
Initial value: 150

(fr) Maximum number of overnight stays by week: Maximum number of overnight stays that can be suggested for a resource and a week\
Initial value: 2

(fr) Overrun ratio for journey overlap on overnight morning: Percent of overrun time allowed for journey to overlap overnight morning stays\
Initial value: 0.0

(fr) Overrun ratio for journey overlap on overnight evening: Percent of overrun time allowed for journey to overlap overnight evening stays\
Initial value: 0.0

(fr) Journey Gain Factor expected for overnight: Factor (in percent) on the Journey time expected because of using overnight. Raise this value to generate less overnight\
Initial value: 75.0

### (fr) Realtime parameters

(fr) Number of solutions found: Maximum number of solutions found by the optimization\
Initial value: 20

(fr) The slots are sorted by cost: If yes, suggested slots are sorted by cost, if no, they are sorted by ascending order of start date\
Initial value: Yes

(fr) Maximum number per day: Maximum number of slots suggested for a day. The best solutions are presented. (If the value is 0, the parameter is not used)\
Initial value: 0

(fr) Only one per day per resource: If Yes is selected then only one slot will be presented per day per resource. If No is selected then there is no limit.\
Initial value: No

(fr) Step of the time grid (in minutes): Step (in minutes from the root of the grid) defining a time grid with one possible solution by cell by default or a selected maximum number. (If the value is 0, the parameter is not used)\
Initial value: 0

(fr) Time start of grid: Time start of the grid steps. By default the step is applied from midnight (00:00)\
Initial value: 00:00

(fr) Irregular grid: If yes, the irregular intervals are used, if no, the regular step of the grid is used from the defined origin\
Initial value: No

(fr) Irregular intervals: All intervals of the time grid used in the case of an irregular grid. hh:mm values separated by ;. Inner values represent both start and end of intervals\
Initial value: 08:00;09:00;09:15;09:30;12:00;14:00;14:30;15:00;16:00;18:00

(fr) Step extended to all days: If Yes is selected then the step is extended to all searching days (the time grid covers all days). If No is selected then the grid is the same for all days (the time grid is independent of the day)\
Initial value: Yes

(fr) Maximum number per cell: Maximum number of solutions suggested for a cell. The best solutions are presented. (If the value is 0, the parameter is not used)\
Initial value: 0

(fr) Maximum number per resource per cell: Maximum number of solutions suggested per resource for a cell. The best solutions are presented. (If the value is 0, the parameter is not used)\
Initial value: 0

(fr) Solutions suggested at each step: If Yes is selected then the solutions are suggested at each step of the grid to fill a maximum of cells. The parameter limiting the number of solutions found is not used in this case.\
Initial value: No

(fr) Presentation of solutions with same cost: Solutions with same costs can be sorted by chronological order or reverse chronological order or by minimizing the time lost with other activities of the schedule\
Initial value: sorted by chronological order

(fr) Others solutions of day suggested: Position of the solutions suggested not at the start and not at the end of a day which already contains activities, or on an empty day. The solutions are searched between two locations (L1 and L2). Several choices are possible: either only near the time of L1 or only near the time of L2, or both near the time of L1 and near the time of L2 or only near the location with the lowest travel time from the appointment to place.\
Initial value: earliest and later

(fr) First solutions of day not empty: Position of the solutions suggested at the start of the day which already contains activities. The solutions are searched between two locations (L1 and L2). Several choices are possible: either only near the time of L1 or only near the time of L2, or both near the time of L1 and near the time of L2 or only near the location with the lowest travel time from the appointment to place.\
Initial value: earliest and later

(fr) Last solutions of day not empty: Position of the solutions suggested at the end of the day which already contains activities. The solutions are searched between two locations (L1 and L2). Several choices are possible: either only near the time of L1 or only near the time of L2, or both near the time of L1 and near the time of L2 or only near the location with the lowest travel time from the appointment to place.\
Initial value: earliest and later

(fr) After an unavailability not worked: Position of the solutions suggested after an unavailability not worked. The solutions are searched between two locations (L1 and L2). Several choices are possible: either only near the time of L1 or only near the time of L2, or both near the time of L1 and near the time of L2 or only near the location with the lowest travel time from the appointment to place.\
Initial value: earliest and later

(fr) Before an unavailability not worked: Position of the solutions suggested before an unavailability not worked. The solutions are searched between two locations (L1 and L2). Several choices are possible: either only near the time of L1 or only near the time of L2, or both near the time of L1 and near the time of L2 or only near the location with the lowest travel time from the appointment to place.\
Initial value: earliest and later

(fr) Maximum cost of the suggested slot: Maximum cost allowed for the suggested slot. (If this value is exceeded and greater than 0then the slot is not available)\
Initial value: 0.0

(fr) Maximum number of minutes to go to the appointment: Maximum number of minutes allowed for the move to go to the appointment. (If this value is exceeded and greater than 0 then the slot is not available)\
Initial value: 0

(fr) Maximum number of minutes to come from the appointment: Maximum number of minutes allowed for the move to come from the appointment. (If this value is exceeded and greater than 0then the slot is not available)\
Initial value: 0

(fr) Maximum number of total minutes of moves (to go to + to come from): Maximum number of minutes of moves allowed for the sum of travel times to go to and to come from the appointment. (If this value is exceeded and greater than 0then the slot is not available)\
Initial value: 0

(fr) Maximum number of minutes for the sum of moves by day: Maximum number of minutes allowed for moves by day. (If this value is exceeded and greater than 0 then the slot is not available)\
Initial value: 0

(fr) Maximum number of km to go to the appointment: Maximum number of kilometers allowed for the move to go to the appointment. (If this value is exceeded and greater than 0then the slot is not available)\
Initial value: 0.0

(fr) Maximum number of km to come from the appointment: Maximum number of kilometers allowed for the move to come from the appointment. (If this value is exceeded and greater than 0then the slot is not available)\
Initial value: 0.0

(fr) Maximum total km (To go to / To come From): Maximum number of kilometers allowed for the sum of moves to go to and to come from the appointment. (If this value is exceeded and greater than 0 then the slot is not available)\
Initial value: 0.0

(fr) Maximum number of km for moves by day: Maximum number of km allowed for the sum of moves by day. (If this value is exceeded and greater than 0then the slot is not available)\
Initial value: 0.0

(fr) Maximum cost of the suggested slot before warning: Maximum cost allowed before warning for the suggested slot. (If this value is exceeded and greater than 0 then the slot is suggested with warning)\
Initial value: 0.0

(fr) Maximum number of minutes to go to the appointment before warning: Maximum number of minutes allowed before warning for the move to go to the appointment. (If this value is exceeded and greater than 0 then the slot is suggested with warning)\
Initial value: 0

(fr) Maximum number of minutes to come from the appointment before warning: Maximum number of minutes allowed before warning for the move to come from the appointment. (If this value is exceeded and greater than 0 then the slot is suggested with warning)\
Initial value: 0

(fr) Maximum number of total minutes of moves (to go to + to come from) before warning: Maximum number of minutes of moves allowed before warning for the sum of travel times to go to and to come from the appointment. (If this value is exceeded and greater than 0 then the slot is suggested with warning)\
Initial value: 0

(fr) Maximum number of minutes for the sum of moves by day before warning: Maximum number of minutes allowed before warning for moves by day. (If this value is exceeded and greater than 0 then the slot is suggested with warning)\
Initial value: 0

(fr) Maximum number of km to go to the appointment before warning: Maximum number of kilometers allowed before warning for the move to go to the appointment. (If this value is exceeded and greater than 0 then the slot is suggested with warning)\
Initial value: 0.0

(fr) Maximum number of km to come from the appointment before warning: Maximum number of kilometers allowed before warning for the move to go to the appointment. (If this value is exceeded and greater than 0 then the slot is suggested with warning)\
Initial value: 0.0

(fr) Maximum total km (To go to / To come From) before warning: Maximum number of kilometers allowed before warning for the sum of moves to go to and to come from the appointment. (If this value is exceeded and greater than 0 then the slot is suggested with warning)\
Initial value: 0.0

(fr) Maximum number of km for moves by day before warning: Maximum number of km allowed before warning for the sum of moves by day. (If this value is exceeded and greater than 0 then the slot is suggested with warning)\
Initial value: 0.0

(fr) Method to set the slipping time interval for confirmed appointments: method to set the arrival time interval during which agreed appointments (confirmed, reserved and accepted) are allowed to slip. Default is\
Initial value: periodic

(fr) Slipping time interval duration (confirmed appointments): length (in minutes) of the slipping time interval for confirmed appointments if applicable\
Initial value: 120

(fr) Reference time of the slipping interval (confirmed appointments): Parameter for some method of slipping period computation: start time of periodic model, mid-day for half\_day model\
Initial value: 00:00

(fr) method to set the slipping time interval for reserved appointments: method to set the arrival time interval during which reserved appointments are allowed to slip. Default is unset because it is usually following the agreed setting.\
Initial value: null

(fr) Slipping time interval duration (reserved appointments): length (in minutes) of the slipping time interval for reserved appointments if applicable\
Initial value: 120

(fr) Reference time of the slipping interval (reserved appointments): Reference time for computing the arrival slipping period in the day, half-day and by time slot modes\
Initial value: 00:00

(fr) method to set the slipping time interval for planned appointments: method to set the arrival time interval during which planned appointments are allowed to slip. The default is: during the whole day\
Initial value: day

(fr) Slipping time interval duration (planned appointments): length (in minutes) of slipping time interval for planned appointments if applicable\
Initial value: 0

(fr) Reference time of the slipping intervals (planned appointments): Reference time for computing the arrival slipping period in the day, half-day and by time slot modes\
Initial value: 00:00

(fr) Enable slipping time interval of appointments with meeting: Enable or disable the use of a slipping time interval of appointments with meeting\
Initial value: Yes

(fr) Aligns start of periodic grid with the start of the Search Time Window: If yes, periodic grid starts on search start time but not to parametrized start time. Set to Yes by default\
Initial value: Yes

(fr) Maintains length when period is truncated on search TimeWindow: if yes, shifts the period found when it overlaps the search time window to maintain constant length. If no, the result is truncated. Set to Yes by default\
Initial value: Yes

(fr) Snap time to round the slipping time interval: Snap time used to round the slipping time interval\
Initial value: 15

(fr) Appointment duration included: Given slot includes duration of appointment\
Initial value: Yes

(fr) Earliest appointment time: Default value for minimum starting appointment time\
Initial value: 08:00

(fr) Latest appointment time: Default value for maximum starting appointment time\
Initial value: 20:00

(fr) Alternative earliest appointment time: Default value for another minimum starting appointment time\
Initial value: 20:00

(fr) Alternative latest appointment time: Default value for another maximum starting appointment time\
Initial value: 20:00

(fr) Search start day: Default value for the searching first day\
Initial value: 1

(fr) Search last day: Default value for the searching last day\
Initial value: 15

(fr) Search day: Default value for the searching day from current to take an appointment at a chosen day\
Initial value: 1

(fr) Factor applied to prioritize the type of intervention: Cost multiplying the gap between 100% and the resource priority for the type of intervention to be performed\
Initial value: 0

(fr) Out of sector surcharge: Cost surcharge added when appointment is out of the resource’s sector\
Initial value: 20.0

(fr) Split appointment surcharge: Cost surcharge added if resource planner show unused time slot between appointments\
Initial value: 10

(fr) Minimum duration of a multiday appointment: Minimum duration (in minutes) of an appointment which can be spread over several days\
Initial value: 0

(fr) Minimum duration placed on first/last day for a multiday appointment: Minimum duration (in minutes) placed on the first or last day for an appointment which can spread over several days. The duration of the appointment placed on the last day may not respect this rule if it is forbidden to add some free time before the first slot on the first day of appointment\
Initial value: 180

(fr) Add free time before first slot: Case of activity over several days: possibility of adding free time before the appointment on the first day if the last day of the appointment doesn’t respect the minimum duration.\
Initial value: Yes

(fr) Devote first day to the multiday appointment: Case of activity over several days: the first day is only used for this activity\
Initial value: No

(fr) Maximum duration of appointment on last day to force it back to previous day: Case of activity over several days: maximum duration of the appointment on the last day which can be removed and forced on previous day by increasing the working time on the previous day. When the value is set to zero, the previous day working time cannot be increased\
Initial value: 20

(fr) Cost of days discontinuity: Cost added for a day discontinuity (used for appointment on many days, in order to discourage appointments interrupted by a week-end for example)\
Initial value: 0

(fr) An appointment on several days can be interrupted by a fullday unavailability: Possibility of interrupting a multi-day visit by full-day unavailabilities to end it afterwards.\
Initial value: No

(fr) An appointment on several days can be split: Possibility of inserting an appointment within another one spread over several days.\
Initial value: No

(fr) An appointment on several days can be interrupted by another: Possibility of interrupting a multi-day appointment to insert another one. Time lost is placed in priority on the last day of the visit and if that is not enough by forcing each end of day as late as possible using the Maximum duration of appointment parameter for forcing the last slot of the previous day\
Initial value: No

(fr) Interrupt Cost: Cost added to the suggestion when it required the interruption of an appointment on several days\
Initial value: 5.0

(fr) An appointment started can be interrupted: Possibility of interrupting a multi-day appointment already started to insert another one. Time lost is placed in priority on the last day of the visit and if that is not enough by forcing each end of day as late as possible using the Maximum duration of appointment parameter for forcing the last slot of the previous day\
Initial value: No

(fr) Possible interruption for a whole day: Ability to interrupt a multi-day appointment and not work on it for a whole day, in order to enable inserting another appointment\
Initial value: No

(fr) Ability to complete the appointment one day later: Ability to complete the appointment over several days using an extra day, in order to enable inserting another appointment\
Initial value: No

(fr) An appointment on several days can continue the next day before the client opens: Possibility to start the appointment earlier before opening the client every day excluding the first day of the appointment. Indeed the first day of the appointment, the resource must always arrive in the opening window of the client\
Initial value: Yes

(fr) An appointment on several days can continue after the customer closes: Possibility of continuing an appointment on several days after the closing of the client and this every day of the appointment.\
Initial value: Yes

(fr) An appointment on one day can continue after the customer closes: Possibility of continuing an appointment on one day after the closing of the client\
Initial value: No

(fr) An appointment on one day can be interrupted by another at today (D0): Possibility of interrupting a single-day appointment to insert another one at today. The appointment interrupted will be finished just after to new one inserted\
Initial value: No

(fr) Interruption cost at D0: Cost added to the suggestion when it required the interruption of an appointment today\
Initial value: 0.0

(fr) An appointment started at D0 can be interrupted: Possibility of interrupting a single-day appointment already started to insert another one. The appointment interrupted will be finished just after the newly inserted one\
Initial value: Yes

(fr) An appointment on one day can be reduced at today: Possibility to reduce an appointment on today’s day to insert another appointment. The end of the interrupted appointment will have to be rescheduled later by a planner. The reduction of the appointment is intended to limit the unplanned other appointments of the day and therefore limit the impact on them.\
Initial value: No

(fr) Client’s availability times are used: If yes then the client’s availability time ranges are used. It is the normal use case. Otherwise the client’s availability times defined in the application are ignored (No is to be used with caution just for testing purposes)\
Initial value: Yes

(fr) Minimum slot duration (split appointment): Minimum duration (in minutes) of a part from a multi-part appointment on one day\
Initial value: 60

(fr) Cost of mobilizing the resource (common override): Specific value for the cost of mobilizing the resource when used in real-time optimization\
Initial value: 0.0

(fr) Cost of mobilizing the resource at D0: Specific value for the cost of mobilizing the resource at today (D0) when used in real-time optimization\
Initial value: 0.0

(fr) Cost of using a wished resource: Cost of using a wished resource when a required resource is defined\
Initial value: 50

(fr) Cost of an appointment not placed today: Added cost for an appointment that is not suggested on the day of today (D0). This cost is used to promote the possible appointment to D0\
Initial value: 0.0

(fr) Cost of unplanning a planned appointment: Fixed cost added to each appointment unplanned as a consequence of placing another one\
Initial value: 2000.0

(fr) Cost per hour of unplanning a planned appointment: Cost added to each hour of planned appointment unplanned as a consequence of placing another one\
Initial value: 40.0

(fr) Cost of unplanning an accepted appointment: Fixed cost added to each accepted appointment unplanned as a consequence of placing another one\
Initial value: 6000.0

(fr) Cost per hour of unplanning an accepted appointment: Cost added to each hour of accepted appointment unplanned as a consequence of placing another one\
Initial value: 50.0

(fr) Cost of unplanning a reserved appointment: Fixed cost added to each reserved appointment unplanned as a consequence of placing another one\
Initial value: 6000.0

(fr) Cost per hour of unplanning a reserved appointment: Cost added to each hour of reserved appointment unplanned as a consequence of placing another one\
Initial value: 50.0

(fr) Cost of unplanning a confirmed appointment: Fixed cost added to each confirmed appointment unplanned as a consequence of placing another one\
Initial value: 6000.0

(fr) Cost per hour of unplanning a confirmed appointment: Cost added to each hour of confirmed appointment unplanned as a consequence of placing another one\
Initial value: 50.0

(fr) Possible unplanning of accepted appointments on RTO "search +": Choose to make possible the unplanning of accepted appointments to place another appointment in real time optimization "search +"\
Initial value: No

(fr) Possible unplanning of reserved appointments on RTO "search +": Choose to make possible the unplanning of reserved appointments to place another appointment in real time optimization "search +"\
Initial value: No

(fr) Possible unplanning of confirmed appointments on RTO "search +": Choose to make possible the unplanning of confirmed appointments to place another appointment in real time optimization "search +"\
Initial value: No

(fr) Possible unplanning of appointments with meeting on RTO "search +": Choose to make possible the unplanning of appointments with meeting to place another appointment in real time optimization "search +"\
Initial value: Yes

(fr) Possible unplanning of marked appointments on RTO "search +": Choose to make possible the unplanning of marked appointments to place another appointment in real time optimization "search +"\
Initial value: Yes

(fr) Cost of unplanning a workrelated unavailability: Fixed cost added to each work-related unavailability unplanned as a consequence of placing another appointment\
Initial value: 4000.0

(fr) Cost per unplanned hour of a workrelated unavailability: Cost added to each hour of work-related unavailability unplanned as a consequence of placing another appointment\
Initial value: 80.0

(fr) Cost of unplanning a nonworkrelated unavailability: Fixed cost added to each non-work-related unavailability unplanned as a consequence of placing another appointment\
Initial value: 6000.0

(fr) Cost per unplanned hour of a nonworkrelated unavailability: Cost added to each hour of non-work-related unavailability unplanned as a consequence of placing another appointment\
Initial value: 120.0

(fr) Cost for nondelivery: Undelivery cost of an appointment having a priority of 50%. Set to 0 if the undelivery cost should not depend on the appointment duration (default)\
Initial value: 0.0

(fr) Hourly rate for nondelivery: Undelivery cost of an appointment taking one hour and having a priority of 50%. Set 0 if the undelivery cost should not depend on the appointment duration (default)\
Initial value: 0.0

(fr) Maximum travel cost without alert: If the cost is greater then an alert is displayed with the suggestion. The parameter is not used if the value is zero\
Initial value: 0.0

(fr) Maximum radius (in km): Maximum radius (in kilometers) of the circle with the Center the point of departure of the day. It defines the circle in which the appointments are possible. The parameter is not used if the value is zero.\
Initial value: 0.0

(fr) Radius calculated by the road: If yes then the radius is calculated by road, if not then it is calculated in a straight line (through the air)\
Initial value: No

(fr) Minimum time between two appointments considered too far: Limit value (in minutes) from which two appointments are considered too far from each other, this causing to apply the cost. The parameter is not used if its value is zero.\
Initial value: 0

(fr) Time overcost for two appointments considered too far: Time overcost (calculated in proportion to minutes) added when two appointments are considered too far\
Initial value: 0.0

(fr) Minimum distance between two appointments considered too far: Limit value (in kilometers) from which two appointments are considered too far from each other, this causing to apply the cost. The parameter is not used if its value is zero.\
Initial value: 0.0

(fr) Kilometer overcost for two appointments considered too far: Overcost per kilometer added when two appointments are considered too far from each other\
Initial value: 0.0

(fr) Cost of not using a mission type favorite weekday (realtime context): Cost added, in real-time optimization, if not using a favorite day of the week for the mission type, weighted by the level of preference of the mission type for this day.\
Initial value: 0.0

(fr) Favorite first days: Formatted string with _;_ separator which contains favorite first days for an appointment on many days. (Example 1;2;5 for Monday, Tuesday and Friday as favorite first days)\
Initial value: NC

(fr) Cost of not using a favorite first day : Cost added when the first day of an appointment is not scheduled on the favorite(s) day(s) of the week (used for appointments on many days)\
Initial value: 2000

(fr) Favorite last days: Formatted string with _;_ separator which contains the favorite last days for an appointment on many days. (Example 1;2;5 for Monday, Tuesday and Friday as favorite last days)\
Initial value: NC

(fr) Cost of not using a favorite last day: Cost added when the last day of an appointment is not scheduled on the favorite(s) day(s) of the week (used for appointment on many days)\
Initial value: 2000

(fr) Night away used: Lets the optimizer suggest a night away on allowed days\
Initial value: No

(fr) Nonfavorite night away used: Lets the optimizer suggest a night away on the initially not allowed days\
Initial value: No

(fr) Cost of nonfavorite night away: Cost of night away on the initially not allowed days\
Initial value: 2000.0

(fr) Placement with compressed travel time (use subject to limitations!): Placement with the possibility to reduce travel time. Warning! This limits or even prevents global optimization later.\
Initial value: No

(fr) Maximum number of minutes compressed: Number of minutes allowed for reducing a travel\
Initial value: 0

(fr) Maximum percentage of compression: Maximum percentage allowed for reducing a travel depending on the duration of this one\
Initial value: 0.0

(fr) Minimum number of minutes: Minimum number of minutes of the appointment after compression. (1 minute will be the smallest value allowed for an appointment)\
Initial value: 1

(fr) Compression travel costs: Added fixed cost for an appointment placement with compressed moves\
Initial value: 3000.0

(fr) Cost per minute of travel compression: Added cost per minute of travel compressed, in other words per minute of move reduced\
Initial value: 50.0

(fr) Placement with compressed duration (subject to usage limitations!): Placement with the possibility to reduce the appointment duration. Warning! This limits or even prevents global optimization later.\
Initial value: No

(fr) Maximum number of minutes compressed: Number of minutes allowed for reducing the appointment duration\
Initial value: 0

(fr) Maximum percentage of compression: Maximum percentage allowed for reducing the appointment duration depending on the duration of this one\
Initial value: 0.0

Minimum number of minutes: Minimum number of minutes of the appointment after compression. (1 minute will be the smallest value allowed for an appointment)\
Initial value: 1

(fr) Cost of appointment compression: Added fixed cost for an appointment placement with compressed duration\
Initial value: 6000.0

(fr) Cost per minute of appointment compression: Added cost per minute of appointment compressed, in other words per minute of appointment reduced\
Initial value: 150.0

(fr) Alert for an already scheduled client: Alert made for taking an appointment on a given day while we already came or will be coming soon to visit this customer a few days earlier or later\
Initial value: No

(fr) Number of days before: Number of days before a day chosen for appointment, raising an alert if we already came or will come soon to visit this customer in this period before the selected day\
Initial value: 0

(fr) Number of days maximum after: Maximum number of days after a day chosen for appointment making, raising an alert if we already came or will come soon to visit this customer in this period following the selected day\
Initial value: 0

(fr) Display solution cost as a chart: Yes to represent the cost of the solution as a chart, No to represent the cost of the solution with the calculated cost value\
Initial value: No

(fr) Intervals used to display the solution cost on chart: All of the intervals used to display the solution costs on chart\
Initial value: 100,200,300,1000,2000

(fr) The hour intervals of the time grid mode: The hour intervals used in time grid mode. hh:mm values separated by ;. Internal values represent both start and end of intervals\
Initial value: 08:00;10:00;12:00;14:00;16:00;18:00

(fr) Second customer availability slots: If yes, then a second time slot of client availability is offered for input in the real time appointment taking page\
Initial value: No

(fr) Search for optimum solution with appointment sliding: Search of a solution with possibility to slide a planned appointment for placing the new appointment\
Initial value: No

### (fr) Batch parameters

(fr) Earliest time for batch: Earliest time for appointments planned by global optimization\
Initial value: 00:00

(fr) Latest time for batch: Latest time for appointments planned by global optimization\
Initial value: 23:59

(fr) Hourly rate for nondelivery: Undelivery cost of an appointment taking one hour and having a priority of 50%. Set 0 if the undelivery cost should not depend on the appointment duration (default)\
Initial value: 0.0

(fr) Priority cost for type of intervention (common override): Specific value for the type of intervention cost priority when used in global optimization\
Initial value: 10

(fr) Cost of mobilizing the resource: Cost added when inserting a single task to an empty day of work\
Initial value: 5.0

(fr) Grade cost: Cost given to the resource having the lowest grade\
Initial value: 100.0

(fr) Cost of not using a mission type favorite weekday: Cost added, in real-time optimization, if not using a favorite day of the week for the mission type, weighted by the level of preference of the mission type for this day.\
Initial value: 0.0

(fr) Overcost per kilometer on first or last journey: Cost added per kilometer on first or last journey. If negative then favors long journeys to groups of close visits. This cost is altered by the resource specific sensitivity to first and last journey, and has to be significantly high to be effective\
Initial value: 0.0

(fr) Startup time (in minutes): Start-up time used to snap appointment to the beginning of the day (in minutes)\
Initial value: 0

(fr) Origin of day cost curve: Tells where is minimum of the cost curve during the appointment completion period. Default is "start", meaning the soonest is the cheapest"\
Initial value: Start

(fr) Day bonus rate for overdue appointments: Method to compute a bonus reducing time cost of outdated appointments to favor their scheduling\
Initial value: shift in time

(fr) Bonus for outdated cancellation time: Time when bonus for outdated is zeroed, in % of optimization search period (0.5 means bonus is 0 in middle of optimization period)\
Initial value: 0.75

(fr) Lead /Lag Ratio: Lead over Lag ratio used in shift models. If 1, the day in advance has same value that a day of lateness, if 0 only lateness is considered\
Initial value: 1.0

(fr) Ignore worksite if visit has a required resource: Ignore worksite assignment constraint for visits having required resources, the resources are not expected to be assigned to the same worksite as the appointment (default: true)\
Initial value: Yes

(fr) Ignore skill if visit has a required resource: Ignore skill constraints for visits having required resources, the resources are not expected to have the appointment required skills (default: true)\
Initial value: Yes

(fr) Ignore task types if visit has a required resource: Ignore task types constraints for visits having required resources, the resources are not expected to have priorities on appointment’s tasks (default: true)\
Initial value: Yes
