ansible-role-redhat_satellite6_capsule_installation
=========

Role to install a Satellite 6 Capsule Server

Prerequisites
--------------

Role Variables
--------------

satellite_fqdn - FQDN of the satellite host

satellite_hammer_user - User to run hammer commands as

satellite_hammer_password - Hammer password

satellite_capsule_server_certs_dir - Target location of where certificates will be collected

satellite_capsule_server_cert_archive - Target location of certificate archive

satellite_installer_enable_remote_discovery - Boolean to enable or disable remote discovery

satellite_installer_enable_tftp - Boolean to enable or disable tftp

satellite_installer_enable_remote_execution_ssh - Boolean to enable or disable execution ssh

satellite_firewall_ports - List of firewall ports to expose. Format of port number and protocol. For example, `443/tcp`.

Example Playbook
----------------

See playbook in the `playbook_examples` directory.

License
-------

Apache 2.0
