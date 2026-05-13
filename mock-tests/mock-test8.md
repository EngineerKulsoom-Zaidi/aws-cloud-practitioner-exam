# AWS Certified Cloud Practitioner (CLF-C02) — Full-Length Mock Exam

> **65 Questions | 90 Minutes | Pass Score: 70% (~45/65)**
> Domains: Cloud Concepts · Security & Compliance · Technology & Services · Billing & Pricing

---

## SECTION 1 — Questions

---

### Question 1 (Single Answer | Scenario)

A startup company is planning to launch a new web application and wants to avoid the upfront capital expense of purchasing servers. They also need the ability to scale their infrastructure up or down based on user demand. Which benefit of cloud computing **BEST** addresses these requirements?

- A. High availability
- B. Elasticity and pay-as-you-go pricing
- C. Dedicated hardware ownership
- D. Fixed capacity planning

---

### Question 2 (Single Answer | Security)

A company has multiple AWS accounts. The security team wants to centrally manage and enforce security policies across ALL accounts, including preventing developers from disabling AWS CloudTrail. Which AWS service should they use?

- A. AWS IAM
- B. AWS Config
- C. AWS Organizations with Service Control Policies (SCPs)
- D. AWS Security Hub

---

### Question 3 (Single Answer | Scenario | Networking)

A company runs a web application with a database backend. They want to ensure that the database servers are NOT directly accessible from the internet, but the web servers need internet access. Which AWS architecture **BEST** meets this requirement?

- A. Place both web and database servers in a public subnet
- B. Place web servers in a public subnet and database servers in a private subnet with a NAT Gateway for outbound traffic
- C. Place both servers in a private subnet behind a NAT Gateway
- D. Place database servers behind an Internet Gateway

---

### Question 4 (Single Answer | Billing)

A company runs a steady-state, predictable batch-processing workload on EC2 that runs 24/7 for 3 years. Which EC2 purchasing option provides the **MOST** cost savings?

- A. On-Demand Instances
- B. Spot Instances
- C. Reserved Instances (3-year, All Upfront)
- D. Dedicated Hosts

---

### Question 5 (Choose TWO | Security)

A company wants to improve the security of their AWS root account. Which **TWO** actions should they take immediately?

- A. Enable multi-factor authentication (MFA) on the root account
- B. Create access keys for the root account for CLI access
- C. Delete the root account and use only IAM users
- D. Avoid using the root account for daily tasks
- E. Share root account credentials with the security team

---

### Question 6 (Single Answer | Well-Architected)

A company wants to minimize the impact of unexpected changes and automate responses to operational events. This is **MOST** aligned with which pillar of the AWS Well-Architected Framework?

- A. Performance Efficiency
- B. Cost Optimization
- C. Operational Excellence
- D. Reliability

---

### Question 7 (Single Answer | Scenario | Storage)

A media company stores video files that are accessed frequently during the first 30 days after upload, then rarely accessed afterward but must be retained for 7 years for compliance. Which S3 storage strategy is **MOST** cost-effective?

- A. Store all objects in S3 Standard for the entire 7 years
- B. Use S3 Intelligent-Tiering for all objects
- C. Use S3 Lifecycle policies to transition objects from S3 Standard to S3 Glacier after 30 days
- D. Store objects in S3 Standard-IA from day one

---

### Question 8 (Single Answer | Security)

A company's security policy requires that all S3 buckets must have server-side encryption enabled and no public access. Which AWS service can continuously monitor and alert when buckets are out of compliance?

- A. Amazon Inspector
- B. AWS Trusted Advisor
- C. AWS Config
- D. Amazon Macie

---

### Question 9 (Single Answer | Scenario | Compute)

A developer wants to run code in response to events such as changes in an S3 bucket or DynamoDB table updates WITHOUT managing any servers or infrastructure. Which AWS service should they use?

- A. Amazon EC2 with Auto Scaling
- B. AWS Elastic Beanstalk
- C. AWS Lambda
- D. Amazon ECS on EC2

---

### Question 10 (Single Answer | Scenario | Networking)

A global company wants to reduce latency for users worldwide accessing their static website hosted on S3. Which AWS service should they use?

- A. AWS Direct Connect
- B. Amazon Route 53 latency routing
- C. Amazon CloudFront
- D. AWS Global Accelerator

---

### Question 11 (Choose TWO | Security)

A company's security team needs to protect their web application from common web exploits like SQL injection and cross-site scripting (XSS). Which **TWO** AWS services should they implement?

- A. AWS WAF
- B. Amazon GuardDuty
- C. AWS Shield Standard
- D. AWS Shield Advanced
- E. Amazon Inspector

---

### Question 12 (Single Answer | Cloud Concepts)

What is the **MAIN** difference between fault tolerance and high availability in AWS?

- A. Fault tolerance means zero downtime with no performance degradation; high availability means minimal downtime with possible brief interruption
- B. High availability means zero downtime; fault tolerance allows for short outages
- C. Fault tolerance and high availability are the same concept
- D. Fault tolerance is only for databases; high availability applies to all services

---

### Question 13 (Single Answer | Billing)

A company wants to track its AWS spending and receive alerts when costs exceed a defined threshold. Which AWS service should they use?

- A. AWS Cost Explorer
- B. AWS Budgets
- C. AWS Pricing Calculator
- D. AWS Trusted Advisor

---

### Question 14 (Single Answer | Shared Responsibility | Security)

A company uses Amazon RDS for their database. Under the AWS Shared Responsibility Model, which of the following is the **CUSTOMER's** responsibility?

- A. Patching the underlying RDS database engine
- B. Managing the physical security of the data center hosting RDS
- C. Configuring database user access controls and managing data encryption
- D. Ensuring the availability of the RDS Multi-AZ failover infrastructure

---

### Question 15 (Single Answer | Networking)

A company needs a dedicated, private network connection from their on-premises data center to AWS with consistent network performance and reduced bandwidth costs. Which service meets this requirement?

- A. AWS VPN
- B. AWS Direct Connect
- C. Amazon VPC Peering
- D. AWS Transit Gateway

---

### Question 16 (Single Answer | Well-Architected)

A company wants to reduce their environmental footprint and improve sustainability of their AWS workloads. This aligns with which AWS Well-Architected Framework pillar?

- A. Cost Optimization
- B. Operational Excellence
- C. Sustainability
- D. Performance Efficiency

---

### Question 17 (Single Answer | Scenario | Database)

A company needs a fully managed, serverless NoSQL database that can handle millions of requests per second with single-digit millisecond latency and automatically scales to any size. Which AWS service should they use?

- A. Amazon RDS for MySQL
- B. Amazon Aurora
- C. Amazon DynamoDB
- D. Amazon Redshift

---

### Question 18 (Single Answer | Security)

A developer accidentally committed AWS access keys to a public GitHub repository. What should be the **FIRST** action to take?

- A. Contact GitHub to remove the file
- B. Rotate the access keys by creating new ones
- C. Immediately deactivate or delete the exposed access keys
- D. Enable MFA on the IAM user

---

### Question 19 (Single Answer | Scenario | Networking)

A company hosts a web application behind an Application Load Balancer (ALB). They want to route traffic to different backend services based on the URL path (/api vs /web). Which feature enables this?

- A. Target Group weighting
- B. Network Load Balancer protocol routing
- C. ALB path-based routing rules
- D. Route 53 weighted routing policy

---

### Question 20 (Choose THREE | Security)

A company wants to ensure their AWS environment follows a zero-trust security model. Which **THREE** services or features should they implement?

