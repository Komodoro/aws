---
sectionid: Dump102022023
sectionclass: h2
parent-id: Questions
title: Dump 1 - 02-02-2023
number: 3100
---

### Question 1/71

* A company needs to deploy an Amazon EC2 instance and attach a storage mount for the operating system and application files. Which AWS service will meet these requirements?

A. Amazon Elastic File System (Amazon EFS)

B. Amazon Elastic Block Store (Amazon EBS)

C. AWS Backup

D. Amazon S3

**Correct Answer: D**

### Question 2/71

* Which AWS service provides alerts when an AWS event may impact a company's AWS resources?

A. AWS Infrastructure Event Management

B. AWS Trusted Advisor

C. AWS Personal Health Dashboard

D. AWS Service Health Dashboard

**Correct Answer: C**

### Question 3/71

* A company wants to improve the overall availability and performance of its applications that are hosted on AWS.
Which AWS service should the company use?

A. AWS Global Accelerator

B. Amazon Lightsail

C. Amazon Connect

D. AWS Storage Gateway

**Correct Answer: A**

### Question 4/71

* A company runs a web application on Amazon EC2 instances. The application must run constantly and is expected to run indefinitely without interruption.
Which EC2 instance purchasing options will meet these requirements MOST cost-effectively? (Select TWO.)

A. On-Demand Instances

B. Spot Instances.

C. Reserved Instances

D. Savings Plans

E. Dedicated Hosts

**Correct Answer: C,D**

Amazon EC2 provides the following purchasing options to enable you to optimize your costs based on your needs:
* On-Demand Instances - Pay, by the second, for the instances that you launch.
* Savings Plans - Reduce your Amazon EC2 costs by making a commitment to a consistent amount of usage, in USD per hour, for a term of 1 or 3 years.
* Reserved Instances - Reduce your Amazon EC2 costs by making a commitment to a consistent instance configuration, including instance type and Region, for a term of 1 or 3 years.
* Spot Instances - Request unused EC2 instances, which can reduce your Amazon EC2 costs significantly.
* Dedicated Hosts - Pay for a physical host that is fully dedicated to running your instances, and bring your existing per-socket, per-core, or per-VM software licenses to reduce costs.
* Dedicated Instances - Pay, by the hour, for instances that run on single-tenant hardware.
* Capacity Reservations - Reserve capacity for your EC2 instances in a specific Availability Zone for any duration.


If you require a capacity reservation, purchase Reserved Instances or Capacity Reservations for a specific Availability Zone.

Spot Instances are a cost-effective choice if you can be flexible about when your applications run and if they can be interrupted. 

Dedicated Hosts or Dedicated Instances can help you address compliance requirements and reduce costs by using your existing server-bound software licenses.


### Question 5/71

* A company that is migrating to the AWS Cloud wants to reduce the operational costs of running its databases. Which combination of actions should the company take to achieve this goal (Select TWO.)

A. Deploy resources across multiple Availability Zones.

B. Activate Amazon DynamoDB Accelerator (DAX)

C. Use the AWS global infrastructure to benefit from economies of scale

D. Decrease operational tasks by using AWS managed services.

E. Automate changes and responses to events.

**Correct Answer: D,E**

### Question 6/71

* A company needs to transfer 60 TB of data to the AWS Cloud in a secure manner.
Which of the following should the company use to meet these requirements?

A. AWS Snowball Edge device

B. Amazon Elastic Block Store (Amazon EBS)

C. Amazon Elastic File System (Amazon EFS)

D. Amazon S3

**Correct Answer: A**
* https://aws.amazon.com/blogs/storage/migrating-hundreds-of-tb-of-data-to-amazon-s3-with-aws-datasync/


### Question 7/71

* Which AWS service provides managed DDoS protection?

A. Amazon Inspector

B. Amazon GuardDuty

C. AWS Firewall Manager

D. AWS Shield

**Correct Answer: D**


### Question 8/71

* A company wants to offer direct phone and chat channels for customer service. The company needs a pay-as-you-go solution that remote customer service agents can use to create and manage voice and chat contact flows.
Which AWS service will meet these requirements?

