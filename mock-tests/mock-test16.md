# AWS Certified Cloud Practitioner (CLF-C02) — Full Mock Exam · Set 2

> **65 Questions · 90 Minutes · Passing Score: 70%**
> All-new question bank | Scenario-based | Security | Networking | Billing | Well-Architected

---

## Instructions

- This exam contains **65 questions** — all different from Set 1.
- You have **90 minutes** to complete it.
- Questions are **single-answer** or **multi-answer** (clearly marked).
- For multi-answer questions, select **only** the number of answers specified.
- The real AWS CLF-C02 passing score is approximately **70%**.
- Scoring **75%+** on this mock exam indicates strong readiness for the real certification.

---

# SECTION 1 — Questions

---

### Question 1 *(Choose ONE)*

A company is deploying a new application on AWS and wants to ensure it can handle sudden spikes in traffic without manual intervention. Which cloud characteristic BEST supports this requirement?

- A. High availability
- B. Fault tolerance
- C. Elasticity
- D. Durability

---

### Question 2 *(Choose ONE)*

A healthcare company must ensure that patient data stored in AWS is encrypted and that they retain full control of the encryption keys. Which AWS service allows customers to create and manage their own encryption keys?

- A. AWS Certificate Manager
- B. AWS Secrets Manager
- C. AWS KMS
- D. AWS CloudHSM

---

### Question 3 *(Choose ONE)*

A startup needs to process incoming customer orders. If the order processing service goes down temporarily, orders must NOT be lost. Which AWS service should they use to decouple order submission from order processing?

- A. Amazon SNS
- B. Amazon SQS
- C. AWS Step Functions
- D. Amazon Kinesis

---

### Question 4 *(Choose THREE)*

Which of the following are pillars of the AWS Well-Architected Framework?

- A. Operational Excellence
- B. Agility
- C. Cost Optimization
- D. Scalability
- E. Reliability

---

### Question 5 *(Choose ONE)*

A company's web servers in a public subnet need to communicate with a database in a private subnet. The database servers must NOT be accessible from the internet. What component allows this architecture?

- A. Internet Gateway
- B. NAT Gateway
- C. VPC Peering
- D. Security Groups and routing tables

---

### Question 6 *(Choose ONE)*

An organization has 10 AWS accounts. They want a single monthly invoice and the ability to share Reserved Instance discounts across all accounts. Which feature enables this?

- A. AWS Cost Explorer
- B. Consolidated Billing via AWS Organizations
- C. AWS Budgets
- D. AWS Pricing Calculator

---

### Question 7 *(Choose ONE)*

Under the AWS Shared Responsibility Model, which of the following is AWS responsible for?

- A. Configuring IAM user permissions
- B. Patching the guest operating system on EC2
- C. Physical security of data center facilities
- D. Enabling CloudTrail in customer accounts

---

### Question 8 *(Choose ONE)*

A media company needs to deliver 4K video content to users in Asia, Europe, and the Americas with minimal buffering. Which AWS service should they use?

- A. Amazon S3 Transfer Acceleration
- B. AWS Global Accelerator
- C. Amazon CloudFront
- D. Amazon Route 53 with latency routing

---

### Question 9 *(Choose ONE)*

A company wants to run machine learning inference workloads that require high-performance GPU processing. Which EC2 instance family should they choose?

- A. C-family (Compute Optimized)
- B. R-family (Memory Optimized)
- C. P-family or G-family (GPU instances)
- D. I-family (Storage Optimized)

---

### Question 10 *(Choose ONE)*

Which AWS service provides DNS failover — automatically routing users to a healthy endpoint when the primary endpoint becomes unhealthy?

- A. AWS CloudFront
- B. Elastic Load Balancer
- C. Amazon Route 53
- D. AWS Global Accelerator

---

### Question 11 *(Choose TWO)*

A company wants to automatically take action whenever an unauthorized API call is detected in their AWS account. Which combination of services enables this?

- A. AWS CloudTrail
- B. Amazon CloudWatch
- C. Amazon Inspector
- D. AWS Config
- E. Amazon GuardDuty

---

### Question 12 *(Choose ONE)*

Which S3 storage class is designed for data that is accessed less than once a month but requires millisecond retrieval when accessed, and is stored in a single Availability Zone to reduce cost?

- A. S3 Standard-IA
- B. S3 Glacier Instant Retrieval
- C. S3 One Zone-IA
- D. S3 Intelligent-Tiering

---

### Question 13 *(Choose ONE)*

A financial institution needs to maintain compliance by ensuring that no one — not even AWS — can access the encryption keys used to protect their data. Which service meets this requirement?

- A. AWS KMS with customer-managed keys
- B. AWS CloudHSM
- C. AWS Secrets Manager
- D. S3 server-side encryption (SSE-S3)

---

### Question 14 *(Choose TWO)*

An e-commerce platform experiences 10x normal traffic every Black Friday. The company wants automatic scaling during peak hours and minimal cost the rest of the year. Which combination is MOST cost-effective?

- A. EC2 Auto Scaling
- B. Dedicated Hosts for all instances
- C. On-Demand Instances during peaks
- D. Reserved Instances for baseline traffic
- E. Spot Instances for the base workload

---

### Question 15 *(Choose ONE)*

Which AWS service enables a company to discover, classify, and protect sensitive data such as personally identifiable information (PII) stored in Amazon S3?

- A. Amazon GuardDuty
- B. Amazon Inspector
- C. Amazon Macie
- D. AWS Security Hub

---

### Question 16 *(Choose ONE)*

A company wants to give a third-party auditing firm read-only access to their AWS account resources without creating long-term credentials. What is the MOST secure approach?

- A. Create an IAM user with read-only permissions and share the password
- B. Create an IAM Role with read-only permissions and allow the auditor to assume it
- C. Share the root account credentials temporarily
- D. Create access keys and email them securely

---

### Question 17 *(Choose ONE)*

Which Well-Architected Framework pillar focuses on the ability to support development and run workloads effectively, gain insight into operations, and continuously improve processes?

- A. Reliability
- B. Performance Efficiency
- C. Operational Excellence
- D. Security

---

### Question 18 *(Choose ONE)*

A company needs to migrate 50 TB of data from their on-premises data center to Amazon S3. Their internet connection is slow and unreliable. Which AWS service should they use?

- A. AWS DataSync
- B. AWS Snowball Edge
- C. AWS Direct Connect
- D. S3 Transfer Acceleration

---

### Question 19 *(Choose ONE)*

Which of the following statements about Security Groups is CORRECT?

- A. Security Groups can explicitly DENY traffic
- B. Security Groups are stateless
- C. Security Groups evaluate all rules before allowing or denying traffic
- D. Security Groups are applied at the subnet level

---

### Question 20 *(Choose ONE)*

A company running a web application wants to protect against SQL injection attacks and common web exploits without deploying additional hardware. Which AWS service provides this?

- A. AWS Shield Standard
- B. AWS WAF
- C. Amazon GuardDuty
- D. Amazon Inspector

---

### Question 21 *(Choose ONE)*

Which pricing model allows customers to commit to a consistent amount of compute usage (measured in $/hour) for 1 or 3 years and receive a discount of up to 66%, with flexibility to change instance types?

- A. Standard Reserved Instances
- B. Spot Instances
- C. Compute Savings Plans
- D. Convertible Reserved Instances

---

### Question 22 *(Choose ONE)*

A company's application runs on EC2 instances in us-east-1. They want to improve read performance for their RDS MySQL database. Users are predominantly reading data. Which feature should they implement?

- A. Enable RDS Multi-AZ
- B. Create RDS Read Replicas
- C. Enable automated backups
- D. Migrate to RDS Proxy

---

### Question 23 *(Choose ONE)*

Which AWS service allows you to run containerized applications in a fully managed Kubernetes environment without managing the control plane?

- A. Amazon ECS
- B. AWS Fargate
- C. Amazon EKS
- D. AWS Elastic Beanstalk

---

### Question 24 *(Choose TWO)*

