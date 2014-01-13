## Common Tasks

### Update the VM to a new version of Mesos

Set `mesos_deb_url` in the profile's [config.json][15] to a newer version of
Mesos and re-provision the VM. New package links can be found on Mesosphere's
[Downloads](http://mesosphere.io/downloads) page.

```bash
( cd profiles/ubuntu_13.04 && vagrant provision )
```

### Connect to the VM directly with SSH
```bash
ssh -i ~/.vagrant.d/insecure_private_key -p 2222 vagrant@10.141.141.10
```

This will result in an SSH session similar to:
```bash
( cd profiles/ubuntu_13.04 && vagrant ssh )
```

[15]: config.md "Configuration"
