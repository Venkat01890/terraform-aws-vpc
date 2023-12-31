### VPC

This module is going to create
* VPC
* Internet Gateway
* 2 Public subnets
* 2 private subnets
* 2 database subnets

### Inputs
* cidr_block(Required) - User has to provide cidr block
* enable_dns_hostnames(Optional) - User can provide enable_dns_hostnames(Optional) ***default is true***
* enable_dns_support(Optional) - User can provide enable_dns_support(Optional) ***default is true***
* common_tags(Optional) - User can provide common_tags for all resources, ***default is empty***
* vpc_tags(Optional) - User can provide vpc_tags for all resources, ***default is empty***
* igw_tags(Optional) - User can provide internet gateway tags for internet gateway resources, ***default is empty***
* public_subnet_cidr(Required) - User must provide a list of 2 public subnet CIDR
* public_subnet_names(Required) - User must provide a list of 2 public subnet names
* private_subnet_cidr(Required) - User must provide a list of 2 private subnet CIDR
* private_subnet_names(Required) - User must provide a list of 2 private subnet names
* database_subnet_cidr(Required) - User must provide a list of 2 database subnet CIDR
* database_subnet_names(Required) - User must provide a list of 2 database subnet names
