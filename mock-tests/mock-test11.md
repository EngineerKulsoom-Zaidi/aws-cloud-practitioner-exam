# AWS Certified Cloud Practitioner (CLF-C02) — Full Mock Exam 2

**65 Questions | 90 Minutes | Pass Score: 70% (≥46 correct)**

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

A company is migrating to AWS and their CTO asks about AWS global infrastructure. Which statement CORRECTLY describes an AWS Availability Zone?

- A. A geographic area that contains multiple data centers connected by high-speed links
- B. One or more discrete data centers with redundant power, networking, and connectivity within a Region
- C. A physical location around the world where AWS caches data to reduce latency
- D. A separate physical location used only for disaster recovery

---

**Question 58** *(Choose ONE)*

A company wants to ensure their application remains available even if an entire AWS Availability Zone experiences an outage. Which architectural design principle achieves this?

- A. Deploy the application in a single large EC2 instance with EBS
- B. Deploy across at least two Availability Zones with a load balancer
- C. Enable CloudWatch alarms to detect AZ failures
- D. Use Amazon Route 53 with failover routing within a single Region

---

**Question 61** *(Choose ONE)*

Which of the following CORRECTLY distinguishes between horizontal scaling and vertical scaling in AWS?

- A. Horizontal scaling means upgrading to a larger instance; vertical scaling means adding more instances
- B. Horizontal scaling means adding more instances of the same size; vertical scaling means upgrading to a larger instance
- C. Horizontal scaling is only possible with Reserved Instances; vertical scaling uses Spot Instances
- D. Horizontal and vertical scaling are the same concept — both refer to elasticity

---

**Question 63** *(Choose ONE)*

A company's new cloud initiative aims to empower developers to experiment and fail fast without fear of large financial losses. Which AWS cloud advantage BEST supports this culture?

- A. Massive economies of scale
- B. Stop spending money running and maintaining data centers
- C. Trade capital expense for variable expense — low cost of experimentation
- D. Global reach in minutes

---

**Question 65** *(Choose TWO)*

An enterprise is evaluating the total value of migrating to AWS. Beyond cost savings, which of the following represent non-financial business value of cloud adoption?

- A. Higher CapEx spending on cloud hardware
- B. Faster time-to-market for new features and products
- C. Increased IT security through shared responsibility
- D. Access to continuously updated services and technologies without hardware refresh cycles
- E. Elimination of all operational overhead

---

### Domain: Security

---

**Question 2** *(Choose TWO)*

An AWS account root user has been used for all daily operations since the account was created. A cloud architect is performing a security review. Which actions should they recommend?

- A. Enable MFA on the root user account
- B. Delete the root user account to prevent misuse
- C. Create individual IAM users and groups for daily tasks
- D. Grant root user access to all developers for transparency
- E. Attach an IAM policy directly to the root user

---

**Question 5** *(Choose ONE)*

A startup is designing a new application and wants to implement security best practices from the beginning. According to the AWS Well-Architected Framework Security pillar, which design principle should they follow?

- A. Apply security at the application layer only
- B. Implement a strong identity foundation using least privilege access
- C. Use a single shared IAM user for the development team to simplify management
- D. Enable security controls only in production, not in development environments

---

**Question 11** *(Choose ONE)*

A company needs EC2 instances to read objects from a specific Amazon S3 bucket. What is the BEST approach following the principle of least privilege?

- A. Create an IAM user with S3 full access and install access keys on the EC2 instance
- B. Create an IAM role with a policy allowing s3:GetObject on the specific bucket and attach it to the EC2 instance
- C. Add the EC2 instance to a security group that allows S3 access
- D. Store the root user credentials in an environment variable on the EC2 instance

---

**Question 14** *(Choose ONE)*

An enterprise wants to prevent users in their AWS Organization from launching EC2 instances outside of specific approved AWS Regions. Which is the MOST effective way to enforce this?

- A. Configure IAM password policies for each account
- B. Apply a Service Control Policy (SCP) that denies EC2 actions in unapproved Regions
- C. Enable AWS Config rules to detect and terminate non-compliant instances
- D. Create IAM permission boundaries on all users

---

**Question 19** *(Choose ONE)*

A company is implementing a web application behind an Application Load Balancer. They want to ensure that only traffic inspected and allowed by a WAF is forwarded to their application. Which is the CORRECT architecture?

- A. Attach AWS WAF to the EC2 instances directly
- B. Associate AWS WAF with the Application Load Balancer
- C. Deploy AWS WAF on the NAT Gateway
- D. Configure WAF rules in the VPC Security Groups

---

**Question 22** *(Choose ONE)*

A company wants to identify sensitive data such as credit card numbers and Social Security numbers stored in their Amazon S3 buckets. Which AWS service should they use?

- A. AWS GuardDuty
- B. Amazon Inspector
- C. Amazon Macie
- D. AWS Config

---

**Question 27** *(Choose TWO)*

A company wants to centrally manage and enforce security policies across 50 AWS accounts and automatically remediate non-compliant resources. Which combination of AWS services BEST achieves this?

- A. AWS IAM in each account individually
- B. AWS Organizations with Service Control Policies
- C. AWS Config with Conformance Packs
- D. AWS Trusted Advisor in each account

---

**Question 31** *(Choose ONE)*

A developer accidentally pushed AWS access keys to a public GitHub repository. What should be the FIRST action taken?

- A. Delete the GitHub repository
- B. Rotate the compromised access keys immediately
- C. Change the IAM user's password
- D. Contact AWS Support to block access

---

**Question 37** *(Choose ONE)*

A company needs to provide read-only access to their AWS billing information to their finance team members. Which is the MOST SECURE approach?

- A. Share the root user credentials with the finance team
- B. Create a single IAM user 'Finance' and share the credentials
- C. Create individual IAM users for each finance team member and attach the Billing read-only policy
- D. Grant the finance team access via the AWS Pricing Calculator

---

**Question 40** *(Choose TWO)*

A company wants to ensure data is encrypted in transit between their on-premises applications and AWS services. Which protocols ensure encryption in transit?

- A. HTTP
- B. HTTPS / TLS
- C. AWS KMS
- D. SSL/TLS with AWS Certificate Manager
- E. FTP

---

**Question 46** *(Choose ONE)*

A company needs to ensure that specific users can only perform actions in AWS during business hours (9 AM to 5 PM on weekdays). Which IAM feature can enforce this?

- A. IAM roles with time-limited sessions
- B. IAM policies with Condition elements using aws:CurrentTime and aws:DayOfWeek
- C. AWS Organizations SCPs with time restrictions
- D. AWS Config rules to detect off-hours access

---

**Question 49** *(Choose ONE)*

A company wants to protect their AWS environment from DDoS attacks and also wants access to the AWS DDoS Response Team (DRT) during attacks. Which AWS Shield plan is required?

- A. AWS Shield Standard (free)
- B. AWS Shield Advanced
- C. AWS WAF with DDoS rules
- D. Amazon GuardDuty with DDoS detection

---

**Question 55** *(Choose ONE)*

A company wants to use a third-party identity provider (like Okta or Active Directory) to allow employees to sign in to the AWS Management Console using their existing corporate credentials. Which AWS feature enables this?

- A. Creating individual IAM users matching Active Directory accounts
- B. AWS Cognito User Pools
- C. IAM Identity Center with SAML 2.0 federation
- D. AWS Directory Service for Microsoft Active Directory

---

**Question 57** *(Choose TWO)*

A company runs a multi-tier web application. They want to implement the principle of 'defense in depth' for network security. Which combination reflects this principle?

- A. Use a single Security Group that allows all traffic
- B. Apply NACLs at the subnet level and Security Groups at the instance level
- C. Use AWS WAF to filter malicious HTTP traffic at the load balancer level
- D. Store all data in a public S3 bucket for easy access
- E. Use a single firewall rule for all application tiers

---

**Question 59** *(Choose ONE)*

A financial company requires that all data stored in Amazon S3 is encrypted and that encryption CANNOT be disabled by any bucket owner. How should they enforce this?

