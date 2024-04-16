# dockerhost_ansible
Ansible playbook for setting up host to run docker containers

## Requirements

* A fresh install of**Ubuntu 20.04**, **CentOS 7.4+**, or **Debian 9**.
* **python** installed for ansible to work. This playbook will try to install python first.

## Generic steps

1. Check the `hosts.example` file on the required variables for your ansible hosts file `/etc/ansible/hosts`

## Steps For Full Install

1. Install your OS. Maybe use https://github.com/neilmillard/host_ansible
2. Set up ansible on your controller machine and make sure that your server has the required entry in the `/etc/ansible/hosts` file.
3. Run the playbook `ansible-playbook dockerhost.yml -b -K`

