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
- planned-vs-actual progress tracking
- project statistics and status monitoring

---

## Core Features

### Project Structure
- project creation and retrieval
- hierarchical building structure
- project-specific process-model assignment
- planned start-date handling
- reusable structures across projects

### Process Models
- reusable process templates
- activity assignment by trade
- duration planning
- sequential and parallel activities
- copying and updating process models

### Trades & Activities
- centralized trade management
- color-coded trades
- activity management
- bulk activity saving
- replace-all workflows

### Tasks & Timeline
- project-linked tasks
- task dependencies and links
- structure-based timeline view
- status visualization
- planned and actual dates
- delayed-task indicators
- Gantt-compatible data endpoints

### Monitoring & Reporting
- task statistics by trade
- completion-status charts
- planned-vs-actual progress curve
- activity overview with filtering
- CSV export

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
- **Reporting:** charts, filters and CSV export

---

## Screenshots

### Project Statistics

Project-level monitoring with total task counts, completion status and breakdown by construction trade.

![Project statistics](../assets/gerstl-management/gerstl-management-project-statistics.jpg)

### Project Structure

Hierarchical project setup with building sections, stairs, floors, units and reusable process-model assignments.

![Project structure](../assets/gerstl-management/gerstl-management-project-structure.jpg)

### Planned vs. Actual Progress

A cumulative planned-vs-actual progress curve for tracking schedule performance over time.

![Planned vs actual progress](../assets/gerstl-management/gerstl-management-planned-actual.jpg)

### Process Model Editor

Reusable construction process templates combine trades, activities, durations and sequencing rules.

![Process model editor](../assets/gerstl-management/gerstl-management-process-model.jpg)

### Trades & Activities

Central administration of construction trades and their related activities, including color coding and editing workflows.

![Trades and activities](../assets/gerstl-management/gerstl-management-trades-activities.jpg)

### Project Timeline / Gantt

Structure-based project timeline showing scheduled activities, statuses, dependencies and task-level details.

![Project timeline](../assets/gerstl-management/gerstl-management-timeline.jpg)

### Activity List

Operational activity overview with structure filters, planned and actual dates, status, sub-assignment and delay indicators.

![Activity list](../assets/gerstl-management/gerstl-management-activity-list.jpg)

---

## Engineering Challenges

The core challenge was modeling a construction process in a way that is reusable across projects while preserving project-specific tasks, links and schedule data.

This required careful separation between process templates, project structures, activities and task instances, while also supporting timeline visualization, planned-vs-actual comparisons and project-level statistics.

---

## My Role

**Full-stack architecture and implementation.**

I designed the data flows, implemented the Laravel API and business logic, built the frontend integration and developed the project timeline, reusable process-model and project-monitoring workflows.

---

> Production source code and internal company data remain private. The screenshots shown here are portfolio-safe versions prepared to demonstrate the product architecture and functionality without exposing confidential information.
