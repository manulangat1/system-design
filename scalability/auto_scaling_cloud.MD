AUTO SCALING & BEST PRACTISES. 

---

* Is the automatic adjustment of compute resources based on load.
* Ensures p4mance, availability and cost efficiency.
* Common in microservices, web apps and event driven systems.

How it works: 

---

* Triggers:
  * CPU usage.
  * Memory.
  * Request rate.
  * Queue legnth
* Types.
  * Horizontal scaling.
  * Vertical scaling.
* Scaling policies:
  * Reactive: based on certain thresholds.
  * Predictive . based on the recent trends.


Monitoring and Proactive scaling. 

---

* Use metrics such as :

  * CPU, memore , network
  * Queue depth, custom KPIs.
* Proactive scaling.

  * Predictive algorithms ( based on ML or trends)
  * Scheduled scaling
* Tools e.g cloud watch, Prometheus + Grafana, Azure monitor, GCP operations. 

Cost optimization stategies : 

---

* Avoid over provinsioning
* Use spot . pre empitable instances for batch workload.s.
* Apply resoiurce limits & quotas.
  Right size regularly based on actiual usage.
* Use autopausing or scale to zero features for idle  services.
