# AWS Certified Cloud Practitioner (CLF-C02) — Full Mock Exam

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

A company is evaluating moving from an on-premises data center to AWS. Which benefit of AWS Cloud allows the company to avoid paying for unused capacity while still handling sudden increases in demand?

- A. High availability
- B. Fault tolerance
- C. Elasticity
- D. Reliability

---

**Question 5** *(Choose ONE)*

A company wants to ensure their architecture can automatically recover from infrastructure failures without human intervention. Which AWS Well-Architected Framework pillar BEST addresses this requirement?

- A. Operational Excellence
- B. Performance Efficiency
- C. Reliability
- D. Cost Optimization

---

**Question 16** *(Choose ONE)*

A company is planning to move to AWS and wants to compare the TOTAL cost of running infrastructure on-premises versus on AWS over a 5-year period. Which AWS tool should they use FIRST?

- A. AWS Pricing Calculator
- B. AWS Cost Explorer
- C. AWS Migration Evaluator (TCO Calculator)
- D. AWS Trusted Advisor

---

**Question 25** *(Choose ONE)*

A company is migrating from a capital expenditure (CapEx) model to an operational expenditure (OpEx) model. Which characteristic of AWS Cloud computing BEST describes this benefit?

- A. Going global in minutes
- B. Trading fixed expenses for variable expenses
- C. Increasing speed and agility
- D. Benefiting from massive economies of scale

---

**Question 36** *(Choose THREE)*

Which of the following are benefits of cloud computing compared to traditional on-premises infrastructure?

- A. Increased capital expenditure for hardware
- B. Faster time to deploy new applications and services
- C. Access to a broad set of global infrastructure in minutes
- D. Elimination of all IT staff requirements
- E. Ability to scale resources up or down on demand

---

**Question 43** *(Choose ONE)*

Which AWS service allows customers to run AWS infrastructure and services on-premises, providing a consistent hybrid cloud experience?

- A. AWS Direct Connect
- B. AWS Snowball Edge
- C. AWS Outposts
- D. AWS Local Zones

---

**Question 49** *(Choose ONE)*

A company wants to use AWS services to quickly experiment with new ideas, fail fast, and iterate without large upfront investments. Which cloud benefit does this BEST describe?

- A. Elasticity
- B. Economy of scale
- C. Agility
- D. High availability

---

**Question 57** *(Choose ONE)*

A company wants to deploy their application to AWS infrastructure that is physically separate from other customers to meet strict compliance requirements, while still using standard EC2 instances. Which EC2 tenancy option should they choose?

- A. Default (shared) tenancy
- B. Dedicated Instances
- C. Dedicated Hosts
- D. Spot Instances

---

**Question 61** *(Choose ONE)*

Which of the following BEST describes the concept of "fault tolerance" in AWS Cloud architecture?

- A. The ability to scale resources up and down based on demand
- B. The ability to continue operating properly in the event of the failure of one or more components
- C. The ability to deploy applications globally across multiple regions
- D. The ability to recover data from a previous backup

---

### Domain: Security

---

**Question 2** *(Choose ONE)*

A company wants to enforce multi-factor authentication (MFA) for all IAM users in their AWS account. Which AWS service or feature should they use to implement this policy organization-wide?

- A. AWS IAM Identity Center
- B. AWS Config rule
- C. AWS IAM policy with a Condition element
- D. AWS Cognito user pools

---

**Question 7** *(Choose TWO)*

Which components of the AWS infrastructure does AWS manage under the AWS Shared Responsibility Model?

- A. Patching the guest operating system on EC2 instances
- B. Physical security of AWS data centers
- C. Network infrastructure and hardware
- D. Configuring security groups on customer VPCs
- E. Encrypting customer data stored in Amazon S3

---

**Question 12** *(Choose ONE)*

A company wants to protect their web application from common web exploits such as SQL injection and cross-site scripting (XSS). Which AWS service should they implement?

- A. AWS Shield Standard
- B. AWS WAF
- C. Amazon Inspector
- D. AWS Firewall Manager

---

**Question 15** *(Choose ONE)*

A company needs to grant temporary AWS credentials to a mobile application that allows users to access their own Amazon S3 objects. The solution should NOT store long-term AWS credentials on the device. Which service should they use?

- A. IAM access keys stored in the app
- B. AWS Cognito Identity Pools
- C. AWS IAM users per mobile user
- D. AWS STS called directly with root credentials

---

**Question 18** *(Choose ONE)*

A company has multiple AWS accounts and wants to enforce Service Control Policies (SCPs) to restrict what actions can be performed across all accounts in their organization. Which AWS service enables this?

- A. AWS IAM
- B. AWS Control Tower
- C. AWS Organizations
- D. AWS Config

---

**Question 20** *(Choose TWO)*

Under the AWS Shared Responsibility Model, which of the following tasks is the CUSTOMER'S responsibility when using Amazon RDS?

- A. Patching the underlying database engine software
- B. Managing database encryption at rest using KMS
- C. Patching the underlying EC2 host hardware
- D. Configuring database security group rules
- E. Maintaining the physical servers in the AWS data center

---

**Question 24** *(Choose ONE)*

A company needs to store database passwords and API keys securely and wants to automatically rotate these credentials on a schedule. Which AWS service BEST meets this requirement?

- A. AWS Systems Manager Parameter Store
- B. AWS Secrets Manager
- C. AWS KMS
- D. AWS Certificate Manager

---

**Question 27** *(Choose ONE)*

A company wants to assess their AWS account for security vulnerabilities, check compliance with best practices, and identify cost optimization opportunities in one unified service. Which AWS service should they use?

- A. AWS Inspector
- B. AWS Security Hub
- C. AWS Trusted Advisor
- D. Amazon Macie

---

**Question 30** *(Choose ONE)*

A company wants to implement a firewall at the SUBNET level that evaluates rules to allow or deny traffic in a STATELESS manner. Which AWS feature provides this?

- A. Security Groups
- B. Network ACLs (NACLs)
- C. AWS WAF
- D. AWS Network Firewall

---

**Question 35** *(Choose ONE)*

A company discovers that one of their EC2 instances has been compromised and is being used for unauthorized cryptocurrency mining. Which AWS service would have DETECTED this threat using machine learning and threat intelligence?

- A. AWS CloudTrail
- B. Amazon Inspector
- C. Amazon GuardDuty
- D. AWS Security Hub

---

**Question 38** *(Choose ONE)*

A company wants to centrally manage encryption keys used to protect data across multiple AWS services and maintain full control over key usage policies. Which AWS service should they use?

- A. AWS Certificate Manager (ACM)
- B. AWS Secrets Manager
- C. AWS Key Management Service (KMS)
- D. AWS CloudHSM

---

**Question 41** *(Choose TWO)*

A company wants to protect their AWS account from DDoS attacks at Layers 3, 4, and 7. Which AWS service combination provides COMPREHENSIVE protection?

- A. AWS Shield Advanced
- B. Amazon GuardDuty
- C. AWS WAF
- D. Amazon Inspector
- E. Amazon Macie

---

**Question 44** *(Choose ONE)*

