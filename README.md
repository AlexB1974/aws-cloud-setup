# aws-cloud-setup
Documentation and setup for a basic AWS cloud environment using Python and GitHub Pages.
# ☁️ AWS Cloud Setup – Alex

This repository documents the process of setting up a basic cloud environment using AWS services, Python, and GitHub Pages.

##  Technologies Used
- AWS IAM
- AWS CLI
- Amazon EC2 & S3
- Python (Boto3)
- GitHub & GitHub Pages

##  Live Demo
Coming soon...

---

##  Setup Overview

### 1. IAM User Creation
- Created IAM user with programmatic and console access
- Assigned policies: `AmazonEC2FullAccess`, `AmazonS3FullAccess`
- Stored credentials securely

### 2. AWS CLI Configuration
- Installed AWS CLI
- Configured credentials using `aws configure`
- Verified access with `aws s3 ls` and `aws ec2 describe-instances`

### 3. Python Integration
- Installed `boto3`
- Tested access to AWS services via Python scripts

### 4. GitHub Repository
- Created public repository
- Added documentation and scripts
- Enabled GitHub Pages for public access

---

## 📈 Future Improvements
- Automate EC2 deployment with Terraform
- Add monitoring with CloudWatch
- Secure access with IAM roles and MFA

##  Author
Alex – Stockholm, Sweden
