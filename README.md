[![](https://github.com/ansible-roles-matsumura/cowsay/workflows/build/badge.svg)](https://github.com/ansible-roles-matsumura/cowsay/actions?query=workflow%3Abuild)
[![CircleCI](https://circleci.com/gh/ansible-roles-matsumura/cowsay.svg?style=svg)](https://circleci.com/gh/ansible-roles-matsumura/cowsay)

Role Description
=========

Installs [Cowsay](https://github.com/tnalpgge/rank-amateur-cowsay) for CentOS7/CentOS8.

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
