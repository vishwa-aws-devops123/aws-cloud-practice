# Amazon EC2 Basics

## What is EC2?

Amazon EC2 (Elastic Compute Cloud) is a virtual server service provided by AWS.

## Common Uses

- Host applications
- Run Linux servers
- Production environments
- Testing environments

## Connecting to EC2

Using SSH:

```bash
ssh -i mykey.pem ec2-user@public-ip
```

## Components

- Instance
- AMI
- Key Pair
- Security Group
- EBS Volume

## Interview Answer

EC2 is a virtual server service in AWS. I can connect to a Linux EC2 instance using SSH, a key pair, and the instance public IP address.
