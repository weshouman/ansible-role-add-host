Role Name
=========

Add given hosts to hostfile.

Status
------
[![Build Status](https://travis-ci.org/weshouman/ansible-role-add-host.svg?branch=master)](https://travis-ci.org/weshouman/ansible-role-add-host)

Requirements
------------

This role doesn't work on docker containers (centos and ubuntu so far). Follow this [issue](https://github.com/ansible/molecule/issues/2060).

Role Variables
--------------

hostname: the hostname to be added
address: the hostname address

Example Playbook
----------------

    - hosts: servers
      roles:
         - { role: weshouman.add_host, hostname: local.example.com, address: 192.168.10.10 }

License
-------

MIT

Author Information
------------------

Authored by Walid Shouman

