Is a centralized entry point for all API requests  handling authentication, caching , routing and security.

Acts as a reverse proxy between clients and BE servers.
Once a request is sent , the api gateway processes them and forwards them to the correct service. 

**Benefits.** 

1. Security
2. Rate Limiting.
3. Load balancing
4. Caching
5. Requests transformation.
6. Logging & Monitoring.

Caching for p4mance optimization. 

Speeds up API responses by storing freq accessed information. 

Types of Caching 

1. In memory caching ( e.g redis).
2. Response caching ( storing API responses for quick re-use).
3. Edge caching (CDN intergration for global performance boost).

API composition and aggregation. 

1.
