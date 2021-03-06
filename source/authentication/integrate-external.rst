Integrating External Server
===========================

You can configure the Policy Server to authenticate to external authentication systems using LDAP, RADIUS, IMAP, POP3, SMTP, or other third-party systems.

LDAP
----
   
Lightweight Directory Access Protocol (LDAP) is an Internet protocol used to maintain data that may include departments, people, groups of people, passwords, email addresses, and much more. Genian NAC can be integrated with LDAP to collect User Information and validate User Credentials.

.. toctree::
   :maxdepth: 1

   active-directory
   
RADIUS
------

Remote Authentication and Dial-in User Service (RADIUS) is a broadly supported client-server protocol that provides centralized authentication, authorization, and accounting functions. Genian NAC can be integrated with RADIUS to also work with LDAP in verifying Users Credentials.

.. toctree::
   :maxdepth: 1

   radius-server
   
IMAP/POP3/SMTP
--------------

Genian NAC can be integrated with IMAP, POP3, or SMTP if LDAP and RADIUS options are not available.

.. toctree::
   :maxdepth: 1

   imap-pop3-smtp
   testing
