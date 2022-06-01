# ansible
Ansible playbooks for Fedora Workstation, Fedora Server and macOS

## Fedora Workstation

On localhost:
``` bash
$ sudo dnf install ansible
$ git clone https://github.com/mjack/ansible.git
$ cd ansible
$ ansible-playbook -K workstation.yml
```

## Fedora Server

On workstation:
``` bash
$ sudo dnf install ansible
$ git clone https://github.com/mjack/ansible.git
$ cd ansible
$ ansible-playbook -i IP_ADDRESS, -K server.yml
```
## macOS

On localhost:
``` bash
$ sudo pip3 install --upgrade pip
$ sudo pip3 install ansible
$ git clone https://github.com/mjack/ansible.git
$ cd ansible
$ ansible-playbook -K macos.yml
```
