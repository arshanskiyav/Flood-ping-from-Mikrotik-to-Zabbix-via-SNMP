Why do you need this?

To get icmp response time between several Mikrotiks and one host in the form of a graph.


To use it you need to:
- create a script on your Mikrotik with name that starts with SNMP_WATCH
- add a community with RW access
- add a host in your Zabbix with an SNMP interface
- attache a template from this repository

After that discover rules will create new items for each script whose name starts with SNMP_WATCH
