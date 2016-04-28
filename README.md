# OpenStack-mitaka (All-in-one node using single NIC) for Ubuntu 14.04LTS
Bash script to install openstack-Mitaka in ubuntu 14.04LTS
![alt tag](https://github.com/CloudenablersPvtLtd/openstack-setup/blob/mitaka/openstack-mitaka/mitaka_configration/openstack-mitaka-logo.png)
>Download the script using the below command:
>>git clone https://github.com/vinothkumarselvaraj/openstack-mitaka.git

>>cd openstack-mitaka/

>Script Usage: bash install.bash --ip_address [Your server Ip] --interface_name [interface name]

>Example: bash install.bash --ip_address 192.168.1.172 --interface_name eth0

IMPORTANT:
  - Use this script in the fresh ubuntu 14.04LTS machine.
  - Must have static IP configured.
  - This script use same NIC/IP for Management/External/VM Datapath networks.
  - Make sure that the IP you have given must have internet connectivity.
  - The interface name must be the NIC name of above mentioned IP.

> Author: Vinoth Kumar Selvaraj

> E-Mail: vinothkumar.s@cloudenablers.com

> website: www.cloudenablers.com

> Date: 20-april-2016 ![alt tag](https://github.com/vinothkumarselvaraj/openstack-mitaka/blob/master/mitaka_configration/logo-splash.png)
