## What is Cloud Security?

- Protects cloud resources, data, and applications from threats.

- AWS uses a Shared Responsibility Model:

        AWS: Security of the cloud (hardware, networking, physical data centers).

        Customer: Security in the cloud (data, applications, IAM, OS configurations).

## Core AWS Security Services

## AWS Identity & Access Management (IAM)

- Control who can access AWS resources.
- Concepts: Users, Groups, Roles, Policies.
- Best practice: Least privilege access.
- Supports MFA (Multi-Factor Authentication).

## AWS Shield

- DDoS protection.
- Standard: Free, protects against common DDoS attacks.
- Advanced: Paid, real-time metrics, 24/7 support.

## AWS Web Application Firewall (WAF)

- Protects apps from web attacks (SQL injection, XSS).
- Works with CloudFront, ALB, API Gateway.
- Customizable rules & rate-limiting.

## AWS GuardDuty

- Threat detection service.
- Monitors: VPC flow logs, CloudTrail logs, DNS logs.
- Detects suspicious activity like compromised EC2 or unauthorized API calls.

## AWS CloudTrail

- Records all API activity in your AWS account.
- Helps with auditing, compliance, and investigation.

## Best Practices

- Enable MFA for all accounts.
- Use IAM roles instead of long-term credentials.
- Encrypt sensitive data at rest and in transit.
- Enable CloudTrail and monitor logs.
- Regularly audit permissions and policies.

I understood that cloud security is shared responsibility, requiring vigilance on identity, data, network, and application levels. Implementing monitoring, encryption, and access control is vital to protect workloads effectively.

Implement defense-in-depth: multiple layers of security (network, application, data).
