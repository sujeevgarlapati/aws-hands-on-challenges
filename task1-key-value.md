# Task X – Create EC2 Key Pair in AWS

## Task Description
Create a key pair for EC2 instances under default VPC.

## Steps Taken
1. Logged into AWS Console.
2. Navigated to **EC2 > Key Pairs**.
3. Searched for existing key pairs to avoid duplicates.
4. Clicked **Create Key Pair**.
5. Entered name: `nautilus-key`
6. Selected key type: RSA
7. Selected private key format: `.pem`
8. Clicked **Create Key Pair** and downloaded the `.pem` file.
9. Verified the key pair appears in EC2 > Key Pairs.

## Notes
- Key pairs are used for secure SSH access to EC2 instances.
- Keep the `.pem` file safe; AWS does not store it.
- This key pair can be associated with instances launched in the default VPC.

