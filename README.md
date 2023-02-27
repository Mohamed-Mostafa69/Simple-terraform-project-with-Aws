# Simple-terraform-project-with-Aws 

Steps to Create this project
----------------------------
Aws Account / IAM user
1- Create vpc
2- Create Internet Gateway
3- Create Custom Route Table
4- Create a Subnet
5- Associate subnet with Route table
6- Create Security Group to allow port 22,80,443
7- Create A Network Interface with an Ip in the Subnet that was Created in Step 4
8- Assign an elastic Ip to the network interface created in step 7
9- Create Ubuntu Server and install/enable apache2

Run Terraform
-------------

- terraform init: Setup a new terraform project for this file.
- terraform apply: Setup the infrastructure as it’s defined in the .tf file.
- terraform destroy: Tear down everything that terraform created.
- terraform state list: Show everything that was created by terraform.
- terraform state show aws_instance.web_instance: Show the details about the ec2 in-
stance that was deployed