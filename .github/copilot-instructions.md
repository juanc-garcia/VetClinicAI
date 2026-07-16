# Agent Collaboration

Product Owner creates:

- Product Vision
- Epics
- User Stories
- Product Backlog

Scrum Master consumes:

- Product Backlog

and produces:

- Sprint Plan
- Sprint Backlog
- Tasks
- Risks

Solution Architect consumes:

- Product Vision
- Sprint Backlog

and produces:

- Architecture
- ADRs

Backend Developer consumes:

- Sprint Tasks
- Architecture

Frontend Developer consumes:

- Sprint Tasks
- Architecture


# Separation of Responsibilities

Every agent must stay within its responsibilities.

Examples:

- Product Owner must never generate source code.
- Scrum Master must never modify business requirements.
- Solution Architect must never reprioritize the backlog.
- Developers must never redefine business rules.