Which of the following are benefits of using AWS Managed Services over self-managed deployments?

- A. AWS manages patching and infrastructure maintenance
- B. Customers get full access to the underlying operating system
- C. Reduced operational burden on the customer
- D. Lower storage costs compared to any self-managed option
- E. Customers control all software stack layers

---

### Question 25 *(Choose ONE)*

A global company wants to ensure that users in different countries are routed to the nearest AWS Region to comply with data residency laws. Which Route 53 routing policy should they use?

- A. Latency-based routing
- B. Weighted routing
- C. Geolocation routing
- D. Failover routing

---

### Question 26 *(Choose ONE)*

A company is running batch analytics workloads that are flexible and can be interrupted. They want the LOWEST possible compute cost. Which EC2 purchasing option is MOST appropriate?

- A. On-Demand
- B. Reserved Instances (1-year)
- C. Spot Instances
- D. Dedicated Hosts

---

### Question 27 *(Choose ONE)*

Which AWS service provides a fully managed data warehouse solution optimized for analytics and complex SQL queries across petabyte-scale datasets?

- A. Amazon RDS
- B. Amazon DynamoDB
- C. Amazon Redshift
- D. Amazon Aurora

---

### Question 28 *(Choose TWO)*

Which of the following actions should a company take to follow AWS security best practices for their root account?

- A. Enable MFA on the root account
- B. Use the root account for all administrative actions
- C. Create IAM users for daily operations
- D. Generate root account access keys for programmatic access
- E. Store the root password in AWS Secrets Manager

---

### Question 29 *(Choose ONE)*

A company wants to monitor the performance of their Lambda functions and set alarms when error rates exceed a threshold. Which service provides this capability?

- A. AWS CloudTrail
- B. AWS X-Ray
- C. Amazon CloudWatch
- D. AWS Config

---

### Question 30 *(Choose ONE)*

Which of the following BEST describes "high availability" in AWS cloud architecture?

- A. The system can handle any amount of traffic without degradation
- B. The system continues to operate with minimal downtime despite component failures
- C. The system automatically reduces costs during low-usage periods
- D. The system backs up data to multiple geographic regions

---

### Question 31 *(Choose ONE)*

A company is storing sensitive customer data in S3. They want to ensure data is encrypted in transit between clients and S3. Which mechanism achieves this?

- A. Enable S3 server-side encryption (SSE-S3)
- B. Use HTTPS (TLS) for all S3 requests
- C. Enable S3 Versioning
- D. Apply an S3 bucket policy restricting public access

---

### Question 32 *(Choose ONE)*

A company needs to automatically convert audio files uploaded to S3 into text transcriptions. Which AWS AI service provides this capability?

- A. Amazon Comprehend
- B. Amazon Polly
- C. Amazon Transcribe
- D. Amazon Textract

---

### Question 33 *(Choose ONE)*

Which AWS Support plan provides access to a dedicated Technical Account Manager (TAM) and AWS Concierge Support for billing and account questions?

- A. Developer
- B. Business
- C. Enterprise On-Ramp
- D. Enterprise

---

### Question 34 *(Choose ONE)*

A company's application in a private subnet needs to call AWS APIs (such as DynamoDB) without routing traffic through the internet. Which AWS feature enables this?

- A. NAT Gateway
- B. VPC Endpoint
- C. Internet Gateway
- D. AWS Direct Connect

---

### Question 35 *(Choose ONE)*

Which of the following is a key difference between Amazon RDS and Amazon DynamoDB?

- A. RDS supports both SQL and NoSQL; DynamoDB supports SQL only
- B. RDS is a relational database; DynamoDB is a key-value and document NoSQL database
- C. DynamoDB requires managing the underlying EC2 instances
- D. RDS automatically scales to millions of requests per second

---

### Question 36 *(Choose ONE)*

A company wants to track changes to their AWS resource configurations over time and receive alerts when configurations deviate from desired settings. Which service should they use?

- A. Amazon CloudWatch
- B. AWS CloudTrail
- C. AWS Config
- D. Amazon Inspector

---

### Question 37 *(Choose ONE)*

Which Well-Architected Framework pillar includes design principles such as "stop guessing capacity needs" and "use serverless architectures"?

- A. Cost Optimization
- B. Reliability
- C. Operational Excellence
- D. Performance Efficiency

---

### Question 38 *(Choose ONE)*

A company wants the LEAST expensive way to host a static website with global availability and no server management. Which combination should they use?

- A. EC2 + Elastic Load Balancer
- B. S3 static website hosting + CloudFront
- C. Elastic Beanstalk + RDS
- D. AWS Lightsail

---

### Question 39 *(Choose ONE)*

An IAM policy has an explicit DENY for s3:DeleteObject. The same user has another policy that explicitly ALLOWs s3:DeleteObject. What is the effective permission?

- A. Allow — the ALLOW overrides the DENY
- B. Deny — explicit DENY always overrides ALLOW
- C. The most recently applied policy wins
- D. It depends on which policy is attached to the user directly vs group

---

### Question 40 *(Choose ONE)*

A startup wants to send real-time notifications to millions of mobile devices when new content is published. Which AWS service is MOST suitable?

- A. Amazon SQS
- B. Amazon SNS
- C. Amazon SES
- D. Amazon EventBridge

---

### Question 41 *(Choose TWO)*

Which of the following are advantages of cloud computing over traditional on-premises infrastructure?

- A. Eliminate all security responsibilities
- B. Trade upfront capital expense for variable operating expense
- C. Benefit from massive economies of scale
- D. Guarantee zero latency for all applications
- E. Unlimited control over physical hardware

---

### Question 42 *(Choose ONE)*

A company has workloads spread across 15 VPCs in the same Region. They need all VPCs to communicate with each other and with their on-premises network. What is the MOST operationally efficient solution?

- A. Create VPC Peering connections between all 15 VPCs
- B. Use AWS Transit Gateway
- C. Deploy a VPN for each VPC
- D. Use VPC Endpoints for inter-VPC communication

---

### Question 43 *(Choose ONE)*

Which service allows customers to run AWS infrastructure and services on-premises, delivering a consistent hybrid cloud experience?

- A. AWS Direct Connect
- B. AWS VPN
- C. AWS Outposts
- D. AWS Local Zones

---

### Question 44 *(Choose ONE)*

A company wants to improve the resilience of their architecture by copying their S3 data to a bucket in a different AWS Region automatically. Which S3 feature enables this?

- A. S3 Versioning
- B. S3 Lifecycle Policies
- C. S3 Cross-Region Replication
- D. S3 Object Lock

---

### Question 45 *(Choose ONE)*

Which AWS service provides Infrastructure as Code (IaC), allowing teams to define and provision AWS resources using JSON or YAML templates?

- A. AWS Elastic Beanstalk
- B. AWS CloudFormation
- C. AWS OpsWorks
- D. AWS Systems Manager

---

### Question 46 *(Choose TWO)*

A company has compliance requirements to retain access logs for 3 years. After 90 days, logs are rarely accessed. Which S3 configuration is MOST cost-effective?

- A. Store in S3 Standard for 90 days, then transition to S3 Glacier
- B. Store all logs in S3 Standard permanently
- C. Use S3 Lifecycle Policy to automate the transition
- D. Delete logs after 90 days
- E. Store all logs in S3 Glacier from day 1

---

### Question 47 *(Choose ONE)*

Which of the following statements about AWS Lambda is CORRECT?

- A. Lambda functions can run for a maximum of 24 hours
- B. Lambda requires you to provision and manage EC2 instances
- C. Lambda automatically scales by running code in response to each trigger
- D. Lambda only supports Python and Node.js

---

### Question 48 *(Choose ONE)*

A company needs a service to analyze customer feedback text for sentiment (positive, negative, neutral) and extract key entities. Which AWS AI service should they use?

- A. Amazon Rekognition
- B. Amazon Transcribe
- C. Amazon Comprehend
- D. Amazon Lex

---

### Question 49 *(Choose ONE)*

Which of the following BEST describes the concept of "fault tolerance"?

