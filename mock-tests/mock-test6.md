# AWS Certified Cloud Practitioner (CLF-C02) — Full Mock Exam
### 65 Questions | Time Allowed: 90 Minutes | Passing Score: ~70%

> **Instructions:** Read each question carefully. For single-answer questions, select the ONE best answer. For multi-answer questions, select exactly the number of answers specified. Unanswered questions are marked incorrect.

---

# SECTION 1 — QUESTIONS

---

### Question 1 *(Choose ONE)*

A company currently hosts its applications in an on-premises data center. The IT team is concerned about unpredictable traffic spikes that frequently cause the servers to run at full capacity. The team wants a solution that automatically adjusts compute capacity based on demand without requiring manual intervention.

Which AWS Cloud concept BEST describes this requirement?

- A. High Availability
- B. Fault Tolerance
- C. Elasticity
- D. Durability

---

### Question 2 *(Choose ONE)*

A startup company is evaluating whether to move its workloads to AWS. The CFO wants to understand the financial model difference between on-premises infrastructure and AWS Cloud.

Which statement BEST describes a key financial benefit of moving to AWS Cloud?

- A. AWS eliminates all IT operational expenses entirely.
- B. AWS converts large upfront capital expenditures (CapEx) into smaller variable operational expenditures (OpEx).
- C. AWS guarantees that total infrastructure costs will always be lower than on-premises.
- D. AWS allows companies to stop paying for software licenses permanently.

---

### Question 3 *(Choose TWO)*

A financial services company wants to ensure its AWS environment follows security best practices. The security team is reviewing the AWS Shared Responsibility Model.

Which of the following are the CUSTOMER'S responsibilities under the AWS Shared Responsibility Model? *(Choose TWO)*

- A. Patching the underlying EC2 hypervisor
- B. Configuring IAM user permissions and policies
- C. Maintaining the physical security of AWS data centers
- D. Encrypting data stored in Amazon S3 buckets
- E. Replacing failed hardware components in AWS infrastructure

---

### Question 4 *(Choose ONE)*

A solutions architect is designing an application that must remain operational even if an entire AWS Availability Zone becomes unavailable. The architect wants to achieve this with the LEAST operational overhead.

Which approach BEST meets this requirement?

- A. Deploy the application in a single EC2 instance with enhanced networking enabled.
- B. Enable CloudWatch alarms to automatically restart the EC2 instance if it fails.
- C. Deploy the application across multiple Availability Zones using an Elastic Load Balancer.
- D. Use AWS CloudFront to cache application content globally.

---

### Question 5 *(Choose ONE)*

A company wants to give a third-party auditing firm temporary, read-only access to specific AWS resources for compliance purposes. The company does not want to create long-term IAM user credentials for the auditors.

What is the MOST secure way to grant this access?

- A. Create an IAM user with read-only permissions and share the credentials with the auditing firm.
- B. Share the company's AWS root account credentials with the auditing firm.
- C. Create an IAM role with read-only permissions and allow the auditing firm to assume the role.
- D. Configure a new AWS account and grant the auditing firm full administrator access.

---

### Question 6 *(Choose ONE)*

A company is running a web application on Amazon EC2 instances. The application receives consistent, predictable traffic 24 hours a day, 7 days a week, for the next 3 years. The company wants to MINIMIZE costs.

Which EC2 purchasing option should the company choose?

- A. On-Demand Instances
- B. Spot Instances
- C. Reserved Instances (1-year or 3-year term)
- D. Dedicated Hosts

---

### Question 7 *(Choose TWO)*

A company is building a data processing pipeline. The workloads are stateless, fault-tolerant, and can be interrupted and restarted without data loss. The jobs typically run for 2–4 hours.

Which EC2 purchasing options are MOST cost-effective for this use case? *(Choose TWO)*

- A. On-Demand Instances
- B. Spot Instances
- C. Reserved Instances
- D. Dedicated Instances
- E. Savings Plans

---

### Question 8 *(Choose ONE)*

A developer needs to run a small piece of code that processes thumbnail images every time a new image is uploaded to Amazon S3. The code runs for less than 15 minutes and is triggered infrequently.

Which AWS service is the MOST cost-effective and operationally efficient for this requirement?

- A. Amazon EC2 with Auto Scaling
- B. AWS Elastic Beanstalk
- C. AWS Lambda
- D. Amazon ECS with Fargate

---

### Question 9 *(Choose ONE)*

A company's security team wants to ensure that all API calls made to AWS services in their account are logged, including the identity of the caller, the time of the call, and the source IP address.

Which AWS service provides this capability?

- A. Amazon CloudWatch
- B. AWS CloudTrail
- C. AWS Config
- D. Amazon Inspector

---

### Question 10 *(Choose TWO)*

A company is designing its AWS network architecture. The security team requires that EC2 instances in a private subnet must be able to access the internet to download software updates, but internet users should NOT be able to initiate connections to those instances.

Which TWO components are required to achieve this? *(Choose TWO)*

- A. Internet Gateway
- B. NAT Gateway
- C. Network Access Control List (NACL)
- D. Security Group with inbound rules open to 0.0.0.0/0
- E. Route table with a route to the NAT Gateway

---

### Question 11 *(Choose ONE)*

A company stores sensitive customer data in Amazon S3. The security team wants to ensure that data is encrypted at rest using keys that the company fully controls, including the ability to rotate and audit key usage.

Which AWS service should the company use to manage these encryption keys?

- A. AWS Certificate Manager (ACM)
- B. AWS Secrets Manager
- C. AWS Key Management Service (KMS)
- D. AWS CloudHSM

---

### Question 12 *(Choose ONE)*

An e-commerce company's website experiences extremely high traffic during Black Friday and Cyber Monday, but normal traffic for the remaining 10 months. The company wants to ensure the infrastructure scales automatically without paying for unused capacity during normal periods.

Which AWS Cloud benefit BEST addresses this scenario?

- A. Global reach
- B. Economies of scale
- C. Elasticity
- D. High availability

---

### Question 13 *(Choose THREE)*

A company is evaluating AWS Cloud against its current on-premises data center. The team wants to understand the cost components that would be ELIMINATED when migrating to AWS.

Which of the following are costs that are eliminated when moving to AWS? *(Choose THREE)*

- A. Purchasing and maintaining physical server hardware
- B. Paying for electricity to power and cool data center equipment
- C. AWS data transfer fees between services in the same Region
- D. Physical data center facility costs (rent, utilities, security staff)
- E. Costs for AWS EC2 compute usage
- F. Costs for developing and maintaining application code

---

### Question 14 *(Choose ONE)*

A company has multiple AWS accounts across different departments. The company wants to centrally manage billing, apply governance policies across all accounts, and share reserved capacity.

Which AWS service should the company use?

- A. AWS Control Tower
- B. AWS Organizations
- C. AWS Service Catalog
- D. AWS Config

---

### Question 15 *(Choose ONE)*

A company's web application is experiencing latency issues for users located in Asia and South America, even though the application is hosted in the US East (N. Virginia) Region. The company wants to reduce latency for global users with MINIMAL changes to the application.

Which AWS service should the company use?

- A. AWS Direct Connect
- B. Amazon Route 53 with simple routing
- C. Amazon CloudFront
- D. AWS Global Accelerator

---

### Question 16 *(Choose ONE)*

A security engineer is reviewing access controls for a company's AWS environment. The engineer wants to implement a control that evaluates traffic at the subnet level, is stateless, and supports both allow and deny rules.

Which AWS networking feature should the engineer configure?

- A. Security Groups
- B. Network Access Control Lists (NACLs)
- C. AWS WAF
- D. AWS Shield

---

### Question 17 *(Choose TWO)*

A company is planning its cloud migration strategy. The CTO wants to understand what AWS is responsible for managing as part of the AWS Shared Responsibility Model.

Which of the following are AWS responsibilities? *(Choose TWO)*

- A. Configuring IAM policies for users
- B. Patching the guest operating system on EC2 instances
- C. Maintaining the physical security of data center facilities
- D. Patching and maintaining the underlying hypervisor infrastructure
- E. Enabling MFA on the root account

---

### Question 18 *(Choose ONE)*

A company wants to migrate its on-premises Oracle database to a fully managed AWS database service with automatic backups, automated patching, and Multi-AZ support.

Which AWS service is MOST appropriate?

- A. Amazon DynamoDB
- B. Amazon Redshift
- C. Amazon RDS
- D. Amazon ElastiCache

---

### Question 19 *(Choose ONE)*

A developer is building an application that requires a highly scalable, fully managed NoSQL database that can handle millions of requests per second with single-digit millisecond latency.

Which AWS database service should the developer choose?

- A. Amazon RDS for MySQL
- B. Amazon DynamoDB
- C. Amazon Aurora
- D. Amazon Redshift

---

### Question 20 *(Choose ONE)*

A company wants to receive automated recommendations to help right-size their EC2 instances, identify idle resources, and check for security best practices in their AWS environment — all without any additional setup.

Which AWS service provides these recommendations?

- A. AWS Cost Explorer
- B. Amazon CloudWatch
- C. AWS Trusted Advisor
- D. AWS Compute Optimizer

---

### Question 21 *(Choose TWO)*

A company's compliance officer wants to ensure that all Amazon S3 buckets in the organization are never made publicly accessible. The officer wants this policy enforced automatically, even if someone tries to change it.

Which TWO services can help enforce this policy? *(Choose TWO)*

- A. Amazon Inspector
- B. AWS Config with managed rules
- C. AWS Organizations Service Control Policies (SCPs)
- D. Amazon Macie
- E. AWS CloudTrail

---

### Question 22 *(Choose ONE)*

A company is designing a disaster recovery strategy for its critical workloads. The recovery time objective (RTO) is 4 hours and the recovery point objective (RPO) is 1 hour. The company wants the MOST cost-effective approach.

Which disaster recovery strategy BEST meets these requirements?

