andrewrothstein.awscli
=========
![Build Status](https://github.com/andrewrothstein/ansible-awscli/actions/workflows/build.yml/badge.svg)

Installs the Amazon AWS [cli](https://aws.amazon.com/cli/).

Requirements
------------

See [meta/main.yml](meta/main.yml)

Role Variables
--------------

See [defaults/main.yml](defaults/main.yml)

Dependencies
------------

See [meta/main.yml](meta/main.yml)

Example Playbook
----------------

```yml
- hosts: servers
  roles:
    - andrewrothstein.awscli
```

License
-------

MIT

Author Information
------------------

Andrew Rothstein <andrew.rothstein@gmail.com>
