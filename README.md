![Ansible Lint](https://github.com/johanneskastl/ansible-role-setup_sssd_as_client_for_389_server/workflows/Ansible%20Lint/badge.svg)

setup_sssd_as_client_for_389_server
=========

Setting up sssd as client for a 389 LDAP server

Requirements
------------

None on the host that is being modified.
Of course you need a running (and working) LDAP server to connect to...

Role Variables
--------------

None.

Dependencies
------------

None

Example Playbook
----------------

    - hosts: servers
      roles:
         - { role: 'johanneskastl.setup_sssd_as_client_for_389_server' }

License
-------

BSD-3-Clause

Author Information
------------------

I am Johannes Kastl, reachable via kastl@b1-systems.de.
