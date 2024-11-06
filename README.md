# modelling-assignment-on-state-diagrams

Gishushu Traffic Lights Functional Specification.

The Gishushu Traffic Lights system is designed to manage traffic at a busy intersection. The system has four main directions:

North-South and South-North directions.

East-West and West-East directions.

The system includes vehicle traffic lights and pedestrian signals to regulate safe movement across the intersection.

Operational Phases

The traffic light system operates in cycles, with each cycle consisting of several phases:

Phase 1 (North-South Green):

Objective: Allow vehicles to travel freely from North to South and vice versa.
Signal States:

North-South: Green

East-West: Red

Pedestrian: Red (Do Not Cross)

Transition: After a specified time, the system transitions to Phase 2.

Phase 2 (North-South Yellow):

Objective: Allow North-South vehicles to prepare to stop.

Signal States:

North-South: Yellow

East-West: Red

Pedestrian: Red (Do Not Cross)

Transition: After a short delay, the system transitions to Phase 3.

Phase 3 (East-West Green):

Objective: Allow vehicles to travel from East to West and vice versa.

Signal States:

East-West: Green

North-South: Red

Pedestrian: Red (Do Not Cross)

Transition: After a specified time, the system transitions to Phase 4.

Phase 4 (East-West Yellow):

Objective: Allow East-West vehicles to prepare to stop.

Signal States:

East-West: Yellow

North-South: Red

Pedestrian: Red (Do Not Cross)

Transition: After a short delay, the system transitions back to Phase 1 or the Pedestrian Phase if triggered.

Pedestrian Phase:

Objective: Allow pedestrians to cross safely across all directions.

Signal States:

All Vehicle Directions: Red

Pedestrian: Green (Safe to Cross)

Transition: After a specified time, the system returns to Phase 1.
