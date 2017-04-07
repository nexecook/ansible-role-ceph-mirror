# Ansible Role: Ceph Mirror

Installs the Ceph mirroring role

## Requirements

None.

## Role Variables

See `defaults/main.yml`.

## Dependencies

nexcess.mirror

## Add to Requirements

    - src: https://github.com/nexcess/ansible-role-ceph-mirror.git
      name: nexcess.ceph-mirror

## Example Playbook

    - hosts: servers
      roles:
        - nexcess.ceph-mirror

## License

MIT / BSD