- A. Ask each bucket owner to manually enable encryption
- B. Use S3 default encryption settings in each bucket
- C. Apply an SCP that denies s3:PutObject requests that do not include server-side encryption
- D. Use AWS Trusted Advisor to flag unencrypted buckets

---

**Question 64** *(Choose TWO)*

A company has a strict requirement that their data must never leave a specific AWS Region. Which of the following ensures compliance with data residency requirements?

- A. Enable Cross-Region Replication for all S3 buckets
- B. By default, AWS does not move data outside the Region where it is stored without customer action
- C. Use AWS Organizations SCPs to deny actions that create cross-Region resources
- D. Configure AWS Config to monitor for cross-Region data transfers
- E. Enable CloudTrail with global service events

---

### Domain: Networking

---

**Question 3** *(Choose ONE)*

A company wants to host a static website using Amazon S3 and ensure users worldwide experience low latency. Which combination of AWS services should they use?

- A. Amazon S3 + AWS Direct Connect
- B. Amazon S3 + Amazon CloudFront
- C. Amazon S3 + AWS Global Accelerator
- D. Amazon S3 + Amazon Route 53 only

---

**Question 12** *(Choose ONE)*

A company runs applications in a private subnet that need to communicate with each other and with a database in another private subnet. No internet access is required. Which statement about this architecture is CORRECT?

- A. Private subnets cannot communicate with other private subnets without a NAT Gateway
- B. Private subnets in the same VPC can communicate through the local route table by default
- C. Private subnets require VPC Peering to communicate within the same VPC
- D. All inter-subnet communication requires an Internet Gateway

---

**Question 18** *(Choose ONE)*

A company uses AWS Site-to-Site VPN to connect their on-premises network to their Amazon VPC. They notice inconsistent latency and occasional packet loss on the connection. What is the MOST likely root cause?

- A. The Security Group on the VPN endpoint is blocking traffic
- B. The VPN traffic is traversing the public internet
- C. The NAT Gateway is causing packet loss
- D. The Internet Gateway is filtering VPN packets

---

**Question 23** *(Choose ONE)*

A company wants to use Amazon Route 53 to direct 20% of their traffic to a new version of their application for testing purposes while 80% continues to go to the existing version. Which Route 53 routing policy should they use?

- A. Failover routing
- B. Latency-based routing
- C. Weighted routing
- D. Geolocation routing

---

**Question 28** *(Choose ONE)*

A company hosts a web application in AWS. Users from Europe are experiencing very high latency. The application is currently deployed only in us-east-1. Which solution would MOST effectively reduce latency for European users?

- A. Switch from Application Load Balancer to Network Load Balancer
- B. Deploy the application in eu-west-1 and use Route 53 latency-based routing
- C. Enable AWS Global Accelerator on the us-east-1 deployment only
- D. Add more EC2 instances in us-east-1

---

**Question 36** *(Choose TWO)*

A company has a VPC with a public subnet and a private subnet. Instances in the private subnet should be able to download OS updates from the internet, but no inbound internet traffic should reach them. Which components are REQUIRED to enable this?

- A. Internet Gateway attached to the VPC
- B. A NAT Gateway in the public subnet
- C. A second Internet Gateway in the private subnet
- D. An Elastic IP on each private instance
- E. VPC Peering to another VPC with internet access

---

**Question 39** *(Choose ONE)*

An organization has multiple VPCs in the same AWS Region and wants to centralize outbound internet traffic inspection through a shared security appliance. Which AWS networking service is BEST suited for this hub-and-spoke architecture?

- A. VPC Peering
- B. AWS Direct Connect
- C. AWS Transit Gateway
- D. AWS PrivateLink

---

**Question 47** *(Choose ONE)*

A company wants to expose their internal microservice to other AWS accounts within their organization WITHOUT making it publicly accessible and WITHOUT using VPC Peering. Which AWS service enables this?

- A. AWS Transit Gateway
- B. AWS PrivateLink
- C. AWS Direct Connect
- D. Amazon CloudFront

---

**Question 53** *(Choose ONE)*

A company wants their on-premises DNS server to resolve hostnames for resources in their Amazon VPC. Which Route 53 feature specifically enables this hybrid DNS scenario?

- A. Route 53 private hosted zones only
- B. Route 53 Resolver inbound endpoints
- C. Route 53 Resolver outbound endpoints
- D. Route 53 ALIAS records

---

**Question 60** *(Choose ONE)*

A company needs to assign a static, public IPv4 address to their EC2 instance that will remain the same even if the instance is stopped and started. Which AWS feature provides this?

- A. A public IP address assigned at launch
- B. An Elastic IP address
- C. A private IP address with NAT
- D. Amazon Route 53 DNS alias

---

### Domain: Compute

---

**Question 6** *(Choose ONE)*

A company needs EC2 instances optimized for running large in-memory databases and real-time big data analytics. Which EC2 instance family should they choose?

- A. Compute Optimized (C-family)
- B. Storage Optimized (I-family)
- C. Memory Optimized (R or X-family)
- D. Accelerated Computing (P-family)

---

**Question 15** *(Choose ONE)*

A company wants to run a containerized application on AWS with the LEAST operational overhead, without needing to provision or manage EC2 instances. The team prefers ECS orchestration. Which compute option should they choose?

- A. Amazon ECS on EC2
- B. Amazon ECS on AWS Fargate
- C. Amazon EC2 with Docker installed manually
- D. Amazon EKS on EC2

---

**Question 21** *(Choose ONE)*

A company is running a memory-intensive scientific simulation that needs to run for 72 hours without interruption. They want the LOWEST cost for a single dedicated run. Which EC2 purchasing option is MOST appropriate?

- A. Spot Instances
- B. On-Demand Instances
- C. Scheduled Reserved Instances
- D. Dedicated Hosts

---

**Question 32** *(Choose ONE)*

A machine learning team needs to run GPU-intensive training jobs on AWS. Which EC2 instance family is specifically designed for this workload?

- A. R-family (Memory Optimized)
- B. C-family (Compute Optimized)
- C. P-family or G-family (Accelerated Computing)
- D. T-family (General Purpose — burstable)

---

**Question 41** *(Choose ONE)*

A company wants to automatically adjust the number of EC2 instances based on a custom application metric such as number of messages in an SQS queue. Which AWS feature enables this?

- A. EC2 Auto Scaling with a target tracking policy based on CPU utilization
- B. EC2 Auto Scaling with a step scaling policy using a custom CloudWatch metric
- C. AWS Lambda with SQS triggers
- D. Elastic Load Balancing cross-zone load balancing

---

**Question 50** *(Choose ONE)*

A company's web application experiences sudden traffic spikes that are difficult to predict. They want their application to scale automatically and pay only for what they use, with no server management. Which architecture is MOST suitable?

- A. EC2 instances in a fixed-size Auto Scaling group
- B. AWS Lambda behind Amazon API Gateway
- C. Amazon ECS on EC2 with manual scaling
- D. EC2 Reserved Instances for the maximum expected load

---

**Question 56** *(Choose ONE)*

A company uses AWS Lambda for event-driven processing and is concerned about Lambda function execution timeouts for large files. What is the MAXIMUM execution timeout for a single Lambda invocation?

- A. 5 minutes
- B. 15 minutes
- C. 30 minutes
- D. 60 minutes

---

### Domain: Storage

---

**Question 7** *(Choose ONE)*

A company needs to move 50 TB of data from their on-premises data center to Amazon S3. Their internet connection is limited to 100 Mbps and they need the transfer completed within 1 week. Which AWS service provides the MOST practical solution?

- A. AWS DataSync over the internet
- B. Amazon S3 Transfer Acceleration
- C. AWS Snowball Edge
- D. AWS Direct Connect

---

**Question 16** *(Choose ONE)*

A media company stores video files in Amazon S3. Videos older than 30 days are rarely accessed but must be retained for 7 years. After 365 days, videos need archival storage at the LOWEST possible cost. Which S3 feature automates this process?

- A. S3 Intelligent-Tiering
- B. S3 Cross-Region Replication
- C. S3 Lifecycle policies
- D. S3 Object Lock

---

