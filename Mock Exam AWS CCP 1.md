1. An eCommerce company plans to use the AWS Cloud to quickly deliver new functionality in an iterative manner, minimizing the time to market.

Which feature of the AWS Cloud provides this functionality?

Elasticity
Agility
Cost effectiveness
Fault tolerance

---

**Answer:**

The feature of the AWS Cloud that aligns with the goal of quickly delivering new functionality in an iterative manner, minimizing time to market, is **Agility** AWS offers various services and tools that enable rapid development, deployment, and scaling of applications, allowing businesses to be more agile in responding to market demands and changing requirements.

---

2. According to the AWS Shared responsibility model, which two tasks are the responsibility of AWS? (Select TWO.)

Manage customer data
Provide physical security for Availability Zones
Encrypt client-side data and authenticate data integrity
Patch the operating system of Amazon S3
Perform identity and access management

---

**Answer:**

According to the AWS Shared Responsibility Model:

1. **Provide physical security for Availability Zones**: AWS is responsible for providing and maintaining the physical security of the infrastructure in the Availability Zones, which includes securing the data centers, facilities, and the hardware infrastructure.

2. **Patch the operating system of Amazon S3**: AWS manages and is responsible for patching and maintaining the underlying infrastructure and services like Amazon S3, including activities related to the operating system and platform.

The other tasks mentioned fall under the customer's responsibility within the AWS Shared Responsibility Model

---

3. A user has limited knowledge of AWS services, but wants to quickly deploy a scalable Node.js application in an Amazon VPC.

Which service should be used to deploy the application?

Amazon EC2
AWS Elastic Beanstalk
AWS CloudFormation
Amazon LightSail

---

**Answer:**

For deploying a scalable Node.js application in an Amazon VPC while considering the user's limited knowledge of AWS services, the ideal choice would be **AWS Elastic Beanstalk**.

AWS Elastic Beanstalk simplifies the deployment and management of applications by automatically handling the details of capacity provisioning, load balancing, auto-scaling, and application health monitoring. It supports various platforms, including Node.js, and allows users to easily deploy applications within an Amazon VPC while abstracting much of the underlying infrastructure complexity. This service is particularly useful for users seeking a quick and straightforward way to deploy scalable applications without needing in-depth knowledge of AWS services.

---

4. What can be used to allow an application running on an Amazon EC2 instance to securely store data in an Amazon S3 bucket without using long-term credentials?

Amazon Connect
AWS IAM access key
AWS Systems Manager
AWS IAM role

---

**Answer:**

To securely allow an application running on an Amazon EC2 instance to access and store data in an Amazon S3 bucket without using long-term credentials, you can utilize an **AWS IAM role**.

IAM roles enable you to delegate permissions to entities that you trust (in this case, the EC2 instance) without having to share long-term credentials. By attaching an IAM role to the EC2 instance, you can grant it temporary credentials with the necessary permissions to interact securely with the S3 bucket. This method ensures security and eliminates the need for storing sensitive credentials within the application code or on the EC2 instance itself.

---

5. Which of the following can be used to identify a specific user who terminated an Amazon RDS DB instance?

AWS CloudTrail
AWS Trusted Advisor
Amazon Inspector
Amazon CloudWatch

---

**Answer:**

To identify a specific user who terminated an Amazon RDS DB instance, you would typically refer to **AWS CloudTrail**.

AWS CloudTrail is a service that provides a record of actions taken by a user, role, or an AWS service in your AWS account. It logs API calls made within your account, including details such as the identity of the entity making the request (user, role, etc.), the time of the request, the action performed, and more. By examining the CloudTrail logs, you can trace back and identify the specific user who terminated an Amazon RDS DB instance or performed any other action within your AWS environment.

---

6. A Cloud Practitioner noticed that IP addresses that are owned by AWS are being used to attempt to flood ports on some of the company’s systems.

To whom should the issue be reported?

AWS Partner Network (APN)
AWS Professional Services
AWS Trust &amp; Safety team
AWS Technical Account Manager (TAM)

---

**Answer:**

The issue of AWS-owned IP addresses attempting to flood ports on the company's systems should be reported to the **AWS Trust &amp; Safety team**. They handle security-related concerns, abuse reports, and potential malicious activities involving AWS services or infrastructure.

Reporting such security incidents to the AWS Trust &amp; Safety team is crucial as they are responsible for investigating and taking appropriate actions to address security concerns, ensure compliance, and maintain a secure environment for AWS customers.

---

7. Which of the following is an advantage for a company running workloads in the AWS Cloud vs on-premises?

Lower overall utilization of server and storage systems
Less staff time is required to launch new workloads
Increased time to market for new application features
Higher acquisition costs to support elastic workloads

---

**Answer:**

An advantage for a company running workloads in the AWS Cloud compared to on-premises environments is:

**Less staff time is required to launch new workloads.**

In AWS, the provisioning and deployment of resources can be automated using services like AWS CloudFormation, AWS Elastic Beanstalk, or AWS Lambda, among others. This automation reduces the time and effort required to set up and launch new workloads compared to traditional on-premises environments where manual provisioning and setup might be needed, thereby saving staff time and increasing operational efficiency.

---

8. Which benefits can a company immediately realize using the AWS Cloud? (Select TWO.)

User control of physical infrastructure
Increased agility
Capital expenses are replaced with variable expenses
Variable expenses are replaced with capital expenses
No responsibility for security

---

**Answer:**

The benefits that a company can immediately realize using the AWS Cloud are:

- **Increased agility**: AWS provides a flexible and scalable environment where resources can be provisioned and scaled rapidly, allowing companies to respond quickly to changing business needs and market demands.
- **Capital expenses are replaced with variable expenses**: AWS operates on a pay-as-you-go pricing model, allowing companies to pay only for the resources they use without the upfront costs associated with purchasing and maintaining physical infrastructure. This helps in converting capital expenses into more manageable and scalable variable expenses.

The other options mentioned, such as user control of physical infrastructure, variable expenses replaced with capital expenses, and no responsibility for security, do not accurately represent immediate benefits or the general nature of AWS cloud services.

