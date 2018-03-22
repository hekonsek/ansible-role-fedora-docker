# Ansible role: Fedora Docker

Ensures that:
- Docker engine is installed and running as a systemd service
- Docker client is installed
- `docker` user group exists and `fedora` user is assigned to it

## Compatibility

This playbook has been tested against Fedora 27.

## Installation 

    ansible-galaxy install hekonsek.fedora-docker,0.5

## Example playbook

    - hosts: localhost
      remote_user: root
      roles:
        - { role: hekonsek.fedora-docker,0.5 }

## License

Apache 2.0
