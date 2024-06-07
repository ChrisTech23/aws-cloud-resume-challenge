Static Website Deployment using AWS Services
This repository contains the code and configuration for deploying a static website using various AWS services.

Table of Contents
Overview
AWS Services Used
Setup
Contributing
License
Overview
This repository serves as a guide for deploying a static website using AWS services such as AWS CloudFront, Certificate Manager, AWS Lambda, DynamoDB, GitHub Actions, and Terraform.

AWS Services Used
AWS CloudFront:

Utilized as a content delivery network (CDN) to distribute the static website's content globally with low latency.
Certificate Manager:

Used to manage SSL/TLS certificates for secure communication between clients and the static website.
AWS Lambda:

Employed for serverless compute functions, enhancing the static website's functionality.
DynamoDB:

Utilized as a NoSQL database for any dynamic data associated with the static website.
GitHub Actions:

Integrated for continuous integration and deployment (CI/CD) of changes made to the static website's codebase.
Terraform:

Infrastructure as Code (IaC) tool used to provision and manage AWS resources required for deploying the static website.
Setup
Follow the steps below to deploy your static website using the mentioned AWS services:

Configure AWS Services:

Set up AWS CloudFront distribution for your static website.
Manage SSL/TLS certificates using Certificate Manager for secure communication.
Implement any serverless functionality using AWS Lambda.
Set up DynamoDB for any dynamic data storage requirements.
Implement CI/CD Pipeline:

Utilize GitHub Actions for automating the deployment process of your static website.
Infrastructure Provisioning:

Use Terraform to define and provision the necessary AWS resources for hosting your static website.
Deployment:

Deploy your static website using the configured AWS services and infrastructure.
Contributing
Contributions to this repository are welcome! If you have any suggestions, improvements, or feature requests, feel free to open an issue or submit a pull request.



