# AWS Certified Cloud Practitioner (CLF-C02) — Full Mock Exam 3

**65 Questions | 90 Minutes | Pass Score: 70% (≥46 correct)**

> Zero overlap with Mock Exam 1 or Mock Exam 2. All questions are original.

---

## Instructions

- Read each question carefully before selecting your answer.
- Single-answer questions: select **ONE** option.
- Multi-answer questions: select the **exact number** of options specified.
- Answers and detailed explanations are in **Section 2** and **Section 3**.

---

# SECTION 1 — Questions

---

### Domain: Cloud Concepts

---

**Question 1** *(Choose ONE)*

A traditional retail company currently forecasts peak load annually and purchases servers 6 months in advance to be ready for holiday demand. In cloud computing, which concept eliminates this need for advance capacity planning?

- A. High availability
- B. Fault tolerance
- C. Elasticity
- D. Durability

---

**Question 2** *(Choose ONE)*

Which AWS infrastructure component serves as a physical location around the world where Amazon CloudFront delivers content to end users with the lowest possible latency?

- A. AWS Availability Zone
- B. AWS Region
- C. AWS Edge Location
- D. AWS Local Zone

---

**Question 3** *(Choose ONE)*

A company is concerned about downtime during a regional natural disaster affecting their primary data center. They want their application to continue serving users even if an entire AWS Region becomes unavailable. Which architectural strategy addresses this concern?

- A. Deploy across multiple Availability Zones within a single Region
- B. Enable Multi-AZ on their RDS database
- C. Deploy across multiple AWS Regions with active-active or active-passive configuration
- D. Use Amazon CloudFront to cache responses globally

---

**Question 4** *(Choose TWO)*

Which of the following are characteristics of cloud computing that differentiate it from traditional on-premises infrastructure?

- A. The customer is responsible for all physical hardware maintenance
- B. Resources can be provisioned and released on demand within minutes
- C. The cloud provider manages the physical infrastructure
- D. All cloud workloads require dedicated hardware per customer
- E. Capital expenditure is required before deploying any application

---

**Question 5** *(Choose ONE)*

A startup wants to launch their MVP (Minimum Viable Product) on AWS and needs to go from idea to production as quickly as possible. Which characteristic of cloud computing MOST directly supports this speed-to-market advantage?

- A. Massive economies of scale
- B. Agility — ability to experiment and deploy rapidly
- C. High durability of data
- D. Pay-per-use pricing model

---

**Question 6** *(Choose ONE)*

Which statement CORRECTLY differentiates high availability from fault tolerance in AWS architectures?

- A. High availability and fault tolerance are interchangeable terms
- B. High availability minimizes downtime during failures; fault tolerance ensures continuous operation with zero downtime
- C. Fault tolerance is achieved only with Reserved Instances
- D. High availability requires deploying in multiple AWS Regions

---

---

### Domain: Security & Compliance

---

**Question 7** *(Choose ONE)*

A company wants to allow a third-party auditor to review their AWS resources and configurations without being able to make any changes. Which AWS feature should they use?

- A. Create an IAM user with AdministratorAccess and share it temporarily
- B. Create an IAM role with read-only permissions and allow the auditor to assume it
- C. Share the root account credentials with view-only instructions
- D. Enable AWS Config and share the console URL with the auditor

---

**Question 8** *(Choose TWO)*

A company runs a multi-account AWS environment. They want to ensure that no account in their organization can disable AWS CloudTrail logging, even the account's own administrators. Which approach achieves this?

- A. Enable CloudTrail in all accounts individually and trust admins to keep it on
- B. Apply a Service Control Policy (SCP) via AWS Organizations that denies the cloudtrail:DeleteTrail and cloudtrail:StopLogging actions
- C. Use AWS Config to detect if CloudTrail is disabled and auto-remediate
- D. Enable AWS CloudTrail at the organization level, which creates a trail in all accounts that cannot be modified by member accounts
- E. Use IAM permission boundaries on all IAM users to prevent CloudTrail changes

---

**Question 9** *(Choose ONE)*

A company stores customer personally identifiable information (PII) in Amazon DynamoDB. They want to ensure the data is encrypted at rest using keys they fully control. Which solution provides the HIGHEST level of customer key control?

- A. DynamoDB default encryption using AWS-owned keys
- B. DynamoDB encryption using AWS-managed keys (aws/dynamodb)
- C. DynamoDB encryption using customer-managed keys (CMK) in AWS KMS
- D. DynamoDB encryption using SSL/TLS in transit

---

**Question 10** *(Choose ONE)*

A company's security policy states that all EC2 instances must be patched within 72 hours of a critical vulnerability disclosure. Which AWS service helps automate the discovery and remediation of missing patches across a fleet of EC2 instances?

- A. Amazon Inspector
- B. AWS Systems Manager Patch Manager
- C. AWS Security Hub
- D. Amazon GuardDuty

---

**Question 11** *(Choose ONE)*

Under the AWS Shared Responsibility Model, which of the following is SOLELY AWS's responsibility?

- A. Configuring IAM roles and policies
- B. Encrypting application data before storing it in S3
- C. Physically destroying decommissioned hard drives in AWS data centers
- D. Enabling MFA on IAM user accounts

---

**Question 12** *(Choose TWO)*

A company needs to comply with a regulation that requires them to maintain an immutable audit log of all administrative actions taken in their AWS account. Which combination of services satisfies this requirement?

- A. Amazon CloudWatch Logs
- B. AWS CloudTrail with log file validation enabled
- C. Amazon S3 with Object Lock (WORM) to store CloudTrail logs
- D. AWS Config with daily snapshots
- E. Amazon GuardDuty threat detection logs

---

**Question 13** *(Choose ONE)*

A developer notices that their application's S3 bucket was accidentally configured to allow public read access. Which S3 feature would have PREVENTED this misconfiguration from ever being applied?

- A. S3 Versioning
- B. S3 Block Public Access at the account level
- C. S3 Object Lock
- D. AWS CloudTrail S3 data event logging

---

**Question 14** *(Choose ONE)*

A company uses Amazon Cognito to manage authentication for their customer-facing mobile application. A user wants to sign in using their existing Google account. Which Cognito feature enables this?

- A. Cognito User Pool — custom authentication flow
- B. Cognito Identity Pool — IAM role-based access
- C. Cognito User Pool — social identity provider (federated sign-in)
- D. AWS IAM Identity Center — enterprise SSO

---

**Question 15** *(Choose ONE)*

An organization wants to ensure their AWS environment follows security best practices and receives automated findings about risky configurations, such as unrestricted SSH access on security groups, across all their accounts in one centralized dashboard. Which AWS service provides this?

- A. AWS Trusted Advisor (Business/Enterprise) — Security checks
- B. Amazon Inspector — network assessments
- C. AWS Security Hub — aggregated security findings
- D. Amazon Macie — data security posture

---

**Question 16** *(Choose ONE)*

A company's cloud security team requires that all new IAM users must create a strong password on first login and cannot reuse the last 10 passwords. Which AWS feature enforces this?

- A. IAM access keys rotation policy
- B. IAM account password policy
- C. AWS Secrets Manager password rotation
- D. AWS Cognito password policy

---

**Question 17** *(Choose TWO)*

A company is reviewing the AWS Shared Responsibility Model for Amazon EC2. Which items are the CUSTOMER'S responsibility?

- A. Hypervisor patching and maintenance
- B. Physical server hardware replacement
- C. Installing and configuring applications on the EC2 instance
- D. Network access control at the AWS data center level
- E. Patching the operating system running on the EC2 instance

---

**Question 18** *(Choose ONE)*

An enterprise CISO wants a comprehensive view of their AWS security posture, including compliance with standards like CIS, PCI DSS, and SOC 2, across all AWS accounts. Which AWS service provides this multi-standard compliance dashboard?

- A. AWS Trusted Advisor
- B. AWS Audit Manager
- C. AWS Security Hub with security standards enabled
- D. Amazon Detective

---

---

### Domain: Networking

---

**Question 19** *(Choose ONE)*

A company launches EC2 instances in a public subnet. Which TWO components must be in place for these instances to receive inbound traffic from the internet?

- A. A NAT Gateway and an Internet Gateway
- B. An Internet Gateway attached to the VPC and a route in the route table pointing to the Internet Gateway
- C. A VPN Gateway and a Direct Connect connection
- D. A Transit Gateway and VPC Peering

---

**Question 20** *(Choose ONE)*

A company has 200 VPCs across multiple AWS accounts and regions. Managing VPC-to-VPC routing has become extremely complex. Which AWS service simplifies this by acting as a central hub for all VPC connectivity?

- A. VPC Peering
- B. AWS PrivateLink
- C. AWS Transit Gateway
- D. AWS Direct Connect Gateway

---

**Question 21** *(Choose ONE)*

An application needs to resolve DNS names of resources within a private Amazon VPC. The company wants to use custom domain names such as "database.internal.company.com" that are only resolvable within the VPC. Which Route 53 feature enables this?

- A. Route 53 public hosted zones
- B. Route 53 private hosted zones
- C. Route 53 Resolver outbound endpoints
- D. Route 53 ALIAS records in a public zone

---

**Question 22** *(Choose TWO)*

A company needs to improve their application's performance for users in Asia-Pacific. Their application is hosted in us-east-1. Which AWS services would help deliver content and reduce latency for Asia-Pacific users WITHOUT requiring the application to be re-deployed in a different Region?

- A. Amazon CloudFront — cache static and dynamic content at Asia-Pacific edge locations
- B. AWS Global Accelerator — route traffic through the AWS global network to the nearest edge
- C. Amazon Route 53 latency-based routing to a new ap-southeast-1 deployment
- D. Amazon ElastiCache in the us-east-1 region
- E. AWS Direct Connect from Asia-Pacific to us-east-1

