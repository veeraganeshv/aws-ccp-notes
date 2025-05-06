# EC2: Deploy a static website
  - Search for EC2 in search box, Open EC2 service.
    
     ![image](https://github.com/user-attachments/assets/a081a410-01aa-4e1a-b190-c536e58a6f01)
  
  - Launch an instance by clicking the launch instance button.

      ![image](https://github.com/user-attachments/assets/8552478e-cac5-43d1-96b6-551abe828c2f)

  - Create New Instance > Give a name and tags (only when needed) to the instance > Choose Free Tier OS ex: Amazon Linux (Default> >  Select Instance type (Free tier : t2 micor)
  - Setup key pair for login setup from terminal like ssh utility.

      ![image](https://github.com/user-attachments/assets/07a8da4e-0d8d-42ed-ab19-834d4f954b9e)

      ![image](https://github.com/user-attachments/assets/124b7f52-0842-4aa5-998a-0ad5eea320e6)

    For windows 10 and above, Mac and Linux Os, select pem file type, for others (windows 7,8) use ppk file type.

  - We can leave the network settings as default settings with default security groups (lauinch-wizard-1) and we can also set our own security rules like allows ssh from anywhere rule.

      ![image](https://github.com/user-attachments/assets/ef522a21-6046-4b7f-99e7-be0f0b6a2af1)
  
    
  - You can start and stop instance from ec2 instances page. 


