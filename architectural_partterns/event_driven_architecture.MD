EVENT DRIVEN ARCHITECTURES. 

* Is a system design pattern where components interact though events instead of direct calls.

Key  x-tics. 

* Async processing.
* Promote loose coupling.
* Enhance Scalability & flexibility

Why use it:

* Enhances system responsiveness.
* Enables real time event processing.
* Supports complex workflows.

---

Pub-Sub vs Event streaming. 

* Pub sub model.

  * Events are broadcasted to multiple subscribers.
  * Each subscriber gets the events once.
  * Examples include RabbitMQ, AWS SNS e.t.c
* Event streaming.

  * Events are stored and consumed in order.
  * Consumers process events at different times.
  * Example include Kafka, AWS Kinesis

---

Key components of an Event driven system. 

* Event producers ( Generate events)
* Event brokers ( Transmit & store events)
* Event consumers ( React to events)
* Event storage( log based persistence for replaying events)

---

Challenges in EDA. 

* Eventual consistency. - no immediate data syncronization.
* Ordering guarantees ( ensuring events are processed in sequence)
* Fault tolerance & retries ( Handling failures gracefully)
* Debugging complexity (Tracing events across microservices)

---

Best cases in an EDA. 

- Use idempotent event processing to avoid duplicates.
- Implement dead-letter queues for failed messages.
- Choose the right event broker based on system needs.
- Ensure event versioning to handle schema changes.

---



Use cases of EDA. 

* Logging & Auditing ( track changes over time.)
* Real time notifications.
* Microservices decoupling (independent scalability & fault tolerance )
* IoT system ( sensor data processing )
* Ecom  order processing.
