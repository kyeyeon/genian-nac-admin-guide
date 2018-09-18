RADIUS Authentication using Gmail Credentials
=============================================

The most common method to WiFi authentication is having a shared SSID and passphrase. 
Shared SSID and passphrase authentication can be effective at keeping the majority of unauthorized users at bay, 
but it doesn’t offer the ability to easily control who is accessing your WiFi network because anyone with the 
SSID and passphrase essentially has full access.
Genian NAC RADIUS server can eliminate shared passphrases by creating unique access to your WiFi for each person on your network using Gmail credentials.

Step 1. Enable Built-In RADIUS Server
-------------------------------------

#. Go to **Preferences** in the top panel
#. Go to **Service > RADIUS Server** in the left Preferences panel

Under **Authentication Server**

#. For **Shared Secret Key**, enter the pre-shared secret key for RADIUS client authentication
#. For **RADIUS Client IP**, enter the IP address or addresses to be allowed as RADIUS Server
#. For **Server Port**, enter the RADIUS authentication port number (*Default is 1812*)
#. For **EAP Authentication**, select **On** then use **GTC** for Default EAP-PEAP
#. For **MAC Authentication**, select **Off**
#. For **Generating Accounting**, select **On** if RADIUS Client does not support generating RADIUS accounting packet
#. For **Genian NAC Authentication**, optional setting to allow users to authenticate from Genian NAC
#. For **LDAP Authentication**, select **Off** to not use LDAP for Authentication
#. For **Web Authentication**, select **Off** to not use a web server for Authentication
#. For **Email Authentication**, select **On** to allow a user to Authenticate by email

Under Accounting Server

#. For **RADIUS Client IP**, enter the IP address or addresses to be allowed as RADIUS Server
#. For **Accounting Port**, use **1813**
#. For **Authentication**, select **On** to allow a user to Authenticate by a remote server
#. For **Shared Secret Key**, enter the pre-shared secret key for RADIUS client authentication
#. For **Acct-Status-Type**, click **Start(1)**, and **Stop(2)** checkboxes to mark beginning and end of Accounting-Request
#. For **Attribute to Match**, select **MAC** to match for Authentication
#. For **Node Status**, select **All Nodes** to be authenticated
#. Click **Update**

Step 2. Configure SMTP Server for Gmail
---------------------------------------

#. Go to **Preferences** in the top panel
#. Go to **User Authentication > Authentication Integration** in the left Preferences panel
#. Find **SMTP Server** section
#. For **Server Address**, type **smtp.gmail.com**
#. For **Server Port**, type **465**
#. For **Domain Name**, type gmail.com (*Only users having gmail.com can authenticate*)
#. Click **Update**

Step 3. Test SMTP Server Settings
---------------------------------

Under **Authentication Test** Click **Test**

#. For **Repository**, select **SMTP** from drop-down
#. For **Username**, type your username for gmail excluding @gmail.com
#. For **Password**, type password associated to above username
#. Click **Authenticate (Test)**
