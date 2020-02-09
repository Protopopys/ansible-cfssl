[![Build Status](https://travis-ci.org/Protopopys/ansible-cfssl.svg?branch=master)](https://travis-ci.org/Protopopys/ansible-cfssl)

Ansible CFSSL
=========

Ansible role for installing CFSSL toolkit.

Role Variables
--------------

use_downloader
downloader
downloader_source_folder
cfssl_toolkit_bin_path
cfssl_toolkit_version
cfssl_toolkit_bin_name

Example Playbook
----------------

Including an example of how to use your role (for instance, with variables
passed in as parameters) is always nice for users too:

    - hosts: servers
      roles:
         - { role: ansible-cfssl, x: 42 }

License
-------

GPLv3

