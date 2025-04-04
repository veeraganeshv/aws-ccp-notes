# AWS IAM Policies
  - IAM has many inbuilt policies
  - We can create our own policy as well
  - From Side menu Policies option it can be created.
  - Permission are made up of policies
  - Ex: IAMReadOnlyAccess, AdminAccess
  - Policies can be edited as json or added from the list of apis available
  - For an IAM user policies can be added,updated and deleted by admin

    Ex: Grant read and write access to Amazon S3 bucket objects policy
    
    Replace **bucket-name** with aws s3 bucketname
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
