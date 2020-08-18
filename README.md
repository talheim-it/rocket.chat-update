# rocket.chat-update
Ansible script to update Rocket.Chat manual installation

Tested with
 - Ubuntu 18.04 Server

## Ansible command
ansible-playbook playbook/rocket-chat-update.yml

## Vars
```
- 
```

## Example playbook
```
- hosts: rocketchat.domain.tld
  roles:
     - rocket.chat-update
  vars: 
```

@ToDo:
Variables for Install and backup path