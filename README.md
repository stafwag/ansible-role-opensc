# Ansible Role: opensc

An ansible role to install opensc packages and enable the opensc service. 

## Requirements

### Supported platforms

* GNU/Linux
* FreeBSD

## Role Variables

None

## Dependencies

None

## Example Playbook

```
---
- name: setup ansible server
  hosts: ansible
  become: true
  roles:
    - stafwag.opensc
```
## License

MIT/BSD

## Author Information

Created by Staf Wagemakers, email: staf@wagemakers.be, website: http://www.wagemakers.be.
