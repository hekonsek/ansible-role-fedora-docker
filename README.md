# Ansible role: Fedora Docker

Ensures that Docker engine is installed and running as a systemd service. Also installs Docker client.

## Compatibility

This playbook has been tested against Fedora 25.

## Installation 

    ansible-galaxy install hekonsek.fedora-docker,0.0

## Example playbook

    - hosts: localhost
      remote_user: root
      roles:
        - { role: "hekonsek.fedora-docker,0.0" }

## License

Apache 2.0
