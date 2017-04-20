[![CircleCI](https://circleci.com/gh/andrewrothstein/ansible-elasticsearch.svg?style=svg)](https://circleci.com/gh/andrewrothstein/ansible-elasticsearch)
andrewrothstein.elasticsearch
=============================

Installs [Elasticsearch](https://www.elastic.co/).

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
    - andrewrothstein.elasticsearch
```

License
-------

MIT

Author Information
------------------

Andrew Rothstein <andrew.rothstein@gmail.com>
