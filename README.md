# Terraform Beginner Bootcamp 2023

## Installation Requirements

### Installing Terraform CLI

Terraform will automatically install via a Gitpod Task that will execute a bin script [bin/install_terraform_cli](bin/install_terraform_cli)

[Terraform CLI Installation Instructions](https://developer.hashicorp.com/terraform/tutorials/aws-get-started/install-cli)

####  Why rewrite the Gitpod Task File

 When starting the Gitpod enviroment the Terraform CLI failed to install automatically because it was hanging on a confirmation for a yes. 
 
Checking the Terraform CLI instructions were different from the ones located in the Gitpod Task File [([PROJECT_ROOT]/.gitpod.yml)](.gitpod.yml). So install steps were updated to match Terraforms documentation.

#### Why a bash script 	:mage:

The Terraform CLI instrustions were abstracted into a bash script and referenced in the Gitpod Task File to keep the task file small, to make the install instructions portal and easier to debug locally.

