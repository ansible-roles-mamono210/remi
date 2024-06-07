[![CircleCI](https://circleci.com/gh/ansible-roles-mamono210/remi/tree/main.svg?style=svg)](https://circleci.com/gh/ansible-roles-mamono210/remi/tree/main)

Role Description
=========

Installs [Remi's RPM repository](https://rpms.remirepo.net) for CentOS Stream 9.

Requirements
------------

None

Role Variables
--------------

See defaults/main.yml.

Dependencies
------------

None

Example Playbook
----------------

```YAML
---
- hosts: all
  become: true
  roles:
    - remi
```

License
-------

BSD
