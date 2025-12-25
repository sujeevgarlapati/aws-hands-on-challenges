# Task 3 – Create Subnet in AWS Default VPC

## Task Description
Create a subnet named `nautilus-subnet` under the default VPC.

## Steps Taken
1. Logged into AWS Console.
2. Navigated to **VPC > Subnets**.
3. Clicked **Create Subnet**.
4. Entered details:
   - Subnet name: `nautilus-subnet`
   - VPC: Default VPC
   - IPv4 CIDR block: `172.31.48.0/24` *(non-overlapping)*
   - Availability Zone: let AWS select
5. Clicked **Create Subnet**.
6. Verified subnet creation.

## Why Subnet?
- Divides the VPC into smaller network segments for better resource management.
- Defines boundaries for routing, security, and isolation.
- Essential for deploying applications incrementally in AWS.

