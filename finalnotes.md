# Final Study Notes

## I. Cloud Concepts Overview

### 1. Summarize a few key points made in the readings or videos 
+ Horizontal Scaling: scaling out and scaling in
+ Vertical Scaling: scaling up and scaling down
+ Six Advantages of Cloud Computing: Trade capital expense for variable expense, Benefit from massive economies of scale, stop guessing capacity, increase speed and agility, stop spending money on running and maintaining data centers, go global in minutes.
+ Cloud Deployment Models: Cloud, Hybrid and On-Premises or Private Cloud.

### 2. Identify two quotes that were made, that you found interesting.

a. "Cloud computing is a model for enabling ubiquitous, convenient, on-demand network access to a shared pool of configurable computing resources (e.g., networks, servers, storage, applications, and services) that can be rapidly provisioned and released with minimal management effort or service provider interaction. This cloud model is composed of five essential characteristics, three service models, and four deployment models" (2.1). <br/>
b. "Runtime failures that are not immediately corrected can have a more significant impact during high-volume usage periods. Not only is the IT resource unable to respond to customer requests, its unexpected failure can decrease overall customer confidence" (2.4).

### 3. What new facts did you learn from this section
a. Clouds can be for public use, like the Internet, and private clouds allow users to access privately owned internet resources such as documents accessed through the internet. <br/>
b. Cloud consumers experience decreased portability moving data from one cloud provider to another cloud provider's services. <br/>
c. SaaS applications, such as Microsoft 365, overall performance relies heavily on a user's internet performance. SaaS is often end-user applications often maintained by the service provider. <br/>
d. The On Premises cloud model, or private cloud, doesn't provide all the benefits of cloud computing but is utilized because of its ability to provide on premise resources.

## II. Cloud Economics, Billing & Support

### Summarize a few key points made in the readings or videos.
+ With a Pay-as-you-go pricing model, costs of operation are optimized to total use.
+ There are three fundamental drivers of cost with AWS:<br/>
a. Compute <br/>
b. Storage <br/>
c. Outbound data transfer <br/>
+ You do not pay for cloud-based resources that are not being used.

+ An Organizational Unit is a container for user accounts.
+ Allow list strategy – You explicitly specify the access that is allowed.
+ Deny list strategy – You explicitly specify the access that is not allowed.

### Identify two quotes that were made, that you found interesting.
a. "One of the main benefits of cloud services is the ability it gives you to optimize costs to match your needs, even as those needs change" (4.01). <br/>
b. "AWS Organizations includes account management and consolidated billing capabilities that enable you to better meet the budgetary, security, and compliance needs of your business. As an administrator of an organization, you can create accounts in your organization and invite existing accounts to join the organization" (4.16). <br/>

## III. Cloud Global Infrastructure

### Summarize a few key points made in the readings or videos. 
+ A DevOps work environment is very collaborative learning environment

#### Evolution of Work Culture 
+ Old work environment: Bad apples in the bunch are the problem
+ New work environment: We need to fix the system
+ Siloization is the process of separating and making clear distinctions between people who work on software and hardware. <br/>

#### A DevOps work culture leads to:
a. Increased transparency and trust within a team <br/>
b. Instruct our coworkers in how to avoid a costly mistake without having to
directly experience it <br/>
c. Increase the time spent on solving new problems, allowing for more innovation.<br/>

#### Four pillars of effective DevOps: 
Collaboration, Tools, Affinity, Scaling 

### Identify two quotes that were made, that you found interesting.
a. "If things broke, it would help prioritize the criticality of further sharing, documenting, and distributing my knowledge and expertise to the business. Ultimately, that would lead to more stability and a better overall outcome for the organization and individuals on the team" (Chapter 1). <br/>

b. "A guiding principle that shaped the devOps movement was the cooperation of software development and operations teams. Before one team can successfully work with another team with a different focus, the individuals on a team need to be able to work with each other" (Chapter 6). <br/>

### What new facts did you learn from this section?

+ Collaboration improves DevOps work cultures and implementing effective updates
+ The term DevOps itself is a portmanteau of “development” and “operations” 
+ It is important to have the right set of tools to improve the success of an organization
+ Sometimes forums, social media, or information repositories can help system admins manage servers

### What questions remain in your mind after reading this section?
a. When software was proprietary, was working with the source code limited because of it being copyrighted? <br/>

b. Did the increased use of open source software increase the collaboration between development and operations? <br/>

## IV. Cloud Secuirty with DevOps

### Summarize a few key points made in the readings or videos.
+ Hackers, attackers or intruders exploit vulnerabilities in software to obtain unauthorized access of systems.
+ Steganography concealing information within another piece of information

#### Types of User Security Control Settings
+ Inherited Controls: Settings preconfigured by AWS
+ Shared Controls: Controller Settings combining customer control settings and AWS.
+ Customer Specific: Controls implemented by the customer when using AWS Cloud services.
+ Data at rest is data stored on a disk and is either encrypted by the Cloud provider or the Client.

