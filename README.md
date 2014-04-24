service-monitoring-config
=========================

Configuration for the tool(s) that perform automated monitoring of

* RIT's network-accessible services
* Host resources (memory, disk ...) associated with those services

and notify RIT staff and/or perform appropriate automated responses 
when problems are detected.

Our convention is to use different branches within this repository
to manage configuration for different automated monitoring tools
(as well as different major versions of these tools).

We do this to accommodate service evolution and/or multiple deployed
instances of automated monitoring hosts.

Current branches:

* nagios35 - Configuration for Nagios Core version 3.5.x
