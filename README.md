# Ansible Role - Docker

Installs docker-ce and docker-compose on Debian and Ubuntu distributions.

## Requirements

None

## Role Variables

```
# Must be one of: true, or false
docker_install_compose: true
# Must be one of: absent, latest, present
docker_packages_state: present
```

## Dependencies

None

## Example Playbook

```yaml
---
- hosts: all
  become: true
  roles:
     - rgschmitz1.docker
```

## License

BSD

## Author Information

Created by [Robert Schmitz III](https://www.rgschmitz.com).