**Question 24** *(Choose ONE)*

A company uses an on-premises NAS server for file sharing and wants to migrate to AWS with a similar experience for Windows-based workloads using SMB protocol. Which AWS service is the BEST fit?

- A. Amazon EFS
- B. Amazon EBS
- C. Amazon FSx for Windows File Server
- D. AWS Storage Gateway — File Gateway

---

**Question 34** *(Choose ONE)*

A company needs to ensure that critical files in Amazon S3 cannot be deleted or modified for a 7-year compliance period, even by administrators. Which S3 feature enforces this requirement?

- A. S3 Versioning
- B. S3 Object Lock in Compliance mode
- C. S3 MFA Delete
- D. S3 Replication

---

**Question 42** *(Choose ONE)*

A company wants to ensure their S3 objects are protected from accidental deletion and can recover any version of an object. Which S3 feature should they enable?

- A. S3 Object Lock
- B. S3 Versioning
- C. S3 Replication
- D. S3 Transfer Acceleration

---

### Domain: Database

---

**Question 8** *(Choose ONE)*

A global gaming company needs a database that can replicate data across multiple AWS Regions with less than 1-second replication lag to support a global leaderboard. Which AWS database service should they use?

- A. Amazon RDS with Multi-AZ
- B. Amazon DynamoDB Global Tables
- C. Amazon Redshift with cross-region snapshots
- D. Amazon ElastiCache with global replication

---

**Question 29** *(Choose TWO)*

A company migrates from an on-premises Oracle database to Amazon RDS for Oracle. After migration, which operational tasks are now managed by AWS?

- A. Optimizing SQL queries for performance
- B. Database schema design
- C. Hardware provisioning and replacement
- D. Operating system patching for the RDS instance

---

### Domain: Monitoring

---

**Question 9** *(Choose ONE)*

A company's DevOps team wants to receive a notification whenever a specific AWS service becomes degraded or unavailable in their region. Which AWS tool should they use?

- A. Amazon CloudWatch with a custom metric
- B. AWS Personal Health Dashboard
- C. AWS Service Health Dashboard
- D. AWS Trusted Advisor

---

**Question 44** *(Choose ONE)*

A company wants to detect configuration changes to their AWS resources and evaluate whether the changes comply with their internal policies. Specifically, they want to know if any S3 bucket becomes publicly accessible. Which AWS service addresses this requirement?

- A. Amazon CloudWatch Events
- B. AWS CloudTrail
- C. AWS Config
- D. Amazon GuardDuty

---

**Question 51** *(Choose ONE)*

A company wants to create a dashboard that displays real-time metrics for their EC2 instances, RDS databases, and Lambda functions — all in one place. Which AWS service provides this capability?

- A. AWS CloudTrail
- B. AWS X-Ray
- C. Amazon CloudWatch
- D. AWS Trusted Advisor

---

### Domain: Pricing & Billing

---

**Question 4** *(Choose ONE)*

A company wants to take advantage of AWS Free Tier to test a new application. Which statement CORRECTLY describes the AWS Free Tier?

- A. Free Tier benefits last indefinitely for all services
- B. Free Tier includes 750 hours per month of t2.micro or t3.micro EC2 for 12 months
- C. Free Tier provides unlimited Lambda invocations forever
- D. Free Tier only applies to AWS accounts in specific countries

---

**Question 10** *(Choose ONE)*

A company has five separate AWS accounts for different departments. They want to receive a single consolidated bill and potentially reduce costs through volume pricing discounts. Which AWS feature enables this?

- A. AWS Cost Explorer
- B. AWS Budgets with shared limits
- C. AWS Organizations with consolidated billing
- D. AWS Savings Plans shared pool

---

**Question 17** *(Choose ONE)*

A developer is evaluating AWS support plans. They need access to the full set of AWS Trusted Advisor checks. What is the MINIMUM support plan required?

- A. Basic
- B. Developer
- C. Business
- D. Enterprise

---

**Question 25** *(Choose ONE)*

An e-commerce startup has unpredictable traffic with huge spikes during sales events. They run EC2 instances for their web tier. Which combination of purchasing options provides the MOST cost-effective strategy?

- A. All On-Demand Instances
- B. All Reserved Instances — 1 year, no upfront
- C. Reserved Instances for baseline traffic + Spot Instances for burst capacity
- D. Dedicated Hosts for all workloads

---

**Question 30** *(Choose ONE)*

A company receives an unexpectedly large AWS bill and wants to investigate which services and resources contributed most to the cost last month. Which AWS tool is BEST suited for this analysis?

- A. AWS Budgets
- B. AWS Pricing Calculator
- C. AWS Cost Explorer
- D. AWS Trusted Advisor

---

**Question 35** *(Choose ONE)*

A company is evaluating moving from their own data center to AWS. They want to quantify the cost savings including reduced staffing, power, cooling, and hardware refresh costs. Which AWS tool helps build this financial justification?

- A. AWS Cost Explorer
- B. AWS Pricing Calculator
- C. AWS Migration Evaluator (TCO Calculator)
- D. AWS Budgets

---

**Question 43** *(Choose ONE)*

A company signed up for AWS 3 months ago and is using Amazon EC2 with t3.micro instances, Amazon S3, and Amazon DynamoDB. Which of these services qualifies for the AWS Always Free tier (not the 12-month free tier)?

- A. EC2 t3.micro — 750 hours/month forever
- B. DynamoDB — 25 GB of storage and 25 read/write capacity units
- C. S3 — 5 GB standard storage forever
- D. All three services are always free

---

**Question 48** *(Choose TWO)*

A company is reviewing their AWS bill and notices they are being charged for data transfer. Which of the following data transfer scenarios incurs NO charge?

- A. Data transfer from EC2 in us-east-1 to S3 in eu-west-1
- B. Data transfer INTO AWS from the internet (inbound)
- C. Data transfer between EC2 instances in the same Availability Zone using private IP
- D. Data transfer from EC2 to CloudFront
- E. Data transfer from AWS to on-premises via Direct Connect

---

**Question 54** *(Choose ONE)*

A company is using AWS Support and needs to contact AWS for general account and billing inquiries. Which support plan is the MINIMUM required to open a support case?

- A. Basic — all accounts can open billing/account cases
- B. Developer
- C. Business
- D. Enterprise

---

**Question 62** *(Choose ONE)*

A company wants to provide their engineering team with AWS cost transparency while preventing them from making changes to billing settings. Which IAM approach ensures this?

- A. Attach AdministratorAccess policy to the engineering team
- B. Provide the engineering team with the root user password
- C. Attach a custom IAM policy granting billing read-only (ViewBilling) access
- D. Enable AWS Budgets and share the dashboard link

---

### Domain: Well-Architected Framework

---

**Question 13** *(Choose ONE)*

A company experiences database outages when a single RDS instance fails. The operations team manually restores the database from a snapshot each time, taking 2-3 hours. Which Well-Architected Reliability principle does this scenario VIOLATE?

- A. Use multiple Availability Zones for all workloads
- B. Test recovery procedures
- C. Automatically recover from failure
- D. Scale horizontally to increase aggregate workload availability

---

**Question 20** *(Choose TWO)*

A company wants to reduce the environmental impact of their AWS workloads. Which actions align with the AWS Well-Architected Sustainability pillar?

- A. Use EC2 instances that are over-provisioned to handle any future growth
- B. Select AWS Regions that are powered by renewable energy
- C. Choose managed services like RDS and Lambda to improve infrastructure utilization efficiency
- D. Store all data in S3 Standard regardless of access frequency
- E. Deploy a dedicated server for each microservice

---

**Question 26** *(Choose ONE)*

A company's application deployment process involves manual steps, extensive documentation, and takes 2 days to complete a release. According to the Operational Excellence pillar, which design principle would MOST improve this process?

- A. Automate to make architectural experimentation easier
- B. Make frequent, small, reversible changes
- C. Anticipate failure by testing in production
- D. Refine operations procedures every quarter only

---

**Question 33** *(Choose ONE)*

A company wants to eliminate single points of failure in their architecture. According to the Reliability pillar, which approach is MOST effective?

