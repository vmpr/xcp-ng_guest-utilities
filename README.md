xcp-ng_guest-utilities
======================
[![Build Status](https://travis-ci.com/vmpr/xcp-ng_guest-utilities.svg?branch=master)](https://travis-ci.com/vmpr/xcp-ng_guest-utilities)

this ansible role can be used to automate the installation of XCP-NG or Citrix Xenserver guest utilities.

Requirements
------------
for the role:

- minimum ansible version: 2.7
- if you use the role with a unprivileged user on your target servers, make sure it's possible to become root via sudo.

for molecule tests:
- [molecule/default/INSTALL.rst](https://github.com/vmpr/xcp-ng_guest-utilities/tree/master/molecule/default/INSTALL.rst)

Role Variables
--------------

Description of all variables are documented here: [defaults/main.yml](https://github.com/vmpr/xcp-ng_guest-utilities/tree/master/defaults/main.yml)

Installation
------------
`ansible-galaxy install vmpr.xcp_ng_guest_utilities`


Example Playbook
----------------
```
    - hosts: virtual_centos_servers
      roles:
         - { role: vmpr.xcp-ng_guest-utilities }
```         

License
-------
Apache

Todo:
-----
- [ ] enable role for ubuntu/debian

Author Information
------------------

Ringo Gierth
