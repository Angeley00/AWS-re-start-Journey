# What is Cloud Computing?
-The delivery of IT resources (compute, storage, databases, networking, etc.) over the internet on a pay-as-you-go basis.

# Key benefits: 
- On-demand
- scalable
- elastic
- cost-efficient
- global reach.

# Cloud Models
- Public Cloud: Services delivered over the internet (e.g., AWS, Azure, GCP).
- Private Cloud: Dedicated infrastructure for one organization.
- Hybrid Cloud: Mix of on-prem + cloud.

# AWS Compute Services

# Amazon EC2 (Elastic Compute Cloud)
- Virtual servers in the cloud.
- Choose instance types based on workload.
- Pricing: On-Demand, Reserved, Spot, Dedicated.
- Supports Auto Scaling + Load Balancing.

# AWS Lambda
- Serverless compute (no servers to manage).
- Runs code only when triggered → pay for execution time.
- Event-driven (e.g., S3 upload, API call, DynamoDB stream).

# Amazon ECS (Elastic Container Service)
- Run and manage Docker containers.
- Works with Fargate (no servers) or EC2.

## AWS Global Infrastructure

- Regions → Physical locations worldwide.
- Availability Zones (AZs) → Multiple isolated data centers within a region.
- Edge Locations → For content delivery (Amazon CloudFront).
- Local Zones & Wavelength Zones → For low-latency computing near users.

