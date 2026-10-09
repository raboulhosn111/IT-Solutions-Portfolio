
# Generator Pro

### Generator Billing & Subscriber Management System

**Project Type:** Commercial Desktop Business Application  
**Platform:** Windows  
**Architecture:** Offline-First  
**Technology Stack:** JavaScript, Node.js, SQLite, HTML, CSS  
**Role:** Solution Architect, Software Developer & Deployment Engineer  
**Status:** Active Development & Refinement

---

## Project Overview

**Generator Pro** is an offline-first desktop business application designed to simplify the administration, billing, and financial management of private electricity generator subscriptions.

The solution addresses the operational requirements of generator owners and operators, particularly in markets where privately managed electricity generation is an essential service.

Generator Pro brings subscriber records, electricity consumption, monthly billing, outstanding balances, payment tracking, and customer communication into a centralized management environment.

The application is designed around practical operational requirements, local data storage, and streamlined monthly billing workflows.

---

## Business Challenge

Private generator operators often manage subscriber information, meter readings, electricity consumption, invoices, and collections through spreadsheets, paper records, or disconnected applications.

These methods create several challenges:

- Time-consuming monthly billing calculations.
- Difficulties maintaining accurate subscriber balances.
- Fragmented payment and collection records.
- Manual invoice preparation and distribution.
- Limited visibility into outstanding payments.
- Dependence on repetitive administrative procedures.
- Internet connectivity constraints.

Generator Pro was conceived to digitize these operations through a unified desktop application.

---

## Core Features & Capabilities

### 1. Subscriber Management

- Centralized subscriber profiles.
- Subscription and account management.
- Subscriber billing information.
- Account history and financial records.
- Subscriber-specific billing workflows.

### 2. Consumption & Billing

- Monthly electricity consumption tracking.
- Meter reading and consumption-based calculations.
- Current-month billing calculations.
- Previous balance carry-forward.
- Payment and credit adjustments.
- Total outstanding balance calculations.
- Monetary calculations preserving decimal precision.

### 3. Invoice Management

- Individual subscriber invoice generation.
- PDF invoice and receipt preparation.
- Billing information presentation.
- Invoice viewing, printing, and sharing workflows.
- Monthly invoice processing.

### 4. Payment & Financial Management

- Subscriber payment recording.
- Outstanding balance tracking.
- Previous balance management.
- Credit and payment adjustments.
- Account-level financial history.

### 5. WhatsApp-Assisted Communication

- Individual subscriber billing messages.
- Customizable billing message templates.
- Preparation of subscriber messages in batches.
- WhatsApp-assisted delivery workflows.
- PDF documents available separately for sharing.

**Important:** WhatsApp message preparation and WhatsApp message delivery are separate operations. The workflow does not claim unattended or fully automatic bulk message sending.

### 6. Offline Operations

- Local-first application architecture.
- SQLite database storage.
- Windows desktop execution.
- Reduced dependency on continuous internet connectivity for core billing operations.

---

## Technical Architecture

Generator Pro uses a desktop-oriented application structure combining a user interface, business logic, billing operations, and local data persistence.

| Component | Technology / Approach |
|---|---|
| Application Platform | Windows Desktop |
| Application Logic | JavaScript / Node.js |
| User Interface | HTML, CSS, JavaScript |
| Database | SQLite |
| Billing | Application-level calculation logic |
| Document Generation | PDF generation |
| Customer Communication | WhatsApp-assisted messaging |
| Data Storage | Local-first persistence |
| Distribution | Packaged Windows application |

### Logical Architecture

```text
                GENERATOR PRO
              Desktop Application
                      |
                      v
                 User Interface
                      |
                      v
              Application Services
                      |
        +-------------+-------------+
        |             |             |
        v             v             v
   Subscribers     Billing       Payments
        |             |             |
        +-------------+-------------+
                      |
                      v
               SQLite Database
                      |
           +----------+----------+
           |                     |
           v                     v
     PDF Generation        Message Preparation
           |                     |
           v                     v
    View / Print / Share    WhatsApp-Assisted
                              Communication
```

