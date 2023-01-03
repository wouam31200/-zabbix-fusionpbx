# zabbix-fusionpbx

Very simple monitoring template for FusionPBX. 
Requires Zabbix v 5.0 or above.

Creates APP : FusionPBX

### Items monitored
  - FusionPBX: Current calls count inbound
  - FusionPBX: Current calls count outbound
  -	FusionPBX: Current calls count total
  - FusionPBX: Current channels count
  -	FusionPBX: Current Registration Count
  -	FusionPBX: Current sessions
  -	FusionPBX processes

### Triggers
  - No freeswitch process running  

### Graphs
 - FusionPBX: Current Calls	
 - FusionPBX: Current Registration Count
 - FusionPBX: Stats

## Installation

Import the template XML file to Zabbix server.

Put the parameters file `userparameter_fusionpbx.conf` on the FusionPBX server in the Zabbix Agent config directory `/etc/zabbix/zabbix_agentd.d/`.