# Mini-SIEM-Project

Welcome to the Mini-SIEM Project! This is where I will be configuring a virtual server to run Wazuh and have virtual client/s have the Wazuh agents installed on them so I can learn more on SIEMs and practice security engineering.

### Current Progress So Far

* Deployed a dedicated Ubuntu Server virtual machine running Wazuh for centralized security monitoring.
* Configured an Ubuntu client virtual machine with the Wazuh agent and verified that endpoint events were being received.
* Investigated Wazuh security alerts by examining event fields, rule IDs, and severity levels.
* Generated three intentional failed sudo authentication attempts and analyzed the resulting alert.
* Traced the alert through Wazuh rules 5400, 5401, and 5404 to understand how parent-child rule conditions determine whether an alert is triggered.