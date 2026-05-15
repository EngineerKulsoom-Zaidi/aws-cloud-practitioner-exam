# AWS Certified Cloud Practitioner (CLF-C02) — Full Mock Exam

> **65 Questions · 90 Minutes · Passing Score: 70%**  
> Difficulty: Realistic exam-level | Includes scenario, security, networking, billing & Well-Architected questions

---

## Instructions

- This exam contains **65 questions**.
- You have **90 minutes** to complete it.
- Questions are either **single-answer** or **multi-answer** (marked clearly).
- For multi-answer questions, select **only** the number of answers specified.
- The passing score for the real AWS CLF-C02 exam is approximately **70%**.

---

# SECTION 1 — Questions

---

### Question 1 *(Choose ONE)*

A company is running an application on-premises and wants to migrate to AWS. They want to avoid paying for idle capacity and only pay for resources they actually use. Which AWS cloud benefit BEST describes this?

- A. High availability  
- B. Elasticity  
- C. Trade capital expense for variable expense  
- D. Increase speed and agility  

---

### Question 2 *(Choose ONE)*

A startup wants to deploy its application across multiple AWS Availability Zones. What is the PRIMARY reason for this architecture decision?

- A. To reduce data transfer costs  
- B. To achieve fault tolerance and high availability  
- C. To increase application performance globally  
- D. To reduce the number of EC2 instances needed  

---

### Question 3 *(Choose TWO)*

Which of the following are characteristics of Amazon S3?

- A. Block-level storage  
- B. Object storage  
- C. Unlimited storage capacity  
- D. Requires an EC2 instance to access  
- E. Suitable only for archival storage  

---

### Question 4 *(Choose ONE)*

A security team requires that all AWS API calls made in their account are logged for auditing purposes. Which AWS service should they enable?

- A. Amazon CloudWatch  
- B. AWS CloudTrail  
- C. AWS Config  
- D. Amazon GuardDuty  

---

### Question 5 *(Choose ONE)*

Which AWS service allows a company to extend its on-premises network to AWS using a private, dedicated connection with consistent network performance?

- A. AWS VPN  
- B. AWS Direct Connect  
- C. Amazon VPC Peering  
- D. AWS Transit Gateway  

---

### Question 6 *(Choose ONE)*

A company needs a database that can handle millions of read/write requests per second with single-digit millisecond latency at any scale. Which AWS service is MOST suitable?

- A. Amazon RDS for MySQL  
- B. Amazon Aurora  
- C. Amazon DynamoDB  
- D. Amazon Redshift  

---

### Question 7 *(Choose ONE)*

Under the AWS Shared Responsibility Model, which of the following is the CUSTOMER'S responsibility?

- A. Physical security of AWS data centers  
- B. Patching the hypervisor  
- C. Configuring Security Groups and NACLs  
- D. Maintaining the global network infrastructure  

---

### Question 8 *(Choose ONE)*

A company wants to run a workload that can tolerate interruptions and needs the MOST cost-effective EC2 pricing option. Which option should they choose?

- A. On-Demand Instances  
- B. Reserved Instances  
- C. Spot Instances  
- D. Dedicated Hosts  

---

### Question 9 *(Choose ONE)*

Which AWS service provides a content delivery network (CDN) that caches content at edge locations to reduce latency for global users?

- A. AWS Global Accelerator  
- B. Amazon CloudFront  
- C. Amazon Route 53  
- D. AWS Direct Connect  

---

### Question 10 *(Choose ONE)*

A company's application experiences highly variable traffic — low during weekdays and extremely high during weekends. Which EC2 feature automatically adjusts the number of instances based on demand?

- A. Elastic Load Balancing  
- B. Amazon EC2 Auto Scaling  
- C. AWS Elastic Beanstalk  
- D. AWS CloudFormation  

---

### Question 11 *(Choose ONE)*

Which of the following BEST describes the concept of "elasticity" in AWS cloud computing?

- A. The ability to deploy applications in multiple geographic regions  
- B. The ability to automatically acquire and release resources based on demand  
- C. The ability to maintain 99.999% uptime  
- D. The ability to encrypt data at rest and in transit  

---

### Question 12 *(Choose ONE)*

A company wants to allow employees to use their corporate Active Directory credentials to sign in to AWS. Which AWS service enables this federated identity management?

- A. AWS IAM  
- B. Amazon Cognito  
- C. AWS IAM Identity Center (SSO)  
- D. AWS KMS  

---

### Question 13 *(Choose ONE)*

Which of the following statements about AWS Regions and Availability Zones is CORRECT?

- A. Each Availability Zone consists of multiple AWS Regions  
- B. Each AWS Region contains at least two Availability Zones  
- C. Edge Locations are the same as Availability Zones  
- D. A Region is a single data center  

---

### Question 14 *(Choose TWO)*

A company is concerned about unauthorized access to their AWS root account. Which TWO actions are AWS best practices to protect the root account?

- A. Enable multi-factor authentication (MFA) on the root account  
- B. Use the root account for daily administrative tasks  
- C. Delete the root account access keys  
- D. Share root account credentials with trusted team members  
- E. Create individual IAM users for daily operations  

---

### Question 15 *(Choose ONE)*

A company needs to store database backups for 7 years for compliance purposes. They rarely need to access these backups. Which S3 storage class is MOST cost-effective?

- A. S3 Standard  
- B. S3 Standard-IA  
- C. S3 Glacier Deep Archive  
- D. S3 One Zone-IA  

---

### Question 16 *(Choose ONE)*

Which pillar of the AWS Well-Architected Framework focuses on the ability of a system to recover from failures and meet business and customer demand?

- A. Operational Excellence  
- B. Performance Efficiency  
- C. Reliability  
- D. Cost Optimization  

---

### Question 17 *(Choose ONE)*

A company wants to monitor their AWS bill and receive an alert when costs exceed $500 in a month. Which AWS service should they use?

- A. AWS Cost Explorer  
- B. AWS Budgets  
- C. AWS Pricing Calculator  
- D. AWS Trusted Advisor  

---

### Question 18 *(Choose ONE)*

Which of the following services operates at the NETWORK LAYER (Layer 4) and can block malicious traffic based on IP addresses and port numbers?

- A. AWS WAF  
- B. AWS Shield Standard  
- C. Network Access Control Lists (NACLs)  
- D. Security Groups  

---

### Question 19 *(Choose ONE)*

A company running an e-commerce site wants to ensure their database automatically fails over to a standby instance in another AZ during an outage, with minimal data loss. Which RDS feature should they enable?

- A. Read Replicas  
- B. Multi-AZ deployment  
- C. RDS Proxy  
- D. Aurora Serverless  

---

### Question 20 *(Choose ONE)*

Which AWS support plan is the MINIMUM plan required to get 24/7 access to Cloud Support Engineers via phone and chat?

- A. Basic  
- B. Developer  
- C. Business  
- D. Enterprise  

---

### Question 21 *(Choose ONE)*

A company has multiple AWS accounts and wants to centrally manage policies, consolidated billing, and service control policies (SCPs). Which AWS service enables this?

- A. AWS Control Tower  
- B. AWS Organizations  
- C. AWS IAM  
- D. AWS Config  

---

### Question 22 *(Choose ONE)*

An application is running on EC2 instances and needs to access an S3 bucket securely WITHOUT using access keys stored in the application code. What is the MOST secure approach?

- A. Store access keys in environment variables  
- B. Hard-code the access keys in the application  
- C. Attach an IAM Role to the EC2 instance  
- D. Create an IAM User and share credentials  

---

### Question 23 *(Choose TWO)*

Which of the following are benefits of using AWS Lambda over traditional EC2 instances?