- A. IAM roles with least privilege policies
- B. Multi-factor authentication (MFA)
- C. Amazon S3 Transfer Acceleration
- D. AWS CloudTrail for API logging
- E. AWS Shield Standard
- F. VPC with private subnets and security groups

---

### Question 21 (Single Answer | Billing)

Which AWS tool provides recommendations to help reduce costs by identifying idle EC2 instances, underutilized Reserved Instances, and open security group rules?

- A. AWS Cost Explorer
- B. AWS Budgets
- C. AWS Trusted Advisor
- D. AWS Compute Optimizer

---

### Question 22 (Single Answer | Scenario | Compute)

A company needs to run a containerized batch processing workload that requires up to 10,000 vCPUs but only runs for 2 hours each night. They want MINIMAL infrastructure management. Which AWS service is **MOST** operationally efficient?

- A. Amazon EC2 On-Demand
- B. Amazon ECS on EC2
- C. AWS Fargate
- D. AWS Batch

---

### Question 23 (Single Answer | Security)

Which AWS service uses machine learning to automatically detect threats such as cryptocurrency mining, unusual API calls, and unauthorized data access in your AWS account?

- A. AWS Config
- B. Amazon Inspector
- C. Amazon GuardDuty
- D. AWS Security Hub

---

### Question 24 (Single Answer | Scenario | Networking)

A company needs to connect 50 VPCs across multiple AWS accounts and regions to their on-premises network through a single gateway. Which AWS service provides this hub-and-spoke connectivity with the **LEAST** administrative overhead?

- A. VPC Peering
- B. AWS Direct Connect
- C. AWS Transit Gateway
- D. Internet Gateway

---

### Question 25 (Single Answer | Well-Architected)

A company wants to design their AWS infrastructure so that if one Availability Zone fails, their application continues to function without manual intervention. Which Well-Architected pillar does this **BEST** represent?

- A. Performance Efficiency
- B. Operational Excellence
- C. Reliability
- D. Security

---

### Question 26 (Single Answer | Billing)

A company is migrating to AWS and wants to estimate the total cost of ownership (TCO) by comparing their on-premises infrastructure costs to AWS. Which tool should they use?

- A. AWS Pricing Calculator
- B. AWS Cost Explorer
- C. AWS Migration Hub
- D. AWS Migration Evaluator (formerly TCO Calculator)

---

### Question 27 (Choose TWO | Storage)

Which **TWO** S3 features can help prevent accidental deletion of critical data?

- A. S3 Versioning
- B. S3 Transfer Acceleration
- C. S3 Object Lock
- D. S3 Replication
- E. S3 Intelligent-Tiering

---

### Question 28 (Single Answer | Security)

A company needs to store and automatically rotate database credentials, API keys, and other secrets. Which AWS service is designed specifically for this purpose?

- A. AWS KMS
- B. AWS Systems Manager Parameter Store
- C. AWS Secrets Manager
- D. AWS Certificate Manager

---

### Question 29 (Single Answer | Scenario | Compute)

A company runs a CPU-intensive scientific simulation that needs to run for 48 hours continuously. The workload can be interrupted and restarted without data loss. Which EC2 purchasing option provides the **LOWEST** cost?

- A. On-Demand Instances
- B. Reserved Instances
- C. Spot Instances
- D. Dedicated Instances

---

### Question 30 (Single Answer | Scenario | Monitoring)

A company wants to track WHO made API calls in their AWS account, from WHICH IP address, and at WHAT time — for security auditing purposes. Which service provides this?

- A. Amazon CloudWatch
- B. AWS CloudTrail
- C. AWS Config
- D. Amazon VPC Flow Logs

---

### Question 31 (Single Answer | Well-Architected)

A company wants to avoid paying for resources they don't need and eliminate waste in their AWS environment. This is **PRIMARILY** addressed by which Well-Architected pillar?

- A. Reliability
- B. Sustainability
- C. Cost Optimization
- D. Operational Excellence

---

### Question 32 (Single Answer | Security)

A company must ensure that S3 objects containing sensitive data are encrypted **in transit**. Which feature enforces this?

- A. S3 Default Encryption
- B. An S3 Bucket Policy with a condition requiring `aws:SecureTransport`
- C. S3 Object Lock
- D. AWS KMS envelope encryption

---

### Question 33 (Single Answer | Scenario | Networking)

A company uses Amazon Route 53 for DNS. They want to route users to a secondary region automatically if the primary region becomes unhealthy. Which Route 53 routing policy should they use?

- A. Weighted routing
- B. Latency-based routing
- C. Failover routing
- D. Geolocation routing

---

### Question 34 (Choose TWO | Cloud Concepts)

Which **TWO** characteristics make cloud computing different from traditional on-premises computing?

- A. Massive economies of scale
- B. Fixed capacity and long procurement lead times
- C. Trade capital expense for variable expense
- D. Physical hardware ownership
- E. On-site IT staff required for all maintenance

---

### Question 35 (Single Answer | Scenario | Compute)

A web application experiences unpredictable traffic spikes. The company wants the application to automatically add EC2 instances during spikes and remove them when traffic decreases. Which service enables this?

- A. Amazon EC2 Auto Scaling
- B. AWS Elastic Load Balancing
- C. AWS CloudFormation
- D. Amazon ECS

---

### Question 36 (Single Answer | Shared Responsibility | Security)

According to the AWS Shared Responsibility Model, which of the following is **ALWAYS** AWS's responsibility?

- A. Configuring Security Groups and NACLs
- B. Managing IAM user permissions
- C. Physical security of the underlying data center hardware
- D. Encrypting customer data at rest

---

### Question 37 (Single Answer | Scenario | Storage)

A company needs to run a shared file system that can be simultaneously mounted by hundreds of Linux-based EC2 instances across multiple Availability Zones. Which AWS storage service should they use?

- A. Amazon EBS
- B. Amazon S3
- C. Amazon EFS
- D. AWS Storage Gateway

---

### Question 38 (Single Answer | Billing)

A company wants to reduce EC2 costs for a flexible workload that can commit to a consistent amount of compute usage (in $/hour) but wants flexibility across instance families and regions. Which option provides the **MOST** cost flexibility with significant savings?

- A. Standard Reserved Instances
- B. Convertible Reserved Instances
- C. Compute Savings Plans
- D. EC2 Instance Savings Plans

---

### Question 39 (Single Answer | Scenario | AI/ML)

A company wants to add a conversational chatbot to their customer service platform that can understand natural language and respond intelligently. Which AWS AI service should they use?

- A. Amazon Rekognition
- B. Amazon Comprehend
- C. Amazon Lex
- D. Amazon Polly

---

### Question 40 (Choose TWO | Networking | Security)

A company wants to control both inbound and outbound traffic at the subnet level AND at the individual EC2 instance level. Which **TWO** AWS network security features should they use?

- A. Security Groups
- B. Network Access Control Lists (NACLs)
- C. AWS WAF
- D. VPC Flow Logs
- E. Amazon Route 53 Resolver

---

### Question 41 (Single Answer | Well-Architected)

A company wants to use AWS services that best match their workload needs rather than over-provisioning "just in case." This is a core concept of which Well-Architected pillar?

- A. Cost Optimization
- B. Performance Efficiency
- C. Reliability
- D. Operational Excellence

---

### Question 42 (Single Answer | Security)

A company needs to federate identities from their corporate Active Directory to AWS so that employees can use their existing corporate credentials to access AWS resources. Which AWS service enables this?

- A. Amazon Cognito
- B. AWS IAM Identity Center (SSO)
- C. AWS Organizations
- D. Amazon Inspector

