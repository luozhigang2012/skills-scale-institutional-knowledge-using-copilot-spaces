# OctoAcme Process Checklists

## Purpose
Provide actionable checklists for each project phase to ensure all roles complete their responsibilities and nothing falls through the cracks.

---

## Project Initiation Checklist

### Product Manager
- [ ] Define clear problem statement with customer impact
- [ ] Establish measurable success metrics (SMART goals)
- [ ] Identify primary stakeholders and champions
- [ ] Validate business case and expected value
- [ ] Review and approve project charter

### Project Manager
- [ ] Create project charter document
- [ ] Identify resource needs and team composition
- [ ] Establish communication plan and cadence
- [ ] Set up project tracking tools (board, repo, docs)
- [ ] Schedule kickoff meeting with all stakeholders
- [ ] Create initial risk register

### Product Owner
- [ ] Review product strategy alignment
- [ ] Prepare high-level backlog structure
- [ ] Identify key user personas and scenarios
- [ ] Validate acceptance criteria approach

### Stakeholder Representative
- [ ] Provide domain expertise and constraints
- [ ] Review and approve problem statement
- [ ] Commit to availability for reviews and decisions
- [ ] Identify compliance and policy requirements

### QA Lead
- [ ] Review success metrics for testability
- [ ] Identify quality risks and mitigation strategies
- [ ] Assess test environment needs
- [ ] Review Definition of Done criteria

### DevOps Engineer
- [ ] Assess infrastructure and deployment complexity
- [ ] Identify required environments (dev, staging, prod)
- [ ] Review security and compliance requirements
- [ ] Estimate infrastructure setup timeline

### Developers
- [ ] Provide technical feasibility assessment
- [ ] Identify major technical risks
- [ ] Estimate rough order of magnitude effort
- [ ] Suggest architecture approach

### Agile Coach
- [ ] Review team structure and capacity
- [ ] Suggest appropriate agile ceremonies
- [ ] Identify potential impediments
- [ ] Recommend process improvements

**Go/No-Go Decision Point**: All critical items above completed before moving to Planning.

---

## Project Planning Checklist

### Product Owner
- [ ] Prioritize backlog items by business value
- [ ] Write user stories with clear acceptance criteria
- [ ] Define Definition of Done with team
- [ ] Ensure stories are sized appropriately (<= 1 sprint)
- [ ] Identify dependencies between stories
- [ ] Schedule backlog refinement sessions

### Project Manager
- [ ] Create detailed project timeline with milestones
- [ ] Map dependencies across teams and systems
- [ ] Assign resources and confirm availability
- [ ] Set up status reporting cadence
- [ ] Update risk register with mitigation plans
- [ ] Schedule recurring ceremonies

### Developers
- [ ] Break down stories into technical tasks
- [ ] Provide detailed effort estimates
- [ ] Identify technical dependencies and risks
- [ ] Review architecture and design approach
- [ ] Set up development environment
- [ ] Establish code review guidelines

### QA Lead
- [ ] Create comprehensive test strategy
- [ ] Define test coverage goals
- [ ] Plan test automation approach
- [ ] Review all acceptance criteria for clarity
- [ ] Set up test environments
- [ ] Define quality metrics to track

### DevOps Engineer
- [ ] Design CI/CD pipeline architecture
- [ ] Set up infrastructure as code
- [ ] Configure environments (dev, staging, prod)
- [ ] Implement monitoring and alerting
- [ ] Document deployment procedures
- [ ] Plan rollback strategies

### Agile Coach
- [ ] Facilitate sprint planning ceremony
- [ ] Coach team on estimation techniques
- [ ] Ensure team commitment is realistic
- [ ] Establish team working agreements
- [ ] Set up retrospective schedule

### Product Manager
- [ ] Validate priorities align with roadmap
- [ ] Confirm success metrics tracking approach
- [ ] Review resource allocation
- [ ] Approve sprint goals

### Stakeholder Representative
- [ ] Review and approve project scope
- [ ] Provide input on priorities
- [ ] Confirm review and approval timeline
- [ ] Communicate to their stakeholder groups

**Planning Complete**: Team is ready to begin execution.

---

## Execution & Tracking Checklist

### Daily Activities

#### Developers
- [ ] Attend daily standup
- [ ] Implement assigned tasks following coding standards
- [ ] Write unit and integration tests
- [ ] Submit pull requests with clear descriptions
- [ ] Review teammate's code and provide feedback
- [ ] Update task status on project board

#### Product Owner
- [ ] Answer team questions promptly
- [ ] Review and accept completed work
- [ ] Refine upcoming backlog items
- [ ] Make priority decisions as needed
- [ ] Prepare for sprint review/demo

#### QA Lead
- [ ] Execute test plans
- [ ] Report and triage defects
- [ ] Review test coverage metrics
- [ ] Validate acceptance criteria met
- [ ] Update quality dashboards

#### DevOps Engineer
- [ ] Monitor CI/CD pipeline health
- [ ] Investigate and fix build failures
- [ ] Review infrastructure alerts
- [ ] Support deployment activities
- [ ] Update runbooks as needed