- A. You pay only when your code executes  
- B. Lambda supports any programming language without restrictions  
- C. No server management is required  
- D. Lambda is better for long-running workloads over 24 hours  
- E. Lambda provides dedicated CPU allocation  

---

### Question 24 *(Choose ONE)*

A company wants to reduce costs for their steady-state EC2 workloads that run 24/7. They can commit to 1 year. Which purchasing option provides the GREATEST discount?

- A. On-Demand Instances  
- B. Spot Instances  
- C. Reserved Instances (Standard, 1-year, All Upfront)  
- D. Savings Plans  

---

### Question 25 *(Choose ONE)*

Which AWS service provides a firewall that filters malicious web traffic at Layer 7, including SQL injection and cross-site scripting (XSS) attacks?

- A. AWS Shield  
- B. AWS WAF  
- C. Security Groups  
- D. Amazon GuardDuty  

---

### Question 26 *(Choose ONE)*

A global company wants to reduce latency for users worldwide accessing their static website hosted on S3. What is the MOST effective solution with LEAST operational overhead?

- A. Deploy EC2 instances in every Region  
- B. Use Amazon CloudFront with S3 as the origin  
- C. Enable S3 Transfer Acceleration  
- D. Use Route 53 latency-based routing  

---

### Question 27 *(Choose ONE)*

Which Well-Architected Framework pillar focuses on using computing resources efficiently to meet system requirements and maintaining that efficiency as demand changes?

- A. Reliability  
- B. Operational Excellence  
- C. Performance Efficiency  
- D. Sustainability  

---

### Question 28 *(Choose ONE)*

A company is evaluating moving to AWS and wants to estimate the cost savings compared to running their own data centers. Which AWS tool helps calculate the Total Cost of Ownership (TCO)?

- A. AWS Pricing Calculator  
- B. AWS Cost Explorer  
- C. AWS TCO Calculator (Migration Evaluator)  
- D. AWS Budgets  

---

### Question 29 *(Choose ONE)*

Which of the following is a characteristic of Amazon EC2 Security Groups?

- A. They are stateless — return traffic must be explicitly allowed  
- B. They operate at the subnet level  
- C. They are stateful — return traffic is automatically allowed  
- D. They support DENY rules like NACLs  

---

### Question 30 *(Choose ONE)*

A company wants to ensure data stored in S3 cannot be deleted or overwritten for a fixed retention period to meet compliance requirements. Which S3 feature should they use?

- A. S3 Versioning  
- B. S3 Object Lock  
- C. S3 Replication  
- D. S3 Lifecycle Policies  

---

### Question 31 *(Choose TWO)*

Which of the following actions are the responsibility of AWS under the Shared Responsibility Model for an RDS database?

- A. Patching the RDS database engine  
- B. Managing database user permissions  
- C. Encrypting data stored in the database  
- D. Maintaining the underlying physical hardware  
- E. Creating and managing database backups  

---

### Question 32 *(Choose ONE)*

A developer needs to run containerized applications on AWS without managing the underlying server infrastructure. Which service provides SERVERLESS container execution?

- A. Amazon ECS with EC2 launch type  
- B. Amazon EKS  
- C. AWS Fargate  
- D. AWS Lambda  

---

### Question 33 *(Choose ONE)*

Which Route 53 routing policy would you use to route 10% of traffic to a new application version while 90% continues to go to the existing version for testing purposes?

- A. Latency-based routing  
- B. Failover routing  
- C. Weighted routing  
- D. Geolocation routing  

---

### Question 34 *(Choose ONE)*

A company wants to implement a principle where employees only have the minimum permissions needed to do their jobs. Which security concept does this represent?

- A. Defense in depth  
- B. Principle of least privilege  
- C. Zero trust architecture  
- D. Security through obscurity  

---

### Question 35 *(Choose ONE)*

Which AWS service helps protect against large-scale DDoS attacks and is automatically included at NO ADDITIONAL COST for all AWS customers?

- A. AWS WAF  
- B. AWS Shield Advanced  
- C. AWS Shield Standard  
- D. Amazon GuardDuty  

---

### Question 36 *(Choose ONE)*

A company's application must store session data that can be accessed by any EC2 instance in an Auto Scaling group. Which storage solution is MOST appropriate?

- A. Amazon EBS  
- B. Instance Store  
- C. Amazon ElastiCache  
- D. AWS Storage Gateway  

---

### Question 37 *(Choose TWO)*

Which of the following are features of Amazon CloudFront?

- A. It can only serve content stored in S3  
- B. It supports both static and dynamic content delivery  
- C. It uses edge locations to cache content closer to users  
- D. It replaces Route 53 for DNS resolution  
- E. It requires content to be replicated across all AWS Regions  

---

### Question 38 *(Choose ONE)*

A startup wants to deploy a web application without managing servers. They want automatic scaling, built-in CI/CD, and support for multiple languages with LEAST operational overhead. Which AWS service is BEST?

- A. Amazon EC2 with Auto Scaling  
- B. AWS Elastic Beanstalk  
- C. AWS Fargate  
- D. Amazon Lightsail  

---

### Question 39 *(Choose ONE)*

Which AWS service provides automated security assessments of EC2 instances, checking for vulnerabilities and unintended network exposures?

- A. AWS Trusted Advisor  
- B. Amazon Inspector  
- C. AWS Config  
- D. Amazon Macie  

---

### Question 40 *(Choose ONE)*

A company needs to send transactional emails and SMS notifications to users from their AWS-based application. Which AWS service should they use?

- A. Amazon SQS  
- B. Amazon SNS  
- C. Amazon SES  
- D. Amazon Pinpoint  

---

### Question 41 *(Choose ONE)*

Under the AWS Well-Architected Framework, which design principle belongs to the RELIABILITY pillar?

- A. Perform operations as code  
- B. Automatically recover from failure  
- C. Implement expenditure awareness  
- D. Adopt a consumption model  

---

### Question 42 *(Choose ONE)*

A company wants to use a VPC with private subnets. Instances in the private subnet need to download software updates from the internet WITHOUT being directly accessible from the internet. What should they use?

- A. Internet Gateway  
- B. VPC Endpoint  
- C. NAT Gateway  
- D. VPN Gateway  

---

### Question 43 *(Choose ONE)*

Which of the following BEST describes the difference between CloudWatch and CloudTrail?

- A. CloudWatch records API calls; CloudTrail monitors resource metrics  
- B. CloudWatch monitors performance metrics and logs; CloudTrail records API activity and user actions  
- C. They are the same service with different names  
- D. CloudTrail is only for S3 bucket activity  

---

### Question 44 *(Choose ONE)*

A company has a 3-year steady-state workload on EC2 and also needs flexibility to change instance families as new hardware releases. Which pricing option is BEST?

- A. Standard Reserved Instances  
- B. Convertible Reserved Instances  
- C. Spot Instances  
- D. On-Demand Instances  

---

### Question 45 *(Choose ONE)*

Which of the following statements about Amazon EBS and Amazon EFS is CORRECT?

- A. EBS can be mounted by multiple EC2 instances simultaneously by default  
- B. EFS is block storage and EBS is file storage  
- C. EBS volumes are tied to a single AZ; EFS is a regional file system  
- D. Both EBS and EFS are object storage solutions  

---

### Question 46 *(Choose ONE)*

A financial services company needs to run workloads on dedicated physical servers due to regulatory requirements. They need per-socket licensing. Which EC2 option should they use?

- A. Reserved Instances  
- B. Dedicated Instances  
- C. Dedicated Hosts  
- D. Spot Instances  

---

### Question 47 *(Choose ONE)*

Which of the following AWS services can be used to decouple application components and ensure messages are not lost if a downstream component becomes unavailable?

- A. Amazon SNS  
- B. Amazon SQS  
- C. AWS Step Functions  
- D. Amazon EventBridge  

---

