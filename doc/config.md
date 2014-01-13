# Playa Mesos Configuration

### config.json
Each profile has a `config.json` where the following options must be set.

<dl>
  <dt>box_name</dt>
  <dd>Vagrant box-name</dd>

  <dt>box_url</dt>
  <dd>URL where the Vagrant box image can be downloaded</dd>

  <dt>ip_address</dt>
  <dd>IP address used by the VM on a private network using a /24 netmask</dd>

  <dt>vm_ram</dt>
  <dd>MB of RAM allocated to the VM</dd>

  <dt>vm_cpus</dt>
  <dd>Number of CPU cores allocated to the VM</dd>

  <dt>mesos_deb_url</dt>
  <dd>URL where the Mesos debian package can be downloaded</dd>
</dl>
