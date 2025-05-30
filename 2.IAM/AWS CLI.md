# Ways to access AWS cloud
## AWS CLI
  - Download AWS ClO from AWS site and access from cmd. After installation check for version. aws --version
  - CLI Available for Windows, MAC and Linux OS
  - We can run various aws cmds from aws cli in cmd and check the services in cmd
  - AWS Cli allows all actions based on access provided to an user. ex: IAM User can access things based on their allowed permissions/roles.

## AWS Secret Access key ID and Access Key
  - We can generate AWS Secret Access ID and KEY and use them to log into AWS from AWS CLI.
  - Access ID and KEY can be generated from AWS Web console.
  - Access Key and ID can be generated for many use cases like Accessing AWS using AWS CLI, an Application running on AWS services requires ID and Key, for the Application to log in to AWS, or for other 3rd party logins.
  - While generating AWS Access Key and ID, AWS also recommends alternative approaches to use AWS Services. ex: Cloud Shell from web console or AWS IAM login from AWS CLI V2.
  - Use Cmd "aws configure" to enter Secret ID and Key and set your region.
  - after login, you can use aws cmds. ex: aws list iam list-users, it will give you output if your user got access else return empty.

    ![image](https://github.com/user-attachments/assets/b195afa9-b166-4956-9947-a8b87cf7d3a3)