### Question 48 *(Choose ONE)*

A company uses AWS Organizations. They want to PREVENT all accounts in a specific OU from creating EC2 instances in regions outside us-east-1 and eu-west-1. Which feature should they use?

- A. IAM permission boundaries  
- B. AWS Config rules  
- C. Service Control Policies (SCPs)  
- D. IAM policies on individual accounts  

---

### Question 49 *(Choose TWO)*

Which of the following are design principles of the Cost Optimization pillar in the AWS Well-Architected Framework?

- A. Implement expenditure awareness  
- B. Automatically recover from failure  
- C. Adopt a consumption model (pay for only what you use)  
- D. Perform operations as code  
- E. Choose the highest-performing resources regardless of cost  

---

### Question 50 *(Choose ONE)*

A company wants to migrate their VMware workloads to AWS with minimal changes. Which service allows running VMware vSphere workloads natively on AWS?

- A. AWS Outposts  
- B. VMware Cloud on AWS  
- C. AWS Server Migration Service  
- D. Amazon EC2 dedicated instances  

---

### Question 51 *(Choose ONE)*

Which Amazon S3 feature automatically moves objects to cheaper storage classes based on defined rules after a specified number of days?

- A. S3 Versioning  
- B. S3 Lifecycle Policies  
- C. S3 Intelligent-Tiering  
- D. S3 Object Lock  

---

### Question 52 *(Choose ONE)*

Which of the following is TRUE about AWS Free Tier?

- A. The Free Tier is available for 3 years after account creation  
- B. All AWS services are included in the Free Tier  
- C. Some Free Tier offerings are always free, while others expire after 12 months  
- D. The Free Tier includes unlimited EC2 usage  

---

### Question 53 *(Choose ONE)*

A company needs to connect two VPCs in different AWS accounts so they can communicate privately. Which solution requires the LEAST administrative overhead?

- A. AWS Site-to-Site VPN  
- B. AWS Transit Gateway  
- C. VPC Peering  
- D. AWS Direct Connect  

---

### Question 54 *(Choose ONE)*

Which AWS service uses machine learning to continuously monitor and detect anomalous behavior, unauthorized access, and potential threats by analyzing CloudTrail, VPC Flow Logs, and DNS logs?

- A. Amazon Inspector  
- B. AWS Security Hub  
- C. Amazon GuardDuty  
- D. Amazon Macie  

---

### Question 55 *(Choose ONE)*

A company wants to implement disaster recovery with a Recovery Time Objective (RTO) of minutes and Recovery Point Objective (RPO) of seconds. Which DR strategy BEST meets this requirement?

- A. Backup and restore  
- B. Pilot light  
- C. Warm standby  
- D. Multi-site active-active  

---

### Question 56 *(Choose TWO)*

Which of the following are valid use cases for Amazon CloudFront?

- A. Caching static website content at edge locations  
- B. Running database queries faster  
- C. Distributing software downloads globally with low latency  
- D. Replacing Amazon RDS for application data  
- E. Replacing Amazon VPC for network isolation  

---

### Question 57 *(Choose ONE)*

A company's application team wants to automatically detect if any S3 bucket in their account is made publicly accessible, and automatically remediate it. Which service combination should they use?

- A. Amazon Inspector + AWS Lambda  
- B. AWS Config + AWS Systems Manager  
- C. AWS Config + AWS Lambda  
- D. Amazon GuardDuty + AWS CloudTrail  

---

### Question 58 *(Choose ONE)*

Which EC2 instance type family is BEST suited for a workload that requires high memory-to-CPU ratio, such as an in-memory database like SAP HANA?

- A. Compute Optimized (C-family)  
- B. General Purpose (M-family)  
- C. Memory Optimized (R, X, or z-family)  
- D. Storage Optimized (I or D-family)  

---

### Question 59 *(Choose ONE)*

A company's security team wants to ensure all data stored on EBS volumes is encrypted. Which approach requires the LEAST management overhead?

- A. Use a third-party encryption tool before writing to EBS  
- B. Enable EBS encryption by default in account settings  
- C. Write application-level encryption code  
- D. Use S3 server-side encryption instead  

---

### Question 60 *(Choose ONE)*

Which AWS service provides a managed Hadoop and Spark framework for processing large datasets (big data analytics) with automatic cluster provisioning?

- A. Amazon Kinesis  
- B. AWS Glue  
- C. Amazon EMR  
- D. Amazon Athena  

---

### Question 61 *(Choose ONE)*

Which of the following statements about AWS Trusted Advisor is CORRECT?

- A. Trusted Advisor requires the Enterprise Support plan to access any checks  
- B. All AWS accounts get access to all Trusted Advisor checks with any support plan  
- C. Basic and Developer support plans get access to core checks only; Business/Enterprise get full access  
- D. Trusted Advisor only provides security recommendations  

---

### Question 62 *(Choose ONE)*

A company needs a Technical Account Manager (TAM) for proactive guidance and architectural reviews. Which support plan includes a TAM?

- A. Basic  
- B. Developer  
- C. Business  
- D. Enterprise  

---

### Question 63 *(Choose TWO)*

Which of the following actions would be MOST effective in reducing the attack surface on an EC2 instance?

- A. Assigning a public IPv6 address  
- B. Removing unnecessary software and services  
- C. Placing the instance in a public subnet  
- D. Using Security Groups to allow only required ports  
- E. Disabling VPC Flow Logs  

---

### Question 64 *(Choose ONE)*

A company is running a critical batch processing job every night at 2 AM. The job runs for 4 hours and cannot be interrupted. Which EC2 purchasing option is MOST cost-effective for this predictable, interruption-sensitive workload?

- A. On-Demand Instances  
- B. Spot Instances  
- C. Scheduled Reserved Instances  
- D. Dedicated Hosts  

---

### Question 65 *(Choose ONE)*

A company wants to implement a multi-account strategy on AWS with automated account provisioning, pre-configured guardrails, and a landing zone. Which service provides this?

- A. AWS Organizations  
- B. AWS Control Tower  
- C. AWS Config  
- D. AWS Service Catalog  

---

---

# SECTION 2 — Answer Key

| Q  | Answer(s) | Topic              |
|----|-----------|---------------------|
| 1  | C         | Cloud Concepts      |
| 2  | B         | Cloud Concepts      |
| 3  | B, C      | Storage             |
| 4  | B         | Security            |
| 5  | B         | Networking          |
| 6  | C         | Database            |
| 7  | C         | Security            |
| 8  | C         | Compute             |
| 9  | B         | Networking          |
| 10 | B         | Compute             |
| 11 | B         | Cloud Concepts      |
| 12 | C         | Security            |
| 13 | B         | Cloud Concepts      |
| 14 | A, C      | Security            |
| 15 | C         | Storage             |
| 16 | C         | Well-Architected    |
| 17 | B         | Billing             |
| 18 | C         | Security/Networking |
| 19 | B         | Database            |
| 20 | C         | Billing/Support     |
| 21 | B         | Security            |
| 22 | C         | Security            |
| 23 | A, C      | Compute             |
| 24 | C         | Billing             |
| 25 | B         | Security            |
| 26 | B         | Networking          |
| 27 | C         | Well-Architected    |
| 28 | C         | Billing             |
| 29 | C         | Networking          |
| 30 | B         | Storage             |
| 31 | A, D      | Security            |
| 32 | C         | Compute             |
| 33 | C         | Networking          |
| 34 | B         | Security            |
| 35 | C         | Security            |
| 36 | C         | Database/Storage    |
| 37 | B, C      | Networking          |
| 38 | B         | Compute             |
| 39 | B         | Security            |
| 40 | B         | Compute             |
| 41 | B         | Well-Architected    |
| 42 | C         | Networking          |
| 43 | B         | Security/Monitoring |
| 44 | B         | Billing             |
| 45 | C         | Storage             |
| 46 | C         | Compute             |
| 47 | B         | Compute             |
| 48 | C         | Security            |
| 49 | A, C      | Well-Architected    |
| 50 | B         | Cloud Concepts      |
| 51 | B         | Storage             |
| 52 | C         | Billing             |
| 53 | C         | Networking          |
| 54 | C         | Security            |
| 55 | D         | Cloud Concepts      |
| 56 | A, C      | Networking          |
| 57 | C         | Security            |
| 58 | C         | Compute             |
| 59 | B         | Security            |
| 60 | C         | Compute             |
| 61 | C         | Billing/Support     |
| 62 | D         | Billing/Support     |
| 63 | B, D      | Security            |
| 64 | C         | Billing             |
| 65 | B         | Well-Architected    |

