# terraform
## My First project on Terraform.
The Complete Terraform code to run an environment of 3 tier application which is fault tolerant and also ensure that the infrastructure is highly available with auto scaling group and policies. This code provides a Application load balancer, Instance in a public subnet which cannot be directly accessed and can be accessed with the ELB and database at the backend which is in private subnet connected to a NAT to provide internet and can be accessed only for the specified IP.
