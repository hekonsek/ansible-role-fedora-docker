# Ansible role: Fedora Docker

Ensures that Docker engine (17.09) is installed and running as a systemd service. Also installs Docker client.

## Compatibility

This playbook has been tested against Fedora 27.

## Installation 

    ansible-galaxy install hekonsek.fedora-docker,0.2

## Example playbook

    - hosts: localhost
      remote_user: root
      roles:
        - { role: "hekonsek.fedora-docker,0.2" }

## License

Apache 2.0
