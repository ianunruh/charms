## Development

Useful commands

```bash
cd /vagrant

juju deploy local:$CHARM_NAME

juju resolved -r $SERVICE_NAME/0

juju remove-unit $SERVICE_NAME/0
juju upgrade-charm $SERVICE_NAME
juju add-unit $SERVICE_NAME
```
