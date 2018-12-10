xcp-ng_guest-utilities
======================
[![Build Status](https://travis-ci.com/vmpr/xcp-ng_guest-utilities.svg?branch=master)](https://travis-ci.com/vmpr/xcp-ng_guest-utilities)

this ansible role can be used to automate the installation of XCP-NG or Citrix Xenserver guest utilities.

Requirements
------------

- minimum ansible version: 2.7
- if you use the role with a unprivileged user on your target servers, make sure it's possible to become root via sudo.

Role Variables
--------------

Description of all variables are documented here: [defaults/main.yml](https://github.com/vmpr/xcp-ng_guest-utilities/tree/master/defaults/main.yml)

Example Playbook
----------------

    - hosts: virtual_centos_servers
      roles:
         - { role: xcp-ng_guest-utilities }

License
-------
Apache

Todo:
-----
- [ ] enable role for ubuntu/debian

Author Information
------------------

Ringo Gierth
