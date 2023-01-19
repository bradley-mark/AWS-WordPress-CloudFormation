# AWS-WordPress-CloudFormation

WordPress basic single instance

Installs and deploys WordPress on to a single Amazon EC2 instance with a local MySQL database for storage.

1. Open CloudFormation console **https://console.aws.amazon.com/cloudformation/home**
2. In the navigation pane, choose **Stacks**
3. Choose **Create stack** With existing resources (import resources)
4. Choose **Next**
5. **Specify template** choose **Upload a template file** choose file **Next**
6. **Identify resources** **Next**
7. **Specify stack details**

**Stack name** WordPress Basic

**DBName** enter DBName

**DBPassword** enter DBPassword

**DBRootPassword** enter DBRootPassword

**DBUser** enter DBUser

**InstanceType** t2.micro

**KeyName** enter Key Pair

**SSHLocation** IP address range
