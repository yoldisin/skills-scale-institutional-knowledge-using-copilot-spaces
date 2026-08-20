# OctoAcme Project Management Process Documentation

## Overview

This directory contains the complete OctoAcme project management framework, a set of lightweight, iterative processes designed to deliver customer value efficiently.

### OctoAcme Principles

- **Customer-first**: Prioritize customer value and usability
- **Iterative delivery**: Deliver small, testable increments
- **Clear ownership**: Each project has a named PM and Product Lead
- **Data-informed decisions**: Measure impact and iterate based on evidence
- **Psychological safety**: Encourage feedback and learning

## OctoAcme Project Management Process Summary

OctoAcme follows a structured, customer-first project lifecycle built on clear ownership, iterative delivery, and data-informed decision-making. The organization defines five core phases: **Initiation** (validating business need and stakeholder alignment), **Planning** (breaking work into shippable increments with acceptance criteria), **Execution** (day-to-day delivery with regular demos and quality gates), **Release** (standardized deployment with rollback readiness), and **Retrospective** (capturing learnings and continuous improvement). Each project is anchored by a lightweight Project One-pager that establishes the problem statement, success metrics, stakeholders, and initial timeline, ensuring teams move forward only when these foundations are solid.

The organization operates with clear role delineation: **Project Managers** coordinate schedules, risks, and cross-team communication; **Product Managers** define outcomes and prioritize the backlog; **Developers** implement features and collaborate on quality; and **QA/Testing** validates acceptance criteria. This separation of concerns—combined with regular touchpoints including daily standups (15 min), weekly delivery syncs, and monthly stakeholder updates—ensures alignment without creating bottlenecks. Escalation paths are well-defined, moving from team-level triage through the PM, Product Lead, and up to sponsors for business-impacting issues.

Quality and risk management are embedded throughout execution rather than bolted on at the end. OctoAcme maintains a **Risk Register** tracking impact, likelihood, and mitigation strategies; requires unit tests, integration tests, and security scanning in CI; enforces small PRs (≤400 lines) with at least one approval before merging; and uses project boards (e.g., GitHub Projects) with clear workflow columns (Backlog → Ready → In Progress → In Review → QA → Done). Before release, teams must confirm passing CI, drafted release notes, a rollback plan, and smoke test preparation, reducing the likelihood of production incidents.

Continuous improvement is codified through structured retrospectives held after sprints, releases, or milestones, where teams reflect on what went well, what could improve, and commit to 2–3 prioritized action items with assigned owners and due dates. This cycle of feedback, action, and measurement—combined with transparent communication templates for weekly status and incident response—creates a learning culture that evolves the process itself over time while maintaining psychological safety and accountability.

## Project Lifecycle & Documentation

OctoAcme projects follow a structured lifecycle. Use this guide to find the right document for your current phase:

### 1. **Initiation** → [Project Initiation Guide](octoacme-project-initiation.md)
   Validate business need, identify stakeholders, define success metrics

### 2. **Planning** → [Project Planning](octoacme-project-planning.md)
   Break work into increments, estimate scope, identify dependencies

### 3. **Execution & Tracking** → [Execution & Tracking](octoacme-execution-and-tracking.md)
   Daily standups, sprint management, quality assurance, blocker escalation

### 4. **Risk & Communication** → [Risk Management & Communication](octoacme-risks-and-communication.md)
   Maintain risk register, communicate with stakeholders, escalate issues

### 5. **Release & Deployment** → [Release & Deployment Guide](octoacme-release-and-deployment.md)
   Pre-release checks, deployment procedures, rollback plans

### 6. **Retrospective & Improvement** → [Retrospective & Continuous Improvement](octoacme-retrospective-and-continuous-improvement.md)
   Capture learnings, identify improvements, track action items

## Reference Documents

- [Project Management Overview](octoacme-project-management-overview.md) — High-level introduction to OctoAcme's approach and key roles
- [Roles & Personas](octoacme-roles-and-personas.md) — Detailed descriptions of PM, PdM, Developer, and QA responsibilities

## How to Use These Docs

- Keep the Project Charter updated in your project repo
- Add process-specific docs into `.copilot/` if you want Copilot Spaces to use them as context
- For questions or improvements, open an issue using the [Add Content to Project Management Process Docs](../.github/ISSUE_TEMPLATE/add-update-content-to-process-docs.yml) template

## Contributing to OctoAcme Documentation

These process documents are living artifacts. If you identify gaps, have improvements, or want to add new processes:

1. Review the existing documents to understand current practices
2. Use the [Add Content to Project Management Process Docs](../.github/ISSUE_TEMPLATE/add-update-content-to-process-docs.yml) issue template
3. Include rationale, suggested content, and acceptance criteria
4. Work with the team to validate and merge improvements

Your feedback helps make OctoAcme processes clearer and more effective for everyone.
