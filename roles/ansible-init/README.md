# ansible-init

Install ansible on managed nodes, so ansible-pull could be used for later automation.

## Variables

In [defaults/main.yml](./defaults/main.yml) **"ansible_user"** has been set based on group names in [hosts.yml](../../hosts.yml) file. you can modify it if you would need.

## Ansible Galaxy

In order to install this role from ansible galaxy you could use command below:

    ansible-galaxy role install masoud-maghsoudi.ansible-init

## Example Playbook

    - hosts: all
      gather_facts: true
      roles:
         - masoudi-maghsoudi.ansible-init

## License

MIT

## Author Information

| Author | Masoud Maghsoudi                      |
| ------ | ------------------------------------- |
| Email  | <masoud_maghsopudi@yahoo.com>         |
| Github | <https://github.com/masoud-maghsoudi> |
