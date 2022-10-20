# How to deploy a three-tier architecture in AWS using Terraform?

### What is Terraform?

Terraform is an open-source infrastructure as a code (IAC) tool that allows to create, manage & deploy the production-ready environment. Terraform codifies cloud APIs into declarative configuration files. Terraform can manage both existing service providers and custom in-house solutions.


### Prerequisites:

* Basic knowledge of AWS & Terraform
* AWS account
* AWS Access & Secret Key

 

We need to run the below steps to create infrastructure.

* terraform init is to initialize the working directory and downloading plugins of the provider
* terraform plan is to create the execution plan for our code
* terraform apply is to create the actual infrastructure. 



* Terraform will create below resources

  * VPC
  * Application Load Balancer
  * Public & Private Subnets
  * EC2 instances
  * RDS instance
  * Route Table
  * Internet Gateway
  * Security Groups for Web & RDS instances
  * Route Table

Once the resource creation finishes you can get the DNS of a load balancer and paste it into the browser and you can see load balancer will send the request to two instances.


 
