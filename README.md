[![](https://github.com/ansible-roles-matsumura/cowsay/workflows/Build/badge.svg)](https://github.com/ansible-roles-matsumura/cowsay/actions?query=workflow%3ABuild)
[![](https://github.com/ansible-roles-matsumura/cowsay/workflows/Lint/badge.svg)](https://github.com/ansible-roles-matsumura/cowsay/actions?query=workflow%3ALint)

Role Description
=========

Installs [Cowsay](https://github.com/tnalpgge/rank-amateur-cowsay) for CentOS7.

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
    - geerlingguy.repo-epel
    - cowsay
```

License
-------

BSD
