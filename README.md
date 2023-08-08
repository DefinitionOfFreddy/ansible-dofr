# ansible-doffr
Personal repository to save my laptop configuration thanks to Ansible.


To play the playbook locally, clone this repo, cd throuh it and run the following command : 

```console
ansible-playbook -b -i localhost, -c local playbook.yml -K
```

This command will play the playbook with the inventory localhost (your machine), the connection local (no ssh needed), and will ask your sudo password (the K option)