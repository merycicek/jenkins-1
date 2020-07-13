Jenkins Class 4
Topic Packer
#devops/jenkins/class/4

Create a Jenkins job to run the packer build. Jenkins job should

Pull the source code
Set all environment variables
Get or use existing packer command to build AMI on AWS
Make sure the job is using listed regions to build the AMI
Environment Variables
AWS access key and secret key to be able to access to AWS

export AWS_ACCESS_KEY='something'
export AWS_SECRET_KEY='something'
export AWS_REGION='us-east-1'
Regions
us-west-2
us-west-1
us-east-2
us-east-1
eu-west-1
© 2020 GitHub, Inc.