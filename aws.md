### ASG  
Auto-Scaling Group. Scale your Amazon EC2 capacity up or down automatically according to conditions you define.

# SG

Security Group. A security group acts as a virtual firewall that controls the traffic for one or more instances. When you launch an instance, you associate one or more security groups with the instance. You add rules to each security group that allow traffic to or from its associated instances.

### Scaling Base on Metrics
You can create scaling policies using CloudWatch alarms to determine when your ASG should scale out OR in. 

### EC2  
Amazon Elastic Compute Cloud. Also referred to simply as an "instance". It is a virutal computing environment. The templates for these instances are _AMIs_. 

### Key Pairs  
Secure login information for your _instances_. 

### Region  
Physical location for your AWS _resources_. 

## AZ  
Availability Zones. Think locations of servers! Amazon instances (EC2s) are hosted in locations all over the world. These locations are composed of regions and Availability Zones. Each region is the geographical area and each has multiple AZs.

### ECS
Think Docker! Amazon EC2 Container Service. Use the API to can launch and stop Docker-enabled applications and query the complete state of your cluster. 

### EBS  
Think server hardware! Amazon Elastic Block Store. This provides persistent block level storage volumes for use with Amazon EC2 instances in the AWS Cloud. Persistant storage volume for your data.  

### AMI  
Think images! Amazon Machine Image provides information required to launch an _instance_ (aka a virual server in the cloud). You specify an AMI when you launch one of these instances and you can launch as many instances from the AMI as you need. It includes a template for root volume for the instance. 

### Redshift 
Think Data! Petabyte-scale data storage that makes it cost-effective to analyze big data.

### SQS 
Simple Queue Service is a message queuing service. It queues messages, a queue is a temporary repo for messages waiting. 

### CloudFormation
A way of specifying templates with infrastructure and using those templates to create that infrastructure. 

### CloudFront
Think content delivery! This is a CDN (content delivery network) that uses regional edge caches to deliver content fast.

### ENI
An elastic network interface (referred to as a network interface in this
documentation) is a virtual network interface that you can attach to an
instance in a VPC. Network interfaces are available only for instances running
in a VPC.

### EFS
Elastic File System. Simple, scalable file storage for use with Amazon EC2 instances in the AWS Cloud.

### KMS

Key management store.
https://aws.amazon.com/kms/

## ALB

Application Load Balancer. Application Load Balancer is best suited for load balancing of HTTP and HTTPS traffic and provides advanced request routing targeted at the delivery of modern application architectures, including microservices and containers. 