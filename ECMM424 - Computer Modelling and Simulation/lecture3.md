# Multi-Server System Simulation

## Markov Chain Formulation

**N(t):** the number of customers in the system at time t.
- The system is at State n if N(t) = n

Exponentially distributed "M" --> memoryless property --> N(t) is
a continuous time Markov chain (CTMC) with state space 0,1, ...

## Multi-Server Example:
**Rules:**
- If both cashiers are idle, cashier 1 gets the customer.
- If cashier 1 is not idle but cashier 2 is, the customer begins
service with cashier 2.
- If both are busy, the customer waits in the queue and begins
service with the first free server.

**Events:**
- A customer arrives.
- A customer completes service from cashier 1.
- A customer completes service from cashier 2.



# Multi-Server Loss System Simulation
M/M/C/C is an M/M/C model with a maximum of C customers/jobs allowed in the system.
- Capacity of the system is limited and equal to the number of servers.
- There are no waiting positions in the queue.
- If the system is full when a job arrives it is denied entrance to the system and is lost.
- Also known as m-Server Loss Systems.

