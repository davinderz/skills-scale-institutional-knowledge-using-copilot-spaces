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

## Scrum Master

### Role Summary
Scrum Masters facilitate agile ceremonies, remove blockers, and coach the team on agile best practices. They ensure the development process runs smoothly and help the team continuously improve their workflow.

### Responsibilities
- Facilitate agile ceremonies (daily standups, sprint planning, retrospectives, sprint reviews)
- Remove impediments and blockers that prevent team progress
- Coach team members on agile principles and practices
- Foster a culture of continuous improvement and transparency
- Track team velocity and process health metrics
- Shield the team from external distractions and context switching

### Goals
- Maximize team productivity and efficiency
- Ensure adherence to agile practices and ceremonies
- Create a self-organizing, high-performing team
- Minimize blockers and reduce cycle time

### Typical Communication
- Daily standups with the delivery team
- Sprint planning and retrospectives with team and Product Manager
- Regular check-ins with PM to escalate risks and dependencies
- Process improvement discussions with PdM and team leads

### Interactions with Other Roles
- **Project Manager**: Escalates schedule risks, coordinates on cross-team dependencies, shares velocity and team health metrics
- **Product Manager**: Aligns on backlog priorities, ensures acceptance criteria clarity, facilitates sprint planning
- **Developers**: Coaches on agile practices, removes blockers, facilitates ceremonies and team communication

---

## UX Designer

### Role Summary
UX Designers own user research, design prototypes, and usability testing. They ensure products are user-centered, intuitive, and aligned with customer needs through research-driven design decisions.

### Responsibilities
- Conduct user research and create user personas
- Design wireframes, prototypes, and high-fidelity mockups
- Lead usability testing and gather user feedback
- Create and maintain design systems and style guides
- Collaborate on user flows and interaction patterns
- Validate designs through testing and iterate based on findings

### Goals
- Deliver user-centered, accessible designs
- Ensure consistent user experience across features
- Validate design decisions with user research and testing
- Minimize usability issues in production

### Typical Communication
- Design reviews and critique sessions
- User research findings presentations
- Design handoff sessions with developers
- Collaboration meetings with Product Manager on user needs

### Interactions with Other Roles
- **Product Manager**: Collaborates on user needs, validates problem statements with research, aligns on feature priorities
- **Developers**: Provides design specifications and assets, reviews implementation for design consistency, iterates on technical constraints
- **Project Manager**: Communicates design timeline and dependencies, flags resource needs for research activities

---

## Security Champion

### Role Summary
Security Champions identify and escalate security risks, advocate for security best practices, and ensure security considerations are integrated throughout the development lifecycle.

### Responsibilities
- Perform security risk assessments for features and changes
- Review code and architecture for security vulnerabilities
- Maintain and enforce security checklists and standards
- Coordinate security testing and vulnerability remediation
- Advocate for secure coding practices and threat modeling
- Stay current on security threats and industry best practices

### Goals
- Minimize security vulnerabilities in production
- Ensure compliance with security standards and policies
- Build security awareness across the team
- Detect and remediate risks early in development

### Typical Communication
- Security reviews during design and code review phases
- Risk escalations to PM and stakeholders
- Security training and awareness sessions with team
- Incident response coordination when needed

### Interactions with Other Roles
- **Project Manager**: Escalates security risks and compliance requirements, coordinates security testing timelines
- **Developers**: Reviews code for security issues, provides guidance on secure coding practices, pairs on security fixes
- **Product Manager**: Advises on security trade-offs in feature design, ensures security requirements are included in acceptance criteria

---

## Data Analyst

### Role Summary
Data Analysts define success metrics, analyze data from releases and experiments, and support data-informed decision making. They build dashboards and provide insights to guide product and process improvements.

### Responsibilities
- Define and track key performance indicators (KPIs)
- Analyze user behavior, feature adoption, and business metrics
- Build dashboards and reports for stakeholders
- Design and evaluate A/B tests and experiments
- Identify trends, patterns, and improvement opportunities
- Ensure data quality and reporting accuracy

### Goals
- Enable data-driven decision making across the team
- Provide actionable insights from data analysis
- Measure and communicate product impact clearly
- Identify opportunities for optimization and growth

### Typical Communication
- Weekly metrics reviews with Product Manager
- Dashboard reviews and insights presentations to stakeholders
- Experiment results and recommendations
- Data deep-dives when investigating specific issues

