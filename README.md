REST Web Service Shiro Turorial
===============================

This code is used in my tutorial to explain how to use Apache Shiro to secure a RESTful web service (or RESTful API if you wil).

The tutorial (REF-SOON) explains how to: 1) add Shiro User Authentication (username/password), which provides clients with a "authentication token" (or bearer token); 2) how to authenticate via the "authentication token" (to access API resources); 3) how to force all the communications to be sent over SSL.

To accomplish this we need to extend some of the default Shiro Filters/Realms, and furthermore generate a "self-signed" certificate to support the SSL communications.

(This will be released very soon!)
