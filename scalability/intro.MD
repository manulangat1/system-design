SCALABILITY 

---

* Is the ability of a system to handle an increasing amount of work , or its potentional to accomodate growth.
* Ensures p4mance , reliability , and availability unser growing load.

Why do systems need to scale. 

---

* User base growth.
* Increased data volume.
* Peak events e.g black friday.
* Avoid service degradation or downtime.
* Meet performance SLA's.

Types of scalability strategies. 

---

1. Vertical scaling.
   * Adds more CPS/RAM to one server.
   * Easy to implement.
   * Limits -> Physical cap, rik of SPF.
2. Horizontal Scaling.
   * Add more servers to distribute the load.
   * Requires load balancer, stateless design.
   * Complex set up ( coordination, replication)
3. Diagonal.
   * Start verical then go horizontal.
   * Common in cloud native apps.
   * Cost effective + long term ready.


Common challenges in scaling. 

---

1. Latency.
   * Delay btwn res and req.
2. Bottlenecks.
3. Downtime
4. Cost
