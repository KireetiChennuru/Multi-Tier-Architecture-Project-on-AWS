# Multi-Tier Architecture Project on AWS

## Overview

This project demonstrates a multi-tier architecture using various AWS services. The architecture includes the use of Amazon SQS, Amazon SNS, API Gateway, DynamoDB, IAM Policies and Roles, and Lambda functions. The purpose of this project is to showcase the integration of these services to create a scalable and reliable application.

## Architecture Diagram

![Architecture Diagram](link-to-architecture-diagram)

## AWS Services Used

### Amazon SQS (Simple Queue Service)
**Purpose**: To decouple the components of a distributed application.

![Amazon SQS Queue](path-to/Amazon-SQS-Queue.jpg)

### Amazon SNS (Simple Notification Service)
**Purpose**: To send notifications from the application.

![Amazon SNS](path-to/Amazon-SNS.jpg)

### API Gateway
**Purpose**: To create and publish APIs.

![API Gateway](path-to/API-Gateway.jpg)

### DynamoDB
**Purpose**: To store application data.

![DynamoDB Table](path-to/DynamoDB-Table.jpg)

### IAM Policies
**Purpose**: To manage permissions for various AWS services.

![IAM Policies](path-to/IAM-Policies.jpg)

### IAM Roles
**Purpose**: To assign permissions to AWS services.

![IAM Roles](path-to/IAM-Roles.jpg)

### AWS Lambda
**Purpose**: To run backend code without provisioning or managing servers.

![POC - Lambda - 1](path-to/POC-Lambda-1.jpg)
![POC - Lambda - 2](path-to/POC-Lambda-2.jpg)
![Lambda Test Event Successful](path-to/Lambda-Test-Event-Successful.jpg)
![Configure Test Event](path-to/Configure-Test-Event.jpg)

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

## Code

- Include any relevant code snippets or links to the full code files in your repository.

## Testing and Validation

- Describe the testing process.
- Include any screenshots or logs showing successful execution.

## Conclusion

- Summarize the key points of the project.
- Mention any challenges faced and how they were overcome.

## References

- List any references or resources used during the project.

## Author

- Provide your name and contact information (optional).
