# AWS Certified Cloud Practitioner (CLF-C02) - Mock Exam 01

**Exam Overview:**
- **Target:** AWS Certified Cloud Practitioner (CLF-C02)
- **Total Questions:** 65
- **Format:** Multiple Choice / Multiple Response
- **Time:** 90 Minutes

---

## SECTION 1 — QUESTIONS

### Question 1
A company is migrating their on-premises infrastructure to AWS. The CTO wants to understand how AWS pricing differs from their current data center model where they purchase servers for a 5-year lifecycle. Which statement **BEST** describes the AWS Cloud pricing model compared to traditional on-premises infrastructure?
* A) AWS requires a minimum 1-year commitment for all compute services
* B) AWS uses a pay-as-you-go model where you pay only for resources consumed
* C) AWS pricing is fixed monthly regardless of usage to simplify budgeting
* D) AWS requires upfront capacity reservations before launching any resources

### Question 2
A startup wants to ensure their web application remains available even if an entire data center experiences an outage. They need to design for high availability. Which **TWO** actions should they take to achieve this goal? (Choose TWO)
* A) Deploy resources across multiple Availability Zones within a Region
* B) Store all application data on a single Amazon EBS volume with snapshots
* C) Use an Application Load Balancer to distribute traffic across instances in multiple Availability Zones
* D) Deploy all resources in a single Availability Zone with larger instance types
* E) Enable versioning on a single S3 bucket in one Availability Zone

### Question 3
A security engineer needs to grant temporary access to an external auditor who requires read-only access to AWS resources for 3 days. The auditor does not have an AWS account. Which approach provides the **MOST** secure method to grant this access?
* A) Create an IAM user with a permanent password and delete it after 3 days
* B) Share the root account credentials with multi-factor authentication enabled
* C) Create an IAM role with appropriate permissions and provide temporary security credentials using AWS STS
* D) Create an IAM group with read-only policies and add the auditor as a new member

### Question 4
A company hosts a critical database on Amazon RDS. The database must remain available in the event of an infrastructure failure in the primary location. Which Amazon RDS feature provides automatic failover to a standby replica in a different Availability Zone?
* A) Read Replicas
* B) Multi-AZ deployment
* C) Automated backups
* D) Database snapshots

### Question 5
A solutions architect is explaining the benefits of migrating to the AWS Cloud to their organization's leadership team. Which **THREE** statements are valid benefits of the AWS Cloud? (Choose THREE)
* A) Trade capital expense for variable expense
* B) Benefit from massive economies of scale
* C) Eliminate all operational responsibilities for infrastructure
* D) Stop guessing capacity
* E) Maintain complete physical control over data center hardware
* F) Increase speed and agility

### Question 6
According to the AWS Shared Responsibility Model, which task is the responsibility of AWS?
* A) Configuring security group rules for EC2 instances
* B) Managing the guest operating system on EC2 instances
* C) Maintaining the physical security of data centers
* D) Encrypting application data at rest in S3 buckets

### Question 7
A retail company experiences significant traffic increases during annual sales events but has minimal traffic during other periods. They need a compute solution that automatically adjusts capacity based on demand. Which combination of AWS services provides the **MOST** cost-effective solution with automatic scaling?
* A) Amazon EC2 Reserved Instances with manual capacity adjustments
* B) Amazon EC2 Auto Scaling with Amazon CloudWatch alarms
* C) AWS Lambda with provisioned concurrency permanently enabled
* D) Amazon EC2 Dedicated Hosts with scheduled scaling

### Question 8
A developer needs to run code in response to changes in an Amazon S3 bucket without managing servers. The code runs for approximately 30 seconds per invocation. Which AWS service is **BEST** suited for this use case?
* A) Amazon EC2
* B) Amazon ECS
* C) AWS Lambda
* D) AWS Batch

### Question 9
A company wants to protect their web application from common web exploits such as SQL injection and cross-site scripting attacks. Which **TWO** AWS services should they use? (Choose TWO)
* A) AWS Shield Standard
* B) AWS WAF
* C) Amazon Inspector
* D) Application Load Balancer security rules
* E) Amazon CloudFront with AWS WAF integration

### Question 10
A company needs to store 500 TB of archival data that will be accessed approximately once per year for compliance audits. Access can tolerate retrieval times of 12 hours. Which Amazon S3 storage class provides the **MOST** cost-effective solution?
* A) S3 Standard
* B) S3 Standard-Infrequent Access
* C) S3 One Zone-Infrequent Access
* D) S3 Glacier Deep Archive

