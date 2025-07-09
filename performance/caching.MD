CACHING. 

---

* Why it matters:
  1. Reduces latency  by avoiding expensive computation  or data retrievals.
  2. Eases load on BE servecies.
  3. Improving UX and scalability.
  4. Critical in low latency high throughput systems.

Types of Caching.

---

1. Client based caching
2. Server Side based caching.
3. CDN caching
4. Database caching

Caching strategies. 

---

1. Write through - data is written first to the cache and DB simultenously.
2. Write back (write behind) - data is written to the cache , Db is updated asynchronously.
3. Lazy loading. ( Cache aside) - cache is populated by demand.
4. Explicit / manual caching - dev decides when to cache or evict.

Cache eviction policies. 

---

1. Least recently used.
2. Least frequently used
3. FiFO - first in first out.
4. TTL - set explicit time for the cache to live.
