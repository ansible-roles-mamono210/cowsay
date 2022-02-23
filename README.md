[![CircleCI](https://circleci.com/gh/ansible-roles-mamono210/cowsay/tree/main.svg?style=svg)](https://circleci.com/gh/ansible-roles-mamono210/cowsay/tree/main)
[![](https://github.com/ansible-roles-matsumura/cowsay/workflows/build/badge.svg)](https://github.com/ansible-roles-matsumura/cowsay/actions?query=workflow%3Abuild)

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
