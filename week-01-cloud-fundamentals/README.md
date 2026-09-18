# Week 1: Cloud Computing Fundamentals & AWS Introduction

## Overview
This week focused on building a foundation in cloud computing before
working hands-on with AWS. I covered core cloud concepts, deployment
models, service models, and explored 10 key AWS services directly in
the AWS Management Console.

## What I Did

**1. Cloud Computing Basics**
Cloud computing means using computing services — storage, servers,
databases, software — over the internet instead of on local hardware.
Providers like AWS own and manage the infrastructure; you rent only
what you need and pay for actual usage.

**2. Cloud Deployment Models**
- **Public Cloud** — shared infrastructure managed by a third party (e.g. AWS, Azure, GCP); cheapest and easiest to start with
- **Private Cloud** — dedicated to a single organization for more control and security (e.g. banks, hospitals)
- **Hybrid Cloud** — a mix of both, keeping sensitive workloads private while running others publicly

**3. Cloud Service Models**
- **IaaS** — raw infrastructure (e.g. EC2, VPC); you manage the OS and apps
- **PaaS** — a managed platform to build on (e.g. Elastic Beanstalk, Lambda)
- **SaaS** — fully finished software, ready to use (e.g. Gmail, Dropbox)

**4. Explored 10 AWS Services in the Console**
Identified the location and purpose of each service, and documented
what it's used for:

| Service | Purpose |
|---|---|
| IAM | Controls who can access AWS resources and what they can do |
| EC2 | Virtual servers to run applications |
| S3 | Stores files, images, backups in the cloud |
| VPC | Private, secure network for AWS resources |
| RDS | Managed relational databases (MySQL, PostgreSQL, etc.) |
| Lambda | Runs code without managing servers |
| CloudWatch | Monitors resources and triggers alarms |
| Route 53 | DNS service that routes users to the right server |
| CloudFront | CDN that speeds up content delivery globally |
| DynamoDB | Fully managed, fast NoSQL database |

## Steps & Screenshots

![IAM console](images/iam-console.png)
*Locating IAM in the AWS Management Console.*

*(Add one screenshot per service you explored, each with a short caption — same pattern as above.)*

## Key Takeaways
- Understanding the different service models (IaaS/PaaS/SaaS) helped clarify how much responsibility AWS takes on versus the user, depending on the service
- Exploring the Console hands-on made the AWS service catalog feel far less overwhelming than reading about it
