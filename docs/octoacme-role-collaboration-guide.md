# OctoAcme Role Collaboration Guide

## Purpose
This guide clarifies how roles work together throughout the project lifecycle, defines typical handoffs, and provides onboarding checklists for each role. Use this alongside [octoacme-roles-and-personas.md](octoacme-roles-and-personas.md) to understand collaboration boundaries and ensure smooth team coordination.

---

## Role Interaction Matrix

This matrix shows typical collaboration touchpoints between roles during key project phases.

| Phase | Key Activities | Primary Roles | Supporting Roles |
|-------|---------------|---------------|------------------|
| **Initiation** | Problem definition, stakeholder alignment, project one-pager | Product Manager, Project Manager | Business Analyst, Stakeholders |
| **Planning** | Backlog creation, estimation, sprint planning, DoD | Product Manager, Scrum Master, Developers | UX Designer, Business Analyst, QA/Testing, DevOps Engineer |
| **Design** | User research, wireframes, design validation | UX Designer, Product Manager | Developers, Business Analyst |
| **Development** | Feature implementation, code reviews, testing | Developers, QA/Testing | UX Designer, DevOps Engineer, Scrum Master |
| **Release** | CI/CD, deployment, monitoring, verification | DevOps Engineer, Developers, QA/Testing | Project Manager, Scrum Master |
| **Retrospective** | Learnings capture, process improvements | Scrum Master, Project Manager | All team members |

---

## Typical Handoffs and Responsibilities

### Product Manager → Business Analyst
**When**: During problem exploration and requirements gathering
**Handoff**: High-level business objectives, target users, success metrics
**Expected Output**: Detailed requirements, process flows, user stories with acceptance criteria

### Business Analyst → UX Designer
**When**: After requirements are validated
**Handoff**: Business requirements, user personas, process flows
**Expected Output**: Wireframes, user journeys, design prototypes

### UX Designer → Developers
**When**: Design validated and ready for implementation
**Handoff**: Approved designs, prototypes, design specs, user flows
**Expected Output**: Implementation that matches design fidelity and usability standards

### Product Manager → Scrum Master
**When**: During sprint planning and backlog refinement
**Handoff**: Prioritized backlog with acceptance criteria
**Expected Output**: Sprint commitments, velocity tracking, impediment resolution

### Developers → QA/Testing
**When**: Feature complete and ready for validation
**Handoff**: Pull request, test instructions, acceptance criteria reference
**Expected Output**: Test results, defect reports, sign-off on acceptance criteria

### QA/Testing → DevOps Engineer
**When**: Feature tested and approved for release
**Handoff**: Release notes, smoke test plan, rollback criteria
**Expected Output**: Successful deployment, monitoring confirmation, post-deploy verification

### Project Manager ↔ All Roles
**Ongoing**: Status reporting, risk escalation, dependency coordination
**Communication**: Weekly syncs, status updates, blocker resolution

---

## Role Onboarding Checklists

### Developer Onboarding

- [ ] Access granted to code repositories and development environments
- [ ] Local development environment setup completed
- [ ] Familiarize with coding standards and review practices (see team wiki)
- [ ] Review Definition of Done and testing requirements
- [ ] Attend sprint planning and standup to understand team rhythm
- [ ] Shadow a code review and PR workflow
- [ ] Complete first small contribution (e.g., documentation fix, minor bug)
- [ ] Meet with Product Manager and UX Designer to understand current priorities

### Product Manager Onboarding

- [ ] Access to product analytics, user research data, and roadmap tools
- [ ] Review product vision, strategy, and current OKRs
- [ ] Meet with stakeholders and understand business objectives
- [ ] Review existing backlog and prioritization criteria
- [ ] Shadow sprint planning and backlog refinement session
- [ ] Meet with UX Designer to review user research and design process
- [ ] Meet with Project Manager to align on communication cadence
- [ ] Review metrics dashboards and success criteria

### Project Manager Onboarding

