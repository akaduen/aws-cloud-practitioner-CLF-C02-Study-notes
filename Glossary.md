# AWS Cloud Practitioner (CLF-C02) Glossary

 I used this glossary of terms for the AWS Certified Cloud Practitioner exam. Last updated: March 12, 2025.

---

## A
- **Access Keys:** Credentials (Access Key ID and Secret Access Key) used for programmatic access to AWS services via APIs or CLI.
- **Availability Zone (AZ):** An isolated data center within an AWS Region, designed for fault tolerance and high availability, connected with low-latency links.
- **AWS Artifact:** A service providing on-demand access to AWS compliance reports and agreements (e.g., GDPR, HIPAA, SOC reports).
- **AWS Budgets:** A tool to set custom cost and usage alerts for monitoring and managing AWS spending.
- **AWS CloudTrail:** A service that logs all API calls and account activities for auditing, security analysis, and troubleshooting.
- **AWS Inspector:** An automated tool that scans applications and infrastructure for security vulnerabilities and deviations from best practices.
- **AWS KMS (Key Management Service):** A service to create, manage, and rotate encryption keys for securing data across AWS services.
- **AWS Shield:** A managed service offering protection against Distributed Denial of Service (DDoS) attacks, with Standard (free) and Advanced (paid) tiers.

## B
- **Billing (Pay-as-you-go):** AWS pricing model where costs are based on actual resource usage, with no upfront fees or long-term commitments.
- **Block Storage:** Data storage in fixed-size blocks, used by services like EBS for persistent, high-performance storage with EC2.
- **Broad Network Access:** A core cloud trait allowing resources to be accessed from anywhere with an internet connection.

## C
- **CapEx (Capital Expenditure):** Traditional upfront costs for physical infrastructure (e.g., buying servers), replaced by OpEx in cloud models.
- **Cloud Computing:** The delivery of IT resources (compute, storage, databases) over the internet, on-demand, with pay-per-use pricing.
- **CloudFront:** AWS Content Delivery Network (CDN) that caches content at Edge Locations to reduce latency and improve delivery speed.
- **CloudWatch:** A monitoring service that collects metrics, logs, and sets alarms for AWS resources (e.g., CPU usage, memory).
- **Compliance:** Adherence to regulatory standards like GDPR, HIPAA, or PCI DSS, facilitated by AWS services and documentation.
- **Compute:** AWS services providing processing power, including EC2 (virtual machines), Lambda (serverless), and Elastic Beanstalk (PaaS).
- **Cost Explorer:** A tool for analyzing historical AWS spending, identifying cost trends, and forecasting future expenses.

## D
- **Data Transfer:** The movement of data into or out of AWS, with outbound transfers incurring costs and inbound typically free.
- **DDoS (Distributed Denial of Service):** A cyberattack that overwhelms a system with traffic, mitigated by AWS Shield.
- **DynamoDB:** A fully managed NoSQL database service offering high scalability, low-latency performance, and flexible data models.

## E
- **EBS (Elastic Block Store):** Block storage service providing persistent disks (SSD or HDD) for EC2 instances, ideal for databases and boot volumes.
- **EC2 (Elastic Compute Cloud):** A service offering resizable virtual machines with customizable operating systems and instance types.
- **Edge Location:** A site in AWS’s global network used by CloudFront to cache content closer to users for faster access.
- **EFS (Elastic File System):** A scalable file storage system for shared access across multiple EC2 instances, supporting NFS protocol.
- **Elastic Beanstalk:** A Platform as a Service (PaaS) that automates application deployment and infrastructure management.
- **Elasticity:** The ability of a cloud system to scale resources up or down dynamically based on workload demand.

## F
- **Five Pillars:** The core components of the Well-Architected Framework: Operational Excellence, Security, Reliability, Performance Efficiency, and Cost Optimization.
- **Free Tier:** A 12-month trial for new AWS users, offering limited free usage (e.g., 750 hours/month of EC2 t2.micro, 5GB S3 storage).

## G
- **GDPR (General Data Protection Regulation):** EU regulation for data privacy and protection, supported by AWS compliance tools and services.
- **Glacier:** A low-cost S3 storage class for archival data, with slower retrieval times (minutes to hours).
- **Global Infrastructure:** AWS’s worldwide network of Regions, Availability Zones, and Edge Locations for service delivery and resilience.

