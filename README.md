[![Build Status](https://travis-ci.org/uniQconsulting-ag/ansible.guacamole.svg?branch=master)](https://travis-ci.org/uniQconsulting-ag/ansible.guacamole)

[![Alt text](https://www.uniqconsulting.ch/images/logo.png)](https://www.uniqconsulting.ch/)

Guacamole HTML5 RDP Gateway Setup with Ansible
==============================================

This Ansible Role is installing and configuring Guacamole HTML5 Gateway
* `Mariadb`
* `Tomcat`
* `Guacamole via RPM`
* `Guacamole extensions: default/main.yml`
* `Nginx reverse proxy`

Requirements
------------

* Currently only tested with CentOS 7
* Ansible 2.4 or higher is required for this Ansible Role

Role Variables
--------------

Variables are self speaking or documented in:   
* `defaults/main.yml`
* `vars/main.yml`

Dependencies
------------

This Ansilbe Role has no dependencies to other Ansilbe Roles

Example Playbook
----------------

Example playbooks for this role are located in ´test´ folder:
* `tests/install_guacamole.yml`

uniQconsulting ag
-----------------

uniQconsulting ag is an IT consulting company with headquarters in Bassersdorf, Switzerland and a wholly owned subsidiary of Netcloud AG since 2017.
Netcloud is a privately held company, reputed for Network and Cloud Services in Switzerland. Although operating independently, both companies have a long history of close collaboration.

uniQconsulting provides a wide range of IT services from the datacenter to the edge and the cloud. The services and solutions of uniQconsulting are well established among clients in business areas like financial services, health care, the public sector and medium sized enterprises.

Depending on individual client requirements, uniQconsulting can assume responsibility for selected, or for all phases of a project. Highly certified and experienced staff guarantee successful implementations. Projects are monitored from start to finish. 

Once a project has been successfully completed, comprehensive services are available to the customer. Our trilingual Expert Helpdesk, based in Switzerland, can take on specific tasks, offloading the client staff, or proactively monitor the IT infrastructure, responding appropriately in the event of an incident or pending change. This gives customers the certainty of being able to call on the appropriate specialist if necessary, without having to build up this know-how internally.

By outsourcing services related to the IT infrastructure, customers can focus on business-applications and processes, resulting in greater transparency and financial predictability in IT operations. The experts at uniQconsulting help customers to create a long-term IT strategy, supporting their overall business goals.

Compliance and security topics are becoming increasingly complex and expensive. Not shying away from thinking outside the box, uniQconsulting focusses on designing high quality and game-changing IT Solutions, with the specific goal of optimizing efficiency and security in digital workflows while maximizing ROI.

We believe in IT-driven success.

License
-------
https://opensource.org/licenses/LGPL-3.0    
Copyright (c) uniQconsulting ag - Chris Ruettimann <cruettimann@uniqconsulting.ch>

