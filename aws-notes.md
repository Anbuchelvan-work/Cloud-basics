# AWS Notes — Day 1

## Global Infrastructure
- Regions
- Availability Zones
- Edge Locations

## Core Services
- EC2 (Virtual Servers)
- S3 (Object Storage)
- IAM (Identity & Access)
- VPC (Networking)

## Notes
- Everything in AWS is built on top of regions and AZs.
- IAM controls who can do what inside AWS.

## Amazon S3 (Simple Storage Service)

- Object storage service
- Stores data as **objects** inside **buckets**
- Buckets must have globally unique names
- Supports versioning, lifecycle policies, encryption
- Common use-cases: backups, websites, logs, media

### S3 Storage Classes
- S3 Standard
- S3 Intelligent-Tiering
- S3 Standard-IA (Infrequent Access)
- S3 One Zone-IA
- S3 Glacier Instant Retrieval
- S3 Glacier Deep Archive

### Notes
- S3 is NOT a file system like EBS; it is object storage.
- Buckets live inside a region.
