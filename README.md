# Build a Virtual Private Cloud

**Author:** Lohit Datta  
**Email:** lohitbatchu@gmail.com

---

## Build a Virtual Private Cloud (VPC)

![Image](http://nextwork.ai/overjoyed_magenta_joyful_vampire/uploads/aws-networks-vpc_2facf927)

---

## Introducing Today's Project!

In this project, I will demonstrate that I can build a Virtual Private Cloud

### What is Amazon VPC?

### Personal reflection

---

## Virtual Private Clouds (VPCs)

### What I did in this step

In this step, I will create a vpc

### How VPCs work

VPCs are the reason why the resources are private to each other with them it would be like having all the files in one google drive

### Why there is a default VPC in AWS accounts

There was already a default VPC in my account ever since my AWS account was created. This is because we would not able to create our own resources such as an EC2 instance

![Image](http://nextwork.ai/overjoyed_magenta_joyful_vampire/uploads/aws-networks-vpc_2facf927)

### Defining IPv4 CIDR blocks

To set up my VPC, I had to define an IPv4 CIDR block, which contains a block of IP addresses that can be used by your VPC

---

## Subnets

### What I did in this step

In this step, I will create a subnet because it will allow me to group similar resources in my VPC together.

### Creating and configuring subnets

Subnets are like neighborhoods to your city which is a VPC and can be used to group similar resources together.There are already subnets existing in my account, one for every availability zone.

### Public vs private subnets

The difference between public and private subnets are public subnet is connected to the internet while private subnet is not connected to the internet.For a subnet to be considered public, it has to be connected to the internet

![Image](http://nextwork.ai/overjoyed_magenta_joyful_vampire/uploads/aws-networks-vpc_157c4219)

### Auto-assigning public IPv4 addresses

Once I created my subnet, I enabled auto assign public IPv4 addresses. This setting makes sure that when I launch instances in my public subnet it will get a public IP address directly. 

---

## Internet gateways

### What I did in this step

In this step, I will create an internet gateway because I want to connect my vpc to the internet

### Setting up internet gateways

Internet gateways are for connecting your VPC to the internet

Attaching an internet gateway to a VPC means that any resource in a public subnet is accessible from the internet.

![Image](http://nextwork.ai/overjoyed_magenta_joyful_vampire/uploads/aws-networks-vpc_4ae90410)

---
