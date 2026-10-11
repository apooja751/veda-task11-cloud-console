# Veda Technology Cloud Computing Internship — Task 11
## Explore a Cloud Provider Console

**Internship Track:** Cloud Computing  
**Task Number:** 11  
**Task Title:** Explore a Cloud Provider Console  
**Cloud Provider:** Amazon Web Services (AWS)  
**Region Explored:** Asia Pacific (Mumbai) — `ap-south-1`  
**Status:** Console exploration and documentation completed

---

## 1. Aim

To explore the AWS Management Console, understand its basic layout, and identify commonly used cloud services for computing, storage, networking, databases, security, monitoring, content delivery, messaging, and backup.

## 2. Objectives

- Understand the basic layout and navigation of the AWS Management Console.
- Explore at least 10 AWS cloud services.
- Identify the purpose and common use cases of each service.
- Compare compute, storage, database, and networking services.
- Understand the importance of AWS Regions and Availability Zones.
- Document the exploration using screenshots.
- Explore cloud services while avoiding unnecessary resource creation and costs.

## 3. Tools and Technologies

- Amazon Web Services (AWS)
- AWS Management Console
- AWS cloud service dashboards
- Windows operating system
- GitHub for project documentation and version control

## 4. Introduction to Cloud Computing

Cloud computing is the delivery of computing resources such as servers, storage, databases, networking, and software over the internet. It allows users to access resources on demand without purchasing and maintaining all the underlying physical infrastructure.

AWS is a cloud computing platform that provides services for hosting applications, storing data, managing networks, running databases, monitoring workloads, and protecting resources.

The AWS Management Console provides a graphical interface for accessing and managing AWS services.

## 5. AWS Management Console Overview

The AWS Management Console was explored to understand its layout and navigation.

**The following components were observed:**

- **Search bar:** Used to search for AWS services.
- **Recently visited services:** Provides quick access to frequently used services.
- **AWS Region selector:** Allows users to select a Region for regional services.
- **Service dashboards:** Display service features, navigation, and resource information.
- **Billing and cost information:** Helps users review usage and estimated costs.
- **Service health:** Provides information about AWS service status and relevant events.

The Mumbai Region (`ap-south-1`) was used for exploring regional services. IAM and CloudFront were explored through their global interfaces.

## 6. AWS Services Explored

The following 10 AWS services were explored through their respective console pages.

| No.|    AWS Service    |          Category           |                               Purpose                                                                |
|----|-------------------|-----------------------------|------------------------------------------------------------------------------------------------------|
| 1  | Amazon EC2        | Compute                     | Provides virtual servers for hosting websites, applications, and computing workloads.                |
| 2  | Amazon S3         | Storage                     | Stores and retrieves objects such as files, images, documents, and backups.                          |
| 3  | AWS IAM           | Security and Identity       | Manages users, roles, policies, and permissions for accessing AWS resources.                         |
| 4  | Amazon VPC        | Networking                  | Provides logically isolated virtual networks, subnets, route tables, and network controls.           |
| 5  | Amazon RDS        | Database                    | Simplifies the setup and management of relational databases such as MySQL and PostgreSQL.            |
| 6  | Amazon CloudWatch | Monitoring                  | Monitors AWS resources and applications using metrics, logs, alarms, and dashboards.                 |
| 7  | AWS Lambda        | Serverless Compute          | Runs code in response to events without requiring users to manage servers.                           |
| 8  | Amazon CloudFront | Content Delivery            | Delivers content through a global network of edge locations to improve content delivery performance. |
| 9  | Amazon SNS        | Messaging and Notifications | Distributes messages and sends notifications to subscribers through supported endpoints.             |
| 10 | AWS Backup        | Backup and Recovery         | Centralizes and automates backup management for supported AWS services.                              |

## 7. Comparison of Compute, Storage, Database, and Networking Services

### 7.1 Compute Services

|        Feature            |                          Amazon EC2                         |                             AWS Lambda                           |
|---------------------------|-------------------------------------------------------------|------------------------------------------------------------------|
| Service type              | Virtual server computing                                    | Serverless computing                                             |
| Infrastructure management | Users manage the operating system and server configuration. | AWS manages the underlying server infrastructure.                |
| Execution                 | Runs applications on provisioned instances.                 | Runs code in response to events or requests.                     |
| Common use case           | Hosting websites and long-running applications.             | Event processing, automation, and lightweight application logic. |

**Comparison:** EC2 provides greater control over virtual servers, while Lambda is suitable for event-driven workloads without direct server management.

### 7.2 Storage Services

|     Feature       |                               Amazon S3                                  |                         AWS Backup                                        |
|-------------------|--------- ----------------------------------------------------------------|---------------------------------------------------------------------------|
| Primary purpose   | Object storage                                                           | Backup and recovery management                                            |
| Data organization | Objects stored in buckets                                                | Backup plans, recovery points, and backup vaults                          |
| Common use case   | Storing documents, images, application files, and static website assets. | Managing backup schedules and recovery workflows for supported resources. |

**Comparison:** S3 stores objects, whereas AWS Backup helps manage the protection and recovery of supported AWS resources.

### 7.3 Database Services

|      Feature      |                          Amazon RDS                              |
|-------------------|------------------------------------------------------------------|
| Database type     | Managed relational database service                              |
| Supported engines | Includes MySQL, PostgreSQL, MariaDB, and other supported engines |
| Management        | AWS manages many routine database administration tasks.          |
| Common use case   | Applications that require a managed relational database.         |

