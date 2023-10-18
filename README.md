# Ansible role: ntp
Keeps system clock synchronized to a network time protocol server.

## DEPRECATED
This ansible role is no longer maintained.

## Requirements
Only tested on Debian stable, for now.

## Role Variables
+ `ntp_subnet` / `ntp_mask`: subnet allowed to query
+ `ntp_servers` (default: pool.ntp.org): upstream servers

## Playbooks
+ `main.yml`: apply role
+ `uninstall.yml`: remove. Run before removing config from inventory.

## Dependencies
None.

## License
+ Ansible role licensed [MIT](LICENSE)

## Author Information
+ Ansible role by [Sean Ho](https://github.com/ho-ansible/)