- A. Multi-Site Active/Active
- B. Warm Standby
- C. Pilot Light
- D. Backup and Restore

---

### Question 23 *(Choose ONE)*

A company has a fleet of EC2 instances running a web application. The operations team wants to automatically detect when CPU utilization exceeds 80% and send an email alert to the team.

Which combination of AWS services should the team use?

- A. AWS CloudTrail and Amazon SES
- B. Amazon CloudWatch and Amazon SNS
- C. AWS Config and Amazon SQS
- D. AWS Trusted Advisor and Amazon SES

---

### Question 24 *(Choose ONE)*

A company is choosing between AWS Direct Connect and AWS Site-to-Site VPN to connect its on-premises data center to AWS. The company requires a consistent, low-latency, high-bandwidth connection that does not traverse the public internet.

Which connection type should the company choose?

- A. AWS Site-to-Site VPN, because it is faster and more reliable
- B. AWS Direct Connect, because it provides a dedicated private connection
- C. Amazon CloudFront, because it reduces latency by caching at edge locations
- D. AWS Transit Gateway, because it connects multiple VPCs together

---

### Question 25 *(Choose TWO)*

A company wants to reduce its AWS costs. The cloud finance team is looking for specific ways to optimize spending on EC2 workloads that run continuously.

Which TWO options would MOST effectively reduce EC2 costs for continuous workloads? *(Choose TWO)*

- A. Use Reserved Instances for workloads with predictable, steady-state usage
- B. Enable Auto Scaling to replace all EC2 instances with Lambda functions
- C. Purchase Compute Savings Plans for flexible savings across instance types and sizes
- D. Enable EC2 instance termination protection
- E. Use On-Demand Instances with EBS-optimized storage

---

### Question 26 *(Choose ONE)*

A global retail company wants to use an AWS service to analyze customer reviews and automatically detect the language and sentiment (positive, negative, neutral) of each review.

Which AWS AI/ML service should the company use?

- A. Amazon Rekognition
- B. Amazon Polly
- C. Amazon Comprehend
- D. Amazon Lex

---

### Question 27 *(Choose ONE)*

A company's application stores user session data and needs a caching layer that provides sub-millisecond read performance to reduce load on the primary database.

Which AWS service is MOST appropriate?

- A. Amazon RDS with Read Replicas
- B. Amazon ElastiCache
- C. Amazon DynamoDB Accelerator (DAX)
- D. Amazon Redshift

---

### Question 28 *(Choose ONE)*

According to the AWS Well-Architected Framework, which pillar focuses on preventing unnecessary costs and achieving the best business outcome at the lowest price point?

- A. Operational Excellence
- B. Performance Efficiency
- C. Reliability
- D. Cost Optimization

---

### Question 29 *(Choose TWO)*

A company wants to protect its web application running on AWS from common web exploits such as SQL injection and cross-site scripting (XSS) attacks. The company also wants to block traffic from specific countries.

Which TWO AWS services should the company use? *(Choose TWO)*

- A. AWS Shield Standard
- B. AWS WAF
- C. Amazon GuardDuty
- D. Amazon Inspector
- E. AWS Firewall Manager (with WAF rules applied geographically)

---

### Question 30 *(Choose ONE)*

A company is building a new application and wants to follow the AWS Well-Architected Framework principle of "Design for failure." The team wants to ensure that no single EC2 instance failure causes a complete outage.

Which architectural pattern BEST demonstrates this principle?

- A. Run a single large EC2 instance with maximum RAM and CPU.
- B. Deploy multiple EC2 instances across multiple Availability Zones behind an Elastic Load Balancer.
- C. Enable detailed CloudWatch monitoring on a single EC2 instance.
- D. Store all application data in Amazon RDS with automated backups enabled.

---

### Question 31 *(Choose ONE)*

A company is migrating workloads to AWS and wants to estimate the total cost of ownership (TCO) before migration. The team wants to compare on-premises infrastructure costs with AWS costs.

Which AWS tool should the company use?

- A. AWS Cost Explorer
- B. AWS Pricing Calculator
- C. AWS TCO Calculator (Migration Evaluator)
- D. AWS Budgets

---

### Question 32 *(Choose ONE)*

A company wants to store large amounts of infrequently accessed data, such as compliance archives, for a minimum of 7 years. The company requires the lowest possible storage cost and does not need immediate retrieval.

Which Amazon S3 storage class is MOST cost-effective?

- A. S3 Standard
- B. S3 Intelligent-Tiering
- C. S3 Glacier Flexible Retrieval
- D. S3 Glacier Deep Archive

---

### Question 33 *(Choose TWO)*

A company uses Amazon EC2 instances and Amazon RDS databases. The operations team wants to back up all resources consistently and manage backup policies centrally.

Which TWO statements about AWS Backup are correct? *(Choose TWO)*

- A. AWS Backup requires separate configuration for each individual AWS service.
- B. AWS Backup provides a centralized console to manage backup policies across multiple AWS services.
- C. AWS Backup supports automated backup scheduling and retention management.
- D. AWS Backup can only back up Amazon EC2 instances, not database services.
- E. AWS Backup requires the use of AWS Lambda to trigger backup jobs.

---

### Question 34 *(Choose ONE)*

A company is building a microservices architecture on AWS. Each microservice must be able to communicate with the others asynchronously, and messages should be stored if a receiving service is temporarily unavailable.

Which AWS service is MOST appropriate for this use case?

- A. Amazon SNS
- B. Amazon SQS
- C. Amazon Kinesis
- D. AWS EventBridge

---

### Question 35 *(Choose ONE)*

A company's compliance team is auditing AWS resource configurations. They want to check whether all EC2 instances have encryption enabled on their EBS volumes and receive automatic alerts when non-compliant resources are found.

Which AWS service should the team use?

- A. Amazon Inspector
- B. AWS Trusted Advisor
- C. AWS Config
- D. Amazon GuardDuty

---

### Question 36 *(Choose ONE)*

A company is designing its VPC architecture. The team wants to allow resources in a private subnet to communicate with resources in another VPC without traffic leaving the AWS network and without using an Internet Gateway.

Which AWS networking feature should the team use?

- A. AWS Direct Connect
- B. VPC Peering
- C. NAT Gateway
- D. AWS VPN CloudHub

---

### Question 37 *(Choose TWO)*

A company wants to implement the principle of least privilege for its AWS environment. The security team is implementing IAM best practices.

Which TWO actions align with the principle of least privilege? *(Choose TWO)*

- A. Attach the `AdministratorAccess` managed policy to all IAM users by default.
- B. Grant IAM users only the permissions they need to perform their specific job functions.
- C. Create IAM policies that deny all actions and whitelist only required actions.
- D. Share IAM root account credentials with senior engineers for convenience.
- E. Use IAM groups to manage permissions for users with similar job roles.

---

### Question 38 *(Choose ONE)*

A company wants to run containers in AWS without managing any servers or clusters. The team wants a fully serverless container solution.

Which AWS service meets this requirement?

- A. Amazon ECS with EC2 launch type
- B. Amazon EKS with EC2 node groups
- C. AWS Fargate
- D. AWS Lambda

---

### Question 39 *(Choose ONE)*

A company is evaluating the benefits of migrating to AWS. The team is concerned about paying for large amounts of compute capacity that sits idle during off-peak hours in their on-premises data center.

Which AWS Cloud advantage directly addresses this concern?

- A. Increased speed and agility
- B. Go global in minutes
- C. Trade fixed expense for variable expense
- D. Benefit from massive economies of scale

---

### Question 40 *(Choose THREE)*

A company wants to monitor the health and performance of its AWS environment. The team needs visibility into infrastructure metrics, application logs, and AWS API activity.

Which THREE AWS services collectively provide this monitoring capability? *(Choose THREE)*

- A. Amazon CloudWatch (metrics and alarms)
- B. AWS CloudTrail (API activity logging)
- C. AWS Trusted Advisor
- D. Amazon Inspector
- E. AWS CloudWatch Logs (application and service logs)
- F. Amazon Macie

---

### Question 41 *(Choose ONE)*

A company needs to ensure that its S3 bucket used for a static website can only be accessed by users who are authenticated through the company's corporate identity provider (IdP) using SAML 2.0.

Which AWS service enables this federated authentication?

- A. AWS IAM with IAM users
- B. Amazon Cognito
- C. AWS Single Sign-On (AWS IAM Identity Center)
- D. AWS Directory Service

---

### Question 42 *(Choose ONE)*

According to the AWS Well-Architected Framework, which pillar is MOST focused on the ability to recover from failures and meet customer demand?

- A. Security
- B. Operational Excellence
- C. Reliability
- D. Performance Efficiency

---

### Question 43 *(Choose ONE)*

A company is running a business-critical application that requires a relational database with automatic failover across Availability Zones and up to 5× the throughput of standard MySQL.

Which AWS database service BEST meets this requirement?

- A. Amazon RDS for MySQL with Multi-AZ
- B. Amazon Aurora
- C. Amazon DynamoDB
- D. Amazon Redshift

---

### Question 44 *(Choose TWO)*

A company's finance team wants to track AWS spending and ensure that costs stay within budget. They want to receive automatic alerts when spending exceeds a defined threshold.

Which TWO AWS services should the finance team use? *(Choose TWO)*

- A. AWS Cost Explorer
- B. AWS Budgets
- C. AWS Trusted Advisor
- D. Amazon CloudWatch billing alarms
- E. AWS Pricing Calculator

---

### Question 45 *(Choose ONE)*

A company wants to protect its AWS infrastructure from large-scale Distributed Denial of Service (DDoS) attacks at the network and transport layers (Layer 3 and Layer 4) at no additional charge.

Which AWS service provides this protection automatically?

- A. AWS WAF
- B. AWS Shield Advanced
- C. AWS Shield Standard
- D. Amazon GuardDuty

---

### Question 46 *(Choose ONE)*