#### Agile Coach
- [ ] Facilitate daily standup
- [ ] Help remove impediments
- [ ] Coach individuals as needed
- [ ] Track team velocity and trends
- [ ] Observe team dynamics

#### Project Manager
- [ ] Update project status
- [ ] Track risks and issues
- [ ] Communicate blockers to stakeholders
- [ ] Manage dependencies
- [ ] Prepare status reports

### Weekly Activities

#### Project Manager
- [ ] Send status update to stakeholders
- [ ] Review risk register and update mitigations
- [ ] Check milestone progress
- [ ] Escalate critical issues

#### Product Manager
- [ ] Review progress against success metrics
- [ ] Adjust priorities based on learnings
- [ ] Validate customer value being delivered
- [ ] Attend product/engineering sync

#### Stakeholder Representative
- [ ] Attend demos or milestone reviews
- [ ] Provide feedback on deliverables
- [ ] Communicate updates to stakeholders
- [ ] Approve completed work in their domain

---

## Release & Deployment Checklist

### Pre-Release

#### Product Owner
- [ ] Final review of release scope
- [ ] Verify all acceptance criteria met
- [ ] Approve release notes
- [ ] Make go/no-go decision

#### QA Lead
- [ ] Complete all test execution
- [ ] Verify zero critical defects
- [ ] Prepare smoke test plan
- [ ] Review quality metrics

#### DevOps Engineer
- [ ] Verify deployment pipeline ready
- [ ] Confirm all environments healthy
- [ ] Prepare rollback plan
- [ ] Schedule deployment window
- [ ] Set up enhanced monitoring

#### Project Manager
- [ ] Confirm all teams ready for release
- [ ] Coordinate deployment timing
- [ ] Prepare communication plan
- [ ] Update stakeholders on schedule

#### Product Manager
- [ ] Validate success metrics tracking ready
- [ ] Prepare user communication
- [ ] Plan post-release monitoring

### During Deployment

#### DevOps Engineer
- [ ] Execute deployment runbook
- [ ] Monitor system health in real-time
- [ ] Verify services operational
- [ ] Execute rollback if needed

#### QA Lead
- [ ] Execute smoke tests immediately
- [ ] Monitor error rates
- [ ] Validate critical user flows

#### Developers
- [ ] Be available for troubleshooting
- [ ] Monitor logs and alerts
- [ ] Fix critical issues if discovered

#### Product Owner
- [ ] Monitor deployment progress
- [ ] Approve or reject based on health checks

### Post-Release

#### Product Manager
- [ ] Monitor success metrics
- [ ] Gather user feedback
- [ ] Announce release to customers

#### DevOps Engineer
- [ ] Monitor system stability (24-48 hours)
- [ ] Review performance metrics
- [ ] Document lessons learned

#### Project Manager
- [ ] Send release completion update
- [ ] Close release milestone
- [ ] Schedule retrospective

#### Stakeholder Representative
- [ ] Inform their stakeholder groups
- [ ] Gather stakeholder feedback

---

## Retrospective Checklist

### Agile Coach
- [ ] Schedule retrospective meeting
- [ ] Choose appropriate retrospective format
- [ ] Facilitate safe, productive discussion
- [ ] Capture insights and action items
- [ ] Assign owners to each action item
- [ ] Set follow-up review date

### Project Manager
- [ ] Document lessons learned
- [ ] Update process documentation with improvements
- [ ] Track action items to completion
- [ ] Share insights with leadership
- [ ] Archive project artifacts

### All Team Members
- [ ] Reflect on what went well
- [ ] Identify improvement opportunities
- [ ] Share honest, constructive feedback
- [ ] Commit to action items
- [ ] Celebrate successes

### Product Owner
- [ ] Reflect on backlog management effectiveness
- [ ] Identify product process improvements
- [ ] Gather team feedback on collaboration

### Developers
- [ ] Share technical learnings
- [ ] Suggest engineering practice improvements
- [ ] Identify technical debt to address

### QA Lead
- [ ] Review quality metrics trends
- [ ] Suggest testing process improvements
- [ ] Share learnings on defect patterns

### DevOps Engineer
- [ ] Review operational metrics
- [ ] Identify infrastructure improvements
- [ ] Share deployment lessons learned

### Product Manager
- [ ] Review outcome data
- [ ] Validate success metrics achieved
- [ ] Share customer feedback
- [ ] Identify product improvements

### Stakeholder Representative
- [ ] Provide stakeholder feedback
- [ ] Share business impact assessment
- [ ] Suggest collaboration improvements

---

## How to Use These Checklists

1. **At Phase Start**: Review relevant checklist with all participants
2. **During Phase**: Track completion of checklist items
3. **At Phase End**: Verify all critical items completed before moving forward
4. **Retrospective**: Review checklist effectiveness and suggest improvements

These checklists can be copied into project documentation or issue templates to ensure consistent execution across projects.

## Reference
These checklists implement role clarity improvements from [Issue #5](https://github.com/luozhigang2012/skills-scale-institutional-knowledge-using-copilot-spaces/issues/5).
