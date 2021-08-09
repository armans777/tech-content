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
Scaling is the ability of a system to grow or shrink in size to meet the increasing user requirement. A scalable system has an advantage because it is adaptable to the changing needs or demands of its users. Scaling can be achieved either by adding more resources to the current system, or by adding new systems in the existing one, or by both.


## Horizontal or scale out
Scaling horizontally means adding more nodes to (or removing nodes from) a system, such as adding a new computer to a distributed software application. An example might involve scaling out from one web server to three. High-performance computing applications, such as seismic analysis and biotechnology, scale workloads horizontally to support tasks that once would have required expensive supercomputers. 

## Vertical or scale up

In vertical scaling, we add more new resources to the same system i.e, increase the amount of RAM, CPU, GPU and other resources to meet the increased computing requirement. It is easy to accomplish. It also consumes less power.

But, Vertical Scaling does not make the system fault-tolerant, i.e if we are scaling application running with a single server and if that server goes down, our entire system will go down. Also, it is often limited to the capacity of a single machine i.e, scaling beyond that capacity of a machine often involves downtime.


![scaling img](https://camo.githubusercontent.com/cf9d8d8f0db8275596a3a3cb163783274b66e57f5bbcafa4015f1b6218220b2c/68747470733a2f2f692e737461636b2e696d6775722e636f6d2f4f6e33744f2e706e67)
## Benefits of scalable systems
A scalable system provides several benefits

* Highly customizable infrastructure according to specific customer’s needs.
* The flexibility of increasing or decreasing the system power according to the needs of the moment and the customer’s availability.
* Scalability ensures a minimum service level even in case of failure.
  