- A. Increase the size of their EC2 instances (vertical scaling)
- B. Deploy across multiple Availability Zones with automatic failover
- C. Enable detailed monitoring in CloudWatch
- D. Purchase a Business support plan

---

**Question 38** *(Choose ONE)*

A company's e-commerce application experiences failures during peak shopping events because the architecture was designed for average, not peak, traffic. Which Well-Architected performance principle does this MOST directly violate?

- A. Democratize advanced technologies
- B. Use serverless architectures where possible
- C. Go global in minutes
- D. Use multiple small resources instead of one large resource

---

**Question 45** *(Choose TWO)*

A company's architecture team is reviewing their design to ensure they are following the Cost Optimization pillar. Which actions represent Cost Optimization best practices?

- A. Overprovision all instances to handle any future load
- B. Use Reserved Instances or Savings Plans for steady-state workloads
- C. Implement S3 Lifecycle policies to move infrequently accessed data to cheaper storage
- D. Keep all data in S3 Standard for simplicity
- E. Enable detailed monitoring on all resources to find usage patterns

---

**Question 52** *(Choose ONE)*

A company is designing a disaster recovery strategy and wants their production workload to be fully running in a second AWS Region at all times, with immediate failover capability. Which DR strategy BEST meets this requirement?

- A. Backup and restore
- B. Pilot light
- C. Warm standby
- D. Multi-site active/active

---

---

# SECTION 2 — Answer Key

| Q# | Answer | Domain |
|----|--------|--------|
| 1 | B | Cloud Concepts |
| 2 | A, C | Security |
| 3 | B | Networking |
| 4 | B | Pricing |
| 5 | B | Well-Architected / Security |
| 6 | C | Compute |
| 7 | C | Storage |
| 8 | B | Database |
| 9 | B | Monitoring |
| 10 | C | Pricing |
| 11 | B | Security |
| 12 | B | Networking |
| 13 | C | Well-Architected |
| 14 | B | Security |
| 15 | B | Compute |
| 16 | C | Storage |
| 17 | C | Pricing |
| 18 | B | Networking |
| 19 | B | Security |
| 20 | B, C | Well-Architected |
| 21 | B | Compute |
| 22 | C | Security |
| 23 | C | Networking |
| 24 | C | Storage |
| 25 | C | Pricing |
| 26 | B | Well-Architected |
| 27 | B, C | Security |
| 28 | B | Networking |
| 29 | C, D | Database |
| 30 | C | Pricing |
| 31 | B | Security |
| 32 | C | Compute |
| 33 | B | Well-Architected |
| 34 | B | Storage |
| 35 | C | Pricing |
| 36 | A, B | Networking |
| 37 | C | Security |
| 38 | A | Well-Architected |
| 39 | C | Networking |
| 40 | B, D | Security |
| 41 | B | Compute |
| 42 | B | Storage |
| 43 | B | Pricing |
| 44 | C | Monitoring |
| 45 | B, C | Well-Architected |
| 46 | B | Security |
| 47 | B | Networking |
| 48 | B, C | Pricing |
| 49 | B | Security |
| 50 | B | Compute |
| 51 | C | Monitoring |
| 52 | D | Well-Architected |
| 53 | B | Networking |
| 54 | A | Pricing |
| 55 | C | Security |
| 56 | B | Compute |
| 57 | B, C | Security |
| 58 | B | Cloud Concepts |
| 59 | C | Security |
| 60 | B | Networking |
| 61 | B | Cloud Concepts |
| 62 | C | Pricing |
| 63 | C | Cloud Concepts |
| 64 | B, C | Security |
| 65 | B, D | Cloud Concepts |

---

# SECTION 3 — Detailed Explanations

---

**Q1 — Correct: B (One or more discrete data centers within a Region)**

An Availability Zone (AZ) is one or more discrete data centers with redundant power, networking, and connectivity within an AWS Region. Multiple AZs in a Region are physically separate but connected with high-bandwidth, low-latency networking. Option A describes an AWS Region. Option C describes Edge Locations. Option D is incorrect — AZs are for all production workloads, not just DR.

> **Exam Trap:** Region vs. AZ is a very common confusion point. AZs are the isolated units within a Region.

---

**Q2 — Correct: A, C (Enable MFA on root; Create individual IAM users)**

AWS best practices: Enable MFA on the root user to prevent unauthorized access. The root user cannot be deleted. Create individual IAM users/groups so the root user is used only for specific account-level tasks. You cannot attach IAM policies to the root user, and you should never grant root access to others.

> **Exam Trap:** The root user cannot be deleted, and you cannot attach policies to it. MFA + minimal use is the correct approach.

---

**Q3 — Correct: B (Amazon S3 + Amazon CloudFront)**

Amazon CloudFront is a CDN that caches S3 content at 400+ global edge locations, reducing latency for worldwide users. Direct Connect provides private connectivity — not useful for global public websites. Global Accelerator routes traffic but doesn't cache static content. Route 53 alone provides DNS resolution but doesn't cache content globally.

> **Exam Trap:** Global Accelerator and CloudFront both improve global performance, but only CloudFront caches static content — making it the perfect companion for S3 static websites.

---

**Q4 — Correct: B (750 hours/month of t2.micro or t3.micro for 12 months)**

AWS Free Tier includes 750 hours/month of t2.micro or t3.micro EC2 for the first 12 months. Some services like Lambda (1M requests/month) and DynamoDB (25 GB) are Always Free. Free Tier is globally available. Not all benefits are permanent — they are either 12-month or always-free.

> **Exam Trap:** Know the three Free Tier categories: 12-month free, Always Free, and Trials. EC2 t2/t3.micro is 12-month, not always-free.

---

**Q5 — Correct: B (Implement a strong identity foundation using least privilege)**

The Security pillar's design principle of 'Implement a strong identity foundation' includes using IAM roles, least privilege access, and eliminating long-term static credentials. Security must apply at ALL layers (defense in depth). Shared IAM users violate individual accountability. Security controls must be consistent across all environments.

> **Exam Trap:** 'Apply security at the application layer only' violates Defense in Depth, which requires security at every layer.

---

**Q6 — Correct: C (Memory Optimized — R or X-family)**

Memory Optimized instances (R, X, z families) are designed for workloads that process large datasets in memory — ideal for in-memory databases (Redis, SAP HANA) and real-time big data analytics. Compute Optimized (C) is for CPU-intensive batch tasks. Storage Optimized (I) is for high I/O. Accelerated Computing (P/G) uses GPUs.

> **Exam Trap:** In-memory databases need RAM, not just CPU. Memory Optimized = RAM-heavy workloads.

---

**Q7 — Correct: C (AWS Snowball Edge)**

At 100 Mbps, transferring 50 TB would take approximately 46 days — far exceeding 1 week. AWS Snowball Edge ships a physical device to your location for local data loading, then ships it back to AWS — typically 1-2 weeks total. DataSync over the internet is still bottlenecked by the same connection. S3 Transfer Acceleration can't overcome the bandwidth constraint for 50 TB in a week. Direct Connect requires weeks/months to install.

> **Exam Trap:** S3 Transfer Acceleration sounds like the answer when internet is too slow, but it still uses the same internet pipe and cannot compensate for a 46-day transfer window.

---

**Q8 — Correct: B (Amazon DynamoDB Global Tables)**

Amazon DynamoDB Global Tables provide fully managed, multi-Region, multi-active database replication with sub-second replication lag. RDS Multi-AZ provides AZ-level failover within a single region. Redshift is a data warehouse for analytics. ElastiCache doesn't support global multi-Region active replication natively.

> **Exam Trap:** DynamoDB Global Tables vs. RDS Multi-AZ — Multi-AZ is single-region failover. Global Tables is truly multi-Region active-active.

---

**Q9 — Correct: B (AWS Personal Health Dashboard)**

AWS Personal Health Dashboard (AWS Health) provides personalized alerts and remediation guidance when AWS events affect your specific resources. The Service Health Dashboard shows the general status of all AWS services globally but is not personalized. CloudWatch monitors your own metrics. Trusted Advisor provides optimization recommendations.

