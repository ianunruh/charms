## Usage

```bash
cd /vagrant

juju deploy local:sensu-api

juju deploy redis-master redis
juju add-relation sensu-api redis:redis-master
```

