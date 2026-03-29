# Day 2 — AWS Core Services

## 🖥️ EC2 (Elastic Compute Cloud)
- Virtual machine service on AWS.
- You can choose OS, CPU, and storage.
- **Steps:**
  1. Go to EC2 → Launch Instance.
  2. Select Amazon Linux 2 AMI.
  3. Choose `t2.micro` (Free Tier).
  4. Configure Security Group → Allow SSH (22) and HTTP (80).
  5. Launch and connect using SSH.

---

## 🗂️ S3 (Simple Storage Service)
- Object-based storage for any file type.
- **Steps:**
  1. S3 → Create Bucket (name: `saipramod-bucket`).
  2. Keep default region.
  3. Upload a sample file.
  4. (Optional) Make file public for static hosting.

---

## 🔐 IAM (Identity and Access Management)
- Controls users, groups, and permissions.
- **Steps:**
  1. IAM → Users → Add user.
  2. Choose Programmatic Access.
  3. Attach “AmazonS3FullAccess” policy.
  4. Download access keys.

---

## ✅ Summary
| Service | Purpose | Example Use |
|----------|----------|-------------|
| EC2 | Run virtual servers | Web apps |
| S3 | Store files | Backups |
| IAM | Manage access | Roles & users |

---

## 📸 Deliverables
- Screenshot of EC2 instance (running).  
- Screenshot of S3 bucket with uploaded file.  
- Screenshot of IAM user creation.