### Identify two quotes that were made, that you found interesting.
a. "AWS Cloud Compliance enables you to understand the robust controls in place at AWS to maintain security and data protection in the cloud in order to achieve compliance with your solutions. As systems are built on top of AWS Cloud infrastructure, compliance responsibilities will be shared" (6.14). <br/>
b. "Some AWS Premium Support plans include access to the Trusted Advisor tool, which offers a one-view snapshot of your service and helps identify common security misconfigurations, suggestions for improving system performance, and underutilized resources" (AWS Best Security Practices).

### What new facts did you learn from this section?
+ Use strong passwords and implement MDA to minimize cybersecurity attacks
+ Try not to use shared identities for security purposes one user one IAM user account 
+ AIC triad Availability Integrity and Confidentiality
+ AWS serviced fall under three categories: Infrastructure services, Container Services, Abstracted Services.
+ AWS Account is the main account (root user) IAM users are controlled by a single AWS account
+ AWS Shield is a Ddos protection service minimizing downtime

## V. Networking & Connectivity

### Summarize a few key points made in the readings or videos.
+ Types of Network Topologies Star, Mesh, Ring, Daisy Chain
+ Protocols are sets of rules for which two entities can communicate
+ Every device in the network is a known as Hostname
+ CIDR address ex /24 is 256 IP addresses 0 to 255
+ DNS is Domain Name System
+ Subnets that can't access the internet are private subnets
+ VPNs connect users by encrypting data being sent

### Identify two quotes that were made, that you found interesting.
a. "In simplest words, it is a global network of smaller networks interconnected using communication protocols that are standardized. The Internet standards describe a framework known as the Internet protocol suite" (7.02)
<br/>
b. "An internet gateway serves two purposes: to provide a target in your VPC route tables for internet-routable traffic, and to perform network address translation (NAT) for instances that have been assigned public IPv4 addresses" (7.12)

### What new facts did you learn from this section?
+ Type “ipconfig” in the command prompt and press ‘Enter’, this gives us the IP address of the device.
+ Type “netstat -a” in the command prompt and press ‘Enter’, this lists all the ports being used.
+ The command ‘nslookup’ gives you the IP address of the domain you are looking for. This also provides the information of our DNS Server.

## VI Compute

### Summarize a few key points made in the readings or videos.
+ Types of Operating Systems: Windows, Mac, Linux
+ User interface: GUI and CLI
+ Instance based machines are IaaS applications 
+ AMI are preconfigured virtual machines
+ five ways to pay for Amazon EC2 instances: On-Demand, Savings Plans, Reserved Instances, and Spot Instances. 
+ Four Pillars of Cost Optimization: Right Size, Increase elasticity, leverage the right pricing model, Optimize storage 
+ Serverless architecture is using services to access servers remotely

### 2. Identify two quotes that were made, that you found interesting.
a. "You can also use Amazon EC2 Auto Scaling to maintain availability of your EC2 fleet and automatically scale your fleet up and down depending on its needs in order to maximize performance and minimize cost" (8.06).
<br/>
b. "Amazon Elastic Container Service (Amazon ECS) is a highly scalable, fast, container management service that makes it easy to run, stop, and manage Docker containers on a cluster" (8.14)

### What new facts did you learn from this section?
+ Linux is an open source OS which is free for users to use and modify
+ A virtual machine is a software based computer running on another computer's OS
+ Hypervisor is the software that runs virtual machines

## VII. Storage

### Summarize a few key points made in the readings or videos. 
+ RAM temporarily stores data while the computer is powered on; temporary saved data is lost when powered off.
Cloud storage is data storage as a service.
+ Cloud storage is data storage as a service.
+ Amazon S3 is an object storage service that is scalable secure, and has high performance.
+ S3 Glacier is good for storing files that need to be saved but not always accessed
+ Bulk Retrievals are the lowest cost S3 glacier service usually complete in 5-12 hours.

### Identify two quotes that were made, that you found interesting. 
+ "Disaster recovery (DR) starts with a plan that works in conjunction with the business continuity and contingency plans" (9.02)
+ "To store and access data in Amazon S3 Glacier, you can use the AWS Management Console. However, only a few operations—such as creating and deleting vaults, and creating and managing archive policies—are available in the console" (9.10)

### What new facts did you learn from this section.
a. Volatile storage (RAM) vs. Non-Volatile storage (HDD SSD) <br/>
b. SSD storage is fast reliable, and uses less power than HDD storage <br/>
c. HDD cost less than SSD especially for larger storage drives. <br/>
d. Fault Tolerance is a system designed to reduce failure. <br/>
e. Cipher text is encrypted text

## VIII. DataBases

