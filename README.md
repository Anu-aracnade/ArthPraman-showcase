# अर्थPraman

### Making financial evidence ready for credit decisions.

ArthPraman is a **Financial Evidence Readiness & Verification Platform** designed to transform fragmented business financial records into a structured, reconciled, and verifiable evidence layer.

[![Live Demo](https://img.shields.io/badge/Live-Demo-0d2b45.svg)](https://arth-praman.vercel.app/)
[![Stack](https://img.shields.io/badge/Stack-Next.js%20%7C%20TypeScript%20%7C%20Supabase-0d2b45.svg)](#technology-stack)
[![Status](https://img.shields.io/badge/Status-Working%20MVP-16805c.svg)](#project-status)
[![License](https://img.shields.io/badge/License-Proprietary-c0392b.svg)](#license)

---

## Product

> **Financial data is everywhere.  
> Trusted financial evidence shouldn't be.**

ArthPraman addresses the gap between having financial records and having financial evidence that can be consistently reviewed.

The platform brings together records from different financial sources, organizes them into a common structure, identifies inconsistencies and duplicate records, evaluates cross-source agreement, and produces an evidence-readiness assessment with a verifiable report.

---

## Demo

**Live Application:** [Open ArthPraman](https://arth-praman.vercel.app/)

[![ArthPraman Product Demo Video](assets/demo_video_thumbnail.png)](https://drive.google.com/file/d/183W73oIF7mwFal0iOkjpnpjEiCCqpOqW/view?usp=drive_link)

---

## Overview

For small businesses, financial information can exist across bank statements, digital ledgers, cash records, spreadsheets, and other sources.

The difficulty is often not the absence of data, but the lack of a consistent way to:

- bring different records together,
- understand where the records agree,
- identify discrepancies and unexplained entries,
- distinguish stronger evidence from self-reported information,
- and present the resulting financial picture in a form that can be reviewed.

ArthPraman is designed as an **evidence preparation and verification layer** between fragmented financial records and formal financial evaluation.

---

## The Problem

### The problem isn't always the business. It's the evidence.

Financial records can be fragmented across:

- Bank statements
- Digital accounting ledgers
- Cash records
- Spreadsheets and exported transaction data
- Self-reported financial information

When these sources are reviewed independently, important questions become difficult to answer:

- Do records from different sources correspond?
- Are some transactions duplicated?
- Where do the records disagree?
- Which financial information is independently supported?
- How much financial activity remains unexplained?
- Is the available evidence sufficiently complete and consistent?

ArthPraman focuses on making those questions easier to answer through a structured evidence workflow.

---

## What ArthPraman Does

```text
Financial Records
       │
       ▼
   Ingestion
       │
       ▼
   Normalization
       │
       ▼
Duplicate Detection
       │
       ▼
  Reconciliation
       │
       ▼
Evidence Health
       │
       ▼
Financial Evidence
   Readiness
       │
       ├───────────────┐
       ▼               ▼
 Evidence Report   Verification
                       QR                     
```

## Public Showcase Repository

This repository is the **public showcase and presentation repository for ArthPraman**.

It is intended to provide a clear, verifiable overview of the product, its purpose, architecture, development process, technical decisions, and working capabilities.

The **complete ArthPraman application source code is maintained separately in a private development repository**. The private repository is also where the active application implementation and deployment are maintained.

This public repository intentionally does **not** expose the complete production implementation or internal technical details required to reproduce the system.

The separation is intentional:

```text
Public Showcase Repository
        │
        ├── Product presentation
        ├── Architecture overview
        ├── Technical concepts
        ├── Development history
        ├── Screenshots & assets
        └── Public project information
                 │
                 ▼
      Private Development Repository
                 │
                 ├── Complete application source
                 ├── Full implementation
                 ├── Internal project configuration
                 └── Production deployment
```

> **Public documentation is provided to demonstrate the project and does not imply that the underlying implementation is open source.**

---

## Development Timeline

ArthPraman was developed as an iterative project from initial implementation through MVP stabilization.

### August 16, 2026 — Development Started

Initial development of the ArthPraman product began, moving from the defined product concept into implementation.

### August 16 – September 2, 2026 — MVP Development & Refinement

The core product was progressively implemented and refined across:

- Financial evidence ingestion
- Data normalization
- Duplicate detection
- Cross-source reconciliation
- Evidence health analysis
- Financial Evidence Readiness
- Evidence report generation
- Verification workflow
- Authentication and business workflows
- Product interface and user experience

The implementation was tested and refined through repeated debugging and validation of the end-to-end workflow.

### September 2, 2026 — MVP Freeze

After the initial development and debugging cycle, the working MVP was considered complete and frozen.

The current public showcase documents this **MVP state** of ArthPraman.

---

## Project Ownership

**अर्थPraman** is an independently developed project by **Anubhab Pathak**.

I designed and developed the project end-to-end, including the product concept, architecture, core financial evidence workflows, reconciliation system, Financial Evidence Readiness methodology, verification flow, reporting system, and application implementation.

The complete production source code is maintained in a private repository. This public repository serves as the official showcase and technical record of **अर्थPraman**.

Creator & Owner — **Anubhab Pathak**