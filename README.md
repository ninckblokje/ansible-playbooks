# ansible-playbooks

## Playbooks

|Playbook|Description|State|
|--------|-----------|-----|
|oudje.yml|Playbook for setting up OpenBSD on the host `oudje` (iMac G3)|Done|
|wsl2.yml||WIP|

## Commands

### Ping

````
ansible all -m ping
````

### Execution

````
ansible-playbook [PLAYBOOK_YML]
````

### Execution with sudo password

````
ansible-playbook [PLAYBOOK_YML] --ask-become-pass
````
