# tf_aws_template
Terraform template for creating an AWS instance.

# AWS Credentials
For terraform to create AWS service instances it requires an access key, and a secret key from your AWS account.  
The information is stored in your home directory in a file called ~/.aws/credentials

The contents of the file look like --

[default]
aws_access_key_id = yourKey
aws_secret_access_key = yourKey
