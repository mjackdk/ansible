# ansible
Ansible playbooks for Fedora Workstation, Fedora Server and macOS. Tested on F36 and Big Sur.

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

Log in to App Store before running the ansible playbook.

On localhost:
``` bash
$ xcode-select --install

$ pip3 install --upgrade --user pip
$ export PATH=$HOME/Library/Python/3.8/bin:$PATH
$ pip3 install --user ansible

$ git clone https://github.com/mjackdk/ansible.git
$ cd ansible

$ ansible-galaxy install -r requirements.yml
$ ansible-playbook -K macos.yml
```
A reboot might be needed for some changes to take effect
