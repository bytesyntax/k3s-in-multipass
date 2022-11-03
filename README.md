# k3s-in-multipass
K3s in multipass is created to setup a k3s cluster over a number of VMs. When run VMs are created via multipass and k3s is installed and connected to the new cluster.
The first node in the list is treated as a control plane node and the remainder as workers.

## Syntax
Just run the script `k3s-in-multipass`

Variables for VMs, RAM and disk size can be changed at the top of the script as needed.

## Prerequisite
Application multipass needs to be installed on the system.
