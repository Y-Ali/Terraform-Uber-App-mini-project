# Terraform Uber App

This repositiory contains a project that uses Terraform to automate the process of running an uber app on AWS

The main.tf file contains:

- 1 VPC
- 1 public and 1 private subnet
- 1 instance for each subnet
- 1 security group for each instance
- Key pair

### Clone this repository
In your terminal:

`git clone git@github.com:Y-Ali/terraform-uber-app.git`

`git pull origin master`

### Create an instance on AWS
Navigate to your directory with the project and type:

`terraform apply`
