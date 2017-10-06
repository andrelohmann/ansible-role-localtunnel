localtunnel
===========

[![Build Status](https://travis-ci.org/andrelohmann/ansible-role-localtunnel.svg?branch=master)](https://travis-ci.org/andrelohmann/ansible-role-localtunnel)

Use this role to install the localtunnel.me client and run it as a deamon in the backgroud using supervisord.

Requirements
------------

This role requires ubuntu and nodejs.

Role Variables
--------------

The default set of variables defines the the settings, localtunnel will be started with

    localtunnel_host: False
    localtunnel_port: 80
    localtunnel_subdomain: False
    localtunnel_local-host: False

Example Playbook
----------------

    - hosts: localtunnel
      roles:
         - { role: andrelohmann.localtunnel }

License
-------

MIT

Author Information
------------------

https://github.com/andrelohmann
