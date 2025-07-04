SERIALIZATION.

---

* Apps need to exchange and store structured data efficiently.
* Serialization converts complex objects into a format that can be easil transferred.
* Used in APIS.

Common Serialization Formats 

---

* JSON

  * Human readable , widely used in REST APIS>
  * Simple ket-value structure , easy to parse.
  * Test based so larger in size compared to binary formants.
* XML

  * Tag based markup language used in legace systems & configuration files.
  * Suppoerts rich data structures.
  * Verbose leading to larger payloads.
* Protocal Buffers ( Protobuf) - compact & efficient used in hRPC.

  * Binary format developed by Google.
  * Faster & smaller than JSON/ CML but requires schema definiction.
  * Used in gRPC for high performance APIS.

Trade Offs : Readibility vs Efficiencu vs Compatibiliyu. 

---

* Readibility : JSON & XML are human readable but inefficient.
* Efficiency : Protobuf & Avro are compact , reducing bandwidth usage.
* Compatibiliy: XML support schema evolution, JSON has limited support.
