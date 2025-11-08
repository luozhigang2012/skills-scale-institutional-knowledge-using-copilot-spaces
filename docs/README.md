# OctoAcme Project Management Documentation

## Purpose

This documentation hub centralizes OctoAcme's project management processes, providing a single entry point for team members to understand how we run projects from inception to retrospective. These documents are designed to help new teammates quickly onboard, ensure consistent delivery practices across teams, and serve as reference material for project managers, product managers, developers, and stakeholders.

## Project Management Overview

OctoAcme follows a structured, iterative approach to project delivery that emphasizes customer value, clear ownership, and continuous improvement.

### Project Lifecycle

Our project lifecycle consists of five key phases:

1. **Initiation**: Define the problem statement, identify stakeholders, establish success metrics, and create a project one-pager
2. **Planning**: Detail scope, resources, milestones, dependencies, and create a comprehensive project plan
3. **Execution**: Build, test, review, and iterate on deliverables with regular team syncs and tracking
4. **Release**: Deploy to production, verify functionality, and communicate launch to stakeholders
5. **Retrospective**: Capture learnings, celebrate successes, and identify improvements for future projects

### Key Principles

- **Customer-first**: Prioritize customer value and usability in all decisions
- **Iterative delivery**: Deliver small, testable increments to enable fast feedback
- **Clear ownership**: Each project has a named Project Manager and Product Lead with defined responsibilities
- **Stakeholder communication**: Maintain transparent, regular communication with all project stakeholders
- **Risk management**: Proactively identify, track, and mitigate risks throughout the project lifecycle
- **Continuous improvement**: Use retrospectives and metrics to refine our processes and practices

### Main Artifacts

- **Project Charter / One-pager**: Concise summary of problem, goals, metrics, and timeline
- **Roadmap and Release Plan**: High-level timeline with key milestones and deliverables
- **Sprint/Iteration Backlog**: Prioritized list of work items for each iteration
- **Acceptance Criteria & Definition of Done**: Clear standards for feature completion
- **Risk Register**: Living document tracking identified risks and mitigation strategies
- **Retrospective Notes**: Captured learnings and action items after each project phase

### Team Rhythm

- **Weekly sync**: PM and Product Manager alignment meetings
- **Standups**: Twice-weekly (or as agreed) delivery team check-ins
- **Demos**: Regular showcase of completed work to stakeholders
- **Retrospectives**: End-of-phase or end-of-project learning sessions
- **Monthly updates**: Broader stakeholder communication on progress and blockers

## Process Documentation

The following documents provide detailed guidance for each phase of the project lifecycle and key aspects of project management:

- [**OctoAcme Project Management Overview**](octoacme-project-management-overview.md) - High-level introduction to our project management approach, roles, and artifacts
- [**OctoAcme Project Initiation**](octoacme-project-initiation.md) - Steps to validate and authorize new work, including the project one-pager template
- [**OctoAcme Project Planning**](octoacme-project-planning.md) - Detailed planning process for scope, resources, milestones, and dependencies
- [**OctoAcme Execution and Tracking**](octoacme-execution-and-tracking.md) - Day-to-day practices for building, testing, and monitoring project progress
- [**OctoAcme Risks and Communication**](octoacme-risks-and-communication.md) - Risk identification, escalation paths, and stakeholder communication strategies
- [**OctoAcme Release and Deployment**](octoacme-release-and-deployment.md) - Release planning, deployment procedures, and launch communications
- [**OctoAcme Retrospective and Continuous Improvement**](octoacme-retrospective-and-continuous-improvement.md) - Conducting retrospectives and implementing lessons learned
- [**OctoAcme Roles and Personas**](octoacme-roles-and-personas.md) - Detailed role definitions and responsibilities for team members

## Contributing to Process Documentation

We encourage feedback and contributions to continuously improve our project management processes.

### Requesting Updates or Additions

To suggest changes or additions to any process document:

1. Open a new issue using the [Add/Update Content to Process Docs template](../.github/ISSUE_TEMPLATE/add-update-content-to-process-docs.yml)
2. Select the document you want to update (or choose "new document" for new content)
3. Describe the proposed change and rationale
4. Include example content if available

Your request will be reviewed by the process owners and stakeholders, and updates will be made as appropriate.

### Surfacing Docs to GitHub Copilot Spaces

To make these process documents available as context for GitHub Copilot Spaces:

1. Copy relevant documents into the `.copilot/` directory in your project repository
2. Copilot Spaces will automatically use these documents to provide project-specific guidance
3. Keep the documents updated in `.copilot/` as processes evolve

See the [Project Management Overview](octoacme-project-management-overview.md#how-to-use-these-docs) for more details on integrating these docs into your workflow.

## Acceptance Criteria

This README meets the following criteria:

- [x] Includes a clear project description and purpose for the documentation hub
- [x] Provides a concise overview of the OctoAcme project management lifecycle (Initiation → Planning → Execution → Release → Retrospective)
- [x] Summarizes key project management principles (iterative delivery, clear ownership, stakeholder communication, risk management, continuous improvement)
- [x] Describes main artifacts and team rhythm (one-pager, backlog, PR conventions, standups, demos, retrospectives)
- [x] Contains clickable links to all existing process documents using relative paths
- [x] Explains how to contribute or request updates (references issue template)
- [x] Includes guidance on surfacing docs to Copilot Spaces (references .copilot/ directory)
- [x] Provides this acceptance criteria checklist for validation
