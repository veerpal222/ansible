Role Name
=========

Wordpress installation for ubuntu

Requirements
------------

This role is only for ubuntu
Before play this role, install docker module in your ansible machine
command: ansible-galaxy collection install community.docker

Role Variables
--------------

DB_PASS: sanjay  #To set database password, by default value is sanjay, you can change it.
DB_NAME: sanjay  #To set database name, by default value is sanjay, you can change it.
By default it will run on 8082 port for your docker machine
use: <ipofdockermachine>:8082 after run this play.
By default Database user "root".
By default name of Database container is 
By default name of wordpress container is


Example Playbook
----------------
---
    - hosts: <dockerhost>
      roles:
         - wordpress

License
-------

BSD

Author Information
------------------

Sanjay Kumar
