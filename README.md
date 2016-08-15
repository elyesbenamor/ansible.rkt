Rkt Install
=========

Usage for install and start the Rkt container runtime in linux.

Role Variables
--------------

| Variable's name | Description | Example |
| --------------- | ----------- | ------- |
| rkt_version  | version of Rkt that you want install. Default's 1.8.0  | 1.8.0  |

Example 
----------------

Install from Galaxy:

	$ ansible-galaxy install ledongthuc.rkt-install

Playbook (for default variables):

    - hosts: all
      roles: 
      	- ledongthuc.rkt-install

Playbook (for specific variables):

    - hosts: all
      roles:
      	- { role: ledongthuc.rkt-install, rkt_version: 1.8.0 }

License
-------

MIT
