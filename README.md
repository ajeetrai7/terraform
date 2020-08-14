# terraform
Terraform repo.  
These terraform scripts is to automate creation of AWS ec2 instance,  
with web-server configuring on ec2 instance.  

Terraform is actually a tool for building,changing and versioning infrastrucutre safely and efficiently.    
Terraform can manage existing and popular service providers as well as custom in house solution.    
Terraform is polularly known as Automation of infrastructure(Infrastructure as code).     
It maintains the state of infrastructure (state managemnet).
Terraform can automate any cloud provider, like Aws, Gcp , Azure.

***** Terraform installation in linux *****  
  
Create a folder named terraform   

$ mkdir terraform  
$ cd terraform    
Download the terraform  
$ wget https://releases.hashicorp.com/terraform/0.13.0/terraform_0.13.0_linux_amd64.zip  
$ ls

Unzip terraform   
$ unzip terraform_0.13.0_linux_amd64.zip
Check terraform version 
$ terraform -version

***** Done with the installation part , next proceed with the terraform execution. ******    
So we will execute some commands to launch automated ec2 instance.     
All the necessary files are available to launch.    

$ terraform plan   
This command will show us about all things getiing provisoning, what all things going to happen .  

$ terraform apply   
This command will execute changes to reach out desired state.   
Parallelism changes when possible. Also it handles and recovers transit error safely.  
This command will basically launch the instance.  

There is one more command to terminate the instance (infrastructure) provisioned.  
$ terraform destroy   