A. Amazon Connect

B. AWS Direct Connect

C. Amazon Cognito

D. Amazon EventBridge (Amazon CloudWatch Events)

**Correct Answer: A**

### Question 9/71

* Which AWS service provides an isolated virtual network to connect AWS services and resources?

A. Amazon EC2

B. Amazon DynamoDB

C. Amazon Lightsail

D. Amazon VPC

**Correct Answer: D**

* Amazon Virtual Private Cloud (Amazon VPC) enables you to launch AWS resources into a virtual network that you've defined. This virtual network closely resembles a traditional network that you'd operate in your own data center, with the benefits of using the scalable infrastructure of AWS.


### Question 10/71

* A company stores several terabytes of data in an Amazon S3 bucket. The company needs to query the data by using standard SQL and does not want to set up infrastructure. Which AWS service should the company use to meet these. requirements?

A. Amazon Athena

B. Amazon EC2

C. Amazon Redshift

D. Amazon RDS

**Correct Answer: A**


### Question 11/71

* Which solution provides a fast, automated and repeatable method of deploying AWS Cloud infrastructure to multiple AWS Regions?

A. Use AWS CodeStar to set up a continuous delivery toolchain for automated deployment

B. Create and use an AWS CloudFormation template

C. Use AWS Systems Manager to automate management tasks such as creating Amazon EC2 Amazon Machine images (AMIS) and applying patches

D. Create and launch an Amazon EC2 Amazon Machine Image (AMI) containing the source code with butt-m deployment hooks lo launch other AWS services

**Correct Answer: B**

### Question 12/71

* Which of the following are AWS best practice recommendations for the use of AWS Identity and Access Management (IAM)? (Select TWO.)

A. Use the AWS account root user for daily access.

B. Use access keys and secret access keys on Amazon EC2.

C. Rotate credentials on a regular basis.

D. Create a shared set of access keys for system administrators.

E. Configure multi-factor authentication (MFA).

**Correct Answer: C,E**
* If you do have an access key for your AWS account root user, delete it. If you must keep it, rotate (change) the access key regularly. To delete or rotate your root user access keys, go to the My Security Credentials page in the AWS Management Console and sign in with your account's email address and password. You can manage your access keys in the Access keys section. For more information about rotating access keys, see Rotating access keys.


### Question 13/71

* A company implements an Amazon EC2 Auto Scaling policy along with an Application Load Balancer to automatically recover unhealthy applications that run on Amazon EC2 instances.
Which pillar of the AWS Well-Architected Framework does this action cover?

A. Performance efficiency

B. Security

C. Reliability

D. Operational excellence

**Correct Answer: C**


### Question 14/71

* Which approach will enhance a user's security on AWS?

A. Create a hybrid architecture by using AWS Direct Connect.

B. Use Multi-AZ deployments with Amazon RDS.

C. Monitor application-specific information with AWS X-Ray.

D. Encrypt data by using AWS Key Management Service (AWS KMS).

**Correct Answer: D**

### Question 15/71
* A company needs to report on events that involve the specific AWS services that the company uses.
Which AWS service or resource can the company use with Amazon CloudWatch to meet this requirement?

A. AWS Trusted Advisor

B. AWS Cloud Trail logs

C. Amazon Inspector

D. AWS Personal Health Dashboard

**Correct Answer: D**

### Question 16/71

* Which service enables customers to audit API calls in their AWS accounts?

A. AWS CloudTrail

B. AWS Trusted Advisor

C. Amazon Inspector

D. AWS X-Ray

**Correct Answer: A**
* AWS Audit Manager is integrated with AWS CloudTrail, a service that provides a record of actions taken by a user, role, or an AWS service in Audit Manager. CloudTrail captures all API calls for Audit Manager as events.

### Question 17/71
* A company is moving its on-premises NoSQL database to the AWS Cloud Which AWS service should the company use for the NoSQL database?

A. Amazon Redshift

B. Amazon Quantum Ledger Database (Amazon QLDB)

C. Amazon DynamoDB

D. Amazon RDS for MySQL

**Correct Answer: C**