- A. A system that automatically scales to meet demand
- B. A system that continues operating correctly even when one or more components fail
- C. A system that recovers data from backups after a failure
- D. A system that distributes load across multiple servers

---

### Question 50 *(Choose ONE)*

A company is using AWS and wants to receive personalized recommendations on how to optimize costs, improve security, increase performance, and achieve fault tolerance. Which service provides these recommendations?

- A. AWS Config
- B. Amazon CloudWatch
- C. AWS Trusted Advisor
- D. AWS Well-Architected Tool

---

### Question 51 *(Choose ONE)*

A company deployed an application in a single AWS Region. They want to implement a disaster recovery strategy that keeps a minimal version of their environment running in a second Region to reduce recovery time. Which DR strategy does this describe?

- A. Backup and restore
- B. Pilot light
- C. Warm standby
- D. Multi-site active-active

---

### Question 52 *(Choose ONE)*

Which feature of AWS Organizations allows administrators to restrict what services and actions can be used in member accounts, even if an IAM policy would otherwise allow it?

- A. Permission boundaries
- B. Resource-based policies
- C. Service Control Policies (SCPs)
- D. Identity-based policies

---

### Question 53 *(Choose ONE)*

A company's development team wants to quickly deploy web applications without managing servers, and needs built-in support for auto-scaling and load balancing. Which service provides the LEAST administrative overhead?

- A. Amazon EC2 with manual configuration
- B. AWS Fargate
- C. AWS Elastic Beanstalk
- D. Amazon EKS

---

### Question 54 *(Choose ONE)*

Which of the following is a characteristic of Amazon EFS (Elastic File System)?

- A. EFS is block storage that attaches to a single EC2 instance
- B. EFS is object storage accessible via REST API
- C. EFS is a shared file system mountable by multiple EC2 instances across multiple AZs
- D. EFS is used primarily for archival storage

---

### Question 55 *(Choose TWO)*

A company needs to ensure that their application can withstand the failure of an entire AWS Availability Zone without service interruption. Which architecture approach achieves this?

- A. Deploy resources in at least two AZs
- B. Use an Elastic Load Balancer to distribute traffic
- C. Enable S3 Versioning
- D. Use Reserved Instances
- E. Deploy all resources in a single large EC2 instance

---

### Question 56 *(Choose ONE)*

Which AWS service provides a fully managed, serverless, pay-per-query service for running SQL queries directly on data stored in Amazon S3 without loading it into a database?

- A. Amazon RDS
- B. Amazon Redshift
- C. Amazon Athena
- D. AWS Glue

---

### Question 57 *(Choose ONE)*

A company wants to build a chatbot for their customer service portal that can understand natural language and engage in multi-turn conversations. Which AWS service should they use?

- A. Amazon Comprehend
- B. Amazon Polly
- C. Amazon Lex
- D. Amazon Transcribe

---

### Question 58 *(Choose ONE)*

Which AWS service automatically evaluates your AWS resources against best practices and provides a compliance dashboard?

- A. Amazon Inspector
- B. AWS Config
- C. AWS Trusted Advisor
- D. Amazon GuardDuty

---

### Question 59 *(Choose ONE)*

A company processes sensitive financial transactions. They need network-level protection at the subnet boundary that can DENY specific IP addresses. What should they use?

- A. Security Groups
- B. IAM Policies
- C. Network Access Control Lists (NACLs)
- D. AWS WAF

---

### Question 60 *(Choose ONE)*

Which of the following is TRUE about the AWS Free Tier for Amazon EC2?

- A. It includes 750 hours/month of any EC2 instance type
- B. It provides unlimited t2.micro usage permanently
- C. It includes 750 hours/month of t2.micro or t3.micro (Linux) for 12 months
- D. It covers all EC2 services including data transfer globally

---

### Question 61 *(Choose ONE)*

A company wants to implement a solution that automatically identifies and redacts PII from documents uploaded to S3. Which combination of services is MOST appropriate?

- A. Amazon Macie + AWS Lambda
- B. Amazon Textract + Amazon Comprehend + AWS Lambda
- C. Amazon Rekognition + AWS Glue
- D. Amazon Transcribe + Amazon Translate

---

### Question 62 *(Choose ONE)*

Which of the following CORRECTLY describes the difference between horizontal scaling and vertical scaling?

- A. Horizontal scaling adds more CPU/RAM to an existing instance; vertical scaling adds more instances
- B. Horizontal scaling adds more instances; vertical scaling increases the size/capacity of an existing instance
- C. Horizontal and vertical scaling are the same concept in AWS
- D. Vertical scaling is always more cost-effective than horizontal scaling

---

### Question 63 *(Choose ONE)*

A company is migrating to AWS and wants to estimate the cost of running their workloads on AWS before migrating. Which tool should they use?

- A. AWS Cost Explorer
- B. AWS Budgets
- C. AWS Pricing Calculator
- D. AWS Trusted Advisor

---

### Question 64 *(Choose ONE)*

Which AWS Support plan provides a response time of less than 1 hour for production system outages?

- A. Basic
- B. Developer
- C. Business
- D. Enterprise

---

### Question 65 *(Choose ONE)*

A company wants to adopt a cloud-first strategy and reduce technical debt. Under the Well-Architected Framework, which design principle supports this by eliminating the need to maintain legacy infrastructure?

- A. Implement expenditure awareness
- B. Stop spending money on undifferentiated heavy lifting
- C. Automatically recover from failure
- D. Test systems at production scale

---

---

# SECTION 2 — Answer Key

| Q  | Answer(s)  | Domain                    |
|----|------------|---------------------------|
| 1  | C          | Cloud Concepts            |
| 2  | D          | Security                  |
| 3  | B          | Compute                   |
| 4  | A, C, E    | Well-Architected          |
| 5  | D          | Networking                |
| 6  | B          | Billing                   |
| 7  | C          | Security                  |
| 8  | C          | Networking                |
| 9  | C          | Compute                   |
| 10 | C          | Networking                |
| 11 | A, B       | Security                  |
| 12 | C          | Storage                   |
| 13 | B          | Security                  |
| 14 | A, D       | Billing                   |
| 15 | C          | Security                  |
| 16 | B          | Security                  |
| 17 | C          | Well-Architected          |
| 18 | B          | Storage                   |
| 19 | C          | Networking                |
| 20 | B          | Security                  |
| 21 | C          | Billing                   |
| 22 | B          | Database                  |
| 23 | C          | Compute                   |
| 24 | A, C       | Cloud Concepts            |
| 25 | C          | Networking                |
| 26 | C          | Billing                   |
| 27 | C          | Database                  |
| 28 | A, C       | Security                  |
| 29 | C          | Monitoring                |
| 30 | B          | Cloud Concepts            |
| 31 | B          | Security                  |
| 32 | C          | AI/ML                     |
| 33 | D          | Billing/Support           |
| 34 | B          | Networking                |
| 35 | B          | Database                  |
| 36 | C          | Security/Monitoring       |
| 37 | D          | Well-Architected          |
| 38 | B          | Billing                   |
| 39 | B          | Security                  |
| 40 | B          | Compute                   |
| 41 | B, C       | Cloud Concepts            |
| 42 | B          | Networking                |
| 43 | C          | Cloud Concepts            |
| 44 | C          | Storage                   |
| 45 | B          | Cloud Concepts            |
| 46 | A, C       | Storage                   |
| 47 | C          | Compute                   |
| 48 | C          | AI/ML                     |
| 49 | B          | Cloud Concepts            |
| 50 | C          | Billing                   |
| 51 | B          | Cloud Concepts            |
| 52 | C          | Security                  |
| 53 | C          | Compute                   |
| 54 | C          | Storage                   |
| 55 | A, B       | Networking                |
| 56 | C          | Database                  |
| 57 | C          | AI/ML                     |
| 58 | B          | Security/Monitoring       |
| 59 | C          | Networking                |
| 60 | C          | Billing                   |
| 61 | B          | AI/ML                     |
| 62 | B          | Cloud Concepts            |
| 63 | C          | Billing                   |
| 64 | C          | Billing/Support           |
| 65 | B          | Well-Architected          |

