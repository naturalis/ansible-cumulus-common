# Ansible Role: Cumulus common

Used in [network](https://github.com/naturalis/network/) repo.

Runnable with:
```bash
ansible-playbook playbooks/cumulus_provision.yml -i environments/prod
```

## Requirements

None.

## Role Variables

Available variables are listed below, along with default values (see `defaults/main.yml`):

```bash
..
```

## Dependencies

None.

## Example Playbook

    - hosts: switches
      roles:
        - ansible-role-cumulus-common

## License

Apache2
