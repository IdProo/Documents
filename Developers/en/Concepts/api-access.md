Applications have two fundamental ways with which they communicate with APIs - using the application identity, or delegating the user's identity. 
Sometimes both methods need to be combined.
\

**OAuth2** is a protocol that allows applications to request access tokens from a security token service and use them to communicate with APIs.
This delegation reduces complexity in both the client applications as well as the APIs since authentication and authorization can be centralized.
\

### OpenID Connect and OAuth 2.0 - better together
**OpenID Connect** and **OAuth 2.0** are very similar - in fact OpenID Connect is an extension on top of OAuth 2.0.
The two fundamental security concerns, authentication and API access, are combined into a single protocol - often with a single round trip to the security token service.
\

We believe that the combination of **OpenID Connect** and **OAuth 2.0** is the best approach to secure modern applications for the foreseeable future. 
IdAMan is an implementation of these two protocols and is highly optimized to solve the typical security problems of today's mobile, native and web applications.
\