### Question 11
An organization wants to consolidate billing for multiple AWS accounts while maintaining separate account boundaries for different business units. Which AWS service should they use?
* A) AWS Cost Explorer
* B) AWS Organizations
* C) AWS Budgets
* D) AWS Control Tower

### Question 12
A company is using Amazon EC2 instances for a batch processing workload that can be interrupted without impact. The workload runs for several hours and can be restarted if needed. Which EC2 purchasing option provides the **MOST** cost-effective solution?
* A) On-Demand Instances
* B) Reserved Instances
* C) Spot Instances
* D) Dedicated Hosts

### Question 13
According to the AWS Well-Architected Framework, which pillar focuses on the ability to run workloads effectively, gain insight into operations, and continuously improve processes?
* A) Security
* B) Reliability
* C) Operational Excellence
* D) Performance Efficiency

### Question 14
A company needs to establish a private, dedicated network connection between their on-premises data center and AWS. The connection must provide consistent network performance. Which **TWO** options meet these requirements? (Choose TWO)
* A) AWS VPN with internet connection
* B) AWS Direct Connect
* C) Amazon CloudFront
* D) AWS Direct Connect with VPN backup
* E) Amazon Route 53

### Question 15
A security team needs to track all API calls made within their AWS account for compliance and security auditing purposes. Which AWS service should they use?
* A) Amazon CloudWatch
* B) AWS CloudTrail
* C) AWS Config
* D) Amazon Inspector

### Question 16
A company wants to deploy a relational database that automatically handles hardware provisioning, database setup, patching, and backups. Which AWS service provides this capability?
* A) Amazon EC2 with self-managed MySQL
* B) Amazon RDS
* C) Amazon DynamoDB
* D) Amazon ElastiCache

### Question 17
A company has deployed an application across three Availability Zones. One Availability Zone becomes unavailable due to a power outage. What characteristic of cloud computing does this architecture demonstrate?
* A) Elasticity
* B) Agility
* C) Fault tolerance
* D) Cost optimization

### Question 18
According to the AWS Shared Responsibility Model, which of the following is the customer's responsibility when using Amazon RDS?
* A) Patching the underlying operating system
* B) Managing database security groups
* C) Replacing failed hardware
* D) Patching the database engine

### Question 19
A company needs to analyze their AWS spending and identify opportunities to reduce costs. Which **TWO** AWS tools can help with this? (Choose TWO)
* A) AWS Cost Explorer
* B) AWS CloudFormation
* C) AWS Trusted Advisor
* D) AWS CloudTrail
* E) Amazon Inspector

### Question 20
A startup needs a fully managed NoSQL database that can scale to handle millions of requests per second with single-digit millisecond latency. Which AWS service should they use?
* A) Amazon RDS
* B) Amazon Aurora
* C) Amazon DynamoDB
* D) Amazon Redshift

### Question 21
A company wants to reduce latency for users accessing their static website content from different geographic locations around the world. Which AWS service should they use?
* A) Amazon S3 Transfer Acceleration
* B) Amazon CloudFront
* C) AWS Global Accelerator
* D) Amazon Route 53

### Question 22
A solutions architect needs to implement a security control that operates at the subnet level and can allow or deny traffic based on IP addresses and port numbers. This control should be stateless. Which AWS feature should they use?
* A) Security groups
* B) Network Access Control Lists (NACLs)
* C) AWS WAF
* D) AWS Shield

### Question 23
A company is evaluating AWS for their infrastructure needs. The CTO asks about the advantages of cloud computing. Which **THREE** are advantages of AWS Cloud computing? (Choose THREE)
* A) Increased time to deploy new applications globally
* B) Trade fixed expense for variable expense
* C) Maintain physical servers in AWS data centers
* D) Go global in minutes
* E) Focus on differentiating your business rather than infrastructure
* F) Require long-term contracts for all services

### Question 24
A company needs to ensure that no IAM user can perform any action unless they have enabled multi-factor authentication (MFA) on their account. Which AWS feature should they use to enforce this requirement?
* A) IAM access keys
* B) IAM password policy
* C) IAM policy conditions
* D) AWS Organizations tag policies

### Question 25
A development team needs to deploy and manage containerized applications on AWS. They want a fully managed service that eliminates the need to manage the underlying container orchestration infrastructure. Which AWS service should they use?
* A) Amazon EC2 with Docker installed
* B) Amazon EKS with self-managed nodes
* C) AWS Fargate
* D) AWS Batch

