# ansible-pull-automate-server-setup
 Automate server setup with the help of ansible-pull and defined roles

## Description
The [main.yml](./main.yml) is used to install and initiate ansible on the managed node. you can deploy it in the first place. It also set a cron job on to automate running ansible-pull based on your needs. you can modify the repository URL for your ansible-pull on [main.yml](./main.yml).

    ansible-playbook main.yml -i hosts.yml

The [local.yml](./local.yml) is a playbook which ansible-pull uses to run. you can add tasks and roles to manage all the automation steps you need. In this demonstration I added [package-mange](./roles/package-manage/) role to maintain packages on the server. for further information about this role you can read its [README.md](./roles/package-manage/README.md) file.


## License

MIT

## Author Information

| Author | Masoud Maghsoudi                      |
| ------ | ------------------------------------- |
| Email  | <masoud_maghsopudi@yahoo.com>         |
| Github | <https://github.com/masoud-maghsoudi> |
