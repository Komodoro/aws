---
sectionid: Module5Quiz
sectionclass: h3
parent-id: Skillbuilder
title: Module 5 Quiz
number: 14350
---

Module 5 quiz

Test your knowledge of some of the key concepts from this module by answering the questions in this quiz.

After answering each question, review the detailed answer explanations and external links to reinforce your understanding of the concepts.

Which Amazon S3 storage classes are optimized for archival data? (Select TWO.)

Amazon S3 Standard

Amazon S3 Glacier Flexible Retrieval

Amazon S3 Intelligent-Tiering

Amazon S3 Standard-IA

    Amazon S3 Glacier Deep Archive


Incorrect

The correct two response options are:

    Amazon S3 Glacier Flexible Retrieval
    Amazon S3 Glacier Deep Archive

Objects stored in the Amazon S3 Glacier Flexible Retrieval storage class can be retrieved within a few minutes to a few hours. By comparison, objects that are stored in the Amazon S3 Glacier Deep Archive storage class can be retrieved within 12 hours.

 

The other response options are incorrect because:

    Amazon S3 Standard is a storage class that is ideal for frequently accessed data, not archival data.
    Amazon S3 Intelligent-Tiering monitors access patterns of objects and automatically moves them between the Amazon S3 Standard and Amazon S3 Standard-IA storage classes. It is not designed for archival data.
    Amazon S3 Standard-IA is ideal for data that is infrequently accessed but requires high availability when needed.

Learn more:

    Amazon S3 storage classes

Which statement or statements are TRUE about Amazon EBS volumes and Amazon EFS file systems?

EBS volumes store data within a single Availability Zone. Amazon EFS file systems store data across multiple Availability Zones.

EBS volumes store data across multiple Availability Zones. Amazon EFS file systems store data within a single Availability Zone.

EBS volumes and Amazon EFS file systems both store data within a single Availability Zone.

EBS volumes and Amazon EFS file systems both store data across multiple Availability Zones.

Incorrect

The correct response option is: EBS volumes store data within a single Availability Zone. Amazon EFS file systems store data across multiple Availability Zones.

 

An EBS volume must be located in the same Availability Zone as the Amazon EC2 instance to which it is attached.

 

Data in an Amazon EFS file system can be accessed concurrently from all the Availability Zones in the Region where the file system is located.


Learn more:

    Amazon EBS volumes
    Amazon EFS: How it works

You want to store data in an object storage service. Which AWS service is best for this type of storage?

Amazon Managed Blockchain

Amazon Elastic File System (Amazon EFS)

Amazon Elastic Block Store (Amazon EBS)

Amazon Simple Storage Service (Amazon S3)

Incorrect

The correct response option is Amazon Simple Storage Service (Amazon S3).

 

The other response options are incorrect because:

    Amazon Managed Blockchain is a service that you can use to create and manage blockchain networks with open-source frameworks. Blockchain is a distributed ledger system that lets multiple parties run transactions and share data without a central authority.
    Amazon Elastic File System (Amazon EFS) is a scalable file system used with AWS Cloud services and on-premises resources. It does not store data as object storage.
    Amazon Elastic Block Store (Amazon EBS) is a service that provides block-level storage volumes that you can use with Amazon EC2 instances.

Learn more:

    Amazon S3
    What is cloud object storage?

Which statement best describes Amazon DynamoDB?

A service that enables you to run relational databases in the AWS Cloud

A serverless key-value database service

A service that you can use to migrate relational databases, nonrelational databases, and other types of data stores

An enterprise-class relational database

Incorrect

The correct response option is A serverless key-value database service.

 

Amazon DynamoDB is a key-value database service. It is serverless, which means that you do not have to provision, patch, or manage servers.

 

The other response options are incorrect because:

    A service that enables you to run relational databases in the AWS Cloud describes Amazon Relational Database Service (Amazon RDS).
    A service that you can use to migrate relational databases, nonrelational databases, and other types of data stores describes AWS Database Migration Service (AWS DMS).
    An enterprise-class relational database describes Amazon Aurora.

Learn more:

    Amazon DynamoDB

Which service is used to query and analyze data across a data warehouse?

Amazon Redshift

Amazon Neptune

Amazon DocumentDB

Amazon ElastiCache

Incorrect

The correct response option is Amazon Redshift.

 

Amazon Redshift is a data warehousing service that you can use for big data analytics. Use Amazon Redshift to collect data from many sources and help you understand relationships and trends across your data.

 

The other response options are incorrect because:

    Amazon Neptune is a graph database service. You can use Amazon Neptune to build and run applications that work with highly connected datasets, such as recommendation engines, fraud detection, and knowledge graphs.
    Amazon DocumentDB is a document database service that supports MongoDB workloads.
    Amazon ElastiCache is a service that adds caching layers on top of your databases to help improve the read times of common requests.

Learn more:

    Amazon Redshift

The next module examines security in the AWS Cloud.