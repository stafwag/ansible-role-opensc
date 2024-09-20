# Ansible Role: opensc

An ansible role to install opensc packages and enable the opensc service. 

## Requirements

### Supported platforms

* GNU/Linux
* FreeBSD

## Installation

### Ansible galaxy

The role is available on [Ansible Galaxy](https://galaxy.ansible.com/ui/standalone/roles/stafwag/opensc).

To install the role from Ansible Galaxy execute the command below. 

```bash
ansible-galaxy install stafwag.opensc
```
### Source Code

If you want to use the source code directly.

Clone the role source code.

```bash
$ git clone https://github.com/stafwag/ansible-role-opensc
```

and put into the [role search path](https://docs.ansible.com/ansible/2.4/playbooks_reuse_roles.html#role-search-path)

## Role Variables

None

## Dependencies

None

## Example Playbook

```
---
- name: Setup ansible server
  hosts: ansible
  become: true
  roles:
    - stafwag.opensc
```
## License

MIT/BSD

## Author Information

Created by Staf Wagemakers, email: staf@wagemakers.be, website: https://www.wagemakers.be, my company https://mask27.dev
