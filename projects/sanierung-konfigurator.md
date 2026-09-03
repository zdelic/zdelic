# Sanierung-Konfigurator

## Renovation Calculation, Quotation & Planning Platform

Sanierung-Konfigurator is a full-stack business application for calculating renovation projects, maintaining a centralized pricebook, creating structured offers and supporting project-planning workflows.

---

## Business Problem

Renovation calculations are often time-consuming, inconsistent and dependent on manually maintained spreadsheets or isolated documents.

The application turns that process into a structured digital workflow where project managers can create calculations by trade, apply pricing rules, generate professional documents and manage users and permissions in one system.

---

## What I Built

I developed the application end to end, including:

- application architecture
- Laravel API backend
- React / TypeScript frontend
- database structure and migrations
- authentication and role-based permissions
- project and calculation workflows
- centralized pricebook
- PDF generation
- signed-document handling
- invitation system
- audit logging
- deployment and ongoing maintenance

---

## Core Features

### Renovation Calculations
- calculations organized by construction trades
- configurable pricing logic
- structured work descriptions
- reusable pricebook data
- project-specific calculation data

### Offers & Documents
- offer creation
- PDF generation
- cover sheets
- sub-PDF workflows
- signed-document upload and retrieval

### Pricebook
- centralized item management
- filtering
- editing permissions
- bulk price adjustments

### Users & Permissions
- authentication with Laravel Sanctum
- role and permission management
- invitation system
- user activation / deactivation
- user-specific pricing modifiers

### Project Management
- project creation and maintenance
- project-linked calculations
- construction schedule / planning feature

### Auditability
- audit log for relevant changes
- permission-protected administrative views

---

## Architecture

```text
┌────────────────────────┐
│ React + TypeScript UI  │
└───────────┬────────────┘
            │ REST API
            ▼
┌────────────────────────┐
│     Laravel Backend    │
│ Sanctum + Permissions  │
└───────────┬────────────┘
            │
            ▼
┌────────────────────────┐
│   MySQL / MariaDB      │
└────────────────────────┘

            │
            ├── PDF generation
            ├── signed documents
            └── audit / invitation workflows
```

---

## Technology Stack

- **Frontend:** React, TypeScript, Vite, Tailwind CSS
- **Backend:** Laravel / PHP
- **Authentication:** Laravel Sanctum
- **Authorization:** Spatie Permission
- **Database:** MySQL / MariaDB
- **PDF:** DomPDF
- **API:** REST / JSON
- **Deployment:** shared hosting / Linux-compatible production setup

---

## Engineering Challenges

Key engineering areas included:

- translating complex business-pricing logic into maintainable software
- keeping calculation and pricebook logic consistent across users
- separating permissions for viewing, creating, editing and deleting business objects
- handling professional PDF output from structured application data
- implementing invitation and user-management workflows
- supporting user-specific pricing behavior without duplicating pricebook data

---

## My Role

**Full-stack development, deployment and maintenance.**

I planned the application structure, implemented the backend and REST API, built the React frontend, designed the database, implemented business logic, permissions and PDF workflows, and maintain the production application.

---

## Screenshots

Recommended screenshots for the public portfolio:

1. dashboard / project overview
2. renovation calculation screen
3. pricebook
4. generated offer / PDF preview
5. construction schedule / Gantt view
6. user / role management

---

> Production data, customer information, pricing data and private source code remain confidential. This case study focuses on architecture, functionality and engineering scope.
