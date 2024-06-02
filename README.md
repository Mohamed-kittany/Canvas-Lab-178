# Working with AWS Lambda

## Lab Overview

This lab involves deploying and configuring a serverless computing solution using AWS Lambda. The primary function of the Lambda setup is to generate a daily sales analysis report. This report is automatically compiled by fetching data from a database and then emailed to the specified recipients.

<img width="794" alt="lambda-activity-architecture" src="https://github.com/Mohamed-kittany/Canvas-Lab-178/assets/161580792/82a259fd-7efc-4876-a45e-8f91c8a5e3ba">


## Steps Involved

### 1. Database Setup
The database is hosted on an Amazon Elastic Compute Cloud (Amazon EC2) instance running a Linux, Apache, MySQL, and PHP (LAMP) stack.

### 2. Parameter Store Configuration
Store the database connection details securely using the Parameter Store feature of AWS Systems Manager, ensuring secure access and management of the database credentials.

### 3. Lambda Function Deployment
Deploy the AWS Lambda function that:
- Retrieves data from the configured database.
- Generates a sales analysis report.
- Sends the report via email on a daily schedule.

## Conclusion

This lab demonstrates the process of setting up a serverless AWS Lambda function for routine data processing tasks. It provides insights into integrating AWS Lambda with other AWS services for efficient and secure operations.
