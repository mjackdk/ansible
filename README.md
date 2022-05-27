# ansible
Ansible playbooks for Fedora Workstation and Fedora Server

## Prerequisites
``` bash
$ sudo dnf install ansible
```

## Workstation

Only on localhost
``` bash
$ ansible-playbook -K workstation.yml
```


## Server
``` bash
$ ansible-playbook -i IP_ADDRESS, -K server.yml
```
