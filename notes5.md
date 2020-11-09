# Notes 5 Networking & Connectivity

### Summarize a few key points made in the readings or videos.
+ Types of Network Topologies Star, Mesh, Ring, Daisy Chain
+ Protocols are sets of rules for which two entities can communicate
+ Every device in the network is a known as Hostname
+ CIDR address ex /24 is 256 IP addresses 0 to 255
+ DNS is Domain Name System
+ Subnets that can't access the internet are private subnets
+ VPNs connect users by encrypting data being sent

### Identify two quotes that were made, that you found interesting.
a. "In simplest words, it is a global network of smaller networks interconnected using communication protocols that are standardized. The Internet standards describe a framework known as the Internet protocol suite" (7.02)
<br/>
b. "An internet gateway serves two purposes: to provide a target in your VPC route tables for internet-routable traffic, and to perform network address translation (NAT) for instances that have been assigned public IPv4 addresses" (7.12)

### What new facts did you learn from this section?
+ Type “ipconfig” in the command prompt and press ‘Enter’, this gives us the IP address of the device.
+ Type “netstat -a” in the command prompt and press ‘Enter’, this lists all the ports being used.
+ The command ‘nslookup’ gives you the IP address of the domain you are looking for. This also provides the information of our DNS Server.

### What questions remain in your mind after reading this section?
a. Can a VPC be publicly available but still be secured in a private cloud?<br/>
b. How do they determine a CIDR number equals a certain number of IP addresses? Ex /24 = 256 ip addresses
