# CHANTIER — Contractor & Field Operations

A simple job companion in development for independent painters, handymen and small home-renovation contractors, working alone or with a few helpers.

**Status: working local v1 prototype · fictional data · private implementation.**

## Simple first\n\nThe default owner view is **Today · Jobs · Costs**. Add a job with three required fields, enter notes inside its job card and record solo expenses without a separate approver. Detailed crew and approval tools are optional.\n\nQuotes, accepted scope, customer balances, payment records and photo receipts are prioritized next; they are not implemented yet. [Research and usability direction](docs/simple-design.md).\n\n## What v1 demonstrates

| Workspace | Working local capability |
| --- | --- |
| Projects | Project/site/customer register, work orders and completion gates |
| Employees and crews | Fictional roster, qualifications, crews and visit assignments |
| Schedule | Availability, absence, qualification, conflict and travel checks |
| Field activity | Progress notes, inspection notes, blockers and punch items |
| Time and materials | Employee submission and independent approval/return |
| Job costs | Approved labour/material costs and project budget remaining |
| Completion | Visit finish, work submission and manager approval or rework |
| Documents | Drawing/document reference and revision register |
| Traceability | Transactional audit records, retry protection and verified recovery |

The demonstration contains **4 projects, 6 work orders, 3 crews, 8 people and 4 scheduled visits**, with connected exceptions and pending reviews. **39 automated tests** validate workflows, booking concurrency, scoped records, approvals, costing, recovery and rendered forms.

All operating records and outcomes are simulated. No client deployment, endorsement, measured time saving or profitability improvement is claimed.

## Product and delivery

- [Business case](docs/business-case.md)
- [V1 scope and release direction](docs/v1-overview.md)

CHANTIER is independent from PRAXIS — Business Process Optimization & Automation. Each has its own scope and repositories.

## Current limits

This is a local demonstration with a simulated actor selector. It is not authenticated login: anyone using the demo can select a manager. Secure accounts, production company isolation, stored photos/files, French translation, real-device visual validation, offline synchronization, billing/payments and store distribution remain outstanding.

Current documents are references rather than uploaded files. Internal budget decisions do not represent customer approvals. Remaining budget is not profit. No live SEAO integration or automated bid submission is implemented.

Application screenshots and the portfolio thumbnail are pending visual review; no mockups are presented as verified captures.

## Technology and professional scope

**Python · SQL / SQLite · Streamlit · Business analysis · Workflow design · Scheduling constraints · Job costing · Automated testing**

This public repository contains presentation material only. Application code, detailed architecture, fixtures, internal rules and development tests remain private.

Copyright © 2026. All rights reserved. No open-source licence or implementation rights are granted.
