# OctoAcme Project Management Documentation

Welcome to the OctoAcme Project Management Docs! This is your comprehensive guide to how we run projects, from initial concept through retrospective and continuous improvement.

## Quick Start by Role

- **Project Managers:** Start with [Project Management Overview](./octoacme-project-management-overview.md), then [Risk Management & Communication](./octoacme-risks-and-communication.md)
- **Product Managers:** Review [Project Initiation](./octoacme-project-initiation.md) and [Project Planning](./octoacme-project-planning.md)
- **Developers:** See [Execution & Tracking](./octoacme-execution-and-tracking.md) and [Release & Deployment](./octoacme-release-and-deployment.md)
- **All Roles:** Understand [OctoAcme Personas](./octoacme-roles-and-personas.md)

## OctoAcme Project Management Overview

OctoAcme follows a structured, lifecycle-based approach to project management grounded in five core principles: **customer-first delivery**, **iterative development**, **clear ownership**, **data-informed decisions**, and **psychological safety**. The organization manages projects through five distinct phases—Initiation, Planning, Execution, Release, and Retrospective—each with defined deliverables and decision gates. Projects are sponsored by named roles including a Project Manager (PM) who coordinates delivery and timelines, a Product Manager (PdM) who defines outcomes and prioritizes work, and supporting developers and QA teams. This role clarity ensures accountability and reduces confusion as projects progress from concept through production deployment.

The execution model emphasizes iterative delivery with a structured team rhythm that includes daily standups (15 minutes), weekly delivery syncs, and sprint-based planning cycles. Work is managed through a project board with standardized columns (Backlog, Ready, In Progress, In Review, QA, Done), and pull requests are kept small (≤400 lines when possible) to facilitate fast review cycles. Quality assurance is built into every phase through unit and integration testing, automated CI/CD pipelines with security scanning, and manual QA acceptance checks. OctoAcme also maintains a Risk Register throughout the project lifecycle, updating it weekly and escalating blockers through defined levels: team-level triage → PM escalation → Product Lead involvement → Sponsor escalation for business-critical issues.

Communication and transparency are central to OctoAcme's success. Stakeholder updates follow a standard template covering weekly progress, next steps, risks, and decisions needed, with monthly updates to broader stakeholder groups. The organization documents all key artifacts—including Project Charters, acceptance criteria, release notes, and retrospective action items—in version-controlled repositories, often within a `.copilot/` directory for easy access by team members and AI assistants. After each sprint, release, or milestone, the team conducts structured retrospectives (45–75 minutes) to capture learnings and assign actionable improvements with clear owners and due dates. This combination of defined workflows, regular communication cadence, and continuous improvement culture enables OctoAcme teams to deliver features reliably while maintaining alignment across engineering, product, and business stakeholders.

## Process Lifecycle Overview

OctoAcme projects follow a structured lifecycle across five phases:

1. **Initiation** - Validate the problem and align stakeholders
2. **Planning** - Create actionable plans and backlog
3. **Execution & Tracking** - Manage day-to-day delivery
4. **Release & Deployment** - Deploy to production safely
5. **Retrospective & Continuous Improvement** - Learn and improve

## Core Principles

- **Customer-first:** prioritize customer value and usability
- **Iterative delivery:** deliver small, testable increments
- **Clear ownership:** each project has a named PM and Product Lead
- **Data-informed decisions:** measure impact and iterate
- **Psychological safety:** encourage feedback and learning

## Complete Documentation Index

- [OctoAcme Project Management Overview](./octoacme-project-management-overview.md) - High-level introduction, roles, and lifecycle
- [Project Initiation Guide](./octoacme-project-initiation.md) - Steps to validate and authorize work
- [Project Planning](./octoacme-project-planning.md) - Turn initiatives into actionable plans
- [Execution & Tracking](./octoacme-execution-and-tracking.md) - Day-to-day execution and progress management
- [Risk Management & Communication](./octoacme-risks-and-communication.md) - Identify and manage risks, communicate status
- [Release & Deployment Guide](./octoacme-release-and-deployment.md) - Standardize how we release to production
- [Retrospective & Continuous Improvement](./octoacme-retrospective-and-continuous-improvement.md) - Capture learnings and iterate
- [OctoAcme Personas](./octoacme-roles-and-personas.md) - Role definitions and responsibilities

## How to Use These Docs

- Keep your project charter in your project repo
- Use the relevant process doc as your guide for each lifecycle phase
- Add process-specific docs to `.copilot/` if using Copilot Spaces
- Update these docs with team learnings and improvements