---

9. Which technology can automatically adjust compute capacity as demand for an application increases or decreases?

Auto Scaling
High availability
Fault tolerance
Load balancing

---

**Answer:**

The technology that can automatically adjust compute capacity as demand for an application increases or decreases is **Auto Scaling**.

Auto Scaling is an AWS feature that enables you to automatically adjust the number of compute resources, such as Amazon EC2 instances, based on predefined conditions or parameters. This helps maintain application availability and performance during varying levels of demand. As demand increases, Auto Scaling can automatically add more instances, and as demand decreases, it can reduce the number of instances, optimizing costs while ensuring the application's scalability and responsiveness.

---

10. Which AWS dashboard displays relevant and timely information to help users manage events in progress, and provides proactive notifications to help plan for scheduled activities?

Amazon CloudWatch dashboard
AWS Service Health Dashboard
AWS Personal Health Dashboard
AWS Trusted Advisor dashboard

---

**Answer:**

The AWS dashboard that displays relevant and timely information to help users manage events in progress and provides proactive notifications for scheduled activities is the **AWS Personal Health Dashboard**.

The AWS Personal Health Dashboard provides alerts and notifications about the health of AWS services that a user is using. It includes information about scheduled maintenance, operational issues, and other events that may affect the user's resources. This dashboard assists users in managing events and taking proactive actions to plan for scheduled activities or respond to issues impacting their AWS resources.

---

11. According to the shared responsibility mode, which security and compliance task is AWS responsible for?

Granting permissions to users and services
Encrypting data at rest
Updating Amazon EC2 host firmware
Updating operating systems

---

**Answer:**

According to the AWS shared responsibility model:

The security and compliance task that AWS is responsible for is **updating Amazon EC2 host firmware**.

AWS manages the underlying infrastructure, including updating the host firmware of EC2 instances, to ensure the security and reliability of the physical infrastructure supporting the cloud services.

---

12. What AWS service, tool, or feature can help companies identify underutilized Amazon EC2 instances and reduce their costs?

Amazon Inspector
Cost Explorer
Consolidated billing
AWS Trusted Advisor

---

**Answer:**

The AWS service that can help companies identify underutilized Amazon EC2 instances and reduce their costs is **AWS Trusted Advisor**.

AWS Trusted Advisor is a tool that inspects your AWS environment and provides recommendations across various categories, including cost optimization, security, performance, and fault tolerance. In the context of identifying underutilized Amazon EC2 instances, Trusted Advisor offers insights into resource utilization, which can help in identifying instances that are underutilized or idle. By acting on these recommendations, companies can optimize their resources, reduce costs, and improve the efficiency of their AWS infrastructure.

---

13. How can an organization gain access to compliance reports natively through the AWS console?

AWS Identity and Access Management (IAM)
AWS Certificate Manager (ACM)
AWS Artifact
AWS Security Hub

---

**Answer:**

An organization can gain access to compliance reports natively through the AWS console using **AWS Artifact**.

AWS Artifact is a service that provides on-demand access to AWS compliance reports and select online agreements. It offers downloadable compliance reports, including certifications, attestations, and other documents related to AWS services. Users can access these reports directly through the AWS Management Console using AWS Artifact, facilitating easy access to compliance-related documentation.

---

14. Which AWS service can be used to run Docker containers?

AWS Lambda
Amazon ECR
Amazon AMI
Amazon ECS

---

**Answer:**

The AWS service that can be used to run Docker containers is **Amazon ECS (Elastic Container Service)**.

Amazon ECS is a fully managed container orchestration service that supports Docker containers. It allows users to run, stop, and manage Docker containers on a cluster of EC2 instances. With ECS, users can easily deploy and scale containerized applications while managing the underlying infrastructure resources efficiently.

---

15. Which AWS service or feature allows a company to receive a single monthly AWS bill when using multiple AWS accounts?

AWS Cost and Usage report
Amazon Cloud Directory
AWS Cost Explorer
Consolidated billing

---

**Answer:**

The AWS service or feature that allows a company to receive a single monthly AWS bill when using multiple AWS accounts is called **Consolidated billing**.

Consolidated billing enables the organization to consolidate payment for multiple AWS accounts within a single payer account. This way, the payer account receives a combined bill that includes the charges from all linked accounts, simplifying the billing and payment process for organizations with multiple AWS accounts.

---

16. Which AWS service can be used to load data from Amazon S3, transform it, and move it to another destination?

Amazon RedShift
Amazon Kinesis
AWS Glue
Amazon EMR

---

**Answer:**

The AWS service that can be used to load data from Amazon S3, transform it, and move it to another destination is **AWS Glue**.

AWS Glue is a fully managed extract, transform, and load (ETL) service that allows users to prepare and transform their data for analytics. It can automatically discover and catalog metadata from various data sources, including Amazon S3, perform ETL operations using a visual interface or custom code, and move the transformed data to another destination, such as another database or data warehouse.

---

17. An application has highly dynamic usage patterns. Which characteristics of the AWS Cloud make it cost-effective for this type of workload? (Select TWO.)

Elasticity
Pay-as-you-go pricing
Strict security
High availability
Reliability

---

**Answer:**

The characteristics of the AWS Cloud that make it cost-effective for an application with highly dynamic usage patterns are:

- **Elasticity**: AWS offers elasticity, allowing resources to automatically scale up or down based on demand. This means that the application can dynamically adjust its resources to match varying workloads, optimizing costs by scaling resources only when needed.
- **Pay-as-you-go pricing**: AWS operates on a pay-as-you-go pricing model, where you pay for the resources you consume. With this pricing model, the costs align directly with the usage of resources. Therefore, for a highly dynamic workload, paying only for the actual resources used during spikes and scaling down during low usage periods can result in cost savings compared to fixed infrastructure costs.

Strict security, high availability, and reliability are important features of the AWS Cloud but might not directly influence the cost-effectiveness of a workload with highly dynamic usage patterns. They are essential for ensuring the security, availability, and reliability of the application but might not directly impact cost optimization based on workload fluctuations.

