# AWS Certified Cloud Practitioner (CLF-C02) - Mock Exam 02

**Exam Overview:**
- **Target:** AWS Certified Cloud Practitioner (CLF-C02)
- **Total Questions:** 65
- **Format:** Multiple Choice / Multiple Response
- **Time:** 90 Minutes

---

## SECTION 1 — QUESTIONS

### Question 1
A company wants to migrate its on-premises Oracle database to AWS but wants to minimize administrative overhead for tasks like patching and backups. Which service should they use?
* A) Amazon EC2 with Oracle installed
* B) Amazon RDS
* C) Amazon DynamoDB
* D) AWS Lambda

### Question 2
Which AWS Cloud benefit refers to the ability to pay only for what you use and change your capacity as needed?
* A) High Availability
* B) Reliability
* C) Agility
* D) Pay-as-you-go pricing

### Question 3
According to the AWS Shared Responsibility Model, which of the following is a responsibility of the customer?
* A) Patching the underlying host of an EC2 instance
* B) Managing the physical security of the data center
* C) Configuring Security Groups and Network ACLs
* D) Decommissioning old storage drives

### Question 4
A company needs to connect their on-premises data center to AWS via a dedicated, private connection that bypasses the public internet. Which service meets this requirement?
* A) AWS Site-to-Site VPN
* B) AWS Direct Connect
* C) Amazon CloudFront
* D) AWS Transit Gateway

### Question 5
Which of the following are pillars of the AWS Well-Architected Framework? (Choose TWO)
* A) Scalability
* B) Operational Excellence
* C) High Availability
* D) Performance Efficiency
* E) Governance

### Question 6
A startup needs to run a short-term, intermittent workload that can be interrupted at any time. Which EC2 instance purchasing option is the MOST cost-effective?
* A) On-Demand Instances
* B) Reserved Instances
* C) Spot Instances
* D) Dedicated Hosts

### Question 7
Which AWS service provides a central place to manage and govern your environment as you grow and scale your workloads across multiple accounts?
* A) AWS Trusted Advisor
* B) AWS Organizations
* C) AWS Config
* D) AWS IAM

### Question 8
A user is unable to access an EC2 instance. The Security Group allows traffic, but the Network ACL denies it. What will be the result?
* A) The traffic will be allowed because Security Groups take precedence.
* B) The traffic will be denied because the NACL is evaluated.
* C) The traffic will be allowed because Security Groups are stateless.
* D) The traffic will be allowed only if the user has an IAM Policy.

### Question 9
Which service allows you to run code without provisioning or managing servers?
* A) Amazon EC2
* B) AWS Lambda
* C) Amazon ECS
* D) Amazon Lightsail

### Question 10
Which S3 storage class is intended for data that is rarely accessed but requires immediate retrieval when requested?
* A) S3 Standard
* B) S3 Intelligent-Tiering
* C) S3 Standard-Infrequent Access (S3 Standard-IA)
* D) S3 Glacier Deep Archive

### Question 11
A company wants to ensure their application is highly available and can survive the failure of a single data center. What should they do?
* A) Deploy the application across multiple Edge Locations.
* B) Deploy the application across multiple Availability Zones.
* C) Deploy the application across multiple AWS Accounts.
* D) Use a single EC2 instance with a larger instance size.

### Question 12
Which tool can be used to estimate the cost of a new solution you are planning to build on AWS?
* A) AWS Cost Explorer
* B) AWS Pricing Calculator
* C) AWS Budgets
* D) AWS Trusted Advisor

### Question 13
A company needs to discover and protect sensitive data, such as personally identifiable information (PII), stored in Amazon S3. Which service should they use?
* A) Amazon GuardDuty
* B) Amazon Macie
* C) AWS Shield
* D) Amazon Inspector

### Question 14
Which of the following is a managed NoSQL database service provided by AWS?
* A) Amazon RDS
* B) Amazon Aurora
* C) Amazon DynamoDB
* D) Amazon Redshift

### Question 15
Under the Shared Responsibility Model, for which of the following is AWS responsible? (Choose TWO)
* A) Protecting the infrastructure that runs AWS services
* B) Managing IAM user permissions
* C) Physical security of the data centers
* D) Encryption of customer data at rest
* E) Patching the guest operating system

### Question 16
Which AWS service can be used to track user activity and API calls across the entire AWS infrastructure?
* A) Amazon CloudWatch
* B) AWS CloudTrail
* C) AWS Config
* D) Amazon Inspector

