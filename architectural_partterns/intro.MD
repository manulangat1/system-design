    **INTRODUCTION**

---



* System architecture - structure of a system and how they interact with each other.
* Impacts on scalability, performance and maintainability.
* N/B keep in mind the architectural choices you make directly influences system behaviour.

    **FACTORS INFLUENCING ARCHITECTURE SELECTION**

***

* Business needs.
* Scalability.
* P4mance.
* Maintainability.

    **SOFTWARE ARCHITECTURE PATTERNS AND STYLES**

---



* Software architecture is the high level structure of a software system, defining components, their relationshis and the way they interact.
  Common architectural styles include:
  1. Monolith. - Entire system is build as a single unified block.
     * A single unified system where all components are tightly coupled and work as a single unit.
       Pros:
       * Simple to develop and debug.
       * Easier to manage in smaller applications.
     * Cons
       * Hard to scale.
       * Difficult to maintain as the codebase grows.
       * High risk of failure e.g a single bug can take down the entire system.
  2. Layered (N- tier ). - Separates system into different layers e.g auth layer, system layer e.t.c  P4mance issues due to
     * A system is splint into multiple layers e.g Presentation, Business Logic and Data) to separate concerns.
     * Pros:

       * Clear separation of concerns.
       * Easier to scale and maintain compared to monolithic.
     * Cons:

       * P4mance overhead due to the layers.
       * May result in tight coupling between certain layers.
     * Used mainly in enterprise applications, CRM systems and banking applications.
  3. Client - Server. - Distinction btwn clients that make the req and servers that processes the request.
     * Hi
  4. Microservices. - smaller independent services that communicate with each other.
     * System is built as a collection of small, independent services, each focused on a specific business capacity.
     * Pros:
       * Independent services can be scaled, deployed and developed separately.
       * Flexibility in technology for each service.
       * Better fault tolerance.
     * Cons:
       * Increased complexity in communication and coordination.
       * Need for robust DevOps and Automation pipelines.
     * UseCases - LargeScale applications, ecom platforms , modern cloud based systems.
  5. Event driven systems. - system reacts to events.
     * A system where components communicate though events instead of direct calls, enabling loose coupling.
     * Pros:
       * Highly decoupled architecture.
       * Excellent for handling async workflows.
       * Better scalability for high traffic systems.
     * Cons:
       * Debugging and tracing becomes more difficult.
       * Difficult to ensure data consistency across services.
     * Use cases: Real time systems, IoT apps, financial trading platforms.
