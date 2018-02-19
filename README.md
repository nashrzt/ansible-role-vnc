Role for VncServer
=========

This Role will install and configure VncServer in ubuntu Server


Requirements
------------

Ansible 2.3+
Python3+

Role Variables
--------------

Role variables are defined in Defaults folder.
User variable can be externalised in the main playbook file.

Dependencies
------------

Dependencies are included in Role
Dependencies have to change for Older Ubuntu Versions

Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

    - hosts: servers
      remote_user: user
      become: true
      become_method: sudo
      roles:
         - ansible-role-vnc

License
-------

Razorthink INC

Author Information
------------------

Nishan P A

Devops Team

Contributors:

Hareesh R