### Question 26
A company stores sensitive customer data in Amazon S3. They need to encrypt this data at rest using encryption keys that they manage and can rotate. Which AWS service should they use for key management?
* A) AWS Certificate Manager
* B) AWS Secrets Manager
* C) AWS Key Management Service (KMS)
* D) AWS CloudHSM

### Question 27
A company wants to ensure their AWS resources are compliant with internal security policies. They need to track configuration changes and evaluate resources against compliance rules. Which **TWO** AWS services should they use together? (Choose TWO)
* A) AWS Config
* B) Amazon CloudWatch
* C) AWS Config Rules
* D) AWS CloudTrail
* E) Amazon GuardDuty

### Question 28
A company is running a production workload on Amazon EC2 instances that requires 24/7 availability for the next 3 years. The workload has predictable and steady-state usage. Which EC2 purchasing option provides the **MOST** cost-effective solution?
* A) On-Demand Instances
* B) Spot Instances
* C) Reserved Instances or Savings Plans
* D) Dedicated Hosts

### Question 29
Which AWS service allows users to create and manage virtual private networks within the AWS Cloud?
* A) Amazon Route 53
* B) Amazon VPC
* C) AWS Direct Connect
* D) Amazon CloudFront

### Question 30
A company wants to automatically identify and remediate security vulnerabilities in their Amazon EC2 instances and container images stored in Amazon ECR. Which AWS service should they use?
* A) AWS Config
* B) Amazon Inspector
* C) AWS Trusted Advisor
* D) Amazon GuardDuty

### Question 31
According to the AWS Well-Architected Framework, which pillar includes the practice of protecting information, systems, and assets while delivering business value through risk assessments and mitigation strategies?
* A) Operational Excellence
* B) Security
* C) Reliability
* D) Cost Optimization

### Question 32
A company is designing a highly available architecture for their web application. They need to distribute incoming traffic across multiple EC2 instances. Which **TWO** options can accomplish this? (Choose TWO)
* A) Amazon Route 53 with simple routing
* B) Application Load Balancer
* C) Network Load Balancer
* D) Amazon CloudFront
* E) AWS Direct Connect

### Question 33
A company needs to migrate a large dataset from their on-premises data center to Amazon S3. The dataset is 80 TB and they have limited network bandwidth. Which AWS service is **BEST** suited for this migration?
* A) AWS Storage Gateway
* B) AWS Snowball
* C) AWS Direct Connect
* D) Amazon S3 Transfer Acceleration

### Question 34
A developer needs to build a mobile application that requires user sign-up, sign-in, and access control features. Which AWS service provides these capabilities with minimal custom development?
* A) AWS IAM
* B) Amazon Cognito
* C) AWS Directory Service
* D) AWS Single Sign-On

### Question 35
A company wants to monitor the CPU utilization of their Amazon EC2 instances and receive alerts when utilization exceeds 80%. Which AWS service should they use to set up monitoring and alerts?
* A) AWS CloudTrail
* B) Amazon CloudWatch
* C) AWS Config
* D) Amazon Inspector

### Question 36
A security team is implementing the principle of least privilege for their AWS environment. Which **THREE** actions align with this principle? (Choose THREE)
* A) Grant all users administrator access for convenience
* B) Create specific IAM policies that grant only required permissions
* C) Use IAM roles instead of sharing long-term credentials
* D) Share access keys across multiple users for simplified management
* E) Regularly review and remove unnecessary permissions
* F) Use the root account for daily administrative tasks

### Question 37
A company runs a web application that requires a domain name that can route users to different endpoints based on their geographic location. Which AWS service and routing policy should they use?
* A) Amazon CloudFront with origin failover
* B) Amazon Route 53 with geolocation routing
* C) Application Load Balancer with path-based routing
* D) AWS Global Accelerator with endpoint groups

### Question 38
According to the AWS Shared Responsibility Model, who is responsible for patching the guest operating system on an Amazon EC2 instance?
* A) AWS
* B) The customer
* C) Shared responsibility between AWS and the customer
* D) The EC2 instance automatically patches itself

### Question 39
A company wants to analyze text documents to extract key phrases, entities, and sentiment for their customer feedback system. Which AWS service should they use?
* A) Amazon Transcribe
* B) Amazon Comprehend
* C) Amazon Polly
* D) Amazon Rekognition

### Question 40
A company needs to protect their internet-facing application from Distributed Denial of Service (DDoS) attacks. Which **TWO** AWS services provide DDoS protection? (Choose TWO)
* A) AWS Shield
* B) Amazon Inspector
* C) AWS WAF
* D) Amazon GuardDuty
* E) AWS Config