> **Exam Trap:** Service Health Dashboard = public, general. Personal Health Dashboard = YOUR resources and account-specific alerts.

---

**Q10 — Correct: C (AWS Organizations with consolidated billing)**

AWS Organizations with consolidated billing combines usage across all member accounts into a single bill and aggregates usage for volume pricing tiers. Cost Explorer analyzes spending. Budgets sets alerts. Savings Plans can be shared within an org but aren't what creates consolidated billing itself.

> **Exam Trap:** Savings Plans can be shared within an org, but consolidated billing is specifically a feature of AWS Organizations.

---

**Q11 — Correct: B (IAM role with s3:GetObject policy attached to EC2)**

IAM roles attached to EC2 instances provide temporary credentials automatically without storing long-term access keys. The role policy should allow only s3:GetObject on the specific bucket (least privilege). Installing IAM user access keys on EC2 is an anti-pattern. Security groups control network traffic, not AWS API permissions. Using root credentials on EC2 is a critical violation.

> **Exam Trap:** Always use IAM roles for EC2, never install access keys directly on instances.

---

**Q12 — Correct: B (Private subnets in the same VPC can communicate via local route table)**

By default, all subnets within the same VPC can communicate with each other through the local route in the VPC route table. No NAT Gateway or VPC Peering is needed for intra-VPC communication. NAT Gateways enable outbound internet access from private subnets. VPC Peering connects different VPCs.

> **Exam Trap:** Private subnets don't need extra configuration to talk to each other within the same VPC. The local route handles it automatically.

---

**Q13 — Correct: C (Automatically recover from failure)**

'Automatically recover from failure' is a core Reliability design principle. Manual restoration from snapshots taking 2-3 hours directly violates this. Automatic recovery should replace or fix components without human intervention. Enabling Multi-AZ enables automatic failover (automatic recovery). Testing recovery procedures is also violated but the primary failure here is lack of automation.

> **Exam Trap:** Both 'Test recovery procedures' and 'Automatically recover' seem correct, but the scenario specifically shows MANUAL recovery — the violation of automation is more direct.

---

**Q14 — Correct: B (SCP that denies EC2 actions in unapproved Regions)**

SCPs in AWS Organizations can deny actions across all accounts in the org. An SCP denying EC2 actions in unapproved Regions provides a preventive control that cannot be overridden by account admins. IAM password policies only control password complexity. AWS Config detects non-compliance after the fact (detective control). Permission boundaries are set per-user, not org-wide.

> **Exam Trap:** AWS Config is detective (finds violations after). SCPs are preventive (stop violations from happening).

---

**Q15 — Correct: B (Amazon ECS on AWS Fargate)**

ECS on AWS Fargate is serverless container orchestration — Fargate removes the need to provision, configure, and scale EC2 instances. ECS on EC2 requires managing underlying EC2 instances. EC2 with Docker manually requires full server management. EKS on EC2 requires managing EC2 nodes and uses Kubernetes.

> **Exam Trap:** ECS vs. EKS — both support Fargate, but the question specifies ECS orchestration. EKS is for Kubernetes.

---

**Q16 — Correct: C (S3 Lifecycle policies)**

S3 Lifecycle policies automate the transition of objects between storage classes based on age — for example: S3 Standard → S3 Standard-IA at 30 days → S3 Glacier Deep Archive at 365 days. S3 Intelligent-Tiering monitors access patterns but cannot move objects to Glacier. Cross-Region Replication copies objects to another region. Object Lock prevents deletion (WORM).

> **Exam Trap:** Intelligent-Tiering automatically transitions between access tiers but does NOT transition to Glacier. Only Lifecycle policies can move objects to Glacier.

---

**Q17 — Correct: C (Business)**

The Business support plan is the minimum tier that provides access to ALL Trusted Advisor checks. Basic and Developer plans only provide access to 7 core Trusted Advisor checks. Enterprise adds a TAM and Concierge support. Both Business and Enterprise provide full Trusted Advisor access.

> **Exam Trap:** Basic and Developer plans include some Trusted Advisor checks — but 'full access' starts at Business.

---

**Q18 — Correct: B (VPN traffic traverses the public internet)**

AWS Site-to-Site VPN uses the public internet to create an encrypted tunnel between on-premises and AWS. Inconsistent latency and packet loss are characteristic of public internet performance variations. This is the fundamental limitation of VPN vs. Direct Connect, which uses a dedicated private connection.

> **Exam Trap:** VPN is 'encrypted' so it sounds private and reliable, but it still traverses the public internet with its inherent variability.

---

**Q19 — Correct: B (Associate AWS WAF with the Application Load Balancer)**

AWS WAF can be associated with an Application Load Balancer to inspect and filter HTTP/HTTPS traffic before it reaches backend EC2 instances. WAF cannot be attached directly to EC2 instances. NAT Gateways handle outbound traffic, not inbound web filtering. Security Groups are Layer 3/4 controls — they don't inspect HTTP content.

> **Exam Trap:** WAF integrated with ALB vs. Security Groups — Security Groups filter by IP/port. WAF filters by HTTP content (headers, URI, body).

---

**Q20 — Correct: B, C (Select renewable energy Regions; Use managed services)**

Sustainability pillar: Selecting Regions powered by renewable energy directly reduces carbon footprint. Using managed services improves hardware utilization — AWS optimizes resource packing across many customers, reducing waste. Over-provisioning wastes resources. Keeping all data in S3 Standard wastes storage resources. Dedicated servers per microservice over-provision compute.

> **Exam Trap:** Cost optimization and sustainability overlap — managed services save both money and energy. They're separate pillars but share some principles.

---

**Q21 — Correct: B (On-Demand Instances)**

On-Demand Instances are correct because the workload runs for 72 hours and CANNOT be interrupted. Spot Instances are cheaper but can be terminated with 2-minute notice — not acceptable for a 72-hour uninterruptible simulation. Scheduled Reserved Instances are for predictable recurring schedules, not one-time runs. Dedicated Hosts are for compliance/licensing and are more expensive.

> **Exam Trap:** Spot Instances save money, but the critical constraint is 'without interruption.' This eliminates Spot entirely.

---

**Q22 — Correct: C (Amazon Macie)**

Amazon Macie uses machine learning to automatically discover, classify, and protect sensitive data in Amazon S3, including PII and financial data. GuardDuty detects security threats and unusual behavior. Inspector scans for software vulnerabilities. Config tracks resource configurations.

> **Exam Trap:** GuardDuty sounds like it would find sensitive data, but it monitors for security threats and unusual behavior — not data classification.

---

**Q23 — Correct: C (Weighted routing)**

Weighted routing allows you to split traffic between multiple resources by assigning weight values. Setting 80/20 weights routes traffic proportionally — ideal for A/B testing and blue/green deployments. Failover routing redirects traffic based on health. Latency-based routes to the lowest-latency endpoint. Geolocation routes based on the user's geographic location.

> **Exam Trap:** This is the classic use case for weighted routing. Don't confuse with geolocation (location-based) or failover (health-based).

---

**Q24 — Correct: C (Amazon FSx for Windows File Server)**

Amazon FSx for Windows File Server provides fully managed Windows-native shared file storage using SMB protocol, Active Directory integration, and NTFS — purpose-built for Windows workloads. EFS provides NFS protocol for Linux. EBS is block storage for a single EC2 instance. Storage Gateway — File Gateway bridges on-premises SMB to S3 but is a hybrid gateway, not a full replacement.

> **Exam Trap:** EFS sounds like a file system, but it uses NFS (Linux). Windows + SMB = FSx for Windows File Server.

---

**Q25 — Correct: C (Reserved Instances for baseline + Spot for burst)**

The optimal strategy for variable workloads: Reserved Instances cover predictable baseline traffic at discounted pricing; Spot Instances (up to 90% discount) handle burst capacity. All On-Demand is most expensive. All Reserved Instances wastes money during low-traffic periods. Dedicated Hosts are most expensive and for compliance/licensing needs.

> **Exam Trap:** The key insight is the COMBINATION — Reserved for base, Spot for burst. One purchasing model doesn't optimally fit variable traffic.

