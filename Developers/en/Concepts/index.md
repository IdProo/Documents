Most modern applications look more or less like this:

![Web app idproo page](_static/appArch.png?sanitize=true)

### The most common interactions are: 
- Browsers communicate with web applications
- Web applications communicate with web APIs (sometimes on their own, sometimes on behalf of a user)
- Browser-based applications communicate with web APIs
- Native applications communicate with web APIs
- Server-based applications communicate with web APIs
- Web APIs communicate with web APIs (sometimes on their own, sometimes on behalf of a user)

Typically each and every layer (front-end, middle-tier and back-end) has to protect resources and implement authentication and/or authorization – often against the same user store.

Outsourcing these fundamental security functions to a security token service prevents duplicating that functionality across those applications and endpoints.

Restructuring the application to support a security token service leads to the following architecture and protocols:

![Web app idproo page](_static/protocols.png?sanitize=true)

Such a design divides security concerns into two parts: 
- [Authentication](#!/Posts/5f74f9cd-5619-42cf-a071-83e44726e9dc/big-picture/de58ab4ca1b54ef682c5611467c762aa)
- [API Access](#!/Posts/5f74f9cd-5619-42cf-a071-83e44726e9dc/big-picture/8385c8bc118e46799b3a1fdb5c24e553) 
- [Terminology](#!/Posts/5f74f9cd-5619-42cf-a071-83e44726e9dc/big-picture/04746b7fa499468091e6395ec215bb58) 
