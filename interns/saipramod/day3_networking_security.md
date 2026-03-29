# Day 3 — Networking & Security in Cloud

## 🌐 Virtual Private Cloud (VPC)
- A **VPC** is your private network in the cloud.
- You can define your own IP range, subnets, and routing.
- **Steps:**
  1. Go to VPC → Create VPC → Choose IPv4 CIDR (e.g. 10.0.0.0/16)
  2. Add public and private subnets.
  3. Attach an Internet Gateway to the public subnet.
  4. Create a route table and associate it with the subnet.

---

## 🧱 Subnets
- Divide your VPC for better traffic management.
- **Public Subnet:** Has internet access (through IGW).  
- **Private Subnet:** No direct internet; used for databases, internal apps.

---

## 🔐 Security Groups
- Virtual firewalls controlling inbound/outbound traffic.
- **Example:**
  - Allow SSH (22) from your IP.
  - Allow HTTP (80) for web access.
  - Deny all other ports by default.

---

## 🔑 Network Access Control Lists (NACLs)
- Act at the subnet level.
- Provide **stateless** packet filtering.
- Used for additional security beyond security groups.

---

## 🧭 Load Balancer
- Distributes traffic across multiple instances.
- Ensures high availability and fault tolerance.
- Example: Create **Application Load Balancer** for HTTP traffic.

---

## 🧰 Tools Used
| Tool | Purpose |

|------|----------|
| VPC | Private network setup |
| Security Groups | Instance-level firewall |
| NACL | Subnet-level firewall |
| Load Balancer | Traffic distribution |

---

## ✅ Deliverables
- Screenshot of custom VPC.
- Screenshot of security group inbound rules.
- Screenshot of Load Balancer dashboard.