### Summarize a few key points made by the readings or video
+ Database is a shared collection of data.
+ Database Management System (DBMS) 
+ Atomic value is a value in the domain that is indivisible
Ex. Domain of Shift has the set of possible days
+ Amazon DB  NoSQL database
+ Amazon RDS is an SQL database
+ Query Retrieval of data
+ Managed Services vs Unmanaged services

### Identify two quotes that were made, that you found interesting.
a. "Majority of the work in a system is done using SELECT, INSERT, UPDATE, and DELETE" (10.05). <br/>
b. "Amazon Aurora is up to five times faster than standard MySQL (Links to an external site.) databases and three times faster than standard PostgreSQL databases. It provides the security, availability, and reliability of commercial databases at 1/10th the cost" (10.12).

### What new facts did you learn from this section?
+ Read and write privileges allow users to read and modify files.
+ Data redundancy is used to improve performance in database
+ Read-only access only allows user to view files.
+ C.F Codd introduced the relational data model which influenced structured query language (SQL)
+ Cloud and IT solutions, and not just database services, typically fall into one of two categories: unmanaged or managed.

## IX. Cloud Architecture

### Summarize a few key points made by the readings or video
+ Five pillars of the AWS Well-Architected Framework — operational excellence, security, reliability, performance efficiency, and cost optimization.
+ Resource constraints is like space on a hard drive or data speed of a ethernet cable
+ Mitigate deployment risk by fixing issues that don't have desired outcomes with accelerated bug fixing and quality assurance.

#### General Design Principles of the Well-Architected Framework
+ Stop Guessing your capacity needs
+ Test systems at production scale
+ Automate to make architectural experimentation easier
+ Allow for evolutionary architectures
+ Drive architectures using data
+ Improve through game days

### Identify two quotes that were made, that you found interesting.
a. "Successful evolution of operations is founded in: frequent small improvements; providing safe environments and time to experiment, develop, and test improvements; and environments in which learning from failures is encouraged" (13). <br/>
b. "The optimal network solution for a workload varies based on latency, throughput requirements, jitter, and bandwidth. Physical constraints, such as user or on-premises resources, determine location options. These constraints can be offset with edge locations or resource placement" (28).

### What new facts did you learn from this section?
+ Security includes: the ability to protect data, systems, and assets to take advantage of cloud technologies.
+ Human Identities: Admins, developers, operators, and end users or members of an organization.
+ Machine Identities: service applications, operation tools, and workloads require identities to secure access.

## X. Automatic Scaling & Monitoring

### Summarize a few key points made by the readings or video
+ Cloud applications change on demand to provide the right level of performance needed to complete a task.
+ Cloudwatch offers basic monitoring services of certain metrics free of charge when using AWS services.
+ Connection draining is closing new request to an unhealthy instance and let existing request finish task.
+ Load balancing regulates network traffic; AWS charges by each load balancer and load capacity units  (LCU) used.
+ Load Balancing Options: the Application Load Balancer (ALB), the Network Load Balancer (NLB), and the Classic Load Balancer (CLB)

### Identify quotes that were made, that you found interesting.
a. "The default retention of CloudWatch logs is forever; however, you can decide on a retention timeframe of up to 10 years. Retention of records stored in S3 buckets can be managed with lifecycle rules" (Wilkins). <br/>
b."ELB load-balancing options integrate with EC2 instances, EC2 auto scaling, Certificate Manager, CloudWatch, Route 53, and, if you’re using the ALB, you can also add a web application firewall (WAF) ACL for additional protection" (Wilkins). <br/>
c. "With sticky sessions enabled on a load balancer, after a request is routed to a target, a cookie is generated by the load balancer and returned to the client. All requests from the client from this point forward include the cookie; the information contained in the cookie ensures that the request is routed by the load balancer to the same back-end server" (Wilkins). <br/>
d. "A Network Load Balancer (NLB) is designed for supporting private resources using the TCP protocol and port number at the fourth layer of the OSI stack. Listeners, target groups, health checks, and most of the features are similar but not exactly the same as an ALB because the NLB is designed for private access" (Wilkins).

### What new facts did you learn from this section?
+ ALB (Application Load Balancer) Layer 7 OSI model.
+ Human Identities: Admins, developers, operators, and end users or members of an organization.
+ Machine Identities: service applications, operation tools, and workloads require identities to secure access.
+ The CloudWatch dashboard is used to monitor metrics of each service.

### Questions to consider when moving to the cloud

1. Do you have golden images for your Web and application servers?
2. Can you replace existing third-party load balancers with ELB services?
3. Are your applications hosted in public subnets?
4. Should you be tracking CloudTrail APIs using CloudWatch log groups and metric filters?
5. Can CloudWatch help monitor your on-premise servers with the installation of the CloudWatch agent?
6. Can launch configurations help you plan your auto scaling deployments?
7. Are billing alarms enabled to manage your developer’s project costs?
8. Can Lambda functions be created to help automate solutions with CloudWatch alerts?
9. Will step scaling policies help improve application performance?
10. Will step scaling policies help you save even more money?
