# Ansible Role: Rofi

[![CI](https://github.com/pluggero/ansible-role-rofi/actions/workflows/ci.yml/badge.svg)](https://github.com/pluggero/ansible-role-rofi/actions/workflows/ci.yml) [![Ansible Galaxy downloads](https://img.shields.io/ansible/role/d/pluggero/rofi?label=Galaxy%20downloads&logo=ansible&color=%23096598)](https://galaxy.ansible.com/ui/standalone/roles/pluggero/rofi)

An Ansible Role that installs a basic configuration of rofi.

## Requirements

Requires a compatible font; Recommended role: `pluggero.nerdfonts`.

## Role Variables

Available variables are listed below, along with default values (see `defaults/main.yml`):

```yaml
rofi_version: "x.x"
```

The version of rofi to install can be defined in the variable `rofi_version`.

```yaml
rofi_install_method: "dynamic"
```

The method used to install rofi can be defined in the variable `rofi_install_method`.
The following methods are available:

- `source`: Installs rofi from source
- `package`: Installs rofi from the package manager of the distribution
  - **NOTE**: This method installs the latest version available in the package manager and not the version defined in `rofi_version`.
- `dynamic`: Installs rofi from package manager if available in the correct version, otherwise installs from source

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
