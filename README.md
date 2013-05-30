zabbix_haproxy
==============

Zabbix script for monitoring haproxy

Usage:

* zhaproxy.py -d : Discovers the frontends/backends configurations
* zhaproxy.py -p &lt;proxy_name&gt; -s &lt;server_name&gt; -v &lt;attribute&gt; : Gets the specified value

UserParameters:

* haproxy.discovery: returns all available metrics
* haproxy.parameter: returns the value of the defined metric

See haproxy.cfg contains the configuration of the zabbix UserParameters.

TODO: Zabbix template