---

**Question 23** *(Choose ONE)*

A company's application requires dedicated, consistent network bandwidth between their on-premises data center and AWS, with latency requirements that the public internet cannot reliably meet. Which AWS service meets this requirement?

- A. AWS Site-to-Site VPN
- B. AWS Direct Connect
- C. AWS PrivateLink
- D. Amazon VPC Peering

---

**Question 24** *(Choose ONE)*

A company wants to block traffic from specific malicious IP addresses from ever reaching their Application Load Balancer, while also protecting against SQL injection attempts in HTTP requests. Which AWS service combination provides BOTH capabilities?

- A. Security Groups + NACLs
- B. AWS WAF with IP set rules and SQL injection rules attached to the ALB
- C. AWS Shield Advanced + Amazon Inspector
- D. Amazon GuardDuty + AWS Config

---

**Question 25** *(Choose ONE)*

A company uses Amazon Route 53 and wants to ensure that traffic is automatically redirected to a backup website hosted in a different Region if the primary website fails its health check. Which Route 53 routing policy should they configure?

- A. Weighted routing
- B. Geolocation routing
- C. Failover routing
- D. Multivalue answer routing

---

**Question 26** *(Choose ONE)*

A solutions architect is designing a VPC with both public and private subnets. Which statement about the difference between a public subnet and a private subnet is CORRECT?

- A. Public subnets use IPv6 addressing; private subnets use IPv4 only
- B. A subnet is public when its route table has a route to an Internet Gateway; a subnet is private when it does not
- C. Public subnets are only for web servers; private subnets are only for databases
- D. Private subnets are completely isolated and can never initiate any outbound traffic

---

**Question 27** *(Choose ONE)*

A company wants to enable their Lambda functions to securely access resources inside a private VPC, such as an RDS database, without exposing those resources to the internet. Which configuration achieves this?

- A. Assign a public IP to the RDS database
- B. Configure the Lambda function to run inside the VPC with appropriate security group rules
- C. Use an Internet Gateway to allow Lambda to reach the VPC
- D. Use AWS Direct Connect to connect Lambda to the VPC

---

**Question 28** *(Choose ONE)*

An AWS Solutions Architect wants to route end-user requests to the nearest AWS Region using latency measurements rather than the user's geographic location. Which Route 53 routing policy does this?

- A. Geoproximity routing
- B. Geolocation routing
- C. Latency-based routing
- D. Weighted routing

---

---

### Domain: Compute

---

**Question 29** *(Choose ONE)*

A company needs to run batch data processing jobs that are fault-tolerant and can be paused and resumed. The jobs typically run for 2–4 hours and can tolerate interruptions. Which EC2 purchasing option provides the LOWEST cost for this scenario?

- A. On-Demand Instances
- B. Reserved Instances — 1 year, partial upfront
- C. Spot Instances
- D. Dedicated Hosts

---

**Question 30** *(Choose ONE)*

A company's application needs to process financial transactions requiring very fast, low-latency disk I/O. The data must persist even if the EC2 instance is stopped. Which storage type should they use?

- A. EC2 instance store
- B. Amazon EBS (Elastic Block Store)
- C. Amazon EFS (Elastic File System)
- D. Amazon S3

---

**Question 31** *(Choose ONE)*

A company wants to deploy a web application without managing or provisioning any infrastructure. The application handles HTTP requests and the team wants to focus entirely on writing code. Which combination of AWS services is MOST suitable?

- A. EC2 Auto Scaling + Application Load Balancer
- B. AWS Lambda + Amazon API Gateway
- C. Amazon ECS on EC2 + Network Load Balancer
- D. Amazon Lightsail + Route 53

---

**Question 32** *(Choose TWO)*

A company is running an application on Amazon EC2. After monitoring, they notice the instances consistently use only 10% of CPU but consume 80% of available memory. What should they do to optimize costs according to AWS best practices?

- A. Switch to Spot Instances to reduce cost immediately
- B. Right-size to a Memory Optimized instance type that better matches the workload profile
- C. Continue with the current instance type since it is working correctly
- D. Use AWS Compute Optimizer recommendations to identify the appropriate instance type
- E. Add more EBS volumes to the instance

---

**Question 33** *(Choose ONE)*

A large enterprise runs thousands of EC2 instances and wants to standardize how they deploy and configure software across their fleet using automated runbooks and remote command execution. Which AWS service provides this operational capability?

- A. AWS CloudFormation
- B. AWS Elastic Beanstalk
- C. AWS Systems Manager (SSM)
- D. Amazon EC2 Auto Scaling

---

**Question 34** *(Choose ONE)*

A company's application runs on EC2 instances in an Auto Scaling group behind an Application Load Balancer. During a sudden traffic spike, some users experience slow response times. What should be reviewed to improve the application's automatic scaling response?

- A. The IAM role attached to the EC2 instances
- B. The Auto Scaling group's scaling policies and CloudWatch alarms
- C. The VPC's Internet Gateway bandwidth
- D. The RDS database's Multi-AZ configuration

---

**Question 35** *(Choose ONE)*

A company needs to process video files that require specialized GPU hardware. The processing is seasonal, occurring only in December. Which combination of options is MOST cost-effective for this scenario?

- A. On-Demand GPU instances (P or G family) during December only
- B. Reserved GPU instances for 3 years
- C. Standard EC2 instances (C-family) with extra CPU
- D. Dedicated Hosts with GPU capability year-round

---

---

### Domain: Storage

---

**Question 36** *(Choose ONE)*

A company has a data analytics workload that generates 100 GB of log files daily. The logs are analyzed frequently for the first 7 days, rarely accessed for the next 23 days, and then must be archived for 5 years at the lowest possible cost. Which S3 configuration BEST meets this requirement?

- A. Store all logs in S3 Standard indefinitely
- B. Configure an S3 Lifecycle policy to transition logs to S3 Standard-IA after 7 days, then to S3 Glacier Deep Archive after 30 days
- C. Use S3 Intelligent-Tiering for all logs to automatically manage transitions
- D. Store logs in S3 Glacier immediately and restore when needed

---

**Question 37** *(Choose ONE)*

An application uses Amazon S3 to store user-uploaded images. The team wants to ensure that even if they accidentally delete a large batch of images, they can recover the previous versions. They also want the bucket to meet a regulatory requirement that objects cannot be permanently deleted without MFA verification by an authorized user. Which combination of S3 features should they enable?

- A. S3 Replication + S3 Object Lock
- B. S3 Versioning + S3 MFA Delete
- C. S3 Lifecycle policies + S3 Block Public Access
- D. S3 Versioning + S3 Cross-Region Replication

---

**Question 38** *(Choose ONE)*

A company runs a High-Performance Computing (HPC) cluster that requires shared file storage with extremely high throughput and low latency. Multiple EC2 instances need simultaneous read/write access. Which AWS storage service is BEST suited?

- A. Amazon EBS with Multi-Attach
- B. Amazon EFS with Provisioned Throughput
- C. Amazon FSx for Lustre
- D. Amazon S3 with Transfer Acceleration

---

**Question 39** *(Choose TWO)*

A company wants to understand the differences between Amazon S3, Amazon EBS, and Amazon EFS. Which statements are CORRECT?

- A. Amazon EBS can be simultaneously attached to hundreds of EC2 instances by default
- B. Amazon S3 is object storage accessed via HTTP APIs; EBS is block storage mounted to a single EC2 instance; EFS is file storage mountable by multiple EC2 instances simultaneously
- C. Amazon EFS stores data as key-value pairs
- D. Amazon EBS is best suited for static websites and object storage
- E. Amazon S3 provides 11 nines (99.999999999%) of data durability

---

**Question 40** *(Choose ONE)*

A manufacturing company stores machine sensor data on local servers in their factory. They want to run local analytics on this data at the edge and automatically sync results to AWS S3, even with intermittent internet connectivity. Which AWS service is MOST appropriate?

- A. AWS Storage Gateway — Volume Gateway
- B. AWS Snowball Edge — Compute Optimized
- C. Amazon S3 Transfer Acceleration
- D. AWS DataSync with a scheduled sync

---

---

### Domain: Database

---

**Question 41** *(Choose ONE)*

A company runs Amazon Aurora MySQL and wants to reduce the read load on their primary instance. They have multiple reporting applications that perform complex queries. Which feature of Aurora should they use?

- A. Aurora Multi-AZ standby instance
- B. Aurora Read Replicas
- C. Aurora Global Database
- D. Aurora Serverless v2

---

**Question 42** *(Choose ONE)*

A company needs a fully managed relational database with automatic backups, automatic minor version upgrades, and up to 15 Read Replicas, with up to 5x the performance of standard MySQL. Which AWS database service meets these requirements?

- A. Amazon RDS for MySQL
- B. Amazon Aurora
- C. Amazon DynamoDB
- D. Amazon Redshift

---

**Question 43** *(Choose ONE)*

A company is designing an e-commerce platform that must handle variable traffic and requires a database that scales read and write capacity automatically without downtime. Which AWS database service is MOST appropriate?

- A. Amazon RDS with Multi-AZ
- B. Amazon Aurora Serverless
- C. Amazon Redshift
- D. Amazon ElastiCache for Redis

---

**Question 44** *(Choose ONE)*

A retail company wants to migrate their Microsoft SQL Server database to AWS with MINIMAL changes to the application. Which AWS service is BEST suited?

- A. Amazon DynamoDB
- B. Amazon Redshift
- C. Amazon RDS for SQL Server
- D. Amazon Aurora PostgreSQL

---

---

### Domain: Monitoring & Management

---

**Question 45** *(Choose ONE)*

