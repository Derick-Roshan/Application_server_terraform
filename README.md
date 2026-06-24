This Terraform file is Hosting the Application or website on the Ec2 instance.

- Incuding VPC, Subnets, Route table, Internet gateway, Security groups, ALB (Application Load Balancer),
  3 Ec2 instance with Bash codes at a same time, attaching Load balancer with 3 ec2 etc..

- Region and security should be change for deploying the project. (provider.tf)

- And It can be usable for any kind of Application after git repo link is changed. (main.tf)

- And Bash code also need to be changed, if is used for any other application deployment. (main.tf)

Advantage: 

- It helps to deploy the project in a minutes.

- Dont need to create the Service from provider each and everytime from scratch.

- Dont want deploy the each and everytime from the scratch.

- easy and Faster Deployment.
  
Deploying process:
