# OctoAcme Role Participation Matrix

## Purpose
Define how each role participates in different project phases and ceremonies to ensure clear accountability and prevent gaps in project execution.

## Role Participation by Project Phase

### Project Initiation

| Role | Participation Level | Key Activities |
|------|-------------------|----------------|
| **Project Manager** | Lead | Facilitate kickoff, create project charter, establish communication plan |
| **Product Manager** | Lead | Define problem statement, success metrics, initial requirements |
| **Product Owner** | Active | Review and validate backlog approach, ensure alignment with product strategy |
| **Stakeholder Representative** | Active | Provide business context, validate problem statement, approve charter |
| **Developers** | Consulted | Provide technical feasibility input, initial effort estimates |
| **QA Lead** | Consulted | Review success metrics for testability, identify quality risks |
| **DevOps Engineer** | Consulted | Assess infrastructure needs, deployment complexity |
| **Agile Coach** | Informed | Review team structure and suggest process improvements |

### Project Planning

| Role | Participation Level | Key Activities |
|------|-------------------|----------------|
| **Project Manager** | Lead | Create detailed project plan, manage dependencies, track milestones |
| **Product Owner** | Lead | Prioritize and refine backlog, define user stories with acceptance criteria |
| **Product Manager** | Active | Validate priorities align with roadmap, confirm success metrics |
| **Developers** | Active | Break down stories, provide detailed estimates, identify technical risks |
| **QA Lead** | Active | Create test strategy, review acceptance criteria, plan test automation |
| **DevOps Engineer** | Active | Plan infrastructure setup, CI/CD pipeline requirements |
| **Agile Coach** | Active | Facilitate planning sessions, ensure proper estimation and commitment |
| **Stakeholder Representative** | Consulted | Review and approve scope, provide constraints and requirements |

### Execution & Tracking

| Role | Participation Level | Key Activities |
|------|-------------------|----------------|
| **Developers** | Lead | Implement features, write tests, conduct code reviews |
| **Product Owner** | Lead | Answer questions, refine stories, accept completed work |
| **QA Lead** | Active | Execute test plans, report defects, validate quality metrics |
| **DevOps Engineer** | Active | Maintain CI/CD pipeline, monitor build health, support deployments |
| **Agile Coach** | Active | Facilitate standups and retrospectives, remove impediments |
| **Project Manager** | Active | Track progress, manage risks, communicate status |
| **Product Manager** | Consulted | Review progress, adjust priorities based on learnings |
| **Stakeholder Representative** | Informed | Receive status updates, provide feedback on demos |

### Release & Deployment

| Role | Participation Level | Key Activities |
|------|-------------------|----------------|
| **DevOps Engineer** | Lead | Execute deployment, monitor systems, handle rollbacks if needed |
| **Product Owner** | Lead | Final acceptance, go/no-go decision, release notes approval |
| **QA Lead** | Active | Execute smoke tests, monitor quality metrics, verify acceptance criteria |
| **Project Manager** | Active | Coordinate release activities, manage communication, track issues |
| **Product Manager** | Active | Validate release meets success criteria, prepare announcements |
| **Developers** | Active | Support deployment, fix critical issues, update documentation |
| **Stakeholder Representative** | Consulted | Approve release for their domain, prepare their teams |
| **Agile Coach** | Informed | Observe release process for improvement opportunities |

### Retrospective & Continuous Improvement

| Role | Participation Level | Key Activities |
|------|-------------------|----------------|
| **Agile Coach** | Lead | Facilitate retrospective, capture insights, track action items |
| **Project Manager** | Lead | Document lessons learned, update process docs, follow up on actions |
| **Product Owner** | Active | Share feedback on backlog process, suggest product improvements |
| **Developers** | Active | Provide technical insights, suggest engineering improvements |
| **QA Lead** | Active | Share quality insights, propose testing improvements |
| **DevOps Engineer** | Active | Share operational insights, suggest infrastructure improvements |
| **Product Manager** | Active | Share outcome data, validate success metrics achieved |
| **Stakeholder Representative** | Consulted | Provide stakeholder feedback and business impact assessment |

## Participation Levels Defined

- **Lead**: Primary owner, responsible for driving outcomes and deliverables
- **Active**: Regular participation, significant contributions to decisions and work
- **Consulted**: Provides input and expertise when needed, reviews key deliverables
- **Informed**: Receives updates and information, minimal active participation

## Key Ceremonies and Role Participation

### Daily Standup
- **Lead**: Agile Coach (facilitates)
- **Active**: Developers, QA Lead, DevOps Engineer, Product Owner
- **Informed**: Project Manager, Product Manager

### Sprint Planning
- **Lead**: Product Owner, Agile Coach
- **Active**: Developers, QA Lead, DevOps Engineer
- **Consulted**: Project Manager, Product Manager
- **Informed**: Stakeholder Representative

### Sprint Review/Demo
- **Lead**: Product Owner
- **Active**: Developers, Project Manager, Product Manager
- **Consulted**: Stakeholder Representative, QA Lead
- **Informed**: All roles invited

### Sprint Retrospective
- **Lead**: Agile Coach
- **Active**: All team members (Developers, Product Owner, QA Lead, DevOps Engineer)
- **Consulted**: Project Manager
- **Informed**: Product Manager, Stakeholder Representative (upon request)

### Backlog Refinement
- **Lead**: Product Owner
- **Active**: Developers, QA Lead
- **Consulted**: Product Manager, DevOps Engineer
- **Informed**: Project Manager

## Accountability Framework

### Clear Ownership Principles
1. Every deliverable has a single accountable owner (one role is "Lead")
2. Decisions are made by those closest to the work with appropriate input
3. Escalation paths are clear when consensus cannot be reached
4. All roles understand their participation level for each activity

### Preventing Gaps
- Use this matrix during project initiation to assign specific people to roles
- Review participation in retrospectives to identify missing perspectives
- Update matrix when new processes or ceremonies are introduced
- Ensure all critical activities have a "Lead" role assigned

## Reference
This matrix implements improvements identified in [Issue #5](https://github.com/luozhigang2012/skills-scale-institutional-knowledge-using-copilot-spaces/issues/5) to address gaps in accountability and role clarity across project phases.
