[![](https://github.com/ansible-roles-matsumura/circleci-cli/workflows/Build/badge.svg)](https://github.com/ansible-roles-matsumura/circleci-cli/actions?query=workflow%3ABuild)
[![](https://github.com/ansible-roles-matsumura/circleci-cli/workflows/Lint/badge.svg)](https://github.com/ansible-roles-matsumura/circleci-cli/actions?query=workflow%3ALint)

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
