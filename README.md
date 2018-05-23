andrewrothstein.ksonnet
=========
[![Build Status](https://travis-ci.org/andrewrothstein/ansible-ksonnet.svg?branch=master)](https://travis-ci.org/andrewrothstein/ansible-ksonnet)

Installs [ksonnet](https://ksonnet.io/).

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
    - andrewrothstein.ksonnet
```

License
-------

MIT

Author Information
------------------

Andrew Rothstein <andrew.rothstein@gmail.com>
