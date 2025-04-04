# AWS IAM Policies
  - IAM has many inbuilt policies
  - We can create our own policy as well
  - From Side menu Policies option it can be created.
  - Permission are made up of policies
  - ex: IAMReadOnlyAccess, AdminAccess
  - Policies can be edited as json or added from the list of apis

    Ex: Grant read and write access to Amazon S3 bucket objects policy

    ```
    {
    "Version": "2012-10-17",
    "Statement": [
        {
            "Sid": "ListObjectsInBucket",
            "Effect": "Allow",
            "Action": ["s3:ListBucket"],
            "Resource": ["arn:aws:s3:::bucket-name"]
        },
        {
            "Sid": "AllObjectActions",
            "Effect": "Allow",
            "Action": "s3:*Object",
            "Resource": ["arn:aws:s3:::bucket-name/*"]
        }
      ]
    }
   
    ```
