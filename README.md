# Ansible Role for TeamViewer

[![Travis](https://img.shields.io/travis/com/alvistack/ansible-role-teamviewer.svg)](https://travis-ci.com/alvistack/ansible-role-teamviewer)
[![GitHub release](https://img.shields.io/github/release/alvistack/ansible-role-teamviewer.svg)](https://github.com/alvistack/ansible-role-teamviewer)
[![GitHub license](https://img.shields.io/github/license/alvistack/ansible-role-teamviewer.svg)](https://github.com/alvistack/ansible-role-teamviewer/blob/master/LICENSE)
[![Ansible Role](https://img.shields.io/badge/galaxy-alvistack.teamviewer-blue.svg)](https://galaxy.ansible.com/alvistack/teamviewer)

Ansible Role for TeamViewer Installation.

## Requirements

This role require Ansible 2.9 or higher.

This role was designed for:

  - Ubuntu 18.04/20.04
  - RHEL/CentOS 7/8
  - openSUSE Leap 15.2
  - Debian 10
  - Fedora 32

## Role Variables

[defaults/main.yml](defaults/main.yml)

## Dependencies

[ansible-galaxy-requirements.yml](ansible-galaxy-requirements.yml)

## Example Playbook

[molecule/default/converge.yml](molecule/default/converge.yml)

This role could simply deploy to `localhost` as below:

    molecule converge -s default

## License

  - Code released under [Apache License 2.0](LICENSE)
  - Docs released under [CC BY 4.0](http://creativecommons.org/licenses/by/4.0/)

## Author Information

  - Wong Hoi Sing Edison
      - <https://twitter.com/hswong3i>
      - <https://github.com/hswong3i>
