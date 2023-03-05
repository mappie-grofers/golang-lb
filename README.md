# golang-lb
A lean Golang based Load Balancer

# Overview
Generally, load balancer is a piece of software or hardware that distributes workload among multiple partitions. 
Take microservice domain as an example, a load balancer distributes requests among a cluster of servers. 
There are many load balancing algorithms, such as round-robin, random, hashing, least work, least latency etc.
Here we are introducing a generic load balancer library that aims to improve both throughput and latency of application when system is under load,
prevent cascading failure caused by service degradation. 
