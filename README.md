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
- `locales`: Locales to install. These are used to generate `/etc/locale.gen` so
  format must be compatible (e.g.: `en_NZ.UTF-8 UTF-8`).
- `default_locale`: Default locale for the system (e.g.: `en_NZ.UTF-8`)
- `debian_backports`: Whether or not to install backports repo

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