---

### Question 43 (Single Answer | Scenario | Database)

A company runs a MySQL database on Amazon RDS. They want to increase read throughput for a read-heavy application without affecting write performance. Which RDS feature should they use?

- A. RDS Multi-AZ deployment
- B. RDS Read Replicas
- C. RDS Automated Backups
- D. RDS Enhanced Monitoring

---

### Question 44 (Single Answer | Cloud Concepts)

A company is evaluating moving to AWS and is concerned about how quickly they can provision new servers compared to their on-premises process which takes weeks. In cloud computing, this rapid provisioning capability is called:

- A. Scalability
- B. Elasticity
- C. Agility
- D. Durability

---

### Question 45 (Single Answer | Scenario | Monitoring)

A company wants to create a dashboard that shows CPU utilization, memory usage, and custom application metrics from their EC2 instances in near real-time. Which AWS service should they use?

- A. AWS CloudTrail
- B. AWS Config
- C. Amazon CloudWatch
- D. AWS X-Ray

---

### Question 46 (Single Answer | Security)

A company wants to enforce a policy that ALL IAM users in their account must use MFA. Which is the **MOST** effective way to enforce this?

- A. Send an email reminder to all users
- B. Use AWS Config rule to detect non-MFA users
- C. Attach an IAM policy that denies all actions unless MFA is present
- D. Enable MFA on the root account only

---

### Question 47 (Choose TWO | Billing)

Which **TWO** AWS services are available at **NO** additional cost?

- A. Amazon EC2
- B. AWS CloudFormation
- C. Amazon S3
- D. Auto Scaling
- E. Amazon RDS

---

### Question 48 (Single Answer | Scenario | Networking)

A company's application in a private subnet needs to download software updates from the internet. Inbound connections from the internet should NOT be allowed. Which component enables this?

- A. Internet Gateway
- B. VPC Peering
- C. NAT Gateway
- D. Egress-Only Internet Gateway

---

### Question 49 (Choose TWO | Well-Architected)

Which **TWO** practices align with the Security pillar of the AWS Well-Architected Framework?

- A. Enabling CloudTrail in all regions
- B. Using Spot Instances for production workloads
- C. Implementing the principle of least privilege for IAM
- D. Rightsizing EC2 instances
- E. Using a single Availability Zone for all resources

---

### Question 50 (Single Answer | Scenario | Storage)

A large financial institution needs to migrate 100 TB of data from their on-premises data center to Amazon S3. Their internet connection is limited to 1 Gbps and they need the transfer completed within a week. Which service is **MOST** appropriate?

- A. AWS DataSync over the internet
- B. AWS Snowball Edge
- C. S3 Transfer Acceleration
- D. AWS Direct Connect

---

### Question 51 (Single Answer | Security)

A company stores sensitive customer PII data in S3 buckets. They need an automated service that can discover and alert them about S3 buckets containing sensitive data and identify data access anomalies. Which service is **BEST** suited?

- A. Amazon GuardDuty
- B. Amazon Macie
- C. AWS Config
- D. AWS Trusted Advisor

---

### Question 52 (Single Answer | Well-Architected)

A company uses AWS CloudFormation templates to deploy infrastructure. When a deployment fails, CloudFormation automatically rolls back to the previous state. This aligns with which Well-Architected design principle?

- A. Perform operations as code
- B. Anticipate failure
- C. Implement reversibility
- D. Manage change in automation

---

### Question 53 (Choose TWO | Compute)

A company is migrating virtual machines from on-premises to AWS. Which **TWO** compute services could they use to run their virtualized workloads?

- A. Amazon EC2
- B. Amazon S3
- C. AWS Lambda
- D. Amazon Lightsail
- E. Amazon DynamoDB

---

### Question 54 (Single Answer | Scenario | Networking)

A company's security policy requires that all traffic between their AWS VPC and their corporate on-premises data center must be encrypted. Which service meets this requirement with the **LEAST** implementation effort?

- A. AWS Direct Connect alone
- B. AWS Site-to-Site VPN
- C. VPC Peering
- D. AWS PrivateLink

---

### Question 55 (Single Answer | Billing)

A company has unpredictable workloads and wants to see a detailed breakdown of their AWS costs by service, region, linked account, and time period to identify spending trends. Which tool is **BEST** suited?

- A. AWS Budgets
- B. AWS Cost Explorer
- C. AWS Pricing Calculator
- D. AWS Billing Console overview

---

### Question 56 (Single Answer | Security)

A company wants to encrypt sensitive data stored in AWS services and needs complete control over the encryption keys, including the ability to revoke key access immediately. Which AWS service should they use?

- A. AWS CloudHSM
- B. AWS Certificate Manager
- C. AWS Key Management Service (KMS)
- D. S3 SSE-S3 (Server-Side Encryption with S3-Managed Keys)

---

### Question 57 (Choose TWO | Well-Architected)

Which **TWO** are best practices under the Reliability pillar of the AWS Well-Architected Framework?

- A. Automatically recover from failure
- B. Deploy in a single Availability Zone to reduce latency
- C. Test recovery procedures
- D. Store all backups only locally in the primary region
- E. Use On-Demand pricing for all workloads

---

### Question 58 (Single Answer | Cloud Concepts)

A company is using AWS and needs to understand the concept of "economies of scale." How does this benefit AWS customers?

- A. AWS provides free training and certification to all customers
- B. AWS aggregates usage across millions of customers, reducing per-unit infrastructure costs which are passed on as lower prices
- C. Customers receive free AWS credits based on usage volume
- D. AWS guarantees 100% uptime SLA for all services

---

### Question 59 (Single Answer | Security)

A company using AWS Organizations wants to prevent ANY account in a specific Organizational Unit (OU) from creating resources in any region outside of us-east-1 and eu-west-1. What should they use?

- A. IAM permission boundaries
- B. AWS Config rules
- C. Service Control Policies (SCPs)
- D. Resource-based policies

---

### Question 60 (Single Answer | Scenario | Networking)

A company wants to host a static website and needs a custom domain name (www.example.com) to point to their CloudFront distribution. Which AWS service handles domain registration and DNS management?

- A. Amazon CloudFront
- B. AWS Certificate Manager
- C. Amazon Route 53
- D. AWS Global Accelerator

---

### Question 61 (Choose TWO | AI/ML)

A company wants to build an application that can analyze customer feedback from reviews and automatically convert the audio from customer calls into text. Which **TWO** AWS AI services should they use?

- A. Amazon Comprehend
- B. Amazon Rekognition
- C. Amazon Transcribe
- D. Amazon Forecast
- E. Amazon Textract

---

### Question 62 (Single Answer | Well-Architected)

A company wants to reduce operational risk by deploying small, incremental changes to production instead of large, infrequent releases. This practice aligns with which Well-Architected design principle?

- A. Make large, comprehensive changes
- B. Make changes reversible by implementing small, reversible steps
- C. Anticipate failure by testing at production scale
- D. Stop guessing about capacity

---

### Question 63 (Choose THREE | Billing)

Which **THREE** pricing models are available for Amazon EC2 instances?

- A. On-Demand
- B. Reserved Instances
- C. Spot Instances
- D. Bulk Instances
- E. Serverless Instances
- F. Standard Instances

---

### Question 64 (Single Answer | Security)

A company uses multiple AWS services and wants a centralized view of security alerts, compliance status, and findings from Amazon GuardDuty, Amazon Inspector, and AWS Macie. Which service aggregates all these findings?

- A. AWS CloudTrail
- B. AWS Security Hub
- C. Amazon Detective
- D. AWS Config

---