---

---

# SECTION 3 — Detailed Explanations

---

### Question 1 — Answer: C

**Why C is correct:** "Trade capital expense for variable expense" (pay-as-you-go) means you pay only for what you consume, with no upfront hardware investment. This directly matches the scenario of avoiding idle capacity costs.

**Why others are wrong:**
- **A. High availability** — Refers to minimizing downtime, not cost model.
- **B. Elasticity** — Refers to auto-scaling capacity up/down, not the billing model.
- **D. Speed and agility** — Refers to rapid provisioning of resources, not cost structure.

**Exam trap:** Elasticity and pay-as-you-go are both cost-related concepts but mean different things. Elasticity = automatic scaling; pay-as-you-go = the billing model.

---

### Question 2 — Answer: B

**Why B is correct:** Availability Zones are isolated failure domains (separate power, networking, and facilities) within a Region. Deploying across multiple AZs protects against single-AZ failure, delivering fault tolerance and high availability.

**Why others are wrong:**
- **A.** Multi-AZ doesn't reduce data transfer costs.
- **C.** Global performance improvement requires multiple Regions or CloudFront, not just multi-AZ.
- **D.** Multi-AZ typically requires MORE instances, not fewer.

**Exam trap:** Confusing multi-AZ (high availability within a region) with multi-Region (global performance/DR).

---

### Question 3 — Answers: B, C

**Why B and C are correct:** S3 is object storage (not block storage) that provides effectively unlimited capacity — you never need to provision storage upfront.

**Why others are wrong:**
- **A.** Block-level storage is EBS, not S3.
- **D.** S3 is accessed via REST API, SDK, or console — no EC2 needed.
- **E.** S3 Standard supports active/hot data; Glacier is for archival.

**Exam trap:** Many candidates confuse S3 (object), EBS (block), and EFS (file) storage types.

---

### Question 4 — Answer: B

**Why B is correct:** AWS CloudTrail records every API call in your account — who made the call, when, from where, and what the call was. It is the primary tool for auditing and governance.

**Why others are wrong:**
- **A. CloudWatch** — Monitors metrics, logs, and sets alarms; does NOT record API calls.
- **C. AWS Config** — Tracks resource configuration changes over time.
- **D. GuardDuty** — Threat detection using ML; doesn't log raw API calls.

**Exam trap:** CloudWatch vs CloudTrail is one of the most common exam traps. Remember: CloudWatch = monitoring; CloudTrail = auditing.

---

### Question 5 — Answer: B

**Why B is correct:** AWS Direct Connect is a dedicated physical network connection from your data center to AWS — private, not over the public internet — delivering consistent bandwidth and low latency.

**Why others are wrong:**
- **A. AWS VPN** — Encrypted but travels over the public internet (variable latency).
- **C. VPC Peering** — Connects two VPCs, not on-premises to AWS.
- **D. Transit Gateway** — A hub for connecting multiple VPCs and VPNs, not a direct on-premises connection.

**Exam trap:** VPN and Direct Connect both connect on-premises to AWS, but only Direct Connect is private and dedicated.

---

### Question 6 — Answer: C

**Why C is correct:** Amazon DynamoDB is a fully managed NoSQL database built for single-digit millisecond performance at any scale — millions of requests per second.

**Why others are wrong:**
- **A. RDS for MySQL** — Relational database; cannot horizontally scale to millions of ops/sec.
- **B. Aurora** — High-performance relational DB but still SQL-based with scaling limits.
- **D. Redshift** — OLAP data warehouse for analytics queries, not transactional throughput.

**Exam trap:** Aurora is often confused with DynamoDB for "high performance." Aurora is the best relational DB; DynamoDB is the answer for massive NoSQL scale.

---

### Question 7 — Answer: C

**Why C is correct:** Security Groups and NACLs are network controls configured by the customer — this falls under "security IN the cloud," which is the customer's responsibility.

**Why others are wrong:**
- **A.** Physical data center security = AWS responsibility.
- **B.** Hypervisor patching = AWS responsibility.
- **D.** Global network infrastructure = AWS responsibility.

**Exam trap:** The shared responsibility model divides responsibilities. AWS manages the infrastructure; customers manage their data, access controls, and network configurations.

---

### Question 8 — Answer: C

**Why C is correct:** Spot Instances offer up to 90% discount vs On-Demand prices. The key requirement — "can tolerate interruptions" — makes Spot the correct choice.

**Why others are wrong:**
- **A. On-Demand** — Most expensive per-hour for flexible compute.
- **B. Reserved Instances** — Cheaper for steady-state but requires commitment; not the most cost-effective for interruptible work.
- **D. Dedicated Hosts** — The most expensive option, used for compliance/licensing needs.

**Exam trap:** Spot vs Reserved — both save money vs On-Demand, but Spot is cheapest for interruptible workloads; Reserved is for steady-state, always-on workloads.

---

### Question 9 — Answer: B

**Why B is correct:** Amazon CloudFront is AWS's global CDN service with 400+ edge locations that cache and deliver content to users from the nearest edge location.

**Why others are wrong:**
- **A. Global Accelerator** — Routes traffic through AWS's backbone network for performance, but does NOT cache content.
- **C. Route 53** — DNS service; resolves domain names but doesn't cache content.
- **D. Direct Connect** — Private network connection to AWS; not a CDN.

**Exam trap:** Global Accelerator vs CloudFront — both improve global performance, but CloudFront caches content; Global Accelerator is for TCP/UDP traffic acceleration without caching.

---

### Question 10 — Answer: B

**Why B is correct:** Amazon EC2 Auto Scaling monitors defined metrics (e.g., CPU utilization) and automatically adds or removes EC2 instances to match demand — the definition of elasticity.

**Why others are wrong:**
- **A. ELB** — Distributes incoming traffic across existing instances; does NOT change instance count.
- **C. Elastic Beanstalk** — PaaS that automates deployment; it uses Auto Scaling internally but is not the specific feature.
- **D. CloudFormation** — Infrastructure as code; provisions resources from templates but is not demand-driven.

---

### Question 11 — Answer: B

**Why B is correct:** Elasticity = the ability to automatically provision and de-provision resources in near real-time to match actual demand. You pay for exactly what you use.

**Why others are wrong:**
- **A.** Deploying in multiple regions is global reach, not elasticity.
- **C.** 99.999% uptime is high availability.
- **D.** Encryption is a security concept.

**Exam trap:** Scalability vs Elasticity — scalability is the ability to scale; elasticity means it happens automatically and dynamically.

---

### Question 12 — Answer: C

**Why C is correct:** AWS IAM Identity Center (formerly AWS SSO) enables federated access using existing enterprise identity providers (Microsoft AD, Okta, etc.) for AWS account and application access.

**Why others are wrong:**
- **A. IAM** — Manages AWS-native users and permissions, not federation with external directories.
- **B. Amazon Cognito** — Designed for customer-facing web/mobile app authentication (user pools), not corporate employee federation.
- **D. KMS** — Key Management Service for encryption; not identity.

