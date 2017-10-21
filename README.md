ansible-sickrage
=========

Install Sickrage in Debian or Ubuntu follwing the docs in [https://github.com/SickRage/SickRage/wiki/Sickrage-installation-Debian-Ubuntu-14-15-16](https://github.com/SickRage/SickRage/wiki/Sickrage-installation-Debian-Ubuntu-14-15-16)

Requirements
------------

none

Role Variables
--------------

`sickrage_version: "v2017.06.05-1"`

`sickrage_user_home_folder: /var/lib/sickrage`

Dependencies
------------

none

Example Playbook
----------------

    - hosts: servers
      remote_user: root
      roles:
         - { role: sickrage, sickrage_version: "v2017.06.05-1" }

License
-------

GPLv3

Author Information
------------------

Pablo Escobar - https://github.com/pescobar