### Question 65 (Single Answer | Scenario | Cloud Concepts)

A company is deciding between continuing to run their infrastructure on-premises or migrating to AWS. Their on-premises model requires them to purchase, rack, and manage servers that take 8 weeks to procure. In AWS, equivalent capacity can be provisioned in minutes. This AWS benefit is **BEST** described as:

- A. High Availability
- B. Durability
- C. Agility
- D. Economies of Scale

---

## SECTION 2 — Answer Key

| Q | Answer | Q | Answer | Q | Answer | Q | Answer | Q | Answer |
|---|--------|---|--------|---|--------|---|--------|---|--------|
| 1 | B | 14 | C | 27 | A, C | 40 | A, B | 53 | A, D |
| 2 | C | 15 | B | 28 | C | 41 | B | 54 | B |
| 3 | B | 16 | C | 29 | C | 42 | B | 55 | B |
| 4 | C | 17 | C | 30 | B | 43 | B | 56 | C |
| 5 | A, D | 18 | C | 31 | C | 44 | C | 57 | A, C |
| 6 | C | 19 | C | 32 | B | 45 | C | 58 | B |
| 7 | C | 20 | A, B, D | 33 | C | 46 | C | 59 | C |
| 8 | C | 21 | C | 34 | A, C | 47 | B, D | 60 | C |
| 9 | C | 22 | D | 35 | A | 48 | C | 61 | A, C |
| 10 | C | 23 | C | 36 | C | 49 | A, C | 62 | B |
| 11 | A, D | 24 | C | 37 | C | 50 | B | 63 | A, B, C |
| 12 | A | 25 | C | 38 | C | 51 | B | 64 | B |
| 13 | B | 26 | D | 39 | C | 52 | C | 65 | C |

---

## SECTION 3 — Detailed Explanations

---

### Q1 — Answer: B

**Why B is correct:** Elasticity allows resources to scale automatically based on demand, and the pay-as-you-go model eliminates upfront capital expenditure (CapEx). This directly addresses both concerns in the scenario.

**Why others are wrong:**
- **A:** High availability focuses on uptime and redundancy, not capital expense or scaling flexibility.
- **C:** Dedicated hardware ownership is the opposite — it implies owning servers, which is the traditional model.
- **D:** Fixed capacity planning is a characteristic of on-premises infrastructure, not cloud computing.

> **Exam Trap:** "Elasticity" and "scalability" are both valid cloud benefits, but elasticity specifically covers automatic scale-in AND scale-out based on demand, which matches the scenario better.

---

### Q2 — Answer: C

**Why C is correct:** AWS Organizations with SCPs allow central governance across multiple accounts. SCPs can explicitly deny actions like `cloudtrail:StopLogging` across all member accounts, overriding even account-level admin permissions.

**Why others are wrong:**
- **A:** IAM operates within a single account and cannot enforce policies across multiple accounts.
- **B:** AWS Config evaluates compliance but cannot enforce or prevent API calls.
- **D:** Security Hub aggregates findings but does not enforce preventive controls.

> **Exam Trap:** Confusing AWS Config (detective control) with SCPs (preventive control). SCPs are the only way to preventively block actions across all accounts in an OU.

---

### Q3 — Answer: B

**Why B is correct:** Public subnets (with Internet Gateway routes) host internet-facing web servers. Private subnets protect database servers from direct internet access. NAT Gateway enables outbound internet for private subnet resources (e.g., patching) without allowing inbound connections.

**Why others are wrong:**
- **A:** Placing databases in a public subnet exposes them directly to the internet — a critical security risk.
- **C:** Web servers in a private subnet cannot receive inbound internet requests, breaking the web application.
- **D:** Internet Gateways enable bidirectional traffic; using one for databases defeats the privacy goal.

> **Exam Trap:** Forgetting that NAT Gateway only allows outbound-initiated connections, not inbound from the internet.

---

### Q4 — Answer: C

**Why C is correct:** Reserved Instances with a 3-year, all-upfront commitment offer the highest discount (up to 72%) for steady-state, predictable workloads. All Upfront maximizes savings compared to Partial or No Upfront payment options.

**Why others are wrong:**
- **A:** On-Demand is the most expensive option, billed per hour/second with no commitment discount.
- **B:** Spot Instances offer high discounts but can be interrupted, making them unsuitable for critical 24/7 workloads.
- **D:** Dedicated Hosts are the most expensive option, used primarily for licensing compliance, not cost optimization.

> **Exam Trap:** Spot Instances seem very cheap, but the question says the workload runs "24/7" making reliability critical and ruling out interruptible Spot.

---

### Q5 — Answers: A, D

**Why A and D are correct:** MFA adds a critical second layer of authentication to the root account. Using IAM users/roles instead of root for daily tasks follows the principle of least privilege and AWS best practice — root should only be used for tasks that explicitly require it.

**Why others are wrong:**
- **B:** Creating root account access keys is strongly discouraged by AWS. Root keys are extremely powerful and dangerous if compromised.
- **C:** You cannot delete the root account — it is permanently tied to the AWS account.
- **E:** Sharing credentials of any kind violates security best practices.

> **Exam Trap:** Option B sounds like a legitimate operational need, but AWS explicitly warns against creating root access keys.

---

### Q6 — Answer: C

**Why C is correct:** Operational Excellence focuses on running and monitoring systems to deliver business value and continually improving processes. Automating responses to events and managing change carefully are core Operational Excellence practices.

**Why others are wrong:**
- **A:** Performance Efficiency is about using computing resources efficiently as demand changes.
- **B:** Cost Optimization focuses on avoiding unnecessary costs.
- **D:** Reliability focuses on ensuring a workload performs its intended function correctly and consistently.

---

### Q7 — Answer: C

**Why C is correct:** S3 Lifecycle policies automatically transition objects between storage classes. S3 Standard for first 30 days handles frequent access efficiently. After 30 days, Glacier provides extremely low-cost storage for the 7-year compliance retention period.

**Why others are wrong:**
- **A:** S3 Standard for 7 years wastes significant cost on data that is rarely accessed after day 30.
- **B:** Intelligent-Tiering incurs monitoring fees and may not be cheaper than direct Glacier for a known archival pattern.
- **D:** Standard-IA is for infrequent access but remains significantly more expensive than Glacier for long-term archives.

---

### Q8 — Answer: C

**Why C is correct:** AWS Config continuously monitors and records AWS resource configurations and evaluates them against desired configurations using managed or custom rules. It can detect and alert when S3 buckets violate encryption or public access policies.

**Why others are wrong:**
- **A:** Amazon Inspector assesses EC2 instances and container images for vulnerabilities, not S3 configuration compliance.
- **B:** Trusted Advisor provides periodic best-practice checks, not continuous real-time compliance monitoring.
- **D:** Amazon Macie focuses on discovering and protecting sensitive data (PII) in S3, not configuration compliance.

> **Exam Trap:** Macie sounds relevant because it involves S3, but it classifies data content — not resource configuration.

---

### Q9 — Answer: C

**Why C is correct:** AWS Lambda is a serverless compute service that runs code in response to events without provisioning or managing servers. S3 and DynamoDB are native Lambda trigger sources.

**Why others are wrong:**
- **A:** EC2 with Auto Scaling still requires managing and provisioning server infrastructure.
- **B:** Elastic Beanstalk manages deployment and scaling but still provisions underlying EC2 instances.
- **D:** ECS on EC2 requires managing the underlying EC2 container host instances.

---

### Q10 — Answer: C

