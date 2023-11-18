#	Project 1
	Cloud Computing Essentials

##	Business Request:
-	The city's web portal needs to migrate the beach wave size prediction page to AWS to improve reliability.

###	Learning Objectives:
-	Articulate the characteristics of the AWS cloud computing platform.
- 	Describe the core benefits of using AWS products and services.
- 	Compare and contrast AWS cloud services to On-Premises infrastructure.
- 	Implement hosting a static web page using Amazon S3

Practice Lab Goals
- Create an AS3
- Enable static web hosting
- Secure the S3 bucket by using a bucket policy

Project 2 - Cloud First Steps

Business Request:
- The island's stabilization system is failing and needs increased reliability and availability for its computational modules.

Learning Objectives:
- Summarize AWS Infrastrucure benefits.
- Describe AWS Regions and Availability Zones.
- Deploy Amazon EC2 instances into multiple Availabilty Zones.

Project 3 - Computing Solutions

Business Request:
- The school server that runs the scheduling solutions needs more memory. Assist with vertically scaling their Amazon EC2 instance.

Learning Objectives:
- Describe Amazon EC2 instance families and instance types.
- Describe horizontal and vertical scaling.
- Recognize options for connecting to Amazon EC2 instances.

Practice Lab Goals
- Explore Amazon EC2 instance types
- Filter EC2 instances based on their attributes.
- Connect to an EC2 instance using Amazon EC2 Connect
- View instance metadata using the instance public IP address
- Start and stop EC2 instance by using Amazon EC2 console

Project 4 - Networking Concepts

Business Request:
- Help the bank setup a secure networking environment which allows communication between resources and the internet.

Learning Objectives:
- Describe key features of VPCs, subnets, internet gateways and route tables.
- Describe the benefits of using Amazon VPCs
- State the basics of CIDR block notation and IP addressing.
- Explain how VPC traffic is routed and secured using gateways, network access control lists, and security groups.

Practice Lab Goals
- Explore the components that comprise a VPC
 	- VPC 10.10.0.0/16
 	- Public subnet 10.10.0.0/24 - Webserver - HTTP:80:Allow
 	- Private subnet 10.10.2.0/24 - DB Server - TCP:3306:Allow
 	- Internet -> Internet gateway -> Router
- Configure a route table attached to a subnet within a VPC
- Configure an internet gateway inside a VPC
- Configure inbound rules within a security group to control access.
- 
- Configure a routing table and attach an internet gateway
- Configure a security group

Project 5: Databases in Practice

Business Request:
- Improve the insurance company's relational database operations, performance, and availability.

Learning Objectives:
- Review the features, benefits and database types available with Amazon RDS.
- Describe vertical and horizontal scaling on Amazon RDS.
- Use Amazon RDS read replicas to increase database performance.
- Implement multi-AZ deployments of Amazon RDS to increase availability.

Project 6: Connecting VPCs

Business Request:
- The city's marketing team wants separate Amazon VPCs for each department that allows communication between Amazon VPCs.

Learning Objectives:
- Summarize how VPC peering works with Amazon VPC.
- Explain the steps for establishing a VPC peering connection.
- Create a peering connection between two Amazon VPCs.
- Establish a peering connection between Amazon VPCs using a specific subnet.

Project 7: First NoSQL Database

Business Request:
- Help the island's streaming entertainment service implement a NoSQL database to develop a anew features.

Learning Objectives:
- Summarize the different uses of common purpose-built databases.
- Describe the features and benefits of Amazon DynamoDB.
- Interact with the elements and attributes of an Amazon DynamoDB database.
- Set up a NoSQL database with Amazon DynamoDB.

Project 8: File Systems in the Cloud

Business Request:
- Help the city's pet modeling agency share file data without provisioning or managing storage

Learning Objectives:
- Summarize the different storage options available on AWS.
- Summarize the key features and benefits of Amazon EFS.
- Identify business use cases for Amazon EFS.
- Configure Amazon EFS endpoints to access centralized storage.

Project 9: Auto-healing and Scaling Applications.

Business Request:
- Assist the city's gaming cafe with implementing auto healing servers while restricting patrons to a specific provisioning capacity.

Learning Objectives:
- Describe the auto healing ans scaling capabilities offered by Auto Scaling groups.
- Create an Auto Scaling group with strict resource boundaries.
- Configure an Auto Scaling group to respond to a time-based event.

Project 10: Highly Available Web Applications

Business Request:
- Help the travel agency create a highly available web application architecture.

Learning Objectives:
- Describe the principles for architecting highly available applications.
- Summarize the benefits of using an AWS Application Load BAlancer (ALB)

Project 11: Core Security Concepts

Business Request:
- Help improve security at the city's stock exchange by ensuring that support engineers can only perform authorized actions.

Learning objectives:
- Describe the creation process and differences AWS IAM users, roles, and groups.
- Review the structure and components of AWS IAM Policies.
- Summarize the AWS Shared Responsibility Model and compliance programs.

Project 12: Cloud Economics

Business Request:
- The city's surf board shop needs a cost estimation of an architecture with variable resource usage

Learning Objectives:
- Describe how pricing estimates are obtained.
- Use the AWS Pricing CAlculator to estimate the price of an AWS architecture.


