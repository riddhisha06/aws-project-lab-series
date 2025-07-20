# ☁️ AWS Cloud Training & Internship Project '25

Welcome to my **AWS Cloud Internship Repository**, featuring real-world projects built using **AWS Free-Tier** services. This collection highlights modular, hands-on implementations with detailed documentation, screenshots, and step-by-step configurations for each AWS service explored during the training.

---

## 🚀 What’s Inside?

Explore my journey through AWS, covering five core modules essential to modern cloud computing:

---

### 1. 🖥️ EC2: Elastic Compute Cloud
> **Launch, Host & Scale Virtual Servers**

Amazon EC2 (Elastic Compute Cloud) allows users to launch and manage virtual machines in the cloud. In this module, I worked with both Amazon Linux and Windows instances.

**Key Highlights:**
- Launched and configured Linux and Windows servers
- Installed and hosted websites using Apache and IIS
- Created and used custom AMIs for faster deployments
- Attached additional EBS Volumes for persistent storage
- Took and restored Snapshots for backup and disaster recovery
- Set up Auto Scaling Groups (ASG) and Load Balancers (ELB) to ensure high availability

🔗 [`Explore EC2 Project`](./Elastic%20Compute%20Cloud%20(EC2).pdf)

---

### 2. 🗃️ S3: Simple Storage Service
> **Store, Protect & Deliver Objects**

Amazon S3 (Simple Storage Service) provides scalable and secure object storage. This module focused on storing, accessing, and securing static and dynamic files.

**Key Highlights:**
- Created multiple **S3 Buckets** with specific configurations
- Managed access permissions (public, private, and IAM-based)
- Enabled **Versioning** to track file changes
- Generated **Presigned URLs** for temporary secure file sharing
- Changed **storage classes** (Standard, IA, Glacier) for cost optimization
- Explored **Static Website Hosting** directly from S3

🔗 [`Explore S3 Project`](./Simple%20Storage%20Service%20(S3).pdf)

---

### 3. 📢 SNS: Simple Notification Service
> **Send Real-Time Alerts**

Amazon SNS (Simple Notification Service) is a messaging service for application-to-person (A2P) communication. This module explored how to send alerts to users instantly.

**Key Highlights:**
- Created **SNS Topics** and **subscriptions** (email and SMS)
- Verified and confirmed subscriptions securely
- Published messages from console and CLI
- Understood the working of **pub-sub architecture**
- Practiced cleaning up unused topics and subscriptions to manage costs

🔗 [`Explore SNS Project`](./Simple%20Notification%20Service%20(SNS).pdf)

---

### 4. 📬 SQS: Simple Queue Service
> **Message Queue for Decoupled Systems**

Amazon SQS (Simple Queue Service) allows decoupling of application components using message queues. This module helped simulate asynchronous processing.

**Key Highlights:**
- Created **Standard Queues** to send and receive messages
- Connected **SNS Topics with SQS** for real-time delivery
- Simulated a **Pub/Sub system** using SNS + SQS
- Used SQS as a trigger for **AWS Lambda functions**
- Learned to manage, purge, and delete queues effectively

🔗 [`Explore SQS Project`](./Simple%20Queue%20Service%20(SQS).pdf)

---

### 5. 🛡️ IAM: Identity & Access Management
> **Secure Access Control in AWS**

AWS IAM (Identity and Access Management) allows you to control access to AWS resources securely. This module was essential for learning how to work in a secure AWS environment.

**Key Highlights:**
- Created **IAM Users**, **Groups**, and **Roles**
- Assigned both **AWS-managed** and **custom policies**
- Tested user permissions for services like EC2 and SNS
- Implemented **least privilege access** best practices
- Practiced **IAM cleanup** by removing inactive users and policies

🔗 [`Explore IAM Project`](./Identity%20and%20Access%20Management%20(IAM).pdf)

---
