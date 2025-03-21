## Ubus  
**Course:** CIE 205 - Data Structures and Algorithms  
**Language:** C++

### Description
Ubus is a simulation project that models the operations of a bus company. It demonstrates the practical use of core data structures such as queues, priority queues, and linked lists in managing a dynamic system. The simulation handles various types of events, including:

- Ready Events (passengers ready to board)
- Cancel Events (passenger cancellation)
- Promote Events (priority upgrades)

The goal is to simulate how passengers are scheduled, assigned to buses, and managed over time using event-driven logic and custom data structures.

### Key Components
- `main.cpp` – Entry point for the simulation
- `Company.*` – Manages overall operations, event processing, and buses
- `Passengers.*` – Stores and processes passenger information
- `Buses.*` – Defines bus behavior and types
- `Event.*`, `ReadyEvent.*`, `CancelEvent.*`, `PromoteEvent.*` – Handle simulation events
- `Time.*` – Manages simulation timing
- `UI.*` – Simple user interface interaction
- `Utilities.*`, `queue.h`, `linkedList.h`, `priority_queue.h` – Custom data structures used internally
- Input/output files:
  - `sample.txt`, `large.txt`, `maxw.txt`, etc. for simulation input
  - `Output.txt` for results

### Features
- Event-driven simulation system
- Custom implementation of data structures
- Dynamic scheduling and passenger management
- Designed for scalability with large datasets

### How to Run
This project was developed using Visual Studio. To run the simulation:

1. Open the `Ubus.vcxproj` file in Visual Studio.
2. Build the project.
3. Provide an input file (e.g., `sample.txt`).
4. Run the program and check the `Output.txt` for results.
