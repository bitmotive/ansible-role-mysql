ansible-role-pythonconf
=========

MySQL configuration

Requirements
------------

This role has only been tested on EL 6 systems using Ansible 1.9.

Role Variables
--------------


Example Playbook
----------------

```
- hosts: webservers
  roles:
    - { role: bitmotive.ansible-role-mysql, tags: "mysql" }
```

License
-------

MIT
