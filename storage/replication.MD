REPLICATION. 

---

* Copying data from one database node to another for redundancy and p4mance.

Benefits of Replication. 

---

* Fault tolerance.
* Read p4mance improvement.
* Data availability.

Tradeoffs in real world systems ( CAP theorem). 

---

* Replication may favour availability.
* Strong consistency may favour availability.

Leader - Follower Replication. 

---

* Writes go to the leader.
* Reads from Followers.

---

Read Replicas. 

* Scaling read heavy workloads.
* Diff in leader - follower.
  * Ofthern used for load balancing reads.
  * Doesn't take part in writes.
*
