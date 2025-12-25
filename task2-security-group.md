# Task 2 – Create Security Group in AWS Default VPC

## Task Description
Create a security group under the default VPC:

- Name: `xfusion-sg`
- Description: `Security group for Nautilus App Servers`
- Inbound Rules:
  - HTTP, port 80, source `0.0.0.0/0`
  - SSH, port 22, source `0.0.0.0/0`

## Steps Taken
1. Logged into AWS Console.
2. Navigated to **EC2 > Security Groups**.
3. Clicked **Create Security Group**.
4. Entered name and description.
5. Selected **default VPC**.
6. Added inbound rules for HTTP and SSH.
7. Clicked **Create Security Group**.
8. Verified the security group appears in the default VPC.

## Why Security Group?
- Acts as a virtual firewall controlling inbound traffic.
- HTTP rule allows web access; SSH rule allows server management.
- Ensures security and controlled access for AWS resources.