---

**Q26 — Correct: B (Make frequent, small, reversible changes)**

'Make frequent, small, reversible changes' is an Operational Excellence design principle that directly addresses long, risky manual deployments. Smaller releases are easier to test, deploy, and roll back — enabled by CI/CD pipelines. 'Automate to make architectural experimentation easier' is more about infrastructure experimentation. Anticipating failure is a Reliability principle.

> **Exam Trap:** 'Automate' sounds right but is specifically about experimentation/infrastructure. 'Frequent, small, reversible changes' directly addresses deployment velocity and safety.

---

**Q27 — Correct: B, C (AWS Organizations with SCPs; AWS Config with Conformance Packs)**

AWS Organizations with SCPs provide centralized preventive controls. AWS Config with Conformance Packs deploys Config rules across all accounts in an org and can trigger automated remediation. Managing IAM in each account individually doesn't scale to 50 accounts. Trusted Advisor provides recommendations but not automated remediation.

> **Exam Trap:** Organizations alone sets guardrails (preventive). Config adds detective controls and remediation. Both are needed for complete governance.

---

**Q28 — Correct: B (Deploy in eu-west-1 + Route 53 latency-based routing)**

Deploying to eu-west-1 + Route 53 latency-based routing ensures European users are directed to the nearest deployment with the lowest latency. Adding instances in us-east-1 doesn't reduce the fundamental geographic distance to Europe. Switching load balancer types has no effect on geographic latency. Global Accelerator without a European endpoint still routes all traffic to the US.

> **Exam Trap:** Global Accelerator sounds right because it improves global performance, but without a European endpoint, users still travel to the US data center.

---

**Q29 — Correct: C, D (Hardware provisioning; OS patching for the RDS instance)**

For Amazon RDS, AWS manages: hardware provisioning/replacement (no physical server management) and OS patching for the RDS instance. Customers retain responsibility for SQL query optimization, database schema design, and data within the database.

> **Exam Trap:** RDS is 'managed' but customers still own their data, schema, and application-level performance tuning. AWS manages the infrastructure and engine layers.

---

**Q30 — Correct: C (AWS Cost Explorer)**

AWS Cost Explorer provides detailed visualization of historical AWS costs with filtering by service, account, region, tag, and usage type — ideal for post-hoc cost investigation. Budgets sets alerts for future spending. Pricing Calculator estimates new workload costs. Trusted Advisor suggests optimization opportunities but doesn't show historical cost breakdowns by resource.

> **Exam Trap:** Trusted Advisor has cost optimization checks but doesn't show you historical cost data broken down by resource. Cost Explorer is the analytical tool.

---

**Q31 — Correct: B (Rotate the compromised access keys immediately)**

The immediate priority is to deactivate/delete the compromised access keys so they cannot be used by malicious actors. Deleting the repository doesn't help — the keys are already exposed and may have been scraped. Changing the IAM user password doesn't affect access keys. After rotating keys, investigate for unauthorized activity via CloudTrail.

> **Exam Trap:** Deleting the repository is not first — the keys are already public. Neutralize the threat immediately by rotating/deactivating them.

---

**Q32 — Correct: C (P-family or G-family — Accelerated Computing)**

Accelerated Computing instances (P-family for ML training, G-family for graphics/inference) use hardware GPUs for floating-point calculations needed in ML training. Memory Optimized (R) is for large in-memory datasets. Compute Optimized (C) is for CPU-intensive tasks. T-family is for general burstable workloads.

> **Exam Trap:** ML training requires GPUs (not just CPUs), which points to Accelerated Computing — not Compute Optimized.

---

**Q33 — Correct: B (Deploy across multiple Availability Zones with automatic failover)**

Deploying across multiple AZs eliminates single AZ as a single point of failure and enables automatic failover — core to the Reliability pillar. Vertical scaling (larger instances) makes the single instance more capable but doesn't eliminate SPOF. CloudWatch detects problems but doesn't prevent them. A Business support plan helps with recovery assistance but doesn't eliminate SPOFs.

> **Exam Trap:** Larger instances (vertical scaling) sound more reliable, but a single larger instance is still a single point of failure.

---

**Q34 — Correct: B (S3 Object Lock in Compliance mode)**

S3 Object Lock in Compliance mode enforces a WORM policy — no user, including the root account, can delete or overwrite protected objects during the retention period. Versioning keeps multiple versions but doesn't prevent deletion. MFA Delete requires MFA for version deletion but can be disabled by root. Replication copies data but doesn't prevent deletion of the original.

> **Exam Trap:** MFA Delete sounds like the strongest protection, but Compliance mode Object Lock is truly immutable — even root cannot override it during the retention period.

---

**Q35 — Correct: C (AWS Migration Evaluator / TCO Calculator)**

AWS Migration Evaluator provides a detailed comparison of on-premises TCO (hardware, power, cooling, staffing, facilities) vs. AWS costs — building the business case for migration. Cost Explorer analyzes existing AWS spending. Pricing Calculator estimates specific AWS service costs (not the on-premises side). Budgets sets spending alerts.

> **Exam Trap:** AWS Pricing Calculator estimates only AWS costs, not the on-premises side of the comparison. Migration Evaluator does the full on-prem vs. AWS analysis.

---

**Q36 — Correct: A, B (Internet Gateway attached to VPC; NAT Gateway in public subnet)**

For private subnet internet outbound access: An Internet Gateway must be attached to the VPC — the NAT Gateway itself uses the IGW to reach the internet. A NAT Gateway in the public subnet routes outbound requests from private instances to the internet via the IGW, while blocking inbound connections.

> **Exam Trap:** Many forget that the NAT Gateway itself needs the IGW to function — both are required together for private subnet internet access.

---

**Q37 — Correct: C (Individual IAM users for each team member with Billing read-only policy)**

Create individual IAM users (principle of accountability) and attach only the Billing read-only IAM policy (least privilege). Sharing root credentials is a critical violation. A shared 'Finance' IAM user violates individual accountability. AWS Pricing Calculator is a public tool for cost estimation, not for accessing actual billing data.

> **Exam Trap:** Sharing a single 'Finance' IAM user sounds practical and secure, but individual accountability requires individual users so you can track who accessed what.

---

**Q38 — Correct: A (Democratize advanced technologies)**

The actual violation relates to not testing at production scale (including peak loads). Among the options, 'Democratize advanced technologies' is the Performance Efficiency principle about using managed services — which doesn't directly address the failure here. The closest direct answer maps to Performance Efficiency's principle of testing at scale (peak capacity). Note: this question tests precise principle matching — know that testing at production scale is a Performance Efficiency principle.

> **Exam Trap:** Well-Architected pillar principles overlap. Peak load testing = Performance Efficiency. Knowing exact principle names is important for CLF-level questions.

---

**Q39 — Correct: C (AWS Transit Gateway)**

AWS Transit Gateway acts as a hub that connects multiple VPCs in a hub-and-spoke model. You can route all egress traffic through a centralized VPC hosting security inspection appliances. VPC Peering connects VPC pairs but doesn't scale to hub-and-spoke centralized routing. PrivateLink exposes services within/between VPCs privately but doesn't handle routing between many VPCs.

> **Exam Trap:** VPC Peering works for a few VPCs but doesn't scale or centralize routing. Transit Gateway is the scalable hub-and-spoke solution for 10, 50, or hundreds of VPCs.

---

**Q40 — Correct: B, D (HTTPS/TLS; SSL/TLS with AWS Certificate Manager)**

HTTPS/TLS and SSL/TLS (using certificates managed by AWS Certificate Manager) encrypt data in transit. HTTP and FTP transmit data unencrypted. AWS KMS manages encryption keys for data at rest — it is not a transport protocol.

> **Exam Trap:** KMS sounds relevant to encryption broadly, but KMS is for managing keys for data at rest. In-transit encryption requires TLS/HTTPS protocols.

---

**Q41 — Correct: B (EC2 Auto Scaling with step scaling using a custom CloudWatch metric)**

