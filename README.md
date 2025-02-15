# Ansible Role: Rofi

[![CI](https://github.com/pluggero/ansible-role-rofi/actions/workflows/ci.yml/badge.svg)](https://github.com/pluggero/ansible-role-rofi/actions/workflows/ci.yml) [![Ansible Galaxy downloads](https://img.shields.io/ansible/role/d/pluggero/rofi?label=Galaxy%20downloads&logo=ansible&color=%23096598)](https://galaxy.ansible.com/ui/standalone/roles/pluggero/rofi)

An Ansible Role that installs a basic configuration of rofi.

## Requirements

Requires a compatible font; Recommended role: `pluggero.nerdfonts`.

## Role Variables

Available variables are listed below, along with default values (see `defaults/main.yml`):

## Dependencies

None.

## Example Playbook

```yaml
- hosts: all
  roles:
    - pluggero.rofi
```

## License

MIT / BSD

## Author Information

This role was created in 2025 by Robin Plugge.
