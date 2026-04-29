# Compute Labs

## Overview
This section contains hands-on labs focused on compute services in AWS, specifically Amazon EC2. These labs demonstrate how to provision, configure, and manage virtual servers in a cloud environment.

The goal of these labs is to build practical skills in deploying and maintaining compute resources while understanding how they integrate with other cloud services.

---

## EC2 Instance Setup

### Objective
To launch and configure an Amazon EC2 instance and understand the core components required to run a virtual server in the cloud.

---

### Key Concepts Covered
- Virtual machines in the cloud
- Amazon Machine Images (AMIs)
- Instance types and performance considerations
- Key pairs and secure access
- Security groups and firewall rules
- Basic instance lifecycle management

---

### Implementation Steps

#### 1. Launching an EC2 Instance
- Navigated to the AWS Management Console
- Selected the EC2 service
- Chose an appropriate Amazon Machine Image (AMI)
- Selected an instance type based on requirements

#### 2. Configuring Access
- Created or selected an existing key pair for secure login
- Configured security groups to allow inbound traffic (e.g., SSH on port 22)

#### 3. Instance Setup
- Reviewed and launched the instance
- Monitored instance status until it was running

#### 4. Connecting to the Instance
- Used SSH to connect to the instance
- Verified connectivity and system access

#### 5. Basic Management
- Started and stopped the instance
- Terminated the instance when no longer needed

---

## Skills Gained
- Provisioning virtual machines in AWS
- Configuring secure access using key pairs and security groups
- Understanding EC2 instance types and use cases
- Managing instance lifecycle operations

---

## Challenges and Solutions

### Challenge
Understanding how security groups control access to the instance.

### Solution
Reviewed inbound and outbound rules and tested connectivity to confirm correct configuration.

---

## Key Learnings
- EC2 provides scalable and flexible compute capacity
- Security configuration is critical when exposing instances to the internet
- Proper instance selection impacts performance and cost
- Cloud-based compute resources can be quickly deployed and managed

---

## Conclusion
These labs provided practical experience in working with Amazon EC2, reinforcing core cloud computing concepts. The ability to launch, configure, and manage instances is a fundamental skill for cloud engineering and forms the foundation for more advanced cloud architectures.

---

## Supporting Files
step-by-step guidance and screenshots.
