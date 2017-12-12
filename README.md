Role Name
=========

This role deploys basic configuration for Cumulus Linux based switches

Requirements
------------

N/A

Role Variables
--------------

timezone: default Asia/Tokyo

nameserver1: default 8.8.8.8

nameserver2: default 8.8.4.4

Dependencies
------------

N/A

Example Playbook
----------------

    - hosts: cumulusswitch
      vars:
        timezone: Asia/Singapore
      remote_user: root
      become: yes
      roles:
        - cumulussw

License
-------

BSD

Author Information
------------------

David Van Cleef - dvc@aeug.org