A company needs to ensure that IAM users are only allowed to perform actions within a specific AWS Region. Which IAM policy element should they use to enforce this?

- A. IAM Permission Boundary
- B. IAM policy with Condition using aws:RequestedRegion
- C. Service Control Policy (SCP)
- D. IAM Resource-based policy

---

**Question 47** *(Choose TWO)*

Which of the following are AWS responsibilities under the Shared Responsibility Model for AWS Lambda?

- A. Writing secure application code
- B. Managing the runtime environment and underlying compute infrastructure
- C. Securing the Lambda execution role permissions
- D. Patching and maintaining the Lambda service infrastructure
- E. Validating input data to prevent injection attacks

---

**Question 51** *(Choose ONE)*

A company wants to audit all changes to their AWS resource configurations over time and ensure resources comply with company policies. Which AWS service provides this capability?

- A. AWS CloudTrail
- B. AWS Config
- C. Amazon Inspector
- D. AWS Trusted Advisor

---

**Question 55** *(Choose ONE)*

A company needs to provide its contractors with temporary access to specific AWS resources for 8 hours. The contractors already have their own identity provider. Which approach follows AWS security best practices?

- A. Create permanent IAM users for each contractor
- B. Share the root account credentials with contractors
- C. Use IAM roles with an identity federation solution and set a session duration of 8 hours
- D. Create a single shared IAM user for all contractors

---

**Question 56** *(Choose TWO)*

Which of the following are true about Security Groups in Amazon VPC?

- A. Security Groups are stateless — return traffic must be explicitly allowed
- B. Security Groups can be applied to subnets
- C. Security Groups are stateful — return traffic is automatically allowed
- D. Security Groups evaluate all rules before allowing traffic
- E. Security Groups only support DENY rules

---

**Question 60** *(Choose ONE)*

A company's application uses hard-coded database passwords in the source code. A security review recommends fixing this. Which Well-Architected pillar and AWS service combination addresses this concern?

- A. Operational Excellence — AWS Config
- B. Security — AWS Secrets Manager
- C. Reliability — AWS Systems Manager
- D. Cost Optimization — AWS Trusted Advisor

---

**Question 63** *(Choose TWO)*

A company is using Amazon S3 to store sensitive customer data. They want to ensure that data is never accidentally made public and receive alerts if a bucket becomes publicly accessible. Which AWS services help achieve this?

- A. Amazon GuardDuty
- B. S3 Block Public Access
- C. Amazon Macie
- D. AWS CloudTrail
- E. AWS Config

---

### Domain: Networking

---

**Question 3** *(Choose ONE)*

A company needs to connect their on-premises data center to AWS with a DEDICATED private connection that does NOT use the public internet. Which AWS service should they use?

- A. AWS Site-to-Site VPN
- B. AWS Direct Connect
- C. Amazon VPC Peering
- D. AWS Transit Gateway

---

**Question 9** *(Choose ONE)*

A company wants to route users in different geographic regions to the nearest AWS endpoint to reduce latency. Which Route 53 routing policy should they use?

- A. Simple routing
- B. Failover routing
- C. Geolocation routing
- D. Latency-based routing

---

**Question 17** *(Choose ONE)*

Which AWS service provides a global content delivery network (CDN) that caches content at edge locations worldwide to reduce latency for end users?

- A. AWS Global Accelerator
- B. Amazon CloudFront
- C. Amazon Route 53
- D. AWS Direct Connect

---

**Question 23** *(Choose ONE)*

A company wants to launch EC2 instances in a private subnet that can access the internet to download software updates but should NOT be reachable from the internet. Which component is required?

- A. Internet Gateway attached to the private subnet
- B. NAT Gateway in a public subnet
- C. VPC Peering connection
- D. AWS Direct Connect gateway

---

**Question 26** *(Choose ONE)*

A company wants to create a logically isolated section of the AWS Cloud where they can launch AWS resources in a virtual network they define. Which AWS service provides this?

- A. AWS Direct Connect
- B. Amazon VPC
- C. AWS Transit Gateway
- D. Amazon Route 53

---

**Question 37** *(Choose ONE)*

A company has VPCs in two different AWS Regions and wants to connect them privately without routing traffic over the public internet. Which solution should they use?

- A. VPC Peering
- B. AWS Transit Gateway inter-Region peering
- C. AWS Site-to-Site VPN
- D. AWS PrivateLink

---

**Question 42** *(Choose ONE)*

A company runs an application in a private subnet that needs to access AWS services like S3 and DynamoDB WITHOUT routing traffic through the public internet or requiring a NAT Gateway. Which feature should they use?

- A. Internet Gateway
- B. VPC Endpoint
- C. AWS PrivateLink
- D. NAT Instance

---

**Question 48** *(Choose ONE)*

A company wants to use a single, globally anycast IP address that routes user requests to the optimal AWS endpoint based on health, geography, and routing policies. Which service provides this?

- A. Amazon CloudFront
- B. Amazon Route 53
- C. AWS Global Accelerator
- D. Amazon VPC Peering

---

**Question 53** *(Choose ONE)*

A company needs to run a high-performance computing (HPC) workload that requires tightly coupled instances with low latency network communication between nodes. Which EC2 feature minimizes network latency between instances?

- A. Enhanced Networking
- B. Placement Groups — Cluster
- C. Dedicated Hosts
- D. Auto Scaling groups

---

**Question 56** *(Choose TWO)*

Which of the following are true about Security Groups in Amazon VPC?

*(See Security section above)*

---

**Question 64** *(Choose ONE)*

A company wants to implement a hybrid DNS solution where on-premises servers can resolve AWS private hosted zone records and AWS resources can resolve on-premises DNS records. Which Route 53 feature enables this?

- A. Route 53 Alias Records
- B. Route 53 Resolver
- C. Route 53 Traffic Policies
- D. Route 53 Geolocation routing

---

### Domain: Compute

---

**Question 8** *(Choose ONE)*

A developer wants to run code in response to HTTP requests without provisioning or managing any servers. The code runs in short bursts and the developer only wants to pay when the code executes. Which AWS service BEST meets these requirements?

- A. Amazon EC2 with Auto Scaling
- B. AWS Lambda
- C. Amazon ECS on EC2
- D. AWS Elastic Beanstalk

---

**Question 19** *(Choose ONE)*

A company runs a web application on EC2 instances behind an Application Load Balancer. During peak hours, the number of users triples. Which feature ensures the application automatically adds EC2 instances during peak periods and removes them when demand decreases?

- A. Elastic IP addresses
- B. Amazon EC2 Auto Scaling
- C. AWS Elastic Beanstalk
- D. Amazon CloudFront

---

**Question 31** *(Choose ONE)*

A company wants to containerize their microservices and run them on AWS without managing the underlying EC2 instances or clusters. Which AWS service provides SERVERLESS container orchestration?

- A. Amazon ECS on EC2
- B. Amazon EKS on EC2
- C. AWS Fargate
- D. Amazon Lightsail

---

### Domain: Storage

---

**Question 6** *(Choose ONE)*

A company stores millions of images in Amazon S3. Images uploaded more than 90 days ago are rarely accessed. The company wants to MINIMIZE storage costs while maintaining immediate access when needed. Which S3 storage class should they use for the older images?

