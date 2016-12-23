Ansible Role: Percona Client
============================

This role will install Percona Client. Note that MariaDB will be removed.

Requirements
------------

None.

Role Variables
--------------

Available variables are listed below, along with default values (see `defaults/main.yml`):

Dependencies
------------

- mosufy.lemp-stack

Example Playbook
----------------

    - name: Install Percona client
      hosts: webservers
      become: true
      become_method: sudo
      roles:
        - mosufy.percona-client

License
-------

This codebase is open-sourced software licensed under the [MIT license](http://opensource.org/licenses/MIT)

Author Information
------------------

For any issues with installation or getting this to work, send an email to: [mosufy@gmail.com](mailto:mosufy@gmail.com)
