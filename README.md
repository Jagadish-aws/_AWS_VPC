# _AWS_VPC


Terraform module for Amazon AWS VPC

# Terraform module for Amazon AWS VPC

This Terraform module creates:

* Amazon AWS VPC
* Internet Gateway
* Subnets in all configured availability zones and routing tables linking them to the Internet Gateway (public subnets)

Additionally, if variable `private_subnets` is set to true, it will create:

* NAT with Elastic IP address in each availability zone
* Private subnet in each availability zone with routing tables linking them to the NAT



