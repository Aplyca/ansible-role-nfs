# Ansible Role: NFS Server

[![Build Status](https://travis-ci.org/Aplyca/ansible-role-nfs.svg?branch=master)](https://travis-ci.org/Aplyca/ansible-role-nfs)
[![Circle CI](https://circleci.com/gh/Aplyca/ansible-role-nfs.png?style=badge)](https://circleci.com/gh/Aplyca/ansible-role-nfs)

Ansible Role that installs an configure Nginx on Debian/Ubuntu.

## Requirements

Use hash behavior for variables in ansible.cfg
See example: https://github.com/Aplyca/ansible-role-nginx/blob/master/tests/ansible.cfg
See official docs: http://docs.ansible.com/intro_configuration.html#hash-behaviour

## Installation

Using ansible galaxy:
```bash
ansible-galaxy install Aplyca.NFS
```
You can add this role as a dependency for other roles, add the role to the meta/main.yml file of your own role:
```yaml
dependencies:
  - { role: Aplyca.NFS }
```

## Role Variables

See default variables: https://github.com/Aplyca/ansible-role-nfs/blob/master/defaults/main.yml

## Dependencies

None.

## Testing

Use Vagrant to test the role:

```bash
cd tests;
vagrant up;
```

## License

MIT / BSD

## Author Information

Mauricio Sánchez from Aplyca SAS (http://www.aplyca.com)
