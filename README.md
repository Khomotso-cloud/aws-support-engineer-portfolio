# AWS VPC Architecture Project

##  Overview
Built a secure AWS VPC with public and private subnets to simulate a real-world cloud environment.

##  Architecture
- VPC (10.0.0.0/16)
- Public Subnet (10.0.1.0/24)
- Private Subnet (10.0.2.0/24)
- Internet Gateway
- NAT Gateway

## Implementation Steps
1. Created VPC and subnets
2. Configured Internet Gateway
3. Set up public route table
4. Created NAT Gateway for private subnet
5. Configured private routing

## Testing
- SSH into public EC2 ✅
- Access private EC2 via bastion host ✅
- Private EC2 internet access via NAT ✅

## 📸 Screenshots


## Key Learnings
- Difference between public and private subnets
- Importance of route tables
- NAT Gateway enables outbound internet for private instances
