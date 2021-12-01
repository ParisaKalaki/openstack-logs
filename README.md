## openstack nova logs

This repository contains the OpenStack nova logs which are created by a [DevStack](https://docs.openstack.org/devstack/latest/) single virtual machine.  

### logs speification 

| Name                                          | Description             |
|-----------------------------------------------|-------------------------|
| openstack-nova-normal-vm-create               | 100k normal log         |
| openstack-vm-destroy-immediately-after-create | 13k abnormal log type 1 |
| openstack-nova-undefine-vm-after-create       | 45k abnormal log type 2 |
| openstack-nova-dhcpoff                        | 4k abnormal log type 3  |
| openstack-nova-sample                         | 25k normal+abnormal log |
