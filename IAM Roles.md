# IAM Roles in AWS
  - AWS allows the creation of roles for accessing different aws services. These roles are assigned to Users, So that they can access services related to that role.
  - IAM > Roles > Create Role
  - There are different types of roles creation trusted entity types are there. ex: For AWS Services, For SAML, For AWS Account, For Web identity.
  - Ex: For AWS Service Trusted entity means, creating a role for any AWS Service (EC2, AppStream, Dynamodb, Kafka), So that they can perfomr action in the AWS Account.
  - Roles give access to perform action to the AWS EC2 Instance in the account when required.
    
     Ex: Role Creation for EC2 Instance with read-only access to IAM of the AWS Account.
     Create Role > Choose AWS Service > EC2 > Add IAM Read Only Access in Permissions