A company wants to be notified when their EC2 instance's CPU utilization stays above 90% for more than 10 minutes, and then automatically restart the instance. Which AWS services should they use?

- A. AWS CloudTrail + AWS Lambda
- B. Amazon CloudWatch Alarm + Amazon SNS + AWS Lambda
- C. AWS Config + AWS Systems Manager
- D. Amazon GuardDuty + AWS Lambda

---

**Question 46** *(Choose ONE)*

An operations team needs to review every AWS API call made to their account over the past 30 days to investigate a suspected security incident. Which AWS service provides this historical API activity log?

- A. Amazon CloudWatch Logs
- B. AWS CloudTrail event history
- C. AWS Config configuration history
- D. Amazon VPC Flow Logs

---

**Question 47** *(Choose ONE)*

A company wants to ensure their AWS architecture stays within defined configuration guardrails — for example, ensuring all S3 buckets have server-side encryption enabled. They want automatic remediation when drift is detected. Which AWS service provides this capability?

- A. AWS CloudTrail with SNS alerts
- B. Amazon CloudWatch with metric filters
- C. AWS Config rules with automatic remediation actions
- D. Amazon Inspector with assessment templates

---

**Question 48** *(Choose TWO)*

A company is new to AWS and wants to understand the current health and operational status of their AWS account. They are looking for a service that provides a prioritized list of recommendations across cost, security, performance, and fault tolerance. Which AWS service or tool provides this, and what is required to access all checks?

- A. AWS Personal Health Dashboard — available to all accounts for free
- B. AWS Trusted Advisor — full checks require a Business or Enterprise support plan
- C. AWS Cost Explorer — available to all accounts for free
- D. AWS Trusted Advisor — 7 core checks are free; full access requires Business or Enterprise plan
- E. Amazon CloudWatch — all metric alarms are free

---

---

### Domain: Pricing & Billing

---

**Question 49** *(Choose ONE)*

A company has workloads that run continuously 24/7 for the next 2 years with predictable usage. They want to commit to AWS compute usage across any instance family, size, and Region to maximize savings. Which pricing option is MOST appropriate?

- A. On-Demand Instances
- B. Spot Instances
- C. Compute Savings Plans — 2-year commitment
- D. Standard Reserved Instances — 1-year, no upfront

---

**Question 50** *(Choose ONE)*

A company wants to set up an alert that triggers when their total AWS bill for the current month is FORECASTED to exceed $10,000, giving them time to take action before the bill arrives. Which AWS service provides forecasted budget alerts?

- A. AWS Cost Explorer with monthly report
- B. AWS Budgets with a forecasted cost budget alert
- C. Amazon CloudWatch billing alarm
- D. AWS Pricing Calculator

---

**Question 51** *(Choose TWO)*

A company has 10 AWS accounts for different teams. They consolidate billing through AWS Organizations. Which cost benefits does consolidated billing provide?

- A. Each account receives Reserved Instance pricing regardless of which account purchased it
- B. Aggregate usage across all accounts can qualify for volume pricing discounts (e.g., S3 tiered pricing)
- C. Reserved Instance and Savings Plans benefits can be shared across all accounts in the organization
- D. Each account receives a dedicated TAM included in consolidated billing
- E. All accounts share a single free tier allowance regardless of how many accounts exist

---

**Question 52** *(Choose ONE)*

A company is building a new application and wants to estimate the monthly AWS cost BEFORE deploying any resources. They have specific services in mind and want to model different configurations. Which AWS tool is designed for this?

- A. AWS Cost Explorer
- B. AWS Migration Evaluator
- C. AWS Pricing Calculator
- D. AWS Budgets

---

**Question 53** *(Choose ONE)*

A startup has been running on AWS for 6 months using On-Demand Instances for their production environment. Usage has stabilized and they run 10 EC2 instances continuously 24/7. Their cloud architect recommends switching the purchasing model. Which option would MOST reduce their monthly EC2 costs without interrupting production?

- A. Switch all instances to Spot Instances
- B. Purchase Standard Reserved Instances for 1 year, all upfront
- C. Add more instances to distribute load
- D. Enable Auto Scaling to reduce instance count during off-peak hours

---

**Question 54** *(Choose ONE)*

A company receives AWS invoices for five separate accounts but wants to reduce billing complexity and take advantage of pooled usage discounts. Which is the FIRST step they should take?

- A. Contact AWS Support to merge all accounts into one
- B. Create an AWS Organization and invite all accounts to join for consolidated billing
- C. Purchase Reserved Instances in each account separately
- D. Use AWS Cost Explorer to combine billing reports manually

---

---

### Domain: Well-Architected Framework

---

**Question 55** *(Choose ONE)*

A company wants to reduce the risk of a misconfigured deployment causing a production outage. According to the AWS Well-Architected Framework, which design principle MOST directly addresses this risk?

- A. Implement a strong identity foundation
- B. Make frequent, small, reversible changes using deployment pipelines
- C. Automate to make architectural experimentation easier
- D. Use managed services to reduce operational burden

---

**Question 56** *(Choose ONE)*

A financial services company wants to ensure their AWS workloads are auditable, traceable, and that all security events are logged and responded to automatically. Which Well-Architected pillar and design principle is MOST relevant?

- A. Operational Excellence — Perform operations as code
- B. Security — Enable traceability
- C. Reliability — Automatically recover from failure
- D. Cost Optimization — Implement cloud financial management

---

**Question 57** *(Choose TWO)*

A company's CTO wants to validate their AWS architecture against AWS best practices before launching a new product. Which AWS tools help evaluate architectures against the Well-Architected Framework? 

- A. AWS Well-Architected Tool
- B. AWS Trusted Advisor
- C. AWS Cost Explorer
- D. AWS CloudFormation Drift Detection
- E. Amazon Inspector

---

**Question 58** *(Choose ONE)*

A company's architecture team is reviewing their disaster recovery strategy. They currently back up data to Amazon S3 daily and restore from backup when failures occur. This results in 8-12 hours of downtime per incident. Which Well-Architected Reliability principle does this architecture fail to address?

- A. Scale horizontally to increase workload availability
- B. Automatically recover from failure
- C. Stop guessing capacity
- D. Test recovery procedures

---

**Question 59** *(Choose ONE)*

A company uses only two large EC2 instances for their web tier, which causes 100% CPU usage during peak hours. A solutions architect recommends distributing the load across multiple smaller instances. According to the Performance Efficiency pillar, which design principle does this recommendation follow?

- A. Democratize advanced technologies
- B. Mechanical sympathy — understand the hardware you are using
- C. Use multiple small resources instead of one large resource
- D. Go global in minutes

---

**Question 60** *(Choose TWO)*

A company wants to apply the Operational Excellence pillar's design principles to their daily operations. Which of the following practices align with this pillar?

- A. Use infrastructure as code (AWS CloudFormation or CDK) to provision resources consistently
- B. Deploy all workloads into a single Availability Zone to reduce complexity
- C. Annotate documentation and runbooks with lessons learned after each incident
- D. Use Reserved Instances for all compute to reduce costs
- E. Store all backups in Amazon Glacier regardless of recovery time requirements

---

**Question 61** *(Choose ONE)*

A company uses a microservices architecture on AWS. They want to understand the flow of requests across multiple services and identify which service is causing latency. Which AWS service is designed for distributed tracing and performance profiling?

- A. AWS CloudTrail
- B. Amazon CloudWatch
- C. AWS X-Ray
- D. Amazon Detective

---

---

### Domain: AI/ML Services

---

**Question 62** *(Choose ONE)*

A media company wants to automatically generate captions and subtitles for their video library by converting spoken audio into text. Which AWS AI service should they use?

- A. Amazon Polly
- B. Amazon Transcribe
- C. Amazon Comprehend
- D. Amazon Lex

---

**Question 63** *(Choose ONE)*

A global e-commerce company sells products in 25 countries and wants to automatically translate product descriptions from English into 24 other languages in real time. Which AWS service enables this?

- A. Amazon Comprehend
- B. Amazon Rekognition
- C. Amazon Translate
- D. Amazon Textract

---

**Question 64** *(Choose ONE)*

A retail company wants to build an intelligent virtual assistant (chatbot) that can understand customer questions in natural language and carry on multi-turn conversations, integrated with their website. Which AWS AI service is MOST appropriate?

- A. Amazon Polly
- B. Amazon Transcribe
- C. Amazon Lex
- D. Amazon Rekognition

---

**Question 65** *(Choose TWO)*

A company wants to use AWS AI services to analyze their social media mentions. They need to determine the overall sentiment (positive, negative, neutral) of customer posts and extract key topics and entity names (such as product names and people). Which AWS service or services should they use?

- A. Amazon Rekognition — for image analysis of social media posts
- B. Amazon Comprehend — for sentiment analysis and entity detection
- C. Amazon Textract — for extracting structured text from documents
- D. Amazon Comprehend — for key phrase and topic extraction from text
- E. Amazon Polly — for converting the posts to speech for review

---

---

# SECTION 2 — Answer Key

