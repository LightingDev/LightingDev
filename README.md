# Hasan Raad

I build production systems that stay correct under load. Infrastructure as code, hardened backends, and CI pipelines that catch real problems before they ship.

## What I build

**[whats](https://github.com/LightingDev/whats)**: WhatsApp commerce assistant *(private)*
A Docker-first monorepo with three services: a Bun and Baileys WhatsApp edge, a PHP 8.6 worker on RoadRunner, and a Nuxt dashboard. It runs on PostgreSQL with pgvector, Redis, RabbitMQ, and Meilisearch. AI enriches the product catalog, but nothing reaches a customer until the owner approves it.
`PHP` `TypeScript` `Bun` `PostgreSQL` `pgvector` `RabbitMQ` `Docker Compose`

**[laravel-aws-infrastructure](https://github.com/LightingDev/laravel-aws-infrastructure)**: Terraform on AWS *(private)*
Terraform for ECS Fargate behind an ALB, RDS PostgreSQL, ElastiCache Redis, and S3. Remote state lives in S3 and DynamoDB. I applied it once to a real AWS account: it created and cleanly destroyed 116 resources. Local and CI checks run fmt, validate, tflint, checkov, and gitleaks before any change lands.
`Terraform` `AWS ECS` `RDS` `ElastiCache` `GitHub Actions`

**[missionquest-backend](https://github.com/LightingDev/missionquest-backend)**: API backend *(private)*
PHP 8.4 on FrankenPHP, with PostgreSQL, Redis, and Mercure for real-time updates. The API has 300 OpenAPI schemas. PHPStan, Psalm, and Semgrep check every change in CI.
`PHP 8.4` `FrankenPHP` `PostgreSQL` `Redis` `OpenAPI`

**[missionquest-android](https://github.com/LightingDev/missionquest-android)**: Android client *(private)*
Kotlin and Jetpack Compose. Baseline profiles speed up app startup. Appium runs the end-to-end tests.
`Kotlin` `Jetpack Compose` `Appium`

## How I work

- **Security first.** Every pipeline scans dependencies, secrets, containers, and code: Trivy, Grype, OSV-Scanner, Semgrep, gitleaks, Checkov. It runs from day one, not after something goes wrong.
- **Infrastructure as code.** Every environment builds from source. Nothing gets hand-configured.
- **Verify, don't assume.** I test changes against a real running stack, not just a linter.

## Stack

`PHP` `TypeScript` `Kotlin` `Go` `Terraform` `PostgreSQL` `Redis` `Docker` `AWS` `GitHub Actions`

---
📫 [LinkedIn](https://www.linkedin.com/in/0hasan-raad/) · [hasan-raad@bk.ru](mailto:hasan-raad@bk.ru) · [automasterpro.net](https://automasterpro.net)
