# Amazon S3 Bucket Creation with Boto3

This Python script demonstrates how to use the Boto3 library to create an Amazon S3 bucket with a specific configuration. In this example, we'll create a private bucket in the `ap-south-1` region named `ambalkar-neelay`.

# Prerequisites

Before running the script, make sure you have the following set up:

1. AWS Account: You'll need an AWS account with the necessary permissions to create S3 buckets.
2. Python: Ensure that you have Python installed on your system.
3. Boto3 Library: Install the Boto3 library using pip


# Preview

https://github.com/neelay-16/S3-Bucket/assets/135517502/193ae3bd-48ca-4016-be7f-1b8f178ca835


# Description

Here, I create an S3 client object named bucket. This object will be used to make API calls to interact with the S3 service.

![image](https://github.com/neelay-16/S3-Bucket/assets/135517502/7e6257b2-c5cf-4b98-8387-4091655ef714)


This code block creates an S3 bucket with the following parameters:
Bucket: This parameter specifies the name of the bucket you want to create. In this case, the bucket will be named 'ambalkar-neelay'.
ACL: This parameter specifies the Access Control List (ACL) for the bucket. In this case, it's set to 'private', which means that only the bucket owner has access to the bucket by default. Other AWS users or roles will not have access unless explicitly granted.
CreateBucketConfiguration: This is an optional parameter that specifies the bucket's configuration. In this case, it sets the location constraint to 'ap-south-1'. This means the bucket will be created in the Asia Pacific (Mumbai) region.

![image](https://github.com/neelay-16/S3-Bucket/assets/135517502/6869892e-8327-4ee7-9600-887e69405d2a)


This will create the specified S3 bucket with the provided configuration.


# Customize

Feel free to customize the script according to your specific needs. You can change the bucket name, ACL, and region based on your requirements.


# Acknowledgments

[Boto3 Documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/index.html) for detailed information on using Boto3 with AWS services.



