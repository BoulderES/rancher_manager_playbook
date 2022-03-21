# Rancher Manager Cluster Deployment Playbook

## Prerequisites

In order to deploy the environment 3 masters will be needed.  
Recommended resources:
- Masters: 4CPUs and 4Gi (min)

This playbook has been tested just in RHEL 8.5 VMs with the mentioned resources with satisfactory results.

The VMs must have the hostname and static IPs configured and if possible the ssh key added.

A DNS server is helpful in order to guarantee the servers' visibility. For this example a VM running containerized pihole and configured as dns server in the VMs was enough.

## License

This project is under the Apache License 2.0 - take a look to the LICENSE file for more details.
