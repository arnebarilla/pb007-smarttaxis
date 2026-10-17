# SmartTaxIS – Information System for an Autonomous Electric Taxi Service

University project (Software Engineering, autumn 2026)
focused on the analysis and design of an information system using UML.

## System description

SmartTaxIS manages a fleet of fully autonomous electric taxis. It covers the
whole lifecycle of a ride – from a customer searching for a car, through
automatic vehicle selection, navigation and payment, to battery charging and
parking when the vehicle is idle.

Key capabilities:

- **Online ordering** – registered customers enter pickup point, destination,
  time and number of passengers; the system selects the best available vehicle
  based on distance, battery level and recent workload.
- **Premium membership** – monthly or annual subscription with a 20 % discount,
  multiple ride offers and the ability to request specific car equipment
  (e.g. entertainment system, child seat).
- **Autonomous navigation** – routes are computed from live traffic data and
  sent to the vehicle as a sequence of waypoints; vehicles report their
  position every second and incidents are escalated to a human operator.
- **Fleet energy management** – vehicles are automatically routed to charging
  stations when the battery drops below 40 % and to reserved parking spots
  when idle.
- **Payments** – rides, cancellation fees and subscriptions are processed
  through an external payment provider using stored payment cards.
- **Administration** – managers maintain employees, vehicles, charging
  stations and parking spots and view operational statistics.

## Project structure

The repository holds the UML model of the system. Each diagram captures a
different view of how SmartTaxIS is expected to behave.

| Diagram | Description |
|---|---|
| Use case diagram | Actors (customers, premium members, operators, managers, external services) and their functionality |
| Analysis class diagram | Domain entities such as Vehicle, Order, Route and Payment and their relationships |
| Activity / sequence diagrams | Key scenarios – placing an order, passenger pickup, battery charging |

The model was created in [Visual Paradigm](https://www.visual-paradigm.com/).

## Authors

- Arne Barilla
- Filip Guoth
- Martin Pšeja