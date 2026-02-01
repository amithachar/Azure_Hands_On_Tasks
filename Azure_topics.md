1. Cloud & Azure Fundamentals (Foundation Layer)

You must understand why cloud exists before touching buttons.

Learn:

What is cloud computing (IaaS, PaaS, SaaS)

Regions, Availability Zones, Paired Regions

Subscription, Tenant, Management Groups

Resource Groups (lifecycle boundary)

Azure basics:

What Microsoft Azure is

Azure Portal, Azure CLI, Azure PowerShell

Azure Resource Manager (ARM)

This maps directly to AZ-900 knowledge.

2. Identity & Access Management (Non-Negotiable)

This is where juniors fail interviews.

Learn:

Entra ID (Azure AD) basics

Users, Groups, Service Principals

Security groups vs Microsoft 365 groups

RBAC (Owner, Contributor, Reader)

Scope: Management Group → Subscription → Resource Group → Resource

Conditional Access (concept level)

Managed Identity (system vs user assigned)

Rule of thumb:
If you don’t understand who can do what, nothing else matters.

3. Compute Services (Where Apps Actually Run)

Learn when to use what, not just how to create.

Virtual Machines

VM creation (Linux & Windows)

VM sizes, disks, NICs

Availability Set vs Availability Zone

VM Scale Sets

Extensions & Custom Script

Platform Compute

Azure App Service (Web Apps)

Azure Functions (serverless)

Azure Container Instances (ACI)

Containers

Docker basics

Azure Kubernetes Service (AKS)

Pods, Services, Ingress (conceptual depth)

4. Networking (Most Feared, Most Valuable)

Networking is what separates beginners from engineers.

Learn:

Virtual Networks (VNet)

Subnets

NSG (Network Security Groups)

Azure Load Balancer

Application Gateway

Azure Firewall (concept)

VNet Peering

VPN Gateway vs ExpressRoute

Private Endpoint vs Service Endpoint

DNS (Azure DNS, Private DNS)

If you can draw traffic flow, you understand networking.

5. Storage & Databases (Data Has Gravity)

Learn:

Storage

Storage Account types

Blob, File, Queue, Table

Containers, Access tiers

SAS tokens

Secure transfer, encryption

Lifecycle rules

Databases (Concept + Basic Use)

Azure SQL Database

SQL Managed Instance

Cosmos DB (API types)

Azure Database for MySQL/PostgreSQL

6. Monitoring, Logging & Alerts (Production Reality)

This is your SRE bridge.

Learn:

Azure Monitor

Metrics vs Logs

Log Analytics Workspace

KQL basics

Alerts (metric & log-based)

Action Groups

VM Insights

Application Insights

You already touched this with CPU alerts—good sign.

7. Security & Governance (Enterprise Layer)

Learn:

Azure Policy

Blueprints (concept)

Resource Locks

Microsoft Defender for Cloud

Secure Score

Key Vault (secrets, keys, certificates)

Disk encryption

Network security design principles

Security is not optional. It’s assumed.

8. Automation & Infrastructure as Code (Career Multiplier)

Manual clicks don’t scale.

Learn:

Azure CLI deeply

ARM templates (concept)

Bicep (preferred)

Terraform (huge demand)

Parameterization & state

This is where cloud engineer → cloud professional happens.

9. DevOps & CI/CD (Real Job Expectations)

Learn:

Git fundamentals

Azure DevOps

Pipelines (YAML)

Build vs Release pipelines

CI/CD for:

App Service

VM

AKS

Secrets in pipelines

Cloud without DevOps is incomplete.

10. Cost Management & Optimization (Managers Love This)

Learn:

Azure Pricing Calculator

Cost Management + Billing

Budgets & alerts

Reserved Instances

Right-sizing VMs

Storage tier optimization

Engineers who save money get remembered.

11. Backup, DR & High Availability (Production Trust)

Learn:

Azure Backup

Recovery Services Vault

VM backup & restore

Azure Site Recovery (ASR)

RTO & RPO concepts

Multi-region design

This is where systems earn trust.

12. Certifications (Optional but Strategic)

Suggested order:

AZ-900 → Fundamentals

AZ-104 → Core Azure Cloud Engineer

AZ-305 → Architect (later)


For ~4 years of experience, you’re no longer judged on what Azure services exist. You’re judged on design choices, failure handling, security posture, and operational maturity.

Below is the 4+ years Azure Cloud Engineer topic map — this is interview-caliber, production-focused, and aligned with what senior engineers are actually asked.


