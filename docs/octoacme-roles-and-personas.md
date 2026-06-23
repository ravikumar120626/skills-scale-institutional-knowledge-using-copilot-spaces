# OctoAcme Personas

This document defines typical roles and responsibilities used in OctoAcme project docs and exercises.

---

## Core Roles

### Developers

#### Role Summary
Developers design, build, test, and deliver software components. They collaborate with product and project leads to implement features that meet acceptance criteria and quality standards.

#### Responsibilities
- Implement features and fixes to meet acceptance criteria
- Write and maintain tests and documentation
- Participate in design and code reviews
- Assist in estimating and planning work
- Help identify technical risks and propose mitigations

#### Goals
- Deliver reliable, maintainable code
- Reduce cycle time from idea to production
- Maintain high test coverage and observability

#### Typical Communication
- Daily standups and sprint planning
- PR descriptions and code review comments
- Technical design docs when needed

---

### Product Managers

#### Role Summary
Product Managers define what should be built to deliver customer and business value. They own the product vision, prioritize the backlog, and measure outcomes.

#### Responsibilities
- Define problem statements and success metrics
- Prioritize the roadmap and backlog
- Collaborate with stakeholders and engineering on trade-offs
- Validate solutions through user research and metrics

#### Goals
- Maximize customer value and impact
- Make clear, data-driven prioritization decisions
- Ensure product-market fit and usability

#### Typical Communication
- Weekly alignment with PM and engineering leads
- Roadmap updates and stakeholder briefings
- Acceptance criteria and feature specs

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

#### Goals
- Deliver projects on time and within scope
- Minimize unplanned work and escalations
- Maintain transparency and alignment across stakeholders

#### Typical Communication
- Weekly status updates and stakeholder reports
- Risk registers and decision logs
- Coordination via project boards and meeting facilitation

---

## Additional Operational Personas

The following personas address cross-cutting concerns and operational needs that emerge during project execution. These roles complement (not replace) the core roles above, and clarify ownership for critical handoffs and decision-making.

### Tech Lead

#### Role Summary
Tech Leads provide technical direction for a feature area or service. They drive design decisions, ensure code quality, mentor engineers, and escalate architectural or technical risks to leadership.

#### Responsibilities
- Define technical approach and architecture for features or services
- Own code review quality and technical standards compliance
- Mentor and grow team members; provide technical guidance
- Identify and escalate technical risks and dependencies early
- Ensure non-functional requirements (performance, scalability, security) are met
- Drive design reviews and decision documentation

#### Goals
- Deliver high-quality, maintainable technical solutions
- Build team capability and reduce single-person dependencies
- Enable informed trade-offs between speed, quality, and scope

#### Interaction with Other Roles
- **With PM/PdM:** Translates requirements into technical scope; negotiates feasibility and timeline impacts
- **With Developers:** Reviews code, provides technical mentorship, ensures acceptance criteria are met
- **With QA:** Partners on test strategy and non-functional requirement validation
- **With Project Manager:** Escalates architecture, dependency, or capacity risks

#### Typical Communication
- Design review meetings and decision logs
- Code review comments and pull request discussions
- Technical risk register updates
- 1:1s with team members

---

### Release / Build Engineer

#### Role Summary
Release/Build Engineers own the release and deployment pipelines. They ensure reliable, repeatable deployments to production and maintain the health of CI/CD infrastructure.

#### Responsibilities
- Design and maintain CI/CD pipelines and infrastructure
- Automate build, test, and deployment processes
- Manage release versioning, tagging, and artifact management
- Create and maintain deployment and rollback runbooks
- Monitor pipeline health and respond to failures
- Coordinate with teams on release readiness and go/no-go decisions

#### Goals
- Enable fast, safe, repeatable deployments
- Minimize manual toil and human error in releases
- Maintain visibility into build and deployment health

#### Interaction with Other Roles
- **With Developers:** Integrates code changes; supports debugging of build failures
- **With QA:** Coordinates deployment to staging and production verification
- **With Project Manager:** Participates in release planning and communicates deployment readiness
- **With Security/Observability leads:** Ensures security scanning and monitoring checks are integrated into pipelines

#### Typical Communication
- Release planning meetings and go/no-go decisions
- Build failure alerts and resolution
- Deployment runbook updates
- Post-incident retrospectives on deployment issues

---

### UX Researcher / Designer

#### Role Summary
UX Researchers and Designers validate user needs, conduct lightweight research, and define user-centric acceptance criteria. They ensure solutions are usable and solve real customer problems.

#### Responsibilities
- Conduct user research, interviews, and usability testing
- Create wireframes, prototypes, and design specifications
- Define usability-focused acceptance criteria
- Collaborate on feature prioritization based on user feedback
- Review designs and usability before QA and release
- Capture UX patterns and design systems evolution

#### Goals
- Ensure features solve real user problems
- Deliver intuitive, accessible user experiences
- Build shared design patterns and consistency across products

#### Interaction with Other Roles
- **With Product Manager/PdM:** Aligns on problem statement and success metrics; advocates for user needs
- **With Developers:** Hands off designs and acceptance criteria; supports implementation discussions
- **With QA:** Defines usability test cases and acceptance criteria; supports manual QA reviews
- **With Documentation Owner:** Ensures user docs and help content align with design

