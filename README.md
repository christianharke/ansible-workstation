# Ansible Playbook: Workstation

## Usage

## Install Ansible

> For other operating systems, see: <https://docs.ansible.com/ansible/latest/installation_guide/intro_installation.html>

### OS X

```sh
curl https://bootstrap.pypa.io/get-pip.py | sudo python
sudo pip install ansible
```

#### Note

On OS X 10.13+, it is necessary to be signed in the Mac App Store before running this playbook. For more details see: <https://github.com/mas-cli/mas/issues/164>

### Run PlayBook

```sh
ansible-galaxy install -r requirements.yml
ansible-playbook -K <env>.yml -e "hostname=<hostname>"
```

## Partially inspired by

- <https://github.com/mathiasbynens/dotfiles/blob/master/.macos>
- <https://github.com/paulmillr/dotfiles/blob/master/etc/macos.sh>
- <https://github.com/geerlingguy/dotfiles/blob/master/.osx>
- <https://github.com/wincent/wincent/blob/master/roles/defaults/tasks/main.yml>
