guacamole-ansible-role
======================

Ansible role to install and configure guacamole with mariadb, self signed ssl cert and nginx reverse proxy.

Requirements
------------
* centos/rhel 7
* ansible >= 2.2
* selinux disabled

Installation
------------
```shell
ansible-galaxy install joe-speedboat.mariadb
ansible-galaxy install joe-speedboat.guacamole
vi tests/install_guacamole.yml
ansible-playbook tests/install_guacamole.yml
```

Example Playbook
----------------
* `tests/install_guacamole.yml`: Real life example

Role Variables
--------------
* check `defaults/main.yml` for complete list
Some variables that require review:
* `guacamole_version`: 0.9.13-incubating
* `mariadb_user_password`: change-this
* `mariadb_root_password`: change-this
* `nginx_reverse_proxy_path`: rdp



Usage
-----
After installation, point your browser to: `https://{{ansible_fqdn}}/{{nginx_reverse_proxy_path}}` eg: https://fqdn/rdp 
Default username and password is: `guacadmin`  
*(Don't forget to change it)*

# License
https://opensource.org/licenses/LGPL-3.0   
Copyright (c) Chris Ruettimann <chris@bitbull.ch>   
---
