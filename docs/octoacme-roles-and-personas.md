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

## Technical Lead

### Role Summary
Technical Leads provide architecture and design leadership, mentor developers, and ensure technical decisions align with project goals and long-term system health.

### Responsibilities
- Architect major technical decisions and design patterns
- Coordinate cross-team technical design reviews
- Mentor developers on best practices and code quality
- Track and prioritize technical debt
- Bridge communication between engineering and product on technical feasibility
- Identify and mitigate technical risks

### Goals
- Maintain system scalability, reliability, and maintainability
- Accelerate team productivity through mentorship and tooling
- Ensure alignment between technical and business objectives
- Reduce technical risk and debt accumulation

### Typical Communication
- Technical design reviews and architecture discussions
- One-on-ones with developers for mentorship
- Escalations to PM/PdM on feasibility and trade-offs
- Documentation of architectural decisions (ADRs)

### Interaction with Other Roles
- Works closely with **Project Manager** for timeline feasibility and planning
- Collaborates with **Product Manager** on feature trade-offs and prioritization
- Partners with **Developers** on design implementation and code reviews
- Coordinates with **QA/Testing** on test automation and acceptance criteria testability

---

## Engineering Manager

### Role Summary
Engineering Managers support team development, manage capacity, and create psychological safety for high-performance delivery. They own people management while working closely with Project and Product Managers on execution.

### Responsibilities
- Hire, onboard, and develop team members
- Conduct performance reviews and career planning
- Manage team capacity and workload balance
- Identify and resolve blockers related to staffing or team dynamics
- Foster psychological safety and continuous learning
- Coordinate with PM on resource allocation and constraints

### Goals
- Build a high-performing, engaged team
- Reduce turnover and improve team retention
- Enable team members' growth and career development
- Prevent burnout and maintain team health metrics

### Typical Communication
- One-on-ones with direct reports
- Skip-level conversations and feedback sessions
- Collaboration with PM/PdM on resourcing and capacity planning
- Team retrospectives and culture-building activities

### Interaction with Other Roles
- Works with **Project Manager** on resourcing decisions and unblocking staffing issues
- Collaborates with **Product Manager** on feature prioritization given team capacity
- Supports **Technical Lead** in mentorship and developer growth
- Communicates with **Developers** on workload, growth opportunities, and team health

---

## Delivery Lead / Scrum Master

### Role Summary
Delivery Leads facilitate agile ceremonies, remove impediments, and coach the team on continuous improvement. They focus on process health and team flow rather than technical decisions or people management.

### Responsibilities
- Facilitate sprint planning, daily standups, reviews, and retrospectives
- Identify and escalate blockers preventing team progress
- Coach team on agile practices and process adherence
- Track and improve team velocity and cycle time metrics
- Remove administrative and process-related obstacles
- Maintain sprint and release dashboards

### Goals
- Maximize team flow and predictability
- Reduce cycle time and waste in delivery process
- Improve sprint consistency and velocity
- Foster continuous improvement mindset

### Typical Communication
- Daily standups and ceremony facilitation
- Blocker escalations to PM and Technical Lead
- Retrospective facilitation and action item tracking
- Team velocity and burndown metrics updates

### Interaction with Other Roles
- Works with **Project Manager** to surface risks and dependencies
- Collaborates with **Technical Lead** on technical blockers and design decisions
- Coaches **Developers** on agile practices and continuous improvement
- Coordinates with **QA/Testing** on readiness criteria and testing cadence

---

## UX Researcher / Designer

### Role Summary
UX Researchers and Designers understand customer needs, define user experience requirements, and validate solutions through research and testing. They ensure features are usable and deliver customer value.

### Responsibilities
- Conduct user research and gather customer feedback
- Define UX requirements and create wireframes/prototypes
- Create design specifications and component libraries
- Validate design solutions through user testing
- Collaborate on acceptance criteria related to user experience
- Document design decisions and design system updates

### Goals
- Maximize usability and customer satisfaction
- Reduce time to user value through research-informed design
- Build a consistent and scalable design system
- Advocate for user needs in prioritization decisions

### Typical Communication
- User research sessions and findings presentations
- Design reviews and feedback sessions
- Collaboration on acceptance criteria with developers and QA
- Design system documentation and component specifications

### Interaction with Other Roles
- Partners with **Product Manager** on outcome definition and success metrics
- Works with **Developers** on design implementation and feasibility
- Coordinates with **QA/Testing** on usability acceptance criteria
- Engages with **Customers/Support Liaison** for direct feedback loops

---

## Support / Customer Success Liaison

### Role Summary
Support and Customer Success Liaisons represent the voice of the customer, escalate issues from the field, and ensure support-related needs are prioritized and addressed in project planning and execution.

### Responsibilities
- Collect customer feedback from support interactions
- Escalate customer pain points and common issues to product team
- Participate in acceptance criteria definition for support-critical features
- Coordinate on incident triage and resolution
- Provide customer context during planning and prioritization
- Validate solutions from a support and customer usability perspective

### Goals
- Reduce customer support load and improve customer satisfaction
- Ensure features are operable and debuggable by support teams
- Accelerate time to resolution for customer issues
- Feed customer insights into product prioritization

### Typical Communication
- Weekly support metrics and trend reports
- Escalations of critical customer issues
- Participation in planning and backlog refinement
- Collaboration on runbooks and support documentation

### Interaction with Other Roles
- Works with **Project Manager** and **Product Manager** on customer-impacting prioritization
- Coordinates with **Developers** on reproducibility, debugging, and incident resolution
- Partners with **QA/Testing** on support scenario testing
- Engages with **UX Designer** on customer experience feedback loops

---

## Role Interaction Matrix

| Role | Reports To | Primary Stakeholders | Key Dependencies |
|------|-----------|---------------------|------------------|
| **Developer** | Engineering Manager / Tech Lead | Team, QA, PM, PdM | Design specs, requirements, infrastructure |
| **Product Manager** | Product Leadership | Stakeholders, customers, team | Market insights, customer feedback |
| **Project Manager** | Delivery Leadership | PM, PdM, team, stakeholders | Resource availability, dependencies |
| **Technical Lead** | Engineering Manager | Team, Architecture | Design decisions, technical debt visibility |
| **Engineering Manager** | Department Head | Team, HR, PM | Hiring, capacity, team dynamics |
| **Delivery Lead** | Project Manager | Team, PM | Sprint goals, blockers, metrics |
| **UX Researcher/Designer** | Design Leadership | PdM, team, customers | User research, acceptance criteria |
| **Support/CS Liaison** | Support Leadership | Support team, customers, PM, PdM | Customer feedback, escalations |

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.
- Reference the interaction matrix when modeling cross-functional workflows and dependencies.
- Use the responsibility descriptions to clarify ownership during project planning and escalations.
