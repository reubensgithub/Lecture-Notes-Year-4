# Discrete-Event Simulation
### Objectives of this Session
- Priciple of Discrete-Event Simulation (DES)
- Time-advance mechanism in DES
- Components and organisation of DES
- DES method for single-server queueing systems

### Definition of DES
- Discrete-Event simulation: modeling of a system as it 
  evolves over time and the system state changes instantaneously
  at a discrete set of points in time.

### The basic idea:
- Only events can change the system state when they occur at a countable
number of points in time.

Event:
- An instantaneous occurrence that may change the state of the system.
- e.g., arrival or departure of a customer to or from the queue.

### Fixed-Increment Time-Advance Approach
- The step, t, is fixed regardless of the actual time of events.
- If one or more events occurred during a step, these events are considered
to occur at the end of this step.

Advantage: Very simple! Can be very efficient when used in right case.
E.g., ATM (Asynchronous transfer model) networks (cell size is fixed to 53 bytes)
Problem: How big should t be?

### Next-Event Time-Advance Approach:
![Next-Event Time Advance Approach](Next-Event-Time-Advance-Approach.jpg)

### Summary of System Description
**Events**:
- Arrival of a customer
- Departure of a customer (after service completion)
**State variables of interest**
- Expected average delay in queue
𝑑(𝑛) = 
- Expected average number of customers in the queue
𝑞(𝑛) =
- Expected server utilisation
𝑢(𝑛) = 

--- IMAGE NOT WORKING. HOST ONLINE AND USE LINK
--- LOOK UP VIDEOS ON COMPUTER MODELING AND SIMULATION


# Implementation of A Single-Server Queueing System Simulator
### Design of an M/M/1 Simulator
--- watch vids on this
