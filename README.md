Ansible RabbitMQ
================

Install and configure rabbitmq on Debian server.

Installation
------------

git submodule add git@github.com/boostmyshoporganization/ansible-rabbitmq roles/rabbitmq

```yaml
roles:
    - rabbitmq
```

Configuration
-------------

```yaml
rabbitmq:
  node_name: "main@localhost"
```