### Question 41
A company needs shared file storage that can be accessed concurrently from multiple Amazon EC2 instances across different Availability Zones. The storage must support the NFS protocol. Which AWS service should they use?
* A) Amazon EBS
* B) Amazon S3
* C) Amazon EFS
* D) Amazon FSx for Windows File Server

### Question 42
A company wants to estimate the cost savings of migrating their on-premises workloads to AWS. Which AWS tool should they use?
* A) AWS Cost Explorer
* B) AWS Pricing Calculator
* C) AWS Migration Hub
* D) AWS Budgets

### Question 43
A startup wants to quickly deploy a WordPress website without managing the underlying infrastructure, operating system, or application stack. Which AWS service requires the **LEAST** operational overhead?
* A) Amazon EC2 with manual WordPress installation
* B) Amazon Lightsail
* C) AWS Elastic Beanstalk
* D) Amazon ECS

### Question 44
According to the AWS Well-Architected Framework, which pillar focuses on using computing resources efficiently to meet system requirements and maintaining that efficiency as demand changes?
* A) Operational Excellence
* B) Security
* C) Reliability
* D) Performance Efficiency

### Question 45
A company needs to grant their EC2 instances access to an S3 bucket without storing credentials on the instances. Which **TWO** options provide the **MOST** secure method? (Choose TWO)
* A) Store AWS access keys in environment variables on the instance
* B) Attach an IAM role to the EC2 instance
* C) Store credentials in an unencrypted configuration file
* D) Use an IAM instance profile
* E) Use the root account credentials

### Question 46
A company wants to receive recommendations for optimizing their AWS environment across cost optimization, performance, security, and fault tolerance categories. Which AWS service provides these recommendations?
* A) AWS Cost Explorer
* B) AWS Trusted Advisor
* C) AWS Config
* D) Amazon CloudWatch

### Question 47
A company needs to convert speech to text for their customer service call recordings stored in Amazon S3. Which AWS service should they use?
* A) Amazon Polly
* B) Amazon Transcribe
* C) Amazon Comprehend
* D) Amazon Lex

### Question 48
A company wants to allow resources in a private subnet to access the internet for software updates without exposing them to inbound internet traffic. Which AWS component should they use?
* A) Internet Gateway
* B) NAT Gateway
* C) VPC Peering
* D) VPN Gateway

### Question 49
A company is planning a disaster recovery strategy for their critical application. They need to minimize data loss and recovery time. According to the AWS Well-Architected Framework Reliability pillar, which **TWO** strategies should they consider? (Choose TWO)
* A) Back up data regularly and test recovery procedures
* B) Deploy all resources in a single Availability Zone for simplicity
* C) Use multiple Availability Zones and Regions for critical workloads
* D) Avoid automation to maintain manual control over recovery
* E) Store all backups in the same Region as production

### Question 50
A financial services company needs to meet regulatory requirements that mandate their data must be stored in a specific geographic location. Which AWS feature helps them meet this requirement?
* A) AWS Global Accelerator
* B) AWS Regions
* C) Amazon CloudFront
* D) Availability Zones

### Question 51
A company wants to implement a microservices architecture using containers. They need full control over the container orchestration platform and want to use Kubernetes. Which AWS service should they use?
* A) Amazon ECS
* B) Amazon EKS
* C) AWS Fargate
* D) AWS Lambda

### Question 52
A company wants to set spending limits and receive alerts when their AWS costs exceed certain thresholds. Which AWS service should they use?
* A) AWS Cost Explorer
* B) AWS Budgets
* C) AWS Trusted Advisor
* D) AWS Pricing Calculator

### Question 53
A company needs to store data that will be frequently accessed and modified by applications. The storage must provide high IOPS and low latency. Which **TWO** AWS storage services are **BEST** suited for this use case? (Choose TWO)
* A) Amazon S3 Glacier
* B) Amazon EBS Provisioned IOPS SSD
* C) Amazon S3 Standard
* D) Amazon EFS
* E) Amazon S3 One Zone-IA

### Question 54
A company wants to continuously monitor their AWS account for malicious activity and unauthorized behavior by analyzing VPC Flow Logs, CloudTrail logs, and DNS logs. Which AWS service should they use?
* A) Amazon Inspector
* B) Amazon GuardDuty
* C) AWS Config
* D) AWS CloudTrail

### Question 55
According to the AWS Shared Responsibility Model, which of the following is AWS responsible for?
* A) Customer data encryption
* B) Operating system patches on EC2 instances
* C) Physical and environmental controls in data centers
* D) Network traffic protection at the application layer

