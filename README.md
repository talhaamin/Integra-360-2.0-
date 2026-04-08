# INTEGRA 360 (2.0)

![.NET 8](https://img.shields.io/badge/.NET-8-512BD4?logo=dotnet&logoColor=white)
![Architecture](https://img.shields.io/badge/Architecture-Clean%20Architecture-0A66C2)
![Platform](https://img.shields.io/badge/Platform-Multi--Tenant%20SaaS-1F8B4C)
![Integration](https://img.shields.io/badge/Approach-API--First-8B5CF6)
![Apps](https://img.shields.io/badge/Experience-Modular%20App%20Suite-F59E0B)

INTEGRA 360 (2.0) is an enterprise-grade SaaS platform designed to unify healthcare operations, corporate administration, and specialized industry workflows within a single digital ecosystem. It brings together HMIS, patient engagement, provider productivity, administration, finance, HR, CRM, supply chain, task execution, POS, education management, and specialty operations on a secure, modular, multi-tenant foundation.

## Table of Contents

- [Executive Summary](#executive-summary)
- [Platform Highlights](#platform-highlights)
- [Product Gallery](#product-gallery)
- [Solution Architecture](#solution-architecture)
- [Module Overview](#module-overview)
- [SaaS 2.0 Capabilities](#saas-20-capabilities)
- [AI Governance and Runtime](#ai-governance-and-runtime)
- [Getting Started](#getting-started)
- [Database-First Scaffold](#database-first-scaffold)
- [Docker](#docker)
- [Example API Requests](#example-api-requests)
- [Frontend Notes](#frontend-notes)

## Executive Summary

Organizations increasingly need a unified operating platform that can reduce fragmentation, strengthen governance, improve service delivery, and scale across multiple business units or sites. INTEGRA 360 (2.0) addresses that need by consolidating mission-critical workflows into one connected platform with centralized identity, configurable modules, tenant-aware governance, and real-time operational visibility.

The result is a system positioned not only as software infrastructure, but as a long-term digital backbone for operational maturity, cross-functional coordination, and scalable growth.

## Platform Highlights

- Multi-tenant, multi-site SaaS architecture
- Modular deployment with app-based enablement
- Secure authentication with JWT and refresh tokens
- Role-based access control with module-level permissions
- Tenant provisioning, subscriptions, and module assignment
- Feature flags and template-driven rollout
- API-first integration model
- Real-time operational visibility with SignalR-enabled experiences
- Security middleware, health checks, auditability, and centralized governance
- AI runtime and AI governance with policy enforcement, approvals, incidents, and model oversight

## Product Gallery

<p align="center">
  <img src="Screens/1-1.png" alt="INTEGRA 360 unified access gateway" width="88%" />
</p>
<p align="center">
  <img src="Screens/1-2.png" alt="INTEGRA 360 unified access gateway" width="88%" />
</p>
<p align="center">
  <img src="Screens/1-3.png" alt="INTEGRA 360 unified access gateway" width="88%" />
</p>
<p align="center">
  <img src="Screens/1-4.png" alt="INTEGRA 360 unified access gateway" width="88%" />
</p>
<p align="center">
  <img src="Screens/1-5.png" alt="INTEGRA 360 unified access gateway" width="88%" />
</p>
<p align="center">
  <img src="Screens/1-6.png" alt="INTEGRA 360 unified access gateway" width="88%" />
</p>

<p align="center">
  <em>Unified application gateway for rapid access to the INTEGRA 360 app ecosystem.</em>
</p>

<p align="center">
  <img src="Screens/2.png" alt="INTEGRA 360 operational dashboard" width="88%" />
</p>

<p align="center">
  <em>Executive and operational dashboards spanning clinical, financial, compliance, and service domains.</em>
</p>

<p align="center">
  <img src="Screens/3.png" alt="INTEGRA 360 role based access control" width="88%" />
</p>

<p align="center">
  <em>Role-based access control and permission management for governed multi-tenant operations.</em>
</p>

<p align="center">
  <img src="Screens/4.png" alt="INTEGRA 360 Tenant Management Login" width="88%" />
</p>

<p align="center">
  <em>Tenant management for governed multi-tenant operations.</em>
</p>

<p align="center">
  <img src="Screens/5.png" alt="INTEGRA 360 Tenant 360 operational Dashboard" width="88%" />
</p>

<p align="center">
  <em>Tenant 360 operational dashboard for governing multi-tenant operations via single screen.</em>
</p>

<p align="center">
  <img src="Screens/6.png" alt="INTEGRA 360 HMIS Login" width="88%" />
</p>

<p align="center">
  <em>Hospital management system main landing dashboard.</em>
</p>

<p align="center">
  <img src="Screens/8.png" alt="HMIS Patient Search" width="88%" />
</p>

<p align="center">
  <em>Patient search.</em>
</p>

<p align="center">
  <img src="Screens/9.png" alt="HMIS Patient Charts" width="88%" />
</p>

<p align="center">
  <em>Patient charts.</em>
</p>
<p align="center">
  <img src="Screens/10.png" alt="HMIS Patient Charts Clinical" width="88%" />
</p>

<p align="center">
  <em>Patient charts clinical.</em>
</p>

<p align="center">
  <img src="Screens/A-1.png" alt="INTEGRA 360 appointments" width="88%" />
</p>
<p align="center">
  <img src="Screens/A-2.png" alt="INTEGRA 360 appointments" width="88%" />
</p>
<p align="center">
  <img src="Screens/A-3.png" alt="INTEGRA 360 appointments" width="88%" />
</p>
<p align="center">
  <img src="Screens/A-4.png" alt="INTEGRA 360 appointments" width="88%" />
</p>
<p align="center">
  <img src="Screens/A-5.png" alt="INTEGRA 360 appointments" width="88%" />
</p>
<p align="center">
  <em>Patient Appointments</em>
</p>
<p align="center">
  <img src="Screens/H-1.png" alt="INTEGRA 360 Human Resource & Workforce Management" width="88%" />
</p>
<p align="center">
  <img src="Screens/H-2.png" alt="INTEGRA 360 Human Resource & Workforce Management" width="88%" />
</p>
<p align="center">
  <img src="Screens/H-3.png" alt="INTEGRA 360 Human Resource & Workforce Management" width="88%" />
</p>
<p align="center">
  <img src="Screens/H-4.png" alt="INTEGRA 360 Human Resource & Workforce Management" width="88%" />
</p>
<p align="center">
  <img src="Screens/H-5.png" alt="INTEGRA 360 Human Resource & Workforce Management" width="88%" />
</p>
<p align="center">
  <img src="Screens/H-6.png" alt="INTEGRA 360 Human Resource & Workforce Management" width="88%" />
</p>
<p align="center">
  <img src="Screens/H-7.png" alt="INTEGRA 360 Human Resource & Workforce Management" width="88%" />
</p>
<p align="center">
  <img src="Screens/H-8.png" alt="INTEGRA 360 Human Resource & Workforce Management" width="88%" />
</p>
<p align="center">
  <em>Human Resource & Workforce Management</em>
</p>

## Solution Architecture

### Backend

- `Dhms.Domain` - domain entities, enums, value objects
- `Dhms.Application` - CQRS, MediatR handlers, validators, interfaces, behaviors
- `Dhms.Infrastructure` - EF Core, repositories, unit of work, JWT, tenant middleware, feature flags, AI services
- `Dhms.Shared` - shared contracts and common response models
- `Dhms.WebAPI` - REST API, authentication, module services, governance APIs, health checks
- `Dhms.Tests` - unit and integration tests

### Frontend Apps

- `src/Dhms.Main` - unified application launch experience
- `src/Dhms.Admin` - platform administration and SaaS control center
- `src/Dhms.Web` - core HMIS and operational super-app
- `src/Dhms.PATIENT` - patient self-service portal
- `src/Dhms.PROVIDER` - provider workspace
- `src/Dhms.SCMweb` - supply chain and inventory management
- `src/Dhms.Finance` - finance and accounting
- `src/Dhms.HR` - human resource management
- `src/Dhms.CRM` - customer relationship management
- `src/Dhms.TASK` - work, task, sprint, and SLA management
- `src/Dhms.POS` - point of sale and cashier operations
- `src/Dhms.IMS` - institution management system
- `src/Dhms.DCLMS` - specialized dairy and livestock operations

## Module Overview

### 1. INTEGRA Main

A central branded launchpad that gives users one entry point into the full INTEGRA 360 ecosystem.

### 2. Admin

The SaaS command center for tenant onboarding, provisioning, plans, subscriptions, feature templates, settings templates, module registry, version control, module assignment, approvals, incidents, policies, model registry, audit trails, and platform-wide governance.

### 3. HMIS Core

The flagship healthcare operations suite covering:

- Patient registration and MPI
- Appointment scheduling and queue management
- OPD, IPD, ED, nursing, ICU, OT, and ward operations
- Provider workflows and clinical documentation
- Orders, lab, radiology, pharmacy, blood bank, and CSSD
- Billing, charge capture, insurance claims, and revenue cycle
- Inventory, work orders, and maintenance
- Quality, safety, clinical audits, and reporting
- HL7, FHIR, and interoperability services

### 4. Patient Portal

A self-service digital experience for patients and families, including:

- Appointment booking, rescheduling, and check-in
- Reports, prescriptions, and clinical summaries
- Care plans, medication adherence, and refill requests
- Billing, payments, and claims visibility
- Messaging, uploads, consents, and family access

### 5. Provider Portal

A focused workspace for clinicians and providers with:

- Inbox, tasks, sessions, calendar, and on-call planning
- OPD, IP, ED, and follow-up workflows
- Orders, result review, and clinical notes
- Templates, discharge, and referral coordination
- Productivity, quality metrics, and feedback visibility

### 6. Supply Chain Management

A complete SCM stack for:

- Catalogs, stores, bins, and stock locator
- Purchase requests, POs, approvals, and contracts
- GRN, QC inspection, returns, issues, transfers, and adjustments
- Batch and expiry tracking, replenishment, and cycle counts
- Vendor performance and procurement analytics

### 7. Finance

An enterprise finance suite that includes:

- General ledger, journals, trial balance, and day book
- Accounts receivable and payable
- Cash book, treasury, and bank reconciliation
- Tax, e-invoicing, price lists, and service charges
- Budgeting, cost centers, and variance analysis
- Fixed assets, depreciation, and disposal
- Period close, statutory reporting, and financial statements

### 8. Human Resources

A people operations platform supporting:

- Employee records, contracts, departments, and org structures
- Attendance, shifts, rosters, and regularization
- Leave management and approvals
- Payroll cycles, runs, components, and payslips
- Goals, reviews, feedback, and performance improvement plans
- Recruitment, interviews, offers, training, and certifications

### 9. CRM

A growth and relationship management suite for:

- Lead capture, qualification, scoring, and assignment
- Accounts, contacts, hierarchy, and segments
- Pipeline, forecasting, targets, and deal desk workflows
- Campaign planning, execution, attribution, and ROI
- Service cases, escalations, SLA tracking, and customer support
- Quotes, approvals, contracts, renewals, and churn prevention

### 10. Task Management

A productivity and execution layer with:

- My worklist, inbox, Kanban, and priority queues
- Project directory, milestones, roadmap, and dependencies
- Sprint planning, active sprint, burndown, and retrospectives
- Backlog refinement, release planning, and estimation
- Time entries, capacity planning, utilization, and approvals
- SLA policies, webhooks, triggers, and team performance analytics

### 11. POS

A retail and cashier operations module for:

- New sales, hold/resume, returns, and parked bills
- Items, categories, discounts, tax rules, and price lists
- Customer directory, loyalty, and membership plans
- Stock visibility and low-stock alerts
- Shift open/close, cash drop, drawer audit, and day-end close
- Sales, payment mix, and tax reporting

### 12. IMS

An institution management system covering:

- Enquiries, applicants, enrollment, and student records
- Programs, courses, sections, and curriculum
- Attendance, exams, marks, results, and transcripts
- Fee plans, invoicing, collections, and dues tracking
- Faculty directory, workload, payroll linkage, and appraisals
- Library, transport, hostel, timetable, notices, and parent messaging

### 13. DCLMS

A specialized industry module for dairy and livestock operations, including:

- Herd overview, tagging, movement, and lifecycle management
- Breeding, insemination, pregnancy, and calving workflows
- Milk collection, yield, quality, and dispatch
- Feed plans, rations, and consumption tracking
- Treatments, vaccination, disease watch, and vet visits
- Farm tasks, barns, equipment, stores, procurement, and settlements

## SaaS 2.0 Capabilities

INTEGRA 360 (2.0) is built around a modern SaaS operating model that supports both rapid rollout and enterprise governance.

- Tenant provisioning and onboarding workflows
- Subscription and plan management
- Module registry and tenant-specific module assignment
- Feature flags and reusable feature templates
- Tenant settings and location settings templates
- Multi-app identity, permissions, and user-module access mapping
- Versioned modules and platform governance
- Usage tracking, approvals queue, incident handling, and audit logs

## AI Governance and Runtime

The platform includes AI governance and runtime services to help organizations adopt AI responsibly.

- AI policy management
- AI model registry
- AI runtime execution workflows
- Approval submission and decision tracking
- Incident logging and status management
- Audit-ready dashboards for model quality and enforcement outcomes

## Getting Started

### Run the solution

```powershell
dotnet restore Dhms.SaaS.sln
dotnet build Dhms.SaaS.sln
```

### Run the API

```powershell
dotnet run --project Dhms.WebAPI/Dhms.WebAPI.csproj
```

### Run frontend apps

```powershell
dotnet run --project src/Dhms.Admin/Dhms.Admin.csproj
dotnet run --project src/Dhms.Web/Dhms.Web.csproj
```

## Database-First Scaffold

Run this after the SQL script is applied:

```powershell
dotnet ef dbcontext scaffold "Server=localhost,1433;Database=DHMS_SaaS;User Id=sa;Password=Your_strong_password123;TrustServerCertificate=True;" Microsoft.EntityFrameworkCore.SqlServer `
  --project Dhms.Infrastructure/Dhms.Infrastructure.csproj `
  --startup-project Dhms.WebAPI/Dhms.WebAPI.csproj `
  --context DhmsDbContext `
  --context-dir Persistence/Scaffolded `
  --output-dir Persistence/Scaffolded/Entities `
  --schema tenant --schema auth --schema setup --schema clinical --schema inventory --schema ops --schema billing --schema integration --schema audit --schema reporting `
  --use-database-names --data-annotations --no-onconfiguring --force
```

Preserve custom `DhmsDbContext` hooks for:

- Tenant scoping
- Site enforcement
- Audit auto population
- Soft activation filters (`Is_Active = 1`)

## Docker

```powershell
docker compose up -d --build
```

## Example API Requests

```bash
curl -X POST "https://localhost:7154/api/v1/Auth/register" \
  -H "Content-Type: application/json" \
  -H "X-Tenant-Id: 1" \
  -H "X-Site-Id: 1" \
  -d '{"userName":"admin","email":"admin@dhms.local","password":"Password123!","tenantId":1,"siteId":1}'

curl -X POST "https://localhost:7154/api/v1/Auth/login" \
  -H "Content-Type: application/json" \
  -H "X-Tenant-Id: 1" \
  -H "X-Site-Id: 1" \
  -d '{"email":"admin@dhms.local","password":"Password123!","tenantId":1,"siteId":1}'
```

## Frontend Notes

For frontend app architecture and setup details, see [src/README.md](src/README.md).