---

### Question 13 — Answer: B

**Why B is correct:** Every AWS Region contains a minimum of 2 Availability Zones (most have 3+). AZs are isolated within a region for fault tolerance.

**Why others are wrong:**
- **A.** Regions contain AZs, not the other way around.
- **C.** Edge Locations are CDN/DNS points (used by CloudFront and Route 53) — completely separate from AZs.
- **D.** A Region is multiple data centers across multiple AZs, not a single data center.

---

### Question 14 — Answers: A, C

**Why A and C are correct:** AWS best practices for root account: (1) Always enable MFA on root account. (2) Delete root access keys — root should never have programmatic access.

**Why others are wrong:**
- **B.** Never use root for daily tasks — create IAM users/roles.
- **D.** Never share root credentials with anyone.
- **E.** Creating IAM users is correct practice but the question asks about protecting the ROOT account specifically.

**Exam trap:** Option E (create IAM users) is good practice but protects the organization, not specifically the root account.

---

### Question 15 — Answer: C

**Why C is correct:** S3 Glacier Deep Archive is the lowest-cost S3 storage class ($0.00099/GB/month), designed for 7-10 year retention with retrieval times of 12-48 hours — perfect for rarely accessed compliance backups.

**Why others are wrong:**
- **A. S3 Standard** — Highest cost; designed for frequently accessed data.
- **B. S3 Standard-IA** — Lower cost but has retrieval fees and minimum storage duration.
- **D. S3 One Zone-IA** — Cheaper than Standard-IA but stores in only one AZ — risky for compliance backups.

---

### Question 16 — Answer: C

**Why C is correct:** The Reliability pillar focuses on a workload's ability to perform its intended function correctly and consistently, including automatic recovery from infrastructure or service disruptions.

**Why others are wrong:**
- **A. Operational Excellence** — Running and improving operations; includes incident response.
- **B. Performance Efficiency** — Using resources efficiently.
- **D. Cost Optimization** — Avoiding unnecessary costs.

---

### Question 17 — Answer: B

**Why B is correct:** AWS Budgets lets you set custom cost or usage thresholds and sends alerts via email or SNS when actual or forecasted spending exceeds your defined limit.

**Why others are wrong:**
- **A. Cost Explorer** — Visualizes and analyzes historical spending; no alerting.
- **C. Pricing Calculator** — Estimates future AWS costs before provisioning.
- **D. Trusted Advisor** — Provides best practice recommendations; doesn't send cost threshold alerts.

---

### Question 18 — Answer: C

**Why C is correct:** NACLs (Network Access Control Lists) operate at the subnet level and are stateless, filtering traffic based on IP address, protocol, and port — Layer 3/4 controls.

**Why others are wrong:**
- **A. AWS WAF** — Layer 7 (HTTP/HTTPS) web application firewall; filters based on HTTP content.
- **B. AWS Shield Standard** — DDoS protection; not a configurable per-rule traffic filter.
- **D. Security Groups** — Operate at the instance/ENI level (Layer 4), are stateful, and only support ALLOW rules.

**Exam trap:** Security Groups vs NACLs is a classic exam trap. Key differences: SGs are stateful + instance-level + ALLOW only; NACLs are stateless + subnet-level + ALLOW and DENY.

---

### Question 19 — Answer: B

**Why B is correct:** RDS Multi-AZ creates a synchronous standby replica in a different AZ. On primary failure, RDS automatically promotes the standby (typically under 60-120 seconds) with no data loss.

**Why others are wrong:**
- **A. Read Replicas** — Asynchronous copies for READ scaling; they are NOT for automatic failover and may have replication lag.
- **C. RDS Proxy** — Improves database connection pooling and efficiency; not for failover.
- **D. Aurora Serverless** — Auto-scales Aurora capacity; not related to multi-AZ failover specifically.

**Exam trap:** Multi-AZ vs Read Replicas is the #1 most common database trap. Multi-AZ = high availability/failover. Read Replicas = read scaling/performance.

---

### Question 20 — Answer: C

**Why C is correct:** The Business Support Plan ($100/month minimum) is the minimum tier with 24/7 phone, chat, and email access to Cloud Support Engineers. It also provides full Trusted Advisor access.

**Why others are wrong:**
- **A. Basic** — No technical support; only documentation, forums, and AWS Health Dashboard.
- **B. Developer** — Business-hours email support only; no phone/chat.
- **D. Enterprise** — Also has 24/7 access plus TAM, but Business is the MINIMUM required.

---

### Question 21 — Answer: B

**Why B is correct:** AWS Organizations is the service for managing multiple AWS accounts, enabling consolidated billing, organizational units (OUs), and Service Control Policies (SCPs) for centralized governance.

**Why others are wrong:**
- **A. Control Tower** — Built on top of Organizations and automates landing zone setup, but the foundational service for multi-account management is Organizations.
- **C. IAM** — Manages users/roles within a single account; cannot span accounts natively.
- **D. Config** — Tracks resource configuration changes; not account management.

---

### Question 22 — Answer: C

**Why C is correct:** IAM Roles attached to EC2 instances provide temporary, automatically rotated credentials via the EC2 instance metadata service. No long-term credentials are stored anywhere.

**Why others are wrong:**
- **A.** Environment variables store credentials persistently — still a security risk.
- **B.** Hard-coding credentials in source code is a critical security vulnerability.
- **D.** IAM User credentials are long-term and require manual rotation management.

**Exam trap:** Always use IAM Roles for EC2 access to other AWS services — never access keys in code or config files.

---

### Question 23 — Answers: A, C

**Why A and C are correct:** Lambda's two primary advantages over EC2: (1) Pay-per-execution billing — you only pay for actual compute time. (2) Serverless — AWS manages all server infrastructure.

**Why others are wrong:**
- **B.** Lambda supports many runtimes but has constraints; it does not support "any language without restrictions."
- **D.** Lambda has a 15-minute maximum execution timeout — not suitable for 24-hour workloads.
- **E.** Lambda uses shared infrastructure without dedicated CPU allocation.

---

### Question 24 — Answer: C

**Why C is correct:** Standard Reserved Instances with All Upfront payment for 1 year provide the maximum discount (up to 72%) for predictable, steady-state workloads.

**Why others are wrong:**
- **A. On-Demand** — No discount; pay by the hour/second.
- **B. Spot** — Potentially cheaper but can be interrupted (not steady-state).
- **D. Savings Plans** — Flexible but provide slightly less discount than Standard RIs; also good, but C is the GREATEST discount.

---

### Question 25 — Answer: B

**Why B is correct:** AWS WAF (Web Application Firewall) operates at Layer 7 (application layer) and uses configurable rules (web ACLs) to block SQL injection, XSS, and other OWASP Top 10 attacks.

**Why others are wrong:**
- **A. AWS Shield** — Provides DDoS protection at Layers 3/4/7 but does not inspect HTTP content for SQLi/XSS.
- **C. Security Groups** — Layer 4 network controls; cannot inspect HTTP request content.
- **D. GuardDuty** — Threat detection service that analyzes logs; doesn't actively block traffic.

**Exam trap:** Shield vs WAF — Shield = DDoS protection (volumetric attacks); WAF = web attack protection (application layer attacks).

---

### Question 26 — Answer: B

**Why B is correct:** CloudFront + S3 is the canonical pattern for global static website delivery — CloudFront caches content at 400+ edge locations, dramatically reducing latency with zero infrastructure to manage.

**Why others are wrong:**
- **A.** Deploying EC2 in every Region requires significant infrastructure management and cost.
- **C. S3 Transfer Acceleration** — Speeds up file UPLOADS to S3, not content delivery to end users.
- **D. Route 53 latency routing** — Directs users to the nearest region but doesn't cache content at the edge.

