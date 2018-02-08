# Ansible Role: Docker

[![Build Status](https://travis-ci.org/michft/ansible-role-docker.svg?branch=master)](https://travis-ci.org/michft/ansible-role-docker)

An Ansible Role that installs [Docker](https://www.docker.com) on Linux.

## Requirements

None.

## Why?

Mostly a copy of Jeff Geerling's Docker role BUT;

  - Uses Docker destroy/create methods from docker documentation.
  - Uses become rather than assuming sudo.
  - Haven't done one of these yet.

## Dependencies

None.

## Example Playbook

```yaml
- hosts: all
  roles:
    - michft.docker
```

## License

MIT / BSD

