## Usage

```bash
cd /vagrant

juju deploy local:sensu-server

juju deploy rabbitmq-server rabbitmq
juju add-relation sensu-server rabbitmq

juju deploy redis-master redis
juju add-relation sensu-server redis:redis-master
```
