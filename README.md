[![CircleCI](https://circleci.com/gh/ansible-roles-mamono210/php/tree/main.svg?style=svg)](https://circleci.com/gh/ansible-roles-mamono210/php/tree/main)

Role Description
=========

Installs [PHP](https://www.php.net) for CentOS7/Stream8.

Requirements
------------

Extra Packages for Enterprise Linux ([EPEL](https://docs.fedoraproject.org/en-US/epel/)) and [Remi's RPM repository](https://rpms.remirepo.net) installed before running this role.

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
    - geerlingguy.repo-remi
    - php
```

License
-------

BSD
