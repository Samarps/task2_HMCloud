# Hybrid Multi Cloud Task2

>> Description of the task:
1. Create the key-pair and security group which allow the port 80.
2. Launch an EC2 instance. In this EC2 instance use the key and security group which we have created in step 1.
3. Launch one storage volume (EFS) and attach that volume into the EC2 instance launched & mount the directory.
4. Get the code uploaded by the developer in GitHub and copy the code in the /var/www/html folder for deployment.
5. Create S3 bucket, and copy/deploy the static images into the S3 bucket and change the permission to public readable.
6 Create a CloudFront using S3 bucket(which contains images) and use the CloudFront URL to update in code.
7. Launch the application for testing from the code itself.