**Comparison:** Amazon RDS reduces the operational effort required to provision, maintain, and manage relational database infrastructure.

### 7.4 Networking Services

|     Feature     |                        Amazon VPC                      |                          Amazon CloudFront                                   |
|-----------------|--------------------------------------------------------|------------------------------------------------------------------------------|
| Primary purpose | Virtual network configuration                          | Content delivery                                                             |
| Main components | Subnets, route tables, gateways, and security controls | Distributions, origins, caching, and edge locations                          |
| Common use case | Connecting and isolating cloud resources securely.     | Delivering website content and other supported content efficiently to users. |

**Comparison:** VPC provides network isolation and traffic routing, while CloudFront improves content delivery through a distributed edge network.

## 8. Screenshot Documentation

Screenshots were captured during the exploration of the AWS Management Console and individual services.

Store the screenshots in the `screenshots/` directory in this repository.

| No. |        Screenshot Filename       |               Description            |
|-----|----------------------------------|--------------------------------------|
| 1   | `01_AWS_Console_Home.png`        | AWS Management Console home page     |
| 2   | `02_AWS_EC2_Dashboard.png`       | Amazon EC2 console                   |
| 3   | `03_AWS_S3_Console.png`          | Amazon S3 console                    |
| 4   | `04_AWS_IAM_Dashboard.png`       | AWS IAM dashboard                    |
| 5   | `05_AWS_VPC_Dashboard.png`       | Amazon VPC dashboard                 |
| 6   | `06_AWS_RDS_Dashboard.png`       | Amazon RDS dashboard                 |
| 7   | `07_AWS_CloudWatch_Dashboard.png`| Amazon CloudWatch overview           |
| 8   | `08_AWS_Lambda_Console.png`      | AWS Lambda console                   |
| 9   | `09_AWS_CloudFront_Console.png`  | Amazon CloudFront distributions page |
| 10  | `10_AWS_SNS_Console.png`         | Amazon SNS console                   |
| 11  | `11_AWS_Backup_Console.png`      | AWS Backup console                   |


## 9. Cost Awareness and Resource Safety

Cloud resource costs depend on the service, configuration, usage, Region, and applicable free-tier or promotional eligibility.

**The following precautions were followed:**

- The task focused on exploring service dashboards and documenting their purposes.
- No new cloud resources were created specifically for this exploration.
- Existing resources were not intentionally modified or deleted as part of this task.
- Pricing and free-tier eligibility should be checked before deploying any cloud resource.
- AWS Billing and Cost Management should be reviewed regularly to identify unexpected charges.

**Rollback note:** Since this task involved console exploration only and no new resources were created, no deployment rollback was required.

## 10. Interview Questions and Answers

### Q1. What is cloud computing?

Cloud computing is the on-demand delivery of computing resources such as servers, storage, databases, and networking over a network, typically with usage-based pricing.

### Q2. What are the major service categories in cloud computing?

Common categories include compute, storage, databases, networking, security and identity, monitoring, application integration, analytics, and backup and recovery.

Cloud service models are commonly classified as Infrastructure as a Service (IaaS), Platform as a Service (PaaS), and Software as a Service (SaaS).

### Q3. What is the difference between an AWS Region and an Availability Zone?

An AWS Region is a separate geographic area where AWS operates infrastructure. An Availability Zone is an isolated location within a Region, consisting of one or more data centres.

Deploying across multiple Availability Zones can improve application availability and resilience.

## 11. Findings and Observations

- The AWS Management Console provides a centralized interface for accessing cloud services.
- AWS services are organized into categories such as compute, storage, networking, databases, security, monitoring, messaging, and backup.
- Each service provides a dashboard or navigation interface suited to its purpose.
- IAM helps control access to AWS resources through identities and permissions.
- VPC supports network isolation and traffic management.
- CloudWatch provides monitoring capabilities for resources and applications.
- AWS cost awareness is important before creating resources or enabling additional service features.

## 12. Conclusion

The AWS Management Console was explored to understand its layout, navigation, and commonly used cloud services. Ten AWS services were identified and documented, and compute, storage, database, and networking services were compared according to their purposes and typical use cases.

The task improved familiarity with AWS cloud infrastructure services and highlighted the importance of security, monitoring, cost awareness, and resource management.

## 13. References

- AWS Management Console: https://console.aws.amazon.com/
- AWS Documentation: https://docs.aws.amazon.com/
- AWS Pricing: https://aws.amazon.com/pricing/
- AWS Free Tier: https://aws.amazon.com/free/

---

## Repository Structure

```text
veda-task11-cloud-console/
├── README.md
└── Screenshots/
    ├── 01_AWS_Console_Home.png
    ├── 02_AWS_EC2_Dashboard.png
    ├── 03_AWS_S3_Console.png
    ├── 04_AWS_IAM_Dashboard.png
    ├── 05_AWS_VPC_Dashboard.png
    ├── 06_AWS_RDS_Dashboard.png
    ├── 07_AWS_CloudWatch_Dashboard.png
    ├── 08_AWS_Lambda_Console.png
    ├── 09_AWS_CloudFront_Console.png
    ├── 10_AWS_SNS_Console.png
    └── 11_AWS_Backup_Console.png
```

