[![Build Status](https://travis-ci.com/danielpieper/ansible-gitlab-runner.svg?branch=main)](https://travis-ci.com/danielpieper/ansible-gitlab-runner)

Gitlab Runner
=========

This role installs [gitlab-runner](https://docs.gitlab.com/runner/) in the users `.local/bin` directory.

Requirements
------------

TODO

Role Variables
--------------

TODO: A description of the settable variables for this role should go here, including any variables that are in defaults/main.yml, vars/main.yml, and any variables that can/should be set via parameters to the role. Any variables that are read from other roles and/or the global scope (ie. hostvars, group vars, etc.) should be mentioned here as well.

Dependencies
------------

None.

Example Playbook
----------------

```
- hosts: localhost
  connection: local
  roles:
     - { role: danielpieper.gitlab_runner }
```

License
-------

MIT
