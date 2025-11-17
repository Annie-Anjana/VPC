# VPC
## Ex-4 Virtual Private Cloud (VPC)
## Name: ANNIE ANJANA A
## Register Number: 212224040025
## AIM
To study the steps involved in setting up a private cloud using AWS or Microsoft Azure platforms and explore its core features and services.

## PROCEDURE
Step 1: Create a Cloud Account

Sign up for an account on AWS or Microsoft Azure.

Complete verification using your email and credit card.

Log in to the AWS Management Console or Azure Portal.

Step 2: Set Up a Virtual Private Cloud (VPC / VNet)

For AWS:

Go to VPC Dashboard → Click Create VPC.

Enter a name and specify the CIDR block (e.g., 10.0.0.0/16).

For Azure:

Navigate to Virtual Network (VNet) in Azure Portal.

Create a VNet by defining name, region, and address space.

Step 3: Configure Subnets and Routing

Create Public and Private Subnets within the VPC or VNet.

Configure Route Tables to manage traffic between subnets and the internet.

Attach an Internet Gateway to the public subnet for external connectivity.

Keep private subnets isolated for internal communication.

Step 4: Create and Launch Instances

Launch an EC2 Instance (AWS) or Virtual Machine (Azure) within your VPC/VNet.

Choose an appropriate AMI or OS Image (Ubuntu, Amazon Linux, Windows).

Assign each instance to the respective subnet (Public/Private).

Step 5: Security Configuration

Create Security Groups (AWS) or Network Security Groups (NSGs) (Azure).

Configure inbound/outbound rules:

Allow SSH (22) for Linux access.

Allow RDP (3389) for Windows access.

Allow HTTP (80) for web servers.

Ensure private subnet instances are not directly accessible from the internet.

Step 6: Storage and Networking

Attach Elastic Block Store (EBS) volumes or Azure Managed Disks.

Configure Load Balancers and NAT Gateways if needed.

Verify DNS, IP allocation, and subnet connectivity.

Step 7: Testing

Use ping, ssh, or RDP to check connectivity between instances.

Test public instance access through the internet.

Confirm internal communication between private instances.

## OUTPUT

<img width="967" height="561" alt="Screenshot 2025-11-17 141541" src="https://github.com/user-attachments/assets/214105b8-d4f4-454d-a7c7-7212420fa199" />

<img width="972" height="560" alt="Screenshot 2025-11-17 141623" src="https://github.com/user-attachments/assets/4db68b25-9cf6-43d6-ab7a-7c8b7bfe662a" />

<img width="965" height="563" alt="Screenshot 2025-11-17 141642" src="https://github.com/user-attachments/assets/5b27f64b-ff34-47ac-ac56-d98438636e7b" />

<img width="965" height="559" alt="Screenshot 2025-11-17 141705" src="https://github.com/user-attachments/assets/8ff3a7da-4d3e-4a0b-8983-9628817b0bfc" />


## RESULT
A private cloud environment was successfully created using the AWS/Azure platform.

Core components such as VPC/VNet, Subnets, Instances, and Security Groups were configured.

The setup was tested and verified for internal communication and external access as per the configuration.
