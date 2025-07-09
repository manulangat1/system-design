QUEUES AND MESSAGING DECOUPLING. 

---





Delivery Guarantees. 

---

1. Atleast once -> message is retried until ack thus may lead to duplicates. Consumers must be idempotent.
2. At most once -> Message is only sent once. No retry thus may result in the message loss.
3. Exactly once.
   * Guaranteed delivery without duplicates.
   * Complex and more resource heavy.
   * Kafka supports it under specific constraints.


Common use cases of Messaging Queues. 

---

1. Order processing.
2. Logging & monitoring.
3. Rate Limiting / Traffic shaping.
4. Email / SMS notification systems.
5. ETL pipelines for real time data transformation.

Best practises for using messaging Queues. 

---

1. Use idempotent consumers.
2. Implement dead letter queues.
3. Monitor queue length & processing time.
4. Handle retries & failures gracefully.
5. Choose deleivery guarantee based on need.
6. Secure your message brokers.
