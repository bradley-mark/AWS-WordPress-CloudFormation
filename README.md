# AWS-WordPress-CloudFormation

WordPress basic single instance

Installs and deploys WordPress on to a single Amazon EC2 instance with a local MySQL database for storage.

1. Open CloudFormation console **https://console.aws.amazon.com/cloudformation/home**
2. In the navigation pane, choose **Stacks**
3. Choose **Create stack** With new resources (standard)
4. Prerequisite - Prepare template choose **Template is ready**
5. **Specify template** choose **Upload a template file** choose file **Next**
6. **Identify resources** **Next**
7. **Specify stack details** enter details

**Stack name** - WordPress-Basic
  
    **DBName**

  **DBPassword** 

  **DBRootPassword**

  **DBUser**
  
  **InstanceType** - t2.micro

  **KeyName** - existing key pair
  
  **SSHLocation** - IP address range

8. Choose **Next**
9. Keep all defaults - **Next**
10. Review - **Submit**

