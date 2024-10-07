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

