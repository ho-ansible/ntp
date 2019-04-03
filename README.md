# Ansible role: ntp
Keeps system clock synchronized to a network time protocol server.

## Requirements
Only tested on Debian stable, for now.

## Role Variables
+ `ntp_subnet` / `ntp_mask`: subnet allowed to query
+ `ntp_servers` (default: pool.ntp.org): upstream servers

## Dependencies
None.

## Example Playbook

```
- hosts: ntp
  roles:
    - { role: ho-ansible.ntp }
```

## License
MIT

## Author Information
Sean Ho, https://github.com/ho-ansible/

