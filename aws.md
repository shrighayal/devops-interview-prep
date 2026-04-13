🔹 General Questions

1. What is AWS?
AWS (Amazon Web Services) is a cloud platform that provides services like computing (EC2), storage (S3), databases (RDS), networking, etc.

2. What is EC2?
EC2 (Elastic Compute Cloud) provides virtual servers in the cloud where you can run applications.

3. EC2 vs S3 vs RDS

EC2 → Virtual machine
S3 → Storage (objects/files)
RDS → Managed database

4. What is AMI?
Amazon Machine Image is a template used to launch EC2 instances.

5. Auto Scaling?
Automatically increases/decreases instances based on traffic.

6. Load Balancer?
Distributes traffic across multiple servers.

7. Public vs Private Subnet

Public → Internet access
Private → No direct internet

8. IAM?
Identity and Access Management for users, roles, permissions.

9. VPC?
Virtual Private Cloud = isolated network in AWS.

10. Scaling types

Vertical → increase size
Horizontal → add instances

🔹 Scenario-Based

1. EC2 not reachable?
Check:

Security group (port 22/80 open)
Instance running
Network ACL
Public IP

2. Highly available architecture?
Use:

Multiple AZ
Load balancer
Auto scaling

3. App slow?

Scale instances
Enable caching (CloudFront)
Optimize DB

4. Secure S3?

Block public access
Use IAM policies
Enable encryption

5. Instance crash?

Use Auto Scaling
Health checks

6. Migration to AWS?

Rehost (lift & shift)
Replatform
Refactor

7. High bill?

Check Cost Explorer
Remove unused resources

8. Secrets handling?

AWS Secrets Manager
Parameter Store

9. CI/CD in AWS?

CodePipeline + CodeBuild + CodeDeploy

10. Monitoring?

CloudWatch