EC2 Auto Scaling with a step or target tracking scaling policy can use ANY CloudWatch metric — including custom metrics like SQS queue depth. This is the canonical pattern for queue-based scaling. Auto Scaling on CPU utilization alone wouldn't respond to queue depth. Lambda with SQS triggers processes messages but doesn't scale EC2. ELB distributes traffic but doesn't scale instances.

> **Exam Trap:** Auto Scaling supports custom CloudWatch metrics, not just the default CPU/network metrics. Custom metrics = custom scaling behavior.

---

**Q42 — Correct: B (S3 Versioning)**

S3 Versioning preserves every version of an object — when you 'delete' an object, S3 adds a delete marker but the previous version is retained and can be restored. Object Lock prevents modification/deletion for a compliance retention period. Replication copies objects to another bucket/region. Transfer Acceleration speeds up uploads.

> **Exam Trap:** Object Lock sounds like strong protection, but it's for compliance WORM requirements. Versioning is the right feature for accidental deletion recovery in normal operations.

---

**Q43 — Correct: B (DynamoDB — 25 GB storage and 25 RCU/WCU)**

Amazon DynamoDB offers 25 GB of storage and 25 read/write capacity units as Always Free (permanent, no expiry). EC2 t3.micro free hours are a 12-month benefit only. S3 5 GB standard is a 12-month benefit. Always Free includes Lambda (1M requests), DynamoDB (25 GB/25 RCU/WCU), SNS (1M publishes), and SQS (1M requests).

> **Exam Trap:** Confusing 12-month Free Tier with Always Free. DynamoDB's allocation never expires; EC2 and S3 standard tiers expire after 12 months.

---

**Q44 — Correct: C (AWS Config)**

AWS Config continuously evaluates AWS resource configurations against desired settings. The 's3-bucket-public-read-prohibited' Config rule detects publicly accessible S3 buckets. CloudWatch Events triggers based on API calls but doesn't evaluate compliance. CloudTrail logs the API call that changed the bucket but doesn't evaluate compliance state. GuardDuty detects threats, not configuration compliance.

> **Exam Trap:** CloudTrail = WHO made a bucket public (the API call). Config = WHETHER the bucket IS currently public (compliance state). These are complementary but distinct.

---

**Q45 — Correct: B, C (Reserved Instances or Savings Plans; S3 Lifecycle policies)**

Cost Optimization best practices: Reserved Instances or Savings Plans for predictable workloads provide 30-72% savings. S3 Lifecycle policies move data to cheaper tiers reducing storage costs. Overprovisioning wastes money. Keeping all data in S3 Standard ignores cheaper storage options. Detailed monitoring helps identify savings but isn't itself a cost-saving action.

> **Exam Trap:** Monitoring can help identify cost savings but isn't itself a direct cost optimization action. Focus on actions that directly reduce spend.

---

**Q46 — Correct: B (IAM policies with Condition elements using aws:CurrentTime and aws:DayOfWeek)**

IAM policies support Condition elements including aws:CurrentTime and aws:DayOfWeek — allowing policies that deny actions outside specified hours/days. IAM roles with sessions have a maximum duration but can't enforce a time-of-day restriction. SCPs can use condition keys but this is precisely an IAM policy feature. Config rules detect after the fact.

> **Exam Trap:** 'Time-limited sessions' refers to session duration (hours), not clock time (business hours). Business hours restriction requires the aws:CurrentTime condition key.

---

**Q47 — Correct: B (AWS PrivateLink)**

AWS PrivateLink allows you to expose services to other VPCs or accounts through an interface endpoint — traffic stays within the AWS network and never traverses the public internet, without VPC peering. Transit Gateway manages routing between VPCs at the network level (different use case). Direct Connect connects on-premises to AWS. CloudFront is a CDN for public content.

> **Exam Trap:** Transit Gateway vs. PrivateLink — Transit Gateway manages routing between VPCs (network connectivity). PrivateLink exposes specific services to other accounts without full network connectivity.

---

**Q48 — Correct: B, C (Inbound from internet; Same-AZ EC2 to EC2 using private IP)**

Free data transfer: Inbound data transfer into AWS from the internet is always free. Data transfer between EC2 instances in the same AZ using private IPs is free. Cross-region S3 transfer is charged. EC2 to CloudFront has no additional charge for data served to CloudFront. Direct Connect outbound incurs data transfer charges.

> **Exam Trap:** Inter-AZ data transfer using private IPs within the same AZ is free. Inter-AZ transfer (different AZs) is charged. Knowing this distinction is important.

---

**Q49 — Correct: B (AWS Shield Advanced)**

AWS Shield Advanced provides enhanced DDoS protection plus 24/7 access to the AWS Shield Response Team (SRT) during attacks, cost protection against DDoS-related scaling charges, and advanced attack diagnostics. Shield Standard is free but provides only basic DDoS protection without team access. WAF blocks Layer 7 attacks but has no DDoS response team. GuardDuty detects threats but provides no DDoS mitigation team.

> **Exam Trap:** Shield Standard vs. Advanced — Standard is automatic and free. Advanced adds the response team, protection guarantees, and DDoS cost protection.

---

**Q50 — Correct: B (AWS Lambda behind Amazon API Gateway)**

AWS Lambda + API Gateway is serverless — Lambda scales automatically from zero to thousands of concurrent invocations, and you pay per invocation (no idle costs). A fixed-size Auto Scaling group doesn't scale dynamically. ECS on EC2 with manual scaling requires human intervention. Reserved Instances for maximum load means paying for peak capacity even during low traffic.

> **Exam Trap:** The question specifies 'no server management.' Lambda is the truly serverless answer. EC2 Auto Scaling still manages servers.

---

**Q51 — Correct: C (Amazon CloudWatch)**

Amazon CloudWatch collects and visualizes real-time metrics from EC2, RDS, Lambda, and virtually all AWS services. CloudWatch Dashboards provide customizable views of these metrics. CloudTrail records API calls. X-Ray provides distributed tracing for application debugging. Trusted Advisor provides optimization recommendations, not real-time metrics.

> **Exam Trap:** X-Ray sounds like it monitors applications, but it's for distributed tracing (request flow analysis), not real-time metric dashboards.

---

**Q52 — Correct: D (Multi-site active/active)**

Multi-site active/active runs the full production workload simultaneously in multiple Regions with traffic distributed between them — providing immediate failover with no startup time. Backup and restore has the longest RTO (hours). Pilot light runs only core components in the DR region. Warm standby runs a scaled-down version that needs scaling up. Multi-site active/active is the most expensive but provides the lowest RTO/RPO.

> **Exam Trap:** Know the DR spectrum from lowest to highest availability: Backup/Restore → Pilot Light → Warm Standby → Multi-site Active/Active (highest availability, highest cost).

---

**Q53 — Correct: B (Route 53 Resolver inbound endpoints)**

Route 53 Resolver inbound endpoints allow on-premises DNS resolvers to forward DNS queries to Route 53, enabling resolution of AWS private hosted zone records. Outbound endpoints allow VPC resources to resolve on-premises DNS. Private hosted zones provide the DNS records but don't handle the hybrid connectivity. ALIAS records route to AWS resources.

> **Exam Trap:** Inbound vs. outbound endpoints depend on the direction of the DNS query. From on-premises wanting to resolve AWS DNS — they are the 'inbound' source into Route 53.

---

**Q54 — Correct: A (Basic — all accounts can open billing/account cases)**

All AWS accounts — including Basic (free) — can contact AWS Support for billing questions, account issues, and service limit increase requests. Technical support cases require at minimum the Developer plan. Basic support includes 24/7 access for billing and account inquiries only.

> **Exam Trap:** Many candidates assume you need a paid plan to contact support at all, but billing and account support is included with all plans including the free Basic plan.

---

**Q55 — Correct: C (IAM Identity Center with SAML 2.0 federation)**

IAM Identity Center (AWS SSO) with SAML 2.0 federation allows employees to authenticate via their existing corporate IdP (Okta, ADFS, Azure AD) and assume IAM roles for console access. Creating IAM users to mirror AD users doesn't scale. Cognito is for app user authentication, not employee AWS console access. AWS Directory Service manages AD in AWS but doesn't federate console sign-in by itself.