- A. S3 Standard
- B. S3 Standard-Infrequent Access (S3 Standard-IA)
- C. S3 Glacier Instant Retrieval
- D. S3 Glacier Flexible Retrieval

---

**Question 33** *(Choose ONE)*

A company needs shared file storage that can be simultaneously accessed by multiple Amazon EC2 Linux instances using the NFS protocol. Which AWS storage service should they use?

- A. Amazon S3
- B. Amazon EBS
- C. Amazon EFS
- D. Amazon FSx for Windows File Server

---

**Question 46** *(Choose ONE)*

A company wants to back up their on-premises data to AWS in a cost-effective way and also wants to access that data locally with low latency. Which AWS service provides this capability?

- A. Amazon S3 Transfer Acceleration
- B. AWS Storage Gateway
- C. AWS Snowball
- D. AWS DataSync

---

### Domain: Database

---

**Question 10** *(Choose ONE)*

A company runs a relational database on-premises and wants to migrate to AWS with MINIMAL changes to the database engine. The company needs automatic failover to a standby instance in a different Availability Zone. Which AWS service and feature should they choose?

- A. Amazon DynamoDB with global tables
- B. Amazon RDS with Multi-AZ deployment
- C. Amazon Aurora Serverless
- D. Amazon ElastiCache with Multi-AZ

---

**Question 28** *(Choose ONE)*

A company needs a fully managed NoSQL database that can scale to handle millions of requests per second with single-digit millisecond latency. Which AWS service should they choose?

- A. Amazon RDS for MySQL
- B. Amazon Redshift
- C. Amazon DynamoDB
- D. Amazon ElastiCache

---

**Question 50** *(Choose ONE)*

A company uses Amazon RDS and wants to improve READ performance for their database without modifying the primary database instance. Which RDS feature should they implement?

- A. Multi-AZ deployment
- B. Read Replicas
- C. Amazon ElastiCache
- D. Database snapshots

---

### Domain: Monitoring

---

**Question 11** *(Choose ONE)*

A security team needs to track all API calls made to their AWS account, including who made the call, the source IP address, and when the call was made. Which AWS service provides this capability?

- A. Amazon CloudWatch
- B. AWS CloudTrail
- C. AWS Config
- D. Amazon GuardDuty

---

**Question 34** *(Choose ONE)*

A company wants to receive an alert whenever their monthly AWS bill exceeds $5,000. Which service should they configure?

- A. AWS Cost Explorer with anomaly detection
- B. AWS Budgets with a cost budget
- C. Amazon CloudWatch billing alarm
- D. AWS Trusted Advisor cost optimization check

---

**Question 59** *(Choose TWO)*

A company wants to monitor their EC2 instance CPU utilization and automatically send an email alert when it exceeds 80% for 5 consecutive minutes. Which services should they use?

- A. AWS CloudTrail
- B. Amazon CloudWatch Alarms
- C. AWS Lambda
- D. Amazon SNS
- E. Amazon SQS

---

### Domain: Pricing & Billing

---

**Question 4** *(Choose ONE)*

A startup wants to run a non-critical batch processing workload on EC2 that can be interrupted at any time. Which EC2 purchasing option provides the MOST cost savings?

- A. On-Demand Instances
- B. Reserved Instances — 1 year, no upfront
- C. Spot Instances
- D. Dedicated Hosts

---

**Question 13** *(Choose ONE)*

A company wants to purchase EC2 capacity with the HIGHEST discount and is willing to commit to a specific instance type in a specific Region for 1 or 3 years. Which pricing option offers the greatest savings?

- A. Convertible Reserved Instances
- B. Standard Reserved Instances
- C. Savings Plans — Compute
- D. On-Demand Capacity Reservations

---

**Question 22** *(Choose ONE)*

A company has predictable, steady-state EC2 usage of 50 instances running 24/7 for the next 3 years. They want to MAXIMIZE cost savings. Which purchasing strategy is MOST appropriate?

- A. All Spot Instances
- B. On-Demand Instances
- C. Reserved Instances — 3-year, all upfront
- D. Savings Plans — Compute, no upfront

---

**Question 32** *(Choose ONE)*

A company wants to understand their projected AWS spending for the NEXT MONTH based on current usage patterns. Which AWS service provides this capability?

- A. AWS Budgets
- B. AWS Cost Explorer
- C. AWS Pricing Calculator
- D. AWS Trusted Advisor

---

**Question 40** *(Choose ONE)*

Which AWS pricing model allows customers to save money on EC2 and Fargate usage across ANY instance family, size, and Region with no upfront commitment required?

- A. Convertible Reserved Instances
- B. Standard Reserved Instances
- C. Compute Savings Plans
- D. EC2 Instance Savings Plans

---

**Question 54** *(Choose ONE)*

A company is currently running workloads on-premises and is evaluating AWS. They want to understand how moving to AWS will change their IT costs. Which AWS tool helps build a business case by estimating on-premises costs versus AWS Cloud costs?

- A. AWS Pricing Calculator
- B. AWS Cost Explorer
- C. AWS Trusted Advisor
- D. AWS Migration Evaluator

---

**Question 62** *(Choose TWO)*

Which of the following AWS support plans provide access to a designated Technical Account Manager (TAM)?

- A. Basic
- B. Developer
- C. Business
- D. Enterprise On-Ramp
- E. Enterprise

---

### Domain: Well-Architected Framework

---

**Question 14** *(Choose ONE)*

A company wants to minimize unnecessary cloud spending by right-sizing EC2 instances and deleting unused resources. Which Well-Architected Framework pillar and AWS service combination BEST supports this?

- A. Reliability — AWS Config
- B. Cost Optimization — AWS Compute Optimizer
- C. Operational Excellence — AWS Systems Manager
- D. Performance Efficiency — Amazon CloudWatch

---

**Question 21** *(Choose ONE)*

A company wants to continuously run automated experiments to test how their system responds to failure and improve system resilience. Which Well-Architected Framework design principle does this BEST represent?

- A. Automate to make architectural experimentation easier
- B. Stop guessing capacity
- C. Test systems at production scale
- D. Design for failure

---

**Question 29** *(Choose ONE)*

Which AWS Well-Architected Framework pillar focuses on understanding business and technical needs and optimizing resource usage to avoid cloud waste?

- A. Reliability
- B. Operational Excellence
- C. Cost Optimization
- D. Sustainability

---

**Question 39** *(Choose TWO)*

A company deploys applications across three AWS Availability Zones with automatic failover. Which combination of Well-Architected pillars does this architecture PRIMARILY address?

- A. Cost Optimization
- B. Reliability
- C. Security
- D. Performance Efficiency
- E. Operational Excellence

---

**Question 45** *(Choose ONE)*

A company wants to implement infrastructure as code to track changes, peer review deployments, and roll back infrastructure changes quickly. Which Well-Architected pillar BEST aligns with this approach?

- A. Reliability
- B. Cost Optimization
- C. Security
- D. Operational Excellence

---

**Question 52** *(Choose TWO)*

Which actions align with the Sustainability pillar of the AWS Well-Architected Framework?