---

### Question 27 — Answer: C

**Why C is correct:** Performance Efficiency is about selecting the right resource types and sizes, monitoring performance, and making informed decisions to maintain efficiency as demand evolves.

**Why others are wrong:**
- **A. Reliability** — Recovery from failures and meeting demand consistency.
- **B. Operational Excellence** — Running and improving operations processes.
- **D. Sustainability** — Minimizing environmental impact of cloud workloads (added in 2021).

---

### Question 28 — Answer: C

**Why C is correct:** AWS Migration Evaluator (formerly TCO Calculator) analyzes your on-premises costs and compares them with equivalent AWS costs, generating a business case for cloud migration.

**Why others are wrong:**
- **A. Pricing Calculator** — Estimates AWS-only costs; doesn't compare with on-premises.
- **B. Cost Explorer** — Analyzes existing AWS spending (post-migration tool).
- **D. Budgets** — Sets spending alerts; not a comparison/estimation tool.

---

### Question 29 — Answer: C

**Why C is correct:** Security Groups are stateful — if you create an inbound rule allowing port 80, the return traffic (outbound response) is automatically permitted without a separate outbound rule.

**Why others are wrong:**
- **A.** That describes NACLs (stateless), not Security Groups.
- **B.** Security Groups operate at the instance/ENI level, not subnet level (NACLs operate at the subnet level).
- **D.** Security Groups only support ALLOW rules. NACLs support both ALLOW and DENY.

**Exam trap:** This is one of the most heavily tested distinctions — Security Groups (stateful, instance-level, ALLOW only) vs NACLs (stateless, subnet-level, ALLOW and DENY).

---

### Question 30 — Answer: B

**Why B is correct:** S3 Object Lock uses WORM (Write Once, Read Many) protection. Objects cannot be deleted or modified for a defined retention period — required for SEC Rule 17a-4, FINRA, and HIPAA compliance.

**Why others are wrong:**
- **A. Versioning** — Keeps multiple versions of objects but doesn't prevent deletion (you can delete all versions).
- **C. Replication** — Copies objects to another bucket; doesn't prevent deletion.
- **D. Lifecycle Policies** — Automates transitions and deletions — the opposite of protecting from deletion.

---

### Question 31 — Answers: A, D

**Why A and D are correct:** For managed services like RDS, AWS is responsible for: patching the database engine and OS, and maintaining all physical infrastructure (hardware, networking, facilities).

**Why others are wrong:**
- **B.** Managing database user accounts and permissions = customer responsibility.
- **C.** Enabling encryption and managing encryption keys = customer responsibility (AWS provides the capability).
- **E.** Configuring automated backups = customer responsibility (AWS provides the feature but customers configure it).

---

### Question 32 — Answer: C

**Why C is correct:** AWS Fargate is the serverless compute engine for containers — you specify the container image and resource requirements; AWS manages all underlying server infrastructure.

**Why others are wrong:**
- **A. ECS with EC2** — Requires you to manage the EC2 instances that host containers.
- **B. EKS** — Managed Kubernetes; still requires node groups (EC2 or Fargate).
- **D. Lambda** — Serverless for function-based code, not full container workloads (though Lambda does support container images with limitations).

---

### Question 33 — Answer: C

**Why C is correct:** Weighted routing distributes traffic based on assigned numeric weights. A 90/10 split is a classic canary or A/B deployment pattern supported natively by Route 53 weighted routing.

**Why others are wrong:**
- **A. Latency-based** — Routes to the lowest-latency region; based on network performance, not percentage split.
- **B. Failover** — Active/passive; routes to secondary only when primary is unhealthy.
- **D. Geolocation** — Routes based on user's geographic location.

---

### Question 34 — Answer: B

**Why B is correct:** The principle of least privilege states that users, systems, and processes should be granted only the minimum permissions required to perform their specific task.

**Why others are wrong:**
- **A. Defense in depth** — Multiple layers of security controls, not specifically about minimizing permissions.
- **C. Zero trust** — "Never trust, always verify" architecture; related but broader concept.
- **D. Security through obscurity** — Hiding system details as a security measure; considered an anti-pattern.

---

### Question 35 — Answer: C

**Why C is correct:** AWS Shield Standard is included at no charge for all AWS customers and provides automatic protection against common, most frequently occurring Layer 3 and Layer 4 DDoS attacks.

**Why others are wrong:**
- **A. WAF** — Paid service; protects against Layer 7 attacks but isn't free for all customers.
- **B. Shield Advanced** — Costs $3,000/month; adds enhanced DDoS protection and 24/7 DRT team.
- **D. GuardDuty** — Threat detection service; has a free trial then paid; not DDoS protection.

---

### Question 36 — Answer: C

**Why C is correct:** ElastiCache (Redis or Memcached) is an in-memory data store accessible by multiple EC2 instances simultaneously — the standard solution for shared session state in Auto Scaling groups.

**Why others are wrong:**
- **A. EBS** — Block storage attached to ONE EC2 instance at a time; cannot be shared across an ASG.
- **B. Instance Store** — Ephemeral local storage tied to a single instance; lost on stop/termination.
- **D. Storage Gateway** — Connects on-premises storage to AWS; not designed for in-memory session data.

---

### Question 37 — Answers: B, C

**Why B and C are correct:** CloudFront delivers both static and dynamic content, and it uses a global network of 400+ edge locations to cache content close to users for lower latency.

**Why others are wrong:**
- **A.** CloudFront supports many origins: S3, EC2, ELB, API Gateway, and even on-premises servers.
- **D.** CloudFront doesn't replace Route 53; both are often used together (Route 53 → CloudFront → origin).
- **E.** CloudFront caches at edge locations; the origin only needs to be in one place.

---

### Question 38 — Answer: B

**Why B is correct:** AWS Elastic Beanstalk is a PaaS that automatically handles provisioning, load balancing, scaling, health monitoring, and deployment — the least operational overhead for web apps in multiple languages.

**Why others are wrong:**
- **A.** EC2 with Auto Scaling requires manually configuring all components (significant overhead).
- **C. Fargate** — Good for containers but requires containerizing the app and more configuration.
- **D. Lightsail** — Simplified VPS suitable for simpler use cases; lacks the full enterprise feature set of Elastic Beanstalk.

---

### Question 39 — Answer: B

**Why B is correct:** Amazon Inspector is an automated vulnerability management service that continuously scans EC2 instances and container images for software vulnerabilities (CVEs) and unintended network exposure.

**Why others are wrong:**
- **A. Trusted Advisor** — Provides best practice checks across categories (cost, security, performance); not deep vulnerability scanning.
- **C. Config** — Tracks configuration changes and compliance; doesn't scan for OS vulnerabilities.
- **D. Macie** — Uses ML to discover and protect sensitive data (PII, credentials) in S3; not vulnerability scanning.

---

### Question 40 — Answer: B

**Why B is correct:** Amazon SNS (Simple Notification Service) is a pub/sub messaging service that supports multiple protocols including SMS, email, push notifications, and HTTP/HTTPS endpoints — covering both requirements.

**Why others are wrong:**
- **A. SQS** — Message queue service; doesn't directly send emails or SMS to end users.
- **C. SES** — Specifically for high-volume email delivery only; cannot send SMS.
- **D. Pinpoint** — Marketing analytics and targeted campaign service; more complex and overkill for transactional notifications.

---

### Question 41 — Answer: B

**Why B is correct:** "Automatically recover from failure" is a core Reliability pillar design principle — systems should monitor KPIs and trigger automation to recover without human intervention.

**Why others are wrong:**
- **A.** "Perform operations as code" = Operational Excellence pillar.
- **C.** "Implement expenditure awareness" = Cost Optimization pillar.
- **D.** "Adopt a consumption model" = Cost Optimization pillar.

