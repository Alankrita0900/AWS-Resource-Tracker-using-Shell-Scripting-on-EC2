Project Overview

This project is a Live DevOps automation project that tracks AWS resource usage using Shell Scripting and AWS CLI on a Linux EC2 instance. The script automatically fetches details of AWS services such as EC2 instances, S3 buckets, Lambda functions, and IAM users from a cloud environment.
The main goal of this project is to demonstrate real-time cloud automation, Linux scripting, and AWS CLI integration, which are essential skills for Cloud and DevOps roles.

Objectives
Deploy and configure an AWS EC2 Linux server
Configure AWS CLI using IAM user credentials
Develop a Shell Script to automate AWS resource tracking
Fetch and monitor AWS resources programmatically
Demonstrate real-time DevOps automation using Bash scripting

Tools and Technologies Used
Amazon Web Services (AWS)
EC2 (Elastic Compute Cloud)
IAM (Identity and Access Management)
AWS CLI (Command Line Interface)
Linux (Amazon Linux 2023)
Shell Scripting (Bash)
MobaXterm (SSH Client)
GitHub (Project Repository)
AWS Services Used
EC2 – For hosting the Linux server
IAM – For secure CLI access using access keys
S3 – For listing storage buckets
Lambda – For listing serverless functions

Project Architecture

IAM User (Access Keys)
↓
AWS CLI Configuration on EC2
↓
Shell Script (AWS Resource Tracker)
↓
AWS Services (EC2, S3, Lambda, IAM)
↓
Automated Resource Usage Output

Output

The script successfully displayed:
EC2 instance details (Instance ID, IP, Status)
List of S3 buckets
IAM users list
Lambda functions information
JSON formatted AWS resource data

Challenges Faced
Incorrect file execution syntax (.file.txt instead of ./file.txt)
Permission issues before using chmod
Filename mismatch during chmod command
Initial script execution errors
These were resolved by correcting permissions and proper execution commands.

Key Learnings
Hands-on experience with AWS EC2 and IAM
AWS CLI configuration and authentication
Linux command line and file permissions
Shell scripting for automation
Real-time DevOps workflow implementation
Cloud resource monitoring using CLI

Conclusion
The AWS Resource Tracker using Shell Scripting project successfully demonstrates end-to-end DevOps automation on a live AWS environment. 
It integrates AWS CLI, Linux, and Bash scripting to monitor cloud resources efficiently, showcasing practical skills in Cloud and DevOps engineering.

Real-World DevOps Use Case
This project simulates how DevOps engineers automate cloud infrastructure monitoring instead of manually checking AWS resources. 
Such scripts are used in production environments for auditing, monitoring, and automation of cloud services.
