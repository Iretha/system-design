---
layout: default
title: Introduction
nav_order: 0
description: "Improve your System Design skills to create better software"
permalink: /
---

# System Design
{: .fs-9 }

TODO 
{: .fs-6 .fw-300 }

[Get started now](#){: .btn .btn-primary .fs-5 .mb-4 .mb-md-0 .mr-2 } [View examples on GitHub](https://github.com/Iretha/system-design){: .btn .fs-5 .mb-4 .mb-md-0 }

---

TODO Description 

## System Design Topics

### Key Metrics

- Throughput
- Latency
- etc

## Key Technologies

### Protocols
### Databases


## Scaling Techniques

### What is scaling? Horizontal vs Vertical?

### Caching

### Load Balancing

### Queues

### DB Scaling
- Database caching?
- Database replication
- Database partitioning
- Database sharding
- Database federation


## How to approach a system design task?

### Identify scope & constraints

#### Identify System Scope

This section is more about FR (Functional Requirements). Ask questions like:
- What system should do?
- Who is going to use it?
- How is going to use it?

    > Such questions will help us to identify the scope and what components do we need.

#### Identify Constraints & Limitations

This section is more about NFR (Non-functional Requirements). We need to identify the scale of the system in terms of data storage, network traffic, operations per second etc. Ask questions to identify:
- Expected Network Traffic 
- Expected Requests per Second
- Expected Reads & Writes per second
- Expected Users
- Expected Storage Space
- Specific requirements (like multi-threading, etc)

    > Such questions will help us to identify possible bottlenecks and how system should scale.

### Start with abstract design (high level architecture) and improve on the go
1. Identify layers
   1. Mobile app/ Web app (Entry Points/ User Apps)
   2. Application/ Service Layer (APIs)
   3. Data Storage Layer (DB)
2. Identify components like:
   1. Users (User API)
   2. Payments (Payment API)
   3. etc
3. Identify communication between layers/ components
   1. Directions
   2. Protocols
4. Identify & Handle Bottlenecks
   1. Identify possible bottlenecks
   2. Suggest techniques to handle them
   3. Compare suggested techniques (Pros & Cons)
5. Improve design to handle bottlenecks
   1. Caching
   2. Load balancing
   3. Queues
   4. Partitioning/ Sharding
   5. Geo Location
   6. etc

### Continue with detailed component design (low-level design) if expected
1. Identify Specific APIs
2. Model Specific DB Schema
3. Solve specific problems (if required)

## System Design Tasks




