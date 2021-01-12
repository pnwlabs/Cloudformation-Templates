# Cloudformation-Templates
Repository for Hybrid Networking VPC Cloudformation Templates
Each one of these CF templates stands up a VPC with some basic features. Each revision adds a few more components to the mix.  The 
mk. 4 revision produces a VPC that is multi-AZ, with public and private subnets in each.  There are specific security groups for the Ec2 instances in each subnet.
There is a NAT gateway for private subnet.  There is a Site to Site VPN created as well.  Lastly the Ec2 webserver is automatically registered with Route53 DNS to prvide a FQDN to reach the webserver.


