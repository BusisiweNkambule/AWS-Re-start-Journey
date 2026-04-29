# Storage Labs

## Overview
This section contains hands-on labs focused on storage solutions in AWS, specifically Amazon Elastic Block Store (EBS). These labs demonstrate how to create, attach, and manage persistent block storage for cloud-based compute resources.

The goal is to understand how storage works in the cloud and how it supports applications requiring reliable and scalable data storage.

---

## Working with EBS (Elastic Block Store)

### Objective
To create and manage EBS volumes and understand how block storage integrates with EC2 instances.

---

### Key Concepts Covered
- Block storage in the cloud
- EBS volumes and their use cases
- Volume attachment and detachment
- File systems and mounting
- Data persistence
- Snapshots and backups

---

### Implementation Steps

#### 1. Creating an EBS Volume
- Navigated to the AWS Management Console
- Selected the EBS service
- Created a new volume with appropriate size and type
- Chose the same availability zone as the target EC2 instance

#### 2. Attaching the Volume
- Attached the EBS volume to an existing EC2 instance
- Verified attachment status in the console

#### 3. Connecting to the Instance
- Used SSH to connect to the EC2 instance
- Identified the attached volume using system commands

#### 4. Formatting and Mounting
- Formatted the volume with a file system (e.g., ext4)
- Mounted the volume to a directory
- Verified that the storage was accessible

#### 5. Managing Data
- Created and stored files on the mounted volume
- Confirmed data persistence

#### 6. Creating Snapshots
- Created snapshots of the volume for backup
- Understood how snapshots can be used for recovery

---

## Skills Gained
- Creating and managing EBS volumes
- Attaching storage to EC2 instances
- Formatting and mounting file systems
- Implementing backup strategies using snapshots
- Understanding persistent storage in cloud environments

---

## Challenges and Solutions

### Challenge
Identifying the correct device name for the attached volume on the instance.

### Solution
Used system commands to list available devices and verify the correct volume before formatting and mounting.

---

## Key Learnings
- EBS provides reliable and persistent storage for EC2 instances
- Volumes must be in the same availability zone as the instance
- Proper mounting is required before using storage
- Snapshots are essential for backup and recovery
- Storage management is critical for application performance and reliability

---

## Conclusion
These labs provided practical experience in working with block storage in AWS. Understanding how to create, attach, and manage EBS volumes is essential for building scalable and reliable cloud-based systems.

---

## Supporting Files
Refer to additional documentation and visuals within this folder for step-by-step configurations and screenshots.
