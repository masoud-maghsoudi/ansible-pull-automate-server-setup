Role Name
=========

Install ansible on managed nodes, so ansible-pull could be used for later automation.

Role Variables
--------------

In [defaults/main.yml](./defaults/main.yml) **"ansible_user"** has been set based on group names in [hosts.yml](../../hosts.yml) file. you can modify it if you would need.



Example Playbook
----------------

    - hosts: all
      roles:
         - ansible-init

License
-------

MIT

Author Information
------------------

| Author | Masoud Maghsoudi                      |
| ------ | ------------------------------------- |
| Email  | <masoud_maghsopudi@yahoo.com>         |
| Github | <https://github.com/masoud-maghsoudi> |