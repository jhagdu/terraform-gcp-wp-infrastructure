# terraform-gcp-wp-infrastructure
This Repository Contains Terraform Code to Deploy WordPress on GCP Infrastructure

# Usage
First Download or Clone this repo to your local system  
After this,  
To Initiate Terraform WorkSpace       :- terraform init  
To create infrastructure, run command :- terraform apply -auto-approve  
To delete infrastructure, run command :- terraform destroy -auto-approve  

# Prerequisites
1) Terraform should be Installed  
2) gcloud SDK should be Installed  
3) Replace the gcpCreds.json file with Yours Service Account Key file  
4) In variables.tf Replace the Project ID with Yours  
