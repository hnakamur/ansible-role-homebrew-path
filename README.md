osx-homebrew-path
=================

An Ansible role to configure PATH for homebrew

Requirements
------------

[Homebrew](http://brew.sh/) must be installed.

Role Variables
--------------

homebrew_prefix: /usr/local

Dependencies
------------

- hnakamur.oh-my-zsh

Example Playbook
----------------

    - hosts: servers
      roles:
         - hnakamur.osx-homebrew

License
-------

MIT

Author Information
------------------

[Hiroaki Nakamura]( http://hnakamur.github.io/ )
