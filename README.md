# terrafrom-ecs

In this project, I used Terraform modules from the "terraform-aws-modules" library to create the VPC, Redis, RDS, S3, and ECS components of the infrastructure. The modules handle the creation of the components and their connection to each other. The modules are configured with the appropriate parameters to connect the Redis instance to the VPC, the RDS instance to the private subnets of the VPC, the S3 bucket to the account, and the ECS cluster to the private subnets of the VPC, the RDS instance, and the Redis instance.
