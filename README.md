add-icinga2-host
======================

Ansible role
------------

These variables must be configured:

- **icinga_server**: Address of icinga server


These variables could be configured:

- **icinga2_template_base**: Name of the base template for the host template
- **icinga2_template_nrpe_checks**: list of nrpe checks
- **icinga2_template_tcp_ports**: list of tcp ports to check
- **icinga2_template_http_vhosts**: list of http vhosts checks 