# AWS Projects

This folder contains AWS projects demonstrating real-world cloud implementations.

# AWS Cloud Architecture Project

## Project Overview
This project demonstrates designing AWS infrastructure using multiple services.

---

## Project Goal
To design a secure and scalable AWS architecture solution.

---

## AWS Services Used
- Amazon EC2
- Amazon RDS
- Amazon S3
- IAM
- VPC

---

## Architecture Design

<img width="1536" height="1024" alt="diagram (1)" src="https://github.com/user-attachments/assets/710093c4-4af7-4062-affe-ea1ae7fd35ee" />
---

# ☕ AHKU Cafe – Amazon S3 Static Website Hosting Project

---

## Project Overview

This project demonstrates hosting a static business website for **AHKU Cafe** using **Amazon S3 Static Website Hosting**.

Amazon S3 was chosen because it provides a cost-effective, highly available, and scalable hosting solution that does not require server management. This makes it ideal for small businesses needing an online presence.

---

## Project Objective

To deploy and host a fully functional static website using Amazon S3 and configure it for public access.

---

## AWS Services Used

- Amazon S3
- AWS IAM
- AWS Management Console

---

## 📋 Prerequisites

Before starting this project, the following were required:

- Active AWS account
- Completed static website files (HTML/CSS)
- Main webpage named `index.html`

---

## Implementation Steps

### Step 1: Log in to AWS Console
1. Navigate to https://aws.amazon.com
2. Click **Sign in to the Console**
3. Enter AWS credentials

---

### Step 2: Access Amazon S3
1. Search for **S3** in AWS Console
2. Open the Amazon S3 dashboard

---

### Step 3: Create S3 Bucket
1. Click **Create Bucket**
2. Enter bucket name:
   ```
   ahku-cafe-website
   ```
3. Select region:
   ```
   Africa (Cape Town)
   ```
4. Leave Object Ownership as default

---

### Step 4: Configure Public Access
1. Uncheck:
   ```
   Block all public access
   ```
2. Confirm warning checkbox
3. Leave versioning disabled
4. Leave encryption enabled
5. Click **Create bucket**

---

### Step 5: Upload Website Files
1. Open the created bucket
2. Click **Upload**
3. Upload:
   - index.html
   - CSS files
   - Images
   - JavaScript files

---

### Step 6: Enable Static Website Hosting
1. Open **Properties** tab
2. Scroll to **Static Website Hosting**
3. Click **Edit**
4. Select:
   ```
   Enable
   ```
5. Choose:
   ```
   Host a static website
   ```
6. Enter:
   ```
   Index document: index.html
   ```
7. Save changes

---

### Step 7: Configure Bucket Policy

Navigate to **Permissions → Bucket Policy**

Paste policy:

```json
{
  "Version": "2012-10-17",
  "Statement": [
    {
      "Sid": "PublicReadGetObject",
      "Effect": "Allow",
      "Principal": "*",
      "Action": "s3:GetObject",
      "Resource": "arn:aws:s3:::ahku-cafe-website/*"
    }
  ]
}
```

Save changes.

---

### Step 8: Access Live Website
1. Go to **Properties**
2. Scroll to **Static Website Hosting**
3. Copy website endpoint URL
4. Open in browser

## Project Outcomes

- Successfully hosted static website using Amazon S3
- Configured public access policies
- Enabled static website hosting
- Deployed real business website solution

---

## Key Learning Outcomes

- Understanding object storage hosting
- Managing bucket policies and permissions
- Deploying static websites in AWS
- Learning cost-effective hosting solutions
- Understanding scalability and availability benefits

---

## Benefits of Using Amazon S3 Hosting

- Low cost
- High availability (99.99%)
- Automatic scalability
- No server maintenance
- Secure data encryption support

---

## Conclusion

Hosting the AHKU Cafe website using Amazon S3 provides a reliable and scalable cloud hosting solution. This project demonstrates how AWS cloud services can support small business digital presence without requiring server infrastructure management.

## Document
<img width="1240" height="1755" alt="AHKU Cafe – Amazon S3 Static Website Hosting Guide (1)_page-0001" src="https://github.com/user-attachments/assets/41aafdfc-8724-4ced-8d99-8d923f19d22e" />
<img width="1240" height="1755" alt="AHKU Cafe – Amazon S3 Static Website Hosting Guide (1)_page-0002" src="https://github.com/user-attachments/assets/921765f8-7e4d-4401-9acb-e7a3ef5984f7" />
<img width="1240" height="1755" alt="AHKU Cafe – Amazon S3 Static Website Hosting Guide (1)_page-0003" src="https://github.com/user-attachments/assets/7f48bda9-14ee-4bf5-94fb-c4a6faa56983" />
<img width="1240" height="1755" alt="AHKU Cafe – Amazon S3 Static Website Hosting Guide (1)_page-0004" src="https://github.com/user-attachments/assets/4aa95628-d646-467f-b197-cbece52c1a31" />
<img width="1240" height="1755" alt="AHKU Cafe – Amazon S3 Static Website Hosting Guide (1)_page-0005" src="https://github.com/user-attachments/assets/9022fa91-137c-41b5-9b9e-6c7b71197255" />
<img width="1240" height="1755" alt="AHKU Cafe – Amazon S3 Static Website Hosting Guide (1)_page-0006" src="https://github.com/user-attachments/assets/d20643ae-4059-4fdf-9707-18a8964b5218" />





