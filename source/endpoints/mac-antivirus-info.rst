Collecting Antivirus Software Information
=========================================

Policy Server communicates with the Agent to collect antivirus software information that is installed on your macOS devices

List of Supported Antivirus by Version
--------------------------------------

See all Antivirus supported with Genian NAC by version.

+---------------+--------------------------------+---------------+
|Vendor         |Product                         |Genian Version |
+===============+================================+===============+
|BitDefender    |BitDefender                     |5.0.14         |
+---------------+--------------------------------+---------------+
|ESET           |ESET NOD32 ANTIVIRUS 9          |5.0.3          |
+---------------+--------------------------------+---------------+
|Estsecurity    |AIYak                           |3.5.0          |
+---------------+--------------------------------+---------------+
|Kaspersky      |Kaspersky                       |3.5.0          |
+---------------+--------------------------------+---------------+
|McAfee         |McAfee                          |4.0.23/3.5.19  |
+---------------+--------------------------------+---------------+
|Symantec       |Norton Antivirus                |4.0.2/3.5.0    |
+---------------+--------------------------------+---------------+
|Trend Micro    |OfficeScan                      |3.5.0          |   
+---------------+--------------------------------+---------------+

To See the Configuration of the Plugin
--------------------------------------

- Go to **System > Update > Genian Software > Plugin > Collect Antivirus Software Information**

To Add the Agent Action to a Policy
-----------------------------------

#. Go to **Policy** in the top panel
#. Go to **Policy > Node Policy** in the left Policy panel
#. Click the **desired Policy ID** in Node Policy window
#. Find **Agent Action**. Click **Assign**
#. Find **Collect Antivirus Software Information** in the **Available** section. Select and drag it into the **Selected** section
#. Click **Add**
#. Click **Update**

To Collect Antivirus Software Information
-----------------------------------------

#. Go to **Policy** in the top panel
#. Go to **Policy > Node Policy > Agent Action** in the left Policy panel
#. Find and click **Collect Antivirus Software Information** in the Agent Action window
#. Enter in **CWP Message**, **Conditions**, and adjust **Agent Actions** based off of your network requirements
#. Click **Update**
