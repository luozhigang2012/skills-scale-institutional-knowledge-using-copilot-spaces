# OctoAcme Personas

This document defines typical roles and responsibilities used in OctoAcme project docs and exercises.

---

## Developers

### Role Summary
Developers design, build, test, and deliver software components. They collaborate with product and project leads to implement features that meet acceptance criteria and quality standards.

### Responsibilities
- Implement features and fixes to meet acceptance criteria
- Write and maintain tests and documentation
- Participate in design and code reviews
- Assist in estimating and planning work
- Help identify technical risks and propose mitigations

### Goals
- Deliver reliable, maintainable code
- Reduce cycle time from idea to production
- Maintain high test coverage and observability

### Typical Communication
- Daily standups and sprint planning
- PR descriptions and code review comments
- Technical design docs when needed

---

## Product Managers

### Role Summary
Product Managers define what should be built to deliver customer and business value. They own the product vision, prioritize the backlog, and measure outcomes.

### Responsibilities
- Define problem statements and success metrics
- Prioritize the roadmap and backlog
- Collaborate with stakeholders and engineering on trade-offs
- Validate solutions through user research and metrics

### Goals
- Maximize customer value and impact
- Make clear, data-driven prioritization decisions
- Ensure product-market fit and usability

### Typical Communication
- Weekly alignment with PM and engineering leads
- Roadmap updates and stakeholder briefings
- Acceptance criteria and feature specs

---

## Project Managers

### Role Summary
Project Managers coordinate delivery activities, manage schedules, risks, and communications. They enable the team to deliver on commitments efficiently.

### Responsibilities
- Create and maintain project plans and timelines
- Manage risks, dependencies, and resource constraints
- Facilitate meetings (kickoff, planning, retrospectives)
- Ensure consistent project documentation and status reporting
- Coordinate cross-team and stakeholder communication

### Goals
- Deliver projects on time and within scope
- Minimize unplanned work and escalations
- Maintain transparency and alignment across stakeholders

### Typical Communication
- Weekly status updates and stakeholder reports
- Risk registers and decision logs
- Coordination via project boards and meeting facilitation

---

## Product Owner

### Role Summary
Product Owners represent the voice of the customer and maximize the value of the product. They maintain and prioritize the product backlog, ensuring the team works on the highest-value items and that user stories have clear acceptance criteria.

### Responsibilities
- Own and prioritize the product backlog
- Define and refine user stories with clear acceptance criteria
- Make trade-off decisions on scope, features, and technical debt
- Accept or reject work based on Definition of Done
- Collaborate with Product Managers on strategy and roadmap alignment
- Ensure the team understands backlog items and their business value

### Goals
- Maximize product value and return on investment
- Ensure team focuses on highest-priority work
- Maintain a healthy, well-groomed backlog
- Enable fast decision-making on scope and priorities

### Typical Communication
- Daily backlog refinement and priority updates
- Sprint planning and review participation
- Stakeholder demos and acceptance sessions
- Clear acceptance criteria and user story documentation

### Interactions with Other Roles
- **Product Managers**: Aligns on product strategy, roadmap, and long-term vision
- **Developers**: Clarifies requirements, answers questions, provides feedback on implementation
- **QA Lead**: Collaborates on acceptance criteria and testing strategies
- **Project Managers**: Coordinates on timeline impacts of priority changes
- **Stakeholder Representatives**: Gathers input and validates priorities against business needs

---

## Stakeholder Representative

### Role Summary
Stakeholder Representatives advocate for specific business areas, user groups, or organizational interests. They provide domain expertise, validate requirements, and ensure project outcomes align with stakeholder needs and constraints.

### Responsibilities
- Represent the needs and constraints of their stakeholder group
- Provide domain expertise and business context
- Review and approve deliverables that impact their area
- Participate in key decision points and milestone reviews
- Escalate concerns and risks affecting their stakeholders
- Ensure compliance with relevant policies and standards

### Goals
- Ensure stakeholder interests are considered in project decisions
- Prevent misalignment between deliverables and business needs
- Enable informed decision-making with domain expertise
- Maintain stakeholder engagement and satisfaction

### Typical Communication
- Milestone reviews and key decision meetings
- Requirements validation and approval sessions
- Feedback on prototypes and demos
- Escalation of risks and concerns to leadership

