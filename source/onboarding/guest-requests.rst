Managing Guest Requests
=======================

Your Guests will request account credentials to use while they are visiting. To manage these requests you have to validate and acknowledge these requests to allow for access

Enable Request User Account Button On CWP
-----------------------------------------

(*Make sure the Network Sensor is active and Node Policy is enabled*)

#. Go to **Policy** in the top panel
#. Go to **Node Policy** in the left Policy panel
#. Find and click **desired name** of **Node Policy** in main Node Policy window
#. Find **Advanced > Authentication Policy > User Account Request** section and select **On**
#. Click **Update**

CWP Address for Guest to Request Credentials
--------------------------------------------

.. code:: bash

   http://(IP of Policy Server)/cwp

Accept Guest Requests
---------------------

#. Go to **Management > Request** in the top panel
#. Go to **User Account Request > Request** in the left Request Management panel
#. Find **Requests** in the User Account Request window. Click **Checkbox**
#. Click **Tasks > Accept All**

Reject Guest Requests
---------------------

#. Go to **Management > Request** in the top panel
#. Go to **User Account Request > Request** in the left Request Management panel
#. Find **Requests** in the User Account Request window. Click **Checkbox**
#. Click **Tasks > Reject All**
