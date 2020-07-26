Role Name
=========

Create OSP Instances for QA Env

Requirements
------------

N/A

Role Variables
--------------

./osp-servers/vars/main.yml

Dependencies
------------

N/A

Example Playbook
----------------

- hosts: localhost
  connection: local
  become: no
  gather_facts: true
  roles:
   - osp-servers

License
-------

BSD

Author Information
------------------

proxi73 for Ansible Homework