---

---

# SECTION 3 — Detailed Explanations

---

### Question 1 — Answer: C

**Why C is correct:** Elasticity is the ability to automatically scale resources up or down in response to demand changes — exactly what's needed for unpredictable traffic spikes without manual intervention.

**Why others are wrong:**
- **A. High availability** — Ensures uptime and minimal downtime; not about handling load spikes automatically.
- **B. Fault tolerance** — The system continues operating despite failures; not about scaling.
- **D. Durability** — Data persistence (e.g., S3's 11 nines of durability); not about traffic handling.

**Exam trap:** High availability and elasticity are often confused. HA = staying up despite failures; Elasticity = scaling automatically with demand.

---

### Question 2 — Answer: D

**Why D is correct:** AWS CloudHSM provides dedicated, single-tenant hardware security modules where only the customer controls the encryption keys — AWS has NO access whatsoever.

**Why others are wrong:**
- **A. ACM** — Manages SSL/TLS certificates; not encryption key management.
- **B. Secrets Manager** — Stores application secrets (API keys, passwords); not HSM-level key management.
- **C. KMS** — Customer-managed keys in KMS give policy control, but AWS manages the underlying hardware and could theoretically access keys under legal compulsion. The question requires "no one including AWS" = CloudHSM.

**Exam trap:** KMS customer-managed keys vs CloudHSM is frequently tested. When "full exclusive control" is required with AWS having zero access, CloudHSM is the answer.

---

### Question 3 — Answer: B

**Why B is correct:** SQS is a durable, persistent message queue — messages remain in the queue (up to 14 days by default) even if the consumer (order processor) is completely down. No orders are lost.

**Why others are wrong:**
- **A. SNS** — Pub/sub; if a subscriber is offline when a message is published, the message is lost.
- **C. Step Functions** — Orchestrates workflows; doesn't provide message durability or act as a buffer.
- **D. Kinesis** — Real-time streaming for data analytics; designed for high-throughput streaming, not reliable order queuing.

**Exam trap:** SNS vs SQS — SNS broadcasts instantly (no storage); SQS stores messages durably until consumed.

---

### Question 4 — Answers: A, C, E

**Why A, C, E are correct:** The six AWS Well-Architected Framework pillars are: Operational Excellence, Security, Reliability, Performance Efficiency, Cost Optimization, and Sustainability.

**Why others are wrong:**
- **B. Agility** — A benefit of cloud computing, not a WAF pillar.
- **D. Scalability** — A design concept and cloud characteristic, not a WAF pillar.

**Exam trap:** The exam includes distractors like Agility, Availability, Scalability, and Durability among the WAF options. Memorize the six pillars precisely.

---

### Question 5 — Answer: D

**Why D is correct:** Private subnets have routing tables with no route to the Internet Gateway. Security Groups control traffic between the web tier (public) and DB tier (private) using private IP addresses. No internet access is allowed to the DB.

**Why others are wrong:**
- **A. Internet Gateway** — Enables internet access; the opposite of what's needed for DB isolation.
- **B. NAT Gateway** — Lets private instances reach the internet for outbound traffic; not for internal communication.
- **C. VPC Peering** — Connects separate VPCs; not for communication within the same VPC.

---

### Question 6 — Answer: B

**Why B is correct:** AWS Organizations Consolidated Billing provides a single invoice for all accounts AND shares Reserved Instance and Savings Plan discounts across member accounts automatically.

**Why others are wrong:**
- **A. Cost Explorer** — Analyzes and visualizes spending; no invoice consolidation.
- **C. Budgets** — Sets spending alerts; no invoice consolidation.
- **D. Pricing Calculator** — Estimates future costs; not billing management.

---

### Question 7 — Answer: C

**Why C is correct:** Physical security of data centers (access controls, surveillance, guards, environmental protection) is entirely AWS's responsibility — "security OF the cloud."

**Why others are wrong:**
- **A.** IAM user configuration = customer responsibility.
- **B.** Guest OS patching on EC2 = customer responsibility (AWS patches the hypervisor, not the guest OS).
- **D.** Enabling CloudTrail = customer responsibility; AWS provides the service but customers must enable it.

**Exam trap:** The shared responsibility model is heavily tested. AWS = physical + hypervisor + global network. Customer = data, OS, applications, IAM, network configs.

---

### Question 8 — Answer: C

**Why C is correct:** Amazon CloudFront is a CDN with 400+ edge locations that caches and delivers video content from the edge closest to each viewer — minimizing buffering and latency for global audiences.

**Why others are wrong:**
- **A. S3 Transfer Acceleration** — Speeds file uploads TO S3; does not improve video delivery to end users.
- **B. Global Accelerator** — Improves TCP/UDP performance via AWS backbone but does NOT cache content.
- **D. Route 53 latency routing** — Routes DNS to nearest Region; doesn't cache or deliver video content at the edge.

**Exam trap:** Global Accelerator vs CloudFront — both improve global performance. CloudFront = content caching CDN. Global Accelerator = network path optimization without caching.

---

### Question 9 — Answer: C

**Why C is correct:** P-family (P3, P4) and G-family (G4, G5) EC2 instances are specifically designed with NVIDIA/AMD GPUs for ML training, inference, HPC, and graphics rendering.

**Why others are wrong:**
- **A. C-family** — High vCPU-to-memory ratio for CPU-intensive work (HPC without GPU, gaming servers).
- **B. R-family** — High memory-to-vCPU ratio for in-memory databases, analytics.
- **D. I-family** — High-speed NVMe SSD storage for I/O-intensive workloads like databases and data warehouses.

---

### Question 10 — Answer: C

**Why C is correct:** Route 53 health checks continuously monitor endpoints and can automatically switch DNS records to a healthy endpoint using Failover routing — providing DNS-level failover.

**Why others are wrong:**
- **A. CloudFront** — CDN; doesn't perform DNS failover between endpoints.
- **B. ELB** — Distributes traffic across healthy targets within a Region; it's not a global DNS failover service.
- **D. Global Accelerator** — Improves routing but Route 53 is the DNS failover service.

---

### Question 11 — Answers: A, B

**Why A and B are correct:** CloudTrail logs all API calls → CloudWatch can filter CloudTrail logs using metric filters, trigger alarms, and invoke Lambda for automated response when unauthorized API calls are detected.

**Why others are wrong:**
- **C. Inspector** — Scans EC2 for software vulnerabilities; not related to API call monitoring.
- **D. Config** — Tracks configuration changes; not real-time API call alerting.
- **E. GuardDuty** — Detects threats using ML on logs; effective but the question asks about the mechanism for detecting unauthorized API calls and taking action, which the CloudTrail + CloudWatch combination enables directly.

---

### Question 12 — Answer: C

**Why C is correct:** S3 One Zone-IA stores data in a single AZ (reducing cost by ~20% vs Standard-IA) with infrequent access pricing but millisecond retrieval. It's appropriate when data can be recreated if an AZ fails.

**Why others are wrong:**
- **A. S3 Standard-IA** — Multi-AZ infrequent access; more expensive than One Zone-IA.
- **B. Glacier Instant Retrieval** — Also millisecond retrieval but optimized for quarterly access patterns; more expensive than One Zone-IA for monthly access.
- **D. Intelligent-Tiering** — Moves objects between tiers automatically based on access patterns; has monitoring/automation fees.

---

### Question 13 — Answer: B

**Why B is correct:** CloudHSM is a dedicated hardware security module — AWS has no access to your keys. Only you have the credentials to manage keys on your CloudHSM. This meets the strictest compliance requirements.

**Why others are wrong:**
- **A. KMS with customer-managed keys** — Customer controls key policies but AWS manages the hardware. Under certain legal circumstances, AWS could access KMS keys.
- **C. Secrets Manager** — Stores and rotates application secrets; not HSM-level key control.
- **D. SSE-S3** — Uses fully AWS-managed keys — customer has the least control.

---

### Question 14 — Answers: A, D

**Why A and D are correct:** The optimal pattern: Reserved Instances cover the predictable baseline (greatest discount for always-on traffic). EC2 Auto Scaling adds capacity (On-Demand or Spot) during peak periods automatically.

**Why others are wrong:**
- **B.** Dedicated Hosts are expensive and for compliance/licensing — overkill for an e-commerce site.
- **C.** On-Demand during peaks without Auto Scaling requires manual intervention.
- **E.** Spot Instances for baseline workload is risky — they can be interrupted, which could take down the core application.

---

### Question 15 — Answer: C

**Why C is correct:** Amazon Macie uses ML to automatically discover, classify, and alert on sensitive data (PII, financial data, credentials) stored in S3 buckets.

**Why others are wrong:**
- **A. GuardDuty** — Detects threats (unauthorized access, cryptomining, reconnaissance) by analyzing CloudTrail/VPC Flow Logs/DNS logs — not S3 data classification.
- **B. Inspector** — Vulnerability scanning for EC2 and container images; not data classification.
- **D. Security Hub** — Aggregates findings from multiple security services; doesn't discover sensitive data.

---

### Question 16 — Answer: B

**Why B is correct:** IAM Roles with STS AssumeRole provide temporary, time-limited credentials — no long-term credentials exist that could be leaked or misused. Cross-account role assumption is the AWS-recommended pattern for third-party access.

**Why others are wrong:**
- **A.** Sharing IAM user passwords creates long-term credential risk.
- **C.** Sharing root credentials is a critical security violation; root has unlimited permissions.
- **D.** Access keys are long-term credentials; emailing them is insecure regardless of method.

---

### Question 17 — Answer: C

**Why C is correct:** Operational Excellence focuses on running workloads effectively, gaining insight through monitoring, and continuously improving processes and procedures. Key principles include: perform operations as code, make frequent small reversible changes, and learn from failures.

**Why others are wrong:**
- **A. Reliability** — Recovery from failures; meeting business demand consistently.
- **B. Performance Efficiency** — Using compute resources efficiently and selecting right types/sizes.
- **D. Security** — Protecting data, systems, and assets.

---

### Question 18 — Answer: B

**Why B is correct:** AWS Snowball Edge is a petabyte-scale physical data transfer device — loaded offline and shipped to AWS. Ideal for 50TB+ transfers over slow/unreliable internet connections where online transfer would take weeks.

**Why others are wrong:**
- **A. DataSync** — Automates online data transfer; requires reliable internet bandwidth.
- **C. Direct Connect** — A permanent dedicated network link (expensive to set up just for migration; also takes weeks to provision).
- **D. S3 Transfer Acceleration** — Uses CloudFront edges to accelerate internet uploads; still requires reliable connectivity.

---

### Question 19 — Answer: C

**Why C is correct:** Security Groups evaluate ALL rules together (there's no rule ordering/priority within a SG) before deciding to allow or deny. Since SGs only have ALLOW rules, if any rule matches, traffic is allowed; otherwise implicitly denied.

**Why others are wrong:**
- **A.** Security Groups cannot explicitly DENY traffic. Only NACLs support explicit DENY.
- **B.** Security Groups are STATEFUL (return traffic automatically allowed). NACLs are stateless.
- **D.** Security Groups operate at the instance/ENI level. NACLs operate at the subnet level.

**Exam trap:** This is the #1 most tested networking distinction — memorize Security Group vs NACL differences completely.

---

### Question 20 — Answer: B

**Why B is correct:** AWS WAF (Web Application Firewall) is specifically designed to protect against Layer 7 web attacks including SQL injection, XSS, and OWASP Top 10 threats using configurable rules and managed rule groups.

**Why others are wrong:**
- **A. Shield Standard** — Protects against DDoS (volumetric) attacks at Layer 3/4; doesn't inspect HTTP request content.
- **C. GuardDuty** — Detects threats by analyzing logs; doesn't actively block web requests.
- **D. Inspector** — Scans EC2 for vulnerabilities; doesn't filter web traffic.

---

### Question 21 — Answer: C

**Why C is correct:** Compute Savings Plans offer up to 66% discount with maximum flexibility — they apply to any EC2 instance (any family, size, OS, tenancy, Region), as well as Fargate and Lambda. You commit to a $/hour spend.

**Why others are wrong:**
- **A. Standard RIs** — Up to 72% discount but locked to specific instance type/Region.
- **B. Spot** — Interruptible compute at market price; not a commitment-based model.
- **D. Convertible RIs** — EC2 only; can change instance type but less flexible than Compute Savings Plans.

**Exam trap:** Savings Plans (Compute vs EC2 Instance) vs Reserved Instances is a frequently tested comparison. Compute Savings Plans = most flexible; Standard RIs = highest discount.

---

### Question 22 — Answer: B

**Why B is correct:** RDS Read Replicas create asynchronous copies of the primary database specifically for serving read traffic. Directing read queries to replicas reduces primary DB load and improves read performance.

**Why others are wrong:**
- **A. Multi-AZ** — Creates a synchronous standby for automatic failover; the standby is NOT accessible for reads. This is purely for high availability.
- **C. Automated backups** — For point-in-time recovery; doesn't help with read performance.
- **D. RDS Proxy** — Manages connection pooling between apps and DB; improves connection efficiency, not read throughput.

**Exam trap:** Multi-AZ vs Read Replicas is the most common database exam trap. Multi-AZ = HA/failover. Read Replicas = read scaling/performance.

---

### Question 23 — Answer: C

**Why C is correct:** Amazon EKS (Elastic Kubernetes Service) provides managed Kubernetes — AWS manages the control plane (master nodes, etcd, API server). Customers manage worker nodes or use Fargate for serverless workers.

**Why others are wrong:**
- **A. ECS** — AWS's proprietary container orchestration service; not Kubernetes.
- **B. Fargate** — Serverless compute engine for containers; runs on top of ECS or EKS — not a Kubernetes service itself.
- **D. Elastic Beanstalk** — PaaS for applications; not a Kubernetes service.

---

### Question 24 — Answers: A, C

**Why A and C are correct:** Managed services (RDS, DynamoDB, EMR, etc.) shift infrastructure tasks to AWS: patching, backups, hardware management, scaling. This reduces operational burden on the customer.

**Why others are wrong:**
- **B.** Fully managed services don't provide OS-level access (e.g., you can't SSH into an RDS instance).
- **D.** Managed services aren't always cheaper — they often cost more than self-managed for raw infrastructure, but the operational savings offset this.
- **E.** Managed services reduce control by design — the tradeoff for reduced overhead.

---

### Question 25 — Answer: C

**Why C is correct:** Geolocation routing routes DNS queries based on the user's geographic location (country, continent, US state) — ensuring EU users go to the EU Region for data residency compliance.

**Why others are wrong:**
- **A. Latency routing** — Goes to the lowest-latency endpoint; a US user might get routed to a non-EU Region if it's faster — violating data residency requirements.
- **B. Weighted routing** — Distributes traffic by percentage; ignores location.
- **D. Failover routing** — Active/passive disaster recovery; doesn't consider location.

---

### Question 26 — Answer: C

**Why C is correct:** Spot Instances offer up to 90% discount for workloads that are flexible and can tolerate interruption. Batch analytics can be restarted if interrupted — the perfect Spot use case.

**Why others are wrong:**
- **A. On-Demand** — No discount; most expensive per-hour option.
- **B. Reserved Instances** — Up to 72% discount but requires 1-3 year commitment; also not cheaper than Spot for interruptible work.
- **D. Dedicated Hosts** — Most expensive option; for compliance/licensing needs.

---

### Question 27 — Answer: C

**Why C is correct:** Amazon Redshift is AWS's petabyte-scale columnar data warehouse — optimized for OLAP analytical queries on large datasets using massively parallel processing.

**Why others are wrong:**
- **A. RDS** — OLTP relational databases; not optimized for petabyte-scale analytics.
- **B. DynamoDB** — NoSQL key-value/document database; not for complex analytical SQL queries.
- **D. Aurora** — High-performance relational database; excellent for OLTP but not a data warehouse.

---

### Question 28 — Answers: A, C

**Why A and C are correct:** AWS root account best practices: (1) Enable MFA immediately — it's the most critical protection. (2) Create individual IAM users for all operations — root should be used only for account-level tasks that specifically require it.

**Why others are wrong:**
- **B.** Root should NEVER be used for daily administrative actions.
- **D.** Root access keys should be DELETED — not generated. AWS explicitly recommends this.
- **E.** Storing the root password in Secrets Manager doesn't follow the principle of minimal root usage.

---

### Question 29 — Answer: C

**Why C is correct:** CloudWatch is the monitoring service that collects Lambda metrics (invocations, errors, duration, concurrent executions, throttles), enables metric-based alarms, and integrates with SNS for notifications.

**Why others are wrong:**
- **A. CloudTrail** — Records Lambda API calls (who invoked CreateFunction, etc.) — not runtime performance metrics.
- **B. X-Ray** — Provides distributed tracing for debugging request flows; not metric-based alerting.
- **D. Config** — Tracks Lambda configuration changes (function code updates, permission changes); not performance metrics.

---

### Question 30 — Answer: B

**Why B is correct:** High availability = the system remains operational with minimal downtime even when components fail. Achieved through redundancy across AZs, ELB, and Auto Scaling.

**Why others are wrong:**
- **A.** Handling any amount of traffic = elasticity/scalability.
- **C.** Automatically reducing costs = cost optimization, not HA.
- **D.** Backing up to multiple regions = disaster recovery; related to HA but not the definition.

---

### Question 31 — Answer: B

**Why B is correct:** HTTPS/TLS encrypts data IN TRANSIT between the client and S3 endpoint. This is the standard mechanism for protecting data moving across the network.

**Why others are wrong:**
- **A. SSE-S3** — Encrypts data AT REST (when stored on disk); doesn't protect data during transmission.
- **C. Versioning** — Maintains object history for recovery; not encryption.
- **D. Bucket policy** — Controls access permissions; doesn't encrypt data.

**Exam trap:** "At rest" vs "in transit" encryption — very commonly tested. At rest = SSE; In transit = HTTPS/TLS.

---

### Question 32 — Answer: C

**Why C is correct:** Amazon Transcribe converts speech (audio/video files) to text — automatic speech recognition (ASR). Perfect for transcribing audio files uploaded to S3.

**Why others are wrong:**
- **A. Comprehend** — NLP on text (sentiment, entities); requires text input, not audio.
- **B. Polly** — Text-to-speech; converts text TO audio (opposite direction).
- **D. Textract** — Extracts text from scanned documents, forms, and tables (images/PDFs); not audio.

**AI/ML service memory aid:** Transcribe = audio → text. Polly = text → audio. Textract = document → text. Comprehend = text → insights.

---

### Question 33 — Answer: D

**Why D is correct:** Only the Enterprise Support Plan ($15,000+/month) provides both a dedicated TAM and Concierge Support (specialized billing/account guidance). Enterprise On-Ramp has a pool of TAMs (not dedicated) and no Concierge.

**Why others are wrong:**
- **A. Developer** — Business-hours email support only; no TAM, no Concierge.
- **B. Business** — 24/7 support engineers + full Trusted Advisor; no TAM, no Concierge.
- **C. Enterprise On-Ramp** — Includes access to a pool of TAMs but not a dedicated TAM, and no Concierge Support.

---

### Question 34 — Answer: B

**Why B is correct:** VPC Endpoints (Gateway or Interface type) allow private subnet resources to communicate with AWS services (S3, DynamoDB, SSM, etc.) through the AWS private network — no internet required.

**Why others are wrong:**
- **A. NAT Gateway** — Routes outbound traffic FROM private subnets TO the internet; still goes through public internet for AWS API calls.
- **C. Internet Gateway** — Provides public internet access; private subnets don't route through IGW.
- **D. Direct Connect** — For on-premises to AWS connectivity; not for VPC-internal traffic to AWS services.

---

### Question 35 — Answer: B

**Why B is correct:** RDS provides managed relational databases (MySQL, PostgreSQL, Oracle, SQL Server, MariaDB) with structured schemas and SQL. DynamoDB is a fully managed NoSQL database supporting key-value and document data models.

**Why others are wrong:**
- **A.** RDS is SQL only; DynamoDB is NoSQL only — not SQL.
- **C.** DynamoDB is fully managed/serverless — no EC2 instances to manage.
- **D.** DynamoDB scales to millions of RPS automatically — not RDS.

---

### Question 36 — Answer: C

**Why C is correct:** AWS Config continuously records configuration states of AWS resources and evaluates them against Config Rules. It provides a timeline of configuration changes and a compliance dashboard.

**Why others are wrong:**
- **A. CloudWatch** — Monitors performance metrics and logs; doesn't track resource configuration changes.
- **B. CloudTrail** — Records API calls (who did what); not configuration state tracking.
- **D. Inspector** — Scans for software vulnerabilities; not configuration compliance.

---

### Question 37 — Answer: D

**Why D is correct:** Performance Efficiency design principles include: stop guessing capacity (use auto scaling), test systems at production scale, use serverless architectures, go global in minutes, and experiment more often.

**Why others are wrong:**
- **A. Cost Optimization** — Adopt consumption model, analyze expenditure, use managed services.
- **B. Reliability** — Automatically recover from failure, test recovery procedures, scale horizontally.
- **C. Operational Excellence** — Perform operations as code, make frequent small changes, anticipate failure.

---

### Question 38 — Answer: B

**Why B is correct:** S3 static website hosting + CloudFront is the canonical serverless, globally distributed, extremely low-cost architecture for static websites. No compute costs, no servers to manage, global edge delivery.

**Why others are wrong:**
- **A.** EC2 + ELB incurs compute (EC2) costs and requires server management — much more expensive.
- **C.** Elastic Beanstalk + RDS is server-based and includes database costs — massive overkill for a static site.
- **D.** Lightsail is a simplified VPS service — still involves a virtual server with compute costs.

---

### Question 39 — Answer: B

**Why B is correct:** AWS IAM policy evaluation logic: Explicit DENY always wins. Regardless of how many ALLOW policies exist from any source (user, group, role, SCP), a single explicit DENY overrides all of them.

**Why others are wrong:**
- **A.** ALLOW never overrides an explicit DENY in AWS IAM.
- **C.** There is no "most recent policy wins" concept in IAM.
- **D.** The source of the policy (user-attached vs group-attached) is irrelevant — DENY always wins.

**Exam trap:** This is a critical IAM evaluation logic question. The hierarchy is: 1) Explicit DENY → stop, deny. 2) Explicit ALLOW → allow. 3) No match → implicit deny.

