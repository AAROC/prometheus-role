Prometheus role
=========

A role to deploy [Hashicorp's Prometheus monitoring service](https://prometheus.io) on arbitrary endpoints.

Requirements
------------

none.

Role Variables
--------------

Role variables include : 

  - `components`: which components are you going to include in this prometheus server ? 

Dependencies
------------

None

Example Playbook
----------------

Use the role in your playbooks as follows : 

    - hosts: servers
      roles:
         - { role: prometheus-role }

License
-------

Apache-2.0

Author Information
------------------

Bruce Becker (CSIR Meraka Institute)