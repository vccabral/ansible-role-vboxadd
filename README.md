vboxadd
=========

A role that will install vboxadd guest additions used for vagrant boxes. 

Requirements
------------

This is for vagrant boxes.

Role Variables
--------------

None.

Dependencies
------------

None.

Example Playbook
----------------

Add the role to a vagrant box to install vboxadd:

    - hosts: servers
      roles:
         - { role: vccabral.vboxadd }

License
-------

The MIT License (MIT)

Author Information
------------------

My name is Chris Cabral. I am a python, django, and ansible developer.
