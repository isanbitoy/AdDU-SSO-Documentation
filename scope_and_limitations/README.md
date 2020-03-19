## Scope and Limitations

The study generally focuses on two scopes, the Login module which is primarily concerned with the
authentication and authorization process of the system and the Security System Integration. Form
authentication, a common part of JOSSO where it can be defined and processed to confirm the identity of the
user, while the authorization module has the process of deciding whether an authenticated user/system is
allowed to access a certain resource or perform a certain action or not. Both of these modules, the
authentication and authorization component, are addressed by JOSSO where it provides a framework and Java
API. For the security system integrator, JOSSO provides interfaces to provide identity namespace to
applications, attach credentials to threads, and to invoke callbacks to query the user which checks their
response and generates a Subject. In the case of encrypting and decrypting algorithm, we are limited to use
the security integrator of JOSSO since the paper centers on the development of the SSO and not mainly on the
security features.
