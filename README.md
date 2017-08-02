andrewrothstein.acbuild
=========
[![Build Status](https://travis-ci.org/andrewrothstein/ansible-acbuild.svg?branch=master)](https://travis-ci.org/andrewrothstein/ansible-acbuild)

Installs [acbuild](https://github.com/containers/build).

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
    - andrewrothstein.acbuild
```

License
-------

MIT

Author Information
------------------

Andrew Rothstein <andrew.rothstein@gmail.com>