---

### Question 40 — Answer: B

**Why B is correct:** Amazon SNS is a pub/sub messaging service that can fan out to millions of subscribers simultaneously via mobile push (APNs, FCM), SMS, email, and HTTP/HTTPS — ideal for mass notifications.

**Why others are wrong:**
- **A. SQS** — Message queue for point-to-point; not designed for broadcasting to millions simultaneously.
- **C. SES** — Email-only service; cannot send mobile push or SMS.
- **D. EventBridge** — Event bus for routing events between AWS services; not for end-user mobile notifications.

---

### Question 41 — Answers: B, C

**Why B and C are correct:** Core cloud computing advantages: (1) Trade CapEx (upfront hardware) for OpEx (pay-as-you-go). (2) Economies of scale — AWS's purchasing power reduces costs for all customers.

**Why others are wrong:**
- **A.** Security responsibilities are SHARED — not eliminated. Customers still own their data and configurations.
- **D.** Zero latency is physically impossible.
- **E.** You lose physical hardware control in the cloud by design.

---

### Question 42 — Answer: B

**Why B is correct:** AWS Transit Gateway is a hub-and-spoke model — each VPC connects once to the TGW. 15 VPCs = 15 connections total. Without TGW, a full mesh requires 105 peering connections. TGW also supports on-premises connectivity via VPN/Direct Connect.

