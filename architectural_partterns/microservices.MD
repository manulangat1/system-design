**MICROSERVICES ARCHITECTURE** 

---



A software design pattern whrre apps are structured as a collection of small, loosely coupled services, each responsible for a specific function.

x- tics:

* Independently deployable services.
* Loosely coupled & modular.
* Scalable & fault tolerant.

---

Indentifying and structuring Microservices. 

* Business capabilities.
* Single Responsibility Principle.
* Data Ownership. - avoid shared databases.
* Independently ownable.

How to structure Microservices: 

1. Decompose by business domain.
2. Define clear APIs.
3. Choose the right granularity.
4. Implement observability.

---

Communication in Microservices

1. Synchronous Communication.
   --------------------------

   * Await a response before proceeding.
   * Types:
     * Rest API's
     * gRPC - uses binary format and better p4mance.
2. Async Communication.
   * Event driven messaging.

---

Challenges of Microservices.

1. Data consistency due to distributed databases thus the rise of eventula consistency.
2. Distributed tracing - Difficult to debug and track requests.
3. Network overhead. More API calls thus increased latency.
4. Security. Authentication, authorization and data protection.

---



Scaling strategies in Microservices. 

1. Horizontal scaling. Add more instances of a server.
2. Auto scaling. Scale up/down automatically.
3. Sharding & database scaling - split databases for high traffic services.
