ansible-my_ubuntu_desktop
=========

This repo can't be used as role! :warning:

It's created only to simplify bootstrapping of my Ubuntu 14.04 desktop.

But if your env match with my one it might be useful.


Tested with:
- ansible 1.9.3
- Ubuntu 14.04

Requirements
------------

- [Ansible](http://docs.ansible.com/intro_installation.html)
- [Vagrant](http://www.vagrantup.com/downloads.html)
- [VirtualBox](https://www.virtualbox.org/wiki/Downloads)


Role Variables
--------------

defaults/main.yml

- docker_opts
- home_user
- docker_group_members
- python_virtualenv_root
- ruby_version


Dependencies
------------

none

Example Playbook
----------------

File `playbook.yml` contains an example of how to use this role

```yaml
- hosts: server
  sudo: true
#  There you can overwrite defaults/main.yml variables
  vars:
#    - home_user: 'bob'
  roles:
    - ansible-my_ubuntu_desktop
```

License
-------

BSD

Author Information
------------------

created by [Artem Zhurbila](http://www.linkedin.com/in/zhurbila)
