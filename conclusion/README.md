## Conclusion

The proponents conclude that using SSO will efficiently shorten the time for students to switch between
AdDU systems and successfully authenticate each user using their credentials. It is also possible to implement
a SSO system to the AdDU systems for easier access and efficiently reduce the time it needs to switch from
the different AdDU systems. The proponents also found out that JOSSO framework is distributed with several
authentication schemes like basic authentication (username/password), strong authentication (digital
certificates), windows Authentication (NTLM), LDAP-Bind Authentication and Automatic Login
(Remember me) among others. And by integrating a single sign-on solution framework specifically JOSSO to
our project it easily exposes single sign-on services using SOAP over HTTP protocol allowing it to easily
integrate with non-java applications such as PHP driven web applications like most of the Ateneo systems. 

- ### Recommendation and Future Work

For future works, the proponents recommend that the SSO system would be synchronized with the
AdDU’s Windows Login. With the addition of synchronizing the SSO with the school’s windows login, the
students/teachers who would use AdDU’s computers would gain immediate access to their accounts on the
school’s systems. Another would be to improve the encryption algorithm for the authentication and
authorization of the SSO system. Improving the encryption algorithm of the SSO system would give it a good
boost on its security as it keeps the passwords of multiple AdDU systems.

- ### Definition of Terms
	- #### <b>Login Module</b> – Checks the credentials provided via an object and the details in which lets you access your account on a particular website or application.
	- #### <b>Authentication</b> – A process which confirms the identity of a user, this can be achieved in a variety of ways, for example by entering passwords or swiping an ID card.
	- #### <b>Authorization</b> – An act of deciding whether an authenticated user is allowed to access certain resources.
	- #### <b>JOSSO</b> – Stands for Java Open Single Sign On, which is the Java implementation of the standard Pluggable Authentication Module (PAM) information security framework.
	- #### <b>PAM</b> – Stands for Pluggable Authentication Module, a mechanism to integrate multiple low-level authentication schemes into a high-level application programming interface (API).
	- #### <b>JAAS</b> – Stands for Java Authentication and Authorization Service, is the Java implementation of the standard Pluggable Authentication Module (PAM) information security framework.
	- #### <b>CAS</b> – Stands for Central Authentication Service, a single sign-on protocol for the web. Its purpose is to permit a user to access multiple applications while providing their credentials (such as userid and password) only once.
	- #### <b>SOAP</b> – Stands for Simple Object Access Protocol, a protocol specification for exchanging structured information in the implementation of Web Services in computer networks. It relies on XML Information Set for its message format, and usually relies on other Application Layer protocols, most notably Hypertext Transfer Protocol (HTTP) or Simple Mail Transfer Protocol (SMTP), for message negotiation and transmission.
	- #### <b>J2EE</b> – Stands for Java 2 Platform Enterprise Edition or Java EE, provides an API and runtime environment for developing and running enterprise software, including network and web services, and other large-scale, multi-tiered, scalable, reliable, and secure network applications.
	- #### <b>LDAP</b> – Stands for Lightweight Directory Access Protocol, an application protocol for accessing and maintaining distributed directory information services over an Internet Protocol (IP) network.
	- #### <b>JDBC</b> – Stands for Java Database Connectivity, a Java API that enables Java programs to execute SQL statements. This allows Java programs to interact with any SQL-compliant database.
	- #### <b>Sublime Text</b> – a cross-platform text and source code editor, with a Python application programming interface (API).

## References

[Bhattacharjee, R. 2008. Authentication using JAAS. Retrieved: January 17, 2013](http://www.javaranch.com/journal/2008/04/authentication-usingJAAS.html)

[Jackson, G. 2012. Shibboleth SSO for small business. Retrieved January 18, 2013](http://www.gavinj.net/2012/08/shibboleth-sso-for-small-business.html)

[Jernevad, Henrik. 2009. Developing a Single Sign-On System: A Java-based authentication platform
aimed at the web. Retrieved September 02, 2013](http://publications.lib.chalmers.se/records/fulltext/117173.pdf)

[Loveland, N. 2002. Single Sign On Through Password Synchronization. Retrieved January 18, 2013](http://www.sans.org/reading_room/whitepapers/authentication/single-sign-passwordsynchronization_140)

[Maurizio, S. 2008. Single sign-on (SSO): Concepts, Methods and Frameworks. Retrieved December 20, 2012](http://mauriziostorani.wordpress.com/2008/07/21/single-sign-on-sso-concepts-methodsand-frameworks/)

[N.A. N.D. Java Authentication and Authorization Service. Retrieved: January 17, 2013](http://en.wikipedia.org/wiki/Java_Authentication_and_Authorization_Service)

[N.A. 2013. SAML Single Sign-On (SSO) Service for Google Apps. Retrieved January 18, 2013](https://developers.google.com/google-apps/sso/saml_reference_implementation)

[Upadhyay M. and Marti, R. N.D. Single Sign-on Using Kerberos in Java. Retrieved January 17, 2013](http://download.java.net/jdk8/docs/technotes/guides/security/jgss/single-signon.htm)