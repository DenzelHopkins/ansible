# Ansible playbooks for different purposes

## Developer environment for ubuntu 22.04.1

### Run ubuntu playbook for inventory staging
> ansible-playbook -i inventories/staging ubuntu.yml

## Ansible vault

### Encrypt
> ansible-vault encrypt roles/ubuntu/defaults/vars/main.yml 

### Decrypt
> ansible-vault decrypt roles/ubuntu/defaults/vars/main.yml 

toDo:
- fix versions of programs