A company has deployed a web application using Amazon EC2 instances behind an Application Load Balancer. The team wants to ensure that the EC2 instances are NOT directly accessible from the internet.

Which VPC design ensures this?

- A. Place the EC2 instances in a public subnet and use Security Groups to restrict access.
- B. Place the EC2 instances in a private subnet with no direct internet access; only the ALB is in the public subnet.
- C. Disable the Internet Gateway for the entire VPC.
- D. Use AWS WAF to block all direct internet traffic to EC2 instances.

---

### Question 47 *(Choose ONE)*

A company is using AWS and wants to ensure its multi-account structure follows best practices. The team wants to create and manage new AWS accounts programmatically, enforce governance policies, and apply Service Control Policies (SCPs).

Which AWS service is designed for this purpose?

- A. AWS Config
- B. AWS IAM
- C. AWS Organizations
- D. AWS Control Tower

---

### Question 48 *(Choose TWO)*

A company wants to migrate its on-premises Microsoft Active Directory to AWS so that employees can use their existing corporate credentials to sign in to AWS applications.

Which TWO AWS services can help accomplish this? *(Choose TWO)*

- A. AWS Directory Service (Managed Microsoft AD)
- B. Amazon Cognito
- C. AWS IAM Identity Center (SSO) with Active Directory integration
- D. AWS Key Management Service (KMS)
- E. AWS Organizations

---

### Question 49 *(Choose ONE)*

A startup is building a new mobile application. The development team wants to focus entirely on writing application code without managing or provisioning any servers, databases, or infrastructure.

Which cloud computing model BEST describes this approach?

- A. Infrastructure as a Service (IaaS)
- B. Platform as a Service (PaaS)
- C. Software as a Service (SaaS)
- D. Serverless computing

---

### Question 50 *(Choose ONE)*

A company wants to analyze petabytes of structured data from multiple sources to generate business intelligence reports. The team needs a fully managed cloud data warehouse service.

Which AWS service should the company use?

- A. Amazon RDS
- B. Amazon DynamoDB
- C. Amazon Redshift
- D. Amazon EMR

---

### Question 51 *(Choose ONE)*

A company's security team discovers that an IAM user's access keys have been accidentally published to a public GitHub repository. What should the team do FIRST?

- A. Delete the IAM user account immediately.
- B. Rotate the access keys and deactivate the compromised keys immediately.
- C. Contact AWS Support and ask them to disable the keys.
- D. Change the IAM user's password.

---

### Question 52 *(Choose TWO)*

A company wants to improve the reliability of its application hosted on AWS. According to the AWS Well-Architected Framework's Reliability pillar, which TWO practices should the company implement? *(Choose TWO)*

- A. Deploy the application in multiple Availability Zones.
- B. Use Reserved Instances to reduce costs.
- C. Implement automated recovery from failure using AWS Auto Scaling.
- D. Reduce the number of AWS Regions used to simplify architecture.
- E. Use the cheapest EC2 instance type available.

---

### Question 53 *(Choose ONE)*

A company is considering the AWS Cloud for its new applications. The management team asks which of the following is NOT a direct benefit of using AWS Cloud.

Which option is NOT a benefit of the AWS Cloud?

- A. Increased speed and agility in deploying new applications
- B. Guaranteed elimination of all security vulnerabilities
- C. Ability to go global in minutes by deploying to multiple Regions
- D. Reduction in total cost of ownership compared to on-premises for many workloads

---

### Question 54 *(Choose ONE)*

A company is concerned about potential security threats in their AWS environment, such as unusual API calls, cryptocurrency mining activity, and unauthorized data exfiltration attempts. They want continuous threat detection.

Which AWS service provides this capability using machine learning?

- A. Amazon Inspector
- B. AWS Shield
- C. Amazon GuardDuty
- D. AWS Config

---

### Question 55 *(Choose TWO)*

A company uses Amazon Route 53 for DNS management. The team wants to route user traffic to the AWS Region with the lowest latency and also wants to configure health checks so that unhealthy endpoints are automatically removed.

Which TWO Route 53 features support this? *(Choose TWO)*

- A. Simple Routing Policy
- B. Latency-Based Routing Policy
- C. Geolocation Routing Policy
- D. Route 53 Health Checks
- E. Failover Routing Policy

---

### Question 56 *(Choose ONE)*

A company is running an application that stores files in Amazon S3. The team wants files that have not been accessed in 90 days to automatically move to a cheaper storage class.

Which S3 feature enables this?

- A. S3 Object Lock
- B. S3 Transfer Acceleration
- C. S3 Lifecycle Policies
- D. S3 Cross-Region Replication

---

### Question 57 *(Choose ONE)*

A company needs to extract text and data from scanned PDF documents and images to automate a manual data entry process.

Which AWS AI/ML service should the company use?

- A. Amazon Rekognition
- B. Amazon Textract
- C. Amazon Comprehend
- D. Amazon Transcribe

---

### Question 58 *(Choose THREE)*

A company is reviewing the benefits of AWS Cloud as part of a digital transformation initiative. The board of directors wants to know the key advantages of cloud computing.

Which THREE are recognized benefits of cloud computing according to AWS? *(Choose THREE)*

- A. Trading capital expense for variable expense
- B. Eliminating the need for application developers
- C. Benefiting from massive economies of scale
- D. Stopping guessing about capacity needs (elasticity)
- E. Guaranteed 100% uptime for all services
- F. Physical ownership of hardware assets

---

### Question 59 *(Choose ONE)*

A company runs a batch processing workload every Friday night for 4 hours. The job is fault-tolerant and can be restarted if interrupted. The company wants the MOST cost-effective compute option.

Which EC2 pricing model should the company use?

- A. On-Demand Instances
- B. Reserved Instances (1-year No Upfront)
- C. Spot Instances
- D. Dedicated Hosts

---

### Question 60 *(Choose ONE)*

A company has deployed an application across three Availability Zones. Despite this deployment, the application went offline when a critical dependency experienced an outage. The team wants to redesign the application to tolerate such failures.

Which AWS Well-Architected Framework pillar and principle BEST guides this redesign?

- A. Cost Optimization — implement serverless architectures
- B. Reliability — implement loose coupling and decoupled components
- C. Operational Excellence — automate operations with runbooks
- D. Performance Efficiency — choose the right instance type

---

### Question 61 *(Choose ONE)*

An organization stores highly sensitive personally identifiable information (PII) in Amazon S3. The security team wants to automatically discover and classify this data, and receive alerts if it becomes publicly accessible.

Which AWS service is designed specifically for this purpose?

- A. Amazon GuardDuty
- B. AWS Config
- C. Amazon Macie
- D. Amazon Inspector

---

### Question 62 *(Choose TWO)*

A company wants to reduce the cost of its AWS data transfer charges. The solutions architect is reviewing the current architecture.

Which TWO actions would REDUCE data transfer costs? *(Choose TWO)*

- A. Use Amazon CloudFront to cache and serve content from edge locations closer to users.
- B. Transfer data between AWS services in different Regions freely.
- C. Use S3 Transfer Acceleration for uploads.
- D. Keep data transfers within the same AWS Region (intra-Region) where possible.
- E. Enable Multi-AZ on Amazon RDS.

---

### Question 63 *(Choose ONE)*

A company is using AWS and wants to give its employees single sign-on (SSO) access to multiple AWS accounts and business applications (like Salesforce and Microsoft 365) using their existing corporate credentials.

Which AWS service should the company use?

- A. Amazon Cognito
- B. AWS IAM
- C. AWS IAM Identity Center (formerly AWS SSO)
- D. AWS Directory Service for Simple AD

---

### Question 64 *(Choose TWO)*

A company is migrating a large volume of data from an on-premises data center to Amazon S3. The data center has a slow internet connection, and the transfer would take months. The team wants to physically transfer the data.

Which TWO AWS services support physical data transfer to AWS? *(Choose TWO)*

- A. AWS Snowball Edge
- B. AWS Direct Connect
- C. AWS DataSync
- D. AWS Snowcone
- E. AWS Storage Gateway

---

### Question 65 *(Choose ONE)*

A company is planning a large-scale migration to AWS. The team wants a structured approach that assesses their current environment, provides migration recommendations, and identifies potential cost savings before the migration begins.

Which AWS program or tool is designed to help companies with pre-migration planning and portfolio assessment?

- A. AWS Well-Architected Tool
- B. AWS Migration Hub
- C. AWS Migration Evaluator (formerly TSO Logic)
- D. AWS Application Discovery Service

---

# SECTION 2 — ANSWER KEY

| Q# | Answer | Type |
|----|--------|------|
| 1  | C | Single |
| 2  | B | Single |
| 3  | B, D | Multi (2) |
| 4  | C | Single |
| 5  | C | Single |
| 6  | C | Single |
| 7  | B, E | Multi (2) |
| 8  | C | Single |
| 9  | B | Single |
| 10 | B, E | Multi (2) |
| 11 | C | Single |
| 12 | C | Single |
| 13 | A, B, D | Multi (3) |
| 14 | B | Single |
| 15 | C | Single |
| 16 | B | Single |
| 17 | C, D | Multi (2) |
| 18 | C | Single |
| 19 | B | Single |
| 20 | C | Single |
| 21 | B, C | Multi (2) |
| 22 | C | Single |
| 23 | B | Single |
| 24 | B | Single |
| 25 | A, C | Multi (2) |
| 26 | C | Single |
| 27 | B | Single |
| 28 | D | Single |
| 29 | B, E | Multi (2) |
| 30 | B | Single |
| 31 | C | Single |
| 32 | D | Single |
| 33 | B, C | Multi (2) |
| 34 | B | Single |
| 35 | C | Single |
| 36 | B | Single |
| 37 | B, E | Multi (2) |
| 38 | C | Single |
| 39 | C | Single |
| 40 | A, B, E | Multi (3) |
| 41 | C | Single |
| 42 | C | Single |
| 43 | B | Single |
| 44 | B, D | Multi (2) |
| 45 | C | Single |
| 46 | B | Single |
| 47 | C | Single |
| 48 | A, C | Multi (2) |
| 49 | D | Single |
| 50 | C | Single |
| 51 | B | Single |
| 52 | A, C | Multi (2) |
| 53 | B | Single |
| 54 | C | Single |
| 55 | B, D | Multi (2) |
| 56 | C | Single |
| 57 | B | Single |
| 58 | A, C, D | Multi (3) |
| 59 | C | Single |
| 60 | B | Single |
| 61 | C | Single |
| 62 | A, D | Multi (2) |
| 63 | C | Single |
| 64 | A, D | Multi (2) |
| 65 | C | Single |

