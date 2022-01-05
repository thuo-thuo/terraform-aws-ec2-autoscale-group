# Assumptions
1. You have cloned this repo and navigated into the autoscaling_example directory.
2. You have installed aws cli from https://docs.aws.amazon.com/cli/latest/userguide/getting-started-install.html.
4. You have created an aws cloud account and logged into it. 
5. On the aws console, you have created an IAM user, granted it rights to access EC2 instances and downloaded the access key and secret access key.
6. You have run aws configure on the terminal and input the access key and secret access key.

# Running the script
1. Navigate into the autoscaling_example directory and run terraform init. 
2. Replace the variables in the fixtures.us-east-2.tfvars file with the values as instructed.
3. Run terraform plan -var-file=fixtures.us-east-2.tfvars -out=path

# Testing the script

* Terraform provider is: https://github.com/cloudposse/terraform-aws-ec2-autoscale-group