[![](https://github.com/ansible-roles-matsumura/cowsay/workflows/yamllint/badge.svg)](https://github.com/ansible-roles-matsumura/cowsay/actions?query=workflow%3Ayamllint)
[![](https://github.com/ansible-roles-matsumura/cowsay/workflows/molecule/badge.svg)](https://github.com/ansible-roles-matsumura/cowsay/actions?query=workflow%3Amolecule)
[![](https://github.com/ansible-roles-matsumura/cowsay/workflows/ansible-lint/badge.svg)](https://github.com/ansible-roles-matsumura/cowsay/actions?query=workflow%3Aansible-lint)
[![](https://github.com/ansible-roles-matsumura/cowsay/workflows/trailing%20whitespace/badge.svg)](https://github.com/ansible-roles-matsumura/cowsay/actions?query=workflow%3A%22trailing+whitespace%22)

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