---

### Question 42 — Answer: C

**Why C is correct:** NAT Gateway (Network Address Translation) enables instances in private subnets to initiate outbound internet connections (for updates, patches) while preventing inbound connections from the internet.

**Why others are wrong:**
- **A. Internet Gateway** — Enables two-way internet communication; attaching it to private subnets would make them effectively public.
- **B. VPC Endpoint** — Provides private connectivity to AWS services (like S3, DynamoDB) without internet access; not for general internet updates.
- **D. VPN Gateway** — Connects to on-premises networks, not for internet access.

---

### Question 43 — Answer: B

**Why B is correct:** CloudWatch = monitoring (CPU metrics, application logs, custom metrics, alarms, dashboards). CloudTrail = auditing (records every API call — who, what, when, from where).

**Why others are wrong:**
- **A.** This has them reversed — a common exam trap.
- **C.** They are distinct services with very different functions.
- **D.** CloudTrail covers ALL AWS services and API calls, not just S3.

**Exam trap:** CloudWatch vs CloudTrail is tested repeatedly. The key memory aid: CloudWatch = performance metrics (watch your app); CloudTrail = audit trail (trail of breadcrumbs of who did what).

---

### Question 44 — Answer: B

**Why B is correct:** Convertible Reserved Instances allow you to exchange the instance type, operating system, or tenancy during the reservation term — essential for adapting to new hardware generations over 3 years. They offer slightly less discount than Standard RIs but provide needed flexibility.

**Why others are wrong:**
- **A. Standard RIs** — Locked to a specific instance type for the entire term; no flexibility.
- **C. Spot** — Interruptible; not suitable for steady-state workloads that can't be interrupted.
- **D. On-Demand** — No discount; most expensive for long-running workloads.

---

### Question 45 — Answer: C

**Why C is correct:** EBS volumes are created in a specific AZ and can only attach to EC2 instances in that same AZ. EFS is a fully managed NFS file system that spans all AZs in a region and can be mounted by thousands of instances simultaneously.

**Why others are wrong:**
- **A.** EBS volumes attach to one instance at a time by default (EBS Multi-Attach exists but is limited).
- **B.** EBS is block storage; EFS is file storage — this is reversed.
- **D.** Neither is object storage — that's S3.

**Exam trap:** EBS vs EFS vs S3 storage type confusion is very common. EBS = block (single AZ, single instance), EFS = file (regional, multi-instance), S3 = object (global, unlimited).

---

### Question 46 — Answer: C

**Why C is correct:** Dedicated Hosts give you a physical server entirely dedicated to your use, with visibility into the underlying hardware (sockets, cores, host IDs). This is required for BYOL (Bring Your Own License) software that is licensed per-socket or per-core.

**Why others are wrong:**
- **A. Reserved Instances** — A pricing model, not a hardware isolation model.
- **B. Dedicated Instances** — Run on dedicated hardware but without host-level visibility or control needed for per-socket licensing.
- **D. Spot Instances** — A pricing model for interruptible workloads; not related to hardware compliance.

---

### Question 47 — Answer: B

**Why B is correct:** Amazon SQS is a fully managed message queue that stores messages durably until a consumer processes them. If the consumer is unavailable, messages stay in the queue — preventing data loss and decoupling components.

**Why others are wrong:**
- **A. SNS** — Pub/sub service; if a subscriber is unavailable when a message is published, the message is lost (no durability by default).
- **C. Step Functions** — Orchestrates workflows; not a message storage/decoupling mechanism.
- **D. EventBridge** — Event bus for routing events; doesn't store messages for retry by default.

---

### Question 48 — Answer: C

**Why C is correct:** Service Control Policies (SCPs) are Organization-level policies that define the maximum available permissions for all accounts in an OU. They can DENY specific actions (like creating EC2 in unapproved regions) across all member accounts.

**Why others are wrong:**
- **A. Permission boundaries** — Limit maximum permissions for individual IAM identities within an account; not applied across an entire OU.
- **B. Config rules** — Detect non-compliance but do NOT prevent actions from occurring.
- **D. IAM policies on individual accounts** — Would require updating each account separately; not centralized.

---

### Question 49 — Answers: A, C

**Why A and C are correct:** Cost Optimization design principles include: implement expenditure awareness (track and understand costs) and adopt a consumption model (pay only for what you use, scale down when not needed).

**Why others are wrong:**
- **B.** "Automatically recover from failure" = Reliability pillar.
- **D.** "Perform operations as code" = Operational Excellence pillar.
- **E.** Choosing highest-performing resources regardless of cost is the OPPOSITE of cost optimization.

---

### Question 50 — Answer: B

**Why B is correct:** VMware Cloud on AWS runs the full VMware SDDC (vSphere, vSAN, NSX-T) on dedicated AWS bare-metal infrastructure. Customers use the same VMware tools and processes — zero re-platforming required.

**Why others are wrong:**
- **A. AWS Outposts** — Brings AWS infrastructure and services on-premises; the opposite direction.
- **C. Server Migration Service** — Migrates VMs to EC2 as AMIs; requires re-platforming.
- **D. EC2 dedicated instances** — Run VMs on dedicated hardware but require rebuilding the environment for AWS, not running VMware natively.

---

### Question 51 — Answer: B

**Why B is correct:** S3 Lifecycle Policies define rules to automatically transition objects between storage classes based on age (e.g., move to S3-IA after 30 days, to Glacier after 90 days, delete after 7 years).

**Why others are wrong:**
- **A. Versioning** — Maintains multiple versions of objects; doesn't move objects between storage classes.
- **C. Intelligent-Tiering** — Automatically moves objects based on ACCESS PATTERNS, not time-based rules; has monitoring fees.
- **D. Object Lock** — Prevents deletion during a retention period; doesn't transition storage classes.

---

### Question 52 — Answer: C

**Why C is correct:** AWS Free Tier has three types: (1) Always Free (Lambda 1M requests/month, DynamoDB 25GB storage), (2) 12-month free (EC2 t2.micro 750 hrs/month, S3 5GB), and (3) Trials (short-term trials of specific services).

**Why others are wrong:**
- **A.** Free Tier is 12 months from account creation (for the time-limited offers), not 3 years.
- **B.** Not all services are in the Free Tier; many require payment from the first use.
- **D.** EC2 Free Tier is limited to 750 hours/month of t2.micro or t3.micro in Linux — not unlimited.

---

### Question 53 — Answer: C

**Why C is correct:** VPC Peering is a direct network connection between two VPCs (same or different accounts/regions) using private IP addresses. It's simple to set up — create a peering connection and update route tables.

**Why others are wrong:**
- **A. Site-to-Site VPN** — Designed for connecting on-premises to AWS; adds unnecessary complexity for VPC-to-VPC.
- **B. Transit Gateway** — Better for connecting 5+ VPCs in a hub-and-spoke model; more complex for just two VPCs.
- **D. Direct Connect** — For on-premises to AWS private connectivity; not for VPC-to-VPC.

---

### Question 54 — Answer: C

**Why C is correct:** Amazon GuardDuty is a managed threat detection service that continuously analyzes CloudTrail management events, VPC Flow Logs, and DNS logs using ML and threat intelligence feeds to identify threats.

**Why others are wrong:**
- **A. Inspector** — Scans for software vulnerabilities and network exposure in EC2/containers.
- **B. Security Hub** — Aggregates and normalizes security findings from multiple services (including GuardDuty); doesn't do the detection itself.
- **D. Macie** — Discovers and protects sensitive data (PII, credentials) in S3 buckets.

---

### Question 55 — Answer: D

**Why D is correct:** Multi-site active-active runs the full production workload simultaneously in multiple locations. Failover is instantaneous — RTO and RPO approach zero (seconds to minutes).

