# Coursework Notes
Let's break down and compare the queueing models:

1. M/M/1 (Single Server Queue)
Queue Structure: Single server.

Arrival Process: Poisson process (exponentially distributed interarrival times).

Service Process: Exponentially distributed service times.

Number of Servers (c): 1.

Queue Length: Infinite (customers can queue indefinitely).

Behavior: Customers arrive, queue, and are served one by one. If the server is busy, the customer waits. Performance measures like the average queue length and waiting time are relatively simple to calculate using formulas based on arrival rate (λ) and service rate (μ).

Use case: Systems where a single resource handles tasks sequentially (e.g., a single cashier at a store).

2. M/M/c (Multi-Server Queue)
Queue Structure: Multiple servers.

Arrival Process: Poisson process.

Service Process: Exponentially distributed service times.

Number of Servers (c): Multiple servers, 
𝑐
≥
1
c≥1.

Queue Length: Infinite (customers can queue indefinitely).

Behavior: Customers arrive, and if a server is free, they are immediately served. Otherwise, they wait in the queue until a server becomes available. With more servers, the system can handle higher traffic loads, reducing average waiting times.

Use case: Call centers, hospitals, or banks where multiple agents or resources serve customers simultaneously.

3. M/M/c/c (Loss System)
Queue Structure: Multiple servers.

Arrival Process: Poisson process.

Service Process: Exponentially distributed service times.

Number of Servers (c): Exactly 
𝑐
c servers.

Queue Length: No queue (queue length is 0).

Behavior: If all 
𝑐
c servers are busy, arriving customers are rejected or lost (they don't enter the system or wait). There is no waiting room. This is also called a loss system.

Use case: Telephone networks, emergency services, or systems with no buffer where requests are dropped when resources are occupied.

4. M1+M2/M/c/c (Two-Class Queue with Blocking)
Queue Structure: Multiple servers with blocking.

Arrival Process: Two distinct Poisson arrival processes (for classes M1 and M2).

Service Process: Exponentially distributed service times.

Number of Servers (c): 
𝑐
c servers.

Queue Length: No queue (loss system, same as M/M/c/c).

Behavior: Customers from two different classes arrive with their own arrival rates (say λ1 for M1 and λ2 for M2). If all servers are busy, customers from both classes are blocked (lost). The system prioritizes or balances the two classes based on predefined rules.

Use case: Systems handling two distinct traffic types, such as premium and standard users in a network service. This model can help analyze and manage blocking probabilities for different user classes.

Summary Comparison
Model	      Servers (c)	      Queue Length	        Arrival Process	         Service Process	         Blocking
M/M/1	1	Infinite	Poisson	Exponential	No blocking
M/M/c	c	Infinite	Poisson	Exponential	No blocking
M/M/c/c	c	0 (no queue)	Poisson	Exponential	Customers blocked when all servers busy
M1+M2/M/c/c	c	0 (no queue)	Two Poisson Processes (M1 & M2)	Exponential	Customers blocked when all servers busy; different classes share system