- A. Use Reserved Instances to reduce costs
- B. Right-size EC2 instances to reduce unused CPU and memory
- C. Deploy applications in a single Availability Zone to minimize data replication
- D. Use managed services like Lambda and Fargate instead of EC2 to improve resource utilization
- E. Enable versioning on S3 buckets

---

**Question 65** *(Choose ONE)*

A company runs their entire workload on a single large EC2 instance. Their solutions architect recommends distributing the workload across smaller instances using a load balancer. Which design principle of the Well-Architected Framework does this BEST represent?

- A. Automate recovery from failure
- B. Use serverless architectures
- C. Use multiple small resources instead of fewer large resources
- D. Enable traceability

---

### Domain: AI/ML Services

---

**Question 58** *(Choose ONE)*

A company wants to automatically extract text, tables, and data from scanned PDF documents and forms without manual effort. Which AWS AI service should they use?

- A. Amazon Rekognition
- B. Amazon Textract
- C. Amazon Comprehend
- D. Amazon Polly

---

---

# SECTION 2 — Answer Key

| Q# | Answer | Domain |
|----|--------|--------|
| 1 | C | Cloud Concepts |
| 2 | C | Security |
| 3 | B | Networking |
| 4 | C | Pricing |
| 5 | C | Well-Architected |
| 6 | B | Storage |
| 7 | B, C | Security |
| 8 | B | Compute |
| 9 | D | Networking |
| 10 | B | Database |
| 11 | B | Monitoring |
| 12 | B | Security |
| 13 | B | Pricing |
| 14 | B | Well-Architected |
| 15 | B | Security |
| 16 | C | Cloud Concepts |
| 17 | B | Networking |
| 18 | C | Security |
| 19 | B | Compute |
| 20 | B, D | Security |
| 21 | C | Well-Architected |
| 22 | C | Pricing |
| 23 | B | Networking |
| 24 | B | Security |
| 25 | B | Cloud Concepts |
| 26 | B | Networking |
| 27 | C | Security |
| 28 | C | Database |
| 29 | C | Well-Architected |
| 30 | B | Security |
| 31 | C | Compute |
| 32 | B | Pricing |
| 33 | C | Storage |
| 34 | B | Monitoring |
| 35 | C | Security |
| 36 | B, C, E | Cloud Concepts |
| 37 | B | Networking |
| 38 | C | Security |
| 39 | B, D | Well-Architected |
| 40 | C | Pricing |
| 41 | A, C | Security |
| 42 | B | Networking |
| 43 | C | Cloud Concepts |
| 44 | B | Security |
| 45 | D | Well-Architected |
| 46 | B | Storage |
| 47 | B, D | Security |
| 48 | C | Networking |
| 49 | C | Cloud Concepts |
| 50 | B | Database |
| 51 | B | Security |
| 52 | B, D | Well-Architected |
| 53 | B | Compute |
| 54 | D | Pricing |
| 55 | C | Security |
| 56 | C, D | Security/Networking |
| 57 | B | Cloud Concepts |
| 58 | B | AI/ML |
| 59 | B, D | Monitoring |
| 60 | B | Well-Architected |
| 61 | B | Cloud Concepts |
| 62 | D, E | Pricing |
| 63 | B, C | Security |
| 64 | B | Networking |
| 65 | C | Well-Architected |

---

# SECTION 3 — Detailed Explanations

---

**Q1 — Correct: C (Elasticity)**

Elasticity allows resources to automatically scale up or down based on demand, meaning you only pay for what you use. High availability ensures systems remain operational; fault tolerance means systems continue working despite failures; reliability ensures a workload performs its intended function correctly. The key phrase is "avoid paying for unused capacity while handling sudden spikes" — that is elasticity.

> **Exam Trap:** Scalability also involves growing resources, but scalability refers to the ability to scale, not the automatic pay-per-use aspect.

---

**Q2 — Correct: C (IAM policy with a Condition element)**

An IAM policy with a Condition element (specifically `aws:MultiFactorAuthPresent`) can enforce MFA at the IAM level for individual users or groups. AWS IAM Identity Center manages SSO access across accounts but doesn't directly enforce IAM user MFA conditions. AWS Config can detect non-compliant resources but cannot enforce MFA directly. Cognito manages app user authentication, not IAM users.

> **Exam Trap:** IAM Identity Center sounds like it should enforce MFA, but it manages federated access, not IAM user policies.

---

**Q3 — Correct: B (AWS Direct Connect)**

AWS Direct Connect provides a dedicated private network connection from your data center to AWS, bypassing the public internet. Site-to-Site VPN creates an encrypted tunnel over the public internet (not dedicated). VPC Peering connects VPCs together, not on-premises to AWS. Transit Gateway connects multiple VPCs and on-premises networks but still uses VPN (internet) unless combined with Direct Connect.

> **Exam Trap:** VPN sounds more "private" due to encryption, but it still traverses the public internet. Direct Connect is the ONLY dedicated private connection.

---

**Q4 — Correct: C (Spot Instances)**

Spot Instances allow you to bid on unused EC2 capacity at discounts of up to 90% compared to On-Demand pricing. They can be interrupted by AWS with a 2-minute warning when capacity is needed elsewhere — ideal for interruptible workloads. On-Demand has no interruption risk but costs the most. Reserved Instances save 30–72% but require a 1 or 3-year commitment. Dedicated Hosts are the most expensive option.

> **Exam Trap:** Reserved Instances sound like the obvious savings answer, but Spot Instances offer deeper discounts for interruptible workloads.

---

**Q5 — Correct: C (Reliability)**

The Reliability pillar focuses on the ability to recover from failures, dynamically acquire resources to meet demand, and mitigate disruptions automatically. Operational Excellence focuses on running and monitoring systems efficiently. Performance Efficiency focuses on using computing resources efficiently. Cost Optimization focuses on avoiding unnecessary costs.

> **Exam Trap:** Operational Excellence sounds like it includes recovery, but automatic recovery from infrastructure failures is squarely in the Reliability pillar.

---

**Q6 — Correct: B (S3 Standard-IA)**

S3 Standard-IA is designed for data that is accessed infrequently but requires rapid access when needed. It costs less than S3 Standard but charges a per-GB retrieval fee. S3 Standard is for frequently accessed data. S3 Glacier Instant Retrieval is for archive data. S3 Glacier Flexible Retrieval has retrieval times of minutes to hours — not truly immediate.

> **Exam Trap:** S3 Glacier Instant Retrieval does offer millisecond access, but it's priced as archival storage. Standard-IA is the correct fit for infrequent but potentially immediate access.

---

**Q7 — Correct: B, C (Physical security of data centers; Network infrastructure and hardware)**

AWS is responsible for the security "of" the cloud: physical security of data centers and the underlying network infrastructure and hardware. Customers are responsible for patching the OS on EC2, configuring security groups, and encrypting their own data.

> **Exam Trap:** S3 data encryption sounds like AWS should manage it, but the customer decides if and how to encrypt their data, even though AWS provides the tools.

---

**Q8 — Correct: B (AWS Lambda)**

