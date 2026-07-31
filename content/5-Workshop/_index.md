---
title: "Workshop"
date: 2026-07-31
weight: 5
chapter: false
pre: " <b> 5. </b> "
---


# Build and Deploy a Serverless Todo Application on AWS

#### Overview

This workshop guides you through building and deploying a serverless Todo and Note web application on AWS. Users can register, manage their profiles, organize tasks with custom statuses and categories, save drafts automatically, apply custom filters, view statistics, import or export tasks, and upload private attachments.

The architecture separates the application into several service groups:
+ **Frontend & Authentication** - Store the static frontend in Amazon S3, deliver it through Amazon CloudFront, and use Amazon Cognito for account registration and authentication.
+ **API & Compute** - Expose protected HTTP endpoints through Amazon API Gateway and process application logic with AWS Lambda.
+ **Data & Storage** - Store user-owned application data in Amazon DynamoDB and store profile pictures and task attachments in a private Amazon S3 bucket.
+ **Monitoring & Permissions** - Collect API and function logs with Amazon CloudWatch and control service access with AWS IAM.

During deployment, you will choose the resource names and AWS Regions that suit your environment. The frontend obtains JWTs from Cognito and sends an access token to API Gateway. API Gateway validates the token before invoking Lambda, while Lambda communicates with DynamoDB, the attachment bucket, and Cognito administrative APIs when required.

#### Content

1. [Workshop overview](5.1-Workshop-overview)
2. [Prerequiste](5.2-Prerequiste/)
3. [Access S3 from VPC](5.3-S3-vpc/)
4. [Access S3 from On-premises](5.4-S3-onprem/)
5. [VPC Endpoint Policies (Bonus)](5.5-Policy/)
6. [Clean up](5.6-Cleanup/)