---

18. Which AWS service should a Cloud Practitioner use to automate conﬁguration management using Puppet?

AWS OpsWorks
AWS CloudFormation
AWS Conﬁg
AWS Systems Manager

---

**Answer:**

For automating configuration management using Puppet on AWS, the appropriate service to use would be **AWS OpsWorks**.

AWS OpsWorks provides managed instances of Chef and Puppet for configuration management, automating tasks like software configurations, deployment, and management. Specifically, it offers an integrated Puppet solution for managing infrastructure and applications within the AWS ecosystem. Therefore, for a Cloud Practitioner aiming to automate configuration management using Puppet, AWS OpsWorks would be the suitable service to utilize.

---

19. Which AWS service is a fully-managed source control service that hosts secure Git-based repositories?

AWS CodePipeline
AWS CodeCommit
AWS CodeBuild
AWS CodeDeploy

---

**Answer:**

The AWS service that serves as a fully-managed source control service hosting secure Git-based repositories is **AWS CodeCommit**.

AWS CodeCommit is a version control service that enables teams to host secure and scalable Git repositories. It provides a secure and highly available repository for storing code, facilitating collaboration among developers working on projects and ensuring version control for software development.

---

20. Which AWS-managed service can be used to process vast amounts of data using a hosted Hadoop framework?

Amazon DynamoDB
Amazon Redshift
Amazon Athena
Amazon EMR

---

**Answer:**

The AWS-managed service that can be used to process vast amounts of data using a hosted Hadoop framework is **Amazon EMR (Elastic MapReduce)**.

Amazon EMR is a service that provides a managed Hadoop framework to process and analyze large amounts of data across a distributed cluster of EC2 instances. It supports various big data processing frameworks like Hadoop, Spark, Presto, and others, making it suitable for diverse data processing and analytics tasks on large datasets.

---

21. Amazon S3 is typically used for which of the following use cases? (Select TWO.)

Host a static website
Message queue
Media hosting
In-memory data cache
Install an operating system

---

**Answer:**

Amazon S3 (Simple Storage Service) is typically used for the following use cases:

- **Host a static website**: Amazon S3 allows users to host static websites by storing HTML, CSS, JavaScript, and other web assets in S3 buckets, making them accessible via a public URL.
- **Media hosting**: S3 is often used to store and serve various types of media files such as images, videos, audio files, and other digital content due to its scalability, durability, and ease of access.

Amazon S3 is not typically used for message queuing, in-memory data caching, or installing an operating system.

---

22. A Service Control Policy (SCP) is used to manage the maximum available permissions and is associated with which of the following?

Service control policies (SCPs) manage permissions for which of the following?

AWS Regions
AWS Organizations
AWS Global Infrastructure
Availability Zones

---

**Answer:**

Service Control Policies (SCPs) are associated with **AWS Organizations**.

AWS Organizations is a service that allows you to centrally manage and govern multiple AWS accounts. SCPs are a feature of AWS Organizations used to manage the maximum available permissions for entities within an organization. SCPs define the permissions that can be applied to member accounts, organizational units, or the entire organization, controlling access to AWS services and resources within those accounts.

---

23. What can a Cloud Practitioner use the AWS Total Cost of Ownership (TCO) Calculator for?

Estimate savings when comparing the AWS Cloud to an on-premises environment
Enable billing alerts to monitor actual AWS costs compared to estimated costs
Estimate a monthly bill for the AWS Cloud resources that will be used
Generate reports that break down AWS Cloud compute costs by duration, resource, or tags

---

**Answer:**

The AWS Total Cost of Ownership (TCO) Calculator is used by a Cloud Practitioner for:

**Estimating savings when comparing the AWS Cloud to an on-premises environment.**

The TCO Calculator assists in estimating and comparing the costs of running workloads in an on-premises environment versus using comparable services in the AWS Cloud. It helps in understanding potential cost savings, operational efficiencies, and other financial considerations associated with migrating to or running workloads in the AWS Cloud compared to an on-premises setup.

---

24. A company has a global user base and needs to deploy AWS services that can decrease network latency for their users. Which services may assist? (Select TWO.)

Amazon CloudFront
AWS Direct Connect
Application Auto Scaling
Amazon VPC
AWS Global Accelerator

---

**Answer:**

For a company with a global user base aiming to decrease network latency, the following AWS services may assist:

- **Amazon CloudFront**: CloudFront is a content delivery network (CDN) service that caches content at edge locations worldwide. It helps in reducing latency by serving content to users from the nearest edge location, thereby improving the overall user experience.
- **AWS Global Accelerator**: Global Accelerator is designed to improve the availability and performance of applications with global users by optimizing the routing path to the AWS infrastructure. It uses the AWS global network to route traffic via the least congested and lowest-latency path to improve responsiveness for users.

Both Amazon CloudFront and AWS Global Accelerator are services aimed at reducing latency and improving the delivery of content or applications to users across the globe.

---

25. Which AWS service should a Cloud Practitioner use to establish a secure network connection between an on-premises network and AWS?

AWS Web Application Firewall (WAF)
AWS Mobile Hub
Amazon Virtual Private Cloud (VPC)
Virtual Private Network

---

**Answer:**

The AWS service that a Cloud Practitioner should use to establish a secure network connection between an on-premises network and AWS is **Virtual Private Network (VPN)**.

