Rkt Install
=========

Usage for install and start the Rkt container runtime in linux.
Currently, I tested it with Ubuntu trusty64 

Role Variables
--------------

	rkt_version: version of Rkt that you want install. Default's 1.8.0

Example 
----------------

Install from Galaxy:

	`$ ansible-galaxy install ledongthuc.rkt-install`

For default configuration:

    - hosts: all
      roles: 
      	- ledongthuc.rkt-install

For specific variables:

    - hosts: all
      roles:
      	- { role: ledongthuc.rkt-install, rkt_version: 1.8.0 }

License
-------

MIT
