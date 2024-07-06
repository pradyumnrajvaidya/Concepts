# **SCALING**

## Table of Contents

- [What is database scaling?](#what-is-database-scaling)

- [What is vertical and horizontal scaling?](#what-is-vertical-and-horizontal-scaling)

- [How to increase database performance and make it more scalable?](#how-to-increase-database-performance-and-make-it-more-scalable)

- [What is replication?](#what-is-replication)

- [What is Cloud Scalability?](#what-is-cloud-scalability)

- [Why is Cloud Scalable?](#why-is-cloud-scalable)

- [What is Amazon Web Services (AWS)?](#what-is-amazon-web-services-aws)

- [What is Load Balancing](#what-is-load-balancing)

- [refrences](#refrences)

## What is database scaling?

- **Database Scalability** is the ability to increase or expand the capacity of database or system resource in order to enhance the performance of usage of your application.
- The CPU and/or memory becomes overloaded, and the database server either cannot respond to all the request throughput or do so in a reasonable amount of time. Your network interface is overloaded, so it cannot support all the network traffic received
- In todays's world, The usage of online websites and apllications is increasing day by day and a lot of companies faces the scalability issues. companies spend a large amount of money for horizontal and vertical scaling.

## What is vertical and horizontal scaling?

Vertical scaling refers to increasing the processing power of a single server or cluster. Both relational and non-relational databases can scale up, but eventually, there will be a limit in terms of maximum processing power and throughput. Horizontal scaling, also known as scale-out, refers to bringing on additional nodes to share the load.

MongoDB Atlas makes it simple to vertically or horizontally scale up or down as needed. You can even enable auto-scaling so your available resources always meet your needs.

## How to increase database performance and make it more scalable?

There are so many ways to increase database performance like - vertical scaling and horizontal scaling etc. There are a variety of scaling techniques that depend on the database system and what components are used. However, they all use the concept of a node, which is an individual machine storing some or all of the data. A group of nodes that work together is called a cluster.

There are two commonly used horizontal database scaling techniques: replication and horizontal partitioning (or sharding). MongoDB is a modern, document-based database that supports both of these.

## What is Replication ?

 Replication means that make a copy of database Replication refers to creating copies of a database or database node. Replication adds fault tolerance to a system. Each node in a cluster contains a copy of the data. If one of the nodes goes down, the cluster is still able to serve client requests because the other nodes in the cluster can respond to the requests.

- Replication is also a form of scaling because client requests can be spread across all the nodes in the cluster instead of overwhelming a single node. This increases the capacity of the system to handle more database read requests.

![P2P](https://webimages.mongodb.com/_com_assets/cms/lly2dso5vg9pytd6i-image5.jpg?auto=format%252Ccompress)

## What is Cloud Scalability?

 Cloud scalability in cloud computing refers to the ability to increase or decrease IT resources as needed to meet changing demand. Scalability is one of the hallmarks of the cloud and the primary driver of its exploding popularity with businesses.

- Elasticity refers to a system’s ability to grow or shrink dynamically in response to changing workload demands, like a sudden spike in web traffic. An elastic system automatically adapts to match resources with demand as closely as possible, in real time. A business that experiences variable and unpredictable workloads might seek an elastic solution in the public cloud.

## Why is Cloud Scalable ?

- A scalable cloud architecture is made possible through virtualization. Unlike physical machines whose resources and performance are relatively set, virtual machines virtual machines (VMs) are highly flexible and can be easily scaled up or down. They can be moved to a different server or hosted on multiple servers at once; workloads and applications can be shifted to larger VMs as needed.

- Third-party cloud providers also have all the vast hardware and software resources already in place to allow for rapid scaling that an individual business could not achieve cost-effectively on its own.

## What is Amazon Web Services (AWS)?

- This is the basic structure of AWS EC2, where EC2 stands for Elastic Compute Cloud. EC2 allow users to use virtual machines of different configurations as per their requirement. It allows various configuration options, mapping of individual server, various pricing options, etc. We will discuss these in detail in AWS Products section. Following is the diagrammatic representation of the architecture.

![P2P](https://www.tutorialspoint.com/amazon_web_services/images/architecture.jpg)

## What is load balancing?

**Load balancing** simply means to hardware or software load over web servers, that improver's the efficiency of the server as well as the application. Following is the diagrammatic representation of AWS architecture with load balancing.

Hardware load balancer is a very common network appliance used in traditional web application architectures.

AWS provides the Elastic Load Balancing service, it distributes the traffic to EC2 instances across multiple available sources, and dynamic addition and removal of Amazon EC2 hosts from the load-balancing rotation.

Elastic Load Balancing can dynamically grow and shrink the load-balancing capacity to adjust to traffic demands and also support sticky sessions to address more advanced routing needs.

## Refrences

- <https://www.mongodb.com/resources/basics/scaling>

- <https://www.vmware.com/topics/glossary/content/cloud-scalability.html>

- <https://www.tutorialspoint.com/amazon_web_services/amazon_web_services_basic_architecture.htm>
