Role Name
=========

This role install docker-ce on ubuntu

Role Variables
--------------

``` These values are default, which can be configured under vars/main.yml
ubuntu_release: xenial
version: 17.06.2~ce-0~ubuntu```


Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

    - hosts: servers
      roles:
         - { role: username.rolename, x: 42 }