## H
- **HIPAA (Health Insurance Portability and Accountability Act):** US regulation for healthcare data security, supported by AWS compliance offerings.
- **Hybrid Cloud:** A deployment model combining public cloud (e.g., AWS) and private infrastructure (e.g., AWS Outposts).

## I
- **IAM (Identity & Access Management):** A service to manage users, groups, permissions, and secure access, supporting MFA and JSON policies.
- **IaaS (Infrastructure as a Service):** A cloud model providing full control over infrastructure resources (e.g., EC2 for virtual servers).
- **Intelligent-Tiering:** An S3 storage class that automatically moves data between access tiers (frequent/infrequent) to optimize costs.
- **Internet Gateway:** A VPC component that enables communication between resources in a VPC and the internet.

## L
- **Lambda:** A serverless compute service that runs code in response to events (e.g., S3 uploads) without managing servers.

## M
- **Measured Service:** A cloud trait where usage is tracked and billed based on actual consumption (pay-as-you-go).
- **MFA (Multi-Factor Authentication):** An additional security layer requiring a second verification step (e.g., code from a device) for logins.
- **Multi-AZ:** A deployment strategy using multiple Availability Zones to enhance fault tolerance and high availability.

## N
- **NoSQL:** A non-relational database type, like DynamoDB, optimized for scalability and unstructured data.

## O
- **Object Storage:** Data storage as objects (e.g., files), used by S3, ideal for unstructured data like backups and media.
- **On-Demand Instances:** An EC2 pricing model with hourly billing and no long-term commitment, offering maximum flexibility.
- **On-Demand Self-Service:** A cloud trait allowing users to provision resources independently without manual intervention.
- **OpEx (Operational Expenditure):** Ongoing operational costs for cloud usage, replacing CapEx in AWS’s pay-as-you-go model.

## P
- **PaaS (Platform as a Service):** A cloud model for application development without server management (e.g., Elastic Beanstalk).
- **PCI DSS (Payment Card Industry Data Security Standard):** A security standard for credit card data, supported by AWS compliance.
- **Pricing Calculator:** An AWS tool to estimate costs before deploying resources, based on service usage and configurations.

## R
- **RDS (Relational Database Service):** A managed SQL database service supporting engines like MySQL, PostgreSQL, and Oracle.
- **Redshift:** A fully managed data warehouse service for large-scale analytics and business intelligence reporting.
- **Region:** A geographic area hosting multiple Availability Zones (e.g., us-east-1, sa-east-1), isolated for resilience.
- **Reserved Instances:** An EC2 pricing model with 1- or 3-year commitments, offering discounts of 30-60% over On-Demand.
- **Resource Pooling:** A cloud trait where resources are shared across users, dynamically allocated by the provider.
- **Root User:** The initial AWS account user with unrestricted access, requiring strong security measures (e.g., MFA).
- **Route 53:** AWS’s scalable Domain Name System (DNS) and domain registration service.

## S
- **S3 (Simple Storage Service):** An object storage service for files and backups, with classes like Standard, Glacier, and Intelligent-Tiering.
- **SaaS (Software as a Service):** Fully managed software delivered over the internet (e.g., Microsoft 365, Salesforce).
- **Security Groups:** Virtual firewalls controlling inbound and outbound traffic to EC2 instances.
- **Serverless:** A computing model where AWS manages servers (e.g., Lambda), allowing focus on code development.
- **Shared Responsibility Model:** A framework dividing security duties: AWS secures the cloud (infra), users secure their use of it (data, configs).
- **Spot Instances:** An EC2 pricing model using spare capacity at a low cost, but instances may be interrupted with short notice.
- **Standard (S3):** The default S3 storage class optimized for frequently accessed data with low latency.
- **Subnet:** A segmented portion of a VPC’s IP range, used to organize and isolate resources within a network.
- **Support Plans:** AWS customer support tiers: Basic (free), Developer ($29/mo), Business ($100/mo), and Enterprise ($15k+/mo).

## T
- **Trusted Advisor:** A service providing recommendations to optimize AWS costs, security, performance, and fault tolerance.

## V
- **VPC (Virtual Private Cloud):** A private, customizable network within AWS, including subnets, gateways, and route tables.

## W
- **Well-Architected Framework:** AWS best practices with five pillars: Operational Excellence, Security, Reliability, Performance Efficiency, and Cost Optimization.

---
