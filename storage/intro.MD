Categories of storage 

---

* Database storage.
* Object storage.
* File storage.
* Block storage.


Storage Properties. 

---

* Durability.  persists even after failures.
* Availability
* Consistency
* (Optional) Atomicity - ops are either all or nothing.
* Isolation - transactions do not affect each other.


Trade offs in storage design. 

---

* Scalability vs Reliability vs Performance.

THE CAP THEOREM. 

---

* In any distributed system, you can only guarantee 2 of the 3
  * Consistency. - All clients see the same view of data, even right after update or delete.
  * Availability. Every req recieves a res even in case of partial node failures.
  * Partition tolerance. ( System continues despite network failures.)

Types of systems based on CAP trade offs. 

---



1. Consistency + Partition.
2. Availability + Partition.
3. Consistency + Availability.


---