### Question 17
A developer wants to simplify the process of deploying and managing a web application without worrying about the underlying infrastructure. Which service should they use?
* A) AWS Elastic Beanstalk
* B) AWS CloudFormation
* C) Amazon EC2
* D) AWS CodeDeploy

### Question 18
Which service is primarily used to distribute content to global users with low latency?
* A) Amazon Route 53
* B) Amazon CloudFront
* C) AWS Global Accelerator
* D) Amazon S3

### Question 19
Which pillar of the Well-Architected Framework focuses on the ability of a system to recover from infrastructure or service disruptions?
* A) Security
* B) Reliability
* C) Sustainability
* D) Operational Excellence

### Question 20
What is the MOST cost-effective way to store data that is accessed only once or twice a year, with a retrieval time of 12 hours?
* A) S3 Standard-IA
* B) S3 Glacier Flexible Retrieval
* C) S3 Glacier Deep Archive
* D) S3 One Zone-IA

### Question 21
A company needs to store files that can be accessed simultaneously by multiple EC2 instances across different Availability Zones. Which storage service is BEST?
* A) Amazon EBS
* B) Amazon EFS
* C) Amazon Instance Store
* D) Amazon S3

### Question 22
Which AWS service provides on-demand downloads of AWS security and compliance reports?
* A) AWS Secrets Manager
* B) AWS Artifact
* C) AWS Certificate Manager
* D) AWS Shield

### Question 23
Which service can identify if an Amazon S3 bucket is publicly accessible?
* A) Amazon Inspector
* B) AWS Trusted Advisor
* C) Amazon CloudWatch
* D) AWS WAF

### Question 24
A company wants to be notified when their monthly AWS bill exceeds a specific threshold. Which service should they use?
* A) AWS Cost Explorer
* B) AWS Budgets
* C) AWS Trusted Advisor
* D) Amazon Simple Email Service (SES)

### Question 25
Which of the following defines "Agility" in the context of AWS Cloud?
* A) The ability to scale resources up and down based on demand.
* B) The ability to reduce the time required to make resources available to developers.
* C) The ability to recover from a system failure automatically.
* D) The ability to deploy applications globally in minutes.

### Question 26
Which service would you use to manage your encryption keys?
* A) AWS Certificate Manager (ACM)
* B) AWS CloudHSM
* C) AWS Key Management Service (KMS)
* D) AWS Secrets Manager

### Question 27
Which of the following is a benefit of moving to the AWS Cloud?
* A) Increased Capital Expenditure (CapEx)
* B) Decreased Variable Expense
* C) Stop spending money on running and maintaining data centers
* D) Manual provisioning of all resources

### Question 28
A company is experiencing DDoS attacks on its web application. Which AWS services can help mitigate these attacks? (Choose TWO)
* A) AWS Shield
* B) Amazon GuardDuty
* C) AWS WAF
* D) AWS KMS
* E) Amazon Inspector

### Question 29
Which EC2 feature allows you to automatically add or remove instances based on changes in demand?
* A) Elastic Load Balancing
* B) Amazon EC2 Auto Scaling
* C) Amazon CloudWatch
* D) AWS Lambda

### Question 30
Which AWS service allows you to create a virtual network in the cloud?
* A) AWS Direct Connect
* B) Amazon VPC
* C) Amazon Route 53
* D) AWS Transit Gateway

### Question 31
A company needs to store a large amount of unstructured data. Which service is MOST appropriate?
* A) Amazon RDS
* B) Amazon EBS
* C) Amazon S3
* D) Amazon DynamoDB

### Question 32
Which of the following are components of an AWS VPC? (Choose TWO)
* A) Subnets
* B) IAM Roles
* C) Internet Gateways
* D) S3 Buckets
* E) Edge Locations

### Question 33
Which AWS service provides a way to convert video and audio files into formats that will play on mobile devices, tablets, and PCs?
* A) Amazon Rekognition
* B) Amazon Polly
* C) Amazon Elastic Transcoder
* D) Amazon Comprehend

### Question 34
A user wants to find out which AWS services are most commonly used in their account to optimize costs. Which tool should they use?
* A) AWS Budgets
* B) AWS Cost Explorer
* C) AWS Pricing Calculator
* D) AWS Trusted Advisor

