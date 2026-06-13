# Hi, I'm Odon — Platform & DevSecOps Engineer 🧜🏽‍♂️

Welcome to my engineering portfolio. Below is a breakdown of my cloud architecture systems mapped directly to core operational pillars:

### 🏰 1. Kubernetes Orchestration & IaC
* [cloud-market-tracker](https://github.com/odonnkongolo/cloud-market-tracker) & [never404-platform](https://github.com/odonnkongolo/never404-platform) — Complete multi-subnet AWS VPC, ECR registry, and Amazon EKS cluster provisioned via Terraform with a fully automated DevSecOps deployment pipeline.

### 🛡️ 2. Event-Driven Auto-Remediation (Cloud Security)
* [devsecops-remediation-bot](https://github.com/odonnkongolo/devsecops-remediation-bot) — An autonomous Python Lambda bot triggered by AWS Config and EventBridge to instantly detect and neutralize public firewall vulnerabilities (Exposed SSH) in real-time.

### 🚀 3. Advanced Release Engineering
* [serverless-canary-release](https://github.com/odonnkongolo/serverless-canary-release) — **Serverless Canary Deployment Pipeline (Release Engineering)**
  * **Advanced Release Engineering:** Designed and executed an automated traffic-shifting canary deployment pipeline using AWS CodeDeploy, successfully shifting 10% of live traffic to new software iterations during release windows.
  * **Risk Mitigation:** Integrated automated 5-minute bake periods to isolate potential system regression issues, completely eliminating the possibility of total application downtime during production deployments.
  * **Immutable Serverless Architecture:** Programmed a decoupled AWS Lambda alias structure using Terraform lifecycle parameters, separating underlying cloud infrastructure orchestration from the software release engine.

### 💥 4. Disaster Recovery (High Availability)
* [multi-region-dr-failover](https://github.com/odonnkongolo/multi-region-dr-failover) — Active-Passive Multi-Region Disaster Recovery architecture utilizing Amazon Route 53 global health checks and dual-region S3 deployments for automated, zero-touch failover.

### 🚚 5. Stateful Cloud Migration & Data Persistence
* [statefull-aws-migration](https://github.com/odonnkongolo/statefull-aws-migration) — Architectural patterns and infrastructure for migrating and managing stateful database workloads in AWS.

### 🎥 6. Platform Observability & Telemetry
* [exacq-telemetry-ops](https://github.com/odonnkongolo/exacq-telemetry-ops) & [cloud-market-tracker](https://github.com/odonnkongolo/cloud-market-tracker) & [never404-platform](https://github.com/odonnkongolo/never404-platform) — Setting up robust monitoring, logging, and tracing across hybrid cloud environments.
