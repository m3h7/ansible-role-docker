# Role docker

Installs Docker to run in root mode.

## Requirements

This role requires Ansible 2.14 or higher.

## Role Variables

See `defaults/main.yml`.

## Dependencies

None.

## Example Playbook

Example show how to install Docker.

    - hosts: servers
      roles:
         - { role: m3h7.docker }

## License

MIT
