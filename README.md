# Name : VISWAJITH LALITHRAM R.V
# REG.NO : 212224240187
---
# EX -4 - AUDITING CLOUD ACTIVITY USING AWS CLOUDTRAIL
---
# Aim
To enable and analyze AWS CloudTrail logs to audit user and resource activities in a cloud environment.
---
# Requirements
AWS Console access
CloudTrail service enabled
S3 bucket (for storing logs)
IAM permissions to view audit logs
---
# Procedure
## Step 1: Enable CloudTrail
Go to CloudTrail from AWS Console Click Trails > Create trail Name: CloudAuditTrail Apply trail to all regions Log events:

Management events: Read & Write
Data events: S3, Lambda (optional) Create or select an S3 bucket for log storage Enable CloudWatch Logs integration (optional)
## Step 2: Review Event History
Go to Event history Filter events by:

Username (IAM role or user)
Event name (e.g., CreateBucket, TerminateInstances)
Date/Time
Resource type (e.g., S3, EC2)
## Step 3: Download or Export Logs:
Use the Download CSV option to export logs Analyze logs in Excel/Sheets for reporting
---
# Output:

![Screenshot 2025-05-21 214759](https://github.com/user-attachments/assets/d8ade3fe-b91a-46d5-ab75-3230ad9634c9)


# Result
All AWS user activities, including volume creation, deletion, and permission changes, were successfully audited using CloudTrail.
