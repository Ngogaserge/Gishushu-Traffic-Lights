
# Gishushu Traffic Lights Control System

This README describes the traffic light control system for the Gishushu intersection in Kigali, Rwanda, providing an overview of the traffic flow, sequence of traffic phases, and detailed descriptions of each state.

## Overview

The Gishushu intersection handles traffic for multiple key routes, allowing controlled access to ensure smooth flow between these directions:
- **Remera ↔ Kacyiru**
- **Remera ↔ Nyarutarama**
- **Nyarutarama ↔ Kacyiru**
- **Nyarutarama ↔ Sonatube**
- **Remera ↔ Sonatube**

Each phase in the traffic light system is designed to optimize movement for a specific pair of directions, with yellow phases in between to ensure safe transitions. Additionally, an "all red" phase is included periodically to allow pedestrians to cross safely.

## Traffic Light Phases

Below is a detailed description of each phase in the traffic sequence, including green light directions, yellow light transitions, and pedestrian crossing phases.

### Phase 1: Remera ↔ Kacyiru Green
- **Active Directions**: Remera to Kacyiru and Kacyiru to Remera
- **Description**: This phase opens the North-South corridor, allowing traffic flow between Remera and Kacyiru. By prioritizing this high-traffic route, congestion along the main corridor is alleviated.
- **Yellow Transition**: After the green phase, a brief yellow light signals the end of this direction, warning vehicles to prepare to stop.
- **Red Directions**: All other directions (Remera to Nyarutarama, Nyarutarama to Sonatube, etc.) remain red.

### Phase 2: Remera to Nyarutarama Green
- **Active Direction**: Remera to Nyarutarama
- **Description**: This phase allows traffic to flow from Remera to Nyarutarama, facilitating movement toward the eastern side of the intersection. This reduces congestion on the main Remera-Kacyiru route by providing an alternate exit.
- **Yellow Transition**: A yellow light is shown at the end of this phase, ensuring vehicles clear the intersection safely.
- **Red Directions**: All other directions are red.

### Phase 3: Nyarutarama to Kacyiru & Nyarutarama to Sonatube Green
- **Active Directions**: Nyarutarama to Kacyiru and Nyarutarama to Sonatube
- **Description**: Traffic flows from Nyarutarama to both Kacyiru and Sonatube, allowing East-West traffic flow while relieving congestion from Nyarutarama. This phase helps distribute traffic away from the primary Remera-Kacyiru route.
- **Yellow Transition**: A yellow phase signals the end, alerting vehicles to prepare to stop.
- **Red Directions**: All other directions remain red.

### Phase 4: Kacyiru to Nyarutarama & Remera to Sonatube Green
- **Active Directions**: Kacyiru to Nyarutarama and Remera to Sonatube
- **Description**: This phase allows movement from Kacyiru to Nyarutarama and Remera to Sonatube. By opening routes toward Sonatube, this phase helps disperse traffic from the central Kacyiru and Remera areas, distributing vehicles across multiple exit points.
- **Yellow Transition**: A yellow light indicates the end of this green phase.
- **Red Directions**: All other directions remain red.

### Phase 5: All Red (Pedestrian Crossing)
- **Active**: All directions are red
- **Description**: During this phase, all vehicular traffic is stopped, allowing pedestrians to cross safely across the intersection. This phase is included periodically within the sequence to ensure pedestrian access without significantly impacting vehicle flow.
- **Transition**: After a set period, the system moves back to Phase 1 (Remera ↔ Kacyiru Green), resuming the vehicle cycle.

## Timing Logic

The traffic light system operates based on a timer for each phase:
- **Green Light Duration**: Each green phase lasts a pre-determined amount of time, sufficient to allow vehicles to pass through the intersection.
- **Yellow Light Duration**: After each green phase, a short yellow light phase signals the end, giving vehicles time to clear the intersection before the next red light.
- **Pedestrian Crossing Duration**: The "All Red" phase is timed to allow pedestrians to cross safely without rushing, then reverts to the main traffic flow.

## Emergency and Manual Override

- **Emergency Mode**: The traffic light system includes an override option for emergency vehicles, allowing them to prioritize their route through the intersection.
- **Manual Control**: Traffic controllers can adjust the sequence manually if necessary, such as during peak traffic hours or events, ensuring adaptable control.
