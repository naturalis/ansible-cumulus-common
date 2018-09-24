# Ansible Role: Cumulus common

Used in [network](https://github.com/naturalis/network/) repo.

Runnable with:
```bash
ansible-playbook playbooks/cumulus_provision.yml -i environments/prod
```

This role will set common settings like NTP, Hostname, Timezone, and a nice MOTD.

## Requirements

None.

## Role Variables

Available variables are listed below.
```bash
ntp:
  - '172.16.200.1'
  - '172.16.44.10'

timezone: 'Europe/Amsterdam'
```

## Dependencies

None.

## Example Playbook

    - hosts: switches
      roles:
        - ansible-cumulus-common

## License

Apache2
