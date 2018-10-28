# Usage:

1. Install Ansible:
    > For other operating systems, see: https://docs.ansible.com/ansible/latest/installation_guide/intro_installation.html
  - OS X:
    ```sh
    $ curl https://bootstrap.pypa.io/get-pip.py | sudo python
    $ sudo pip install ansible
    ```
2. Run PlayBook: `ansible-playbook -K <env>.yml -e "hostname=<hostname>"`