### Interactions with Other Roles
- **Product Manager**: Collaborates on success metrics definition, provides analysis to inform prioritization, validates hypotheses with data
- **Project Manager**: Shares progress metrics and KPIs, supports data-driven timeline and resource decisions
- **Developers**: Coordinates on instrumentation and data collection, validates data integrity, requests technical implementation for tracking

---

## Business Stakeholder

### Role Summary
Business Stakeholders provide business context, strategic priorities, and final approvals for deliverables. They represent business units and ensure projects align with organizational goals and requirements.

### Responsibilities
- Define business requirements and success criteria
- Provide context on market conditions and competitive landscape
- Review deliverables and provide approvals at key milestones
- Communicate business priorities and constraints
- Make go/no-go decisions at critical decision gates
- Represent business unit interests in project planning

### Goals
- Ensure projects deliver measurable business value
- Align technical delivery with business strategy
- Minimize business risk and maximize ROI
- Maintain clear communication of business expectations

### Typical Communication
- Monthly stakeholder updates from PM and PdM
- Milestone reviews and approval meetings
- Strategic planning sessions and roadmap reviews
- Ad-hoc consultations on business priorities

### Interactions with Other Roles
- **Project Manager**: Receives status updates, provides approvals at milestones, escalates business concerns or changes in priority
- **Product Manager**: Defines business goals and success criteria, reviews roadmap alignment, provides market and customer insights
- **Developers**: Reviews demos and deliverables, provides business context for technical decisions when needed

---

## Role Interaction Model

This section illustrates how all roles work together across the project lifecycle to ensure clear ownership and minimize gaps.

### Key Interaction Points

**Planning Phase**
- **Business Stakeholder** defines business goals → **Product Manager** translates to product requirements → **Project Manager** creates delivery plan → **Scrum Master** facilitates sprint planning → **Developers** estimate and commit to work
- **UX Designer** researches user needs → **Product Manager** incorporates into feature specs → **Developers** implement design
- **Data Analyst** defines success metrics → **Product Manager** aligns on KPIs → **Project Manager** tracks in project plan

**Development Phase**
- **Scrum Master** facilitates daily standups → **Developers** report progress and blockers → **Project Manager** tracks overall timeline
- **UX Designer** provides design specs → **Developers** implement → **UX Designer** validates implementation
- **Security Champion** reviews code and architecture → **Developers** remediate issues → **Project Manager** tracks security tasks
- **Product Manager** clarifies requirements → **Developers** implement features → **Scrum Master** removes blockers

**Release Phase**
- **Developers** deliver features → **Project Manager** coordinates release → **Product Manager** validates acceptance criteria → **Business Stakeholder** approves for production
- **Data Analyst** instruments tracking → **Developers** implement → **Data Analyst** monitors post-launch metrics
- **Security Champion** performs final security review → **Project Manager** confirms sign-off

**Retrospective Phase**
- **Scrum Master** facilitates retrospective → **All roles** provide feedback → **Project Manager** documents action items → **Team** commits to improvements
- **Data Analyst** presents outcome data → **Product Manager** evaluates success → **Business Stakeholder** reviews business impact

---

## Onboarding Checklist for Teams

Use this checklist to ensure clear role coverage and accountability for your project.

### Role Assignment
- [ ] Project Manager assigned and documented
- [ ] Product Manager assigned and documented
- [ ] Lead Developer(s) identified
- [ ] Scrum Master assigned (or responsibilities delegated)
- [ ] UX Designer assigned for user-facing features
- [ ] Security Champion identified for security review
- [ ] Data Analyst assigned for metrics and analysis
- [ ] Business Stakeholder(s) identified and engaged

### Role Clarity
- [ ] Each role's responsibilities are clearly defined for this project
- [ ] Interaction points between roles are documented
- [ ] Decision-making authority is clear for each role
- [ ] Escalation paths are defined for each role
- [ ] Communication cadence is established (standups, reviews, etc.)

### Coverage Validation
- [ ] All project phases have clear role ownership (planning, development, release, retrospective)
- [ ] Security review process is defined and owner is assigned
- [ ] UX/design process is defined for user-facing work
- [ ] Metrics and success criteria have an owner
- [ ] Business approval gates are identified with stakeholder names

### Documentation
- [ ] Role assignments documented in project charter or README
- [ ] Contact information for each role is accessible
- [ ] Responsibilities are added to project documentation
- [ ] This checklist is reviewed at project kickoff

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.
- This document addresses process improvement recommendations from [Issue #4](https://github.com/davinderz/skills-scale-institutional-knowledge-using-copilot-spaces/issues/4) to enhance role clarity and cross-functional collaboration.

