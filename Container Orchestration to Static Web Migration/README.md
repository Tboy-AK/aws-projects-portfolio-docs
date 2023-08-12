# Container Orchestration to Static Web

This project was aimed at migrating static web applications from ECS and EKS to CloudFront through S3

## AWS Services

- Amazon ECS
- Amazon CloudFront
- Amazon S3

## Other Resources
- Bitbucket pipeline

## Advantages
- Cost optmization: S3 storage is cheap. CloudFront distributions allow free requests up to millions every month. Requests are cached, so S3 retrieval cost is significantly reduced.
- Security: Security headers and WAF
- Caching: Regional and Global.
- Speed: Could promote faster responses.

## Challenges
- Dynamic values per environment: E.g. API URLs between development, staging and production.
- Security credentials: E.g. tokens
