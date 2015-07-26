Debian-Composer
===============

Dependency manager for PHP

Requirements
------------

This role requires a debian compliant system such as ubuntu.

Role Variables
--------------

No variables

Dependencies
------------

None

Example Playbook
----------------

    - hosts: servers
      roles:
         - { role: loranger.debian-composer }

Tasks
-----

  - Install [composer](https://getcomposer.org/)

License
-------

BSD