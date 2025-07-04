**Why is it needed:**

1. High availability- ensures that the system is availbale even under high uptime.
2. Traffic distribution. - distributes traffic through out multiple servers.
3. Prevents overload of a single server.
4. Improved performance -
5. Handles failures gracefully.
6. Supports scalability.

**Types of Load balancing.**

1. Based on type of layer on OSI model.
   1.1 Layer 4 ( Transport layer. ) - make routing decision based on the network level data
   1.2 Layer 7 ( Application layer ) - makes routing decision at the HTTP / HTTPs level. this makes it fast.Inspect actual respect content.
2. Based on the deployment.
   2.1 Hardware load balancers.
   2.2 Software load balancers
   2.3 Cloud based load balancers e.g AWS ALB.

**Load Balancing strategies.**

1. Static load balancing.
   Distributes traffic based on a pre configured set of rules. It is used mainly on where the traffic is predictable.
   **1.1 Round robin.**
   Distributes requests sequentially to every server.
   **1.2 Least trafic.**
   Distributes traffic to the client with the least traffic.
   **1.3 IP hashing.**
   Routes requests based on the clients IP.
2. Dynamic load balancing.
   2.1 Least response time.
   Requests are sent to the server with the least response time.
   2.2 Adaptive load balancing

   uses real time monitoring to make routing decisions.

   2.3 Weighted load balancing.

   Assigns differents weights to server depending on the capacity.