| Q# | Answer | Domain |
|----|--------|--------|
| 1 | C | Cloud Concepts |
| 2 | C | Cloud Concepts |
| 3 | C | Cloud Concepts |
| 4 | B, C | Cloud Concepts |
| 5 | B | Cloud Concepts |
| 6 | B | Cloud Concepts |
| 7 | B | Security |
| 8 | B, D | Security |
| 9 | C | Security |
| 10 | B | Security |
| 11 | C | Security |
| 12 | B, C | Security |
| 13 | B | Security |
| 14 | C | Security |
| 15 | C | Security |
| 16 | B | Security |
| 17 | C, E | Security |
| 18 | C | Security |
| 19 | B | Networking |
| 20 | C | Networking |
| 21 | B | Networking |
| 22 | A, B | Networking |
| 23 | B | Networking |
| 24 | B | Networking |
| 25 | C | Networking |
| 26 | B | Networking |
| 27 | B | Networking |
| 28 | C | Networking |
| 29 | C | Compute |
| 30 | B | Compute |
| 31 | B | Compute |
| 32 | B, D | Compute |
| 33 | C | Compute |
| 34 | B | Compute |
| 35 | A | Compute |
| 36 | B | Storage |
| 37 | B | Storage |
| 38 | C | Storage |
| 39 | B, E | Storage |
| 40 | B | Storage |
| 41 | B | Database |
| 42 | B | Database |
| 43 | B | Database |
| 44 | C | Database |
| 45 | B | Monitoring |
| 46 | B | Monitoring |
| 47 | C | Monitoring |
| 48 | B, D | Monitoring |
| 49 | C | Pricing |
| 50 | B | Pricing |
| 51 | B, C | Pricing |
| 52 | C | Pricing |
| 53 | B | Pricing |
| 54 | B | Pricing |
| 55 | B | Well-Architected |
| 56 | B | Well-Architected |
| 57 | A, B | Well-Architected |
| 58 | B | Well-Architected |
| 59 | C | Well-Architected |
| 60 | A, C | Well-Architected |
| 61 | C | Well-Architected |
| 62 | B | AI/ML |
| 63 | C | AI/ML |
| 64 | C | AI/ML |
| 65 | B, D | AI/ML |

---

# SECTION 3 — Detailed Explanations

---

**Q1 — Correct: C (Elasticity)**

Elasticity is the cloud's ability to automatically provision and release resources in response to real-time demand — eliminating the need to predict and pre-purchase capacity for peak load. Retailers no longer need to buy 6 months in advance; they scale up during holidays and scale back down afterward, paying only for what they use. High availability = systems stay up during failures. Fault tolerance = systems continue operating during component failures. Durability = data is not lost.

> **Exam Trap:** Scalability means you CAN grow, but elasticity means you can grow AND shrink automatically — and you don't have to predict future needs.

---

**Q2 — Correct: C (AWS Edge Location)**

Edge Locations are infrastructure points of presence (PoPs) distributed globally where Amazon CloudFront caches content close to end users. They are distinct from Regions (geographic clusters of AZs) and AZs (data centers within a Region). Local Zones extend AWS Regions to specific metropolitan areas for ultra-low latency but are not the same as Edge Locations.

> **Exam Trap:** Edge Locations ≠ Regions ≠ AZs. Know each definition. Edge Locations are for CloudFront CDN caching and Route 53 DNS resolution — not for running EC2 or RDS.

---

**Q3 — Correct: C (Deploy across multiple AWS Regions)**

Deploying across multiple AWS Regions with active-active or active-passive configuration protects against full Regional failures, including natural disasters. Multi-AZ deployment protects against AZ failures within a single Region — a disaster could affect the entire Region. CloudFront caches content but doesn't make the application available if the origin Region is down.

> **Exam Trap:** Multi-AZ ≠ Multi-Region. Multi-AZ = same Region, different data center. Multi-Region = geographically separate. For regional disaster resilience, you need Multi-Region.

---

**Q4 — Correct: B, C (On-demand provisioning; Cloud provider manages physical infrastructure)**

Key cloud characteristics: resources can be provisioned and released on demand within minutes (vs. weeks for physical hardware), and the cloud provider manages all physical infrastructure. Cloud customers are NOT responsible for hardware maintenance. Cloud supports multi-tenancy — dedicated hardware per customer is not a cloud characteristic. CapEx is what cloud ELIMINATES — you use OpEx (pay-as-you-go) instead.

> **Exam Trap:** The shift from CapEx to OpEx is a cloud benefit. Option E describes the opposite of cloud computing.

---

**Q5 — Correct: B (Agility — ability to experiment and deploy rapidly)**

Agility is the cloud benefit that allows businesses to go from idea to production rapidly — no hardware procurement, no long procurement cycles, instant resource provisioning. This directly supports MVP launches and fast iteration. Economies of scale = lower prices. Durability = data protection. Pay-per-use = cost model, not speed.

> **Exam Trap:** Pay-per-use pricing enables experimentation without financial risk, but it's not the same as agility. Agility = speed of deployment and experimentation.

---

**Q6 — Correct: B (High availability minimizes downtime; fault tolerance = zero downtime)**

High availability (HA) means a system is designed to minimize downtime — it may experience brief interruptions during failover but recovers quickly. Fault tolerance means the system continues operating with NO interruption even when components fail (more expensive, uses redundancy). HA ≠ Fault Tolerance. HA doesn't require multiple Regions specifically.

> **Exam Trap:** Both HA and fault tolerance deal with failures, but fault tolerance has zero downtime (more complex and costly). HA accepts minimal disruption.

---

**Q7 — Correct: B (IAM role with read-only permissions for the auditor to assume)**

IAM roles can be created with read-only permissions (e.g., SecurityAudit or ReadOnlyAccess managed policies) and the external auditor can be granted permission to assume the role using cross-account access. This follows least privilege and avoids sharing credentials. Sharing root credentials or IAM user credentials is a security violation. AWS Config alone doesn't provide console access.

> **Exam Trap:** When granting external parties access, always use IAM roles with time-limited assumption — never share credentials.

---

**Q8 — Correct: B, D (SCP denying CloudTrail actions; Organization-level CloudTrail)**

Two complementary approaches: (1) An SCP can explicitly deny cloudtrail:DeleteTrail and cloudtrail:StopLogging to all accounts in the organization — even account admins cannot override SCPs. (2) Enabling CloudTrail at the organization level creates a trail in all accounts that member accounts cannot modify (read-only for member accounts). Config detects violations after the fact but can't prevent them. IAM permission boundaries affect users within an account but can still be overridden by account admins.

> **Exam Trap:** SCPs are preventive; Config is detective. For CANNOT disable = SCP or org-level trail, not Config.

---

**Q9 — Correct: C (Customer-managed keys in AWS KMS)**

Customer-managed keys (CMK) in AWS KMS give customers FULL control: you create the key, define the key policy (who can use it and when), can rotate it, can disable it, and can audit all usage via CloudTrail. AWS-owned keys — AWS fully manages them, customers have no visibility or control. AWS-managed keys — AWS rotates them automatically, customers can see them but can't control policies. SSL/TLS is encryption in transit, not at rest.

> **Exam Trap:** AWS-owned keys (default) are convenient but give zero customer control. Customer-managed CMKs give maximum control. AWS-managed keys are a middle ground.

---

**Q10 — Correct: B (AWS Systems Manager Patch Manager)**

AWS Systems Manager Patch Manager automates the discovery and remediation of missing patches across EC2 instances (and on-premises servers). You define patch baselines, maintenance windows, and compliance reporting. Amazon Inspector identifies vulnerabilities (software CVEs) but doesn't automatically deploy patches. Security Hub aggregates findings but doesn't patch. GuardDuty detects threats but doesn't patch.

> **Exam Trap:** Inspector IDENTIFIES vulnerabilities; Patch Manager REMEDIATES them. Both are relevant to patching but serve different functions.

---

**Q11 — Correct: C (Physically destroying decommissioned hard drives)**

Physical destruction of decommissioned storage media in AWS data centers is solely AWS's responsibility — customers have no access to physical hardware. All other options are the customer's responsibility: configuring IAM, encrypting application data, and enabling MFA are all customer actions that AWS provides tools for but does not perform.

> **Exam Trap:** The Shared Responsibility Model: AWS manages security "of" the cloud (physical infrastructure). Customers manage security "in" the cloud (configurations, data, access).

---

**Q12 — Correct: B, C (CloudTrail with log file validation; S3 with Object Lock for storage)**

An immutable audit log requires: (1) AWS CloudTrail with log file validation enabled — this uses SHA-256 hashing to detect if log files have been tampered with; (2) storing those logs in S3 with Object Lock (WORM) so they cannot be deleted or modified during the retention period. CloudWatch Logs are for application/system logs, not API audit logs. Config tracks resource configurations, not a complete API audit trail. GuardDuty logs are for threat detection.

> **Exam Trap:** CloudTrail alone is not immutable — logs in S3 can be deleted. You need Object Lock to make them truly immutable.

---

**Q13 — Correct: B (S3 Block Public Access at the account level)**

S3 Block Public Access settings at the account (or bucket) level prevent any bucket ACL or bucket policy from granting public access — these settings OVERRIDE any individual bucket configuration that attempts to enable public access. This is a preventive control that stops the misconfiguration from being applied at all. Versioning protects data from deletion. Object Lock prevents modification. CloudTrail logs the action after it happens.

> **Exam Trap:** S3 Block Public Access is the ONLY way to guarantee that no bucket in an account can be made public. Individual bucket settings are overridden by account-level Block Public Access.

---

**Q14 — Correct: C (Cognito User Pool — social identity provider / federated sign-in)**

Amazon Cognito User Pools support federated sign-in via social identity providers (Google, Facebook, Apple, Amazon) and SAML/OIDC providers. This allows users to sign in with their existing Google accounts. Cognito Identity Pools provide AWS credentials (for accessing AWS services), not app sign-in. IAM Identity Center is for employee access to AWS accounts, not customer-facing apps.

> **Exam Trap:** Cognito User Pools = app user authentication. Cognito Identity Pools = AWS resource access. IAM Identity Center = employee AWS console access.

---

**Q15 — Correct: C (AWS Security Hub — aggregated security findings)**

AWS Security Hub aggregates, organizes, and prioritizes security findings from multiple AWS services (GuardDuty, Inspector, Macie, Config, Firewall Manager) and third-party tools into a centralized security dashboard. It evaluates resources against security best practices and provides a security score. Trusted Advisor has some security checks but is primarily an optimization tool. Inspector does network assessments but focuses on EC2/containers. Macie focuses specifically on S3 data protection.