**Why C is correct:** Amazon CloudFront is a Content Delivery Network (CDN) that caches content at edge locations worldwide, dramatically reducing latency for static content like websites, images, and videos hosted on S3.

**Why others are wrong:**
- **A:** Direct Connect provides dedicated private connectivity from on-premises to AWS, not global content delivery.
- **B:** Route 53 latency routing routes users to the closest AWS region but doesn't cache content.
- **D:** Global Accelerator improves performance of dynamic applications through the AWS network but is not the standard answer for static website CDN use cases.

---

### Q11 — Answers: A, D

**Why A and D are correct:** AWS WAF filters HTTP requests and blocks SQL injection, XSS, and other web exploits using customizable rules. AWS Shield Advanced provides enhanced DDoS protection and integrates with WAF for comprehensive protection.

**Why others are wrong:**
- **B:** GuardDuty is a threat detection service — it identifies unusual behavior but does not block web exploits.
- **C:** Shield Standard only protects against volumetric DDoS attacks, not application-layer web exploits.
- **E:** Inspector assesses EC2 and container vulnerabilities, not web application exploits.

---

### Q12 — Answer: A

**Why A is correct:** Fault tolerance means a system continues operating without degradation even when components fail (zero downtime, zero performance loss). High availability minimizes downtime (e.g., 99.99% uptime) but may allow brief failover periods.

**Why others are wrong:**
- **B:** This reverses the definitions. Fault tolerance provides the stronger guarantee.
- **C:** They are related but distinct concepts with different SLA guarantees.
- **D:** Both concepts apply to all system types.

---

### Q13 — Answer: B

**Why B is correct:** AWS Budgets allows you to set custom cost, usage, savings plans, and reservation budgets and receive alerts via SNS or email when thresholds are breached.

**Why others are wrong:**
- **A:** Cost Explorer visualizes and analyzes past spending patterns but does not send threshold alerts.
- **C:** Pricing Calculator estimates costs before deployment — it has no runtime monitoring capability.
- **D:** Trusted Advisor gives best-practice recommendations; its cost checks are not real-time budget alerts.

---

### Q14 — Answer: C

**Why C is correct:** For managed services like RDS, AWS manages the OS, engine patching, and underlying infrastructure. The customer is responsible for database-level security: user accounts, permissions, and enabling/configuring encryption (via KMS).

**Why others are wrong:**
- **A:** AWS patches the RDS database engine — this is a key benefit of managed services.
- **B:** Physical security of all data centers is entirely AWS's responsibility.
- **D:** Multi-AZ infrastructure is managed and maintained by AWS.

> **Exam Trap:** The Shared Responsibility Model shifts based on service type. For managed services (RDS, Lambda), AWS takes on more responsibility than for unmanaged (EC2).

---

### Q15 — Answer: B

**Why B is correct:** AWS Direct Connect provides a dedicated physical fiber connection from your data center to AWS, offering consistent latency, higher bandwidth, and lower data transfer costs compared to internet-based connections.

**Why others are wrong:**
- **A:** VPN uses the public internet with encryption — it can have variable latency and is not dedicated bandwidth.
- **C:** VPC Peering connects two VPCs within AWS, not on-premises networks to AWS.
- **D:** Transit Gateway connects multiple VPCs and on-premises networks but requires an underlying connection method (Direct Connect or VPN).

---

### Q16 — Answer: C

**Why C is correct:** The Sustainability pillar (the 6th pillar, added in 2021) focuses on minimizing the environmental impact of running cloud workloads, including using efficient instance types, rightsizing, and reducing carbon footprint.

**Why others are wrong:**
- **A:** Cost Optimization focuses on financial efficiency, not environmental impact (though they often align).
- **B:** Operational Excellence is about running and improving operations, not sustainability.
- **D:** Performance Efficiency is about matching resources to performance needs — not specifically environmental impact.

> **Exam Trap:** Sustainability was added in 2021 and is frequently tested as a "new" pillar. Don't confuse it with Cost Optimization.

---

### Q17 — Answer: C

**Why C is correct:** DynamoDB is a fully managed, serverless NoSQL key-value and document database that delivers single-digit millisecond performance at any scale with automatic capacity scaling.

**Why others are wrong:**
- **A:** RDS for MySQL is a relational database — it doesn't auto-scale compute and requires instance management.
- **B:** Aurora is a high-performance relational database, not a NoSQL solution.
- **D:** Redshift is a data warehousing service optimized for analytics, not high-throughput transactional workloads.

---

### Q18 — Answer: C

**Why C is correct:** The first priority is to immediately deactivate or delete the compromised access keys to stop any unauthorized usage. Attackers continuously scan GitHub and may have already used the keys.

**Why others are wrong:**
- **A:** Removing from GitHub should happen but is not the first step — the keys must be invalidated immediately.
- **B:** Creating new keys doesn't help unless the old compromised keys are first deactivated.
- **D:** Enabling MFA is good practice but doesn't address the immediately compromised access keys.

---

### Q19 — Answer: C

**Why C is correct:** ALB supports content-based routing (path-based routing) that directs requests to specific target groups based on the URL path (e.g., `/api/*` to one target group, `/web/*` to another).

**Why others are wrong:**
- **A:** Target group weighting distributes traffic between groups by percentage, not by URL path.
- **B:** NLB operates at Layer 4 (TCP/UDP) and cannot inspect URL paths.
- **D:** Route 53 routing policies operate at the DNS level and cannot inspect individual URL request paths.

---

### Q20 — Answers: A, B, D

**Why A, B, and D are correct:** Zero-trust requires verifying identity (MFA), granting minimal permissions (least privilege IAM), and logging all actions (CloudTrail) for complete auditability and traceability.

**Why others are wrong:**
- **C:** S3 Transfer Acceleration improves upload speeds using CloudFront edge locations — it's a performance feature.
- **E:** Shield Standard protects against DDoS but is not a zero-trust identity or access control mechanism.
- **F:** VPC segmentation provides valuable network security but doesn't directly implement zero-trust identity verification.

---

### Q21 — Answer: C

**Why C is correct:** AWS Trusted Advisor scans your environment and provides recommendations across five categories: Cost Optimization, Security, Fault Tolerance, Performance, and Service Limits — including idle EC2 instances and underutilized Reserved Instances.

**Why others are wrong:**
- **A:** Cost Explorer analyzes spending trends and forecasts costs but doesn't scan infrastructure for optimization.
- **B:** AWS Budgets tracks spending against thresholds but doesn't provide resource recommendations.
- **D:** Compute Optimizer recommends optimal configurations for EC2, Lambda, and EBS but doesn't cover security or fault tolerance.

---

### Q22 — Answer: D

**Why D is correct:** AWS Batch is a fully managed service that dynamically provisions compute resources and plans, schedules, and runs batch workloads at any scale. It eliminates all server management and is ideal for large-scale, ephemeral batch jobs.

**Why others are wrong:**
- **A:** EC2 On-Demand requires manual provisioning and management of all instances.
- **B:** ECS on EC2 requires managing the underlying EC2 container host infrastructure.
- **C:** Fargate runs containers without managing servers but lacks the job scheduling and queue management that AWS Batch provides natively.

---

### Q23 — Answer: C

**Why C is correct:** Amazon GuardDuty is a managed threat detection service that uses ML, anomaly detection, and threat intelligence to identify threats like cryptomining, account compromise, and unusual API activity by analyzing CloudTrail, VPC Flow Logs, and DNS logs.

**Why others are wrong:**
- **A:** Config monitors resource configuration compliance — it doesn't detect behavioral threats.
- **B:** Inspector assesses vulnerabilities in EC2 instances and container images, not behavioral anomalies.
- **D:** Security Hub aggregates findings from GuardDuty and others but doesn't generate threat detections itself.

