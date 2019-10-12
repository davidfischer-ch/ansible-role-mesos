# Ansible Role mesos

Library of Ansible plugins and roles for deploying various services.
See [ansible-roles](https://github.com/davidfischer-ch/ansible-roles) for additional documentation.

This repository hosts the role mesos and may depend of other roles and plugins of the library.

## Status

This role is not complete, old and (probably) outdated.
Apache MesOS 1.4.1 was released the 16th November 2017.

## Dependencies

See [meta](meta/main.yml).

## Variables

TODO VARIABLES

## Example

### PlayBook

```
- hosts:
    - mesos
  roles:
    - mesos
```

### Variables

```
java_apt_repository: ''
java_version: 8

mesos_version: 1.4.1
```

## License

See [LICENSE.rst](LICENSE.rst).

## Authors

See [AUTHORS](AUTHORS).

2014-2019 - David Fischer
