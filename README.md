# Ambro van Wyk

**DevOps / Cloud Engineer** · Saldanha, South Africa · Remote-only

I build and secure AWS infrastructure for international clients — focused on cloud migrations, compliance automation, and microservice architecture on AWS.

## What I work with

- **AWS** — EC2, VPC (advanced subnetting, Transit Gateway), Lambda, API Gateway, EventBridge, RDS, S3, SQS/SNS, KMS, Secrets Manager, CloudFront, Route53, Elastic Beanstalk
- **IaC & CI/CD** — CloudFormation, CodePipeline, CodeBuild, CodeDeploy, CodeArtifact, CodeCommit
- **Security & compliance** — SecurityHub, AWS Config, CloudTrail, WAF, GuardDuty, Wazuh SIEM, self-hosted Sentry
- **Observability** — CloudWatch (Logs, Alarms, Log Insights), Chatbot + Slack, Lambda-based alert routing
- **Application / data** — PHP (WordPress, Eloquent, Swoole), MySQL, MongoDB, REST API design, TCP/IoT protocol handling
- **AI-assisted development** — Claude Code (Claude Opus 4.6) as daily pair-programmer, extending my effective language range beyond the Node.js / PHP / Python daily drivers

## Certifications

- AWS Certified DevOps Engineer – Professional (2025)
- AWS Certified SysOps Administrator – Associate (2023, current to 2028)
- AWS Certified Developer – Associate (2024, current to 2028)
- AWS Certified Cloud Practitioner (2021, current to 2027)
- ISO/IEC 27001 ISMS Lead Implementer — TrecCert (2024)

## Recent work

At **DevProx** (Aug 2021 – present):

- **Foundational AWS infrastructure** for an EU client — own the estate that every workload below runs on. Multi-VPC topology (QA + Prod) joined to the client office via Transit Gateway, governance via Budgets / Config / SecurityHub org-wide, centralised CloudWatch logging with Slack bridges, CI/CD on GitHub Actions with self-hosted runners alongside AWS-native pipelines, secrets in Secrets Manager with least-privilege IAM, and resilience via AWS Backup and cross-region replication.
- **Production OAuth 2.0 authorization server** for an EU client — designed and shipped the server on AWS serverless (SAM, 12 Lambdas, 8 DynamoDB tables, API Gateway, KMS) with a React + TypeScript admin dashboard. Ran a full RFC compliance programme against RFCs 6749 / 6750 / 7009 / 7517 / 7519 / 7636 / 7638 / 8414 (~190 requirements verified), and built scheduled AI-driven security reviews in GitHub Actions across five repos.
- **IoT telemetry microservice** for ~800 vehicle trackers — NLB + load-balanced `php-swoole` listeners + MongoDB + REST API. Designed a **dual-write migration strategy** that mirrored raw data to the legacy backend while building out the new pipeline, enabling safe incremental cutover instead of a big-bang switch.
- **Platform standardisation** for the same EU client — maintain a reusable Tina4 PHP reference template for spinning up new demo apps, plus a bridge layer of shared Lambda functions for Slack error reporting, Kubernetes log forwarding, self-hosted GitHub Actions runners, and ChatOps.
- **Cloud migration** of a complex PHP/WordPress + PHP/Eloquent/MySQL monolith from bare metal to AWS for an EU automotive leasing client — systematic cutover to EC2, then to cloud-native services; built observability, alerting, and security hardening from the ground up.
- **Compliance & detection engineering** for a US fintech — drove SecurityHub findings to closure and built CloudWatch Log Insights queries over WAF logs to catch real CIA threats, going beyond compliance checkboxes.

## Background

20+ years of technical work. Earlier career: industrial Electrical Technician and PLC programmer (Cape Transvaal Printers, Duferco Steel Processing) — fault-finding on high-value machinery where downtime cost thousands per minute. Reskilled into cloud 2019–2021 after a serious accident; now remote-first by necessity and by design.

## What I'm looking for

Open to remote-only **DevOps / Cloud / Platform Engineering** roles at scale-ups and enterprises. Comfortable across timezones — standard office hours or shifted to align with EU/US teams.

## Contact

- Email: ambro@ambrovanwyk.com
- LinkedIn: [abraham-van-wyk](https://www.linkedin.com/in/abraham-van-wyk-8216b4217/)
