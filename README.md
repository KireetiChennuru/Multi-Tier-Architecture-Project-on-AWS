# Designing a Serverless Web Backend on AWS

## Overview

This project demonstrates a multi-tier architecture using various AWS services. The architecture includes the use of Amazon SQS, Amazon SNS, API Gateway, DynamoDB, IAM Policies and Roles, and Lambda functions. The purpose of this project is to showcase the integration of these services to create a scalable and reliable application.

## Architecture Diagram

![Cloud Architecture](https://live.staticflickr.com/65535/53899875198_0486ec367c_k.jpg)

## AWS Services Used

### Amazon SQS (Simple Queue Service)
**Purpose**: To decouple the components of a distributed application.

![Amazon SQS Queue](https://live.staticflickr.com/65535/53886982255_393c99f84d_k.jpg)

### Amazon SNS (Simple Notification Service)
**Purpose**: To send notifications from the application.

![Amazon SNS](https://live.staticflickr.com/65535/53885650482_2f1fadd921_k.jpg)

### API Gateway
**Purpose**: To create and publish APIs.

![API Gateway](https://live.staticflickr.com/65535/53886790623_00a699f698_k.jpg)

### DynamoDB
**Purpose**: To store application data.

![DynamoDB Table](https://live.staticflickr.com/65535/53885650397_3153e85321_k.jpg)

### IAM Policies
**Purpose**: To manage permissions for various AWS services.

![IAM Policies](https://live.staticflickr.com/65535/53885650387_7c2a069ee1_k.jpg)

### IAM Roles
**Purpose**: To assign permissions to AWS services.

![IAM Roles](https://live.staticflickr.com/65535/53886564001_a43b634abd_k.jpg)

### AWS Lambda
**Purpose**: To run backend code without provisioning or managing servers.

![POC - Lambda - 1](https://live.staticflickr.com/65535/53885650312_418ad18ee6_k.jpg)
![POC - Lambda - 2](https://live.staticflickr.com/65535/53886563956_a09ee93d0a_k.jpg)
![Lambda Test Event Successful](https://live.staticflickr.com/65535/53886563981_9636fddf81_k.jpg)
![Configure Test Event](https://live.staticflickr.com/65535/53886790598_01fddf1bb4_k.jpg)

## Step-by-Step Guide

### Setting Up the Environment
- Create an IAM role with the necessary permissions.
- Set up the DynamoDB table.
- Create an SQS queue.
- Create an SNS topic.
- Configure the API Gateway.

### Deploying the Lambda Function
- Write the Lambda function code.
- Create a Lambda function in the AWS Management Console.
- Attach the IAM role to the Lambda function.
- Test the Lambda function.

### Connecting the Components
- Set up the API Gateway to trigger the Lambda function.
- Configure the Lambda function to interact with DynamoDB, SQS, and SNS.
- Test the end-to-end flow.

## Testing and Validation
- Testing was a critical phase in this project. I meticulously tested each component and the integrated flow to ensure smooth operation. The tests included validating data flow through DynamoDB, message queuing in SQS, notifications via SNS, and API calls through API Gateway triggering Lambda functions.

## Conclusion
- This project was a fantastic learning experience that underscored the power and flexibility of AWS services. From handling backend operations with Lambda to managing data with DynamoDB and ensuring efficient communication with SQS and SNS, each service played a crucial role in the overall architecture.

## Key Takeaways
- Decoupling Components: SQS and SNS are invaluable for creating loosely coupled systems.
- Serverless Computing: AWS Lambda offers a scalable and cost-effective solution for running code.
- Effective Permission Management: IAM policies and roles are essential for secure and efficient access control.
- API Management: API Gateway provides a robust platform for creating and managing APIs.

## Author

- Kireeti Chennuru | www.linkedin.com/in/kireeti-chennuru