**Why others are wrong:**
- **A.** 15 VPCs in full mesh = 15*(15-1)/2 = 105 peering connections — complex and unmanageable.
- **C.** Separate VPN per VPC is expensive and doesn't connect VPCs to each other.
- **D.** VPC Endpoints connect to AWS services, not to other VPCs.

---

### Question 43 — Answer: C

**Why C is correct:** AWS Outposts delivers AWS-managed compute and storage hardware physically installed in your data center, running AWS services locally with the same APIs as AWS cloud — consistent hybrid experience.

**Why others are wrong:**
- **A. Direct Connect** — A private dedicated network link FROM your premises TO AWS; doesn't bring AWS to your premises.
- **B. VPN** — Encrypted network tunnel to AWS; doesn't bring AWS infrastructure on-premises.
- **D. Local Zones** — AWS-managed mini-Regions in specific cities for low-latency; still AWS-hosted, not on-premises.

---

### Question 44 — Answer: C

**Why C is correct:** S3 Cross-Region Replication (CRR) automatically replicates objects from a source bucket to a destination bucket in a DIFFERENT AWS Region — providing geographic redundancy and compliance support.

**Why others are wrong:**
- **A. Versioning** — Maintains multiple versions within the SAME bucket; no cross-region copying.
- **B. Lifecycle Policies** — Transitions objects between storage classes or deletes them; no cross-region movement.
- **D. Object Lock** — WORM protection against deletion; no cross-region functionality.

