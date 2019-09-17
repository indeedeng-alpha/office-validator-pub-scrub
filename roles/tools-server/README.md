Role Name
=========

This role checks to make sure insecure ports are not open at an office using the tools server at each site.

Requirements
------------
Prior to running this role, the tools server needs to be configured and reachable from the Ansible Tower (or from the Ansible server where the playbook that calls this role is run). 


Role Variables
--------------

This role uses a variables file that contains a list of IP addresses to scan.

Dependencies
------------
This role does not require any other roles to be run first.


License
-------

BSD

Author Information
------------------

Created by Sarah Tovar, August 2019
