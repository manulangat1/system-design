**Sharding.**

---

* Splitting data across multiple databases to scale horizontally.
* Needed becases of p4mance and storage limits of a single node.
* Types of Sharding.
  * Horizontal sharding. - Rows are distibuted across shards (most common.)
  * Vertical sharding - tables or columns are split across shards based on function or access pattern.

**Sharding strategies.** 

---

1. Range based sharding.
   * Split by value ranges
   * Can create hot spots.
2. Hash based sharding.
   * Distribute using a hash function.
   * Even distribution but harder to query ranges.
3. Consistent hashing for resilient hash based sharding.
   * Trad hashing breaks when nodes are added / removed.
   * Only a subset of keys neeed to be re-mapped when toplogy changes.
   * Enables better elasticity and fault tolerance.
4. Geo based sharding.
   * Shard by user region / location.
   * Usedul in geo-distributed systems.

**Polyglot persistence.** 

---

* Using diff types of databases for diff components/services.
* Benefits include:
  * Better p4mance.
  * Optimized storage and queries.
*
