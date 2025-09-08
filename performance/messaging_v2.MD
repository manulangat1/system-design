Why use async messaging:

1. Loose coupling -> Decouple producers from consumers.
2. Improved p4mance. Producers dont block waiting for consumers.
3. Scalability: Consumers can scale independently.
4. Resilience. Message durability adds fault tolerance.
5. Flexibility: Easily add new consumers without chaning producers.

Key concepts of Messaging systems. 

1. Message - data packet sent from producer to consumer.
2. Producer - sends the message.
3. Consumer - Receives and process the message.
4. Broker / Queue - Stores and delivers the messages.
5. Topic / Queue - Logical channel for message delivery.
6. Ack. -> Acknowledgement of successful processing.


When to use Queues in Architecture. 

1. When workloads are busty.
2. When you need decoupling btwn services.
3. For background jobs ( e.g email, processing, exports)
4. For rate limited or expensive ops.
5. To buffer spikes in traffic.

Popular message brokers:

1. Rabbitmq.
   ---------


   - Built on AMQP. - designed for reliable message delivery.
   - Follows a push based model.
   - Supports ack, retries and dead letter queues.
   - Great for task distribution, bg jobs and real time notificaitons.
   - Focuses on routing flexibility.
   - Messages are removed after consumption.
2. Kafka.

   - Built for high through put, durable  , distibuted event logs.
   - Uses a pull based model - consumers read at their own pace.
   - Stores messages in partitioned logs ( supports message replay)
   - Ideal for event sourcing, real time analytics and stream processing.
   - Highly scalable and fault tolerant.
   - Messages are retained for configurable durations ( even after consumption)

Delivery Guanrantees.

1. At least once ( default in many systems).
   -----------------------------------------


   - Message is retried until ack.
   - May lead to duplicates.
   - Consumers must be idempotent.
2. At most once.

   - Messages are sent only once.
   - No retries -> may result in message loss.
3. Exactly once .

   * Guaranteed single delivert without duplicates.
   * Complex and more resource heavy.
   * Kafka supports it under specific constratints.

Best practises for using messaging queues:

1. Use idempotent consumers.
2. Implement dead letter queues.
3. Monitor queue legnth & processing time.
4. Handle retries and failures gracefully.
5. Choose delivery semantics based on need.
6. Secure your message brokers ( auth, encryption etc)
