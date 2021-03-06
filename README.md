# ansible-api

A restful http api for ansible 2.x
- v0.2.2 fit for ansible version <=2.3.x
- v0.2.6 fit for ansible version >=2.6.x (python>=3.5)

## What is it?

[Ansible](https://github.com/ansible/ansible/) is a radically simple IT automation system.
If you are trying to use it and not like CLI, you can try me now. I can provide you use ansible by A RESTful HTTP Api

## Changelog

- 0.2.6 adaptive ansible 2.6.4 and add asynchronization mode
- 0.2.2 optimize log
- 0.2.1 optimize log and allow mutil-instance in the same host
- 0.2.0 support websocket, remove code invaded in ansible

## How to install

- [preparatory work] python version >= 3.5 (use asyncio featrue)
- pip3 install git+https://github.com/lfbear/ansible-api.git

## How to use it

- default configuration: /etc/ansible/api.cfg
- start: 
```
ansible-api -c [Configfile, Optional] -d [Daemon Mode, Optional]
```
eg: ansible-api -c /etc/ansible/api.cfg -d > /dev/null &

## How to prepare your data

[HTTP API Usage](https://github.com/lfbear/ansible-api/wiki/http-api-usage)
