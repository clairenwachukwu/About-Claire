<link rel="stylesheet" href="https://cdn.jsdelivr.net/gh/devicons/devicon@v2.15.1/devicon.min.css">
          

# Claire 👋 
### Cloud DevOps Engineer
Hey there! I'm Claire, an experienced IT professional with a diverse background spanning IT support and software development. Equipped with an AWS Solutions Architect Associate certification and bolstered by a Master's in IT Management, I thrive on devising innovative solutions and harnessing technology for impactful outcomes. My career has encompassed leadership roles across various tech industries, spearheading projects ranging from monitoring tool migration, cloud cost optimization, and security to automation, SLO/SLI generation, and implementation. Join me on my GitHub journey, where I share insights, projects, and code, reflecting my fervor for achieving excellence in the ever-evolving tech landscape.

## 💼LANGUAGES AND TOOLS
Here are some of the tools and languages I have experience with and used in projects:

<div style="display: flex; justify-content: space-around;">
    <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/amazonwebservices/amazonwebservices-plain-wordmark.svg" width="100px"/>
    <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/javascript/javascript-original.svg" width="70px"/>
    <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/python/python-plain-wordmark.svg" width="70px"/>
    <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/terraform/terraform-original.svg" width="70px"/>
    <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/ansible/ansible-original-wordmark.svg" width="70px"/>
    <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/jira/jira-original-wordmark.svg" width="70px"/>
    <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/linux/linux-original.svg" width="70px"/>
    <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/jenkins/jenkins-original.svg" width="70px"/>
    <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/docker/docker-original.svg" width="70px"/>
    <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/kubernetes/kubernetes-plain.svg" width="70px"/>
</div>

## 👩‍💻 PROJECTS
### EC2 Master
This AWS project aims to create a highly available and scalable web application infrastructure using Amazon Web Services (AWS). The infrastructure includes a Virtual Private Cloud (VPC) with public and private subnets spread across multiple Availability Zones (AZs), EC2 instances hosting an Nginx web server, an Application Load Balancer (ALB), Auto Scaling Group, and CloudWatch alarms for automatic scaling based on CPU utilization.

![Alt text](https://github.com/clairenwachukwu/clairenwachukwu/blob/1876023b75d7a4e26a9022fec0eeb0f7e05c18f2/ec2MasterImg.png)
Application Architecture used:


EC2 (Elastic Compute Cloud)
Networking Services:
VPC (Virtual Private Cloud)
Internet Gateway
Route Table
Subnet
NAT Gateway
Security Group
ALB (Application Load Balancer)
Auto Scaling
CloudWatch
Other Technology used:
Terraform
Bash 


Architecture Overview:
The project architecture consists of the following components:

VPC: A Virtual Private Cloud (VPC) is created

Public Subnets: Three public subnets are created, each in a different Availability Zone, allowing instances in these subnets to have public internet access

Private Subnets: Three private subnets are created, each in a different Availability Zone, where EC2 instances hosting the web application reside. These instances do not have direct internet access.

Internet Gateway: An Internet Gateway is attached to the VPC, allowing instances in the public subnets to connect to the internet.

NAT Gateway:A NAT Gateway is deployed in one of the public subnets, enabling instances in the private subnets to initiate outbound traffic to the internet while keeping them secure.

Security Groups: Security groups are implemented to control inbound and outbound traffic for the instances.

ALB: An Application Load Balancer (ALB) is created in the public subnets to distribute incoming web traffic across multiple instances.

Auto Scaling Group: An Auto Scaling Group is configured to automatically scale the number of EC2 instances based on CPU utilization. CloudWatch alarms trigger scaling policies.

          
          

          

          



