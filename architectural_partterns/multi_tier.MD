**MULTI TIER ARCHITECTURE**

---

* Is a software design parttern that structures applications into multiple layers, each responsible for specific functions. This separation enhances scalability., maintainability, p4mance and security.
* Key points:
  * Organizes apps into independent layers.
  * Separates concerns e.g UI, business logic and data storage.
  * Enhances better scalability, p4mance and security.
  * Used in web apps, enterprise systems and cloud architectures.


**2 TIER ARCHITECTURE.**

---

* Consists of a client layer and a database layer. The client interacts directly with the database. without an intermediate business logic layer.
* How it works:

  * Client layer: UI, application logic.
  * Database layer: stores and retrieves data.
  * Data flows directly between the client and the database.
* Pros:

  * Simple to implement.
  * Fast for small scale applications.
* Cons:

  * Poor scalability.
  * Security risks,  ( direct access to the database)
* Example use case. A desktop app querying an SQL database.


3 TIER ARCHITECTURE. 

---

* Consists of a client layer, business logic layer (server) and a database layer.
* How it works:

  * The frontend interacts with the business layer ( API server)
  * The business logic layer process the req and communicates with the DB layer.
* Pros:

  * Improves scalability and security.
  * Better SOC.
  * Easier maintainance.
* Cons:

  * Slighly higher latency due to extra processing.
* Examples include traditional web applications.

N TIER ARCHITECTURE. 

---

* Extends beyond 3-tier by adding more specialized layers like caching, API gateway, microservices e.t.c
* Why use?
  * Handles high traffic & complex business logic.
  * Allows independent scaling of different services.
* Examples:
  * Microservices based applications.
  * Large scale enterprise applications.

P4mance and Scalability Impacts.
--------------------------------

---

* Latency considerations and its solutions e.g caching , load balancing
* Scaling Strategies.
  * Vertical scaling ( adding resources to a single server)
  * Horizontal scaling ( adding more servers , distributing the load.)
  *