### Question 35
Which of the following is a feature of Amazon Route 53?
* A) Content Caching
* B) Domain Name Registration
* C) Firewall protection
* D) Data Encryption

### Question 36
A company wants to run its own containerized applications on AWS without managing the underlying EC2 instances. Which service should they use?
* A) Amazon ECS with EC2 launch type
* B) AWS Fargate
* C) Amazon EKS
* D) AWS Elastic Beanstalk

### Question 37
Which AWS service uses machine learning to automatically analyze and extract text and data from scanned documents?
* A) Amazon Comprehend
* B) Amazon Rekognition
* C) Amazon Textract
* D) Amazon Polly

### Question 38
Which of the following is a characteristic of an AWS Region?
* A) A single data center
* B) A collection of Edge Locations
* C) A physical location consisting of multiple Availability Zones
* D) A specific rack in an AWS data center

### Question 39
Which AWS service provides real-time guidance to help you provision your resources following AWS best practices?
* A) AWS Config
* B) AWS Trusted Advisor
* C) Amazon Inspector
* D) AWS CloudTrail

### Question 40
What is the minimum number of Availability Zones you should use for a highly available architecture?
* A) 1
* B) 2
* C) 3
* D) 4

### Question 41
Which of the following are benefits of using Amazon RDS instead of installing a database on an EC2 instance? (Choose TWO)
* A) Automated backups and patching
* B) Full control over the operating system
* C) High availability with Multi-AZ deployment
* D) Lower cost for small, infrequent workloads
* E) Support for any custom database engine

### Question 42
Which service is used to protect against common web exploits such as SQL injection and Cross-Site Scripting (XSS)?
* A) AWS Shield
* B) AWS WAF
* C) Amazon GuardDuty
* D) AWS Firewall Manager

### Question 43
A company has a legacy application that requires a specific version of an operating system and a specific set of software installed. Which compute service is the BEST fit?
* A) AWS Lambda
* B) AWS Fargate
* C) Amazon EC2
* D) Amazon Lightsail

### Question 44
Which AWS service is used to create and manage a collection of related AWS resources in a predictable and repeatable way using code?
* A) AWS Elastic Beanstalk
* B) AWS CloudFormation
* C) AWS OpsWorks
* D) AWS Systems Manager

### Question 45
Which of the following can be used to gain programmatic access to AWS? (Choose TWO)
* A) AWS Management Console
* B) AWS Command Line Interface (CLI)
* C) AWS SDKs
* D) AWS Personal Health Dashboard
* E) AWS Trusted Advisor

### Question 46
Which service provides a highly available and scalable Domain Name System (DNS) web service?
* A) Amazon VPC
* B) Amazon Route 53
* C) Amazon CloudFront
* D) AWS Direct Connect

### Question 47
A company wants to improve the performance of their global application by using the AWS private network to route traffic to the nearest endpoint. Which service should they use?
* A) Amazon CloudFront
* B) AWS Global Accelerator
* C) AWS Site-to-Site VPN
* D) Amazon Route 53

### Question 48
Which AWS service allows you to build conversational interfaces into any application using voice and text?
* A) Amazon Polly
* B) Amazon Lex
* C) Amazon Rekognition
* D) Amazon Comprehend

### Question 49
Which of the following is a principle of the AWS Well-Architected Framework's "Sustainability" pillar?
* A) Maximize utilization of resources
* B) Minimize the number of AWS accounts
* C) Use as many EC2 instances as possible to ensure reliability
* D) Always use the latest generation of hardware

### Question 50
Which AWS service provides a searchable inventory of your AWS resources and tracks changes to their configurations over time?
* A) AWS CloudTrail
* B) AWS Config
* C) AWS Trusted Advisor
* D) Amazon Inspector

### Question 51
A developer needs to store a password for a database. Which AWS service is designed for securely storing and rotating secrets?
* A) AWS Key Management Service (KMS)
* B) AWS Secrets Manager
* C) AWS Systems Manager Parameter Store
* D) AWS IAM

### Question 52
Which service would you use to provide temporary security credentials to users who sign in through a social identity provider like Google or Facebook?
* A) AWS IAM
* B) Amazon Cognito
* C) AWS Directory Service
* D) AWS Organizations

### Question 53
Which of the following describes the concept of "Elasticity" in AWS?
* A) The ability to scale up a single instance by adding more RAM.
* B) The ability to automatically grow and shrink resources based on demand.
* C) The ability to store an unlimited amount of data in S3.
* D) The ability to run applications in multiple regions.

