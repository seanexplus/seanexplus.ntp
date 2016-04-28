seanexplus.ntp
============

Sets up NTP on CentOS 7

Requirements
------------

None

Role Variables
--------------

customServer: True/False

ntpServer: server

Dependencies
------------

None

Example Playbook
----------------

    - hosts:
        - centos
      roles:
        - seanexplus.ntp

License
-------

BSD

Author Information
------------------

Yu-Lan Chiang <seanexplus@gmail.com>