### Question 18/71
* A company is undergoing a security audit. The audit includes security validation and compliance validation of the AWS infrastructure and services that the company uses. The auditor needs to locate compliance-related information and must download AWS security and compliance documents. These documents include the System and Organization Control (SOC) reports.
Which AWS service or group can provide these documents?

A. AWS Config

B. AWS Support

C. AWS Abuse team

D. AWS Artifact

**Correct Answer: D**


### Question 19/71

* Which Reserved Instance (Rl) provides the HIGHEST average cost savings compared to an On-Demand Instance?

A. 1-year. No Upfront. Standard Rl

B. 3-year. No Upfront. Convertible Rl

C. 1-year. All Upfront. Convertible Rl

D. 3-year. All Upfront, Standard Rl

**Correct Answer: D**

### Question 20/71

* A company wants a cost-effective option when running its applications in an Amazon EC2 instance for short time periods. The applications can be interrupted. Which EC2 instance type will meet these requirements?

A. Spot Instances

B. On-Demand Instances

C. Reserved Instances

D. Dedicated Instances

**Correct Answer: A**
* Spot Instances - Spot Instances are the most cost-effective choice if you are flexible about when your applications run and if your applications can be interrupted.

### Question 21/71

* Which task is the responsibility of the customer according to the AWS snared responsibility model?

A. Patch the Amazon DynamoDB operating system

B. Protect the hardware that runs AWS services

C. Secure Amazon CloudFront edge locations by allowing physical access according to the principle of least privilege

D. Use AWS Identity and Access Management (IAM) according to the principle of least privilege

**Correct Answer: D**

### Question 22/71
* A company plans to create a data lake that uses Amazon S3. Which factor will have the MOST effect on cost?

A. The addition of S3 bucket policies

B. The selection of S3 storage tiers

C. S3 ingest fees for each request

D. Charges to transfer existing data into Amazon S3

**Correct Answer: D**

### Question 23/71
* What is a benefit of using AWS serverless computing?

A. Application deployment and management are not required.

B. Application security will be fully managed by AWS.

C. Monitoring and logging are not needed.

D. Management of infrastructure is offloaded to AWS.

**Correct Answer: D**

* Serverless computing allows you to build and run applications and services without thinking about servers. With serverless computing, your application still runs on servers, but all the server management is done by AWS.

### Question 24/71
* A company runs applications that process credit card information. Auditors have asked if the AWS environment has changed since the previous audit. If the AWS environment has changed, the auditors want to know how it has changed. Which AWS services can provide this information? (Select TWO.)

A. AWS Artifact

B. AWS Trusted Advisor

C. AWS Config

D. AWS Cloud Trail

E. AWS Identity and Access Management (IAM)

**Correct Answer: C,D**

* AWS Artifact is your go-to, central resource for compliance-related information that matters to you. It provides on-demand access to AWS' security and compliance reports and select online agreements.
* AWS Trusted Advisor provides recommendations that help you follow AWS best practices. Trusted Advisor evaluates your account by using checks. These checks identify ways to optimize your AWS infrastructure, improve security and performance, reduce costs, and monitor service quotas.
* AWS Config is a service that enables you to assess, audit, and evaluate the configurations of your AWS resources. Config continuously monitors and records your AWS resource configurations and allows you to automate the evaluation of recorded configurations against desired configurations.
* AWS CloudTrail enables auditing, security monitoring, and operational troubleshooting by tracking user activity and API usage. CloudTrail logs, continuously monitors, and retains account activity related to actions across your AWS infrastructure, giving you control over storage, analysis, and remediation actions.
* AWS Identity and Access Management (IAM) provides fine-grained access control across all of AWS. With IAM, you can specify who can access which services and resources, and under which conditions. With IAM policies, you manage permissions to your workforce and systems to ensure least-privilege permissions.


### Question 25/71
* A company recently mutated to AWS and wants to enable intelligent threat protection and continuous monitoring across all of its AWS accounts.
Which AWS service should the company use lo achieve this goal?

A. Amazon Detective

B. Amazon Macie

C. AWS Shield

D. Amazon GuardDuty

**Correct Answer: D**


