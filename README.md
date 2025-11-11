# AWS Cloud Resource Inventory Automation using Shell Script

## Objective
Automatically list AWS cloud resources across multiple services using a single Bash script, instead of manually checking each service inside the AWS Console.

##  Tools Used
- AWS EC2 (Ubuntu)
- AWS CLI v2
- Linux Shell Scripting
- IAM user (ReadOnlyAccess)

##  Description
This script takes **2 inputs**:

1) AWS Region  
2) AWS Service Name  

Based on this, it calls AWS CLI and prints all resources for that service.

### Supported AWS Services
- EC2
- S3
- IAM
- VPC
- CloudFront
- CloudWatch
- CloudFormation
- Lambda
- SNS
- SQS
- DynamoDB
- EBS
- Route53

---

## Sample Results

| Service | Command | Output Summary |
|---------|---------|----------------|
| EC2 | `./aws_resource_list.sh ap-south-1 ec2` | Lists running EC2 instances |
| S3 | `./aws_resource_list.sh ap-south-1 s3` | Lists S3 buckets |
| IAM | `./aws_resource_list.sh ap-south-1 iam` | Lists IAM users |

---

## Conclusion
Using this shell script, we can **automate AWS resource inventory** without opening AWS console.

This saves time and helps DevOps engineers to **quickly audit clou**
