# Ansible role: nginx web server

## Requirements
Only tested on Debian stable, for now.

## Role Variables
+ `variable`: description
+ `nginx_keystore` (default: `{{ inventory_dir }}/.nginx/ssl`): local dir storing SSL certs

## Playbooks
+ `main.yml`: apply role

## Dependencies
None.

## License
MIT

## Author Information
Sean Ho, https://github.com/ho-ansible/
