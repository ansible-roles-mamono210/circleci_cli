[![](https://github.com/ansible-roles-matsumura/circleci-cli/workflows/ansible-lint/badge.svg)](https://github.com/ansible-roles-matsumura/circleci-cli/actions?query=workflow%3Aansible-lint)
[![](https://github.com/ansible-roles-matsumura/circleci-cli/workflows/molecule/badge.svg)](https://github.com/ansible-roles-matsumura/circleci-cli/actions?query=workflow%3Amolecule)
[![](https://github.com/ansible-roles-matsumura/circleci-cli/workflows/trailing%20whitespace/badge.svg)](https://github.com/ansible-roles-matsumura/circleci-cli/actions?query=workflow%3A%22trailing+whitespace%22)
[![](https://github.com/ansible-roles-matsumura/circleci-cli/workflows/yamllint/badge.svg)](https://github.com/ansible-roles-matsumura/circleci-cli/actions?query=workflow%3Ayamllint)

Role Description
=========

Installs [circleci-cli](https://github.com/CircleCI-Public/circleci-cli) for CentOS7/CentOS8.

Requirements
------------

None

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
    - circleci-cli
```

License
-------

BSD