---

### Q24 — Answer: C

**Why C is correct:** AWS Transit Gateway acts as a cloud router/network hub, connecting thousands of VPCs and on-premises networks through a single managed gateway, dramatically reducing connectivity complexity.

**Why others are wrong:**
- **A:** VPC Peering is non-transitive and requires n*(n-1)/2 connections for 50 VPCs — unmanageable at scale.
- **B:** Direct Connect is the physical connection method, not a routing hub for multiple VPCs.
- **D:** Internet Gateway is for public internet access, not inter-VPC or on-premises connectivity.

---

### Q25 — Answer: C

**Why C is correct:** The Reliability pillar focuses on the ability of a workload to perform its intended function correctly and consistently. Designing for AZ failure through Multi-AZ deployments and automatic failover is a core Reliability practice.

**Why others are wrong:**
- **A:** Performance Efficiency is about efficient resource usage, not fault tolerance.
- **B:** Operational Excellence is about operational processes and procedures.
- **D:** Security is about protecting data and systems, not infrastructure resilience.

---

### Q26 — Answer: D

**Why D is correct:** AWS Migration Evaluator (formerly TCO Calculator) helps organizations build a business case for cloud migration by comparing on-premises costs (hardware, facilities, staff) against projected AWS costs.

**Why others are wrong:**
- **A:** Pricing Calculator estimates AWS service costs but doesn't model or compare against on-premises costs.
- **B:** Cost Explorer analyzes existing AWS spending — it cannot model on-premises scenarios.
- **C:** Migration Hub tracks migration progress but doesn't generate TCO financial comparisons.

---

### Q27 — Answers: A, C

**Why A and C are correct:** S3 Versioning retains all versions of objects, so a delete marker doesn't permanently remove older versions. S3 Object Lock (WORM) prevents objects from being deleted or overwritten for a specified retention period.

**Why others are wrong:**
- **B:** Transfer Acceleration improves upload speed using CloudFront — it has no data protection function.
- **D:** S3 Replication copies objects to another bucket but doesn't prevent deletion of the source.
- **E:** Intelligent-Tiering moves data between storage tiers for cost savings — it doesn't prevent deletion.

---

### Q28 — Answer: C

**Why C is correct:** AWS Secrets Manager is designed specifically to store, retrieve, and automatically rotate secrets like database credentials and API keys. It integrates natively with RDS, Redshift, and DocumentDB for automatic rotation.

**Why others are wrong:**
- **A:** KMS manages encryption keys, not application secrets or credentials.
- **B:** Parameter Store can store secrets but does NOT natively support automatic rotation without custom Lambda functions.
- **D:** Certificate Manager manages SSL/TLS certificates, not application secrets.

> **Exam Trap:** Parameter Store vs Secrets Manager — both store secrets but Secrets Manager provides AUTOMATIC rotation natively.

---

### Q29 — Answer: C

**Why C is correct:** Spot Instances offer up to 90% discount over On-Demand. Since the scientific workload can checkpoint and restart (fault-tolerant), it can tolerate interruptions, making Spot the best cost choice.

**Why others are wrong:**
- **A:** On-Demand is the most expensive option for long-running workloads with no commitment.
- **B:** Reserved Instances require 1- or 3-year commitments — not optimal for intermittent workloads.
- **D:** Dedicated Instances are the most expensive option and are used for licensing compliance.

---

### Q30 — Answer: B

**Why B is correct:** AWS CloudTrail records all API calls made to AWS services, capturing: who made the call (IAM user/role), what action was taken, when it occurred, from which IP address, and the request/response details.

**Why others are wrong:**
- **A:** CloudWatch monitors performance metrics and application logs — it does not track API call history.
- **C:** Config tracks resource configuration changes over time — it uses CloudTrail data but focuses on configuration state.
- **D:** VPC Flow Logs capture network traffic at the ENI level, not API-level audit trails.

---

### Q31 — Answer: C

**Why C is correct:** Cost Optimization focuses on avoiding unnecessary costs, identifying underutilized resources, rightsizing instances, and selecting appropriate pricing models.

**Why others are wrong:**
- **A:** Reliability focuses on maintaining functionality and recovering from failures.
- **B:** Sustainability focuses on environmental impact reduction.
- **D:** Operational Excellence focuses on running operations effectively, not cost reduction.

---

### Q32 — Answer: B

**Why B is correct:** A bucket policy with the condition key `aws:SecureTransport: false` set to `Deny` ensures all requests must use HTTPS/TLS. Without this policy, S3 accepts both HTTP and HTTPS requests.

**Why others are wrong:**
- **A:** Default encryption encrypts data at rest — not data in transit.
- **C:** Object Lock prevents deletion and modification — it does not enforce transport security.
- **D:** KMS envelope encryption is a data-at-rest encryption method, not for securing data in transit.

---

### Q33 — Answer: C

**Why C is correct:** Route 53 Failover routing automatically redirects traffic from a primary endpoint to a secondary endpoint when health checks detect the primary is unhealthy — this is the active-passive failover pattern.

**Why others are wrong:**
- **A:** Weighted routing distributes traffic by percentage — it does not react to health checks for failover.
- **B:** Latency routing sends traffic to the lowest-latency region — not based on health status.
- **D:** Geolocation routing is based on user geographic location, not endpoint health.

---

### Q34 — Answers: A, C

**Why A and C are correct:** Cloud providers achieve massive economies of scale by aggregating usage across millions of customers, lowering per-unit costs. Cloud also converts CapEx (buying servers) to OpEx (paying per usage).

**Why others are wrong:**
- **B:** Long procurement and fixed capacity are on-premises limitations, not cloud benefits.
- **D:** Physical hardware ownership is an on-premises model — cloud abstracts it away.
- **E:** On-site IT staff is required for on-premises — cloud reduces this overhead.

---

### Q35 — Answer: A

**Why A is correct:** EC2 Auto Scaling automatically adjusts the number of instances in a group based on demand using scaling policies triggered by CloudWatch metrics.

**Why others are wrong:**
- **B:** ELB distributes traffic across existing instances — it does not add or remove instances.
- **C:** CloudFormation provisions infrastructure as code — it doesn't scale dynamically based on demand.
- **D:** ECS orchestrates containers but doesn't automatically scale the underlying EC2 fleet without Auto Scaling.

---

### Q36 — Answer: C

**Why C is correct:** Physical security of all AWS global infrastructure (data centers, hardware, networking equipment) is always and entirely AWS's responsibility, regardless of which service the customer uses.

**Why others are wrong:**
- **A:** Security Groups and NACLs are customer-managed network controls.
- **B:** IAM user permissions are entirely managed by the customer.
- **D:** Encrypting data at rest is shared — AWS provides tools (KMS), but the customer must enable and configure it.

---

### Q37 — Answer: C

**Why C is correct:** Amazon EFS is a fully managed, elastic NFS file system that can be concurrently accessed by thousands of EC2 instances across multiple AZs in a region, making it ideal for shared file workloads.

**Why others are wrong:**
- **A:** EBS volumes can only be attached to a single EC2 instance at a time (with very limited multi-attach exceptions).
- **B:** S3 is object storage — it is not a POSIX-compliant file system and cannot be mounted like a network share.
- **D:** Storage Gateway connects on-premises environments to AWS storage — not for EC2-to-EC2 shared access.

---

### Q38 — Answer: C

**Why C is correct:** Compute Savings Plans offer up to 66% savings and provide the most flexibility — automatically applying to any EC2 instance family, size, OS, and region, as well as Lambda and Fargate usage.

