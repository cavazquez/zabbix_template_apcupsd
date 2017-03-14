Zabbix template apcupsd
==========================

Tested on Zabbix Version 3.2

FEATURES
--------
* Model
* Driver
* Remaining battery percentage
* Remaining runtime in minutes
* Status Connection
* Timeout

REQUIREMENTS
------------
* Zabbix server version 3.2

INSTALLATION
------------
* Agent
  * Copy __userparameter_apcupsd.conf__ to __/etc/zabbix/zabbix_agentd.d/userparameter_apcupsd.conf__
  * Restart zabbix_agent
* Server
  * Import template __template_apcupsd.xml__ file


LICENSE
-------
GNU GENERAL PUBLIC LICENSE Version 3, 29 June 2007