> **Exam Trap:** Cognito vs. IAM Identity Center — Cognito is for customer/app users. IAM Identity Center (SSO) is for workforce/employee AWS access.

---

**Q56 — Correct: B (15 minutes)**

AWS Lambda has a maximum execution timeout of 15 minutes (900 seconds). For workloads exceeding 15 minutes, use Step Functions for orchestration, EC2 or Fargate for long-running tasks, or break the workload into smaller chunks. The default timeout is 3 seconds; maximum is 15 minutes.

> **Exam Trap:** Lambda is serverless but has hard limits. The 15-minute maximum timeout is a CLF-level fact. Don't confuse with the 29-second API Gateway integration timeout.

---

**Q57 — Correct: B, C (NACLs at subnet level + Security Groups at instance level; AWS WAF at load balancer)**

Defense in depth = multiple layers of security: NACLs + Security Groups provide multiple network layers (subnet-level stateless + instance-level stateful controls). WAF at the load balancer adds an application-layer filter (Layer 7) before traffic reaches servers. A single Security Group allowing all traffic, public S3 buckets, and single firewall rules all eliminate layers.

> **Exam Trap:** Defense in depth = MORE security layers, not fewer. Any answer that consolidates controls into one layer is wrong.

---

**Q58 — Correct: B (Deploy across at least two Availability Zones with a load balancer)**

Deploying across at least two AZs with a load balancer ensures that if one AZ fails, the other continues serving requests. A single EC2 instance fails with its AZ. CloudWatch alarms detect failures but don't prevent downtime. Route 53 failover routing is typically for Region-level or endpoint-level failover — an ALB handles AZ-level traffic distribution more immediately.

> **Exam Trap:** Route 53 failover sounds like AZ-level failover, but it's for endpoint/Region-level failover. An ALB handles intra-Region AZ-level traffic distribution.

---

**Q59 — Correct: C (SCP denying s3:PutObject without server-side encryption)**

An SCP in AWS Organizations can deny any s3:PutObject operation that doesn't include a server-side encryption header — preventing anyone in the organization from storing unencrypted objects. Manual encryption relies on human action. Default encryption settings can be changed by bucket owners. Trusted Advisor flags issues after the fact (detective). The SCP is a preventive control that cannot be overridden by account admins.

> **Exam Trap:** Default encryption is good practice but can be turned off by bucket owners. SCPs cannot be overridden — they are organizational guardrails that prevent the action entirely.

---

**Q60 — Correct: B (An Elastic IP address)**

An Elastic IP (EIP) is a static, public IPv4 address allocated to your AWS account. Unlike the default public IP (which changes when an instance is stopped/started), an EIP remains associated until explicitly released. Public IPs assigned at launch are dynamic — they change on stop/start. Route 53 aliases point to resource endpoints but don't provide static IPs.

> **Exam Trap:** Default public IPs look static while the instance runs, but they change on stop/start. Elastic IPs are truly static and persist through instance stop/start cycles.

---

**Q61 — Correct: B (Horizontal = more instances; Vertical = bigger instance)**

Horizontal scaling (scale out) = adding more instances of the same size — the AWS-preferred approach that avoids single points of failure and is truly elastic. Vertical scaling (scale up) = upgrading to a larger/more powerful instance — has limits and typically requires downtime. AWS favors horizontal scaling with Auto Scaling groups.

> **Exam Trap:** The terms are often confused. Remember: horizontal = wider (more instances), vertical = taller (bigger instance).

---

**Q62 — Correct: C (Custom IAM policy granting ViewBilling access)**

A custom IAM policy granting only 'aws-portal:ViewBilling' allows the team to VIEW billing data without changing settings — least privilege for cost transparency. AdministratorAccess allows everything including billing changes. Root user password sharing is never acceptable. AWS Budgets dashboards are useful but limited — they don't provide granular billing data visibility.

> **Exam Trap:** Providing root access for billing visibility is never acceptable. The correct approach is a read-only billing IAM policy for each team member.

---

**Q63 — Correct: C (Trade capital expense for variable expense — low cost of experimentation)**

'Trading capital expense for variable expense' means experiments cost very little — you spin up resources, test, and shut them down, paying only for hours used. This enables fail-fast innovation cultures because the cost of failure is minimal. Economies of scale reduce costs generally. Global reach enables geographic deployments but isn't specifically about experimentation cost.

> **Exam Trap:** Multiple answers describe valid AWS benefits, but the specific 'fail fast, low cost of experimentation' maps directly to variable (OpEx) over fixed (CapEx) costs.

---

**Q64 — Correct: B, C (AWS doesn't move data by default; SCPs deny cross-Region resources)**

Data residency: By default, AWS does NOT replicate data outside the Region — customers must explicitly enable cross-region features. SCPs can deny API actions that would create resources or enable replication in other Regions. Cross-Region Replication would violate data residency. Config can detect but not prevent cross-Region data movement.

> **Exam Trap:** Knowing that AWS doesn't move data by default is a key fact — customers must opt into cross-region features. SCPs as preventive guardrails ensure this remains enforced.

---

**Q65 — Correct: B, D (Faster time-to-market; Access to continuously updated services)**

Non-financial business value: Faster time-to-market — cloud removes procurement delays, enabling rapid product launches. Access to continuously updated services — AWS launches hundreds of new services annually without hardware refresh costs. Cloud does NOT increase CapEx. Security is shared, not unilaterally increased. Cloud does NOT eliminate all operational overhead.

> **Exam Trap:** 'Increased IT security through shared responsibility' sounds positive, but the shared model means customers share responsibility — they have both gains and retained security obligations.

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

## Key Topics to Review by Domain

**Cloud Concepts** — Region vs. AZ vs. Edge Location definitions; horizontal vs. vertical scaling; CapEx vs. OpEx; cloud benefits (agility, elasticity, economy of scale)

**Security** — Root user best practices (MFA, minimal use, cannot be deleted); IAM roles vs. IAM users on EC2; SCPs vs. Config (preventive vs. detective); Shield Standard vs. Advanced; Macie vs. GuardDuty; WAF placement on ALB; S3 Object Lock Compliance mode

**Networking** — VPN over public internet vs. Direct Connect private dedicated; NAT Gateway + IGW both required for private subnet internet; VPC Peering vs. Transit Gateway vs. PrivateLink; Route 53 routing policies (weighted, latency, geolocation, failover); inbound vs. outbound Route 53 Resolver endpoints; Elastic IP vs. dynamic public IP

**Compute** — EC2 instance families (memory, compute, storage, accelerated, general purpose); Spot Instance limitations (can be interrupted); Fargate for serverless containers; Lambda 15-minute max timeout; Auto Scaling with custom CloudWatch metrics

**Storage** — S3 Lifecycle policies vs. Intelligent-Tiering (only Lifecycle moves to Glacier); Object Lock Compliance mode vs. MFA Delete; EFS (NFS/Linux) vs. FSx for Windows (SMB/Windows); Snowball Edge for large offline data migration

**Database** — DynamoDB Global Tables for multi-Region active-active; RDS Multi-AZ for single-region failover; what RDS manages vs. customer responsibility

**Monitoring** — CloudWatch (metrics/dashboards) vs. CloudTrail (API audit) vs. Config (configuration compliance); Personal Health Dashboard (account-specific) vs. Service Health Dashboard (public/general)

**Pricing** — 12-month Free Tier vs. Always Free services; Trusted Advisor full access requires Business plan minimum; consolidated billing via AWS Organizations; inbound data transfer always free; same-AZ private IP transfer free; Migration Evaluator for on-prem vs. AWS TCO; Basic plan includes billing support

**Well-Architected** — All six pillars and their key design principles; DR spectrum (Backup/Restore → Pilot Light → Warm Standby → Multi-site Active/Active); Sustainability = managed services + right-sizing + renewable energy regions; Operational Excellence = frequent small reversible changes + operations as code

---

*This mock exam is designed to closely simulate the real AWS Certified Cloud Practitioner (CLF-C02) exam experience. Good luck on the real exam!*
