Ansible Base
============

[![Build
Status](https://travis-ci.org/mauroveron/ansible-base.svg?branch=master)](https://travis-ci.org/mauroveron/ansible-base)

Base software and configuration for Debian systems.

Requirements
------------

None

Role Variables
--------------

- `timezone`: The timezone
- `locale`: Locale string (e.g.: `en_NZ`)

Dependencies
------------

None

Example Playbook
----------------

    - hosts: servers
      roles:
         - { role: maurov.baseline }

License
-------

BSD

Author Information
------------------

An optional section for the role authors to include contact information, or a
website (HTML is not allowed).
