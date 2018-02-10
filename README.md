ntp
=========

An Ansible Role that installs ntp client on RHEL/Centos 7 system.

- Add repository https://download.docker.com/linux/centos/docker-ce.repo
- Activate stable repo
- Install docker-ce
- Install python-docker-py


Requirements
------------

RHEL/Centos 7 system

Role Variables
--------------

N/A

Dependencies
------------

N/A

Example Playbook
----------------

    - hosts: servers
      roles:
         - ntp 

License
-------

MIT

Author Information
------------------

This role was created by [Lucien Stuker](https://www.newbit.ch/)
