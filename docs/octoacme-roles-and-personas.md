# OctoAcme Personas

This document defines typical roles and responsibilities used in OctoAcme project docs and exercises.

---

## Core Project Delivery Roles

### Developers

#### Role Summary
Developers design, build, test, and deliver software components. They collaborate with product and project leads to implement features that meet acceptance criteria and quality standards.

#### Responsibilities
- Implement features and fixes to meet acceptance criteria
- Write and maintain tests and documentation
- Participate in design and code reviews
- Assist in estimating and planning work
- Help identify technical risks and propose mitigations
- Collaborate with Technical Lead on architecture decisions
- Participate in security and performance reviews

#### Goals
- Deliver reliable, maintainable code
- Reduce cycle time from idea to production
- Maintain high test coverage and observability
- Proactively communicate blockers and dependencies

#### Typical Communication
- Daily standups and sprint planning
- PR descriptions and code review comments
- Technical design docs when needed
- Architecture decision records (ADRs)
- Integration kickoff meetings with Release Manager and DevOps

#### Handoffs
- **Takes work from:** Product Manager (acceptance criteria), Technical Lead (design guidance)
- **Hands off to:** QA (for testing), Release Manager (for deployment readiness)

---

### Product Managers

#### Role Summary
Product Managers define what should be built to deliver customer and business value. They own the product vision, prioritize the backlog, and measure outcomes.

#### Responsibilities
- Define problem statements and success metrics
- Prioritize the roadmap and backlog
- Collaborate with stakeholders and engineering on trade-offs
- Validate solutions through user research and metrics
- Work with Data Analyst to track and measure success post-release
- Partner with Support Liaison to incorporate customer feedback

#### Goals
- Maximize customer value and impact
- Make clear, data-driven prioritization decisions
- Ensure product-market fit and usability

#### Typical Communication
- Weekly alignment with PM and engineering leads
- Roadmap updates and stakeholder briefings
- Acceptance criteria and feature specs
- Post-release metric reviews with Data Analyst

#### Handoffs
- **Takes work from:** Stakeholders (requirements), Support Liaison (customer feedback)
- **Hands off to:** Project Manager (prioritized backlog), Developers (detailed acceptance criteria)

---

### Project Managers

#### Role Summary
Project Managers coordinate delivery activities, manage schedules, risks, and communications. They enable the team to deliver on commitments efficiently.

#### Responsibilities
- Create and maintain project plans and timelines
- Manage risks, dependencies, and resource constraints
- Facilitate meetings (kickoff, planning, retrospectives)
- Ensure consistent project documentation and status reporting
- Coordinate cross-team and stakeholder communication
- Escalate blockers and facilitate resolution
- Coordinate release readiness reviews with Release Manager and DevOps

#### Goals
- Deliver projects on time and within scope
- Minimize unplanned work and escalations
- Maintain transparency and alignment across stakeholders

#### Typical Communication
- Weekly status updates and stakeholder reports
- Risk registers and decision logs
- Coordination via project boards and meeting facilitation
- Pre-release checklists and go/no-go decisions with Release Manager

#### Handoffs
- **Takes work from:** Product Manager (prioritized backlog), Stakeholders (constraints)
- **Hands off to:** Release Manager (release readiness), Stakeholders (delivery announcements)

---

## Specialized Cross-Functional Roles

### Technical Lead / System Architect

#### Role Summary
Technical Leads own high-level technical direction and architecture decisions for projects. They collaborate with developers, product managers, and system architects to ensure solutions are feasible, scalable, and maintainable.

#### Responsibilities
- Define technical architecture and design patterns
- Lead architecture review sessions and technical design discussions
- Identify technical risks and propose mitigation strategies
- Mentor developers on technical best practices
- Partner with Security Engineer on security architecture reviews
- Review integration points with DevOps and Release Manager
- Provide technical input to capacity and effort estimation

#### Goals
- Ensure technical decisions align with long-term system health
- Reduce technical debt and rework
- Enable team velocity through clear technical direction
- Maintain system scalability and reliability

#### Typical Communication
- Architecture design review sessions
- Technical decision records (TDRs)
- Code review guidance on complex changes
- Integration planning with cross-functional teams
- Pre-release technical readiness reviews

#### Handoffs
- **Takes work from:** Product Manager (feature specifications), Project Manager (timeline constraints)
- **Hands off to:** Developers (architecture guidance), Security Engineer (security review), DevOps (deployment implications)

---

### DevOps / Platform Engineer

#### Role Summary
DevOps Engineers manage CI/CD pipelines, deployment automation, environment reliability, and infrastructure. They enable seamless delivery and operate production systems with high availability and observability.

