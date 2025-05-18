# Security Groups Hands-On working
  - The security tab for an instance is available in the instance details, and we can refer to the security rules and its details of that instance. It contains inbound and outbound rules of that instance.

    ![image](https://github.com/user-attachments/assets/83fa469c-f4b1-4d42-804d-4fd2cfeec4e0)

  - The Security group button available from the side menu shows the full list of security groups available for all the instances. We can select groups and view security group rules associated with that group.

    ![image](https://github.com/user-attachments/assets/9263c3cc-8f3c-40e8-b676-217eb8729a65)

  - For every security group created, there is a security group id created and used also an identifier.

    ![image](https://github.com/user-attachments/assets/2bec4f8b-7b46-444f-8c48-546492a83c64)

  - There are inbound and outbound rules associated to every security group.

      Inbound: traffic coming into the EC2 instance. ex: someone trying to access an EC2 instance with the IP address

      ![image](https://github.com/user-attachments/assets/3cda27b2-ca99-4a64-8635-06d04a1d35b4)

      Due to inbound rules HTTP, the service (webapp/any backend app) running inside ec2 instance can be accessible from outside. If it is not configured, when the service is accessed, then it will give a timeout error.

      **HTTP CONFIGURED**
    
      ![image](https://github.com/user-attachments/assets/d97d9497-9faa-4697-86d8-6784846bebbc)
      


      Outbound: traffic going out of the EC2 instance. EC2 instance trying to access any api/site to get information.

