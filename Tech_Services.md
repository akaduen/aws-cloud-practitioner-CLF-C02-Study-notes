# AWS Cloud Practitioner (CLF-C02) - Technology & Services

---

## Global Architecture
- **Regions:** Geographically distinct zones (e.g., us-east-1, sa-east-1), each containing multiple AZs.
- **Availability Zones (AZs):** Independent data centers within a region, connected with low-latency links for redundancy.
- **Edge Locations:** Points for content delivery acceleration, utilized by CloudFront for faster access.

## Primary Services
### Compute Options
- **EC2 (Elastic Compute Cloud):** Customizable virtual servers (choose OS, instance type) for flexible computing.
- **Lambda:** Event-driven, serverless code execution (e.g., triggered by file uploads to S3).
- **Elastic Beanstalk:** Automated app deployment platform that manages underlying infrastructure.

### Storage Solutions
- **S3 (Simple Storage Service):** Scalable object storage for files and backups.
  - Tiers: Standard (high-speed access), Glacier (low-cost archival), Intelligent-Tiering (cost-adaptive).
- **EBS (Elastic Block Store):** Persistent block storage for EC2 instances, available in SSD or HDD options.
- **EFS (Elastic File System):** Multi-instance file system enabling shared access across EC2 instances.

### Database Services
- **RDS (Relational Database Service):** Managed relational databases (e.g., MySQL, PostgreSQL).
- **DynamoDB:** High-performance NoSQL database with seamless scaling capabilities.
- **Redshift:** Analytical data warehouse optimized for large datasets and reporting.

### Networking Features
- **VPC (Virtual Private Cloud):** Isolated virtual network with customizable subnets and routing.
- **Route 53:** Scalable DNS and domain management service for reliable name resolution.
- **CloudFront:** Content delivery network caching data at edge locations for low-latency delivery.

### Monitoring Capabilities
- **CloudWatch:** Tracks performance metrics, logs, and sets alerts (e.g., monitors CPU load, memory usage).
- **Trusted Advisor:** Analyzes account for cost savings, security gaps, and performance optimization.

## Design Principles (Well-Architected Framework)
- **Five Core Pillars:**
  1. **Operational Excellence:** Emphasizes automation, monitoring, and operational efficiency.
  2. **Security:** Ensures robust protection of data and systems.
  3. **Reliability:** Builds resilience with redundancy (e.g., Multi-AZ deployments).
  4. **Performance Efficiency:** Matches resources to workload demands for optimal performance.
  5. **Cost Optimization:** Minimizes unnecessary spending through efficient resource use.

---
