AWS services used in the program

RDS: To store the data, our programme (udagram) first created a Postgres Relational Database Service.
Moreover, this is the database URL: database-1.cdfq2jlm7u6x.us-east-1.rds.amazonaws.com

S3 bucket: The frontend application then required Simple Storage Service for deployment, where all of the required files were uploaded. this is the S3 URL: http://moh-udagram.s3-website-us-east-1.amazonaws.com  

Elastic Beanstalk (EB) : Then we used the AWS Elastic Beanstalk service to transfer the build archive to an S3 bucket for the backend deployment.this is Beanstalk URL: http://udagram-api-dev.eba-empq9hcu.us-east-1.elasticbeanstalk.com