AWS Lambda is a serverless compute service that runs code in response to events (including HTTP via API Gateway) without provisioning or managing servers. You pay only for compute time consumed. EC2 with Auto Scaling requires managing servers. ECS on EC2 requires provisioning EC2 instances. Elastic Beanstalk is a PaaS that still provisions underlying EC2 infrastructure.

> **Exam Trap:** Elastic Beanstalk reduces management overhead but is NOT serverless — it still provisions EC2 instances underneath.

---

**Q9 — Correct: D (Latency-based routing)**

Latency-based routing directs users to the AWS Region that provides the lowest latency. Geolocation routing routes based on the user's geographic location, not necessarily the nearest/fastest endpoint. Simple routing has a single resource. Failover routing redirects traffic based on health check status.

> **Exam Trap:** Geolocation routing sounds like it routes to the nearest location, but it routes based on the request's origin country/continent, not latency.

---

**Q10 — Correct: B (Amazon RDS with Multi-AZ deployment)**

Amazon RDS with Multi-AZ deployment automatically provisions a synchronous standby replica in a different AZ, with automatic failover. It supports standard relational database engines with minimal application changes. DynamoDB is NoSQL. Aurora Serverless is a new engine. ElastiCache is an in-memory cache.

> **Exam Trap:** Aurora Serverless sounds appealing but Aurora is a different engine from most on-premises databases.

---

**Q11 — Correct: B (AWS CloudTrail)**

AWS CloudTrail records all API calls made in your AWS account, capturing who made the call, the source IP, timestamp, and request/response details. CloudWatch monitors performance metrics and logs. AWS Config records resource configuration changes. GuardDuty uses CloudTrail data for threat detection.

> **Exam Trap:** CloudWatch vs. CloudTrail — CloudWatch = performance/metrics. CloudTrail = API activity auditing.

---

**Q12 — Correct: B (AWS WAF)**

AWS WAF protects web applications from common exploits like SQL injection and XSS by filtering HTTP/HTTPS traffic based on rules. AWS Shield protects against DDoS attacks. Amazon Inspector assesses EC2 instances for vulnerabilities. AWS Firewall Manager helps manage WAF rules across accounts.

> **Exam Trap:** AWS Shield sounds like it protects web apps, but Shield is DDoS-focused. WAF is specifically for application-layer (Layer 7) exploits.

---

**Q13 — Correct: B (Standard Reserved Instances)**

Standard Reserved Instances offer the highest discount (up to 72%) in exchange for a commitment to a specific instance type, Region, OS, and tenancy for 1 or 3 years. Convertible Reserved Instances offer less discount (~54%) but allow changes. Compute Savings Plans offer flexibility but slightly lower discounts. On-Demand Capacity Reservations reserve capacity but don't offer discounts.

> **Exam Trap:** Convertible RIs sound better because of flexibility, but flexibility comes at the cost of lower discounts.

---

**Q14 — Correct: B (Cost Optimization — AWS Compute Optimizer)**

The Cost Optimization pillar focuses on running systems at the lowest price. AWS Compute Optimizer uses ML to analyze utilization metrics and recommend optimal EC2 instance types. AWS Config tracks compliance. Systems Manager helps with operational automation. CloudWatch provides metrics but not instance recommendations.

> **Exam Trap:** CloudWatch + right-sizing sounds reasonable because CloudWatch gives metrics, but Compute Optimizer is the specific service for EC2 right-sizing recommendations.

---

**Q15 — Correct: B (AWS Cognito Identity Pools)**

Amazon Cognito Identity Pools provide temporary, limited-privilege AWS credentials to mobile/web app users via AWS STS without storing long-term credentials. Storing IAM access keys on devices is a security anti-pattern. Creating IAM users per mobile user doesn't scale. Calling STS with root credentials is dangerous.

> **Exam Trap:** STS is technically what delivers the credentials, but Cognito is the managed service designed for this mobile app use case.

---

**Q16 — Correct: C (AWS Migration Evaluator)**

AWS Migration Evaluator (formerly TCO Calculator) helps organizations estimate the total cost of ownership comparing on-premises to AWS. AWS Pricing Calculator estimates the cost of specific AWS services. Cost Explorer analyzes historical AWS spending. Trusted Advisor provides recommendations for existing workloads.

> **Exam Trap:** AWS Pricing Calculator is often confused with TCO analysis, but it's for estimating AWS service costs, not on-prem vs. AWS comparison.

---

**Q17 — Correct: B (Amazon CloudFront)**

Amazon CloudFront is AWS's CDN service that caches content at 400+ edge locations globally, reducing latency. Global Accelerator improves performance using the AWS global network but doesn't cache content. Route 53 is DNS. Direct Connect is a dedicated network connection.

> **Exam Trap:** CloudFront CACHES content at edge locations. Global Accelerator doesn't cache — it routes traffic optimally over the AWS backbone.

---

**Q18 — Correct: C (AWS Organizations)**

AWS Organizations allows you to centrally manage multiple AWS accounts and apply Service Control Policies (SCPs) to restrict or allow actions across all accounts or specific organizational units. IAM manages permissions within a single account. Control Tower builds on Organizations. Config records changes but doesn't apply restrictions.

> **Exam Trap:** AWS Control Tower uses Organizations SCPs under the hood, but SCPs are a feature of AWS Organizations specifically.

---

**Q19 — Correct: B (Amazon EC2 Auto Scaling)**

Amazon EC2 Auto Scaling automatically adjusts the number of EC2 instances in response to demand, scaling out during peak periods and scaling in when demand drops. Elastic IPs are static IP addresses. Elastic Beanstalk is a deployment platform. CloudFront is a CDN.

> **Exam Trap:** Elastic Beanstalk can manage Auto Scaling groups, but the feature that performs the actual scaling is EC2 Auto Scaling.

---

**Q20 — Correct: B, D (Managing encryption at rest using KMS; Configuring database security group rules)**

For RDS, AWS manages the underlying OS and hardware. The customer is responsible for: (1) managing encryption at rest (choosing to enable it and managing KMS keys) and (2) configuring security groups. AWS patches the database engine, hardware, and maintains physical servers.

> **Exam Trap:** "Patching the database engine" sounds like customer responsibility, but RDS is a managed service where AWS handles DB engine patching.

---

**Q21 — Correct: C (Test systems at production scale)**

Running automated experiments to test system responses to failure maps to the Reliability pillar's "Test recovery procedures" and the Well-Architected design principle of "Test systems at production scale." This includes testing failure conditions at real traffic levels.

> **Exam Trap:** Multiple options sound similar. Testing failure scenarios = Reliability pillar.

---

**Q22 — Correct: C (Reserved Instances — 3-year, all upfront)**

For predictable, steady-state 24/7 usage over 3 years, Reserved Instances with 3-year All Upfront payment offer the maximum discount (up to 72% off On-Demand). Spot Instances can be interrupted — not suitable for 24/7 production. Compute Savings Plans offer ~66% but slightly less than Standard RIs for the same commitment level.

> **Exam Trap:** Savings Plans are flexible and appealing, but they offer slightly less discount than Standard Reserved Instances for the same commitment.

---

**Q23 — Correct: B (NAT Gateway in a public subnet)**