- [ ] Access to project boards, risk registers, and documentation repositories
- [ ] Review project charter, timelines, and key milestones
- [ ] Meet with stakeholders and understand escalation paths
- [ ] Shadow weekly syncs and understand reporting cadence
- [ ] Review risk management process and dependency tracking
- [ ] Meet with Scrum Master to align on sprint execution and capacity planning
- [ ] Familiarize with communication templates and status report format
- [ ] Review past retrospectives to understand team improvements

### Scrum Master Onboarding

- [ ] Access to project boards, sprint tracking tools, and team metrics
- [ ] Review Agile practices and team's specific sprint process
- [ ] Shadow sprint ceremonies (planning, standup, review, retrospective)
- [ ] Meet with Product Manager to understand backlog priorities
- [ ] Meet with Project Manager to align on capacity and cross-team dependencies
- [ ] Review team velocity, metrics, and improvement action items
- [ ] Understand escalation process for blockers and impediments
- [ ] Meet with team members individually to understand working styles

### UX Designer Onboarding

- [ ] Access to design tools, user research data, and design system
- [ ] Review existing design patterns, style guide, and component library
- [ ] Meet with Product Manager to understand product vision and user needs
- [ ] Review current user journeys, personas, and research findings
- [ ] Shadow usability testing session or design critique
- [ ] Meet with Developers to understand technical constraints and design implementation process
- [ ] Review acceptance criteria format and how design is validated in QA
- [ ] Familiarize with design handoff process and collaboration tools

### DevOps Engineer Onboarding

- [ ] Access to infrastructure, CI/CD pipelines, and monitoring tools
- [ ] Review current deployment processes and release schedule
- [ ] Understand infrastructure architecture and environments (dev, staging, prod)
- [ ] Review monitoring dashboards, alerting, and incident response process
- [ ] Meet with Developers to understand build and testing requirements
- [ ] Shadow a deployment and review rollback procedures
- [ ] Review security scanning tools and integration with CI/CD
- [ ] Familiarize with infrastructure as code and configuration management

### Business Analyst Onboarding

- [ ] Access to requirements documentation, stakeholder lists, and project artifacts
- [ ] Review business objectives, success metrics, and strategic goals
- [ ] Meet with Product Manager to understand product strategy and priorities
- [ ] Meet with key stakeholders to understand their needs and concerns
- [ ] Review past requirements documents and user story formats
- [ ] Shadow requirements gathering session or workshop
- [ ] Familiarize with backlog grooming process and acceptance criteria standards
- [ ] Meet with Developers to understand technical feasibility and constraints

### QA/Testing Onboarding

- [ ] Access to test environments, testing tools, and defect tracking systems
- [ ] Review test strategy, test plans, and automation framework
- [ ] Familiarize with Definition of Done and acceptance criteria standards
- [ ] Meet with Developers to understand testability and automated test practices
- [ ] Shadow manual testing session and review test case documentation
- [ ] Review defect reporting process and severity/priority definitions
- [ ] Meet with DevOps Engineer to understand CI/CD test integration
- [ ] Understand smoke testing procedures and post-deployment verification

---

## Collaboration Best Practices

### Clear Handoffs
- Always document what's being handed off (e.g., design specs, requirements, test results)
- Include context: why the work was done, what decisions were made, what's still open
- Set clear expectations: what you need from the recipient and when

### Effective Communication
- Use the right channel: async (project boards, docs) vs sync (meetings, slack)
- Over-communicate when handing off across time zones or teams
- Don't assume shared context—provide links and background

### Ownership and Accountability
- Each deliverable should have a clear owner
- When responsibilities overlap, explicitly agree on who drives what
- Escalate early when boundaries are unclear

### Continuous Feedback
- Regularly check if collaboration patterns are working
- Raise process issues in retrospectives
- Iterate on handoff processes to reduce friction

---

## Using This Guide

- **New team members**: Use the onboarding checklist for your role
- **Project Managers**: Reference the interaction matrix when planning project phases
- **All roles**: Review collaboration points to understand how you fit into the broader team
- **Retrospectives**: Use this guide to identify gaps in collaboration or handoffs that need improvement

For detailed role responsibilities, see [octoacme-roles-and-personas.md](octoacme-roles-and-personas.md).
