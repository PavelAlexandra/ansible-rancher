# ansible-rancher
Ansible role to pull and run a rancher server docker container


# DESCRIPTION

The role is used to pull and run a docker container with Rancher server.


Example of usage: 
```sh
- name: Deploy Rancher Server 
  hosts: rancher 
  roles: 
    - { role: ansible-rancher }
