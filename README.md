# PROVISION

## Requirements

- [Vagrant](https://www.vagrantup.com/docs/installation/)
- [Ansible](http://docs.ansible.com/ansible/intro_installation.html#latest-releases-via-pip)

### Tested versions:
```
Vagrant 1.9.2
Ansible 2.2.1
```

## How to:

- run post-install configuration:
```
vagrant ssh controller -c 'ansible-playbook /vagrant/playbooks/post_install.yml'
```

- setup services:
```
vagrant ssh controller -c 'ansible-playbook /vagrant/playbooks/setup_services.yml'
```
