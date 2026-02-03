# OctoAcme Personas

This document defines typical roles and responsibilities used in OctoAcme project docs and exercises.

## How to Use This Document
Use these persona definitions as a reference for:
- **Project One-pagers**: Identify which roles are needed for your project
- **Planning**: Assign responsibilities and understand cross-functional dependencies
- **Onboarding**: Help new team members understand who does what and how roles interact
- **RACI Matrix**: Use the responsibility notes below to build a RACI (Responsible, Accountable, Consulted, Informed) matrix for your project's key activities

Each persona includes:
- Role Summary and core responsibilities
- Goals and typical communication patterns
- Interaction notes showing how the role works with PM, PdM, Developers, and QA
- RACI-style notes for common activities (requirements, design, development, testing, release, support handoff)

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

### Interactions
- **With PM**: Provide estimates, raise blockers, coordinate on timelines
- **With PdM**: Clarify requirements, discuss technical trade-offs
- **With Developers**: Collaborate on design, conduct code reviews
- **With QA**: Coordinate testing approach, fix reported issues

### RACI for Common Activities
- Requirements: Consulted
- Design: Responsible/Accountable (technical design)
- Development: Responsible/Accountable
- Testing: Responsible (unit/integration), Consulted (E2E)
- Release: Consulted
- Support Handoff: Informed

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

### Interactions
- **With PM**: Coordinate on delivery schedules, identify risks, align on scope
- **With PdM**: Self-coordination on prioritization and customer feedback
- **With Developers**: Review acceptance criteria, answer questions on user needs
- **With QA**: Define success metrics and acceptance tests

### RACI for Common Activities
- Requirements: Responsible/Accountable
- Design: Accountable (product design), Consulted (technical)
- Development: Informed
- Testing: Consulted (acceptance criteria)
- Release: Consulted
- Support Handoff: Informed

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

### Interactions
- **With PM**: Self-coordination on project execution
- **With PdM**: Align on priorities, manage scope and timeline trade-offs
- **With Developers**: Remove blockers, coordinate dependencies
- **With QA**: Ensure test coverage and quality gates are met

### RACI for Common Activities
- Requirements: Informed
- Design: Informed
- Development: Informed
- Testing: Informed
- Release: Accountable (coordination and go/no-go decision)
- Support Handoff: Responsible (ensures handoff occurs)

---

## QA/Testing Engineers

### Role Summary
QA/Testing Engineers validate that features meet acceptance criteria and quality standards. They design test plans, execute tests, and identify defects before release.

### Responsibilities
- Create test plans and test cases based on acceptance criteria
- Execute manual and automated tests
- Report and track defects through resolution
- Validate fixes and conduct regression testing
- Participate in release go/no-go decisions

### Goals
- Ensure features meet quality standards before release
- Reduce production defects and customer-reported issues
- Improve test automation coverage

### Typical Communication
- Daily standups and sprint planning
- Bug reports and test result summaries
- Release readiness status updates

### Interactions
- **With PM**: Report testing progress and blockers
- **With PdM**: Clarify acceptance criteria and edge cases
- **With Developers**: Collaborate on reproducible bug reports and fixes
- **With QA**: Coordinate test coverage across team members

### RACI for Common Activities
- Requirements: Consulted (testability review)
- Design: Consulted (test approach)
- Development: Informed
- Testing: Responsible/Accountable
- Release: Consulted (quality gate approval)
- Support Handoff: Responsible (test results documentation)

---

## UX Designer

### Role Summary
UX Designers create user experiences and interfaces that are intuitive, accessible, and aligned with user needs. They conduct research, create wireframes and prototypes, and validate designs through usability testing.

### Responsibilities
- Conduct user research and usability testing
- Create wireframes, mockups, and interactive prototypes
- Define information architecture and user flows
- Provide design specifications and assets to developers
- Validate implemented features against design standards
- Maintain design systems and style guides

### Goals
- Deliver intuitive, accessible user experiences
- Reduce user friction and improve satisfaction
- Ensure design consistency across features

### Typical Communication
- Design reviews and critique sessions
- Wireframes, prototypes, and design specs
- Usability test findings and recommendations

### Interactions
- **With PM**: Coordinate on timelines and design dependencies
- **With PdM**: Collaborate on user needs, requirements, and success metrics
- **With Developers**: Provide design assets, clarify implementation details, review built features
- **With QA**: Define UI/UX test scenarios and acceptance criteria

### RACI for Common Activities
- Requirements: Consulted (user needs and usability)
- Design: Responsible/Accountable (UX/UI design)
- Development: Consulted (implementation questions)
- Testing: Consulted (usability validation)
- Release: Informed
- Support Handoff: Informed

---

## Data Analyst

### Role Summary
Data Analysts collect, process, and interpret data to support decision-making and measure product success. They create dashboards, generate insights, and help teams understand user behavior and system performance.

### Responsibilities
- Define and track key metrics and KPIs
- Build dashboards and reports for stakeholders
- Analyze user behavior and feature adoption
- Identify trends, anomalies, and opportunities for improvement
- Support A/B test design and analysis
- Provide data-driven recommendations

