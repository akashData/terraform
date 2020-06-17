# terraform
Task1: 

=> Have to create/launch Application using Terraform :

1. Create the key and security group which allow the port 80, 22.

2. Launch EC2 instance.

3. In this Ec2 instance use the key and security group which we have created in step 1.

4. Launch one Volume (EBS) and mount that volume into /var/www/html

5. The developer has uploaded the code into GitHub repo and other repo with some images.

6. Copy the GitHub repo code into /var/www/html.

7. Create an S3 bucket, and copy/deploy the images from GitHub repo into the S3 bucket and change the permission to public readable.

8 Create a Cloudfront using S3 bucket(which contains images) and use the Cloudfront URL to update in code in /var/www/html.
