# IAM: Users and Groups
  - IAM is Identity and Access Management Service. It's a global service.
  - The Root (Main Account) account created is the default account. It should not be shared or used.
  - Create Users and then use them as needed, assign them to groups, and those groups have the necessary permissions.
  - Users are people in the organization and can be grouped. Some users are also not in any group (not a best practice).
  - Users can also belong to multiple groups.
  - Groups only contain users, not other groups.
  - ex: Group: Developers -> Anna, Carter, Sid  | Group: Operations -> Blake, Levi, | Group: Testers -> Zoro, Luffy | Group: Managers -> Zoro, Anna, Levi
# IAM: Permissions
  - Users or Groups can be assigned with a json document called policies
  - These policies contain the permissions of the users. You should not allow every user to do everything. That's why policies exists.
  - Follow the Least Privilege Principle: Give only the needed permissions user. Don't give more permissions to a user.

 Ex: Policy
  
  ![image](https://github.com/user-attachments/assets/4f07e0c1-7c14-4343-962a-3dfbe7ea894f)

