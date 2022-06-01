# ansible
Ansible playbooks for Fedora Workstation, Fedora Server and macOS

## Fedora Workstation

On localhost:
``` bash
$ sudo dnf install ansible

$ git clone https://github.com/mjackdk/ansible.git
$ cd ansible

$ ansible-playbook -K workstation.yml
```

## Fedora Server

On workstation, with ssh access to server:
``` bash
$ sudo dnf install ansible

$ git clone https://github.com/mjackdk/ansible.git
$ cd ansible

$ ansible-playbook -i IP_ADDRESS, -K server.yml
```
## macOS

On localhost:
``` bash
$ xcode-select --install

$ sudo pip3 install --upgrade pip
$ sudo pip3 install ansible

$ git clone https://github.com/mjackdk/ansible.git
$ cd ansible

$ ansible-galaxy install -r requirements.yml
$ ansible-playbook -K macos.yml
```