A NAT Gateway placed in a public subnet allows instances in a private subnet to initiate outbound internet connections while preventing inbound connections from the internet. An Internet Gateway enables bi-directional internet traffic. VPC Peering connects VPCs. Direct Connect is for on-premises connectivity.

> **Exam Trap:** An Internet Gateway is necessary for the VPC to have internet access, but a NAT Gateway is the specific component for outbound-only access for private subnet instances.

---

**Q24 — Correct: B (AWS Secrets Manager)**

AWS Secrets Manager is specifically designed to store, manage, and automatically rotate secrets like database passwords and API keys. Systems Manager Parameter Store can store secrets but does NOT natively support automatic rotation. KMS manages encryption keys, not secrets/passwords. Certificate Manager manages SSL/TLS certificates.

> **Exam Trap:** Parameter Store is similar to Secrets Manager but automatic rotation is the key differentiator.

---

**Q25 — Correct: B (Trading fixed expenses for variable expenses)**

"Trading fixed expenses (CapEx) for variable expenses (OpEx)" is a core benefit of AWS Cloud. You pay only for resources consumed instead of investing in data center infrastructure upfront. "Economies of scale" refers to AWS's purchasing power lowering costs, not the CapEx-to-OpEx shift.

> **Exam Trap:** "Economies of scale" also reduces costs but refers to AWS's ability to offer lower prices, not the CapEx-to-OpEx shift.

---

**Q26 — Correct: B (Amazon VPC)**

Amazon VPC lets you provision a logically isolated section of the AWS Cloud where you can launch resources in a virtual network that you define, including IP address ranges, subnets, route tables, and gateways. Direct Connect is a physical connection. Transit Gateway connects multiple VPCs. Route 53 is DNS.

> **Exam Trap:** The wording "logically isolated" is the precise VPC definition. Don't confuse with availability zones or regions.

---

**Q27 — Correct: C (AWS Trusted Advisor)**

AWS Trusted Advisor provides real-time guidance across five categories: Cost Optimization, Performance, Security, Fault Tolerance, and Service Limits. Amazon Inspector assesses for software vulnerabilities only. Security Hub aggregates security findings but doesn't cover cost optimization. Amazon Macie discovers and protects sensitive data in S3.

> **Exam Trap:** Security Hub only covers security — not cost optimization or performance. Trusted Advisor covers all five categories.

---

**Q28 — Correct: C (Amazon DynamoDB)**

Amazon DynamoDB is a fully managed NoSQL key-value and document database that delivers consistent single-digit millisecond performance at any scale. RDS for MySQL is a relational database. Redshift is for analytics workloads. ElastiCache is an in-memory cache, not a primary database.

> **Exam Trap:** ElastiCache offers sub-millisecond latency but is a caching layer, not a standalone database.

---

**Q29 — Correct: C (Cost Optimization)**

The Cost Optimization pillar focuses on understanding and controlling cloud spending, selecting the most appropriate pricing model, and avoiding unnecessary costs. Sustainability also involves reducing waste but focuses on environmental impact. Read carefully — the question asks about "cloud waste" in a cost context.

> **Exam Trap:** Sustainability also involves reducing waste (environmental), but Cost Optimization specifically covers avoiding CLOUD SPENDING waste.

---

**Q30 — Correct: B (Network ACLs / NACLs)**

Network ACLs are stateless firewalls that operate at the subnet level, evaluating inbound and outbound rules independently. Return traffic must be explicitly allowed. Security Groups are stateful and operate at the instance level. AWS WAF operates at Layer 7. AWS Network Firewall is a managed firewall service for VPCs.

> **Exam Trap:** NACLs = subnet level, stateless. Security Groups = instance level, stateful.

---

**Q31 — Correct: C (AWS Fargate)**

AWS Fargate is a serverless compute engine for containers that works with both ECS and EKS. It removes the need to provision and manage EC2 instances. ECS on EC2 and EKS on EC2 both require managing EC2 instances. Lightsail is for small applications, not container orchestration.

> **Exam Trap:** Fargate is a LAUNCH TYPE for ECS/EKS, not a standalone orchestration service. But for "no EC2 management for containers," Fargate is correct.

---

**Q32 — Correct: B (AWS Cost Explorer)**

AWS Cost Explorer has a forecasting feature that uses historical usage data to predict future costs, including projections for the next month or next 12 months. AWS Budgets sets spending thresholds and alerts. Pricing Calculator estimates costs for new workloads. Trusted Advisor provides optimization recommendations.

> **Exam Trap:** AWS Budgets sounds like it would forecast spending, but Budgets is for setting alerts, not forecasting. Cost Explorer is the forecasting tool.

---

**Q33 — Correct: C (Amazon EFS)**

Amazon EFS provides a scalable, fully managed NFS file system that can be mounted by multiple EC2 instances simultaneously across multiple AZs. S3 is object storage accessed via APIs. EBS volumes can only be attached to one EC2 instance at a time. FSx for Windows File Server uses SMB protocol, not NFS.

> **Exam Trap:** NFS = EFS. SMB = FSx for Windows.

---

**Q34 — Correct: B (AWS Budgets)**

AWS Budgets allows you to set custom cost budgets and configure alerts when costs exceed a defined threshold. Cost Explorer anomaly detection finds unexpected cost spikes. CloudWatch billing alarms can also work but Budgets is the recommended, purpose-built service for this scenario.

> **Exam Trap:** CloudWatch billing alarms also work technically, but AWS Budgets is the recommended service for budget threshold alerts.

---

**Q35 — Correct: C (Amazon GuardDuty)**

Amazon GuardDuty is a threat detection service that continuously monitors for malicious activity using ML, anomaly detection, and threat intelligence feeds. It can detect cryptocurrency mining as a specific finding type. CloudTrail logs API activity. Inspector scans for software vulnerabilities. Security Hub aggregates findings.

> **Exam Trap:** Inspector sounds like it would detect "compromised" instances, but Inspector scans for software vulnerabilities — not runtime threats like crypto mining.

---

**Q36 — Correct: B, C, E (Faster deployment; Global infrastructure in minutes; On-demand scaling)**

Three key cloud benefits: faster time to deploy (no hardware procurement), global infrastructure accessible in minutes, and on-demand scaling without upfront investments. Cloud REDUCES CapEx. Cloud reduces IT overhead but does NOT eliminate all IT staff.

> **Exam Trap:** "Elimination of all IT staff" is a common misconception. Cloud shifts IT responsibilities but doesn't eliminate the need for IT professionals.

---

**Q37 — Correct: B (AWS Transit Gateway inter-Region peering)**

AWS Transit Gateway supports inter-Region peering, allowing VPCs in different AWS Regions to connect privately over the AWS backbone network. VPC Peering also supports inter-Region connections — both technically work, but Transit Gateway is the more scalable solution. Site-to-Site VPN uses the public internet.

> **Exam Trap:** Both VPC Peering and Transit Gateway work for inter-Region connectivity. Transit Gateway scales better for multiple VPCs.

---

**Q38 — Correct: C (AWS KMS)**

AWS KMS is a managed service for creating and controlling cryptographic keys used to encrypt data across AWS services. ACM manages SSL/TLS certificates. Secrets Manager stores application secrets. CloudHSM provides dedicated hardware security modules for stricter compliance but is more complex.