### Question 54
Which AWS service is used to automate the assessment of applications for exposure, vulnerabilities, and deviations from best practices?
* A) Amazon GuardDuty
* B) Amazon Inspector
* C) AWS WAF
* D) AWS Trusted Advisor

### Question 55
A company needs to run a data warehouse for complex analytical queries. Which AWS service should they use?
* A) Amazon RDS
* B) Amazon DynamoDB
* C) Amazon Redshift
* D) Amazon ElastiCache

### Question 56
Which of the following is part of the AWS "Economy of Scale" benefit?
* A) Users can deploy resources in minutes.
* B) AWS can achieve lower variable costs due to its massive scale.
* C) AWS provides free support for all users.
* D) AWS automatically manages all customer security responsibilities.

### Question 57
Which IAM entity is used to grant permissions to an AWS service so it can access other AWS services?
* A) IAM User
* B) IAM Group
* C) IAM Role
* D) IAM Policy

### Question 58
Which of the following are use cases for Amazon S3? (Choose TWO)
* A) Hosting a static website
* B) Running a relational database
* C) Storing software backup images
* D) Storing frequently changing files for a high-performance compute cluster
* E) Acting as a boot volume for an EC2 instance

### Question 59
What is the purpose of an Internet Gateway in an AWS VPC?
* A) To provide a private connection to a data center.
* B) To allow communication between the VPC and the internet.
* C) To load balance traffic across multiple EC2 instances.
* D) To encrypt data at rest within the VPC.

### Question 60
Which AWS support plan provides access to a dedicated Technical Account Manager (TAM)?
* A) Developer
* B) Business
* C) Enterprise On-Ramp
* D) Enterprise

### Question 61
A user wants to transfer petabytes of data to AWS using a physical device because the internet connection is too slow. Which service should they use?
* A) AWS DataSync
* B) AWS Snowball Edge
* C) AWS Storage Gateway
* D) Amazon S3 Transfer Acceleration

### Question 62
Which of the following describes the "Reliability" pillar of the Well-Architected Framework?
* A) The ability to run workloads efficiently.
* B) The ability of a system to recover from failure and mitigate disruptions.
* C) The ability to protect information and systems.
* D) The focus on using the fewest resources to meet requirements.

### Question 63
A company has several AWS accounts and wants to benefit from volume discounts by combining their usage. Which feature should they use?
* A) AWS Budgets
* B) Consolidated Billing
* C) AWS Cost Explorer
* D) Savings Plans

### Question 64
Which service is an automated security assessment service that helps improve the security and compliance of applications deployed on AWS?
* A) AWS Shield
* B) Amazon Inspector
* C) AWS WAF
* D) Amazon Macie

### Question 65
Which AWS service allows you to quickly deploy and manage applications in the AWS Cloud without having to learn about the infrastructure that runs those applications?
* A) Amazon EC2
* B) AWS CloudFormation
* C) AWS Elastic Beanstalk
* D) AWS OpsWorks

---

## SECTION 2 — ANSWER KEY

| Q# | Answer | Q# | Answer | Q# | Answer |
|---|---|---|---|---|---|
| 1 | B | 23 | B | 45 | B, C |
| 2 | D | 24 | B | 46 | B |
| 3 | C | 25 | B | 47 | B |
| 4 | B | 26 | C | 48 | B |
| 5 | B, D | 27 | C | 49 | A |
| 6 | C | 28 | A, C | 50 | B |
| 7 | B | 29 | B | 51 | B |
| 8 | B | 30 | B | 52 | B |
| 9 | B | 31 | C | 53 | B |
| 10 | C | 32 | A, C | 54 | B |
| 11 | B | 33 | C | 55 | C |
| 12 | B | 34 | B | 56 | B |
| 13 | B | 35 | B | 57 | C |
| 14 | C | 36 | B | 58 | A, C |
| 15 | A, C | 37 | C | 59 | B |
| 16 | B | 38 | C | 60 | D |
| 17 | A | 39 | B | 61 | B |
| 18 | B | 40 | B | 62 | B |
| 19 | B | 41 | A, C | 63 | B |
| 20 | C | 42 | B | 64 | B |
| 21 | B | 43 | C | 65 | C |
| 22 | B | 44 | B | | |
