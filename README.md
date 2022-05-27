# ansible
Ansible playbooks for home network

## Workstation
``` bash
$ ansible-playbook -K workstation.yml
```


## Server
``` bash
$ ansible-playbook -i IP_ADDRESS, -K server.yml
# Only on x86_64 systems
$ ansible-playbook -i IP_ADDRESS, -K machines.yml
```
