# Scaling and Domain Name Resolution Labs

## Overview

This repository contains practical cloud computing labs focused on two core infrastructure concepts:

- **Scaling systems** to handle increasing or fluctuating workloads
- **Domain Name Resolution (DNS)** to map domain names to IP addresses and route traffic efficiently

These labs are designed to strengthen hands-on skills in cloud architecture, scalability, and networking fundamentals.

---

## Objectives

By completing these labs, you will be able to:

- Understand vertical vs horizontal scaling
- Configure and test auto scaling systems
- Implement and evaluate load balancing
- Understand DNS architecture and resolution flow
- Configure DNS records (A, CNAME, Alias)
- Troubleshoot common DNS and connectivity issues
- Understand how DNS integrates with cloud infrastructure


---

## Scaling Labs

### Lab 1: Horizontal Scaling
- Deploy multiple compute instances
- Distribute traffic across instances
- Observe system performance under load

### Lab 2: Auto Scaling Groups
- Configure auto scaling policies
- Define scaling triggers (CPU, traffic, etc.)
- Test scaling up and scaling down behavior

### Lab 3: Load Balancing
- Set up a load balancer
- Register multiple backend instances
- Verify even traffic distribution

---

## Domain Name Resolution Labs

### Lab 1: DNS Basics
- Understand how DNS works
- Map domain names to IP addresses
- Use tools like `nslookup` and `dig`

### Lab 2: DNS Configuration
- Create and manage DNS records
- Configure A, CNAME, and Alias records
- Connect domain names to cloud resources

### Lab 3: DNS Troubleshooting
- Diagnose DNS resolution issues
- Handle propagation delays
- Fix misconfigured records

---

## Key Concepts

- Cloud scalability (horizontal and vertical scaling)
- Elastic infrastructure design
- Load balancing strategies
- DNS hierarchy and resolution process
- High availability and fault tolerance
- Cloud networking fundamentals

---

## Tools & Technologies

- Cloud platforms (AWS / Azure / GCP)
- Virtual machines / EC2 instances
- Load balancers
- DNS management tools (e.g. Route 53 or equivalent)
- Command-line tools (`nslookup`, `dig`, `ping`)
- Web servers (Apache / Nginx)

---

## Expected Outcomes

After completing these labs, you will be able to:

- Design scalable cloud architectures
- Configure DNS for real-world applications
- Route traffic efficiently using load balancers
- Troubleshoot networking and DNS issues
- Apply foundational cloud engineering concepts in practice

---

## Notes

- Scaling may take time depending on cloud configuration
- DNS changes can take time due to propagation delays
- Always document configurations for debugging and review
- Use diagrams in the `visuals/` folder for better understanding

