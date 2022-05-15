[![CircleCI](https://circleci.com/gh/ansible-roles-mamono210/cowsay/tree/main.svg?style=svg)](https://circleci.com/gh/ansible-roles-mamono210/cowsay/tree/main)

Role Description
=========

Installs [Cowsay](https://github.com/tnalpgge/rank-amateur-cowsay) for CentOS7/Stream8.

Requirements
------------

EPEL installed before running this role.

Role Variables
--------------

None

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
    - robertdebock.epel
    - cowsay
```

License
-------

BSD
