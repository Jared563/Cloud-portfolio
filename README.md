A curated collection of projects, documentation, and code showcasing hands-on skills in designing, deploying, and managing cloud solutions (AWS, Azure, GCP), demonstrating practical experience with services, automation (IaC, CI/CD), serverless, and security to prove capabilities beyond theory.


# Cloud Portfolio

## Project 1: Static Website on AWS

- Service: Amazon S3
- Region: ap-northeast-1
- Purpose: Host my cloud portfolio site

### What I did
- Created S3 bucket
- Enabled static website hosting
- Uploaded HTML file
- Made site publicly accessible   http://jaredpaul-cloud-portfolio.s3-website-ap-northeast-1.amazonaws.com

### Next steps
- Add CloudFront
- Add HTTPS
- Connect custom domain

### Update Day 2
- Added CloudFront distribution
- Enabled HTTPS
- Improved performance and security

**CloudFront URL:** dy9tgsv382a07.cloudfront.net


### Update Day 3
- Connected custom domain via Route 53
- Enabled HTTPS with ACM
- Implemented IAM user (least privilege)
- Added CloudWatch monitoring

## Project 2: EC2 Linux Web Server

- Service: Amazon EC2
- OS: Amazon Linux 2023
- Web Server: Nginx

### What I did
- Launched EC2 instance
- Connected via SSH
- Installed and configured Nginx
- Secured access with security groups

