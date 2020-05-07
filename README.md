[![](https://github.com/ansible-roles-matsumura/circleci-cli/workflows/yamllint/badge.svg)](https://github.com/ansible-roles-matsumura/circleci-cli/actions?query=workflow%3Ayamllint)
[![](https://github.com/ansible-roles-matsumura/circleci-cli/workflows/ansible-playbook/badge.svg)](https://github.com/ansible-roles-matsumura/circleci-cli/actions?query=workflow%3Aansible-playbook)
[![](https://github.com/ansible-roles-matsumura/circleci-cli/workflows/ansible-lint/badge.svg)](https://github.com/ansible-roles-matsumura/circleci-cli/actions?query=workflow%3Aansible-lint)
[![](https://github.com/ansible-roles-matsumura/circleci-cli/workflows/trailing%20whitespace/badge.svg)](https://github.com/ansible-roles-matsumura/circleci-cli/actions?query=workflow%3A%22trailing+whitespace%22)

Role Description
=========

Installs [circleci-cli](https://github.com/CircleCI-Public/circleci-cli) for CentOS7.

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
