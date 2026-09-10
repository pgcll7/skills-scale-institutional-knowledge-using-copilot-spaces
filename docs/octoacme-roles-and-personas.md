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

## QA/Testing Lead

### Role Summary
QA/Testing Leads own quality assurance strategy and coordinate testing efforts across the project. They work with developers to define test approaches, validate acceptance criteria, and ensure confidence in releases.

### Responsibilities
- Design and maintain test plans and test automation strategies
- Coordinate QA efforts and testing activities with the team
- Validate that acceptance criteria are met before release
- Manage test automation tools and frameworks
- Identify quality risks and propose testing approaches to mitigate them
- Track quality metrics and test coverage

### Goals
- Achieve high test coverage with effective automated and manual tests
- Detect defects early in the development cycle
- Build team confidence in release quality
- Reduce post-release defects and support burden

### Typical Communication
- Test planning discussions with Developers and Product Managers
- Quality metrics and test reports to Project Managers
- Release readiness reviews before deployments
- Coordination of smoke tests and UAT activities

### Interactions with Existing Roles
- **With Developers**: Collaborate on test strategy, test coverage targets, and integration test planning
- **With Product Managers**: Validate acceptance criteria are testable; prioritize testing based on feature importance
- **With Project Managers**: Provide quality status and release readiness assessments; identify quality-related risks and dependencies

---

## Sponsor/Executive Stakeholder

### Role Summary
Sponsors are senior stakeholders who provide business context, strategic direction, and decision-making authority. They ensure projects align with business priorities and remove organizational barriers.

### Responsibilities
- Provide business context and strategic rationale for projects
- Approve major project decisions and resource allocations
- Remove organizational blockers and dependencies outside the team's control
- Participate in milestone reviews and gate decisions
- Communicate project status and outcomes to executive leadership

### Goals
- Ensure business goals and objectives are achieved
- Maintain stakeholder alignment and executive visibility
- Optimize resource allocation across competing priorities
- Manage business-level risks and dependencies

### Typical Communication
- Project charter and approval meetings
- Milestone and gate reviews
- Escalation of critical risks and decisions
- Executive status updates and outcome reporting

### Interactions with Existing Roles
- **With Project Managers**: Receive escalations of high-impact issues; provide timely decisions on trade-offs and resources
- **With Product Managers**: Align on business priorities, success metrics, and strategic direction
- **With Team**: Participate in kickoffs and major milestones to demonstrate commitment and provide context

---

## Technical Lead/Architect

### Role Summary
Technical Leads drive technical strategy, make architectural decisions, and mentor developers. They ensure solutions are scalable, maintainable, and aligned with technical standards.

### Responsibilities
- Define technical strategy and architecture for projects
- Make or facilitate major technical decisions
- Conduct technical design reviews and code reviews
- Identify technical risks and propose mitigation strategies
- Mentor developers on technical best practices and architectural patterns
- Manage technical debt and plan refactoring efforts
- Ensure solutions meet non-functional requirements (performance, scalability, security)

### Goals
- Deliver sound technical architecture that supports current and future needs
- Reduce rework through good design and early technical decision-making
- Build team capability and technical decision-making maturity
- Maintain code quality and architectural consistency

### Typical Communication
- Technical design reviews and architecture discussions
- Code review feedback and mentoring
- Risk assessments and technical trade-off analyses
- Technology and dependency decisions

### Interactions with Existing Roles
- **With Developers**: Provide technical guidance, review designs and code, mentor on best practices
- **With Project Managers**: Advise on technical timeline impacts, technical risks, and architectural dependencies
- **With Product Managers**: Discuss feasibility of features, technical trade-offs, and non-functional requirements
- **With QA/Testing Lead**: Define testability requirements and technical testing strategy

---

## Dependent Team Lead/Partner

### Role Summary
Dependent Team Leads represent partner or dependent teams whose work impacts this project. They coordinate cross-team dependencies and ensure integration points are well-managed.

### Responsibilities
- Coordinate dependencies and handoffs with dependent teams
- Communicate integration requirements and timelines clearly
- Manage resource availability from partner teams
- Participate in project planning and kickoff to identify dependencies early
- Escalate resource conflicts or timeline misalignments
- Ensure partner team work progresses on schedule and meets integration requirements

### Goals
- Deliver dependent work on time and integrated successfully
- Maintain clear communication across team boundaries
- Prevent surprises and minimize integration rework
- Enable both teams to succeed through transparent coordination

### Typical Communication
- Dependency tracking and integration sync meetings
- Integration requirement specifications
- Timeline and readiness updates
- Escalation of blockers or resource conflicts

### Interactions with Existing Roles
- **With Project Managers**: Participate in dependency identification, provide timeline and capacity visibility, escalate blockers
- **With Developers**: Define integration requirements and technical handoff points
- **With Technical Leads**: Discuss architectural integration points and technical dependencies
- **With Team**: Attend kickoff and planning sessions to ensure dependencies are well-understood

---

## Business Analyst/Domain Expert

### Role Summary
Business Analysts translate business requirements into technical specifications and validate that solutions meet business needs. They facilitate conversations between business stakeholders and the delivery team.

### Responsibilities
- Analyze and document business requirements clearly
- Translate business needs into acceptance criteria and user stories
- Validate that solutions address the original business problem
- Facilitate discussions between stakeholders and the delivery team
- Clarify ambiguous requirements and resolve conflicts
- Ensure acceptance criteria are testable and measurable
- Document business logic and domain knowledge for team reference

### Goals
- Ensure requirements are clear, complete, and testable before development
- Reduce rework due to misunderstood or incomplete requirements
- Build shared understanding of business problems across the team
- Deliver solutions that truly address business needs

### Typical Communication
- Requirement refinement and clarification sessions
- User story creation and acceptance criteria definition
- Business process documentation
- Validation and acceptance of completed work

### Interactions with Existing Roles
- **With Product Managers**: Collaborate on requirements prioritization and success metrics
- **With Developers**: Clarify acceptance criteria, answer domain questions, help with story refinement
- **With Project Managers**: Provide visibility into requirement clarity and readiness; identify requirements-related risks
- **With QA/Testing Lead**: Ensure acceptance criteria are testable and define test scenarios

---

## Communication/Marketing Lead

### Role Summary
Communication/Marketing Leads manage release communications and coordinate announcements for high-visibility releases. They ensure customers, support teams, and stakeholders are well-informed and prepared for new features or changes.

### Responsibilities
- Coordinate release announcements and communications strategy
- Draft and publish release notes and customer-facing documentation
- Coordinate announcement timing with deployments and support team readiness
- Prepare customer education and training materials
- Manage FAQ and known issues documentation
- Communicate with support teams on product changes and new features

### Goals
- Ensure clear, timely communication of releases and changes
- Build customer awareness and successful adoption
- Reduce support burden through proactive communication
- Maintain positive customer perception of releases

### Typical Communication
- Release planning and communication strategy meetings
- Release note drafting and review
- Announcement timing coordination
- Customer communication and support materials

### Interactions with Existing Roles
- **With Product Managers**: Align on release messaging and customer value propositions
- **With Project Managers**: Coordinate release timeline and readiness activities
- **With Developers**: Gather technical accuracy information for documentation
- **With QA/Testing Lead**: Understand known issues and compatibility information for communication

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.