> **Exam Trap:** CloudHSM also manages encryption keys but is expensive and complex. KMS is the standard managed solution.

---

**Q39 — Correct: B, D (Reliability; Performance Efficiency)**

Multi-AZ with automatic failover primarily addresses Reliability (systems recover automatically from AZ failures) and Performance Efficiency (distributing load across AZs improves resource efficiency). Cost Optimization is not the primary focus. Security is not directly addressed by multi-AZ. Operational Excellence is about running systems effectively.

> **Exam Trap:** Multi-AZ is usually discussed in the context of Reliability, but it also contributes to Performance Efficiency.

---

**Q40 — Correct: C (Compute Savings Plans)**

Compute Savings Plans offer the highest flexibility — savings apply across any EC2 instance family, size, OS, tenancy, and Region, as well as AWS Fargate. EC2 Instance Savings Plans are locked to a specific instance family in a specific Region. Standard RIs are tied to specific instance type, Region, OS.

> **Exam Trap:** Savings Plans DO require a usage commitment (1 or 3 years), just no upfront payment. The flexibility keyword is "ANY instance family, size, and Region."

---

**Q41 — Correct: A, C (AWS Shield Advanced; AWS WAF)**

AWS Shield Advanced provides enhanced DDoS protection at Layers 3 and 4 with 24/7 access to the AWS DDoS Response Team. AWS WAF provides Layer 7 protection against web exploits and can block application-layer DDoS. GuardDuty detects threats but doesn't block DDoS.

> **Exam Trap:** Shield Standard (free, automatic) only protects L3/L4. You need Shield Advanced + WAF for comprehensive L3/4/7 protection.

---

**Q42 — Correct: B (VPC Endpoint)**

VPC Endpoints allow EC2 instances in private subnets to privately communicate with AWS services like S3 and DynamoDB without internet access, NAT Gateways, or VPN connections. Gateway endpoints for S3 and DynamoDB are free. PrivateLink (Interface Endpoints) is used for other AWS services.

> **Exam Trap:** PrivateLink and VPC Endpoints are related. Gateway Endpoints (for S3, DynamoDB) are a type of VPC Endpoint. The broader category is VPC Endpoints.

---

**Q43 — Correct: C (AWS Outposts)**

AWS Outposts brings native AWS services, infrastructure, and operating models to any data center or on-premises facility. Direct Connect is a network connection to AWS. Snowball Edge is for temporary edge computing and data transfer. Local Zones are AWS-managed facilities for low latency in cities, not customer premises.

> **Exam Trap:** Snowball Edge has compute capabilities but is for temporary/data transfer use. Outposts is the persistent on-premises AWS solution.

---

**Q44 — Correct: B (IAM policy with Condition using aws:RequestedRegion)**

An IAM policy with a Condition element using `aws:RequestedRegion` restricts API calls to specific AWS Regions. SCPs work at the AWS Organizations level. Permission Boundaries set maximum permissions but don't restrict by region directly. Resource-based policies are attached to resources, not users.

> **Exam Trap:** SCPs could also restrict regions, but they work at the organization/account level. The question asks about IAM users specifically.

---

**Q45 — Correct: D (Operational Excellence)**

The Operational Excellence pillar includes "Perform operations as code" (IaC) and "Make small, reversible changes." Tracking, peer review, and rollback of IaC are core Operational Excellence practices. IaC also supports Reliability and Security, but the PRIMARY pillar for "operations as code" is Operational Excellence.

> **Exam Trap:** IaC also supports Reliability (quick recovery) and Security (consistent deployment), but Operational Excellence is the primary home for operations-as-code practices.

---

**Q46 — Correct: B (AWS Storage Gateway)**

AWS Storage Gateway connects on-premises environments to AWS cloud storage, caching frequently accessed data locally for low latency while storing the full dataset in AWS. S3 Transfer Acceleration speeds up uploads. Snowball is for large one-time migration. DataSync transfers data but doesn't provide local caching.

> **Exam Trap:** DataSync is often confused with Storage Gateway. DataSync transfers data; Storage Gateway provides ongoing hybrid storage with local caching.

---

**Q47 — Correct: B, D (Managing runtime environment; Patching Lambda service infrastructure)**

For AWS Lambda, AWS manages the runtime environment and underlying compute infrastructure, and patches/maintains the Lambda service infrastructure. Customers are responsible for writing secure code, configuring execution role permissions, and validating input data.

> **Exam Trap:** With Lambda being "serverless," it's tempting to think AWS manages everything. Customers are still responsible for the CODE they deploy, the IAM roles they configure, and input validation.

---

**Q48 — Correct: C (AWS Global Accelerator)**

AWS Global Accelerator provides static anycast IP addresses that serve as a fixed entry point to applications, routing traffic using the AWS global network to the optimal endpoint based on health, geography, and routing policies. CloudFront is a CDN that caches content. Route 53 uses domain names, not static IPs.

> **Exam Trap:** CloudFront and Global Accelerator both improve global performance. CloudFront CACHES content (CDN). Global Accelerator routes traffic without caching using static anycast IPs.

---

**Q49 — Correct: C (Agility)**

Agility refers to the speed at which cloud resources can be deployed, allowing companies to experiment, innovate, and bring ideas to market faster with lower risk. Elasticity = scaling resources. Economy of scale = lower pricing from AWS's purchasing power. High availability = systems continuously operational.

> **Exam Trap:** Elasticity and agility are often confused. Elasticity = scale up/down with demand. Agility = speed of innovation and experimentation.

---

**Q50 — Correct: B (Read Replicas)**

Read Replicas create read-only copies of the primary database that can serve read traffic, reducing load on the primary instance. Multi-AZ creates a standby for failover only — the standby is NOT readable in standard RDS. ElastiCache caches results but requires application changes. Snapshots are for backup/restore.