#### Typical Communication
- Design review sessions and feedback
- User research findings and synthesis
- Design specification documents
- Usability test results and recommendations

---

### Data Analyst / Metrics Owner

#### Role Summary
Data Analysts and Metrics Owners define instrumentation needs, validate telemetry, and prepare dashboards and reports. They ensure projects are measured against success metrics and inform post-release decisions.

#### Responsibilities
- Define success metrics and instrumentation requirements early
- Validate telemetry implementation and data quality
- Build dashboards and reports for project tracking and post-release monitoring
- Analyze adoption, usage, and impact metrics
- Conduct post-release analysis and communicate findings
- Identify anomalies and support incident investigation

#### Goals
- Enable data-driven decision-making throughout the project lifecycle
- Measure and communicate project impact and ROI
- Support rapid problem detection and response

#### Interaction with Other Roles
- **With Product Manager/PdM:** Aligns on success metrics and KPIs at project start
- **With Developers:** Ensures proper instrumentation and telemetry integration
- **With Project Manager:** Provides weekly metrics updates and trend analysis
- **With QA:** Supports test data setup and validates monitoring during QA testing

#### Typical Communication
- Success metrics definition sessions
- Weekly metrics dashboards and status updates
- Post-release analysis and retrospectives
- Anomaly alerts and investigation support

---

### Documentation Owner / Technical Writer

#### Role Summary
Documentation Owners ensure user-facing docs, internal runbooks, and support materials are complete, accurate, and accessible. They are the bridge between technical teams and users/support.

#### Responsibilities
- Own user-facing documentation and help content
- Create and maintain internal runbooks and operational guides
- Collect information from teams and synthesize into clear documentation
- Review documentation for accuracy and completeness before release
- Maintain consistency in tone, format, and terminology
- Work with support teams to identify documentation gaps

#### Goals
- Reduce support burden by providing clear, comprehensive documentation
- Enable self-service and faster onboarding
- Build a single source of truth for user and operational guidance

#### Interaction with Other Roles
- **With Developers:** Gathers technical details and reviews for accuracy
- **With QA:** Validates documentation against actual behavior and edge cases
- **With Product Manager/PdM:** Ensures docs reflect intended use and value propositions
- **With Project Manager:** Included in release planning to ensure docs are ready
- **With Support Liaison:** Receives feedback on gaps and unclear areas

#### Typical Communication
- Documentation drafts and review cycles
- Information gathering sessions with technical teams
- Release notes and migration guide preparation
- Support team feedback and gap analysis

---

### Support Liaison / Customer Success Contact

#### Role Summary
Support Liaisons act as the voice of the customer within the product team. They triage support issues, collect patterns of customer impact, and feed insights back to product and engineering.

#### Responsibilities
- Serve as primary point of contact for support team escalations
- Triage and categorize support issues for product team review
- Identify patterns and trends in customer-impacting issues
- Escalate high-priority or widespread issues to engineering and product
- Participate in incident response for customer-impacting issues
- Collect and communicate customer feedback on features and quality

#### Goals
- Reduce time to resolution for customer issues
- Identify and prioritize quality and usability problems
- Enable faster feedback loops between customers and product teams

#### Interaction with Other Roles
- **With Support Team:** Receives escalations and customer feedback
- **With Product Manager/PdM:** Communicates customer needs and requests
- **With Project Manager:** Escalates and tracks resolution of customer-impacting issues
- **With QA:** Provides real-world failure scenarios and edge cases
- **With Documentation Owner:** Reports documentation gaps and confusion

#### Typical Communication
- Support triage meetings and escalation emails
- Customer feedback summaries and trend reports
- Incident participation and post-mortem contributions
- Weekly customer impact briefings

---

## How These Personas Work Together

### Example: Feature Release Scenario

1. **Planning Phase:**
   - PdM defines success metrics with Data Analyst
   - UX Researcher validates customer needs
   - Tech Lead estimates technical scope
   - PM creates timeline with Release Engineer input

2. **Execution Phase:**
   - Developers implement; Tech Lead reviews code
   - QA tests against acceptance criteria (UX and functional)
   - Documentation Owner drafts user guides
   - Data Analyst sets up instrumentation

3. **Release Phase:**
   - Release Engineer prepares deployment pipeline
   - All acceptance criteria must be met
   - Documentation is finalized
   - Support Liaison briefs support team

4. **Post-Release:**
   - Data Analyst monitors success metrics
   - Support Liaison escalates customer issues
   - Team captures learnings in retrospective
   - All action items fed into next iteration

### Example: Incident Scenario

When a critical production issue occurs:
- **Support Liaison** identifies and escalates the issue
- **Tech Lead** and **Developers** diagnose root cause
- **Release Engineer** prepares and executes rollback if needed
- **Project Manager** coordinates communication and escalation
- **Data Analyst** analyzes impact scope
- **Documentation Owner** prepares communication if needed
- **Team** conducts post-incident retrospective to prevent recurrence

---

## How to Use These Personas in Your Projects

- **On project kickoff:** Identify which personas apply to your project and assign owners
- **In Copilot Spaces:** Use persona names as context prompts (e.g., "From the perspective of a Tech Lead...") to shape role-specific guidance
- **In retrospectives:** Discuss where handoffs were smooth or rough and how personas could clarify ownership
- **In documentation:** Reference personas in checklists and processes to make responsibilities explicit