**Why others are wrong:**
- **A. Backup and restore** — Highest RTO/RPO (hours to days); lowest cost but slowest recovery.
- **B. Pilot light** — Core systems are running but not at full scale; RTO of hours.
- **C. Warm standby** — Scaled-down but fully functional environment; RTO of minutes to hours.

**DR Strategy comparison:** Backup & Restore < Pilot Light < Warm Standby < Multi-site Active-Active (in terms of cost, RTO, and RPO from slowest/cheapest to fastest/most expensive).

---

### Question 56 — Answers: A, C

**Why A and C are correct:** CloudFront is designed for: caching static website content (HTML, CSS, images) at edge locations and distributing large file downloads (software, games, media) globally with low latency.

**Why others are wrong:**
- **B.** CloudFront doesn't run database queries; it's a CDN, not a database service.
- **D.** CloudFront doesn't replace RDS; it has no database functionality.
- **E.** VPC provides network isolation; CloudFront is a content delivery service — no overlap.

---

### Question 57 — Answer: C

**Why C is correct:** The pattern is: AWS Config detects non-compliant resources (public S3 bucket) using managed Config Rules → triggers an AWS Lambda function → Lambda uses the S3 API to remove public access. This is the standard automated compliance remediation pattern.

**Why others are wrong:**
- **A. Inspector** — Scans EC2 for vulnerabilities; doesn't monitor S3 bucket policies.
- **B. Systems Manager** — Better for EC2 operations like patch management; not the right tool for S3 compliance.
- **D. GuardDuty + CloudTrail** — GuardDuty detects threats but doesn't enforce S3 bucket configurations; CloudTrail logs actions but doesn't remediate.

---

### Question 58 — Answer: C

**Why C is correct:** Memory Optimized instances (R-family for large memory, X-family for very large memory, z-family for high-frequency) provide high memory-to-vCPU ratios — purpose-built for in-memory databases like SAP HANA, Redis clusters, and HPC.

**Why others are wrong:**
- **A. Compute Optimized (C)** — High CPU-to-memory ratio; for compute-intensive workloads (HPC, gaming servers, scientific modeling).
- **B. General Purpose (M)** — Balanced CPU/memory for most workloads; not specialized for memory-heavy requirements.
- **D. Storage Optimized (I, D)** — High sequential disk I/O and storage throughput; for data warehousing, Hadoop, distributed file systems.

---

### Question 59 — Answer: B

**Why B is correct:** Enabling EBS encryption by default in account/region settings (under EC2 settings) ensures all NEW EBS volumes and snapshots are automatically encrypted with your default KMS key — zero additional effort per volume.

**Why others are wrong:**
- **A.** Third-party tools add complexity, licensing cost, and performance overhead.
- **C.** Application-level encryption requires significant development effort and doesn't protect the storage layer.
- **D.** S3 encryption is for S3 objects; it has no bearing on EBS volumes — completely different storage services.

---

### Question 60 — Answer: C

**Why C is correct:** Amazon EMR (Elastic MapReduce) provides managed clusters running Apache Hadoop, Apache Spark, HBase, Presto, and other big data frameworks, with automatic provisioning and scaling.

**Why others are wrong:**
- **A. Kinesis** — Real-time streaming data ingestion and processing; not batch Hadoop/Spark.
- **B. AWS Glue** — Serverless ETL service; good for data cataloging and transformation but not a full Spark cluster manager.
- **D. Athena** — Serverless interactive SQL queries directly on S3 data using Presto; not a full Hadoop/Spark cluster.

---

### Question 61 — Answer: C

**Why C is correct:** Trusted Advisor access is tiered: Basic and Developer plans get 7 core checks (basic security and limits). Business and Enterprise plans get access to ALL 200+ checks across all 5 categories.

**Why others are wrong:**
- **A.** Core checks are available to all plans, including Basic — no Enterprise requirement.
- **B.** Not all checks are available on all plans — full access requires Business or Enterprise.
- **D.** Trusted Advisor covers 5 pillars: Cost Optimization, Security, Fault Tolerance, Performance, Service Limits — not just security.

---

### Question 62 — Answer: D

**Why D is correct:** A Technical Account Manager (TAM) is exclusively available with the Enterprise Support Plan (and Enterprise On-Ramp). The TAM provides proactive, personalized guidance, architectural reviews, and is the primary AWS contact.

**Why others are wrong:**
- **A. Basic** — No technical support at all.
- **B. Developer** — Business-hours email support; no TAM.
- **C. Business** — 24/7 support engineers access; NO dedicated TAM.

---

### Question 63 — Answers: B, D

**Why B and D are correct:** Reducing attack surface: (1) Remove unnecessary software, services, and open ports — less running code means fewer potential vulnerabilities. (2) Configure Security Groups with the minimum required ports/protocols open.

**Why others are wrong:**
- **A.** Assigning additional IP addresses (IPv6) expands the attack surface, not reduces it.
- **C.** Public subnets expose instances to the internet; private subnets reduce attack surface.
- **E.** Disabling VPC Flow Logs removes visibility for threat detection — reducing security monitoring, not the attack surface.

---

### Question 64 — Answer: C

**Why C is correct:** Scheduled Reserved Instances let you reserve capacity for a specific recurring time window (e.g., nightly 2 AM–6 AM, daily) at a discounted price versus On-Demand. The workload is predictable, non-interruptible, and not 24/7 — making this the ideal option.

**Why others are wrong:**
- **A. On-Demand** — No discount; the most expensive option for this regular workload.
- **B. Spot** — Can be interrupted; unacceptable for a critical batch job that "cannot be interrupted."
- **D. Dedicated Hosts** — For compliance/licensing requirements; overkill and most expensive option.

---

### Question 65 — Answer: B

**Why B is correct:** AWS Control Tower automates the setup of a secure, well-architected multi-account AWS environment (called a landing zone) with pre-configured guardrails (preventive SCPs and detective Config rules), centralized logging, and an Account Factory for automated account vending.

**Why others are wrong:**
- **A. Organizations** — The foundational service that Control Tower is built on, but doesn't provide automated landing zone setup or guardrails out of the box.
- **C. Config** — Detects configuration drift; doesn't provision accounts or set up landing zones.
- **D. Service Catalog** — Manages a catalog of approved AWS products/templates; not for multi-account governance at the organizational level.

---

---

## Scoring Guide

| Score | Result | Readiness |
|-------|--------|-----------|
| 80–100% | Excellent | Very strong readiness for the real exam |
| 70–79% | Pass | Good readiness; review weak areas |
| 60–69% | Borderline | Review all explanations; retake in 1–2 weeks |
| Below 60% | Needs work | Study the AWS Cloud Practitioner course materials before retaking |

---

## Topic Coverage Summary

| Domain | Questions Covered |
|--------|------------------|
| Cloud Concepts | 1, 2, 11, 13, 50, 55 |
| Security & Compliance | 4, 7, 12, 14, 18, 21, 22, 25, 30, 31, 34, 35, 39, 48, 54, 57, 59, 63 |
| Networking | 5, 9, 26, 29, 33, 37, 42, 53, 56 |
| Compute | 8, 10, 23, 32, 38, 40, 46, 47, 58, 60 |
| Storage | 3, 15, 30, 45, 51 |
| Database | 6, 19, 36 |
| Billing & Pricing | 17, 20, 24, 28, 44, 52, 61, 62, 64 |
| Well-Architected Framework | 16, 27, 41, 49, 65 |
| Monitoring | 4, 43 |

---

*This mock exam is designed to reflect the difficulty and style of the real AWS Certified Cloud Practitioner (CLF-C02) exam. Scoring 75%+ on this mock exam indicates strong readiness for the certification.*
