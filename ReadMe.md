# Zabbix-Couchbase-3.0
Zabbix monitor template for Couchbase 3.0/3.1

Couchbase Monitoring Template for Zabbix
====================

This template is a fixed version of original template by [myaaaaa-chan].

Files:

	*userparameter_couchbase_3.0.conf (Configuration file for Zabbix Agent)
    *zbx_couchbase_templates_3.0.xml (Template that utilize the performance counter defined)

Macro required:

	*{$USERNAME} -> Admin account username
	*{$PASSWORD} -> Admin account passwrod
	*{$BUCKET} -> Bucket Name
	*{$HDD_INDEX} -> Harddisk Index for monitoring target
	*{$SSD_INDEX} -> SSD index for the monitoring target
    
