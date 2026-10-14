# Glossary

Batch Optimisation : optimisation method for series of visits, whereby a specially formulated batch processing treatment is applied to large numbers of appointments. Batch optimisation optimises all the appointments and automatically fills the plannings or agendas. The operator then validates each appointment, by confirming it directly or liaising with the customer to finalise the booking.

Real time optimisation (RTO) : interactive optimisation method who makes several suggestions for each appointment to the operator, who can then choose an appointment that is less attractive perhaps in terms of price, but that suits the customer better.

Re-activate : change an appointment’s status in the planning to **requested**. This means the appointment can now be re-optimised separately from the planning using Real Time(RTO) or Batch optimisation.

Suspended (or unplanned) : is an appointment status outside the planning that cannot be reoptimised via RTO or Batch optimisation without manual intervention on the part of a user to re-activate the appointment.

Period of fulfilment : period during which a requested appointment can be planned. It is delimited by a baseline date and a latest date.

External reference : permits exchanges between databases or via CSV files. This can be modified via the interface.

Geocoding : designates the fact of associating a geographic position to an address. This treatment is based on a [Geocoding Table](https://mynomadia.com/privatedoc/9LLcWh7j74sENa54/optitime-doc/docs/en/otgs-reference-book/_glossary.html) and returns a [geocoding score](https://mynomadia.com/privatedoc/9LLcWh7j74sENa54/optitime-doc/docs/en/otgs-reference-book/_glossary.html#geocodage-score).

Geocoding score : the geocoding score corresponds to the pertinence of the X-Y coordinates found. This pertinence is evaluated according to two criteria: the geocoding level, and a percentage score depending on the level of geocoding.

Geocoding table : database containing addresses and points of interest (for example: certain stations or small villages or points of interest)

Heuristic : calculation method for finding an optimisation solution. Generally speaking, a first solution is generated and the associated cost calculated. Next, a new solution is calculated from the first (permutation of route stops…) for which a cost is calculated. If the new solution is less costly than the previous one, it will serve as the basis for calculating a new solution, otherwise the first solution is conserved, and so on.
