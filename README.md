# Cockpit

This role handles installing Cockpit and enabling it start on boot.

## Requirements

The hosts you are targeting should have the following packages:

- python >= 2.6
- python-dnf

## Role Variables

None

## Dependencies

None

## Example Playbook

```yaml
- hosts: servers
  roles:
    - role: jaredhocutt.cockpit
```

## License

MIT

## Author Information

Jared Hocutt (@jaredhocutt)