> **Exam Trap:** Security Hub is the AGGREGATOR of security findings. The other services (GuardDuty, Inspector, Macie) are the GENERATORS of findings that feed into Security Hub.

---

**Q16 — Correct: B (IAM account password policy)**

AWS IAM account password policy allows administrators to set requirements for all IAM user passwords in the account, including minimum length, character type requirements, password expiration, prevention of password reuse (last N passwords), and requiring users to change their password at first login. Access key rotation is for access keys, not passwords. Secrets Manager is for application secrets. Cognito password policies apply to Cognito user pools.

> **Exam Trap:** IAM password policy = IAM console user passwords. Cognito password policy = app user passwords. They're separate systems.

---

**Q17 — Correct: C, E (Installing applications; Patching the OS on EC2)**

For EC2, customers are responsible for: everything inside the OS — installing applications, configuring software, and most importantly patching the operating system (since EC2 gives you control of the OS, unlike managed services like RDS). AWS is responsible for: hypervisor maintenance, physical server hardware, and data center network access. 

> **Exam Trap:** EC2 OS patching = customer responsibility. RDS OS patching = AWS responsibility. This is a key differentiator between managed (RDS) and unmanaged (EC2) services.

---

**Q18 — Correct: C (AWS Security Hub with security standards enabled)**

AWS Security Hub, when security standards are enabled, provides automated compliance checks against frameworks like CIS AWS Foundations Benchmark, AWS Foundational Security Best Practices, PCI DSS, and NIST. It provides a compliance score and dashboard across all accounts in the organization. AWS Audit Manager automates audit evidence collection. Trusted Advisor provides best practice recommendations. Amazon Detective helps investigate security incidents.

> **Exam Trap:** Audit Manager vs. Security Hub — Audit Manager COLLECTS evidence for auditors. Security Hub MONITORS and scores compliance posture in real time.

---

**Q19 — Correct: B (Internet Gateway + route in the route table pointing to the IGW)**

For EC2 instances in a public subnet to receive inbound internet traffic: (1) An Internet Gateway must be attached to the VPC; (2) The subnet's route table must have a route (0.0.0.0/0 → IGW) directing internet traffic through the IGW; (3) The EC2 instance also needs a public IP (Elastic IP or auto-assigned public IP). A NAT Gateway is for OUTBOUND internet access from private subnets — it does NOT allow inbound connections.

> **Exam Trap:** NAT Gateway = outbound only for private subnets. Internet Gateway = bidirectional for public subnets. A subnet becomes 'public' by having a route to the IGW.

---

**Q20 — Correct: C (AWS Transit Gateway)**

AWS Transit Gateway is a hub-and-spoke network transit hub that can connect thousands of VPCs and on-premises networks through a single gateway. As networks grow, Transit Gateway dramatically reduces the complexity of managing hundreds of individual VPC peering connections (which scale as N*(N-1)/2 connections). VPC Peering is point-to-point and doesn't scale. PrivateLink exposes services, not networks. Direct Connect Gateway connects on-premises to AWS.

> **Exam Trap:** VPC Peering is simple and free for small numbers of VPCs but becomes unmanageable at scale. Transit Gateway is the scalable solution.

---

**Q21 — Correct: B (Route 53 private hosted zones)**

Route 53 private hosted zones allow you to create DNS records (like database.internal.company.com) that are only resolvable within one or more specified VPCs — they are not visible on the public internet. Public hosted zones are for publicly resolvable DNS. Resolver outbound endpoints forward queries from the VPC to on-premises DNS. ALIAS records point to AWS resources but in a public zone.

> **Exam Trap:** Private hosted zones ≠ private DNS within a VPC by default. You must associate the private hosted zone with the VPC for instances in that VPC to resolve it.

---

**Q22 — Correct: A, B (CloudFront; Global Accelerator)**

Without re-deploying the application to a new Region: (1) CloudFront caches static and dynamic content at Asia-Pacific edge locations — users get content from the nearest edge, dramatically reducing latency; (2) Global Accelerator routes user requests through the AWS global backbone network to the us-east-1 endpoint faster than the public internet. Route 53 latency routing requires a new deployment in ap-southeast-1. ElastiCache in us-east-1 doesn't help Asia-Pacific users.

> **Exam Trap:** CloudFront and Global Accelerator both improve global performance without a new Region deployment. The key difference: CloudFront CACHES content; Global Accelerator ROUTES traffic optimally.

---

**Q23 — Correct: B (AWS Direct Connect)**

AWS Direct Connect provides a dedicated, private network connection from on-premises to AWS, bypassing the public internet entirely. It offers consistent latency, predictable bandwidth, and lower data transfer rates for high-volume workloads. Site-to-Site VPN is encrypted but uses the public internet — still subject to internet congestion. PrivateLink connects within AWS. VPC Peering connects VPCs.

> **Exam Trap:** VPN = encrypted but public internet (variable latency). Direct Connect = dedicated private connection (consistent latency). For SLA-grade connectivity, use Direct Connect.

---

**Q24 — Correct: B (AWS WAF with IP set rules and SQL injection rules on the ALB)**

AWS WAF can block specific IP addresses using IP set rules AND detect/block SQL injection attempts in HTTP requests using managed rule groups — both applied to the Application Load Balancer. Security Groups block at IP/port level (Layer 3/4) but cannot inspect HTTP content. NACLs can block IPs but not SQL injection. Shield + Inspector don't provide request-level filtering.

> **Exam Trap:** Security Groups can block IPs but CANNOT inspect HTTP request content. WAF operates at Layer 7 (HTTP) — it can inspect headers, URI paths, query strings, and request body.

---

**Q25 — Correct: C (Failover routing)**

Route 53 Failover routing is designed exactly for this scenario: the primary resource serves traffic normally; if the primary health check fails, Route 53 automatically redirects all traffic to the secondary (failover) resource. Weighted routing splits traffic by percentage ratios. Geolocation routes based on user's geographic origin. Multivalue answer returns multiple healthy records for load distribution (not primary/backup).

> **Exam Trap:** Failover routing ≠ weighted routing. Failover = all-or-nothing switch based on health. Weighted = split traffic by ratio.

---

**Q26 — Correct: B (A subnet is public when its route table has a route to an Internet Gateway)**

The ONLY difference between a public and private subnet is the route table: a public subnet has a route (0.0.0.0/0) pointing to an Internet Gateway; a private subnet does not. Both can use IPv4. The intended use (web server vs. database) is a best practice, not a technical definition. Private subnets CAN initiate outbound traffic — through a NAT Gateway.

> **Exam Trap:** Public/private subnet is entirely determined by the route table, not by the type of resources in the subnet. A 'database in a public subnet' is a bad practice but technically valid.

---

**Q27 — Correct: B (Configure Lambda to run inside the VPC with appropriate security group rules)**

AWS Lambda can be configured to run inside a VPC by specifying subnets and security groups. This allows Lambda functions to securely access VPC-private resources like RDS databases using private IPs, without the RDS being publicly accessible. Assigning a public IP to RDS defeats the purpose of a private subnet. Lambda doesn't need an Internet Gateway or Direct Connect to access VPC resources.

> **Exam Trap:** Lambda runs outside VPCs by default — it cannot reach VPC-internal resources unless explicitly configured to run inside the VPC. VPC-enabled Lambda requires proper subnet and security group configuration.

---

**Q28 — Correct: C (Latency-based routing)**

Latency-based routing directs users to the Region that provides the LOWEST MEASURED LATENCY — based on actual network latency measurements, not geographic distance. Geoproximity routing is based on the geographic distance between users and resources (can be biased). Geolocation routing is based on the requestor's geographic location (country/continent), not latency. Weighted routing distributes traffic by percentage.

> **Exam Trap:** Geolocation routes based on WHERE the user is (country). Latency-based routes based on SPEED (actual network latency). They often produce similar results but are conceptually and technically different.

---

**Q29 — Correct: C (Spot Instances)**

Spot Instances are ideal for fault-tolerant batch jobs that can tolerate interruptions — they offer discounts of up to 90% vs. On-Demand. The key characteristics that make this workload suitable: it's fault-tolerant and can be paused/resumed. On-Demand is full price. Reserved Instances require a 1-3 year commitment for a one-time batch job type. Dedicated Hosts are for compliance/licensing.

> **Exam Trap:** "Fault-tolerant" + "can tolerate interruptions" = Spot Instances. "Cannot be interrupted" = On-Demand or Reserved. Read the scenario carefully for interruptibility.

---

**Q30 — Correct: B (Amazon EBS)**

Amazon EBS (Elastic Block Store) provides persistent block storage for EC2 instances — data persists even when the instance is stopped or restarted. It supports high IOPS configurations suitable for financial transaction processing. EC2 instance store is ephemeral — data is lost when the instance stops. EFS is file storage for multiple instances (not block). S3 is object storage accessed via HTTP, not block-level I/O.

> **Exam Trap:** EC2 instance store is the FASTEST disk option but is ephemeral (data lost on stop/terminate). EBS is persistent block storage. For production databases requiring persistence, always EBS.

---

**Q31 — Correct: B (AWS Lambda + Amazon API Gateway)**

AWS Lambda + API Gateway is the canonical serverless architecture for HTTP applications — fully managed, no servers, no infrastructure to provision, scales automatically. EC2 Auto Scaling + ALB is powerful but requires managing EC2 instances. ECS on EC2 + NLB is container-based but requires EC2 node management. Lightsail is a simplified VPS — still has servers.

> **Exam Trap:** "Without managing infrastructure" + "focus entirely on code" = serverless = Lambda + API Gateway. Elastic Beanstalk and Lightsail still provision underlying servers.

