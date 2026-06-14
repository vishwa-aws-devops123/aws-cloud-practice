# Security Groups

## What is a Security Group?

A Security Group acts like a virtual firewall for AWS resources.

## Controls

- Inbound Traffic
- Outbound Traffic

## Example

Allow SSH:

Port: 22

Source:

```text
your-ip-address
```

Allow Web Traffic:

```text
80 (HTTP)
443 (HTTPS)
```

## Interview Answer

A Security Group acts like a firewall and controls incoming and outgoing traffic to AWS resources such as EC2 instances.