**Why others are wrong:**
- **A:** Standard RIs give the highest EC2 discount but are locked to a specific instance family, size, and region.
- **B:** Convertible RIs allow instance family changes but offer less discount than Compute Savings Plans.
- **D:** EC2 Instance Savings Plans are more restrictive — they apply to a specific instance family in a chosen region only.

---

### Q39 — Answer: C

**Why C is correct:** Amazon Lex is the service powering conversational interfaces (chatbots) using natural language understanding (NLU) and automatic speech recognition — the same technology behind Alexa.

**Why others are wrong:**
- **A:** Rekognition provides computer vision capabilities for image and video analysis.
- **B:** Comprehend is an NLP service for analyzing existing text (sentiment, entities) — it doesn't build conversational interfaces.
- **D:** Polly converts text to speech — it can give a chatbot a voice but doesn't handle conversation logic.

---

### Q40 — Answers: A, B

**Why A and B are correct:** Security Groups act as stateful firewalls at the instance/ENI level. NACLs are stateless and operate at the subnet level, controlling inbound and outbound traffic independently.

**Why others are wrong:**
- **C:** WAF operates at the application (HTTP) layer to filter web requests — not at the subnet or instance network level.
- **D:** VPC Flow Logs capture traffic data for monitoring and auditing — they don't control or filter traffic.
- **E:** Route 53 Resolver handles DNS resolution — it doesn't control network traffic flow.

> **Exam Trap:** Security Groups vs NACLs — Security Groups are STATEFUL (return traffic automatically allowed); NACLs are STATELESS (both inbound and outbound rules must explicitly allow return traffic).

---

### Q41 — Answer: B

**Why B is correct:** Performance Efficiency focuses on using computing resources efficiently to meet system requirements and maintaining efficiency as demand changes — which includes selecting the right resource type and size for each workload.

**Why others are wrong:**
- **A:** Cost Optimization overlaps but focuses on the financial side — Performance Efficiency is about matching resources to performance needs.
- **C:** Reliability focuses on maintaining functionality under failure conditions.
- **D:** Operational Excellence is about running and improving operational processes.

---

### Q42 — Answer: B

**Why B is correct:** AWS IAM Identity Center (formerly AWS SSO) enables centralized identity federation. It integrates with Active Directory and allows employees to use existing corporate credentials to access multiple AWS accounts.

**Why others are wrong:**
- **A:** Cognito is designed for customer-facing identity in web and mobile applications — not corporate employee federation.
- **C:** Organizations manages multiple AWS accounts but doesn't provide identity federation.
- **D:** Inspector is a vulnerability assessment service, not an identity tool.

---

### Q43 — Answer: B

**Why B is correct:** RDS Read Replicas create asynchronous read-only copies of the database that can handle read traffic, offloading the primary instance and improving read throughput for read-heavy applications.

**Why others are wrong:**
- **A:** Multi-AZ provides high availability through synchronous standby replication — the standby does NOT serve read traffic.
- **C:** Automated Backups protect data but don't scale read performance.
- **D:** Enhanced Monitoring provides detailed OS metrics — it has no impact on read throughput.

> **Exam Trap:** Multi-AZ vs Read Replicas — Multi-AZ is for HIGH AVAILABILITY (automatic failover). Read Replicas are for READ SCALING (performance). The standby in Multi-AZ is not accessible for reads.

---

### Q44 — Answer: C

**Why C is correct:** Agility in cloud computing refers to the dramatically reduced time it takes to provision and deploy resources (minutes vs weeks on-premises), allowing companies to innovate faster.

