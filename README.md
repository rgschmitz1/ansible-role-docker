# Ansible Role - Docker

Installs docker and docker-compose on Linux.

## Requirements

None

## Role Variables

See `defaults/main.yml` for a list of supported variables.

## Dependencies

None.

## Example Playbook

```yaml
---
- hosts: all
  become: yes
  roles:
     - rgschmitz1.docker
```

## License

BSD

## Author Information

Created by [Robert Schmitz III](https://www.rgschmitz.com).
