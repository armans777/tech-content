# Load Balancer

## What is load balancing ?

Load balancing is the efficient distribution of network or application traffic across multiple servers in a server farm. Each load balancer sits between client devices and backend servers, receiving and then distributing incoming requests to any available server capable of fulfilling them.

## A load balancer performs the following functions :

* Distributes client requests or network load efficiently across multiple servers
* Ensures [`high availability`](https://en.wikipedia.org/wiki/High_availability) and reliability by sending requests only to servers that are online.
* Provides the flexibility to add or subtract servers as required.

## Load Balancing Algorithms

* **Round Robin** – Requests are distributed across the group of servers sequentially.
* **Least Connections** – A new request is sent to the server with the fewest current connections to clients. The relative computing capacity of each server is factored into determining which one has the least connections.
* **Least Time** – Sends requests to the server selected by a formula that combines the fastest response time and fewest active connections.
* **Hash** – Distributes requests based on a key you define, such as the client IP address or the request URL.
of loads if the set of upstream servers changes.
* **IP Hash** – The IP address of the client is used to determine which server receives the request.
* **Random with Two Choices** – Picks two servers at random and sends the request to the one that is selected by then applying the Least Connections algorithm.
  
## Benefits of Load Balancing
* Reduced downtime
* Scalable
* Redundancy
* Flexibility
* Efficiency

# Scaling
Scalability is the property of a system to handle a growing amount of work by adding resources to the system.

Resources fall into two broad categories :  horizontal and vertical.

## Horizontal or scale out
Scaling horizontally means adding more nodes to (or removing nodes from) a system, such as adding a new computer to a distributed software application. An example might involve scaling out from one web server to three. High-performance computing applications, such as seismic analysis and biotechnology, scale workloads horizontally to support tasks that once would have required expensive supercomputers. 

## Vertical or scale up

Scaling vertically means adding resources to (or removing resources from) a single node, typically involving the addition of CPUs, memory or storage to a single computer.

## Benefits of scalable systems
A scalable system provides several benefits :

* Highly customizable infrastructure according to specific customer’s needs.
* The flexibility of increasing or decreasing the system power according to the needs of the moment and the customer’s availability.
* Scalability ensures a minimum service level even in case of failure.
  
