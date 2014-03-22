Ansible Testing with Vagrant
============================

## Vagrant Setup

    $ vagrant box list
        ansibleDebian  (virtualbox)
        asnibleCentos6 (virtualbox)

### Nodes

nodes = [
  { :hostname => 'ex7proxy',   :ip => '192.168.0.40', :box => 'ansibleDebian' },
  { :hostname => 'ex7db',      :ip => '192.168.0.41', :box => 'asnibleCentos6' },
  { :hostname => 'ex7web1',    :ip => '192.168.0.42', :box => 'ansibleDebian' },
  { :hostname => 'ex7web2',    :ip => '192.168.0.43', :box => 'asnibleCentos6' },
  { :hostname => 'ex7static1', :ip => '192.168.0.44', :box => 'ansibleDebian' },
  { :hostname => 'ex7static2', :ip => '192.168.0.45', :box => 'asnibleCentos6' },
  { :hostname => 'ex7cache',   :ip => '192.168.0.46', :box => 'ansibleDebian' },
]

    
    --private-key=~/.vagrant.d/insecure_private_key -u vagrant



