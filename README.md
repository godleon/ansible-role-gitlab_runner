[![Build Status](https://travis-ci.org/godleon/ansible-role-gitlab_runner.svg?branch=master)](https://travis-ci.org/godleon/ansible-role-gitlab_runner)


Role Name
=========

**godleon.gitlab_runner**

Requirements
------------

### Software

- Python2.7 (**Ubuntu Xenial**)
> sudo apt-get update && sudo apt-get -y install python2.7

Role Variables
--------------

A description of the settable variables for this role should go here, including any variables that are in defaults/main.yml, vars/main.yml, and any variables that can/should be set via parameters to the role. Any variables that are read from other roles and/or the global scope (ie. hostvars, group vars, etc.) should be mentioned here as well.

Dependencies
------------

- godeon.docker

> ansible-galaxy install godleon.docker

Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

```yml
- hosts: servers
  roles:
    - { role: godleon.docker }
    - { role: godleon.gitlab_runner }
```

License
-------

MIT

Author Information
------------------

**Leon Tseng** 

-  [godleon@GitHub](https://github.com/godleon)