# Networking Labs

## Overview
This section contains hands-on labs focused on networking concepts within AWS. These labs explore how cloud resources communicate, how networks are structured, and how connectivity and access are controlled.

The goal is to develop a strong understanding of cloud networking fundamentals and how to design secure and scalable network architectures.

---

## Networking Concepts and Configuration

### Objective
To understand and implement core networking components in AWS, including Virtual Private Cloud (VPC), subnets, routing, and internet connectivity.

---

### Key Concepts Covered
- Virtual Private Cloud (VPC)
- Subnets (public and private)
- IP addressing and CIDR blocks
- Route tables and routing
- Internet Gateway and NAT
- Domain Name System (DNS)
- Network security basics

---

### Implementation Steps

#### 1. Creating a VPC
- Navigated to the AWS Management Console
- Created a Virtual Private Cloud (VPC)
- Defined a CIDR block for the network

#### 2. Configuring Subnets
- Created public and private subnets
- Assigned CIDR ranges to each subnet
- Ensured proper segmentation of resources

#### 3. Setting Up Internet Connectivity
- Created and attached an Internet Gateway to the VPC
- Enabled internet access for public subnet resources

#### 4. Configuring Route Tables
- Created route tables
- Added routes to direct traffic through the Internet Gateway
- Associated route tables with appropriate subnets

#### 5. Managing Network Access
- Configured security groups and network access controls
- Controlled inbound and outbound traffic rules

---

## Skills Gained
- Designing and configuring cloud networks
- Understanding how resources communicate within a VPC
- Implementing secure network access controls
- Managing routing and internet connectivity

---

## Challenges and Solutions

### Challenge
Understanding how routing and subnet associations affect connectivity.

### Solution
Tested different configurations and verified connectivity to ensure correct routing behavior.

---

## Key Learnings
- A well-designed network is critical for application performance and security
- Public and private subnet separation improves security
- Routing determines how traffic flows within and outside the network
- Security groups and network controls are essential for protecting resources

---

## Conclusion
These labs provided practical experience in building and managing cloud networking infrastructure. Understanding networking in AWS is essential for designing scalable, secure, and reliable systems.

---

## Supporting Files
Refer to additional documentation and visuals within this folder for detailed configurations and screenshots.
