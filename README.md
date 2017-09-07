JunOS Requirements
=========

Installs JunOS requirements onto a Ansible server or Ansible Tower node.  Include this role in any Junos automation playbook to ensure that the
ansible server has the correct Junos requirements.

Requirements
------------

Ansible 2.3+

Role Variables
--------------

No role variables

Dependencies
------------

None

Example Playbook
----------------
```
- hosts: junos_devices
  connection: local
  roles:
    - junos_requirements
    - system
    - interface
```

License
-------

MIT

Author Information
------------------

Stanley Karunditu (@linuxsimba)
