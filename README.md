# Ansible Role: PostgreSQL-Client

Installs PostgreSQL client on Debian and Ubuntu servers.

[![Build Status](https://travis-ci.org/AlphaNodes/ansible-postgresql-client.svg?branch=master)](https://travis-ci.org/AlphaNodes/ansible-postgresql-client)

## Dependencies

  none

## Example Playbook

    - hosts: db-client
      vars:
        postgresql_client_use_repo: yes
      roles:
        - AlphaNodes.postgresql-client

## License

GPL Version 3

This ansible role is taken mostly out of [ansible-postgresql-client](https://github.com/azavea/ansible-postgresql-client.git) from Azavea Inc., but I stripped it down for brevity.