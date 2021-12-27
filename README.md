# ngx_http_access_port_module
Deny or allow clients indicated by source ip and port (range)

This module is similar to the module ngx_http_access in the nginx code base, but using denyp, allowp (instead of deny, allow),
Syntax:	allowp | denyp address | CIDR lower_port upper_port;
