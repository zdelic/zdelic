# Construction Budget & Cost Controlling

## Budget Planning & Cost Tracking Application

A business application for project-level budget planning, cost tracking and financial controlling in construction projects.

---

## Business Problem

Project managers need a practical way to compare planned budgets with incoming costs, assign costs to accounts and sub-accounts, and keep a transparent overview of project financial performance.

The application centralizes these workflows and replaces fragmented spreadsheet-based tracking.

---

## What I Built

I developed the application with responsibility for:

- application architecture
- Python / Flask backend
- database model
- role-based user access
- project assignments
- budget and cost workflows
- account and sub-account structures
- data import / processing logic
- reporting views
- deployment and maintenance

---

## Core Features

### Budget Management
- project-level budgets
- planned cost structures
- account and sub-account grouping
- budget updates and historical tracking

### Cost Controlling
- project cost entries
- comparison of planned vs. actual values
- additional-cost / variation workflows
- financial overview by project

### Users & Projects
- role-based access
- user-to-project assignment
- project-specific views

### Data Processing
- import and parsing workflows
- PDF / text data processing
- structured cost data handling

---

## Architecture

```text
Web UI / Jinja Views
        │
        ▼
   Flask Application
        │
        ├── Authentication / Roles
        ├── Budget Logic
        ├── Cost Logic
        ├── Import / Parsing
        └── Reporting
        │
        ▼
   SQLAlchemy / SQLite
```

---

## Technology Stack

- **Backend:** Python, Flask
- **ORM:** SQLAlchemy
- **Database:** SQLite
- **Frontend:** Jinja templates, HTML / CSS / JavaScript
- **Security:** Flask-Security, CSRF protection, role-based authorization
- **Document Processing:** PyMuPDF

---

## Engineering Challenges

Key areas included:

- modeling construction cost structures in a maintainable database
- assigning users to projects and enforcing project-scoped access
- comparing planned and actual cost data
- parsing external source data into structured application records
- keeping budget and cost views understandable for non-technical users

---

## My Role

**Full-stack development and maintenance.**

I designed the data model, implemented the backend logic, built the application views and workflows, and maintained the system as an internal business application.

---

## Screenshots

Recommended public screenshots:

1. project budget overview
2. planned vs. actual costs
3. account / sub-account structure
4. cost-entry workflow
5. reporting / controlling view

---

> Real project financial data and production source code remain private. This case study documents the functionality and engineering scope only.
