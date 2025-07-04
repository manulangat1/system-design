**WEB SESSIONS.**

---



* goal is to understand how to maintain state in web applications.
* HTTP is a stateless protocol thus a challenge for user sessions because

Techniques for maintaining state.

---



* Session based auth,  ( server side session storage + cookies for session IDS).
  * Server maintains session state.
  * Client holds only session ID.
  * User logs in -> Server creates a session and assigns a sessionId .
  * Session data is stored on the server side , while session ID is sent to the client.
  * Client stores the sessionId in the cookie.
* Token Based Authentication.
  * Session state is embeded within the token itself.
  * Server does not need to track user sessions.
  * Encodes session data in a self contained token.
  * No need for server side session storage.
  * Used in modern stateless authentication.

Security concerns in Session MGT. 

---

* Session Hijacking. - stolen session IDs.  ( always use https.)
* Cross-Site Request Forgery - Unauthorized actions.
* Secure Cookie Handling: Avoiding theft via Secure, HttpOnly and SameSite flags.

Best practises for Scaling Session MGT. 

---

1. Sticky sessions vs Distributed Sessions.
2. Storing session data in redis, memchached.
3. Stateless authentication ( JWTS ) for scalability.
