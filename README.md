apache2_mod_rpaf
=========

Ansible role to install and configure mod_rpaf.  

Requirements
------------

Debian/Ubuntu and compatible systems.

Role Variables
---------------

apache2_mod_rpaf_ips: List of trusted ip addresses that setup X-Forwarded-For header. 

Example Playbook
----------------

    - hosts: servers
      roles:
         - davidkarban.apache_mod_rpaf

License
-------

Apache Licence 2.0

