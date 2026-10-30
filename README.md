# AWS VPC Peering Project

**Author:** Pratik Sambhaji Gorule  
**AWS Region:** Mumbai (`ap-south-1`)  
**Project Type:** AWS Networking Hands-on Project

## Project Overview

This project demonstrates the configuration of VPC Peering between two Amazon Virtual Private Clouds (VPCs) in AWS.

The project covers VPC creation, subnet configuration, route tables, security groups, EC2 instances, and network connectivity testing.

## Architecture

- VPC-A: `10.10.0.0/16`
- VPC-B: `10.20.0.0/16`
- VPC Peering ID: `pcx-078e8e902dd4bfbea`

## Subnet Configuration

| VPC | Subnet | CIDR |
|---|---|---|
| VPC-A | Public | `10.10.1.0/24` |
| VPC-A | Private | `10.10.2.0/24` |
| VPC-B | Private | `10.20.1.0/24` |

## EC2 Instances

| Instance | Private IP |
|---|---|
| Bastion Host | `10.10.1.215` |
| App-A | `10.10.2.222` |
| App-B | `10.20.1.233` |

## AWS Services Used

- Amazon VPC
- Amazon EC2
- VPC Peering
- Route Tables
- Security Groups
- Internet Gateway
- AWS Systems Manager Session Manager

## Key Learnings

- VPC and subnet configuration
- CIDR addressing
- Route table configuration
- VPC Peering
- Security group rules
- ICMP and SSH troubleshooting
- AWS network connectivity

## Project Report

See `Pratik_Sambhaji_Gorule_EWB_VPC_Peering.pdf` for the project documentation.

## Author

Pratik Sambhaji Gorule