---

**Q32 — Correct: B, D (Right-size to Memory Optimized; Use AWS Compute Optimizer)**

The workload uses 10% CPU but 80% memory — it's memory-bound, not CPU-bound. Right-sizing action: switch to a Memory Optimized instance (R-family) which offers more RAM per dollar. AWS Compute Optimizer analyzes CloudWatch utilization metrics and recommends the optimal instance type using ML. Switching to Spot Instances reduces cost but doesn't fix the instance type mismatch. Adding EBS volumes addresses storage, not memory/CPU optimization.

> **Exam Trap:** Low CPU ≠ right-sized. High memory usage tells you the workload is memory-bound — you need a Memory Optimized instance, not just a cheaper version of the wrong type.

---

**Q33 — Correct: C (AWS Systems Manager — SSM)**

AWS Systems Manager provides a unified operational hub for managing EC2 instances at scale — including Run Command (remote command execution without SSH), State Manager (automation runbooks for maintaining state), Patch Manager (patch automation), and Session Manager (secure remote access). CloudFormation provisions infrastructure. Elastic Beanstalk deploys applications. EC2 Auto Scaling manages instance count.

> **Exam Trap:** CloudFormation is for provisioning infrastructure (creating EC2 instances). Systems Manager is for operating/managing existing instances (running commands, patching, configuring).

---

**Q34 — Correct: B (Auto Scaling group's scaling policies and CloudWatch alarms)**

Auto Scaling groups use CloudWatch alarms to trigger scaling actions — if the alarm threshold or cooldown periods are not tuned correctly, the group may scale too slowly, causing users to experience latency during the ramp-up period. The IAM role doesn't affect scaling speed. Internet Gateway bandwidth is not a bottleneck for auto scaling. RDS Multi-AZ affects database availability, not Auto Scaling response time.

> **Exam Trap:** Auto Scaling doesn't react instantly — it depends on CloudWatch alarm evaluation periods, cooldown periods, and instance warm-up time. Slow scaling = policy tuning needed.

---

**Q35 — Correct: A (On-Demand GPU instances during December only)**

On-Demand GPU instances (P or G family) during December only is the most cost-effective for SEASONAL workloads: you pay only for the hours used in December with no commitment. Reserved Instances for 3 years would pay for GPU capacity 11 months of the year that isn't used — enormous waste. Standard C-family instances don't have GPUs — wrong tool. Dedicated Hosts year-round also pays for idle months.

> **Exam Trap:** Reserved Instances save money for steady-state workloads. For seasonal or one-time workloads, On-Demand avoids paying for unused capacity outside the season.

---

**Q36 — Correct: B (Lifecycle policy: Standard → Standard-IA at 7 days → Glacier Deep Archive at 30 days)**

The Lifecycle policy precisely matches the access patterns: S3 Standard for the first 7 days (frequent access), then S3 Standard-IA (rare access, lower cost), then S3 Glacier Deep Archive at 30 days (archival, lowest cost) for the 5-year retention. Storing everything in S3 Standard is expensive. Intelligent-Tiering is for unpredictable access patterns — it doesn't offer fine-grained time-based archival to Glacier Deep Archive. Storing immediately in Glacier means no easy access during the first 7 days.

> **Exam Trap:** S3 Intelligent-Tiering is NOT the answer for ALL storage optimization questions. When you have PREDICTABLE access patterns with time-based rules, Lifecycle policies are more appropriate and cost-effective.

---

**Q37 — Correct: B (S3 Versioning + S3 MFA Delete)**

S3 Versioning retains all versions of objects, allowing recovery from accidental deletion (the delete creates a marker but the previous version is preserved). S3 MFA Delete requires MFA authentication for permanent deletion of versions or suspending versioning — meeting the regulatory requirement that objects cannot be permanently deleted without MFA authorization. S3 Replication copies data but doesn't inherently prevent deletion. Object Lock is WORM (can't be deleted during retention period).

> **Exam Trap:** Object Lock prevents all deletion (even authorized). MFA Delete adds a verification step for authorized deletion — specifically requiring MFA. Know which requirement each feature meets.

---

**Q38 — Correct: C (Amazon FSx for Lustre)**

Amazon FSx for Lustre is a fully managed, high-performance parallel file system purpose-built for HPC workloads — it provides sub-millisecond latency and hundreds of GB/s of throughput. It supports simultaneous access from thousands of compute nodes. EBS with Multi-Attach has limited compatibility and throughput. EFS provides good shared access but is NFS-based and less suited for extreme HPC throughput requirements. S3 Transfer Acceleration speeds up object uploads/downloads but doesn't provide a file system.

> **Exam Trap:** EFS vs. FSx for Lustre — EFS is good for general shared file storage (NFS). FSx for Lustre is for HIGH-PERFORMANCE COMPUTING requiring extreme throughput and POSIX compliance.

---

**Q39 — Correct: B, E (S3 is object/HTTP; EBS is block/single instance; EFS is file/multi-instance; S3 11 nines durability)**

S3 = object storage accessed via HTTP APIs, designed for web-scale storage; EBS = block storage mounted to a single EC2 instance (like a hard drive); EFS = file system mountable by multiple EC2 instances via NFS. S3 provides 11 nines (99.999999999%) of data durability — a well-known AWS fact. EBS cannot be attached to hundreds of instances simultaneously (Multi-Attach is limited). EFS stores data as files, not key-value pairs (DynamoDB is key-value).

> **Exam Trap:** EBS Multi-Attach exists but is very limited (max 16 instances, only io1/io2 volumes, same AZ). The general rule is still: EBS = one instance at a time.

---

**Q40 — Correct: B (AWS Snowball Edge — Compute Optimized)**

AWS Snowball Edge Compute Optimized is a ruggedized edge computing and data transfer device that can run compute workloads locally (EC2-compatible instances, Lambda functions) and synchronize data to AWS S3 even with intermittent connectivity. It's designed for edge computing in environments like factories, ships, and remote locations. Storage Gateway — Volume Gateway is for hybrid cloud block storage. S3 Transfer Acceleration requires active internet. DataSync requires consistent network connectivity for scheduled syncs.

> **Exam Trap:** Snowball is commonly associated with large one-time data migration. Snowball Edge adds LOCAL COMPUTE capability for edge processing — different use case from pure data transfer.

---

**Q41 — Correct: B (Aurora Read Replicas)**

Amazon Aurora supports up to 15 Read Replicas (vs. 5 for standard RDS) that can serve read traffic from reporting applications, reducing load on the primary instance. Aurora Multi-AZ standby is for automatic failover — it cannot serve read traffic (similar to standard RDS Multi-AZ). Aurora Global Database replicates to other Regions for disaster recovery and global read access. Aurora Serverless scales capacity automatically but doesn't specifically distribute read load.

> **Exam Trap:** Aurora Multi-AZ standby ≠ Read Replicas. The standby is for failover ONLY. Read Replicas serve read traffic AND can be used for failover promotion.

---

**Q42 — Correct: B (Amazon Aurora)**

Amazon Aurora is a cloud-native relational database that provides up to 5x the performance of standard MySQL and 3x the performance of PostgreSQL. It supports up to 15 Read Replicas, automatic backups with point-in-time recovery, and automatic minor version upgrades. Standard RDS MySQL supports up to 5 Read Replicas and doesn't claim 5x performance. DynamoDB is NoSQL. Redshift is a data warehouse.

> **Exam Trap:** Aurora IS compatible with MySQL and PostgreSQL but is its own database engine optimized for the cloud — not just "RDS MySQL with better performance."

---

**Q43 — Correct: B (Amazon Aurora Serverless)**

Amazon Aurora Serverless automatically adjusts read and write capacity based on actual usage with no downtime — perfect for variable/unpredictable traffic e-commerce workloads. You don't pre-provision capacity. RDS Multi-AZ provides failover but requires pre-provisioned capacity. Redshift is a data warehouse. ElastiCache is a caching layer, not a primary relational database.

> **Exam Trap:** Aurora Serverless = capacity scales automatically. Standard Aurora = you provision a specific instance size. Both are relational databases.

---

**Q44 — Correct: C (Amazon RDS for SQL Server)**

Amazon RDS for SQL Server provides a fully managed SQL Server environment — minimal application changes since the SQL Server engine is the same. DynamoDB is NoSQL and requires major application changes. Redshift is a columnar data warehouse. Aurora PostgreSQL is a different relational engine requiring application modifications.

> **Exam Trap:** "Minimal changes to the application" means you need the SAME database engine. SQL Server → RDS for SQL Server. Oracle → RDS for Oracle. Not a migration to a different engine.

---

**Q45 — Correct: B (CloudWatch Alarm + Amazon SNS + AWS Lambda)**

The solution: CloudWatch monitors EC2 CPU utilization metric → CloudWatch Alarm triggers when CPU > 90% for 10 minutes → sends notification via SNS → SNS invokes Lambda function → Lambda calls the EC2 API to restart the instance. CloudTrail logs API calls — doesn't monitor metrics. Config evaluates configuration compliance. GuardDuty detects threats.

> **Exam Trap:** CloudWatch Alarms can trigger EC2 actions (reboot, stop, terminate) DIRECTLY as alarm actions — you don't necessarily need Lambda for simple restart actions. But for custom logic, Lambda is the correct addition. SNS is the notification mechanism.

---

**Q46 — Correct: B (AWS CloudTrail event history)**

AWS CloudTrail records all AWS API calls in the account, including who made the call, from which IP address, which service/action was called, and when. CloudTrail event history provides a searchable log of the past 90 days of management events for free. VPC Flow Logs capture network traffic (IP/port), not AWS API calls. Config captures resource configuration state changes. CloudWatch Logs captures application/system logs.