### Question 56
A company wants to build a conversational chatbot that can understand natural language and respond to customer inquiries. Which AWS service should they use?
* A) Amazon Comprehend
* B) Amazon Polly
* C) Amazon Lex
* D) Amazon Transcribe

### Question 57
A company wants to optimize their AWS costs. They have identified several strategies to reduce spending. Which **THREE** strategies are valid cost optimization techniques? (Choose THREE)
* A) Use Reserved Instances or Savings Plans for predictable workloads
* B) Keep all EC2 instances running at all times to avoid startup latency
* C) Choose the appropriate storage class based on access patterns
* D) Use a single large instance instead of multiple smaller instances for all workloads
* E) Implement auto scaling to match capacity with demand
* F) Store all data in S3 Standard regardless of access frequency

### Question 58
A company is using multiple AWS services and wants to deploy infrastructure as code to ensure consistent and repeatable deployments. Which AWS service should they use?
* A) AWS Systems Manager
* B) AWS CloudFormation
* C) AWS Config
* D) AWS OpsWorks

### Question 59
A company needs to identify and protect against malicious IP addresses and domains in their AWS environment. Which AWS service provides threat intelligence and helps identify potentially compromised instances?
* A) AWS WAF
* B) Amazon GuardDuty
* C) Amazon Inspector
* D) AWS Shield

### Question 60
A company wants to improve the security of their root account. Which **TWO** actions are AWS best practices for securing the root account? (Choose TWO)
* A) Use the root account for daily administrative tasks
* B) Enable multi-factor authentication (MFA) on the root account
* C) Share root account credentials with the IT team for emergencies
* D) Create IAM users for administrative tasks instead of using root
* E) Store root credentials in an S3 bucket for backup

### Question 61
According to the AWS Well-Architected Framework, which pillar focuses on avoiding unnecessary costs and understanding spending over time?
* A) Operational Excellence
* B) Security
* C) Reliability
* D) Cost Optimization

### Question 62
A company has deployed an application in a VPC. Instances in a private subnet need to download software updates from the internet without being directly accessible from the internet. Which architecture meets this requirement with the **LEAST** operational overhead?
* A) Deploy a NAT instance in a public subnet
* B) Deploy a NAT Gateway in a public subnet
* C) Attach an Elastic IP to each private instance
* D) Use VPC peering with another VPC that has internet access

### Question 63
A company needs to scan images and videos for objects, people, text, and inappropriate content as part of their content moderation system. Which AWS service should they use?
* A) Amazon Comprehend
* B) Amazon Rekognition
* C) Amazon Textract
* D) Amazon Polly

### Question 64
A company is designing their VPC architecture and needs to understand the difference between security groups and network ACLs. Which **TWO** statements correctly describe the differences? (Choose TWO)
* A) Security groups are stateful; network ACLs are stateless
* B) Security groups operate at the subnet level; network ACLs operate at the instance level
* C) Security groups support allow rules only; network ACLs support both allow and deny rules
* D) Security groups are stateless; network ACLs are stateful
* E) Network ACLs are applied at the VPC level; security groups are applied at the Region level

### Question 65
According to the AWS Well-Architected Framework, which pillar includes practices such as performing operations as code, making frequent small reversible changes, and anticipating failure?
* A) Operational Excellence
* B) Security
* C) Performance Efficiency
* D) Sustainability

---

## ANSWER KEY

| Q# | Answer | Q# | Answer | Q# | Answer |
|---|---|---|---|---|---|
| 1 | B | 23 | B, D, E | 45 | B, D |
| 2 | A, C | 24 | C | 46 | B |
| 3 | C | 25 | C | 47 | B |
| 4 | B | 26 | C | 48 | B |
| 5 | A, B, F | 27 | A, C | 49 | A, C |
| 6 | C | 28 | C | 50 | B |
| 7 | B | 29 | B | 51 | B |
| 8 | C | 30 | B | 52 | B |
| 9 | B, E | 31 | B | 53 | B, D |
| 10 | D | 32 | B, C | 54 | B |
| 11 | B | 33 | B | 55 | C |
| 12 | C | 34 | B | 56 | C |
| 13 | C | 35 | B | 57 | A, C, E |
| 14 | B, D | 36 | B, C, E | 58 | B |
| 15 | B | 37 | B | 59 | B |
| 16 | B | 38 | B | 60 | B, D |
| 17 | C | 39 | B | 61 | D |
| 18 | B | 40 | A, C | 62 | B |
| 19 | A, C | 41 | C | 63 | B |
| 20 | C | 42 | B | 64 | A, C |
| 21 | B | 43 | B | 65 | A |
| 22 | B | 44 | D | | |
