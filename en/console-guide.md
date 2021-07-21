## Network > Network Interface > Console User Guide


#### Create network interface

* Name: Enter a name for the network interface.
* VPC: Select the VPC in which to create the network interface.
* Subnet: Select the subnet in which to create the network interface.
* Select security group: Select the security group to use on the network interface. Multiple selections can be made.

Click **OK** to create the network interface.

#### Change network interface
Among the properties of the network interface, you can change the name, IP, and security group.
Changes can be made without a floating IP connection.

#### Delete network interface
Delete the network selected interface.
A network interface cannot be deleted if connected to the device.

#### Change source/target check
You can enable or disable source/target check to determine if it is the source or target of the traffic that the instance receives.
For network interfaces of NAT instances, source/target check should not be enabled, so manage the enable/disable features through this menu.

> [Reference] Difference between creating a network interface when creating an instance and assigning an existing network interface
>
> When creating a new network interface when creating an instance, if you delete the instance, the automatically created network interface is also deleted.
> However, when creating an instance by assigning an existing network interface and deleting the connected instance, the network interfaces used by the instance will not be deleted together. The remaining network interfaces can be connected and used by other instances in the future.
