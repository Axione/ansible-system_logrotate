# ansible-system_logrotate

## Description

[![Galaxy Role](https://img.shields.io/badge/galaxy-system_logrotate-purple?style=flat)](https://galaxy.ansible.com/lotusnoir/system_logrotate)
[![Version](https://img.shields.io/github/release/lotusnoir/ansible-system_logrotate.svg)](https://github.com/lotusnoir/ansible-system_logrotate/releases/latest)
[![GitHub repo size](https://img.shields.io/github/repo-size/lotusnoir/ansible-system_logrotate?color=orange&style=flat)](https://galaxy.ansible.com/lotusnoir/system_logrotate)
[![downloads](https://img.shields.io/ansible/role/d/)](https://galaxy.ansible.com/lotusnoir/system_logrotate)
[![Ansible Quality Score](https://img.shields.io/ansible/quality/)](https://galaxy.ansible.com/lotusnoir/system_logrotate)
[![License](https://img.shields.io/badge/license-Apache--2.0-brightgreen?style=flat)](https://opensource.org/licenses/Apache-2.0)

Configures logrotate options
## Requirements

none

## Role variables

See [variables](/defaults/main.yml) for more details.

## Examples

        ---
        - hosts: system_logrotate
          become: true
          become_method: sudo
          gather_facts: true
          roles:
            - role: ansible-system_logrotate


## License

This project is licensed under Apache License. See [LICENSE](/LICENSE) for more details.

## Author Information

- [Philippe LEAL](https://github.com/lotusnoir)