> **Exam Trap:** Multi-AZ standby instance CANNOT be used for reads in standard RDS (it's for failover only). Only Read Replicas serve read traffic.

---

**Q51 — Correct: B (AWS Config)**

AWS Config continuously monitors and records AWS resource configurations and evaluates them against desired configurations (compliance rules). CloudTrail records API calls (who did what). Inspector scans for software vulnerabilities. Trusted Advisor provides recommendations.

> **Exam Trap:** CloudTrail = WHO made API calls (audit trail). Config = WHAT the resource configuration looks like and whether it changed.

---

**Q52 — Correct: B, D (Right-size EC2 instances; Use managed services like Lambda and Fargate)**

Sustainability focuses on minimizing environmental impact. Right-sizing reduces wasted resources (energy waste). Using managed serverless services improves hardware utilization efficiency. Reserved Instances save money but don't reduce resource utilization. Single-AZ wastes idle standby resources.

> **Exam Trap:** Reserved Instances are a pricing model, not a resource utilization strategy. Sustainability = reduce actual compute/energy consumption.

---

**Q53 — Correct: B (Placement Groups — Cluster)**

Cluster Placement Groups place EC2 instances in a single AZ in close physical proximity connected via high-bandwidth, low-latency networking, specifically designed for HPC workloads. Enhanced Networking improves individual instance network performance but doesn't control physical placement.

> **Exam Trap:** Enhanced Networking sounds right for "low latency network," but Placement Groups — Cluster ensures PHYSICAL proximity for inter-node HPC communication.

---

**Q54 — Correct: D (AWS Migration Evaluator)**

AWS Migration Evaluator provides an accurate assessment of what it would cost to run on-premises workloads on AWS and compares against current on-premises spending. AWS Pricing Calculator estimates AWS service costs from scratch. Cost Explorer analyzes existing AWS spending. Trusted Advisor optimizes existing AWS usage.

> **Exam Trap:** Pricing Calculator = estimate AWS service costs. Migration Evaluator = compare on-premises TCO vs. AWS.

---

**Q55 — Correct: C (IAM roles with identity federation)**

IAM Roles with identity federation allow contractors to authenticate with their existing identity provider and assume an IAM role with a configurable session duration. Temporary credentials from STS are automatically issued. Permanent IAM users are a security risk. Shared IAM users violate individual accountability.

> **Exam Trap:** Creating IAM users seems like the safe option, but temporary role assumption via federation is best practice for contractors.

---

**Q56 — Correct: C, D (Security Groups are stateful; Security Groups evaluate all rules)**

Security Groups are stateful — when you allow inbound traffic, return outbound traffic is automatically allowed. Security Groups evaluate ALL rules before deciding to allow traffic. They operate at the instance level, not subnet level. They support only ALLOW rules — deny is implicit.

> **Exam Trap:** NACLs = stateless (return traffic must be explicitly allowed). Security Groups = stateful (return traffic automatically allowed). Also: SGs have only ALLOW rules.

---

**Q57 — Correct: B (Dedicated Instances)**

Dedicated Instances run on hardware dedicated to a single customer (physically isolated) but don't give visibility into the specific host. Dedicated Hosts provide the same isolation PLUS visibility into physical server details needed for bring-your-own-license (BYOL) scenarios. Default/shared tenancy shares hardware.

> **Exam Trap:** Both Dedicated Instances and Dedicated Hosts provide physical isolation. Dedicated Hosts are for BYOL scenarios. For simple physical isolation without license requirements, Dedicated Instances are sufficient.

---

**Q58 — Correct: B (Amazon Textract)**

Amazon Textract automatically extracts text, handwriting, tables, and structured data from scanned documents and forms. Rekognition analyzes images and videos (faces, objects, labels). Comprehend performs NLP (sentiment analysis, entity detection). Polly converts text to speech.

> **Exam Trap:** Rekognition sounds like it reads image documents, but it's for image/video analysis. Textract is specifically for document text extraction.

---

**Q59 — Correct: B, D (Amazon CloudWatch Alarms; Amazon SNS)**

Amazon CloudWatch Alarms monitors metrics (like CPU utilization) and triggers actions when thresholds are breached. Amazon SNS sends notifications (email, SMS, HTTP) when the alarm is triggered. CloudTrail is for API auditing. Lambda could be triggered but isn't needed for email alerting. SQS is a message queue.

> **Exam Trap:** The canonical pattern is CloudWatch Alarm → SNS Topic → Email subscription. SNS is the direct notification service, not Lambda.

---

**Q60 — Correct: B (Security — AWS Secrets Manager)**

The Security pillar emphasizes "Protect data in transit and at rest" and "Implement a strong identity foundation." Hard-coded credentials violate this. AWS Secrets Manager stores and manages secrets securely, making them available to applications via API. Systems Manager Parameter Store can store secrets but lacks automatic rotation.

> **Exam Trap:** Systems Manager Parameter Store seems correct, but Secrets Manager with automatic rotation is the Security pillar recommendation for database credentials.

---

**Q61 — Correct: B (Continue operating despite component failures)**

Fault tolerance is the ability of a system to continue functioning even when one or more components fail — without any disruption. High availability accepts brief interruptions during failover; fault tolerance means NO interruption at all.

> **Exam Trap:** HA = minimal downtime during failure. Fault tolerance = ZERO downtime even during failure (more expensive/complex).

---

**Q62 — Correct: D, E (Enterprise On-Ramp; Enterprise)**

A Technical Account Manager (TAM) is provided with Enterprise On-Ramp (pool of TAMs) and Enterprise (designated TAM) support plans. Basic and Developer plans have no TAM. Business plan has 24/7 Cloud Support Engineers but no TAM.

> **Exam Trap:** Many candidates assume Business plan includes a TAM because it's the first significant paid tier. TAMs start at Enterprise On-Ramp.

---

**Q63 — Correct: B, C (S3 Block Public Access; Amazon Macie)**

S3 Block Public Access prevents buckets and objects from being made publicly accessible. Amazon Macie uses ML to discover, classify, and protect sensitive data in S3 and alerts when data is exposed publicly. GuardDuty detects threats. CloudTrail logs API calls. Config can detect public buckets but is less purpose-built.

> **Exam Trap:** AWS Config can also detect public S3 buckets, but S3 Block Public Access + Macie is the canonical pairing for preventing public exposure AND alerting on sensitive data exposure.

---

**Q64 — Correct: B (Route 53 Resolver)**

Amazon Route 53 Resolver enables hybrid DNS by providing inbound endpoints (on-premises can query Route 53 private hosted zones) and outbound endpoints (EC2 instances can resolve on-premises DNS records). Alias Records route to AWS resources. Traffic Policies define routing rules. Geolocation routing is based on user location.

> **Exam Trap:** Route 53 Resolver (formerly Amazon DNS Resolver) handles DNS resolution in hybrid environments — often overlooked in exam preparation.

---

**Q65 — Correct: C (Use multiple small resources instead of fewer large resources)**

"Use multiple small resources instead of fewer large resources" is a Performance Efficiency design principle. Distributing workloads horizontally across smaller instances improves performance, resilience, and cost efficiency compared to vertically scaling a single large instance.

> **Exam Trap:** This also relates to Reliability (fewer eggs in one basket), but the specific language about "multiple small resources vs. fewer large" maps directly to Performance Efficiency.

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

## Key Topics to Review If You Missed Questions

- **Shared Responsibility Model** — Know what AWS manages vs. customer manages for EC2, RDS, Lambda, and S3
- **Pricing Models** — Spot vs. On-Demand vs. Reserved vs. Savings Plans and when to use each
- **CloudTrail vs. CloudWatch vs. Config** — Three most commonly confused monitoring services
- **Security Groups vs. NACLs** — Stateful vs. stateless, instance vs. subnet level
- **Direct Connect vs. VPN** — Dedicated private vs. encrypted internet tunnel
- **CloudFront vs. Global Accelerator** — CDN with caching vs. traffic routing with static IPs
- **Secrets Manager vs. Parameter Store** — Automatic rotation is the key differentiator
- **Well-Architected Pillars** — Know all six pillars and their core design principles
- **RDS Multi-AZ vs. Read Replicas** — Failover vs. read performance
- **AWS Organizations SCPs** — Organization-wide permission restrictions

---

*This mock exam is designed to closely simulate the real AWS Certified Cloud Practitioner (CLF-C02) exam experience. Good luck on the real exam!*
