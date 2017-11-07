Travis-ci status: [![Build Status](https://secure.travis-ci.org/jackl0phty/ansible-role-nmap.png?branch=master)](http://travis-ci.org/jackl0phty/ansible-role-arch-linux)

Role Name
=========

This Ansible role will focus on Arch Linux support.

Requirements
------------

Recent verson of Ansible.

Role Variables
--------------

arch_linux_group_packages - Arch Group packages to be installed.
arch_linux_additional_packages - Additional packages to be installed.

Dependencies
------------

A list of other roles hosted on Galaxy should go here, plus any details in regards to parameters that may need to be set for other roles, or variables that are used from other roles.

Example Playbook
----------------

    - hosts: servers
      roles:
         - { role: jackl0phty.arch_linux }

License
-------

Apache 2.0 License which can be found [here](https://www.apache.org/licenses/LICENSE-2.0).

Author Information
------------------

An optional section for the role authors to include contact information, or a website (HTML is not allowed).
