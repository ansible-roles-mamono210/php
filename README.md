[![](https://github.com/ansible-roles-mamono210/php/workflows/build/badge.svg)](https://github.com/ansible-roles-mamono210/php/actions?query=workflow%3Abuild)

Role Description
=========

Installs [PHP](https://www.php.net) for CentOS7.

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
