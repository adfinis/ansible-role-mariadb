ROLE MARIADB
=============

 [![License](https://img.shields.io/github/license/adfinis/ansible-role-mariadb.svg?style=flat-square)](https://github.com/adfinis/ansible-role-mariadb/blob/master/LICENSE)
[![GitHub](https://img.shields.io/github/actions/workflow/status/adfinis/ansible-role-mariadb/ansible-ci.yml?style=flat-square)](https://github.com/adfinis/ansible-role-mariadb/actions)
 [![Galaxy](https://img.shields.io/badge/galaxy-adfinis.mariadb-660198.svg?style=flat-square)](https://galaxy.ansible.com/adfinis/mariadb)

This role allows you to configure MariaDB server including databases, users and
SSL certificates.

## Requirements

None

## Role Variables

Check the [defaults/main.yml](defaults/main.yml) for available settings and description.

In [vars/<os_version>.yml](vars/) you can find OS specific vars and settings.

## Dependencies

None

## Example Playbook

You can include the role in your Ansible playbooks like any other role:

```yaml
  - hosts: servers
    roles:
       - adfinis.mariadb
```

## License

[GPL-3.0](https://github.com/adfinis/ansible-role-mariadb/blob/master/LICENSE)


## Author Information

mariadb role was written by:

* Adfinis AG [Website](https://adfinis.com/) | [Twitter](https://twitter.com/adfinis) | [GitHub](https://github.com/adfinis)