> **Exam Trap:** CloudTrail = WHO called WHAT AWS API. VPC Flow Logs = WHAT network traffic entered/left a VPC. CloudWatch Logs = application logging. Config = WHAT configuration resources have. All different.

---

**Q47 — Correct: C (AWS Config rules with automatic remediation actions)**

AWS Config continuously evaluates resource configurations against Config rules (e.g., s3-bucket-server-side-encryption-enabled). When a resource violates a rule, Config can trigger automatic remediation using AWS Systems Manager Automation documents — for example, automatically enabling encryption on non-compliant S3 buckets. CloudTrail logs changes but doesn't remediate. CloudWatch with metric filters can trigger alarms but doesn't evaluate resource configuration compliance. Inspector scans for software vulnerabilities.

> **Exam Trap:** Config detects + can remediate configuration drift. CloudTrail detects changes but doesn't evaluate against policy or remediate. Config rules + remediation = the full compliance automation loop.

---

**Q48 — Correct: B, D (Trusted Advisor — full checks require Business/Enterprise; 7 core checks are free)**

These two statements together correctly describe AWS Trusted Advisor: Basic and Developer plans provide access to 7 core checks (covering basic security and service limits). Full access to ALL checks (including cost optimization, performance, and fault tolerance checks) requires a Business or Enterprise support plan. The Personal Health Dashboard is free for all accounts. Cost Explorer is free. CloudWatch has a free tier but full alarm functionality has costs.

> **Exam Trap:** Trusted Advisor has TWO tiers of access — 7 free core checks vs. full checks (Business/Enterprise). Know this distinction cold for the exam.

---

**Q49 — Correct: C (Compute Savings Plans — 2-year commitment)**

Compute Savings Plans offer savings (up to 66%) across ANY EC2 instance family, size, OS, tenancy, and Region, as well as AWS Fargate and Lambda — maximum flexibility with a 2-year commitment. On-Demand is full price with no commitment. Spot Instances can be interrupted — not suitable for 24/7 continuous production workloads. Standard Reserved Instances (1-year) provide less savings duration and are locked to a specific instance type.

> **Exam Trap:** Compute Savings Plans vs. Standard Reserved Instances — Savings Plans offer flexibility across instance types/regions; Standard RIs are locked to a specific type/region but can offer higher discounts for the most predictable workloads.

---

**Q50 — Correct: B (AWS Budgets with a forecasted cost budget alert)**

AWS Budgets supports FORECASTED budget alerts — it projects future spending based on current usage trends and alerts when the forecast is expected to EXCEED the budget threshold, before the actual bill arrives. This is the key differentiator from regular cost alerts. CloudWatch billing alarms trigger when ACTUAL costs exceed a threshold (reactive). Cost Explorer shows historical and forecasted data but doesn't proactively alert. Pricing Calculator estimates costs for new workloads.

> **Exam Trap:** AWS Budgets has two types of cost alerts: actual (current charges exceeded) and forecasted (projected to exceed). The question asks specifically for FORECASTED — AWS Budgets is the only service with this capability.

---

**Q51 — Correct: B, C (Volume discounts on aggregate usage; RI and Savings Plans sharing)**

Consolidated billing cost benefits: (1) Aggregate usage across all accounts qualifies for higher volume pricing tiers — for example, S3 per-GB pricing decreases in tiers and pooled usage across 10 accounts reaches lower pricing faster than any one account alone; (2) Reserved Instances and Savings Plans purchased in one account can be applied to any other account in the organization, ensuring maximum utilization of committed discounts. TAM is included in Enterprise support, not consolidated billing. Each account gets its own 12-month free tier.

> **Exam Trap:** Individual accounts each get their own Free Tier — they are NOT shared across an organization. RI/Savings Plans discounts ARE shared.

---

**Q52 — Correct: C (AWS Pricing Calculator)**

AWS Pricing Calculator (calculator.aws.amazon.com) allows you to estimate the monthly cost of specific AWS services by configuring resource settings before deployment — perfect for pre-deployment cost modeling. Cost Explorer analyzes existing AWS spending. Migration Evaluator compares on-premises vs. AWS costs. Budgets sets spending alerts for existing accounts.

> **Exam Trap:** Pricing Calculator = estimate FUTURE costs for planned workloads (no account needed). Cost Explorer = analyze ACTUAL historical costs of existing AWS usage.

---

**Q53 — Correct: B (Standard Reserved Instances — 1 year, all upfront)**

For stable, predictable 24/7 production usage that has been running for 6 months without interruption, Standard Reserved Instances for 1 year with all upfront payment offers the maximum discount (up to 72% off On-Demand) without service interruption. Switching to Spot Instances risks interruption — unacceptable for production. Adding more instances increases cost. Auto Scaling to reduce count could affect production availability.

> **Exam Trap:** Spot Instances = cheapest but interruptible. Reserved Instances = committed discount for steady-state workloads. For PRODUCTION that cannot be interrupted, Reserved is correct.

---

**Q54 — Correct: B (Create an AWS Organization and invite all accounts for consolidated billing)**

The correct first step is to create an AWS Organization (designating one account as management/master account) and then invite the other 4 accounts to join as member accounts. This enables consolidated billing automatically — all member account charges appear on the management account's bill. You cannot merge accounts into one. Purchasing RIs separately doesn't solve the billing complexity. Cost Explorer can't merge bills.

> **Exam Trap:** AWS Organizations is the service that enables consolidated billing — not a direct AWS billing feature on its own. Organizations also enables SCPs, but billing consolidation is a key feature.

---

**Q55 — Correct: B (Make frequent, small, reversible changes using deployment pipelines)**

The Operational Excellence pillar's design principle of making frequent, small, reversible changes reduces the blast radius of any single deployment. Using deployment pipelines with automated testing and the ability to roll back minimizes the risk of a single misconfigured deployment causing a production outage. Implementing strong identity = Security pillar. Automate for experimentation = also Operational Excellence but more about infrastructure testing. Managed services = reduces operational burden overall.

> **Exam Trap:** Multiple Well-Architected principles seem relevant to reducing deployment risk. "Frequent, small, reversible changes" is the most DIRECT principle addressing deployment-caused outages.

---

**Q56 — Correct: B (Security — Enable traceability)**

'Enable traceability' is a core Security pillar design principle: integrate logs and metrics with systems to automatically respond and alert, maintain a complete audit trail of all actions, and enable investigation of security incidents. This directly aligns with logging and automated response. 'Perform operations as code' = Operational Excellence. 'Automatically recover from failure' = Reliability. 'Cloud financial management' = Cost Optimization.

> **Exam Trap:** Traceability sounds operational but it's a SECURITY principle — knowing who did what, when, and from where is fundamental to security posture.

---

**Q57 — Correct: A, B (AWS Well-Architected Tool; AWS Trusted Advisor)**

The AWS Well-Architected Tool is a self-service tool that guides you through structured review questions across all six pillars and generates a report highlighting high-risk issues. AWS Trusted Advisor provides automated best practice checks against AWS-defined guidelines (overlapping with Well-Architected recommendations in security, cost, fault tolerance, and performance). Cost Explorer is for cost analysis. CloudFormation Drift Detection checks infrastructure state. Inspector scans for software vulnerabilities.

> **Exam Trap:** Well-Architected Tool is for in-depth architectural reviews. Trusted Advisor is for automated, ongoing operational checks. Both validate architectures — from different angles.

---

**Q58 — Correct: B (Automatically recover from failure)**

The scenario describes manual intervention (backup restore) that takes 8-12 hours — the fundamental violation is the absence of automated recovery. The Reliability pillar's 'Automatically recover from failure' principle requires systems to detect and recover from failures without human intervention. 'Stop guessing capacity' is about provisioning. 'Scale horizontally' is about distributing load. 'Test recovery procedures' is violated too, but the PRIMARY violation is no automation.

> **Exam Trap:** Backup and restore IS a DR strategy (the cheapest), but its RTO (hours) violates 'automatically recover.' The principle isn't just about having a backup — it's about automated, fast recovery.

---

**Q59 — Correct: C (Use multiple small resources instead of one large resource)**

The Performance Efficiency pillar design principle 'Use multiple small resources instead of one large resource' recommends distributing load horizontally. This improves utilization, resilience, and allows more granular scaling. 'Democratize advanced technologies' means using AWS managed services instead of building them yourself. 'Mechanical sympathy' means understanding the hardware characteristics. 'Go global in minutes' means deploying in multiple regions easily.

> **Exam Trap:** 'Democratize advanced technologies' and 'use multiple small resources' are both Performance Efficiency principles. Read carefully — the scenario is about splitting load across instances, not about using managed services.

---

**Q60 — Correct: A, C (IaC for consistent provisioning; Document lessons learned after incidents)**

Operational Excellence design principles: (1) 'Perform operations as code' — using IaC (CloudFormation, CDK) ensures consistent, repeatable, version-controlled infrastructure deployment; (2) 'Learn from all operational events and failures' — annotating runbooks with lessons learned improves procedures over time. Single-AZ deployment reduces reliability. Reserved Instances are a Cost Optimization action. Glacier for all backups ignores recovery time requirements.

> **Exam Trap:** Cost optimization actions (Reserved Instances) are often included as distractors in Well-Architected pillar questions. Always match the action to the correct pillar.

---

**Q61 — Correct: C (AWS X-Ray)**

AWS X-Ray provides distributed tracing for microservices architectures — it traces requests as they travel through multiple services, identifies bottlenecks, visualizes service maps, and helps diagnose performance issues. CloudTrail records API calls to AWS services. CloudWatch monitors metrics and logs. Amazon Detective investigates security incidents using log data.

> **Exam Trap:** CloudWatch monitors metrics (CPU, latency, error counts). X-Ray traces the actual request FLOW through services, showing where latency is introduced in a distributed system.

