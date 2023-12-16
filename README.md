<link rel="stylesheet" href="https://cdn.jsdelivr.net/gh/devicons/devicon@v2.15.1/devicon.min.css">
          

# Claire 👋 
### Cloud DevOps Engineer
Hey there! I'm Claire, an experienced IT professional with a diverse background spanning IT support and software development. Equipped with an AWS Solutions Architect Associate certification and bolstered by a Master's in IT Management, I thrive on devising innovative solutions and harnessing technology for impactful outcomes. My career has encompassed leadership roles across various tech industries, spearheading projects ranging from monitoring tool migration, cloud cost optimization, and security to automation, SLO/SLI generation, and implementation. Join me on my GitHub journey, where I share insights, projects, and code, reflecting my fervor for achieving excellence in the ever-evolving tech landscape.

----
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

---
## 👩‍💻 PROJECTS
### 1) EC2 Master
This AWS project aims to create a highly available and scalable web application infrastructure using Amazon Web Services (AWS). The infrastructure includes a Virtual Private Cloud (VPC) with public and private subnets spread across multiple Availability Zones (AZs), EC2 instances hosting an Nginx web server, an Application Load Balancer (ALB), Auto Scaling Group, and CloudWatch alarms for automatic scaling based on CPU utilization.

<img src="https://github.com/clairenwachukwu/clairenwachukwu/blob/1876023b75d7a4e26a9022fec0eeb0f7e05c18f2/ec2MasterImg.png" alt="Alt text" style="width:auto;height:400px;">

#### Application Architecture used:
+ EC2 (Elastic Compute Cloud) 
+ Networking Services: VPC, Internet Gateway, Route Table, Subnet, NAT Gateway, Security Group
+ ALB (Application Load Balancer)
+ Auto Scaling
+ CloudWatch
+ Other Technology used: Terraform, Shell scripting


#### Architecture Overview:
The project architecture consists of the following components:

- VPC: A Virtual Private Cloud (VPC) is created

- Public Subnets: Three public subnets are created, each in a different Availability Zone, allowing instances in these subnets to have public internet access

- Private Subnets: Three private subnets are created, each in a different Availability Zone, where EC2 instances hosting the web application reside. These instances do not have direct internet access.

- Internet Gateway: An Internet Gateway is attached to the VPC, allowing instances in the public subnets to connect to the internet.

- NAT Gateway:A NAT Gateway is deployed in one of the public subnets, enabling instances in the private subnets to initiate outbound traffic to the internet while keeping them secure.

- Security Groups: Security groups are implemented to control inbound and outbound traffic for the instances.

- ALB: An Application Load Balancer (ALB) is created in the public subnets to distribute incoming web traffic across multiple instances.

- Auto Scaling Group: An Auto Scaling Group is configured to automatically scale the number of EC2 instances based on CPU utilization. CloudWatch alarms trigger scaling policies.

#### Project Deployment:[          ](https://github.com/clairenwachukwu/ec2Master.git)https://github.com/clairenwachukwu/ec2Master.git

---
### 2) Cloud-Based Exponent Calculator
This Exponent calculator Application is a serverless end-to-end cloud-based project designed to calculate the exponent of two numbers provided by the user. The project utilizes several AWS services such as AWS Amplify, S3 bucket, API Gateway, Lambda functions, IAM, and DynamoDB to create scalable, secure, and highly available architecture.

<img src="https://github.com/clairenwachukwu/clairenwachukwu/blob/feeb1b534fc2b669f509082f47c397691f864d18/exponentCalImg.png" alt="Alt text" style="width:auto;height:400px;">

#### Architecture Overview:
The architecture of the AWS Calculator Application is designed to handle user requests efficiently, compute the exponent, and store the results in a database for future reference. Here's an overview of the components and their interactions:

+ Amazon S3:
The static HTML, CSS, and JavaScript files of the application are hosted on an Amazon S3 bucket. S3 ensures high availability and low latency for serving these files to users globally.

+ AWS Amplify:
Amplify is used for deploying and managing the frontend application. It simplifies the process of connecting the frontend to backend services.

+ API Gateway:
API Gateway acts as a gateway for the frontend to communicate with the backend Lambda functions. It provides a secure and scalable API endpoint for the frontend application.

+ Lambda Functions:
AWS Lambda functions are serverless compute services that execute the exponent calculation logic. A Lambda function is created to receive user input and perform the exponent calculation and for storing the results in DynamoDB.

+ IAM (Identity and Access Management):
IAM roles and policies are used to manage permissions for the Lambda functions. The functions are granted specific permissions to interact with other AWS services securely.

+ DynamoDB:
DynamoDB is a NoSQL database service provided by AWS. It is used to store the calculated exponents along with relevant metadata. DynamoDB offers fast and reliable performance at any scale.

+ Other Technology used: Terraform, Python, Bash

#### Project Deployment: https://github.com/clairenwachukwu/ec2Master.git

---

## 🛠️  Currently Working On..
###  DevSecOps Pipeline Project: Deploy Netflix Clone on Kubernetes
In this project centered around DevSecOps practices, my goal is to employ a secure continuous integration and continuous deployment (CICD) pipeline, orchestrated by Jenkins, to deploy a Netflix-like application as a Docker container onto a Kubernetes cluster. This deployment involves the utilization of various widely-used DevOps tools such as Docker, Sonarqube, Trivy, Prometheus, Grafana, and additionally, Argocd and Helm for managing Kubernetes deployments.

<img src="https://github.com/clairenwachukwu/clairenwachukwu/blob/2de831c5f6b3833423fbadea4705ec3aa8fad499/DevSecOps%20Project.png" alt="Alt text" style="width:auto;height:500px;">

The application and infrastructure repositories for this project are currently private but happy to answer questions if you have any 😊.

---

### :fire: My Stats :
![GitHub Streak](http://github-readme-streak-stats.herokuapp.com?user=clairenwachukwu&theme=dark&background=000000)
![Top Langs](https://github-readme-stats.vercel.app/api/top-langs/?username=clairenwachukwu&layout=compact&theme=vision-friendly-dark)




          



