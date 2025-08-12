**1. Install Terraform**
Download and install Terraform from the official site.

**2. Install AWS CLI**
Follow the installation guide here:
https://docs.aws.amazon.com/cli/latest/userguide/getting-started-install.html

**3. Verify AWS CLI Installation**
Open your terminal and run:
aws --version

**4. Create an AWS IAM User**
Go to the AWS Management Console and create a new user with programmatic access.
Download the CSV file containing the Access Key ID and Secret Access Key for this user. Keep it safe.

**5. Set Up Your Project Folder**
Create a new folder for your Terraform project and add the following files:

  provider.tf

  variable.tf

  main.tf

  outputs.tf

  index.html (a single file containing all HTML, CSS, and JS)

  error.html

**6. Configure AWS CLI**
Open a terminal and run:
aws configure
Enter your Access Key ID and Secret Access Key from the CSV file. Leave the default region and output format empty or set as needed.

**7. Terraform Commands**

Initialize the project:
terraform init

Preview the changes Terraform will make:
terraform plan

Apply the changes (create resources):
terraform apply
Type yes when prompted.

To remove the created resources:
terraform destroy
Type yes when prompted.

