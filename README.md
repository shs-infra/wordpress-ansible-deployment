# Ansible Demo - WordPress Setup (WIP)

This is a simple Ansible project to provision a basic web server.

## What it does
- Updates system packages
- Installs Nginx
- Starts and enables Nginx

## How to run
ansible-playbook -i inventories/inventory.ini playbooks/site.yml

## Tech
- Ansible
- Linux