*This diagram represents the logical solution design and does not disclose proprietary implementation details.*

---

## Billing Workflow

A typical monthly billing cycle follows these operational stages:

1. **Subscriber Selection:** Identify the subscribers included in the billing period.
2. **Consumption Recording:** Enter or review the relevant meter readings and consumption information.
3. **Billing Calculation:** Calculate the applicable monthly charges.
4. **Balance Reconciliation:** Incorporate previous balances, payments, and credits.
5. **Invoice Preparation:** Generate subscriber billing information and supporting documents.
6. **Customer Communication:** Prepare billing messages for WhatsApp-assisted sharing.
7. **Payment Recording:** Record collections and update subscriber account balances.

The workflow is designed to reduce repetitive administrative work and improve financial record consistency.

---

## Engineering & Development Responsibilities

### Solution Architecture

- Defined the application's functional structure and business workflows.
- Designed an offline-first approach suitable for local operational requirements.
- Structured subscriber, billing, and payment management capabilities.

### Application Development

- Developed and refined JavaScript-based desktop application functionality.
- Integrated SQLite for local data persistence.
- Implemented consumption, billing, and account balance workflows.
- Developed invoice and customer communication functionality.

### Packaging & Deployment

- Worked on Windows application packaging and executable distribution.
- Addressed Node.js runtime dependencies and deployment compatibility.
- Investigated runtime initialization, security verification, and installation issues.
- Refined application usability and operational workflows.

### Quality & Reliability

- Reviewed financial calculations and billing presentation.
- Improved the handling of monetary precision.
- Refined message preparation and document generation processes.
- Identified and addressed application deployment and operational issues.

---

## Design Principles

### Offline-First Operation

Core business functionality is designed to operate locally without requiring continuous cloud connectivity.

### Operational Simplicity

The interface and workflows prioritize the everyday requirements of generator operators.

### Financial Accuracy

Billing and balance management emphasize consistent calculations, historical balances, and transparent payment records.

### Practical Communication

The solution supports subscriber communication using familiar messaging workflows without misrepresenting message preparation as automatic delivery.

### Maintainability

The application is structured for continued functional improvements, troubleshooting, and deployment refinement.

---

## Business Value

Generator Pro is designed to deliver the following operational benefits:

| Business Area | Intended Benefit |
|---|---|
| Subscriber Administration | Centralized customer and subscription records |
| Monthly Billing | Reduced repetitive calculation work |
| Financial Management | Improved visibility into balances and payments |
| Invoice Processing | Standardized subscriber billing documents |
| Communication | Faster preparation of individual billing messages |
| Connectivity | Core operations available without continuous internet access |
| Record Management | Structured local storage of operational information |

---

## Development & Deployment

Generator Pro is undergoing iterative development and refinement, with particular attention to:

- Desktop application packaging.
- Runtime dependency management.
- Invoice management workflows.
- PDF document generation.
- WhatsApp-assisted communication.
- Subscriber account accuracy.
- User interface and usability improvements.

Features described in this document represent the application's development scope and implemented workflows; individual capabilities may continue to evolve.

---

## Project Documentation & Availability

This repository provides a professional technical overview of Generator Pro.

Additional sanitized application screenshots, system diagrams, and demonstrations may be published separately.

**Source Code:** Proprietary — Not publicly distributed.  
**Project Category:** Desktop Software / Utility Billing / Business Automation  
**Project Status:** Active Development & Refinement

---

## Developer

**Rami N. Aboulhosn**  
IT Solutions Architect | Software Developer | Digital Transformation Specialist

- **LinkedIn:** [Rami N. Aboulhosn](https://www.linkedin.com/in/aboulhosn-rami)
- **GitHub:** [@raboulhosn111](https://github.com/raboulhosn111)
- **Location:** Lebanon

---

[Back to IT Solutions Portfolio](../README.md)

**© 2026 Rami N. Aboulhosn. All rights reserved.**
