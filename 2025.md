# Interview Questions

<details> 
<summary>Naggaro</summary>
<br>

> Round - 1

- GCP
  - compute engine vs app engine in gcp?
- Docker
  - docker vs VM ? explain in detail ?
  - docker deamon vs docker client?
- Java
  - shallow copy vs deep copy ?
  - how deep copy works in nested objects ?
  - java-8, default and static methods whats the advantage? 
  - executor service framework, how does it work and benefit?
- Spring
  - dependency injection ? types ? which is preferred ? 
  - problem with setter based injection ? -- reflection slows down the performance
  - how spring-data jpa is different from jpa and hibernate?  
  - does spring-data jpa uses hibernate internally?
- Database
  - how many tables do you need for many to many relationship?

> Round - 2
- Java
  - Why java-8 is functional programming ?
  - What are Method References ?
  - What is different in terms of memory model in java-17 ? which GC is used ?
- Spring
  - ** Explain setter based vs constructor based injection, use case with example ?
  - ** In case there are two beans needs to be initialized, A and B, if A is not initialized and B wants to access,
  How can you initialize Bean A --> SETTER BASED, ANY OTHER WAYS
  - How to create custom endpoint for actuator and how to count exceptions ?
  - How to resolve circular dependencies in spring boot ?
  - How to achieve fault tolerance without using spring-boot ?
  - Alternative to saga patterns ?
  - Consistency level in saga patterns ?
  - Explain Authentication & Authorization ? How to achieve it ?
- Microservices
  - Tell me all the Microservices Patterns ?
  - How to implement fault tolerance in mircoservices ?
  - What are non-functional requirements in microservices ?
  - How to secure mircoservices ?
- Docker
  - How to create image using docker ?
  - What are the commands used inside Dockerfile ?
- Kubernets
  - Auto-scaling in gcp or kubernetes ?
  - What is bestway to deploy all the services at once ? -- Kubernetes

> Round 3
- Java
  - Optimistic vs Pesimisstic Locking ?
  - Give me a scenario where you encountered threading issue and how you fixed it ?
- Program
  - Program to query department based maximum average salary ?
  - Program to order the strings based on the length ?
- Spring
  - Between two apps, App A uses one of the component of App B as library, It is throwing exception stating bean is not initialized, how to fix it ?
  - How would you rollback transactions in services ?
- Microservices
  - What is blue / green deployment ?
  - service mesh and its implementation with example ?
  - Difference between gateway and ingress ?
  - Explain cqrs pattern ? problems ?
- Kubernets
  - How kubernetes implements blue / green deployment ?

</details>

<details> 
<summary>Verint</summary>
<br>

> Round - 1
- what is CQRS pattern ?
- redis cache usage ?
- completeble future and its methods ? specially for async and sync calls ?
- spring-data starter required ? whats the use ?
- spring entity life cycle ? **
- Loan Delivery System: Design a Loan Origination Platform using OOPs concepts - Factory for Loan Type, Strategy for Interest Calculation, Observer for Notifications.
- Interface based implmentation

</details>

<details> 
<summary>Cashfree Payments</summary>
<br>

> Round - 1
- handle exceptions in micro-services ?
- handle exceptions for async calls ?
- Implement rate-limiting ? Types ? which one have you used [spring gateway ratelimiter]
- How to bypass rate-limiter ?
- Distributed transactions without 2PC ?
- How to perform database migration ?
- How to deploy database migration without downtime ?
- How to test micro-services ? All test types
- Debug production issues ? How to address quickly ? Quality vs Quick fix
- tell all the isolation level for transactions ?
- which all isolation level will get deadlocks ?

</details>

<details> 
<summary>Nextiva</summary>
<br>

> Round 1
- Explain stateful management ? example ?
- How to manage requests if increase from 10K to 10M ?
- ordering in kafka partitions ?
- where do you stored failed records in kafka ? 
- spring-batch is different from normal scheduler ?
- Program for removing adjescent duplicate elements in string ? -- Stack + StringBuiler
- Bus Booking System ?

</details>

<details> 
<summary>Best Buy</summary>
<br>

> Round 2
- scope of beans and which one to use for parameters
- rate limiter, where it is used with scenario  
- microservice issue w.r.t circular dependencies
- how does spring as framework handles millions of requests
- when to use service mesh, explain one scenario
- program from hacker rank site

</details>

<details> 
<summary>JP Morgan Chase</summary>
<br>

> Round 1
- mircoservices patterns
- how to secure the application, all security ways
- program for skipping one value and updating another value of map

</details>

