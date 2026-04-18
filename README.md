# Serverless Notification System — SNS, DynamoDB & CloudWatch

## Project Overview
Built an event-driven serverless architecture on AWS using SNS for real-time notifications, DynamoDB for data persistence, and CloudWatch for monitoring and alarms. No servers to manage — fully managed services.

## Architecture
Event Trigger → SNS Topic → Email/SMS Notification
                   ↓
             DynamoDB (Data Store)
                   ↓
           CloudWatch Alarm (Monitoring)

## AWS Services Used
- Amazon SNS (Simple Notification Service)
- Amazon DynamoDB (NoSQL data storage)
- Amazon CloudWatch (Alarms + Logs)
- IAM Roles (Least-privilege access)

## What I Built
- SNS topic with email subscription for real-time alerts
- DynamoDB table with partition key for event data storage
- CloudWatch alarms to monitor DynamoDB read/write capacity
- IAM roles with least-privilege policy for each service

## Key Learnings
- Event-driven architecture patterns on AWS
- SNS vs SQS — when to use which
- DynamoDB partition key design for performance
- CloudWatch metrics and alarm threshold configuration

## Certification
AWS Certified Solutions Architect – Associate (SAA-C03)
