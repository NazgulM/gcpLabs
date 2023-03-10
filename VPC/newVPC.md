# Create new VPC 

Create VPC Network
Name -> IPv6 range disabled by default -> Subnets -> Custom for choosing needed subnet -> Add subnet --> Choose all IPV4 firewall rules, check all -> Dynamic routing mode -> Regional --> Create

For wordpress project I have to create firewall rule:
Create a firewall rule
Name -> Logs off -> network which is our new created VPC -> Priority 1000 -> Direction of traffic ->  Ingress
Specified target tags ->  target tags can give the name of my vm
-> Source filter IPv4 ranges --> 0.0.0.0/0 -> Protocols and port -> Specified protocols and ports -> TCP -> 80 for HTTP -> Create 