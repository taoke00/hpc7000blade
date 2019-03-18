# hp c7000 blade
add snmp v2c host
macros add {$SNMP_COMMUNITY}, mostly "public" 
zabbix template tested on zabbix v3.4
translate most mib oid to numberic using script so do not need extra mib file in zabbix server.
