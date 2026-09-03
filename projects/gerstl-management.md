# Construction Process Management CRM

## Project Timeline & Workflow Management System

A full-stack construction process-management application for organizing projects, reusable process models, trades, activities, tasks, dependencies and timeline data.

---

## Business Problem

Construction projects involve many dependent activities that need to be structured consistently across projects while still allowing project-specific planning and progress tracking.

The application provides a reusable process model and project timeline structure instead of managing these workflows through disconnected spreadsheets or static schedules.

---

## What I Built

I implemented the full-stack application architecture, including:

- Laravel backend
- authenticated REST API
- React-based frontend
- project and structure management
- reusable process models
- trades and activity management
- task creation and linking
- project timeline / Gantt data
- user authentication and role-based access

---

## Core Features

### Project Structure
- project creation and retrieval
- project-specific structure data
- user-authenticated access

### Process Models
- reusable process templates
- activity assignment
- copying and updating process models

### Trades & Activities
- trade management
- activity management
- bulk activity saving
- replace-all workflows

### Tasks & Timeline
- project-linked tasks
- task dependencies
- task links
- project timeline data
- Gantt-compatible data endpoints

### Authentication & Roles
- Laravel Sanctum authentication
- role-protected areas
- admin and site-management access patterns

---

## Architecture

```text
React Frontend
      │
      │ REST / JSON
      ▼
Laravel API
      │
      ├── Projects
      ├── Structures
      ├── Process Models
      ├── Trades / Activities
      └── Tasks / Timeline
      │
      ▼
Database
```

---

## Technology Stack

- **Backend:** Laravel / PHP
- **Frontend:** React, Vite, Tailwind CSS
- **Authentication:** Laravel Sanctum
- **API:** REST / JSON
- **Planning:** timeline and Gantt-compatible task data

---

## Engineering Challenges

The core challenge is modeling a construction process in a way that is reusable across projects while preserving project-specific tasks, links and schedule data.

This required careful separation between process templates, project structures, activities and task instances.

---

## My Role

**Full-stack architecture and implementation.**

I designed the data flows, implemented the Laravel API and business logic, built the frontend integration and developed the project timeline / process-management workflows.

---

## Screenshots

Recommended public screenshots:

1. project overview
2. process model editor
3. project structure
4. activity / trade management
5. timeline or Gantt screen

---

> This portfolio case study describes the technical scope without exposing internal company data or private production source code.