---

### Question 45 — Answer: B

**Why B is correct:** AWS CloudFormation is the native AWS Infrastructure as Code service — templates define resources in JSON/YAML, and CloudFormation provisions, updates, and deletes infrastructure stacks.

**Why others are wrong:**
- **A. Elastic Beanstalk** — PaaS for application deployment; not IaC.
- **C. OpsWorks** — Managed configuration management using Puppet/Chef; not template-based IaC.
- **D. Systems Manager** — Manages operational tasks on running resources (patching, run commands); not IaC.

---

### Question 46 — Answers: A, C

**Why A and C are correct:** S3 Standard for the first 90 days (fast access when auditors might need them) → transition to S3 Glacier for 3-year compliance retention (lowest cost for rarely accessed data). S3 Lifecycle Policies automate this transition — combining A + C is the full solution.

**Why others are wrong:**
- **B.** Storing permanently in S3 Standard is very expensive for 3 years of rarely-accessed logs.
- **D.** Deleting after 90 days violates the 3-year compliance requirement.
- **E.** Starting in Glacier makes logs difficult to access during the first 90 days when they may be needed for active investigations.

---

### Question 47 — Answer: C

**Why C is correct:** Lambda automatically runs a new execution environment for every invocation trigger — scaling from 0 to thousands of concurrent executions instantly with no configuration required.

**Why others are wrong:**
- **A.** Lambda maximum timeout is 15 minutes (900 seconds) — not 24 hours.
- **B.** Lambda is serverless — no EC2 provisioning or management whatsoever.
- **D.** Lambda supports Python, Node.js, Java, Go, Ruby, .NET, PowerShell, and custom runtimes.

---

### Question 48 — Answer: C

**Why C is correct:** Amazon Comprehend is the NLP service that performs sentiment analysis (positive/negative/neutral/mixed), entity recognition, key phrase extraction, and topic modeling on text data.

**Why others are wrong:**
- **A. Rekognition** — Computer vision for analyzing images and videos (face detection, object detection).
- **B. Transcribe** — Converts speech/audio to text; doesn't analyze sentiment.
- **D. Lex** — Builds conversational chatbots; doesn't perform sentiment analysis on existing text.

---

### Question 49 — Answer: B

**Why B is correct:** Fault tolerance = the system continues to operate correctly (no service interruption) despite one or more component failures — achieved through redundancy and failover mechanisms.

**Why others are wrong:**
- **A.** Automatic scaling to meet demand = elasticity.
- **C.** Recovering data from backups = disaster recovery (implies some downtime/data loss).
- **D.** Distributing load across servers = load balancing (supports fault tolerance but is not the definition).

---

### Question 50 — Answer: C

**Why C is correct:** AWS Trusted Advisor provides automated, real-time recommendations across 5 categories: Cost Optimization, Security, Fault Tolerance, Performance, and Service Limits — with actual checks against your current AWS environment.

**Why others are wrong:**
- **A. Config** — Tracks and evaluates resource configuration compliance; no cost or performance recommendations.
- **B. CloudWatch** — Monitoring service; no architectural recommendations.
- **D. Well-Architected Tool** — Provides WAF pillar reviews; requires manual input and review — not automated live environment scanning.

---

### Question 51 — Answer: B

**Why B is correct:** Pilot light keeps the minimum core components running (DB replica, core AMIs ready) in the DR Region. On disaster, you quickly provision the remaining infrastructure around the "pilot light" — faster than backup/restore but less expensive than warm standby.

**Why others are wrong:**
- **A. Backup and restore** — No resources running in DR; highest RTO/RPO (hours to days). Lowest cost.
- **C. Warm standby** — A scaled-down but fully functional version of the production environment is running and ready; faster RTO than pilot light.
- **D. Multi-site active-active** — Full production capacity running in both regions simultaneously; RTO/RPO near-zero. Most expensive.

**DR Strategy spectrum:** Backup & Restore < Pilot Light < Warm Standby < Multi-site Active-Active (RTO: slow → fast, Cost: low → high).

---

### Question 52 — Answer: C

**Why C is correct:** Service Control Policies (SCPs) are Organization-level guardrails that define the maximum permissions available to all accounts in an OU — they cannot be overridden by any IAM policy within the account, even AdministratorAccess.

**Why others are wrong:**
- **A. Permission boundaries** — Limit maximum permissions for individual IAM entities (users/roles) within a single account; not Organization-wide.
- **B. Resource-based policies** — Attached to resources (S3 buckets, SQS queues); control resource access, not account-wide restrictions.
- **D. Identity-based policies** — Attached to IAM users/roles; can be restricted by SCPs.

---

### Question 53 — Answer: C

**Why C is correct:** AWS Elastic Beanstalk is the fastest path from code to running application — upload your code, and Beanstalk handles EC2 provisioning, ELB configuration, Auto Scaling, health monitoring, and deployment. Zero server expertise needed.

**Why others are wrong:**
- **A.** EC2 with manual configuration requires significant setup: VPC, security groups, load balancer, scaling policies, deployment scripts — high overhead.
- **B. Fargate** — Good for containers but requires Dockerfile, ECS task definitions, containerization expertise.
- **D. EKS** — Requires Kubernetes expertise; complex configuration for cluster, nodes, pods, services.

---

### Question 54 — Answer: C

**Why C is correct:** Amazon EFS is a fully managed NFS (Network File System) that can be mounted simultaneously by thousands of EC2 instances across all AZs in a Region — true shared file storage.

**Why others are wrong:**
- **A.** EBS is block storage attached to ONE instance at a time in ONE AZ.
- **B.** S3 is object storage with REST API access — not EFS.
- **D.** Glacier (S3 Glacier) is for archival storage — not EFS.

**Storage type summary:** S3 = object, EBS = block (single instance), EFS = file (shared/multi-instance), Glacier = archive.

---

### Question 55 — Answers: A, B

**Why A and B are correct:** AZ fault tolerance requires: (1) Resources deployed in at least 2 AZs so one AZ failure doesn't cause complete outage. (2) ELB automatically detects unhealthy AZ and routes traffic only to healthy AZs.

**Why others are wrong:**
- **C. S3 Versioning** — Protects against accidental deletion; doesn't provide AZ fault tolerance.
- **D. Reserved Instances** — A pricing model; no impact on availability.
- **E.** Single large EC2 = single point of failure; if the AZ fails, so does the instance.

---

### Question 56 — Answer: C

**Why C is correct:** Amazon Athena is serverless — write standard SQL to query data directly in S3, pay only for the data scanned ($5/TB). No clusters to provision, no data loading required.

