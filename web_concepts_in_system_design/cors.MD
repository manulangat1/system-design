CROSS ORIGIN RESOURCE SHARING ( CORS )

---

* Need for CORS:
  * WEb apps rely on APIs hosted on different domains.
* Is a mechanism that allows secure cross origin communication.
* It is server driven this server must explicityly allow  or deny access.

Types of requests. 

---

* Simple requests -> GET, POST without any custom headers.
* Pre flight requests: Needed for PUT, DELETE or custom headers.

Alternatives to CORS & Role of API Gateways 

---

1. Reverse proxy
   * Forwards client request to the BE bu[assing browser CORS restrictions.
2. API Fateway handling CORS:
   * Centralized control of CORS policies for multiple services.

The above help in the sense that: 

    * Reverse proxies handle cross-origin requests internally to avoid CORS issues.

    * API GW enforce CORS policies centrally, ensuring security and consistency.

* Both improve p4mance by reducing unnecessary browser preflight requests.
