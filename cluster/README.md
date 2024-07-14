# Create EKS Cluster

This repository creates the following resources in AWS Cloud:

- A VPC
- 2 public subnets, 2 private subnets in two AZs
- One internet gateway
- Elastic IPs for NAT gateways
- 2 NAT gateways in both public subnets
- Route tables
- One security group
- EKS cluster IAM role
- An EKS cluster
- Node Group and Node Group IAM role
