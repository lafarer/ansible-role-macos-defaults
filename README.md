# macos-default

Ansible role to configure defaults on macOS

## Requirements

Ansible 2.0

## Role Variables

## Dependencies

## Example Playbook

```
    - hosts: servers
      vars:
        Bluetooth_Enabled: true
        Bluetooth_ShowInMenuBar: false

      roles:
         - { role: lafarer.macos-defaults }
```

## License

MIT

## Author Information