Sagemaker XGBoost Implementation
This project demonstrates the implementation of XGBoost using Amazon SageMaker. It includes steps for creating an S3 bucket, uploading data, and mapping model paths.

Steps to Follow
1. Importing Necessary Libraries:
   
Make sure to import the required libraries for AWS S3 operations and SageMaker functionalities


2. Creating an S3 Bucket:
 
Create an S3 bucket to store your training and testing data. This can be done using the AWS Management Console or via the AWS SDK


3. Mapping Train and Test Data in S3:
   
Upload your training and test datasets to the S3 bucket. Ensure the paths are correctly mapped


4. Mapping the Path of the Models in S3

Specify the S3 path where your models will be stored after training

Usage:


(i)Set Up AWS Credentials: Ensure your AWS credentials are configured properly. You can set this up via the AWS CLI or environment variables.


(ii)Run the Script: Execute the provided script to start the training process. The script will use the specified S3 paths for data and model storage.


(iii)Monitor Training: Check the SageMaker console for the training job status and logs.


Dependencies:

(i)boto3

(ii)sagemaker


-->> Install dependencies using pip:


            "pip install boto3 sagemaker"


