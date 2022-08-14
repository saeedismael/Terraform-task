# Terraform-task

In this repository, i used Terraform to create the following enviroment:

    VPC
    2 Subnets: a public and a private subnet
    Internet Gateway
    NAT Gateway
    Route Tables - one foreach subnet
    Route Tables Associations
    an instance with WordPress installed on the public subnet
    an instance with MySQL installed on the private subnet


## Run Terraform:



```bash
  git clone https://github.com/saeedismael/Terraform-task.git

  cd Terraform-Task

  terraform init

  terraform plan  
  
  terraform apply
```
