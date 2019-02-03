[![Build Status](https://travis-ci.org/marvel-nccr/ansible-role-add-user.svg?branch=master)](https://travis-ci.org/marvel-nccr/ansible-role-add-user)
# Ansible Role: marvel-nccr.add_user

An ansible role that adds a user with public key and/or password.

## Installation

`ansible-galaxy install marvel-nccr.add_user`

## Role Variables

See `defaults/main.yml`.

## Example Playbook

```
  - hosts: servers
    roles:
    - role: marvel-nccr.add_user
```

## License

MIT

## Contact

Please direct inquiries regarding Quantum Mobile and associated ansible roles to the [AiiDA mailinglist](http://www.aiida.net/mailing-list/).
