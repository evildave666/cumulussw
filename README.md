Role Name
=========

This role deploys basic configuration for Cumulus Linux based switches

Requirements
------------

N/A

Role Variables
--------------

Default timezone is Asia/Tokyo, settable via the timezone variable.

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
