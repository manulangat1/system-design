RELIABILITY.

* Why it matters:

  * Users expect systems to be always available, consistent, trustworthy.
  * Downtime costs money, reputation and user trust.
  * High reliability = low failure + fast recovery.
* Is the ability of a system to operate continuosly without failure.
* It includes:

  * Correctness
  * Consistency
  * Fault tolerance.
  * Uptime.

Key metrics.

---

1. MTBF - mean time btwn failures
2. MTTR - mean time to recovery.

Impact of reliability on system design.

---

1. Redudancy
2. Health checks and monitoring.
3. Retry mechanisms and circuit breakers.
4. Distributed design patterns. ( replication, quorum)

Reliability challenges in distributed systems.

---

1. Network partitions.
2. Node failures.
3. Eventual consistency.

Solution to reliability challenfes in system design.

---

1. Use CAP- aware design.
2. Ensure fault isolaton.
3. Implement replication ^ consus alogrithms.


Reliability in cloud native systems. 

---

* Design for :
  * Transcient failures.
  * Auto scaling and self healing.
  * Chaos engineering to test resilience.
