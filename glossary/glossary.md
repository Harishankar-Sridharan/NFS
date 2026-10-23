# Glossary

This glossary defines the main terms used in the NFS user guide.

**Batch optimization**
: An optimization method for series of visits. A specially formulated batch process is applied to a large number of appointments. Batch optimization optimizes all the appointments and fills the plannings (agendas) automatically. The operator then validates each appointment, either by confirming it directly or by contacting the customer to finalize the booking.

**Real-time optimization (RTO)**
: An interactive optimization method that offers the operator several suggestions for each appointment. The operator can then choose an option that is perhaps less attractive in terms of price but suits the customer better.

**Re-activate**
: Change the status of an appointment in the planning to **requested**. The appointment can then be re-optimized separately from the planning, using real-time optimization (RTO) or batch optimization.

**Suspended (or unplanned)**
: An appointment status outside the planning. A suspended appointment cannot be re-optimized by RTO or batch optimization until a user re-activates it manually.

**Period of fulfilment**
: The period during which a requested appointment can be planned. It is delimited by a baseline date and a latest date.

**External reference**
: A reference that allows data exchange between databases or through CSV files. You can modify it in the interface.

**Geocoding**
: Associating a geographic position with an address. The process uses a geocoding table and returns a geocoding score.

**Geocoding score**
: The relevance of the X-Y coordinates found. It is evaluated according to two criteria: the geocoding level, and a percentage score that depends on that level.

**Geocoding table**
: A database that contains addresses and points of interest (for example, certain stations, small villages or other points of interest).

**Heuristic**
: A calculation method for finding an optimization solution. In general, the method generates a first solution and calculates its cost. It then calculates a new solution from the first one (for example, by permuting route stops) and calculates its cost. If the new solution costs less than the previous one, it becomes the basis for calculating the next solution. Otherwise, the method keeps the first solution, and so on.
