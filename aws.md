# AWS Interview Questions & Answers

## 🔹 General Questions

### 1. What is AWS?
AWS (Amazon Web Services) is a cloud platform that provides on-demand computing services like servers, storage, and databases.

### 2. What is EC2?
EC2 (Elastic Compute Cloud) provides virtual servers in the cloud.

### 3. Difference between EC2, S3, RDS?
- EC2 → Virtual server
- S3 → Storage
- RDS → Managed database

### 4. What is IAM?
IAM is used to manage users, roles, and permissions securely.

---

## 🔹 Scenario-Based Questions

### 1. EC2 instance not reachable?
- Check Security Group (port 22/80)
- Check instance status
- Verify key pair
- Check NACL

### 2. High traffic issue?
- Enable Auto Scaling
- Use Load Balancer
- Use CloudWatch monitoring

### 3. AWS bill increased?
- Check billing dashboard
- Identify high-usage services
- Stop unused resources