#### Responsibilities
- Design and maintain CI/CD pipelines and automation
- Manage deployment environments (dev, staging, production)
- Ensure infrastructure reliability, scalability, and security
- Implement automated testing, linting, and security scanning
- Manage rollback procedures and incident response
- Work with Release Manager on deployment coordination
- Collaborate with Security Engineer on infrastructure hardening
- Provide observability, logging, and monitoring

#### Goals
- Enable fast, safe, and reliable deployments
- Minimize deployment failures and rollbacks
- Maintain high uptime and system performance
- Automate manual processes to reduce human error

#### Typical Communication
- Release coordination meetings with Release Manager
- Infrastructure and deployment runbooks
- CI/CD status and incident communications
- Post-deployment verification reports
- Security and compliance audits with Security Engineer

#### Handoffs
- **Takes work from:** Technical Lead (deployment requirements), Release Manager (release schedule)
- **Hands off to:** Release Manager (deployment readiness), Support Liaison (infrastructure status for incident response)

---

### Release Manager / Build & Release Coordinator

#### Role Summary
Release Managers coordinate release windows, validate release readiness, manage pre-release checklists, and communicate release status to stakeholders. They serve as the central hub for release orchestration across development, QA, operations, and support teams.

#### Responsibilities
- Define and maintain release schedule and milestones
- Manage release readiness checklists with Development, QA, DevOps, and Security
- Coordinate pre-release testing, staging validation, and smoke tests
- Communicate release status to Product Manager, Project Manager, and stakeholders
- Schedule deployment windows and coordinate rollout
- Interface between development and operations teams
- Manage release notes and documentation
- Coordinate post-deployment verification and issue triage

#### Goals
- Ensure all releases meet quality and readiness standards
- Reduce release-related incidents and rollbacks
- Maintain clear communication and transparency with all stakeholders
- Enable rapid, confident deployments

#### Typical Communication
- Release readiness sync meetings
- Pre-release checklists and status reports
- Release notes and stakeholder communications
- Post-deployment verification meetings
- Incident coordination if release issues arise

#### Handoffs
- **Takes work from:** Project Manager (go/no-go decision), DevOps (deployment readiness), QA (test results), Security Engineer (security sign-off)
- **Hands off to:** DevOps (deployment execution), Support Liaison (release announcements), Stakeholders (release updates)

---

### Security Engineer / Security Reviewer

#### Role Summary
Security Engineers perform threat assessments, code reviews, and compliance validation to ensure projects meet security requirements. They work proactively to identify and mitigate security risks throughout the development lifecycle.

#### Responsibilities
- Conduct threat modeling and security architecture reviews
- Review code changes for security vulnerabilities
- Approve or flag security scanning and penetration test results
- Ensure compliance with security policies and standards
- Partner with Technical Lead on security design decisions
- Validate third-party dependencies for vulnerabilities
- Escalate critical security issues to Product Lead and Security on-call
- Provide security guidance in pre-release reviews

#### Goals
- Prevent security vulnerabilities from reaching production
- Maintain compliance with organizational and regulatory standards
- Foster a security-aware development culture
- Enable fast, secure deployments without compromising safety

#### Typical Communication
- Security design review sessions
- Vulnerability assessment reports
- Security scanning results and remediation guidance
- Compliance audit findings
- Incident response for security-related issues

#### Handoffs
- **Takes work from:** Technical Lead (architecture for review), Developers (code for scanning), Release Manager (pre-release validation)
- **Hands off to:** Project Manager (risk escalations), Release Manager (security sign-off), Support Liaison (security incident information)

---

### Data Analyst / Metrics Owner

#### Role Summary
Data Analysts define success metrics, implement tracking instrumentation, and provide post-release analysis. They enable data-driven decisions and measure the impact of delivered features.

#### Responsibilities
- Define success metrics and KPIs aligned with project goals
- Implement metric tracking and instrumentation in code
- Analyze post-release data and measure feature impact
- Provide insights to Product Manager and Project Manager on results
- Identify anomalies or issues through metric analysis
- Create dashboards and reports for ongoing monitoring
- Collaborate with Development and DevOps on observability

#### Goals
- Enable clear measurement of project success
- Support data-driven decision-making for future iterations
- Identify and escalate production issues early through anomalies
- Continuously improve observability and metrics

#### Typical Communication
- Pre-release metric planning meetings
- Post-release data analysis reports
- Dashboard and KPI reviews
- Anomaly alerts and escalations
- Metrics-driven retrospectives

#### Handoffs
- **Takes work from:** Product Manager (success metrics), Developers (instrumentation code)
- **Hands off to:** Product Manager (analysis and insights), Project Manager (metric status reports)

---

### UX Researcher / Designer Representative

#### Role Summary
UX Researchers and Designers ensure features are usable, accessible, and meet user needs. They bring customer perspective throughout the development lifecycle and validate that acceptance criteria include user experience considerations.

