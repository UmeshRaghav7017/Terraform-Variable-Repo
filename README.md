# Terraform-Variable-Repo
This repo is created for maintaining the terraform variable code. 

# what is terraformm variable?
 ANS:-Terraform variables help avoid hardcoding values and make the code reusable and flexible across different environments.

# why we use terraform variable?
ANS:-

Step1: Declare 
Step2: Assign a value 
Step3: use (where we use)

#1.terraform apply -auto-approve -var="Rgname=littlerg-dev"(Cli)
#2.terraform apply -auto-approve -var-file="dev.tfvars"(cli)
#3. rg.auto.tfvars
#4. terraform.tfvars
#5. default (we can pass the value as default inside the variable block)
#6. If we not declare any variable of the value then we have to put the value on Cli.
 Note:   If we not pass any value of the variable by use above method then you have to assign 
         a value of the variable by the terminal(cli mode).