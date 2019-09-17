Role Name
=========

This role uses facts gathered by other roles and compares the status to the office standards to generate a pass/fail report for office devices. The report is saved on the report server specified in the inventory file.

Requirements
------------
Prior to running this role, the other roles need to be run as this role uses the facts gathered by those roles to determine if the devices passed or failed. The report server must also be accessible and the role setup-report-server needs to have been run in advance.

Role Variables
--------------

This role uses facts set by other roles and uses variables set in vars/main.yml that define the standards for the office. 

Dependencies
------------
This role requires that all other roles have been successfully completed.


License
-------

BSD

Author Information
------------------

Created by Sarah Tovar, May 2019