**Why others are wrong:**
- **A:** Scalability refers to handling growing workloads by adding resources.
- **B:** Elasticity is automatic scale-in and scale-out based on demand.
- **D:** Durability refers to data protection and longevity (e.g., S3's 11 nines durability).

---

### Q45 — Answer: C

**Why C is correct:** Amazon CloudWatch collects monitoring and observability data (metrics, logs, events) from AWS services and custom applications. It supports custom dashboards, alarms, and automated responses.

**Why others are wrong:**
- **A:** CloudTrail records API calls for auditing, not performance metrics.
- **B:** Config tracks resource configuration state over time, not performance metrics.
- **D:** X-Ray provides distributed tracing for application debugging — not a general performance metrics dashboard.

---

### Q46 — Answer: C

**Why C is correct:** Attaching an IAM policy with a `Deny` on all actions when `aws:MultiFactorAuthPresent` is `false` effectively blocks ALL actions for users without MFA — enforcing MFA at the permission level programmatically.

**Why others are wrong:**
- **A:** Email reminders are non-technical controls that can be ignored.
- **B:** Config can detect non-MFA users but reports rather than prevents access.
- **D:** Enabling MFA only on root doesn't protect separate IAM users.

---

### Q47 — Answers: B, D

**Why B and D are correct:** AWS CloudFormation and Auto Scaling are free services — you only pay for the AWS resources they create or manage (e.g., EC2 instances, EBS volumes, etc.).

**Why others are wrong:**
- **A:** EC2 charges per instance-hour based on instance type and purchasing option.
- **C:** S3 charges for storage (per GB), requests, and data transfer.
- **E:** RDS charges for DB instance hours, storage, and I/O.

---

### Q48 — Answer: C

**Why C is correct:** A NAT Gateway allows instances in private subnets to initiate outbound connections to the internet (for updates, patches) while preventing the internet from initiating inbound connections to those instances.

**Why others are wrong:**
- **A:** An Internet Gateway allows bidirectional traffic — it also allows inbound connections from the internet.
- **B:** VPC Peering connects two VPCs together — it doesn't provide internet access.
- **D:** Egress-Only Internet Gateway is specifically for IPv6 traffic only — not IPv4.

---

### Q49 — Answers: A, C

**Why A and C are correct:** CloudTrail logging (traceability) and least privilege IAM (protecting access) are both foundational Security pillar practices in the Well-Architected Framework.

**Why others are wrong:**
- **B:** Spot Instances are a cost optimization strategy — unreliable for production workloads.
- **D:** Rightsizing is a Cost Optimization practice.
- **E:** Single AZ deployment reduces reliability — it's contrary to best practices.

---

### Q50 — Answer: B

**Why B is correct:** At 1 Gbps theoretical maximum, transferring 100 TB over the internet would take approximately 9 days — exceeding the one-week deadline. AWS Snowball Edge is a physical appliance that ships data to AWS without relying on network bandwidth.

**Why others are wrong:**
- **A:** DataSync over 1 Gbps internet would take too long and is unreliable at this scale.
- **C:** Transfer Acceleration improves internet upload speeds but still depends on available bandwidth.
- **D:** Direct Connect takes weeks to provision — it's not a rapid data migration solution.

---

### Q51 — Answer: B

**Why B is correct:** Amazon Macie uses ML to automatically discover, classify, and protect sensitive data in S3, including PII. It alerts on buckets containing sensitive data and detects anomalous access patterns.

**Why others are wrong:**
- **A:** GuardDuty detects threats like account compromise and cryptomining but doesn't classify PII data in S3.
- **C:** Config tracks resource configuration — it doesn't classify data content.
- **D:** Trusted Advisor checks bucket permissions but doesn't classify data content for PII.

---

### Q52 — Answer: C

**Why C is correct:** "Implement reversibility" (make changes reversible) is a design principle of the Operational Excellence pillar. Rollback capability ensures changes can be undone quickly, minimizing impact of failed deployments.

**Why others are wrong:**
- **A:** Performing operations as code refers to using templates rather than manual processes — related but not specific to rollback.
- **B:** Anticipating failure is a Reliability principle.
- **D:** Managing change in automation refers to deploying small, frequent changes safely — related but the rollback specifically reflects reversibility.

---

### Q53 — Answers: A, D

**Why A and D are correct:** EC2 provides full virtual machine instances equivalent to on-premises VMs. Amazon Lightsail provides simple virtual private servers (a simplified EC2 experience) suitable for straightforward VM migrations.

**Why others are wrong:**
- **B:** S3 is object storage, not a compute service for running VMs.
- **C:** Lambda is serverless event-driven compute — it runs functions, not virtual machines.
- **E:** DynamoDB is a NoSQL database, not a compute service.

---

### Q54 — Answer: B

**Why B is correct:** AWS Site-to-Site VPN establishes an encrypted IPsec tunnel over the internet between a VPC and an on-premises network. Encryption is built-in by design and can be configured in minutes.

**Why others are wrong:**
- **A:** Direct Connect alone provides a dedicated private connection but traffic is NOT encrypted by default.
- **C:** VPC Peering connects two VPCs within AWS — it cannot connect to on-premises networks.
- **D:** PrivateLink provides private connectivity for AWS services within the AWS network — not for on-premises connectivity.

> **Exam Trap:** Direct Connect is private (uses dedicated fiber) but is NOT encrypted. You need VPN over Direct Connect for encryption.

---

### Q55 — Answer: B

**Why B is correct:** AWS Cost Explorer provides an interactive interface to visualize, understand, and manage AWS costs. It allows filtering by service, region, linked account, tags, and time period with granularity down to daily or hourly usage.

**Why others are wrong:**
- **A:** AWS Budgets is for setting spending thresholds and alerts — not for detailed cost analysis and trend visualization.
- **C:** Pricing Calculator estimates future costs for planned architectures — it doesn't analyze existing billing.
- **D:** The Billing Console overview shows aggregate totals — it lacks the filtering, grouping, and trend analysis of Cost Explorer.

---

### Q56 — Answer: C

**Why C is correct:** AWS KMS with Customer Managed Keys (CMKs) gives you full control over encryption keys, including the ability to disable or delete keys immediately, effectively revoking access to all data encrypted with those keys.

**Why others are wrong:**
- **A:** CloudHSM provides dedicated hardware security modules for maximum control but requires significantly more management overhead — not the first-choice answer for general key control.
- **B:** Certificate Manager manages SSL/TLS certificates, not general-purpose encryption keys.
- **D:** SSE-S3 uses keys managed entirely by AWS — customers have no control over those keys.

---

### Q57 — Answers: A, C

**Why A and C are correct:** Automatic recovery (using health checks, Auto Scaling, and Multi-AZ failover) and testing recovery procedures (to validate that mechanisms actually work) are both core Reliability pillar practices.

**Why others are wrong:**
- **B:** Single AZ deployment creates a single point of failure — contrary to Reliability best practices.
- **D:** Storing backups only in the primary region risks losing them if the region fails — cross-region backup is recommended.
- **E:** Pricing models are a Cost Optimization concern, not Reliability.

---

### Q58 — Answer: B

**Why B is correct:** Economies of scale means that as AWS grows its massive customer base and infrastructure, it can reduce per-unit costs through aggregated purchasing power and operational efficiency, passing savings to customers as lower prices over time.

**Why others are wrong:**
- **A:** AWS offers training resources but this is separate from economies of scale.
- **C:** Credits exist in some programs but are not the definition of economies of scale.
- **D:** No AWS service guarantees 100% uptime — SLAs vary by service.

---

### Q59 — Answer: C

**Why C is correct:** Service Control Policies in AWS Organizations are the only control that can restrict entire OUs and accounts from taking actions in specific regions. They serve as guardrails that override all account-level IAM permissions.

**Why others are wrong:**
- **A:** Permission boundaries limit maximum IAM permissions within a single account — they cannot be applied across accounts in an OU.
- **B:** Config rules evaluate compliance but cannot preventively block API actions.
- **D:** Resource-based policies are attached to individual resources — they cannot enforce organization-wide regional restrictions.

---

### Q60 — Answer: C

**Why C is correct:** Amazon Route 53 is AWS's scalable DNS and domain name registration service. It can register domain names and create DNS records (Alias or CNAME) that point to CloudFront distributions.

**Why others are wrong:**
- **A:** CloudFront is the CDN that serves content — it doesn't manage DNS or domain registration.
- **B:** ACM provides SSL/TLS certificates — it cannot register domains or manage DNS records.
- **D:** Global Accelerator uses static anycast IPs to accelerate traffic — it doesn't handle domain registration or DNS.

---

### Q61 — Answers: A, C

**Why A and C are correct:** Amazon Comprehend performs NLP on text to extract sentiment, entities, and key phrases from customer reviews. Amazon Transcribe converts speech (audio) to text from customer call recordings.

**Why others are wrong:**
- **B:** Rekognition analyzes images and video — not text sentiment or audio.
- **D:** Forecast is a time-series forecasting service for business metrics — not for speech or text analysis.
- **E:** Textract extracts text from scanned documents and images — not from audio recordings.

---

### Q62 — Answer: B

**Why B is correct:** "Make small, reversible changes" is a core Operational Excellence pillar principle. Frequent, small deployments reduce the blast radius of failures and allow faster rollback when something goes wrong.

**Why others are wrong:**
- **A:** Large, comprehensive changes are the anti-pattern that this principle is specifically designed to avoid.
- **C:** Anticipating failure is a Reliability principle involving testing for failures, not about deployment size.
- **D:** Stopping guessing at capacity is a Performance Efficiency principle.

---

### Q63 — Answers: A, B, C

**Why A, B, and C are correct:** On-Demand (pay per second/hour, no commitment), Reserved Instances (1 or 3-year commitment for discounts), and Spot Instances (bid on unused capacity for up to 90% savings) are the three core EC2 purchasing models.

**Why others are wrong:**
- **D:** "Bulk Instances" is not an AWS EC2 pricing model.
- **E:** "Serverless Instances" is not a real option — Lambda is serverless, EC2 always requires provisioning.
- **F:** "Standard Instances" is not a pricing model — it refers to a sub-type within the Reserved Instance model.

---

### Q64 — Answer: B

**Why B is correct:** AWS Security Hub provides a centralized dashboard that aggregates, organizes, and prioritizes security findings from multiple AWS services including GuardDuty, Inspector, and Macie — giving a unified view of your security posture.

**Why others are wrong:**
- **A:** CloudTrail provides API logs for auditing — it doesn't aggregate security findings from other services.
- **C:** Amazon Detective analyzes and investigates security findings for root cause analysis — it's for deep investigation after a finding, not aggregation.
- **D:** Config tracks resource configurations — it doesn't aggregate findings from GuardDuty, Inspector, or Macie.

---

### Q65 — Answer: C

**Why C is correct:** Agility refers to the dramatically reduced time it takes to provision and experiment with new resources in the cloud (minutes vs weeks on-premises), allowing companies to innovate faster and respond to market changes.

**Why others are wrong:**
- **A:** High Availability refers to minimizing downtime through redundancy — not provisioning speed.
- **B:** Durability refers to data longevity and protection from loss (e.g., S3's eleven 9s of durability).
- **D:** Economies of Scale refers to cost benefits from massive aggregated purchasing power — not provisioning speed.

---

*Good luck on your AWS Certified Cloud Practitioner exam!*
*Pass score: 700/1000 — roughly 70% correct.*
