Install terraform
Install awscli : https://docs.aws.amazon.com/cli/latest/userguide/getting-started-install.html
Check if installed : aws –version
Create new user on aws and store/download csv file of access id and secret access key
Create new project folder :
1)	Create provider.tf
2)	Create variable.tf (enter unique bucket name here)
3)	Create main.tf
4)	Create outputs.tf
5)	index.html (Make “index.html” file that includes all the html,css and js.)
6)	error.html
Open terminal  
	aws configure -> add those id and key. Keep empty for next remaining 2 fields.
	Terraform init
	Terraform plan
	Terraform apply -> yes
	Terraform destoy -> yes (if want to delete)