1. Azure Architecture & Design (Core Expectation)

At 4 years, you must explain why a design exists.

Learn deeply:

Hub–Spoke architecture

Landing Zone concepts

Subscription strategy (Prod / Non-Prod / Sandbox)

Resource group design patterns

Availability Zones vs Availability Sets (real trade-offs)

Stateless vs stateful workloads

Multi-region design patterns

Failover strategies (active-active vs active-passive)

Interview signal:

“I design for failure first, not success.”

2. Identity, Security & Zero Trust (Must Be Strong)

This is a filter topic.

Learn:

Entra ID (Azure AD) architecture

RBAC vs ABAC

Custom roles

Managed Identity (real use cases)

Conditional Access (concept + scenarios)

Privileged Identity Management (PIM)

Service principals vs workload identity

Key Vault integration patterns

Secret rotation strategies

You should be able to answer:

“How do you grant production access safely?”

3. Advanced Networking (High-Value Skill)

Networking separates mid from senior.

Learn:

Hub–Spoke with Firewall

Azure Firewall vs NSG vs NVA

Application Gateway vs Load Balancer

WAF policies

Private Endpoint vs Service Endpoint (deep comparison)

VNet peering (transitive limitations)

DNS design (Private DNS zones)

Hybrid connectivity (VPN vs ExpressRoute)

Traffic inspection & routing (UDRs)

Expected skill:

Draw packet flow from internet → app → database

4. Compute at Scale (Not Just VM Creation)

Learn:

Virtual Machines

VM Scale Sets (autoscaling rules)

OS vs Data disk strategies

Image pipelines (Shared Image Gallery)

Patch management

Custom Script Extensions

Run Command

Containers

AKS architecture

Node pools (system vs user)

Ingress controllers

Pod autoscaling

Network policies

Secrets management in AKS

Upgrade & rollback strategies

At 4 years, AKS familiarity is a strong advantage.

5. Observability & SRE Practices (Very Important)

You’re expected to think like an SRE.

Learn:

Azure Monitor internals

Metrics vs Logs vs Traces

Log Analytics Workspace design

KQL (joins, filters, time series)

Alert fatigue & noise reduction

Dynamic thresholds

Action Groups integrations

SLIs, SLOs, error budgets (conceptual)

Be ready to answer:

“How do you know production is healthy?”

6. Infrastructure as Code (Mandatory)

Manual portal work is no longer impressive.

Learn:

Azure CLI scripting

ARM templates (reading/debugging)

Bicep (preferred)

Terraform (state, backend, modules)

Environment parameterization

Drift detection

Secret handling in IaC

Expected mindset:

“Infrastructure should be reproducible, not remembered.”

7. CI/CD & DevOps Integration

Cloud engineers at 4 years own pipelines, not just infra.

Learn:

Azure DevOps pipelines (YAML)

CI vs CD separation

Multi-stage pipelines

Approvals & gates

Secure variables

Deployment strategies (blue-green, canary)

Rollback mechanisms

Infra + app pipelines together

8. Security, Governance & Compliance

This is where enterprises live.

Learn:

Azure Policy (deny, audit, modify)

Initiative definitions

Resource locks

Defender for Cloud

Secure Score

Compliance concepts (ISO, SOC, PCI – high level)

Logging for audits

You should be able to say:

“How do you prevent bad resources from being created?”

9. Backup, DR & Business Continuity

Senior engineers think beyond uptime.

Learn:

Azure Backup architecture

Recovery Services Vault

Restore testing

Azure Site Recovery (ASR)

RTO vs RPO mapping

Cross-region DR

Backup cost optimization

10. Cost Optimization & FinOps Thinking

At 4 years, cost awareness is expected.

Learn:

Cost Management + Billing

Budgets & alerts

VM right-sizing

Reserved Instances vs Savings Plans

Storage tier optimization

Cost allocation using tags

Smart engineers save money without breaking systems.

11. Real-World Scenarios You Must Handle

You should confidently explain:

API latency spike → investigation steps

VM CPU high → short-term vs long-term fix

Storage access leak → containment

Region outage → recovery plan

Deployment failure → rollback

Alert storm → suppression strategy

This is where interviews are won.

One-Line Self-Assessment Rule

If you can:

Design it

Secure it

Monitor it

Automate it

Recover it

You’re operating at 4+ years Azure Cloud Engineer level.

AZ-400 → DevOps (if interested)

Certs don’t replace skills—but they open doors.
