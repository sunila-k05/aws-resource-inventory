# AWS Cloud Resource Inventory (Shell Script)

This project automates listing AWS resources using AWS CLI.

## How it works:
This script accepts 2 inputs:
1) AWS Region
2) AWS Service name

Example:
./aws_resource_list.sh ap-south-1 ec2

This will list all EC2 instances in the Mumbai region.

## Why this project is useful?
Instead of going to AWS console and checking each service manually,
DevOps engineers can run this one script to get all resources quickly.