### Interactions with Other Roles
- **Product Owner**: Provides input on priorities and validates user stories
- **Product Managers**: Shares stakeholder feedback and business requirements
- **Project Managers**: Receives status updates and provides approvals
- **Agile Coach**: Participates in ceremonies and provides stakeholder perspective
- **All Team Members**: Available for questions and clarifications on business needs

---

## Agile Coach

### Role Summary
Agile Coaches guide teams in adopting and improving agile practices. They facilitate ceremonies, remove impediments, and foster a culture of continuous improvement and psychological safety.

### Responsibilities
- Facilitate agile ceremonies (standups, retrospectives, planning)
- Coach team members on agile principles and practices
- Identify and help remove organizational impediments
- Foster psychological safety and team collaboration
- Guide teams through agile transformations and improvements
- Promote transparency and data-driven decision making
- Support Scrum Masters and team leads in their roles

### Goals
- Enable team self-organization and continuous improvement
- Improve team velocity, quality, and predictability
- Build strong agile mindset and practices across the organization
- Create environments where teams can do their best work

### Typical Communication
- Facilitation of all agile ceremonies
- One-on-one coaching sessions with team members
- Retrospective insights and improvement recommendations
- Training sessions and workshops on agile practices

### Interactions with Other Roles
- **Project Managers**: Collaborates on process improvements and team health
- **Product Owner**: Coaches on backlog management and stakeholder engagement
- **Developers**: Provides guidance on technical practices (TDD, CI/CD, pair programming)
- **QA Lead**: Supports quality practices integration into agile workflow
- **All Team Members**: Available for coaching and removing impediments

---

## QA Lead

### Role Summary
QA Leads ensure quality is built into the product throughout the development lifecycle. They define testing strategies, coordinate quality assurance activities, and advocate for testability and reliability.

### Responsibilities
- Define overall testing strategy and quality standards
- Lead test planning and coordinate testing activities
- Review acceptance criteria for testability
- Implement and maintain test automation frameworks
- Track quality metrics and defect trends
- Identify quality risks early in the development cycle
- Mentor team members on testing best practices
- Ensure compliance with quality standards and regulations

### Goals
- Prevent defects rather than just finding them
- Maintain high product quality and reliability
- Reduce time spent on manual testing through automation
- Build quality awareness across the entire team

### Typical Communication
- Test plans and quality reports
- Defect triage meetings and risk assessments
- Code review feedback focused on testability
- Quality metrics dashboards and trend analysis

### Interactions with Other Roles
- **Developers**: Collaborates on testability, reviews tests, pairs on complex scenarios
- **Product Owner**: Reviews acceptance criteria, provides input on Definition of Done
- **DevOps Engineer**: Coordinates test automation in CI/CD pipelines
- **Project Managers**: Reports quality metrics and testing progress
- **Agile Coach**: Participates in retrospectives with quality improvement insights

---

## DevOps Engineer

### Role Summary
DevOps Engineers enable fast, reliable delivery through automation, infrastructure management, and operational excellence. They build and maintain CI/CD pipelines, monitoring systems, and deployment infrastructure.

### Responsibilities
- Design and maintain CI/CD pipelines
- Manage infrastructure as code and cloud resources
- Implement monitoring, logging, and alerting systems
- Automate deployment and rollback processes
- Ensure security best practices in infrastructure and pipelines
- Optimize build and deployment times
- Support incident response and root cause analysis
- Enable developer self-service for deployments

### Goals
- Enable fast, safe, automated deployments
- Minimize deployment failures and recovery time
- Provide excellent observability and debugging tools
- Reduce manual operations and toil

### Typical Communication
- Deployment runbooks and infrastructure documentation
- Incident reports and post-mortems
- Performance and availability metrics dashboards
- Architecture review participation for operational considerations

### Interactions with Other Roles
- **Developers**: Provides tooling and infrastructure, helps optimize builds and deployments
- **QA Lead**: Integrates automated tests into CI/CD pipelines
- **Project Managers**: Reports on deployment readiness and operational risks
- **Product Owner**: Provides deployment capabilities that enable faster feature delivery
- **Agile Coach**: Participates in retrospectives with operational improvement insights

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.
- The expanded roles provide clearer accountability and reduce gaps in project responsibilities.

