[![CircleCI](https://circleci.com/gh/ansible-roles-mamono210/cowsay/tree/main.svg?style=svg)](https://circleci.com/gh/ansible-roles-mamono210/cowsay/tree/main)

Role Description
=========

Installs [Cowsay](https://github.com/tnalpgge/rank-amateur-cowsay) for Linux.

Requirements
------------

[EPEL](https://docs.fedoraproject.org/en-US/epel/) installed before running this role.

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
    - geerlingguy.epel
    - cowsay
```

Testing
-------

The role includes a Molecule scenario and linting configuration. You can
run the checks locally with:

```bash
yamllint .
ansible-lint
molecule test
```

License
-------

BSD
