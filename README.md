[![CircleCI](https://circleci.com/gh/ansible-roles-mamono210/circleci_cli/tree/main.svg?style=svg)](https://circleci.com/gh/ansible-roles-mamono210/circleci_cli/tree/main)
[![](https://github.com/ansible-roles-matsumura/circleci-cli/workflows/build/badge.svg)](https://github.com/ansible-roles-matsumura/circleci-cli/actions?query=workflow%3Abuild)

Role Description
=========

Installs [circleci-cli](https://github.com/CircleCI-Public/circleci-cli) for CentOS7/Stream8.

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
