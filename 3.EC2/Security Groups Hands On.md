# Security Groups Hands-On working
  - The security tab for an instance is available in the instance details, and we can refer to the security rules and its details of that instance. It contains inbound and outbound rules of that instance.

    ![image](https://github.com/user-attachments/assets/83fa469c-f4b1-4d42-804d-4fd2cfeec4e0)

  - The Security group button available from the side menu shows the full list of security groups available for all the instances. We can select groups and view security group rules associated with that group.

    ![image](https://github.com/user-attachments/assets/9263c3cc-8f3c-40e8-b676-217eb8729a65)

  - For every security group created, there is a security group id created and used also an identifier.

    ![image](https://github.com/user-attachments/assets/2bec4f8b-7b46-444f-8c48-546492a83c64)

  - There are inbound and outbound rules associated to every security group.

      **Inbound**: traffic coming into the EC2 instance. ex: someone trying to access an EC2 instance with the IP address

      ![image](https://github.com/user-attachments/assets/3cda27b2-ca99-4a64-8635-06d04a1d35b4)

      Due to the inbound rule **HTTP**, the service (webapp/any backend app) running inside ec2 instance can be accessed from anywhere outside. If it is not configured, and when the service is accessed, it will give a timeout error.

      **HTTP CONFIGURED**
    
      ![image](https://github.com/user-attachments/assets/d97d9497-9faa-4697-86d8-6784846bebbc)
      
      **Website accessible**

      ![image](https://github.com/user-attachments/assets/7135aaca-e5ff-452a-b22c-d23a2e7293c0)

      **HTTP REMOVED** (Updated the inbound rules: Deleted the existing rule and clicked save rules)

      ![image](https://github.com/user-attachments/assets/02e14419-62fd-40e0-925e-46845a6f0515)
      
      **WEBSITE TIMEOUT ERROR (KEEPS ON LOADING)**

      ![image](https://github.com/user-attachments/assets/101b7003-6660-49bf-b01a-9506ccb192f2)

      **CONFIGURE HTTP INBOUND RULE**

      **TYPE UPDATED**

      ![image](https://github.com/user-attachments/assets/1bb90d8b-71b4-4c9f-9c99-b9166127d4a6)

      **IPV4 Updated**
      
      ![image](https://github.com/user-attachments/assets/540ec79c-4106-476b-abb6-bcfeee882e14)

      **Save Rules**

      ![image](https://github.com/user-attachments/assets/a4737397-f222-405a-846c-7f9aeecfb27e)

      ![image](https://github.com/user-attachments/assets/83a52a26-d3a3-4746-9a65-1c09e0fb9dc2)

      ![image](https://github.com/user-attachments/assets/dd62b39a-8d3f-4ae7-a683-a7b1979dfb8c)

      **WEBSITE ACCESSIBLE AGAIN**

      ![image](https://github.com/user-attachments/assets/7c3d1397-3f1d-4e08-9539-8f9bc7516aa5)

      Likewise, we can add many inbound rules to a security group. Ex: Adding HTTP Rule to the inbound rules.

      ![image](https://github.com/user-attachments/assets/e74b1f81-0cbc-4d18-a311-b9c2f1463c70)





      **Outbound**: traffic going out of the EC2 instance. EC2 instance trying to access any api/site to get information.