---

# SECTION 3 — DETAILED EXPLANATIONS

---

### Q1 — Elasticity vs. Scalability
**Answer: C — Elasticity**

**Why C is correct:** Elasticity refers to the ability of a system to automatically scale resources up AND down based on real-time demand — adding capacity when demand spikes and releasing it when demand drops. The scenario describes unpredictable traffic spikes requiring automatic adjustment without manual intervention, which is the definition of elasticity.

**Why the others are wrong:**
- **A (High Availability):** Means the system remains operational despite failures — not about scaling capacity to match demand.
- **B (Fault Tolerance):** The ability to continue operating despite component failures, with zero or minimal impact.
- **D (Durability):** Refers to data persistence and protection against data loss (e.g., S3's 11 nines of durability).

**Exam Trap:** Many candidates confuse Elasticity with Scalability. *Scalability* is the ability to handle increased load (scale up/out), while *Elasticity* includes the automatic scaling DOWN as well — paying only for what you use.

---

### Q2 — CapEx vs. OpEx
**Answer: B**

**Why B is correct:** One of the primary cloud computing benefits documented by AWS is the conversion of large capital expenditures (CapEx — buying servers, building data centers) into smaller, variable operational expenditures (OpEx — paying per hour/GB/request). This improves cash flow and reduces financial risk.

**Why the others are wrong:**
- **A:** AWS does NOT eliminate all IT expenses — you still pay for compute, storage, and transfer.
- **C:** AWS does not guarantee lower costs — it *can* reduce costs, but workloads not optimized for cloud can actually cost more.
- **D:** AWS does not eliminate software licensing. AWS does offer License Included options and BYOL, but licenses still exist.

**Exam Trap:** Option C sounds appealing but is deliberately incorrect — cost savings are not *guaranteed*; they depend on workload optimization.

---

### Q3 — Shared Responsibility Model
**Answer: B, D**

**Why B and D are correct:** Under the Shared Responsibility Model, customers are responsible for **security IN the cloud**: IAM user permissions/policies (B) and encrypting data at rest in S3 (D) are both customer responsibilities.

**Why the others are wrong:**
- **A (Hypervisor patching):** AWS responsibility — "security OF the cloud."
- **C (Physical data center security):** AWS responsibility — customers never manage physical infrastructure.
- **E (Hardware replacement):** AWS responsibility.

**Exam Trap:** The exam often lists hardware and physical infrastructure tasks alongside customer tasks. Always remember: if it involves physical infrastructure or the underlying hypervisor, it's AWS's responsibility.

---

### Q4 — Multi-AZ High Availability
**Answer: C**

**Why C is correct:** Deploying across multiple Availability Zones (AZs) with an Elastic Load Balancer ensures that if one AZ goes down, traffic automatically routes to instances in other AZs. This provides high availability with minimal operational overhead as AWS manages the load balancing.

**Why the others are wrong:**
- **A:** A single instance in one AZ provides no protection against AZ failure.
- **B:** CloudWatch alarms can restart instances but cannot protect against an entire AZ outage.
- **D:** CloudFront caches static content but does not make the application itself highly available.

**Exam Trap:** Option D is tempting because CloudFront is a global service, but it's a CDN, not a high availability solution for compute.

---

### Q5 — IAM Roles for Third-Party Access
**Answer: C**

**Why C is correct:** IAM Roles with cross-account trust policies allow third parties to temporarily assume a role and gain only the permissions attached to that role. No long-term credentials are created. This is the most secure and AWS-recommended approach.

**Why the others are wrong:**
- **A:** Creating IAM users with shared credentials violates the principle of least privilege and creates a security risk if credentials are not rotated.
- **B:** NEVER share root account credentials — this violates every AWS security best practice.
- **D:** Creating a new account with full administrator access is extreme overprivilege.

**Exam Trap:** Option A seems reasonable but sharing IAM user credentials is an anti-pattern. IAM Roles with STS (Security Token Service) for temporary credentials is always preferred.

---

### Q6 — EC2 Reserved Instances for Steady-State Workloads
**Answer: C**

**Why C is correct:** For consistent, predictable 24/7 workloads running over 1–3 years, Reserved Instances provide the greatest discount (up to 72% vs On-Demand) in exchange for a term commitment. This is the textbook use case for Reserved Instances.

**Why the others are wrong:**
- **A (On-Demand):** Most flexible but most expensive for long-running workloads.
- **B (Spot):** Spot instances can be interrupted — not suitable for 24/7 production workloads requiring consistent availability.
- **D (Dedicated Hosts):** Used for compliance/licensing requirements; significantly more expensive than standard Reserved Instances.

**Exam Trap:** Spot Instances sound cheapest, but the scenario says "consistent, predictable traffic 24/7" — Spot can be interrupted, making it unsuitable here.

---

### Q7 — Spot Instances and Savings Plans for Fault-Tolerant Workloads
**Answer: B, E**

**Why B and E are correct:**
- **B (Spot Instances):** Stateless, fault-tolerant workloads that can be interrupted and restarted are the ideal use case for Spot Instances, which can be up to 90% cheaper than On-Demand.
- **E (Savings Plans):** Compute Savings Plans offer flexibility (apply to any instance family, size, Region) and significant discounts for committed usage. They are appropriate for background compute workloads.

**Why the others are wrong:**
- **A (On-Demand):** More expensive with no commitment required; not cost-optimized.
- **C (Reserved Instances):** Best for steady-state, predictable workloads requiring specific instance types — less flexible.
- **D (Dedicated Instances):** Used for compliance requirements; very expensive.

**Exam Trap:** Savings Plans (E) vs Reserved Instances (C) is a common confusion. Savings Plans are more flexible; Reserved Instances lock you into a specific instance family and Region.

---

### Q8 — AWS Lambda for Event-Driven Processing
**Answer: C**

**Why C is correct:** AWS Lambda is designed exactly for this use case: small, short-running code triggered by events (like S3 uploads). You pay only when the function runs, and Lambda scales automatically. No servers to manage.

**Why the others are wrong:**
- **A (EC2 with Auto Scaling):** Massively over-engineered for a simple event-driven task; you pay for EC2 even when idle.
- **B (Elastic Beanstalk):** A PaaS for long-running web applications — not suitable for infrequent, event-driven code.
- **D (ECS with Fargate):** Suitable for containerized microservices, but adds unnecessary complexity for this simple use case.

**Exam Trap:** ECS with Fargate sounds "serverless" and tempts candidates. Lambda is the correct answer for simple, short-duration event-driven functions.

---

### Q9 — AWS CloudTrail for API Logging
**Answer: B**

**Why B is correct:** AWS CloudTrail records every API call made in an AWS account — who made the call, when, from where, and what actions were taken. It is the audit log for AWS.

**Why the others are wrong:**
- **A (CloudWatch):** Monitors metrics (CPU, memory, network) and logs from applications/infrastructure — NOT API calls.
- **C (AWS Config):** Records configuration changes to AWS resources over time — different from logging API calls.
- **D (Amazon Inspector):** An automated security assessment service for EC2 instances and container images.

**Exam Trap:** CloudWatch vs CloudTrail is a frequent exam trap. Remember: **CloudTrail = WHO did WHAT to WHICH resource. CloudWatch = How is my infrastructure performing?**

---

### Q10 — NAT Gateway for Private Subnet Internet Access
**Answer: B, E**

**Why B and E are correct:**
- **B (NAT Gateway):** Allows instances in a private subnet to initiate outbound connections to the internet (for updates) while preventing inbound internet-initiated connections. The NAT Gateway is placed in a public subnet.
- **E (Route table with route to NAT Gateway):** The private subnet's route table must have a route directing internet-bound traffic (0.0.0.0/0) to the NAT Gateway.

**Why the others are wrong:**
- **A (Internet Gateway alone):** An IGW allows both inbound and outbound traffic — it does not protect against inbound connections.
- **C (NACL):** NACLs can filter traffic but don't enable outbound internet access for private subnets.
- **D (Security Group with 0.0.0.0/0):** Opening inbound rules to all traffic defeats the purpose of a private subnet.

**Exam Trap:** Candidates often include the Internet Gateway as an answer. The IGW is needed in the VPC, but the *private subnet* routes to the NAT Gateway, not the IGW directly.

---

### Q11 — AWS KMS for Customer-Managed Keys
**Answer: C**

**Why C is correct:** AWS KMS (Key Management Service) allows customers to create, manage, control, and audit cryptographic keys. It integrates with S3, EBS, RDS, and many other services to encrypt data at rest. Customers can rotate keys and use CloudTrail to audit key usage.

**Why the others are wrong:**
- **A (ACM):** Manages SSL/TLS certificates for HTTPS — not for data-at-rest encryption keys.
- **B (Secrets Manager):** Stores and rotates secrets (database passwords, API keys) — not a general encryption key service.
- **D (CloudHSM):** A dedicated hardware security module for customers needing FIPS 140-2 Level 3 compliance. More complex and expensive than KMS; KMS already provides customer-managed keys (CMKs).

**Exam Trap:** CloudHSM sounds more "secure" and might seem like the right answer. However, KMS with Customer Managed Keys (CMKs) meets the described requirements and is more operationally efficient for most use cases.

---

### Q12 — Elasticity for Variable Workloads
**Answer: C**

**Why C is correct:** Elasticity is the ability to automatically acquire and release resources based on demand. The Black Friday scenario — extreme peaks followed by very low traffic — is the classic example of where cloud elasticity eliminates the need to over-provision for peak loads.

**Why the others are wrong:**
- **A (Global reach):** About deploying to multiple Regions worldwide — not about scaling for demand.
- **B (Economies of scale):** AWS passes cost savings from its massive purchasing power to customers — a real benefit but not the one described.
- **D (High availability):** About surviving failures — not about matching capacity to demand fluctuations.

---

### Q13 — Costs Eliminated by Moving to AWS
**Answer: A, B, D**

**Why A, B, and D are correct:** When moving to AWS, the following on-premises costs are eliminated:
- **A:** No more purchasing servers, switches, storage hardware.
- **B:** No more electricity bills for running servers and cooling systems.
- **D:** No more data center rent, utilities, or physical security staff.

**Why the others are wrong:**
- **C:** Data transfer between services in the same Region is generally free, but this is an AWS cost, not an on-premises cost being eliminated.
- **E:** EC2 costs are *new* AWS costs that replace on-premises hardware costs — not eliminated.
- **F:** Application code development is needed whether on-premises or in the cloud.

**Exam Trap:** Option E is a trap — you still pay for EC2, you're just replacing CapEx with OpEx.

---

### Q14 — AWS Organizations for Multi-Account Management
**Answer: B**

**Why B is correct:** AWS Organizations is specifically designed to centrally manage multiple AWS accounts, consolidate billing (single bill for all accounts), share Reserved Instance benefits, and apply Service Control Policies (SCPs) to enforce governance.

**Why the others are wrong:**
- **A (Control Tower):** Built ON TOP of Organizations — it helps set up a multi-account environment with guardrails, but Organizations is the foundational service.
- **C (Service Catalog):** Manages approved product portfolios for teams — not multi-account governance.
- **D (Config):** Records resource configurations — not multi-account management.

**Exam Trap:** Control Tower vs Organizations. Control Tower provides a landing zone and uses Organizations underneath. The question asks about centrally managing billing, governance, and reserved capacity — Organizations is the direct answer.

---

### Q15 — Amazon CloudFront for Global Latency
**Answer: C**

**Why C is correct:** Amazon CloudFront is a Content Delivery Network (CDN) with 400+ edge locations globally. It caches content at edge locations close to users, dramatically reducing latency for users in Asia and South America without requiring the company to deploy infrastructure in those Regions.

**Why the others are wrong:**
- **A (Direct Connect):** A dedicated private connection between on-premises and AWS — doesn't help with global user latency.
- **B (Route 53 simple routing):** Routes DNS queries but doesn't reduce application latency.
- **D (Global Accelerator):** Also reduces latency, but uses the AWS global network backbone. CloudFront is specifically designed for content delivery and caching — which is "MINIMAL changes to the application."

**Exam Trap:** Global Accelerator is a valid answer for latency reduction but is for applications requiring static IP addresses or non-cacheable content. CloudFront is the more common answer for web applications and content delivery.

---

### Q16 — NACLs: Stateless Subnet-Level Firewall
**Answer: B**

**Why B is correct:** Network Access Control Lists (NACLs) are:
- Evaluated at the **subnet level** (not instance level)
- **Stateless** — you must explicitly define both inbound AND outbound rules
- Support both **ALLOW and DENY** rules

**Why the others are wrong:**
- **A (Security Groups):** Operate at the instance/ENI level, are *stateful* (return traffic automatically allowed), and only support ALLOW rules.
- **C (WAF):** Protects against web application attacks at Layer 7 — not a subnet-level firewall.
- **D (Shield):** DDoS protection — not a traffic filtering mechanism for subnets.

**Exam Trap:** Security Groups vs NACLs is a critical distinction. The key words "subnet level," "stateless," and "allow AND deny rules" point directly to NACLs.

---

### Q17 — AWS Shared Responsibility: AWS Responsibilities
**Answer: C, D**

**Why C and D are correct:**
- **C (Physical security of data centers):** AWS manages all physical infrastructure — fences, guards, biometrics, surveillance.
- **D (Hypervisor patching):** AWS manages the underlying virtualization infrastructure (hypervisor, firmware).

**Why the others are wrong:**
- **A (IAM policies):** Customer responsibility — customers control who has access to what.
- **B (Guest OS patching on EC2):** Customer responsibility — AWS gives you the OS but you must patch it (unlike managed services like RDS where AWS patches the DB engine).
- **E (Enabling MFA on root):** Customer responsibility — AWS cannot configure your account security settings for you.

---

### Q18 — Amazon RDS for Managed Relational Databases
**Answer: C**

**Why C is correct:** Amazon RDS supports Oracle, MySQL, PostgreSQL, SQL Server, and MariaDB with fully managed features: automated backups, automated patching, Multi-AZ high availability, and read replicas — exactly what the scenario describes.

**Why the others are wrong:**
- **A (DynamoDB):** A NoSQL database — not suitable for migrating an Oracle relational database.
- **B (Redshift):** A data warehouse for analytics — not for OLTP relational workloads.
- **D (ElastiCache):** An in-memory caching service (Redis/Memcached) — not a relational database.

---

### Q19 — Amazon DynamoDB for NoSQL at Scale
**Answer: B**

**Why B is correct:** DynamoDB is a fully managed, serverless NoSQL database that delivers single-digit millisecond performance at any scale. It can handle millions of requests per second and scales automatically.

**Why the others are wrong:**
- **A (RDS MySQL):** A relational database — does not offer single-digit millisecond latency at millions of requests per second without significant architecture work.
- **C (Aurora):** A relational database — high performance, but still SQL-based and not NoSQL.
- **D (Redshift):** A columnar data warehouse for analytics — not for high-throughput transactional workloads.

**Exam Trap:** Aurora sounds impressive and scalable, but it's still a relational (SQL) database. The question specifies "NoSQL."

---

### Q20 — AWS Trusted Advisor
**Answer: C**

**Why C is correct:** AWS Trusted Advisor provides automated recommendations across five categories: **Cost Optimization, Performance, Security, Fault Tolerance, and Service Limits**. It identifies idle EC2 instances, underutilized resources, and security misconfigurations — all "out of the box" with no setup.

**Why the others are wrong:**
- **A (Cost Explorer):** Visualizes past and projected AWS costs — it doesn't provide right-sizing recommendations.
- **B (CloudWatch):** Monitors metrics and creates alarms — it doesn't give architectural recommendations.
- **D (Compute Optimizer):** Provides EC2 right-sizing recommendations but is focused only on compute — not the full scope of security checks and cost checks that Trusted Advisor provides.

**Exam Trap:** Compute Optimizer specifically handles right-sizing, but Trusted Advisor is broader (also checks security, fault tolerance). The question asks for a service that checks right-sizing AND security AND idle resources.

---

### Q21 — Preventing Public S3 Buckets
**Answer: B, C**

**Why B and C are correct:**
- **B (AWS Config):** AWS Config managed rules (like `s3-bucket-public-read-prohibited`) continuously evaluate whether S3 buckets are publicly accessible and flag non-compliant resources. Auto-remediation can be configured.
- **C (SCPs via Organizations):** Service Control Policies can be applied across all accounts in an Organization to explicitly deny any action that makes S3 buckets public — enforced at the API level before any action succeeds.

**Why the others are wrong:**
- **A (Amazon Inspector):** Assesses EC2 instances and Lambda functions for software vulnerabilities — not S3 bucket policies.
- **D (Amazon Macie):** Discovers and classifies sensitive data in S3 — doesn't enforce public access controls.
- **E (CloudTrail):** Logs API calls but doesn't enforce or prevent actions.

---

### Q22 — Disaster Recovery Strategies
**Answer: C — Pilot Light**

**Why C is correct:** Pilot Light involves keeping a minimal version of the core system (database, critical services) running in AWS at all times. In the event of a disaster, you scale up the remaining components. This achieves an RTO of a few hours and a low RPO — balancing cost and recovery speed.

**DR Strategy Comparison:**
| Strategy | RTO | RPO | Cost |
|----------|-----|-----|------|
| Backup & Restore | Hours–Days | Hours | Lowest |
| Pilot Light | Hours | Minutes | Low |
| Warm Standby | Minutes | Seconds | Medium |
| Multi-Site Active/Active | Near-zero | Near-zero | Highest |

**Why A is wrong:** Multi-Site Active/Active meets near-zero RTO/RPO but is the most expensive — overkill for 4-hour RTO.
**Why D is wrong:** Backup & Restore is cheapest but typically has RTO and RPO measured in hours to days — may not meet a 1-hour RPO requirement.

---

### Q23 — CloudWatch + SNS for Monitoring and Alerts
**Answer: B**

**Why B is correct:** Amazon CloudWatch monitors EC2 CPU metrics. You create a CloudWatch Alarm that triggers when CPU > 80%. The alarm triggers an Amazon SNS (Simple Notification Service) topic, which sends an email notification to subscribers.

**Why the others are wrong:**
- **A (CloudTrail + SES):** CloudTrail logs API calls — doesn't monitor CPU metrics.
- **C (Config + SQS):** Config monitors configuration changes, not performance metrics; SQS is a queue, not a notification service.
- **D (Trusted Advisor + SES):** Trusted Advisor checks are periodic, not real-time metric monitoring.

---

### Q24 — AWS Direct Connect vs VPN
**Answer: B**

**Why B is correct:** AWS Direct Connect provides a dedicated, private physical connection from an on-premises location to AWS. It does NOT traverse the public internet, providing consistent low latency and high bandwidth — ideal for mission-critical, bandwidth-intensive workloads.

**Why the others are wrong:**
- **A (VPN):** Site-to-Site VPN creates an encrypted tunnel over the public internet — network performance varies based on internet conditions.
- **C (CloudFront):** A CDN — has nothing to do with on-premises connectivity.
- **D (Transit Gateway):** Connects multiple VPCs and on-premises networks together — it's a hub, not a connection type.

---

### Q25 — Reducing EC2 Costs for Continuous Workloads
**Answer: A, C**

**Why A and C are correct:**
- **A (Reserved Instances):** For specific EC2 instance types running 24/7 for 1–3 years, Reserved Instances offer up to 72% savings.
- **C (Compute Savings Plans):** Offer up to 66% savings with more flexibility (apply across any EC2 instance type, size, OS, and Region). Ideal for diverse or changing instance usage.

**Why the others are wrong:**
- **B:** Lambda and EC2 Auto Scaling are different services — you can't replace EC2 instances with Lambda using Auto Scaling.
- **D (Termination protection):** Prevents accidental termination — doesn't reduce costs.
- **E (On-Demand + EBS-Optimized):** EBS-Optimized improves storage performance, not cost; On-Demand is the baseline, most expensive option.

---

### Q26 — Amazon Comprehend for NLP
**Answer: C**

**Why C is correct:** Amazon Comprehend is a Natural Language Processing (NLP) service that uses machine learning to detect language, sentiment (positive, negative, neutral, mixed), entities, and key phrases in text — exactly what's needed for analyzing customer reviews.

**Why the others are wrong:**
- **A (Rekognition):** Analyzes images and videos — not text.
- **B (Polly):** Converts text to speech — not text analysis.
- **D (Lex):** Builds conversational chatbots — not for batch text sentiment analysis.

---

### Q27 — Amazon ElastiCache for Database Caching
**Answer: B**

**Why B is correct:** Amazon ElastiCache (Redis or Memcached) is an in-memory caching service that stores frequently accessed data in memory for sub-millisecond retrieval — dramatically reducing database load.

**Why the others are wrong:**
- **A (RDS Read Replicas):** Read replicas reduce read load on the primary database but still query from disk (millisecond range, not sub-millisecond).
- **C (DynamoDB DAX):** DynamoDB Accelerator is a caching layer specifically for DynamoDB — not a general-purpose cache for other databases.
- **D (Redshift):** A data warehouse for analytics — not a caching solution.

---

### Q28 — Well-Architected Framework: Cost Optimization
**Answer: D**

**Why D is correct:** The Cost Optimization pillar of the AWS Well-Architected Framework focuses on delivering business value at the lowest price point — including right-sizing resources, eliminating waste, and using appropriate pricing models.

**The Six Pillars:**
1. **Operational Excellence** — Run, monitor, and improve operations
2. **Security** — Protect data and systems
3. **Reliability** — Recover from failures, meet demand
4. **Performance Efficiency** — Use resources efficiently
5. **Cost Optimization** — Avoid unnecessary costs
6. **Sustainability** — Minimize environmental impact

---

### Q29 — AWS WAF and Firewall Manager
**Answer: B, E**

**Why B and E are correct:**
- **B (AWS WAF):** Web Application Firewall that protects against SQL injection, XSS, and other Layer 7 attacks. Geographic blocking is a WAF feature.
- **E (AWS Firewall Manager):** Centrally configures and manages WAF rules across multiple accounts and resources, including geographic (IP-based) rules.

**Why the others are wrong:**
- **A (Shield Standard):** Protects against DDoS at Layer 3/4 — not application-layer attacks like SQLi/XSS.
- **C (GuardDuty):** Threat detection for unusual account activity — not a traffic filtering/blocking service.
- **D (Inspector):** Software vulnerability assessment — not a web traffic filtering service.

---

### Q30 — Design for Failure (Multi-AZ + ELB)
**Answer: B**

**Why B is correct:** Deploying EC2 instances across multiple AZs behind an ELB is the textbook "design for failure" pattern. If one AZ goes down, the ELB routes traffic to instances in other AZs automatically.

**Why the others are wrong:**
- **A:** A single large instance is a single point of failure — the opposite of designing for failure.
- **C:** CloudWatch monitoring tells you about failures but doesn't prevent them.
- **D:** RDS with backups addresses data recovery, not compute availability.

---

### Q31 — AWS Migration Evaluator (TCO Calculator)
**Answer: C**

**Why C is correct:** AWS Migration Evaluator (formerly TSO Logic, and originally AWS TCO Calculator) is specifically designed to assess on-premises environments and compare costs with running equivalent workloads on AWS — helping organizations build a business case for cloud migration.

**Why the others are wrong:**
- **A (Cost Explorer):** Analyzes *existing* AWS spending — not pre-migration cost comparison.
- **B (Pricing Calculator):** Estimates costs for specific AWS services — useful but not for comprehensive TCO comparison.
- **D (Budgets):** Sets spending limits and alerts — not for pre-migration planning.

---

### Q32 — S3 Glacier Deep Archive
**Answer: D**

**Why D is correct:** S3 Glacier Deep Archive is the lowest-cost S3 storage class, designed for data that is rarely accessed and must be retained for 7–10+ years (regulatory compliance archives). Retrieval takes 12–48 hours, which is acceptable for compliance archives.

**S3 Storage Class Cost (Lowest to Highest):**
Deep Archive → Glacier Flexible Retrieval → S3-IA → S3 Standard-IA → S3 Intelligent-Tiering → S3 Standard

**Why the others are wrong:**
- **A (S3 Standard):** Most expensive — designed for frequently accessed data.
- **B (Intelligent-Tiering):** Automatically moves data between tiers but has monitoring costs — not optimal for data you know won't be accessed.
- **C (Glacier Flexible Retrieval):** Cheaper than Standard, but more expensive than Deep Archive.

---

### Q33 — AWS Backup
**Answer: B, C**

**Why B and C are correct:**
- **B:** AWS Backup provides a single console to define and manage backup policies across EC2, EBS, RDS, DynamoDB, EFS, S3, and more.
- **C:** AWS Backup supports automated scheduling (backup plans) and configurable retention periods.

**Why the others are wrong:**
- **A:** AWS Backup's purpose is *centralized* management — you don't need to configure each service separately.
- **D:** AWS Backup supports EC2, EBS, RDS, Aurora, DynamoDB, EFS, FSx, and more.
- **E:** No Lambda functions are required — it's a managed service.

---

### Q34 — Amazon SQS for Asynchronous Microservices
**Answer: B**

**Why B is correct:** Amazon SQS (Simple Queue Service) is a fully managed message queuing service that decouples microservices. Messages persist in the queue even if the receiving service is unavailable — ensuring no messages are lost. This is the classic asynchronous, decoupled microservices pattern.

**Why the others are wrong:**
- **A (SNS):** A pub/sub notification service — if a subscriber is unavailable when a message is published, the message is lost (unless combined with SQS).
- **C (Kinesis):** A real-time data streaming service — better for large-scale data streaming and analytics, not simple microservice messaging.
- **D (EventBridge):** An event bus for routing events — great for event-driven architectures but SNS+SQS is more appropriate for guaranteed message delivery between microservices.

---

### Q35 — AWS Config for Compliance Monitoring
**Answer: C**

**Why C is correct:** AWS Config records configuration of AWS resources and evaluates them against desired rules (e.g., "EBS volumes must be encrypted"). It can automatically alert when non-compliant resources are found and integrate with SSM Automation for auto-remediation.

**Why the others are wrong:**
- **A (Inspector):** Assesses software vulnerabilities (CVEs) in EC2 and Lambda — not configuration compliance.
- **B (Trusted Advisor):** Provides recommendations but doesn't continuously evaluate custom compliance rules.
- **D (GuardDuty):** Detects security threats (unusual behavior, malicious IPs) — not configuration compliance.

---

### Q36 — VPC Peering
**Answer: B**

**Why B is correct:** VPC Peering creates a network connection between two VPCs, allowing resources to communicate using private IP addresses. Traffic stays entirely within the AWS network — no Internet Gateway, VPN, or Direct Connect needed.

**Why the others are wrong:**
- **A (Direct Connect):** For connecting on-premises to AWS — not for VPC-to-VPC communication.
- **C (NAT Gateway):** Enables private subnet instances to access the internet outbound — not for VPC-to-VPC communication.
- **D (VPN CloudHub):** Connects multiple on-premises networks to AWS — hub-and-spoke for on-premises.

---

### Q37 — IAM Least Privilege Best Practices
**Answer: B, E**

**Why B and E are correct:**
- **B:** Granting only required permissions is the core definition of least privilege.
- **E:** IAM Groups allow you to assign permissions to all users with the same job role simultaneously — a best practice for managing permissions at scale.

**Why the others are wrong:**
- **A:** AdministratorAccess for all users is the opposite of least privilege — massive security risk.
- **C:** While creating deny-all-then-whitelist policies can achieve least privilege, this is not standard IAM practice and is overly complex. IAM policies typically use allow-only statements with scoped permissions.
- **D:** Sharing root credentials violates every security best practice — root should have MFA and never shared.

---

### Q38 — AWS Fargate for Serverless Containers
**Answer: C**

**Why C is correct:** AWS Fargate is a serverless compute engine for containers that works with both ECS and EKS. With Fargate, you don't provision, manage, or scale EC2 instances — AWS manages the underlying infrastructure. You simply define your container and run it.

**Why the others are wrong:**
- **A (ECS with EC2):** Requires managing EC2 instances (patching, scaling, cluster management).
- **B (EKS with EC2):** Requires managing EC2 node groups.
- **D (Lambda):** Serverless but NOT containers in the traditional sense — Lambda runs code, not arbitrary container workloads. Lambda has stricter limits (15 min max, 10GB memory).

**Exam Trap:** Lambda is "serverless" but is for functions/code, not running container workloads. Fargate is serverless FOR CONTAINERS.

---

### Q39 — Variable Expense vs Fixed Expense
**Answer: C**

**Why C is correct:** "Trade fixed expense for variable expense" means instead of paying upfront for servers (fixed cost regardless of usage), you pay only for what you use (variable cost). This directly addresses idle capacity in on-premises environments — you pay for idle servers but with AWS you don't.

**Why the others are wrong:**
- **A (Speed and agility):** About faster deployment, not cost structure.
- **B (Go global in minutes):** About geographic deployment speed, not cost of idle capacity.
- **D (Economies of scale):** About AWS passing its bulk purchasing savings to customers — a real benefit but not about the CapEx/OpEx conversion.

---

### Q40 — CloudWatch + CloudTrail + CloudWatch Logs
**Answer: A, B, E**

**Why A, B, and E are correct:**
- **A (CloudWatch):** Collects and monitors infrastructure metrics (CPU, memory, network) and creates alarms.
- **B (CloudTrail):** Logs all AWS API activity — who did what, when.
- **E (CloudWatch Logs):** Collects and stores application logs, OS logs, and service logs for centralized analysis.

**Why the others are wrong:**
- **C (Trusted Advisor):** Provides best-practice recommendations — not real-time monitoring.
- **D (Inspector):** Vulnerability scanning — not monitoring metrics or logs.
- **F (Macie):** Finds sensitive data in S3 — not a general monitoring tool.

---

### Q41 — AWS IAM Identity Center for Federated SSO
**Answer: C**

**Why C is correct:** AWS IAM Identity Center (formerly AWS SSO) is designed specifically for providing single sign-on access to AWS accounts and business applications using external identity providers (SAML 2.0) — including corporate IdPs.

**Why the others are wrong:**
- **A (IAM with IAM users):** IAM users have long-term credentials — not federated authentication with a corporate IdP.
- **B (Cognito):** Designed for customer-facing application authentication (mobile/web app users) — not corporate employee SSO.
- **D (Directory Service):** Provides managed Active Directory — it's a directory, not an SSO solution by itself.

---

### Q42 — Well-Architected Reliability Pillar
**Answer: C**

**Why C is correct:** The Reliability pillar focuses on the ability of a workload to perform its intended function correctly and consistently, recover from failures, and dynamically acquire computing resources to meet demand.

**Why the others are wrong:**
- **A (Security):** Protecting data and systems from threats.
- **B (Operational Excellence):** Running and monitoring systems, improving processes.
- **D (Performance Efficiency):** Using computing resources efficiently, selecting the right resource types.

---

### Q43 — Amazon Aurora for High-Performance Relational Database
**Answer: B**

**Why B is correct:** Amazon Aurora is a MySQL and PostgreSQL-compatible relational database built for the cloud, offering up to 5× the throughput of standard MySQL and 3× that of PostgreSQL. It features automatic Multi-AZ replication (6 copies across 3 AZs), automatic failover, and serverless options.

**Why the others are wrong:**
- **A (RDS for MySQL with Multi-AZ):** Provides Multi-AZ but not the 5× performance multiplier — RDS MySQL is standard MySQL performance.
- **C (DynamoDB):** NoSQL — not relational; doesn't support SQL queries natively.
- **D (Redshift):** An analytical data warehouse — not for OLTP transactional workloads.

**Exam Trap:** RDS MySQL with Multi-AZ provides high availability but NOT the 5× throughput. The 5× throughput is the distinguishing Aurora feature.

---

### Q44 — AWS Budgets and CloudWatch Billing Alarms
**Answer: B, D**

**Why B and D are correct:**
- **B (AWS Budgets):** Set custom cost/usage thresholds and receive alerts (email, SNS) when spending approaches or exceeds limits. Supports cost budgets, usage budgets, RI utilization budgets.
- **D (CloudWatch billing alarms):** Set up alarms triggered by estimated charges, which can send SNS notifications to email.

**Why the others are wrong:**
- **A (Cost Explorer):** Analyzes and visualizes past spending — doesn't set spending alerts.
- **C (Trusted Advisor):** Provides cost optimization recommendations — not spending threshold alerts.
- **E (Pricing Calculator):** Estimates future costs — not for monitoring actual spending.

---

### Q45 — AWS Shield Standard
**Answer: C**

**Why C is correct:** AWS Shield Standard is automatically enabled for ALL AWS customers at NO additional charge. It provides protection against the most common and frequently occurring network (Layer 3) and transport (Layer 4) DDoS attacks.

**Why the others are wrong:**
- **A (WAF):** Protects against Layer 7 web application attacks — not DDoS at L3/L4; requires configuration and has costs.
- **B (Shield Advanced):** Provides enhanced DDoS protection with 24/7 DDoS response team access and financial guarantees — costs $3,000/month.
- **D (GuardDuty):** Threat intelligence and anomaly detection — not a DDoS protection service.

**Exam Trap:** The question specifies "at no additional charge" — this is the key differentiator pointing to Shield Standard, not Shield Advanced.

---

### Q46 — Private Subnet for EC2 Instances
**Answer: B**

**Why B is correct:** Best practice for web application architecture: ALB in a public subnet (receives internet traffic), EC2 instances in a private subnet (no direct internet access). The ALB forwards requests to EC2 instances — EC2 instances have no public IPs and are not directly reachable from the internet.

**Why the others are wrong:**
- **A:** Instances in a public subnet have public IPs even with Security Groups — they're reachable from the internet.
- **C:** Disabling the IGW for the entire VPC would break the ALB's ability to receive internet traffic.
- **D:** WAF filters traffic but doesn't prevent EC2 from being directly internet-accessible if they're in a public subnet.

---

### Q47 — AWS Organizations for Multi-Account Governance
**Answer: C**

**Why C is correct:** AWS Organizations is the service that manages multiple AWS accounts, enables consolidated billing, and is the foundation for applying Service Control Policies (SCPs) that restrict actions across accounts.

**Why the others are wrong:**
- **A (Config):** Monitors configuration changes — not for account management.
- **B (IAM):** Manages identities within a single account — not multi-account governance.
- **D (Control Tower):** Built on Organizations — it provides a landing zone framework but Organizations is the fundamental service for SCPs and account management.

---

### Q48 — Active Directory Integration with AWS
**Answer: A, C**

**Why A and C are correct:**
- **A (AWS Directory Service — Managed Microsoft AD):** Provides a fully managed Microsoft Active Directory in AWS — employees can use corporate AD credentials.
- **C (IAM Identity Center with AD integration):** Enables SSO to AWS accounts and applications using AD credentials, connecting to either Managed Microsoft AD or on-premises AD via AD Connector.

**Why the others are wrong:**
- **B (Cognito):** For customer-facing app authentication — not corporate employee AD integration.
- **D (KMS):** Encryption key management — not authentication.
- **E (Organizations):** Multi-account management — not directory/authentication service.

---

### Q49 — Serverless Computing Model
**Answer: D**

**Why D is correct:** Serverless computing is the model where developers write code (or run containers) without managing servers. AWS handles all underlying infrastructure. This allows the team to focus entirely on application code.

**Why the others are wrong:**
- **A (IaaS):** Provides virtualized compute, storage, and networking — you still manage the OS and everything above it (EC2 is IaaS).
- **B (PaaS):** Provides a platform for developing/deploying apps — you manage the application but not the OS (Elastic Beanstalk is closer to PaaS).
- **C (SaaS):** Pre-built applications delivered over the internet (Salesforce, Gmail) — the company is building an app, not using one.

**Exam Trap:** The question might seem to be about PaaS, but "serverless computing" is increasingly recognized as its own model and is the most accurate description here.

---

### Q50 — Amazon Redshift for Data Warehousing
**Answer: C**

**Why C is correct:** Amazon Redshift is a fully managed, petabyte-scale cloud data warehouse optimized for complex analytical queries (OLAP) across large datasets — perfect for BI reporting.

**Why the others are wrong:**
- **A (RDS):** OLTP relational database — not optimized for petabyte-scale analytics.
- **B (DynamoDB):** NoSQL database for transactional workloads — not analytics.
- **D (EMR):** Elastic MapReduce processes big data using Spark/Hadoop — more for ETL and data processing than BI reporting.

---

### Q51 — Compromised Access Keys
**Answer: B**

**Why B is correct:** The FIRST action when access keys are compromised is to immediately deactivate the compromised keys and rotate (create new) keys. This stops any ongoing unauthorized access immediately. Then investigate what actions were performed using CloudTrail.

**Why the others are wrong:**
- **A:** Deleting the IAM user would disrupt legitimate operations — first step is key rotation, not deletion.
- **C:** AWS Support cannot deactivate your account's IAM keys on your behalf — this is a customer responsibility.
- **D:** Changing the IAM user password doesn't invalidate access keys — they are separate credentials.

---

### Q52 — Reliability Pillar Best Practices
**Answer: A, C**

**Why A and C are correct:**
- **A (Multi-AZ deployment):** Core Reliability recommendation — eliminate single points of failure by distributing across AZs.
- **C (Automated recovery with Auto Scaling):** Auto Scaling automatically replaces unhealthy instances — implementing automated recovery.

**Why the others are wrong:**
- **B (Reserved Instances):** A cost optimization strategy — not a reliability practice.
- **D:** Using fewer Regions reduces geographic redundancy — hurts reliability.
- **E:** Cheapest instance may be undersized and degrade performance — not a reliability practice.

---

### Q53 — AWS Cloud Is NOT a Security Silver Bullet
**Answer: B**

**Why B is correct:** AWS does NOT guarantee the elimination of ALL security vulnerabilities. Security is a shared responsibility — customers are responsible for securing their applications, configuring IAM properly, patching their OS, etc. AWS secures the underlying infrastructure, but customers can still introduce vulnerabilities.

**Why the others are wrong (they ARE genuine benefits):**
- **A:** True — AWS enables faster deployment cycles.
- **C:** True — deploy to any of 30+ Regions in minutes.
- **D:** True — most workloads see TCO reduction when optimized for cloud.

---

### Q54 — Amazon GuardDuty for Threat Detection
**Answer: C**

**Why C is correct:** Amazon GuardDuty is a continuous threat detection service that uses machine learning, anomaly detection, and threat intelligence to identify threats like cryptocurrency mining, unauthorized API calls, and unusual data exfiltration patterns.

**Why the others are wrong:**
- **A (Inspector):** Scans EC2/Lambda for software vulnerabilities (CVEs) — not behavioral threat detection.
- **B (Shield):** DDoS protection — not threat detection.
- **D (Config):** Configuration compliance monitoring — not threat detection.

---

### Q55 — Route 53 Latency Routing + Health Checks
**Answer: B, D**

**Why B and D are correct:**
- **B (Latency-Based Routing):** Routes users to the AWS Region with the lowest latency for that user's location — exactly what's needed.
- **D (Route 53 Health Checks):** Monitors endpoint health and automatically removes unhealthy endpoints from DNS responses.

**Why the others are wrong:**
- **A (Simple Routing):** Routes to a single resource — no health checks, no latency awareness.
- **C (Geolocation Routing):** Routes based on user's geographic location — doesn't optimize for latency.
- **E (Failover Routing):** Routes to a secondary endpoint if primary fails — not latency-based routing.

---

### Q56 — S3 Lifecycle Policies
**Answer: C**

**Why C is correct:** S3 Lifecycle Policies automate the transition of objects between storage classes based on rules (e.g., move to S3-IA after 30 days, move to Glacier after 90 days, delete after 7 years). This is exactly how to handle objects not accessed in 90 days automatically.

**Why the others are wrong:**
- **A (Object Lock):** Prevents objects from being deleted or overwritten — a compliance/retention lock, not tiering.
- **B (Transfer Acceleration):** Speeds up S3 uploads using CloudFront edge locations — not related to storage class management.
- **D (Cross-Region Replication):** Copies objects to another Region — not tiering within a Region.

---

### Q57 — Amazon Textract for Document Processing
**Answer: B**

**Why B is correct:** Amazon Textract is an ML service that automatically extracts text, handwriting, and structured data (forms, tables) from scanned documents (PDFs, images) — automating manual data entry.

**Why the others are wrong:**
- **A (Rekognition):** Analyzes images for objects, faces, labels, and moderation — not document text extraction.
- **C (Comprehend):** NLP for text already in digital format — analyzes text but doesn't extract text from document images.
- **D (Transcribe):** Converts spoken audio to text — not document scanning.

---

### Q58 — Six Benefits of Cloud Computing
**Answer: A, C, D**

**Why A, C, and D are correct (Three of the Six AWS Cloud Benefits):**
- **A:** Trade capital expense for variable expense ✓
- **C:** Benefit from massive economies of scale ✓
- **D:** Stop guessing capacity (elasticity) ✓

The six AWS cloud benefits are:
1. Trade CapEx for variable expense
2. Benefit from massive economies of scale
3. Stop guessing capacity
4. Increase speed and agility
5. Stop spending money on data center operations
6. Go global in minutes

**Why the others are wrong:**
- **B:** Developers are still needed — cloud doesn't eliminate the need for people.
- **E:** No cloud provider guarantees 100% uptime.
- **F:** Cloud means you DON'T own hardware — you rent capacity.

---

### Q59 — Spot Instances for Fault-Tolerant Batch Jobs
**Answer: C**

**Why C is correct:** Spot Instances are up to 90% cheaper than On-Demand and are ideal for fault-tolerant, interruptible batch workloads. A 4-hour Friday night job that can be restarted if interrupted is the textbook Spot Instance use case.

**Why the others are wrong:**
- **A (On-Demand):** No interruption risk, but 3–4× more expensive than Spot — not cost-optimized for this use case.
- **B (Reserved Instances):** Requires 1–3 year commitment — wasteful for a weekly 4-hour job (168 hours/week, only 4 hours used = 2.4% utilization).
- **D (Dedicated Hosts):** Used for BYOL and compliance — most expensive option.

---

### Q60 — Reliability: Loose Coupling
**Answer: B**

**Why B is correct:** The Reliability pillar recommends loose coupling — designing components so that failures in one don't cascade to others. Tightly coupled dependencies are a common cause of widespread outages. Using queues, managed services, and decoupled interfaces prevents cascading failures.

**Why the others are wrong:**
- **A (Cost Optimization/Serverless):** Serverless doesn't inherently solve dependency coupling problems.
- **C (Operational Excellence/Runbooks):** Automation helps respond to failures but doesn't prevent cascade failures from tight coupling.
- **D (Performance Efficiency/Instance type):** Instance selection doesn't address architectural coupling.

---

### Q61 — Amazon Macie for PII Discovery
**Answer: C**

**Why C is correct:** Amazon Macie is a fully managed data security service that uses machine learning to automatically discover, classify, and protect sensitive data (PII, PHI, financial data) in Amazon S3. It provides alerts when sensitive data is publicly accessible.

**Why the others are wrong:**
- **A (GuardDuty):** Detects security threats and unusual activity — not data classification.
- **B (Config):** Monitors resource configurations — doesn't classify data content.
- **D (Inspector):** Scans for software vulnerabilities — not data classification.

---

### Q62 — Reducing Data Transfer Costs
**Answer: A, D**

**Why A and D are correct:**
- **A (CloudFront):** Serving content from edge locations means data is fetched from CloudFront (cheaper data transfer rates) rather than directly from EC2/S3 in a Region. Significantly reduces data transfer out costs.
- **D (Same-Region transfers):** Data transfer between AWS services within the same Region is typically free or very low cost. Cross-Region data transfer incurs fees.

**Why the others are wrong:**
- **B:** Cross-Region data transfer has fees — this statement is incorrect.
- **C (S3 Transfer Acceleration):** Speeds UP uploads using edge locations — this INCREASES, not decreases, costs (premium feature).
- **E (RDS Multi-AZ):** A high availability feature — doesn't reduce data transfer costs.

---

### Q63 — AWS IAM Identity Center for Enterprise SSO
**Answer: C**

**Why C is correct:** AWS IAM Identity Center (formerly AWS SSO) provides centralized SSO access to multiple AWS accounts and external business applications. It integrates with corporate identity providers (Active Directory, Okta, etc.) via SAML 2.0 — giving employees one login for AWS and SaaS apps.

**Why the others are wrong:**
- **A (Cognito):** Customer-facing identity — for apps' end-users, not corporate employees.
- **B (IAM):** Manages fine-grained AWS permissions — doesn't provide SSO across multiple accounts and third-party apps.
- **D (Simple AD):** A lightweight directory service — not designed for multi-account SSO.

---

### Q64 — Physical Data Transfer: Snowball and Snowcone
**Answer: A, D**

**Why A and D are correct:**
- **A (AWS Snowball Edge):** A physical appliance that holds 80–210 TB of data. AWS ships it to you, you load data, ship it back, and AWS uploads to S3 — ideal for large-scale migrations with slow internet.
- **D (AWS Snowcone):** A smaller physical device (8–14 TB) for edge locations and small-scale data transfer — also part of the AWS Snow Family.

**Why the others are wrong:**
- **B (Direct Connect):** A dedicated network connection — still transfers data over the wire; helpful for ongoing connectivity but not physical device-based transfer.
- **C (DataSync):** An online data transfer service that moves data over the network (internet or Direct Connect) — not a physical transfer option.
- **E (Storage Gateway):** A hybrid storage service that connects on-premises to S3 over the network — not physical transfer.

---

### Q65 — AWS Migration Evaluator for Pre-Migration Planning
**Answer: C**

**Why C is correct:** AWS Migration Evaluator (formerly TSO Logic, and previously part of the AWS TCO Calculator suite) provides a detailed assessment of an organization's on-premises environment, identifies right-sizing opportunities, and projects AWS costs — helping build a business case before migration.

**Why the others are wrong:**
- **A (Well-Architected Tool):** Reviews existing AWS workloads against best practices — used AFTER migration, not before.
- **B (Migration Hub):** Tracks migration progress and consolidates migration status across tools — used DURING migration.
- **D (Application Discovery Service):** Discovers on-premises applications and dependencies (agentless or agent-based) — a component of pre-migration planning, but more of a discovery tool than a full TCO/planning tool.

---

# EXAM SCORING GUIDE

| Score Range | Result | Recommendation |
|-------------|--------|----------------|
| 58–65 (89–100%) | Exceptional | Ready to certify — schedule your exam! |
| 52–57 (80–88%) | Strong Pass | Review weak areas, then schedule |
| 46–51 (70–79%) | Pass (borderline) | Study weak areas for 1–2 more weeks |
| 39–45 (60–69%) | Near Miss | Review key services and Well-Architected Framework |
| Below 39 (<60%) | Needs More Study | Focus on foundational concepts before retaking |

> **Note:** The actual AWS CLF-C02 exam has a scaled passing score of 700/1000 (approximately 70%). Scores on this mock exam should be used directionally, not as a precise prediction.

---

## AREAS TO REVIEW BY DOMAIN

**If you struggled with Q1, Q12, Q39, Q58:** Review Cloud Concepts and the 6 benefits of cloud computing.

**If you struggled with Q3, Q17, Q51, Q53:** Review the Shared Responsibility Model carefully — it appears in many questions.

**If you struggled with Q5, Q16, Q37, Q45, Q46:** Focus on IAM, Security Groups vs NACLs, and Shield tiers.

**If you struggled with Q10, Q24, Q36, Q55:** Deep-dive into VPC fundamentals: subnets, NAT, VPC Peering, Direct Connect.

**If you struggled with Q22, Q28, Q42, Q52, Q60:** Review the AWS Well-Architected Framework six pillars and their key principles.

**If you struggled with Q6, Q7, Q25, Q44, Q59, Q62:** Study EC2 pricing models and AWS cost management tools.

---

*End of Mock Exam — AWS Certified Cloud Practitioner (CLF-C02)*
*Generated for exam preparation purposes. Always refer to official AWS documentation for the most current information.*
