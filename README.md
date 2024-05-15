# ansible apt collection

[![](https://github.com/damex/ansible-collections-apt/workflows/linting/badge.svg)](https://github.com/damex/ansible-collections-apt/actions)

## Description

The apt collection is designed to be used with any modern Debian Linux derivatives.

## Installation

There are multiple ways to incorporate the apt collection into your ansible environment.

`Ansible Galaxy` users can add apt collection using the following command:

```bash
ansible-galaxy collection install damex.apt
```

`Ansible Galaxy` users can also add apt collection to requirements.yml:

```requirements.yml
collections:
  - name: damex.apt
    version: 1.4.1
```

and install it afterward using the following command:

```bash
ansible-galaxy install --role-file requirements.yml --force --force-with-deps
```

## Roles Included
* [damex.apt_cache](roles/apt_cache/README.md)
* [damex.apt_keys](roles/apt_keys/README.md)
* [damex.apt_packages](roles/apt_packages/README.md)
* [damex.apt_preferences](roles/apt_preferences/README.md)
* [damex.apt_repositories](roles/apt_repositories/README.md)

You can report bugs or feature requests at:

* https://github.com/damex/ansible-collections-apt/issues
