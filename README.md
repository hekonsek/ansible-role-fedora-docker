# Ansible role: Fedora firewall port

Ensures that firewall is installed and running, then ensures that given port on firewall is open.

## Compatibility

This playbook has been tested against Fedora 25.

## Installation 

    ansible-galaxy install hekonsek.fedora-firewall-port,0.0

## Example playbook

    # Open port 80
    - hosts: localhost
      roles:
        - { role: hekonsek.fedora-firewall-port,0.0, vars: {targetPort: 80}  }

## License

Apache 2.0# ansible-role-fedora-docker
