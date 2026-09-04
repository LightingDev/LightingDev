# Hi, I'm LightingDev

Full-stack developer focused on production systems that stay correct under load — infrastructure as code, hardened backends, and CI pipelines that actually catch problems before they ship.

## What I build

**[whats](https://github.com/LightingDev/whats)** — WhatsApp commerce assistant *(private)*
A Docker-first monorepo: a Bun/Baileys WhatsApp edge, a PHP 8.6 + RoadRunner business-logic worker, and a Nuxt operator dashboard, backed by PostgreSQL (pgvector), Redis, RabbitMQ, and Meilisearch. AI-assisted catalog enrichment sits behind an explicit trust boundary — nothing customer-facing ships without owner approval.
`PHP` `TypeScript` `Bun` `PostgreSQL` `pgvector` `RabbitMQ` `Docker Compose`

**[laravel-aws-infrastructure](https://github.com/LightingDev/laravel-aws-infrastructure)** — Terraform on AWS *(private)*
ECS Fargate behind an ALB, RDS PostgreSQL, ElastiCache Redis, and S3, with remote state on S3 + DynamoDB. Applied once to a real AWS account — 116 managed resources created and cleanly destroyed. Gated locally and in CI by `fmt`, `validate`, `tflint`, `checkov`, and `gitleaks`.
`Terraform` `AWS ECS` `RDS` `ElastiCache` `GitHub Actions`

**[missionquest-backend](https://github.com/LightingDev/missionquest-backend)** — API backend *(private)*
PHP 8.4 on FrankenPHP, PostgreSQL, Redis, and Mercure for real-time updates. Fully OpenAPI-documented (300 schemas), enforced by PHPStan, Psalm, and Semgrep in CI.
`PHP 8.4` `FrankenPHP` `PostgreSQL` `Redis` `OpenAPI`

**[missionquest-android](https://github.com/LightingDev/missionquest-android)** — Android client *(private)*
Kotlin + Jetpack Compose, backed by baseline profiles for startup performance and Appium-driven end-to-end tests.
`Kotlin` `Jetpack Compose` `Appium`

## How I work

- **Security-first**: dependency, secret, container, and SAST scanning wired into every pipeline (Trivy, Grype, OSV-Scanner, Semgrep/OpenGrep, gitleaks, Checkov) — not bolted on after the fact.
- **Infrastructure as code**: environments are reproducible from source, not hand-configured.
- **Verify, don't assume**: changes get tested against a real running stack before they're called done, not just linted.

## Stack

`PHP` `TypeScript` `Kotlin` `Go` `Terraform` `PostgreSQL` `Redis` `Docker` `AWS` `GitHub Actions`

---
<!-- Add your own links below -->
📫 Reach me at — *(add your email / site / LinkedIn here)*
