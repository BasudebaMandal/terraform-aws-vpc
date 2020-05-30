# terraform-aws-vpc
Create VPC with multiple subnets on AWS by using this terraform infra provisioning code ( IaaC)

AWS Resources:
•	Region
•	Availability zone
•	VPC
•	Web and DB tiers
•	Security Groups ( Web tier , DB tier )
•	Internet Gateway
•	Route Table
•	Route Table and Subnet association
•	EC2 instance in Web and DB tier

Requirements:
    
•	Terraform Binary
•	Access_key ( for programmatic access )
•	Secret_key ( for programmatic access )
•	Key_name ( To access ec2 instances )
•	Path_of_Private_key_on_local_machine ( To access ec2 instances )

Installation :

To create a VPC on aws using terraform code in this repository, variables need to be configured as per the one’s own need.

Commands :

•	Terraform init
•	Terraform plan -out aws_vpc.plan
•	Terraform apply aws_vpc.plan
