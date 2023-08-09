# ansible-doffr
Personal repository to save my laptop configuration thanks to Ansible.


To play the playbook locally, clone this repo, cd throuh it and run the following command : 

```console
ansible-playbook -b -i localhost, -c local playbook.yml -K
```

This command will play the playbook with the inventory localhost (your machine), the connection local (no ssh needed), and will ask your sudo password (the K option)


To play it without cloning this project, you can use [ansible-pull](https://docs.ansible.com/ansible/latest/cli/ansible-pull.html) :

```command
ansible-pull -U https://github.com/definitionoffreddy/ansible-dofr  playbook.yml -i localhost, -K
```
