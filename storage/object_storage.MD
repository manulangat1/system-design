OBJECT STORAGE. 

---

* storage arch that manages data as objects, not files or blocks.
* Each obj contains:
  * Data itself.
  * unique identifier.
  * Metadata.

Concepts in object storage. 

---

* Obj is a selc contained unit of data.
* Bucket. -> logical container for storing objects ( like a folder).
* Metadata -> Custom data that describes the object

Important considerations with Object storage. 

---

1. P4mance considerations.

   * Latency - has a higher latency than block / file.
   * Throughput. - Designed for massive parralel access.
   * Consitency - Evential consistency in some platforms e.g s3
   * Access patterns. Suited for write-once, read many workloads.
2. Cost considerations.

   * Storage class tiers. - Standard infrequent access, archive
   * Charges
   * Best practises.
     * Use lifecycle rules for archiving or deltion.
     * Monitor usage and optimize classes.
   *