---

**Q62 — Correct: B (Amazon Transcribe)**

Amazon Transcribe is AWS's automatic speech recognition (ASR) service that converts spoken audio to text — ideal for generating captions and subtitles for video content. Amazon Polly does the OPPOSITE: it converts TEXT to SPEECH (text-to-speech). Amazon Comprehend analyzes text for sentiment, entities, and key phrases. Amazon Lex builds conversational chatbots using NLU.

> **Exam Trap:** Polly vs. Transcribe — Polly = text → speech. Transcribe = speech → text. These are commonly swapped on the exam. Remember: Transcribe = convert audio TO text (like a transcription service).

---

**Q63 — Correct: C (Amazon Translate)**

Amazon Translate is a neural machine translation service that provides fast, high-quality language translation. It supports real-time translation and batch translation for large volumes of text across dozens of languages. Amazon Comprehend analyzes text (sentiment, entities) but doesn't translate. Rekognition analyzes images and video. Textract extracts text from documents.

> **Exam Trap:** Comprehend understands text (sentiment, language detection, entities). Translate converts text from one language to another. They're often confused because Comprehend can detect language — but only Translate actually translates.

---

**Q64 — Correct: C (Amazon Lex)**

Amazon Lex is AWS's conversational AI service for building chatbots with natural language understanding (NLU) and automatic speech recognition (ASR). It supports multi-turn conversations, intents, slots, and can integrate with websites, mobile apps, and messaging platforms. Polly converts text to speech. Transcribe converts speech to text. Rekognition analyzes images and video.

> **Exam Trap:** Lex is the conversational CHATBOT service. Comprehend understands text passively. Lex actively manages conversation flows with intents and dialog management.

---

**Q65 — Correct: B, D (Amazon Comprehend for sentiment analysis and entity detection; Amazon Comprehend for key phrase and topic extraction)**

Both correct answers point to Amazon Comprehend — the NLP service that performs sentiment analysis (positive/negative/neutral/mixed), entity recognition (people, products, places), key phrase extraction, and topic modeling on text. The two correct choices both describe valid, different capabilities of Comprehend. Rekognition is for image/video analysis. Textract extracts text from scanned documents (not NLP analysis). Polly converts text to speech.

> **Exam Trap:** This question tests whether you know that Comprehend handles MULTIPLE text analysis tasks — sentiment, entities, key phrases, syntax, and topic detection — all in the same service. Both B and D are correct because they describe different Comprehend capabilities.

---

## Scoring Guide

| Score | Percentage | Result |
|-------|-----------|--------|
| 59–65 | 91–100% | Outstanding — Exam Ready |
| 52–58 | 80–89% | Strong — Review weak areas |
| 46–51 | 71–79% | Passing — More practice recommended |
| 39–45 | 60–70% | Borderline — Significant review needed |
| < 39 | < 60% | Not ready — Focused study required |

---

## Domain-by-Domain Study Checklist

### Cloud Concepts
- [ ] Region vs. AZ vs. Edge Location — know exact definitions
- [ ] Elasticity vs. scalability vs. agility (three different concepts)
- [ ] High availability vs. fault tolerance (HA = minimal downtime, FT = zero downtime)
- [ ] CapEx vs. OpEx — cloud shifts to OpEx (variable expense)
- [ ] Multi-AZ vs. Multi-Region — different levels of resiliency

### Security
- [ ] Shared Responsibility Model — know EC2 vs. RDS vs. Lambda customer vs. AWS responsibilities
- [ ] Root user — cannot be deleted, must have MFA, rarely use, cannot attach IAM policies
- [ ] IAM roles vs. IAM users — roles for EC2 instances (never install access keys on EC2)
- [ ] SCP (preventive) vs. Config (detective) vs. CloudTrail (audit)
- [ ] KMS CMK (full customer control) vs. AWS-managed keys vs. AWS-owned keys
- [ ] S3 Block Public Access — account-level override that prevents any public bucket
- [ ] Object Lock Compliance vs. MFA Delete vs. Versioning — different protections
- [ ] Cognito User Pools (app auth) vs. Identity Pools (AWS credentials) vs. IAM Identity Center (employees)
- [ ] Security Hub = aggregator; GuardDuty, Inspector, Macie = generators
- [ ] WAF = Layer 7 HTTP filtering; Security Groups = Layer 3/4; NACLs = stateless subnet-level

### Networking
- [ ] Public subnet = route table has route to Internet Gateway
- [ ] Private subnet = no route to Internet Gateway; uses NAT Gateway for outbound only
- [ ] NAT Gateway = outbound only for private subnets; requires Internet Gateway to work
- [ ] Direct Connect = dedicated private (consistent); VPN = encrypted but public internet (variable)
- [ ] VPC Peering = point-to-point; Transit Gateway = hub-and-spoke (scalable)
- [ ] PrivateLink = expose specific services across accounts without peering
- [ ] CloudFront = CDN with caching; Global Accelerator = routing with static anycast IPs
- [ ] Route 53 routing policies: failover, latency-based, geolocation, weighted, multivalue, geoproximity
- [ ] Private hosted zones = DNS only resolvable within VPC; not on public internet

### Compute
- [ ] EC2 instance families: T (burstable/general), C (compute), R/X (memory), I (storage), P/G (GPU/ML)
- [ ] Spot = cheapest but interruptible; On-Demand = no commitment; Reserved = committed discount
- [ ] Compute Savings Plans = flexible across instance families; EC2 Instance Savings Plans = less flexible
- [ ] Lambda = max 15-minute timeout, event-driven, pay-per-invocation
- [ ] Fargate = serverless containers (no EC2 management); ECS/EKS on EC2 = manage EC2 nodes
- [ ] Systems Manager = manage/operate EC2 fleet; CloudFormation = provision infrastructure
- [ ] Auto Scaling policies + CloudWatch alarms = automatic scaling based on metrics

### Storage
- [ ] S3 = object storage (HTTP API); EBS = block storage (one EC2); EFS = file storage (many EC2, NFS)
- [ ] FSx for Windows = SMB for Windows; FSx for Lustre = HPC high-throughput
- [ ] S3 durability = 11 nines (99.999999999%)
- [ ] S3 Lifecycle policies = time-based archival to cheaper tiers (only way to move to Glacier automatically)
- [ ] S3 Intelligent-Tiering = automatic for unpredictable access (does NOT move to Glacier)
- [ ] Instance store = ephemeral (fastest); EBS = persistent; good for production databases
- [ ] Snowball Edge = edge compute + data transfer for disconnected/remote locations

### Database
- [ ] Aurora = up to 5x MySQL performance, up to 15 Read Replicas, cloud-native
- [ ] Aurora Serverless = auto-scales capacity; Aurora standard = provisioned capacity
- [ ] RDS Multi-AZ = automatic failover (standby NOT for reads); Read Replicas = read offloading
- [ ] DynamoDB Global Tables = multi-Region active-active; sub-second replication
- [ ] "Minimal application changes" = same database engine (e.g., SQL Server → RDS for SQL Server)
- [ ] Redshift = data warehouse (analytics, not OLTP); ElastiCache = caching layer

### Monitoring
- [ ] CloudWatch = metrics, alarms, dashboards, logs (YOUR resources)
- [ ] CloudTrail = API audit trail (WHO called WHAT API)
- [ ] Config = resource configuration compliance (WHAT configuration IS each resource)
- [ ] Personal Health Dashboard = YOUR account's service health events
- [ ] Service Health Dashboard = public/general AWS service status
- [ ] X-Ray = distributed tracing for microservices; request flow visualization
- [ ] Trusted Advisor: 7 core checks (Basic/Developer); all checks (Business/Enterprise)

### Pricing
- [ ] AWS Budgets = proactive alerts (actual OR forecasted); Cost Explorer = historical analysis
- [ ] Pricing Calculator = estimate future AWS costs before deployment
- [ ] Migration Evaluator (TCO Calculator) = on-premises vs. AWS cost comparison
- [ ] Consolidated billing = single bill + pooled volume discounts + shared RI/Savings Plans
- [ ] Each account gets its own Free Tier; they are NOT shared in an organization
- [ ] Basic support = billing/account questions only; Developer = technical cases; Business = all Trusted Advisor checks + 24/7 phone; Enterprise = TAM

### Well-Architected Framework
- [ ] 6 pillars: Operational Excellence, Security, Reliability, Performance Efficiency, Cost Optimization, Sustainability
- [ ] Operational Excellence: IaC, small/reversible changes, learn from incidents, runbooks
- [ ] Security: least privilege, enable traceability, defense in depth, automate security
- [ ] Reliability: multi-AZ, automatic recovery, test recovery procedures, no SPOF
- [ ] Performance Efficiency: right-sizing, multiple small resources, use managed services, test at scale
- [ ] Cost Optimization: right-sizing, Reserved/Savings Plans, Lifecycle policies, eliminate waste
- [ ] Sustainability: managed services, right-sizing, renewable energy Regions, reduce waste

### AI/ML Services
- [ ] Polly = TEXT → SPEECH (text-to-speech)
- [ ] Transcribe = SPEECH → TEXT (audio transcription)
- [ ] Lex = CHATBOT (NLU + ASR + dialog management)
- [ ] Comprehend = NLP analysis (sentiment, entities, key phrases, topics, language detection)
- [ ] Translate = language TRANSLATION (one language to another)
- [ ] Rekognition = IMAGE/VIDEO analysis (faces, objects, labels, moderation)
- [ ] Textract = DOCUMENT text extraction (scanned PDFs, forms, tables)

---

*This is Mock Exam 3 in the AWS CLF-C02 Practice Series. Use all three exams to assess readiness and identify weak domains before sitting the real exam.*
