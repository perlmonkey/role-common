Common
=====

This role installs and configures some common system packages that are useful on all Debian/Ubuntu systems.

Requirements
------------

This role requires Ansible 1.4 or higher and platform requirements are listed in the metadata file.

Role Variables
--------------

The variables that can be passed to this role and a brief description about them are as follows.

	common:
	  timezone: Europe/Berlin

Examples
========

Set up complete common tasks on all hosts

	- hosts: all
	  sudo: True
	  roles:
	     - { role: role-common, tags: common}


Dependencies
------------

None

License
-------

BSD

Author Information
------------------

Stephan Hochhaus <stephan@yauh.de>

[yauh.de](http://yauh.de)


