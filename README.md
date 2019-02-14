# Ansible Role: Cumulus common

This role will set common settings like NTP, Hostname, Timezone, and a nice MOTD.

Naturalis uses this role together with a private inventory.

## Requirements

None.

## Role Variables

Available variables are listed below.
```bash
timezone: 'Etc/UTC'
resolv_conf:
  - 10.114.0.1
ntp:
  servers:
    - '192.168.1.1'
    - '192.168.1.2'
  interfaces:
    - vlan114
```

## Dependencies

None.

## Example Playbook
```bash
    - hosts: switches
      roles:
        - ansible-cumulus-common
```
## License

Apache2
