# CHANTIER — Contractor & Field Operations

A simple job companion in development for independent painters, handymen and small home-renovation contractors, working alone or with a few helpers.

**Status: working local v1 prototype · fictional data · private implementation.**

## Simple first

The default owner view is **Today · Jobs · Money**. Add a job with three required fields, enter notes inside its job card and record solo expenses without a separate approver. Detailed crew and approval tools are optional.

Quotes, manually recorded customer decisions, agreed extras, payment/refund/reversal records, remaining customer balances and validated local photo/receipt storage are implemented. These are local records; no actual payment is processed. [Research and usability direction](docs/simple-design.md).

## What v1 demonstrates

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

The default opt-in demonstration contains **4 fictional home jobs and 3 roster records**, with quotes, a deposit, a paid completed job, expenses and dates anchored to setup day. The private implementation documents **62 automated tests**; that count is its recorded development baseline, not a fresh execution during this documentation update.

All operating records and outcomes are simulated. No client deployment, endorsement, measured time saving or profitability improvement is claimed.

## Product and delivery

- [Business case](docs/business-case.md)
- [V1 scope and release direction](docs/v1-overview.md)

CHANTIER is independent from PRAXIS — Business Process Optimization & Automation. Each has its own scope and repositories.

## Current limits

This is a local demonstration with a simulated actor selector. It is not authenticated login: anyone using the demo can select a manager. Secure accounts, production company isolation, hosted file access, French translation, real-device visual validation, offline synchronization, compliant invoicing, integrated payment processing and store distribution remain outstanding.

Current documents are references rather than uploaded files. Internal budget decisions do not represent customer approvals. Remaining budget is not profit. No live SEAO integration or automated bid submission is implemented.

Application screenshots and the portfolio thumbnail are pending visual review; no mockups are presented as verified captures.

## Technology and professional scope

**Python · SQL / SQLite · Streamlit · Business analysis · Workflow design · Scheduling constraints · Job costing · Automated testing**

This public repository contains presentation material only. Application code, detailed architecture, fixtures, internal rules and development tests remain private.

Copyright © 2026. All rights reserved. No open-source licence or implementation rights are granted.

## Who it benefits

Independent painters, handymen and small renovation contractors, working alone or with a few helpers: a quick daily view of jobs, expenses, agreed work and recorded customer balances.

These are intended users and benefits, not evidence of adoption or measured customer outcomes.