A VPN connection allows secure communication between an on-premises network (via a customer's network device) and the Amazon Virtual Private Cloud (VPC) over the internet. It creates an encrypted tunnel for transmitting data, ensuring a secure and private connection between the on-premises infrastructure and resources hosted in the AWS Cloud.

---

26. A cloud practitioner needs to migrate a 70 TB of data from an on-premises data center into the AWS Cloud. The company has a slow and unreliable internet connection.

Which AWS service can the cloud practitioner leverage to transfer the data?

AWS Storage Gateway
AWS DataSync
Amazon S3 Glacier
AWS Snowball

---

**Answer:**

Given the large amount of data (70 TB) and the limitations of a slow and unreliable internet connection, the AWS service that a cloud practitioner can leverage to transfer the data is **AWS Snowball**.

AWS Snowball is a physical data transport solution that simplifies large-scale data transfers into and out of the AWS Cloud. It involves a physical device (Snowball) that is shipped to the customer's location, allowing them to securely transfer large amounts of data by physically transferring the data on the device. Once the data is loaded onto the Snowball device, it can be shipped back to AWS to upload the data into an S3 bucket within the AWS Cloud, bypassing the constraints of slow or unreliable internet connections for large-scale data migration.

---

27. Which on-premises costs must be included in a Total Cost of Ownership (TCO) calculation when comparing against the AWS Cloud? (Select TWO.)

Project management services
Operating system administration
Network infrastructure in the data center
Physical compute hardware
Database schema development

---

**Answer:**

When calculating the Total Cost of Ownership (TCO) to compare against the AWS Cloud, the following on-premises costs should be included:

- **Network infrastructure in the data center**: This includes costs associated with networking hardware, switches, routers, cabling, and related infrastructure required for the on-premises network.
- **Physical compute hardware**: This encompasses costs associated with purchasing, maintaining, and upgrading the physical servers or compute hardware used in the on-premises data center.

Project management services, operating system administration, and database schema development are important aspects of IT operations but are not direct on-premises infrastructure costs that need to be accounted for in a TCO comparison against the AWS Cloud.

---

28. A user needs an automated security assessment report that will identify unintended network access to Amazon EC2 instances and vulnerabilities on those instances.

Which AWS service will provide this assessment report?

Amazon Inspector
AWS Conﬁg
Amazon Macie
EC2 security groups

---

**Answer:**

For automated security assessment and identifying unintended network access as well as vulnerabilities on Amazon EC2 instances, the AWS service that provides this assessment report is **Amazon Inspector**.

Amazon Inspector is an automated security assessment service that examines the security posture of AWS resources, including EC2 instances. It helps in identifying security vulnerabilities, unintended network access, and deviations from security best practices by analyzing the configuration and behavior of EC2 instances, providing detailed security assessment reports.

---

29. Which service can a Cloud Practitioner use to configure custom cost and usage limits and enable alerts for when defined thresholds are exceeded?

Consolidated billing
Cost Explorer
AWS Trusted Advisor
AWS Budgets

---

**Answer:**

A Cloud Practitioner can use **AWS Budgets** to configure custom cost and usage limits and enable alerts for when defined thresholds are exceeded.

AWS Budgets is a service that allows users to set custom budgets for cost and usage, defining limits based on expenditures or usage patterns. Users can receive alerts via email or SNS (Simple Notification Service) when their defined thresholds are approaching or exceeded, helping them to proactively monitor and control costs within AWS.

---

30. A company is migrating virtual machines (VMs) from their data center to the AWS Cloud. The company plans to deploy these migrated machines on Amazon EC2.

Which cloud computing model will the company use for this operation?

Platform as a Service (PaaS)
Infrastructure as a Service (IaaS)
Function as a Service (FaaS)
Software as a Service (SaaS)

---

**Answer:**

The cloud computing model that the company will use for migrating virtual machines (VMs) from their data center to Amazon EC2 is **Infrastructure as a Service (IaaS)**.

Infrastructure as a Service (IaaS) provides virtualized computing resources over the internet. With Amazon EC2 (Elastic Compute Cloud), users can access and control virtual servers (EC2 instances) in the AWS Cloud, allowing them to migrate their existing VMs to the cloud infrastructure while retaining control over the operating system, applications, and configurations, similar to the control they had in their own data center.

---

31. Which AWS service does AWS Snowball Edge natively support?

AWS Trusted Advisor
AWS Database Migration Service (AWS DMS)
Amazon EC2
AWS Server Migration Service (AWS SMS)

---

**Answer:**

AWS Snowball Edge natively supports **Amazon EC2 (Elastic Compute Cloud)**.

Snowball Edge is a physical data transfer device that also includes limited compute capabilities. Users can run EC2 instances on Snowball Edge devices to perform edge computing tasks closer to the data source, enabling data processing and analysis in remote or disconnected environments before transferring the data back to AWS.

---

32. A Cloud Practitioner wants to configure the AWS CLI for programmatic access to AWS services. Which credential components are required? (Select TWO.)

A secret access key
An access key ID
A public key
An IAM Role
A private key

---

**Answer:**

To configure the AWS CLI for programmatic access to AWS services, the required credential components are:

- **An access key ID**: This is an identifier used to authenticate requests made to AWS services.
- **A secret access key**: This key is associated with the access key ID and is used for cryptographic signing of requests sent to AWS, providing secure access.

An IAM Role, public key, and private key are not directly used as credential components for configuring the AWS CLI for programmatic access.

---

33. How should an organization deploy an application running on multiple EC2 instances to ensure that a power failure does not cause an application outage?

Launch the EC2 instances in separate regions
Launch the EC2 instances into Edge Locations
Launch the EC2 instances into different Availability Zones
Launch the EC2 instances into different VPCs

---

**Answer:**

To ensure that a power failure does not cause an application outage, an organization should deploy an application running on multiple EC2 instances into **different Availability Zones**.

AWS Availability Zones (AZs) are distinct locations within a region that are engineered to be isolated from failures in other AZs. By distributing EC2 instances across different Availability Zones within the same region, the organization can achieve high availability and fault tolerance. This setup helps ensure that if a power failure or other localized issue affects one Availability Zone, the application running on instances in other AZs remains operational, minimizing the risk of an application outage.

---

34. Which AWS service is used to send both text and email messages from distributed applications?

Amazon Simple Workflow Service (Amazon SWF)
Amazon Simple Queue Service (Amazon SQS)
Amazon Simple Notiﬁcation Service (Amazon SNS)
Amazon Simple Email Service (Amazon SES)

---

**Answer:**

The AWS service used to send both text (SMS) and email messages from distributed applications is **Amazon Simple Notification Service (Amazon SNS)**.

Amazon SNS is a fully managed pub/sub messaging service that supports sending notifications (including both text messages and emails) to a variety of endpoints, such as mobile devices, email, HTTP, SQS, Lambda, and more. It allows developers to send messages to multiple subscribers simultaneously, making it suitable for distributed applications that need to send notifications across different communication channels.

---

35. A company is interested in moving its on-premises NoSQL database into the AWS Cloud.

Which AWS service should the company use to replace their existing database?

Amazon RDS for MySQL
Amazon Quantum Ledger Database (Amazon QLDB)
Amazon DynamoDB
Amazon Redshift

---

**Answer:**

To replace an on-premises NoSQL database while moving into the AWS Cloud, the suitable AWS service to consider is **Amazon DynamoDB**.

Amazon DynamoDB is a fully managed NoSQL database service provided by AWS. It offers seamless scalability, high performance, and reliability for applications that require a flexible and distributed non-relational database solution. DynamoDB can serve as a suitable replacement for an existing on-premises NoSQL database in the AWS Cloud.

---

36. Which AWS services offer compute capabilities? (Select TWO.)

Amazon DynamoDB
Amazon CloudHSM
AWS Lambda
Amazon EFS
Amazon ECS

---

**Answer:**

The AWS services that offer compute capabilities are:

- **AWS Lambda**: It provides serverless compute where you can run code without provisioning or managing servers, paying only for the compute time consumed.
- **Amazon ECS (Elastic Container Service)**: It allows you to run and manage containers at scale using Docker containers on EC2 instances, providing compute resources for containerized applications.

Amazon DynamoDB is a fully managed NoSQL database service, Amazon CloudHSM is a hardware security module service, and Amazon EFS (Elastic File System) is a scalable file storage service. These services do not directly offer compute capabilities; instead, they cater to storage, security, and database needs.

---

37. Which of the following tasks can a user perform to optimize Amazon EC2 costs? (Select TWO.)

Implement Auto Scaling groups to add and remove instances based on demand
Set a budget to limit spending on Amazon EC2 instances using AWS Budgets
Create a policy to restrict IAM users from accessing the Amazon EC2 console
Purchase Amazon EC2 Reserved Instances
Create users in a single Region to reduce the spread of EC2 instances globally

---

**Answer:**

To optimize Amazon EC2 costs, the following tasks can be performed:

- **Implement Auto Scaling groups to add and remove instances based on demand**: Auto Scaling automatically adjusts the number of EC2 instances based on demand, helping optimize costs by scaling resources to match actual needs.
- **Purchase Amazon EC2 Reserved Instances**: Reserved Instances offer significant cost savings compared to On-Demand Instances by providing a discounted pricing model for a specified term. This can help reduce EC2 costs for predictable workloads.

Setting a budget using AWS Budgets can assist in monitoring and controlling costs but does not directly optimize EC2 costs. Creating policies to restrict IAM users and concentrating users in a single region do not directly impact EC2 cost optimization.

---

38. Which AWS hybrid storage service enables a user’s on-premises applications to seamlessly use AWS Cloud storage?

AWS Backup
AWS Storage Gateway
AWS Direct Connect
Amazon Connect

---

**Answer:**

The AWS hybrid storage service that enables a user's on-premises applications to seamlessly use AWS Cloud storage is **AWS Storage Gateway**.

AWS Storage Gateway allows on-premises applications to access virtually unlimited AWS Cloud storage while maintaining on-premises hardware. It acts as a bridge between on-premises environments and the AWS Cloud, providing different storage interfaces, such as file, volume, or tape, to connect on-premises systems with various AWS storage services like Amazon S3, Amazon Glacier, and others.

---

39. According to the shared responsibility model, which security-related task is the responsibility of the customer?

Maintaining physical networking configuration
Securing servers and racks at AWS data centers
Maintaining server-side encryption
Maintaining firewall configurations at a hardware level

---

**Answer:**

Within the AWS Shared Responsibility Model, the security-related task that is the responsibility of the customer is:

- **Maintaining server-side encryption**: Ensuring encryption of data at rest, which involves managing encryption keys, implementing encryption mechanisms, and handling encryption-related configurations, is the responsibility of the customer.

The other tasks mentioned are the responsibility of AWS or fall outside the typical scope of the customer

---

40. How can an organization take advantage of tiered pricing across multiple business units within an organization?

AWS Organizations service control policies (SCPs)
All Upfront Reserved Instances
Cost Explorer utilization reports
AWS Organizations consolidated billing

---

**Answer:**

To take advantage of tiered pricing across multiple business units within an organization, the appropriate approach would be to use **AWS Organizations consolidated billing**.

Consolidated billing in AWS Organizations allows organizations to combine the usage from multiple AWS accounts and benefit from volume discounts, such as volume-tiered pricing for certain services. By consolidating billing across multiple accounts under a single payer account, organizations can reach higher usage tiers more quickly, which can lead to lower per-unit pricing for various AWS services. This structure helps in optimizing costs by aggregating the usage across different business units or accounts within the organization.

---

41. A company needs to use third-party software for its workload on AWS.

Is there a feature or service of AWS that the company can use to purchase the software?

AWS License Manager
AWS Resource Access Manager
AWS Marketplace
AWS Managed Service

---

**Answer:**

Yes, the feature or service of AWS that the company can use to purchase third-party software for its workload is the **AWS Marketplace**.

The AWS Marketplace is an online store that offers a wide range of third-party software solutions, products, and services that are ready to use on the AWS platform. It allows customers to discover, purchase, deploy, and manage software from various vendors, enabling easy procurement and deployment of third-party software directly within their AWS environment.

---

42. A company needs a consistent and dedicated connection between AWS resources and an on-premise system.

Which AWS service can fulﬁl this requirement?

Amazon Connect
AWS DataSync
AWS Direct Connect
AWS Managed VPN

---

**Answer:**

For a consistent and dedicated connection between AWS resources and an on-premise system, the suitable AWS service is **AWS Direct Connect**.

AWS Direct Connect establishes a dedicated network connection between an on-premises location (data center, office, etc.) and AWS, bypassing the public internet. This dedicated connection can help in achieving consistent network performance, reduced latency, and increased security for accessing AWS resources, creating a more reliable and predictable network link between the on-premises infrastructure and AWS.

---

43. A Cloud Practitioner is re-architecting a monolithic application. Which design principles for cloud architecture do AWS recommend? (Select TWO.)

Use self-managed servers
Rely on individual components
Design for scalability
Implement manual scalability
Implement loose coupling

---

**Answer:**

When re-architecting a monolithic application, AWS recommends the following design principles for cloud architecture:

- **Design for scalability**: This principle involves designing systems that can efficiently scale in response to changing demands or workloads. It involves using scalable services and architectures to handle varying levels of traffic or load without sacrificing performance.
- **Implement loose coupling**: This principle involves designing components that are independent and loosely connected, reducing dependencies between different parts of the system. It allows for flexibility, easier maintenance, and scalability of individual components without affecting the entire system.

Relying on individual components, implementing manual scalability, and using self-managed servers are not recommended design principles for modern cloud architecture when re-architecting monolithic applications.

---

44. A company needs an AWS service that can continuously monitor the company's AWS account. If there are any changes to the architecture, members of the team must be contacted.

Which service will meet these requirements?

Amazon GuardDuty
Amazon Macie
AWS Config
AWS Trusted Advisor

---

**Answer:**

The AWS service that can continuously monitor the company's AWS account for any changes to the architecture and notify team members is **AWS Config**.

AWS Config provides continuous monitoring and assessment of AWS resource configurations, recording changes and maintaining a history of configurations over time. It can detect changes to the architecture and notify designated team members through Amazon SNS (Simple Notification Service), enabling them to review and take action if necessary in response to any modifications made within the AWS environment.

---

45. Which cloud architecture design principle is supported by deploying workloads across multiple Availability Zones?

Design for failure
Design for agility
Automate infrastructure
Enable elasticity

---

**Answer:**

Deploying workloads across multiple Availability Zones supports the cloud architecture design principle of **"Design for failure."**

Designing for failure involves creating systems that can handle failures and disruptions without causing a complete outage. Deploying across multiple Availability Zones increases fault tolerance by ensuring that if one Availability Zone experiences an outage or failure, the workload can continue operating in another Zone, thereby minimizing the impact of failures and enhancing the overall resilience of the system.

---

46. Which Amazon EC2 pricing model should be avoided if a workload cannot accept interruption if capacity becomes temporarily unavailable?

Standard Reserved Instances
Convertible Reserved Instances
On-Demand Instances
Spot Instances

---

**Answer:**

If a workload cannot accept interruption or temporary unavailability of capacity, the Amazon EC2 pricing model that should be avoided is **Spot Instances**.

Spot Instances offer spare EC2 capacity at significantly reduced prices compared to On-Demand instances. However, they can be interrupted by AWS with short notice if the current Spot price exceeds the bid price specified by the user. This makes Spot Instances unsuitable for workloads that require continuous and uninterrupted availability without the risk of sudden termination.

---

47. According to the AWS shared responsibility model, which task is the customer's responsibility?

Maintaining the infrastructure needed to run Amazon DynamoDB
Updating the operating system of AWS Lambda instances
Maintaining Amazon API Gateway infrastructure
Updating the guest operating system on Amazon EC2 instances

---

**Answer:**

According to the AWS shared responsibility model:

**Updating the guest operating system on Amazon EC2 instances** is the customer's responsibility.

Customers are responsible for managing and updating the guest operating systems, including security patches and updates, on Amazon EC2 instances. AWS manages the underlying infrastructure and hypervisor, but customers are accountable for the configuration and maintenance of the operating system running on their EC2 instances.

---

48. Which benefit of AWS enables companies to replace upfront fixed expenses with variable expenses when using on-demand technology services?

Economies of scale
Global reach
High availability
Pay-as-you-go pricing

---

**Answer:**

The benefit of AWS that enables companies to replace upfront fixed expenses with variable expenses when using on-demand technology services is **Pay-as-you-go pricing**.

Pay-as-you-go pricing within AWS allows companies to pay only for the resources they consume without any upfront costs or long-term commitments. This model enables flexibility and cost-effectiveness by shifting from traditional fixed expenses to variable expenses based on actual usage of AWS services.

---

49. AWS are able to continue to reduce their pricing due to:

The AWS global infrastructure
Reserved instance pricing
Economies of scale
Pay-as-you go pricing

---

**Answer:**

AWS is able to continue reducing their pricing due to **Economies of scale**.

Economies of scale refer to the cost advantages that AWS gains as it expands its operations and serves a larger customer base. As AWS grows and increases its infrastructure, it benefits from cost efficiencies associated with operating at a larger scale. This allows AWS to optimize its costs and, in many cases, pass on those savings to customers in the form of reduced pricing for its services. While features like the global infrastructure, reserved instances, and pay-as-you-go pricing contribute to cost optimization, economies of scale are a major driving force behind AWS's ability to continually reduce pricing.

---

50. Which combination of steps will enable multi-factor authentication (MFA) on an AWS account? (Select TWO.)

Activate the MFA device in the IAM console or by using the AWS CLI
Acquire an MFA-compatible device
Activate AWS Shield on an MFA-compatible device
Contact AWS Support to initiate MFA activation
Activate the MFA device by using Amazon GuardDuty

---

**Answer:**

To enable multi-factor authentication (MFA) on an AWS account, the following steps should be taken:

- **Acquire an MFA-compatible device**: This involves obtaining a hardware or software-based MFA device that is compatible with the AWS MFA service.
- **Activate the MFA device in the IAM console or by using the AWS CLI**: Once you have the MFA-compatible device, you need to activate it in the AWS Identity and Access Management (IAM) console or through the AWS Command Line Interface (CLI). This process links the device to the AWS account for MFA authentication.

Activating AWS Shield or Amazon GuardDuty does not directly enable MFA. Contacting AWS Support is not typically required to enable MFA.

---

51. Which AWS service helps customers meet corporate, contractual, and regulatory compliance requirements for data security by using dedicated hardware appliances within the AWS Cloud?

AWS Secrets Manager
AWS CloudHSM
AWS Directory Service
AWS Key Management Service (AWS KMS)

---

**Answer:**

The AWS service that helps customers meet corporate, contractual, and regulatory compliance requirements for data security by using dedicated hardware appliances within the AWS Cloud is **AWS CloudHSM** (Hardware Security Module).

AWS CloudHSM provides dedicated Hardware Security Modules (HSMs) that allow customers to generate and use their encryption keys in a Hardware Security Module, which is a tamper-resistant hardware appliance designed to securely store cryptographic key material. This service enables customers to fulfill various compliance requirements for data security, ensuring the protection of sensitive information within the AWS Cloud.

---

52. A Cloud practitioner wants to know if there are services which can protect from DDoS (Distributed Denial of Service) attacks directed at AWS services.

Which AWS service or tool will provide this protection?

Network access control list (ACL)
Amazon GuardDuty
Security group
AWS Shield

---

**Answer:**

The AWS service that provides protection against DDoS (Distributed Denial of Service) attacks directed at AWS services is **AWS Shield**.

AWS Shield is a managed Distributed Denial of Service (DDoS) protection service that safeguards web applications running on AWS against the most common and frequently occurring DDoS attacks. AWS Shield Standard is automatically included at no additional charge with all AWS accounts, providing protection against common DDoS attacks. AWS Shield Advanced offers additional protection against more sophisticated attacks and includes enhanced monitoring and reporting features.

---

53. What is the function of Amazon EC2 Auto Scaling?

Automatically updates the EC2 pricing model, based on demand
Scales the size of EC2 instances up or down automatically, based on demand
Automatically modifies the network throughput of EC2 instances, based on demand
Scales the number of EC2 instances in or out automatically, based on demand

---

**Answer:**

The function of Amazon EC2 Auto Scaling is to **scale the number of EC2 instances in or out automatically, based on demand**.

Amazon EC2 Auto Scaling enables users to automatically adjust the number of EC2 instances in a group, known as an Auto Scaling Group, to match demand or predefined conditions. It helps maintain application availability and performance by automatically scaling the number of instances up or down based on metrics, such as CPU utilization, network traffic, or other custom-defined metrics. This scaling capability allows for the seamless handling of fluctuating workloads while optimizing costs by adjusting resources based on actual demand.

---

54. Which AWS service can be used to perform data extract, transform, and load (ETL) operations so you can prepare data for analytics?

Amazon QuickSight
AWS Glue
Amazon S3 Select
Amazon Athena

---

**Answer:**

The AWS service used to perform data extract, transform, and load (ETL) operations for preparing data for analytics is **AWS Glue**.

AWS Glue is a fully managed extract, transform, and load (ETL) service that makes it simple and cost-effective to prepare and load data for analytics. It helps in discovering, cataloging, cleaning, and transforming data from various sources for analytics purposes, making it easier to query and analyze data in Amazon S3, Redshift, and other data stores.

---

55. Which of the following best describes an Availability Zone in the AWS Cloud?

One or more edge locations based around the world
One or more physical data centers
A subnet for deploying resources into
A completely isolated geographic location

---

**Answer:**

An Availability Zone in the AWS Cloud can best be described as **one or more physical data centers**.

An Availability Zone (AZ) is a distinct location within a geographic region that contains one or more data centers, each equipped with redundant power, networking, and connectivity. AZs are designed to be isolated from failures in other AZs while being interconnected through low-latency links. Deploying resources across multiple AZs helps ensure high availability and fault tolerance for applications and services running in the AWS Cloud.

---

56. Which Amazon EC2 tool acts as a virtual firewall to control inbound and outbound traffic to an EC2 instance?

Security Group
AWS WAF
Network access control list (ACL)
AWS Shield

---

**Answer:**

The Amazon EC2 tool that acts as a virtual firewall to control both inbound and outbound traffic to an EC2 instance is called a **Security Group**.

Security Groups are associated with EC2 instances and operate at the instance level. They act as virtual firewalls, controlling the traffic by allowing or denying access based on rules defined for inbound and outbound traffic to and from the associated EC2 instances. Security Groups help manage access by specifying protocols, ports, and IP address ranges to control the flow of traffic.

---

57. Which of the following statements are security principles within the AWS Well-Architected Framework? (Select TWO.)

Analyze and attribute expenditures
Protect data in transit and at rest
Perform operations as code
Deploy globally in minute
Monitor, alert, and audit actions and changes to AWS resources

---

**Answer:**

The security principles within the AWS Well-Architected Framework are:

- **Protect data in transit and at rest**: This principle focuses on securing data both when it's in motion (transit) and when it's stored (at rest) by using encryption, secure protocols, and implementing security measures to safeguard sensitive information.
- **Monitor, alert, and audit actions and changes to AWS resources**: This principle emphasizes the importance of monitoring, alerting, and auditing to maintain visibility and control over actions and changes made to AWS resources, enabling timely detection and response to security-related events.

Analyzing and attributing expenditures, performing operations as code, and deploying globally in minutes are not security principles within the AWS Well-Architected Framework.

---

58. Which of the following are valid best practices for using the AWS Identity and Access Management (IAM) service? (Select TWO.)

Create individual IAM users
Embed access keys in application code
Grant maximum privileges to IAM users
Use groups to assign permissions to IAM users
Use inline policies instead of customer managed policies

---

**Answer:**

Valid best practices for using the AWS Identity and Access Management (IAM) service include:

- **Create individual IAM users**: It is a recommended practice to create separate IAM user accounts for individuals accessing AWS resources. This allows for better management, tracking, and control over permissions and actions taken by each user.
- **Use groups to assign permissions to IAM users**: By organizing users into groups with similar roles or permissions, you can efficiently manage permissions by assigning policies to groups rather than to individual users, making it easier to maintain and modify access across multiple users.

Embedding access keys in application code and granting maximum privileges to IAM users are not recommended practices as they can pose security risks and may lead to excessive permissions. Additionally, using inline policies instead of customer-managed policies can result in more complex and harder-to-manage permission structures.

---

59. A company plan to move the application development to AWS. Which benefits can they achieve when developing and running applications in the AWS Cloud compared to on-premises? (Select TWO.)

AWS makes it easy to implement high availability
AWS will fully manage the entire application
AWS can accommodate large changes in application demand
AWS takes care of application security patching
AWS automatically replicates all data globally

---

**Answer:**

When developing and running applications in the AWS Cloud compared to on-premises, the benefits that can be achieved are:

- **AWS makes it easy to implement high availability**: AWS offers various services and features that facilitate the implementation of high availability architectures, allowing applications to run across multiple Availability Zones or regions for increased fault tolerance and resilience.
- **AWS can accommodate large changes in application demand**: AWS provides the capability to easily scale resources up or down based on demand, ensuring that applications can dynamically handle fluctuations in traffic or workload without manual intervention.

AWS does not fully manage the entire application; rather, it provides infrastructure and services for running applications. Also, while AWS offers services to enhance security, application security patching and data replication globally typically require configuration and management by the user.

---

60. A company requires a dashboard for reporting when using a business intelligence solution. Which AWS service can a Cloud Practitioner use?

Which AWS service can be used?

Amazon Athena
Amazon Redshift
Amazon Kinesis
Amazon QuickSight

---

**Answer:**

For creating a dashboard for reporting when using a business intelligence solution in AWS, the suitable AWS service that a Cloud Practitioner can use is **Amazon QuickSight**.

Amazon QuickSight is a fully managed business intelligence (BI) service provided by AWS. It allows users to create interactive dashboards and perform ad-hoc analysis on various data sources. QuickSight enables the creation of visually appealing dashboards and reports to gain insights from the data stored in various AWS services and external sources.

---

61. Which of the statements below is correct in relation to Consolidated Billing? (Select TWO.)

You are charged a fee per user
You can combine usage and share volume pricing discounts
You pay a fee per linked account
You receive one bill per AWS account
You receive a single bill for multiple accounts

---

**Answer:**

In relation to Consolidated Billing:

- **You can combine usage and share volume pricing discounts**: Consolidated Billing allows combining the usage across multiple linked accounts to reach volume discounts, optimizing costs by aggregating usage for pricing benefits.
- **You receive a single bill for multiple accounts**: With Consolidated Billing, you receive a unified bill that consolidates the charges for all linked AWS accounts, making it easier to manage and track expenses across the accounts.

Consolidated Billing does not charge a fee per user or a fee per linked account; rather, it streamlines billing by consolidating usage charges into a single bill for multiple accounts.

---

62. What should a Cloud Practitioner ensure when designing a highly available architecture on AWS?

There are enough servers to run at peak load available at all times
Servers have low-latency and high throughput network connectivity
A single monolithic application component handles all operations
The failure of a single component should not affect the application

---

**Answer:**

When designing a highly available architecture on AWS, a Cloud Practitioner should ensure that:

**The failure of a single component should not affect the application.**

Designing for high availability involves implementing fault-tolerant architectures where individual components or services are resilient to failures. Redundancy, load balancing, fault isolation, and using multiple Availability Zones are some strategies used to ensure that if one component fails, the overall system continues to function without significant impact or downtime.

The other options listed are not ideal practices for achieving high availability:

- Having enough servers at peak load doesn’t ensure high availability; it's more about the fault tolerance of the architecture.
- Low-latency and high throughput network connectivity are important but don’t solely guarantee high availability.
- Relying on a single monolithic application component can lead to a single point of failure, decreasing rather than increasing availability.

---

63. Which of the following should be used to improve the security of access to the AWS Management Console? (Select TWO.)

AWS Multi-Factor Authentication (AWS MFA)
Strong password policies
Security group rules
AWS Certiﬁcate Manager
AWS Secrets Manager

---

**Answer:**

To improve the security of access to the AWS Management Console, the following measures should be considered:

- **AWS Multi-Factor Authentication (AWS MFA)**: Enabling multi-factor authentication adds an extra layer of security to the login process, requiring users to provide a second authentication factor along with their password, such as a code from a mobile device, enhancing account security.
- **Strong password policies**: Enforcing strong password policies, including complex passwords, regular password rotations, and avoiding the reuse of passwords, helps prevent unauthorized access to accounts by making it harder for attackers to guess or crack passwords.

Security group rules, AWS Certificate Manager, and AWS Secrets Manager are not directly related to improving the security of access to the AWS Management Console. Security group rules apply to network access controls for AWS resources, while AWS Certificate Manager and AWS Secrets Manager are used for managing SSL/TLS certificates and secrets, respectively, but they do not directly impact console access security.

---

64. Which AWS service can act as a hybrid storage solution to connect on-premises workloads with the AWS cloud?

AWS Direct Connect
Amazon Connect
AWS Storage Gateway
AWS Backup

---

**Answer:**

The AWS service that can act as a hybrid storage solution to connect on-premises workloads with the AWS cloud is **AWS Storage Gateway**.

AWS Storage Gateway enables on-premises applications to seamlessly use AWS Cloud storage by providing a hybrid cloud storage solution. It connects on-premises environments to AWS storage services such as Amazon S3, Amazon Glacier, and Amazon EBS. This allows data to be stored in the AWS Cloud while still being accessible from on-premises applications and systems.

---

65. A Cloud Practitioner requires a simple method to identify if unrestricted access to resources has been allowed by security groups. Which service can the Cloud Practitioner use?

AWS CloudTrail
Amazon CloudWatch
VPC Flow Logs
AWS Trusted Advisor

---

**Answer:**

To identify if unrestricted access to resources has been allowed by security groups, the Cloud Practitioner can use **AWS Trusted Advisor**.

AWS Trusted Advisor includes a "Security Groups - Unrestricted Access" check that identifies security groups with overly permissive rules that allow unrestricted access to specific resources. This check helps in identifying potential security risks associated with security group configurations by highlighting rules that might grant access more broadly than necessary.

---