### Goals
- Enable data-informed decision-making
- Measure and communicate product impact
- Identify opportunities for optimization

### Typical Communication
- Weekly metric reviews and insights reports
- Dashboard demonstrations and training
- Ad-hoc data requests and analysis

### Interactions
- **With PM**: Provide data for status reports and risk identification
- **With PdM**: Define success metrics, analyze feature impact, support prioritization decisions
- **With Developers**: Clarify instrumentation requirements and data structure
- **With QA**: Validate data accuracy and test metric collection

### RACI for Common Activities
- Requirements: Consulted (metrics and instrumentation)
- Design: Consulted (data collection needs)
- Development: Consulted (instrumentation implementation)
- Testing: Consulted (data validation)
- Release: Consulted (pre/post-launch metrics)
- Support Handoff: Responsible (dashboards and metric documentation)

---

## DevOps Engineer

### Role Summary
DevOps Engineers build and maintain CI/CD pipelines, infrastructure, and deployment automation. They ensure reliable, secure, and efficient software delivery and operations.

### Responsibilities
- Design and maintain CI/CD pipelines
- Manage infrastructure as code (IaC)
- Monitor system health and performance
- Automate deployment and rollback procedures
- Implement security and compliance controls
- Respond to production incidents and outages

### Goals
- Enable fast, reliable deployments with minimal downtime
- Maintain system reliability and performance
- Improve automation and reduce manual operations

### Typical Communication
- Daily operational status updates
- Incident reports and postmortems
- Infrastructure and deployment documentation

### Interactions
- **With PM**: Coordinate release windows, provide deployment status, escalate infrastructure risks
- **With PdM**: Inform about operational constraints affecting features
- **With Developers**: Collaborate on deployment strategies, troubleshoot build/deploy issues, optimize pipelines
- **With QA**: Enable test automation infrastructure, support performance testing

### RACI for Common Activities
- Requirements: Consulted (operational requirements)
- Design: Consulted (deployment and scalability)
- Development: Consulted (pipeline and infrastructure)
- Testing: Responsible (CI/CD pipeline), Consulted (test automation)
- Release: Responsible (deployment execution)
- Support Handoff: Responsible (operational runbooks and monitoring)

---

## Technical Writer

### Role Summary
Technical Writers create and maintain documentation for internal processes, APIs, user guides, and release notes. They ensure documentation is accurate, clear, and up-to-date.

### Responsibilities
- Write and update user documentation and guides
- Create developer documentation (API docs, integration guides)
- Document internal processes and workflows
- Write and edit release notes
- Maintain documentation structure and navigation
- Collaborate with subject matter experts for accuracy

### Goals
- Provide clear, accurate, and accessible documentation
- Reduce support burden through self-service content
- Keep documentation current with product changes

### Typical Communication
- Documentation reviews and editing sessions
- Release note summaries
- Process documentation updates

### Interactions
- **With PM**: Document project processes, create status report templates, maintain project documentation
- **With PdM**: Write user-facing feature documentation and release communications
- **With Developers**: Document APIs, technical architecture, and developer guides
- **With QA**: Document test processes and known issues

### RACI for Common Activities
- Requirements: Informed
- Design: Consulted (documentation needs)
- Development: Consulted (technical accuracy)
- Testing: Informed
- Release: Responsible (release notes and documentation updates)
- Support Handoff: Responsible (support documentation and knowledge base)

---

## Customer Support / Support Engineer

### Role Summary
Customer Support / Support Engineers serve as the first line of support for users and customers. They troubleshoot issues, collect feedback, document problems, and coordinate with product and engineering teams.

### Responsibilities
- Respond to customer inquiries and issues
- Troubleshoot and resolve common problems
- Escalate bugs and feature requests to engineering
- Document issues and workarounds in knowledge base
- Collect and synthesize customer feedback
- Assist with QA and user acceptance testing

### Goals
- Resolve customer issues quickly and effectively
- Improve customer satisfaction and product usability
- Provide feedback loop between customers and product teams

### Typical Communication
- Daily ticket queue reviews
- Weekly feedback summaries to product team
- Issue escalations and customer impact reports

### Interactions
- **With PM**: Coordinate on release communications, report customer impact of issues, request status updates
- **With PdM**: Provide customer feedback and feature requests, prioritize bug fixes based on customer impact
- **With Developers**: Report bugs with reproduction steps, validate fixes in staging
- **With QA**: Collaborate on reproduction of customer-reported issues, assist with user acceptance testing

### RACI for Common Activities
- Requirements: Consulted (customer needs and pain points)
- Design: Consulted (usability feedback)
- Development: Informed
- Testing: Consulted (user acceptance testing)
- Release: Informed (customer communication)
- Support Handoff: Accountable (receives handoff, provides ongoing support)

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.
- Reference this document when creating project one-pagers to identify which roles are needed.
- Use the RACI notes to build responsibility matrices for your specific project activities.

