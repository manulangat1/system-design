DB Optimization techniques. 

---

Replication. 

---

* Is the process of copying and maintaining database objects in multiple databases.
* Why do we need replication:
  1. High availability. - ensure data is available in case of failure.
  2. Load balancing - distribute read traffic across multiple servers.
  3. Disaster recovery - Maintain copies of data across diff locations.
* Types of replication:
  1. Master-slace replication -> One primary DB , multiple replicas for reads.
  2. Master - Master replication: Multiple primary databases, of used for writes and redudancy.
*
