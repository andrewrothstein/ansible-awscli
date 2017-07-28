andrewrothstein.awscli
=========
[![Build Status](https://travis-ci.org/andrewrothstein/ansible-awscli.svg?branch=master)](https://travis-ci.org/andrewrothstein/ansible-awscli)

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
