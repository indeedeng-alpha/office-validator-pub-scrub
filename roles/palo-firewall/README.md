Role Name
=========

This role gathers information from office palo alto firewalls and sets facts that are used in the generate-report role to determine if the device status passes office standards.

Requirements
------------
PaloAltoNetworks.paloaltonetworks ansible galaxy role must be installed, and the firewalls need to be configured and reachable from the Ansible Tower (or from the Ansible server where the playbook that calls this role is run). They also need to have the remote office password changed to meet the current standard.


Role Variables
--------------
This role sets facts and uses variables {{ snet }}, {{ site }}, {{ palo_pass }}, {{ palo_user }} that needs to be set up in the inventory file.

Dependencies
------------
This role does not require any other roles to be run first.


License
-------

BSD

Author Information
------------------

Created by Sarah Tovar, August 2019
