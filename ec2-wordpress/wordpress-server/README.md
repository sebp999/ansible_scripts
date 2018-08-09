Wordpress Server
=========

Sets up a single apache server on a given AWS EC2 with a separate RDS database, and sets up separate virtual hosts for a list of domains.

Requirements
------------

A separate RDS database, already set up.  You can upload existing content from another server per domain as zip files under files/

Role Variables
--------------

vars: 
  - websites: a list of of the domains you want to set up for.
  - db_host: the address of the RDS database that you have set up

Dependencies
------------


Example Playbook
----------------

Provided 

License
-------

BSD

Author Information
------------------

An optional section for the role authors to include contact information, or a website (HTML is not allowed).