#### Responsibilities
- Conduct user research and usability testing
- Validate feature designs against user needs
- Ensure accessibility standards (WCAG) are met
- Review acceptance criteria for UX implications
- Collaborate with Product Manager on feature specifications
- Conduct usability reviews with development team
- Identify and escalate UX risks and concerns

#### Goals
- Ensure delivered features are usable and accessible
- Reduce post-release UX-related issues
- Incorporate customer voice throughout development
- Maintain usability standards across all features

#### Typical Communication
- Usability research findings and reports
- Design review sessions
- Acceptance criteria review with Product Manager and Developers
- Accessibility audit results
- User feedback integration discussions

#### Handoffs
- **Takes work from:** Product Manager (feature specifications), Developers (implementation for testing)
- **Hands off to:** Product Manager (usability insights), QA (accessibility test cases)

---

### Support Liaison / Customer Success Representative

#### Role Summary
Support Liaisons bring the customer perspective to the team and help triage incoming issues post-release. They connect customer feedback with product prioritization and support incident response.

#### Responsibilities
- Communicate customer needs and pain points to Product Manager
- Triage and categorize incoming support issues post-release
- Identify patterns in customer feedback and feature requests
- Coordinate with Product Manager on hotfix priorities
- Provide customer context during incident response
- Escalate critical customer-impacting issues to Release Manager and Incident Commander
- Document customer feedback for product retrospectives

#### Goals
- Ensure customer voice informs product prioritization
- Rapidly identify and triage production issues
- Minimize customer impact of bugs and regressions
- Build customer trust through responsive support

#### Typical Communication
- Customer feedback summaries for Product Manager
- Post-release issue triage reports
- Incident coordination and customer communication
- Feature request aggregation and analysis
- Customer success metrics and trends

#### Handoffs
- **Takes work from:** Customers (feedback and issues), Release Manager (release information)
- **Hands off to:** Product Manager (aggregated feedback), Project Manager (issue priorities)

---

### Compliance / Legal Reviewer

#### Role Summary
Compliance and Legal Reviewers ensure that projects meet regulatory, contractual, and organizational requirements. They provide approvals at critical decision gates to ensure alignment with policies and standards.

#### Responsibilities
- Review regulatory and contractual implications of features
- Ensure data privacy and protection compliance (GDPR, CCPA, etc.)
- Validate licensing and intellectual property concerns
- Provide required approvals for regulated functionality
- Escalate compliance risks to Product Lead and Legal teams
- Review customer-facing documentation for compliance accuracy
- Maintain compliance audit trails and documentation

#### Goals
- Prevent regulatory and legal risks from reaching production
- Ensure organizational compliance with applicable standards
- Enable compliant, confident feature releases
- Maintain audit readiness and documentation

#### Typical Communication
- Compliance review sessions at project gates
- Regulatory impact assessments
- Licensing and IP approval documentation
- Compliance audit findings
- Legal risk escalations

#### Handoffs
- **Takes work from:** Product Manager (feature specifications), Technical Lead (architecture for review)
- **Hands off to:** Product Lead (compliance sign-off), Project Manager (risk escalations)

---

## Role Interactions Matrix

This matrix shows which roles interact and collaborate on key project activities:

| Activity | PM | PdM | Dev | QA | Tech Lead | DevOps | Release Mgr | Security | Data | UX | Support | Compliance |
|----------|----|----|-----|----|-----------|---------|-----------|-----------|----|----|---------|----|
| **Project Initiation** | L | L | C | - | C | - | - | C | - | C | C | C |
| **Planning & Design** | L | L | C | - | L | C | - | C | - | L | - | C |
| **Estimation** | C | C | L | - | L | C | - | - | - | - | - | - |
| **Development** | - | - | L | - | C | C | - | C | - | - | - | - |
| **Code Review** | - | - | L | - | L | - | - | C | - | - | - | - |
| **Testing & QA** | C | - | C | L | - | - | - | C | - | C | - | - |
| **Security Review** | - | - | - | - | C | - | - | L | - | - | - | C |
| **Release Readiness** | C | C | - | C | - | L | L | L | - | - | - | - |
| **Deployment** | - | - | - | - | - | L | L | - | - | - | - | - |
| **Post-Release** | C | L | - | - | - | C | L | - | L | - | L | - |
| **Incident Response** | C | - | C | - | C | L | L | L | C | - | L | - |

**Legend:**
- **L** = Lead / Primary Responsibility
- **C** = Collaborates / Participates
- **-** = Not typically involved

---

## How these personas are used in the exercise

- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.
- Reference the Role Interactions Matrix when planning project activities to identify necessary collaboration points.
- Clarify RACI (Responsible, Accountable, Consulted, Informed) by reviewing handoff sections for each role.