**Why others are wrong:**
- **A. RDS** — Data must be loaded into a managed relational database; not S3 querying.
- **B. Redshift** — Data warehouse; data must be loaded before querying.
- **D. Glue** — ETL service for extracting, transforming, and loading data; doesn't execute end-user SQL queries.

---

### Question 57 — Answer: C

**Why C is correct:** Amazon Lex provides automatic speech recognition (ASR) and natural language understanding (NLU) for building conversational chatbots. It's the technology behind Alexa and supports multi-turn dialogues.

**Why others are wrong:**
- **A. Comprehend** — NLP text analysis (sentiment, entities); not a chatbot builder.
- **B. Polly** — Text-to-speech; gives chatbots a voice but doesn't handle conversation logic.
- **D. Transcribe** — Speech-to-text; converts audio to text but doesn't understand intent or manage conversations.

---

### Question 58 — Answer: B

**Why B is correct:** AWS Config evaluates resource configurations against Config Rules and provides a compliance dashboard showing which resources are compliant and which are not, with full configuration history.

**Why others are wrong:**
- **A. Inspector** — Vulnerability scanning for EC2/containers; not configuration compliance checking.
- **C. Trusted Advisor** — Gives recommendations but not a per-resource compliance dashboard with historical configuration states.
- **D. GuardDuty** — Threat detection using log analysis; not compliance checking.

---

### Question 59 — Answer: C

**Why C is correct:** NACLs operate at the subnet boundary and are the ONLY network control that supports explicit DENY rules by IP address. Rules are evaluated in number order (lower number = higher priority).

**Why others are wrong:**
- **A. Security Groups** — Instance-level; only ALLOW rules. Cannot explicitly DENY specific IPs.
- **B. IAM Policies** — Control who can make AWS API calls; have no effect on network traffic between hosts.
- **D. WAF** — Layer 7 (HTTP/HTTPS); not subnet-level IP blocking for financial transaction servers.

**Exam trap:** Security Groups vs NACLs — SGs = instance level, stateful, ALLOW only. NACLs = subnet level, stateless, ALLOW and DENY.

---

### Question 60 — Answer: C

**Why C is correct:** The EC2 Free Tier provides exactly 750 hours/month of t2.micro (or t3.micro in Regions without t2.micro) running Linux, for 12 months from account creation date.

**Why others are wrong:**
- **A.** Only t2.micro/t3.micro (Linux) qualify — not any instance type.
- **B.** The Free Tier is NOT permanent for EC2; it expires after 12 months.
- **D.** Data transfer has its own Free Tier limits; not all data transfer is free.

---

### Question 61 — Answer: B

**Why B is correct:** The correct pipeline: Amazon Textract extracts text from uploaded documents → Amazon Comprehend identifies PII entities in the extracted text → AWS Lambda implements the redaction logic and outputs the redacted version.

**Why others are wrong:**
- **A. Macie + Lambda** — Macie discovers sensitive data in S3 at a bucket/object level but cannot extract and process document text for PII redaction.
- **C. Rekognition + Glue** — Rekognition is for image/video analysis; Glue is for ETL — neither handles document PII redaction.
- **D. Transcribe + Translate** — Transcribe converts audio; Translate does language translation — wrong services entirely.

---

### Question 62 — Answer: B

**Why B is correct:** Horizontal scaling (scale out/in) = adding/removing instances in a fleet — preferred AWS pattern, supports elasticity and fault tolerance. Vertical scaling (scale up/down) = changing the instance size (more CPU/RAM) — has upper limits and may require downtime.

**Why others are wrong:**
- **A.** This is the reverse — horizontal = more instances; vertical = bigger instance.
- **C.** They are fundamentally different concepts with different trade-offs.
- **D.** Vertical scaling is often MORE expensive as instance sizes grow (premium for larger instances) and doesn't improve fault tolerance.

---

### Question 63 — Answer: C

**Why C is correct:** AWS Pricing Calculator is designed for pre-migration/pre-provisioning cost estimation — model your intended architecture and get a monthly cost estimate before spending anything.

**Why others are wrong:**
- **A. Cost Explorer** — Analyzes and visualizes historical spending on an existing AWS account; useless before migration.
- **B. Budgets** — Sets spending alerts; not a cost estimation tool.
- **D. Trusted Advisor** — Provides recommendations on existing resources; not a cost estimator for planned workloads.

---

### Question 64 — Answer: C

**Why C is correct:** Business Support SLA for production system down: less than 1 hour response time. This is the minimum plan that offers sub-1-hour production support response.

**Support response times summary:**
- Basic: No technical support
- Developer: 12 hours (general guidance), business hours only
- Business: 1 hour (production down), 4 hours (production impaired), 24 hours (general)
- Enterprise: 15 minutes (business-critical system down), 1 hour (production down)

**Why others are wrong:**
- **A. Basic** — No technical support at all.
- **B. Developer** — Business hours only; slowest response times.
- **D. Enterprise** — Also has <1 hour for production down (and <15 min for business-critical), but Business is the MINIMUM plan meeting the requirement.

---

### Question 65 — Answer: B

**Why B is correct:** "Stop spending money on undifferentiated heavy lifting" means using AWS managed services and the cloud instead of maintaining commodity infrastructure, servers, and legacy systems that don't differentiate your business.

**Why others are wrong:**
- **A. Implement expenditure awareness** — Cost Optimization principle about tracking and understanding cloud spending.
- **C. Automatically recover from failure** — Reliability pillar design principle.
- **D. Test systems at production scale** — Performance Efficiency pillar design principle.

---

---

## Scoring Guide

| Score | Result | Readiness Assessment |
|-------|--------|----------------------|
| 80–100% | Excellent | Very strong readiness — schedule your exam |
| 70–79% | Pass | Good readiness — review flagged areas |
| 60–69% | Borderline | Study weak domains and retake in 1–2 weeks |
| Below 60% | Needs work | Complete an AWS Cloud Practitioner training course first |

---

## Topic Coverage Summary

| Domain | Questions |
|--------|-----------|
| Cloud Concepts | 1, 24, 30, 41, 43, 45, 49, 51, 62 |
| Security & Compliance | 2, 7, 11, 13, 15, 16, 19, 20, 28, 31, 36, 39, 52, 58, 59 |
| Networking | 5, 8, 10, 25, 34, 42, 55 |
| Compute | 3, 9, 14, 23, 26, 40, 47, 53 |
| Storage | 12, 18, 31, 44, 46, 54 |
| Database | 22, 27, 35, 56 |
| Billing & Pricing | 6, 14, 21, 26, 33, 38, 50, 60, 63, 64 |
| Well-Architected Framework | 4, 17, 37, 65 |
| Monitoring | 11, 29, 36, 58 |
| AI/ML Services | 32, 48, 57, 61 |

---

## Key Exam Traps Covered in This Set

| Trap | Questions |
|------|-----------|
| KMS vs CloudHSM (key control) | 2, 13 |
| SNS vs SQS (messaging) | 3, 40 |
| Multi-AZ vs Read Replicas | 22 |
| Security Groups vs NACLs | 19, 59 |
| CloudWatch vs CloudTrail | 11, 29, 36 |
| Shield vs WAF | 20 |
| EBS vs EFS vs S3 storage types | 12, 54 |
| Explicit DENY in IAM | 39 |
| Pilot light vs Warm standby vs Active-Active | 51 |
| Latency vs Geolocation routing | 25 |
| Spot vs Reserved vs Savings Plans | 21, 26 |
| Transit Gateway vs VPC Peering | 42 |
| Trusted Advisor vs Well-Architected Tool | 50 |
| Transcribe vs Polly vs Textract vs Comprehend | 32, 48, 61 |

---

*This is Set 2 of the AWS CLF-C02 Mock Exam series. Combined with Set 1 (65 questions), you have 130 unique practice questions to prepare for your certification.*

*Scoring 75%+ on both sets indicates strong readiness for the real AWS Certified Cloud Practitioner exam.*
