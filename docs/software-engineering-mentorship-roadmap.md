# Software Engineering Mentorship Roadmap 4.1

**Target Role:** Backend / Software Engineer  
**Target Industry:** Fintech / Digital Banking / SaaS  
**Primary Technology Stack:** TypeScript, Node.js, NestJS, PostgreSQL  
**Initial Direct Mentoring:** 15 hours across 11 proposed sessions; extendable by mutual agreement  
**Estimated Learning Duration:** Indicative 3–6 months; flexible based on learning progress  

**Status:** Draft for Mentor Review

---

## 1. Program Overview

### Objective

The objective of this mentorship program is to develop an engineering mindset and practical competencies required to design, build, validate, and maintain reliable backend systems.

The program emphasizes software engineering fundamentals, problem-solving capabilities, system architecture, database reliability, application security, payment integration, and technical decision-making.

Rather than focusing solely on mastering specific technologies, the candidate is expected to understand the reasoning behind engineering decisions and demonstrate the ability to apply those decisions through practical implementation.

### Target Competencies

- Analyze business problems and translate them into technical requirements.
- Build modular and maintainable backend applications using TypeScript and NestJS.
- Design relational databases and implement reliable data operations.
- Understand software architecture and system design fundamentals.
- Apply database transactions, concurrency handling, and idempotency.
- Identify common backend security risks and implement appropriate security controls.
- Apply testing practices to validate business logic, system behavior, and security requirements.
- Integrate an external payment gateway using Xendit and handle payment notifications securely and reliably.
- Communicate technical decisions through documentation, RFCs, and technical discussions.

## 2. Learning Workflow

The mentorship follows an engineering-oriented workflow:

1. Problem Discovery & Requirement Analysis
2. Project Planning & Scope Definition
3. System Architecture & Data Design
4. Technical Design Document (TDD) & RFC
5. Security Considerations & Threat Analysis
6. Minimal UX/UI Prototyping
7. Backend Implementation using NestJS
8. Testing, Security Validation & Reliability Review
9. Technical Presentation & Engineering Evaluation

The candidate is expected to understand the problem before selecting technologies or implementing solutions.

All curriculum topics are retained; learning depth, pace, and evidence of achievement are adjusted to the candidate's progress.

The estimated 3–6 months is indicative, not a fixed completion deadline.

## 3. Curriculum Pillars

### Pillar 1 — Problem Solving, Logic & Business Algorithmic Thinking

Develop the ability to analyze problems, understand business rules, and translate requirements into logical solutions.

**Topics:**

- Problem Decomposition
- Computational Thinking
- Algorithmic Thinking
- Data Structures Fundamentals
- Business Logic Modeling
- Edge Case Identification
- Complexity Analysis Fundamentals
- State and Workflow Modeling

**Expected Outcome:**

The candidate can independently analyze a business problem, identify relevant constraints, define business rules, and translate them into implementable logic.

### Pillar 2 — TypeScript Ecosystem & Runtime Mechanics

Develop strong TypeScript fundamentals and understand the runtime environment used in modern backend development.

**Topics:**

- TypeScript Strict Mode
- Type System, Generics, and Utility Types
- Advanced TypeScript Concepts
- Node.js and Bun Runtime Fundamentals
- Event Loop and Asynchronous Processing
- Promises and Async/Await
- Error Handling
- NestJS Modules, Controllers, and Providers
- Dependency Injection and Inversion of Control
- Middleware, Guards, Interceptors, and Pipes

**Expected Outcome:**

The candidate can build type-safe backend applications, understand asynchronous execution, and explain the role of NestJS architectural components.

### Pillar 3 — Software Architecture & Clean Architecture

Develop the ability to structure backend applications with clear responsibilities and maintainable boundaries.

**Topics:**

- Layered Architecture
- Modular Architecture
- Separation of Concerns
- Dependency Direction
- Repository Abstraction
- SOLID Principles
- Design Patterns: Repository, Factory, Singleton, and Strategy
- Unit Testing and Integration Testing
- Maintainability and Testability

**Expected Outcome:**

The candidate can design modular backend applications, maintain clear separation of responsibilities, and explain architectural trade-offs.

### Pillar 4 — PostgreSQL Engineering & High-Reliability Systems

Develop the ability to design relational databases and implement reliable data operations.

**Topics:**

- Relational Data Modeling
- Database Normalization
- Primary Keys, Foreign Keys, and Constraints
- Indexing and Query Optimization
- Query Execution Plans
- ACID Transactions
- Transaction Isolation Levels
- Race Conditions
- Row-Level Locking
- Optimistic and Pessimistic Locking
- Idempotency
- Payment Gateway Integration Fundamentals using Xendit
- Payment Request / Invoice Creation and Payment Lifecycle
- Webhook Handling, Callback Token Verification, and Payment Status Management
- Connection Pooling
- Redis Fundamentals
- Rate Limiting
- Message Queue and Distributed Lock Concepts

**Expected Outcome:**

The candidate can design relational schemas, write efficient queries, implement database transactions, and understand common reliability problems in concurrent backend systems.

### Pillar 5 — Project Management & Delivery Planning

Develop the ability to plan and manage software development work based on clear objectives and constraints.

**Topics:**

- Problem Definition and Project Objectives
- Scope, Assumptions, and Constraints
- Acceptance Criteria
- Epics, Features, and User Stories
- Backlog Management
- Estimation and Prioritization
- Milestone Planning
- Risk Identification
- Kanban and Scrum Fundamentals
- Definition of Ready and Definition of Done

**Expected Outcome:**

The candidate can translate project requirements into manageable tasks, define project scope, and plan incremental delivery.

### Pillar 6 — System Design

Develop the ability to design backend systems based on functional and non-functional requirements.

**Topics:**

- Functional and Non-Functional Requirements
- High-Level Design (HLD)
- Low-Level Design (LLD)
- Component and Sequence Diagrams
- API Design
- Data Flow and State Machine
- Scalability and Availability
- Consistency and Latency
- Reliability and Performance
- Security Considerations
- Observability Fundamentals
- Engineering Trade-offs

**Expected Outcome:**

The candidate can produce a system design, identify technical constraints, evaluate architectural alternatives, and explain the trade-offs behind design decisions.

### Pillar 7 — TDD & RFC

Develop the ability to document technical decisions and communicate implementation plans before development.

**Topics:**

- Technical Design Document Structure
- Context, Goals, and Non-Goals
- Functional and Non-Functional Requirements
- Architecture and Data Model
- API Specification
- Alternative Solutions
- Trade-offs and Risks
- Security Considerations
- Testing Strategy
- Rollout and Migration Planning
- RFC Review and Feedback Process

**Expected Outcome:**

The candidate can produce a technical design document and RFC that explain the problem, proposed solution, alternatives, risks, and implementation approach.

### Pillar 8 — Product Thinking & Minimal UI/UX Prototyping

Develop basic product awareness and the ability to collaborate with frontend and product teams.

**Topics:**

- User Journey
- User Flow
- Wireframing
- Minimal Prototyping
- Form and Navigation Design
- Validation and Error States
- Loading and Empty States
- Accessibility Fundamentals

**Expected Outcome:**

The candidate can understand user workflows and create basic prototypes to validate product requirements before implementation.

### Pillar 9 — Technical Communication & Career Readiness

Develop the ability to communicate engineering decisions and demonstrate technical competency.

**Topics:**

- Explaining Technical Decisions
- Engineering Trade-off Discussions
- Technical Documentation
- OpenAPI Documentation
- Pull Request Description
- Commit Message Conventions
- Code Review
- Technical Presentation
- English for Technical Communication
- Backend and System Design Interview Fundamentals

**Expected Outcome:**

The candidate can explain implementation decisions, communicate technical risks, document work, and present project results clearly.

### Pillar 10 — Security Engineering Fundamentals

Develop the ability to identify, prevent, and mitigate common security risks in backend applications throughout the design, implementation, testing, and deployment lifecycle.

#### 1. Authentication & Authorization Security

- Authentication and Authorization Fundamentals
- JWT Security
- Access Token and Refresh Token
- Password Hashing using Argon2 or bcrypt
- Role-Based Access Control (RBAC)
- Permission-Based Authorization
- Object-Level and Function-Level Access Control
- Session and Token Management

#### 2. OWASP API Security

- OWASP API Security Top 10
- Broken Object Level Authorization (BOLA)
- Broken Authentication
- Broken Object Property Level Authorization
- Broken Function Level Authorization
- Unrestricted Resource Consumption
- Security Misconfiguration
- Server-Side Request Forgery (SSRF) Fundamentals

#### 3. Secure Data Handling

- Sensitive Data Protection
- Secrets Management
- Environment and Credential Management
- Secure Token Handling
- Prevention of Sensitive Data Exposure
- Database Credential Management

#### 4. Input Validation & Attack Prevention

- SQL Injection Prevention
- Parameterized Queries
- Input Validation and Sanitization
- Mass Assignment Prevention
- Request Size Limiting
- Rate Limiting
- Secure Error Handling

#### 5. Threat Modeling & Security by Design

- Threat Modeling Fundamentals
- Attack Surface Identification
- STRIDE Fundamentals
- Security Requirements
- Security Risk Assessment
- Security Considerations during System Design

#### 6. Security Testing

- Authentication Testing
- Authorization Testing
- Access Control Testing
- Input Validation Testing
- API Security Testing
- Negative Test Cases for Security-Sensitive Workflows

**Expected Outcome:**

The candidate can identify common backend security risks, implement appropriate security controls, and validate them through practical testing within a backend project.

## 4. Competency Prioritization & Learning Depth

To maintain a focused and realistic learning process, all curriculum topics are categorized into three competency levels based on their importance to the Backend / Software Engineer role.

### Priority 1 — Core Competencies (Mastery)

- Problem Solving and Business Logic
- TypeScript Fundamentals and Advanced Concepts
- Node.js Runtime Mechanics
- NestJS Development
- Database Design and SQL
- Software Architecture Fundamentals
- Unit and Integration Testing
- Authentication and Authorization Fundamentals
- Password Hashing
- SQL Injection Prevention

**Learning Expectation:**

The candidate must be able to explain, implement, debug, and evaluate these competencies independently.

### Priority 2 — Applied Engineering Competencies (Practical Application)

- Database Transactions and ACID
- Concurrency and Race Condition Handling
- Idempotency
- System Design
- Clean Architecture
- Security Engineering
- OWASP API Security
- Secrets Management
- Threat Modeling Fundamentals
- Security Testing
- Project Planning and Delivery
- Basic Observability

**Learning Expectation:**

The candidate must be able to apply these concepts to practical engineering problems and explain the reasoning behind their implementation.

### Priority 3 — Supporting Competencies (Working Knowledge)

- UI/UX Fundamentals
- Project Management Methodologies
- Advanced Design Patterns
- Message Queue Concepts
- Distributed Lock Concepts
- Technical Communication
- Technical Documentation

**Learning Expectation:**

The candidate should understand the purpose, use cases, and basic trade-offs of these competencies without requiring deep specialization at this stage.

### Learning Principle

Learning depth should be determined by competency requirements and practical relevance, not by the number of topics completed.

The mentor and mentee should prioritize learning activities based on the candidate's initial assessment, project requirements, and demonstrated learning progress.

### Learning Pace & Sustainable Progress

The candidate is not expected to master every topic at the same depth or complete the entire curriculum within the initial mentoring hours.

Progress should be evaluated through demonstrated understanding, practical implementation, reflection, and the ability to explain technical decisions.

Repetition, independent study, project work, and rest are legitimate parts of the learning process.

The mentor and mentee may adjust pacing and milestones to prevent an unsustainable workload and support long-term consistency.

## 5. Learning Phases

### Phase 1 — Problem Discovery & TypeScript Mastery

**Focus:**

- Problem Decomposition
- Business Logic Analysis
- TypeScript Fundamentals and Advanced Concepts
- Strict TypeScript Configuration
- Asynchronous Programming
- Node.js Runtime Mechanics

**Deliverables:**

- Problem Analysis Document
- Business Rules and Edge Cases
- TypeScript Implementation Exercises

### Phase 2 — NestJS Modular API & Runtime Mechanics

**Focus:**

- NestJS Architecture
- Modules, Controllers, and Providers
- Dependency Injection
- Middleware, Guards, Interceptors, and Pipes
- REST API Design
- Authentication Fundamentals

**Deliverables:**

- Modular NestJS API
- API Specification
- Authentication Implementation

### Phase 3 — Architecture, TDD/RFC & Testing

**Focus:**

- Clean Architecture Fundamentals
- SOLID Principles
- Separation of Concerns
- Technical Design Document
- RFC Writing
- Unit and Integration Testing

**Deliverables:**

- Architecture Diagram
- Technical Design Document
- RFC Document
- Automated Test Cases

### Phase 4 — Database Reliability, Security & System Design

**Focus:**

- PostgreSQL Engineering
- Database Transactions and ACID
- Concurrency and Race Conditions
- Idempotency
- Database Locking
- Security Engineering Fundamentals
- Threat Modeling
- API Security
- Security Testing
- System Design

**Deliverables:**

- Database Schema and ERD
- Transaction and Concurrency Implementation
- Security Risk Assessment
- Security Test Cases
- System Design Document

### Phase 5 — Project Planning & Product Validation

**Focus:**

- Project Scope and Objectives
- User Stories and Acceptance Criteria
- Backlog Management
- Milestone Planning
- Risk Management
- User Flow and Wireframing

**Deliverables:**

- Project Brief
- Product Backlog
- Milestone Plan
- Basic UI/UX Prototype

### Phase 6 — Portfolio Project Execution & Technical Defense

**Focus:**

- End-to-End Backend Implementation
- Xendit Payment Gateway Integration and Webhook Reliability
- Architecture Review
- Database Reliability Review
- Security Validation
- Automated Testing
- Code Review
- Technical Documentation
- Technical Presentation

**Deliverables:**

- Completed Backend Portfolio Project
- OpenAPI Documentation
- Test Evidence
- Security Validation Evidence
- README and Technical Documentation
- Final Technical Presentation

## 6. Portfolio Project Options

### Option 1 — Digital Wallet & Transaction Engine API

A backend system for managing digital wallets and financial transactions, including external payment processing integration using Xendit.

**Core Features / Engineering Focus:**

- User Registration and Authentication
- Wallet Creation and Management
- Balance Management
- Fund Transfer
- Transaction History
- Atomic Database Transactions
- Idempotency
- Audit Logs
- Role-Based Access Control
- Xendit Payment Gateway Integration (Sandbox/Test Mode)
- Payment Request / Invoice Creation
- Payment Webhook Handling
- Webhook Callback Token Verification
- Payment Status and Transaction State Management

**Additional Engineering Focus:**

- Database Transactions
- ACID Properties
- Concurrency Handling
- Idempotency
- API Security
- Object-Level Authorization
- Security Testing

### Option 2 — High-Concurrency Seat & Ticket Booking Engine

A backend system for handling seat reservations and ticket purchases under high concurrency.

**Core Features / Engineering Focus:**

- Concurrency Control
- Database Locking
- Transaction Consistency
- Idempotency
- Reservation Expiration
- Race Condition Prevention

### Option 3 — Flash Sale & Inventory Management API

A backend system for managing limited inventory during high-traffic sales events.

**Core Features / Engineering Focus:**

- Inventory Consistency
- Concurrency Handling
- Atomic Transactions
- Queue-Based Processing
- Rate Limiting
- Resource Consumption Control

### Option 4 — Ride-Hailing & Order Dispatch Matching

A backend system for matching customer orders with available service providers.

**Core Features / Engineering Focus:**

- Matching Algorithms
- Geospatial Fundamentals
- State Management
- Asynchronous Processing
- System Design
- Scalability Considerations

## 7. Mentoring Session Allocation

**Initial Direct Mentoring Commitment:** 15 Hours.

This is the initial mentoring agreement, not a maximum limit for the overall program.

Additional mentoring hours may be arranged by mutual agreement based on learning progress, competency gaps, project complexity, and further learning needs.

The session allocation below is a proposed starting structure and may be adjusted by the mentor and mentee.

| Session | Focus | Duration (Hours) |
|---|---|---:|
| 1 | Diagnostic Assessment & Learning Objectives | 1.5 |
| 2 | Problem Solving & TypeScript | 1.5 |
| 3 | NestJS & Runtime Mechanics | 1.5 |
| 4 | Software Architecture & Testing | 1.5 |
| 5 | Project Management & Delivery Planning | 1.5 |
| 6 | System Design & Technical Documentation | 1.5 |
| 7 | TDD/RFC & Engineering Decisions | 1 |
| 8 | PostgreSQL, ACID & Concurrency | 1.5 |
| 9 | Security Engineering & API Security | 1.5 |
| 10 | Reliability, Observability & Product Validation | 1 |
| 11 | Architecture Review, Code Review & Technical Defense | 1 |
| **Total** | | **15** |

**Mentoring Principle:**

Direct mentoring sessions should prioritize conceptual clarification, technical discussions, design reviews, problem-solving guidance, and feedback.

Implementation, experimentation, documentation, and independent exercises are expected to be completed outside mentoring sessions.

The pace and number of sessions may be extended when additional guidance is beneficial; completion should be based on demonstrated competency rather than a rigid hour or calendar limit.

## 8. Graduation Criteria

### Problem Solving

- Independently analyze a business problem.
- Identify requirements, constraints, and edge cases.
- Translate business rules into technical logic.

### Backend Development

- Build modular and type-safe NestJS applications.
- Understand asynchronous processing.
- Implement REST APIs with appropriate validation and error handling.

### Software Architecture

- Explain architectural decisions.
- Apply separation of concerns.
- Design maintainable and testable application structures.

### Database Engineering

- Design relational schemas.
- Implement transactions.
- Understand common concurrency problems and implement appropriate handling for the project's scope, with guidance when needed.
- Apply idempotency where required.

### Security Engineering

- Implement authentication and authorization.
- Protect sensitive data and application credentials.
- Identify common API security risks.
- Apply appropriate security controls.
- Integrate Xendit payment flows and process verified payment webhooks without duplicate transaction effects.
- Demonstrate security validation through relevant automated tests for the project's scope.

### System Design & Documentation

- Produce basic system design documentation.
- Create TDD/RFC documents.
- Explain engineering trade-offs.

### Project Delivery

- Define project scope and acceptance criteria.
- Manage a project backlog.
- Deliver a functional backend portfolio project with documented scope, trade-offs, and testing evidence.

### Technical Communication

- Explain technical decisions.
- Participate in code review.
- Present project architecture and implementation results.

## 9. Required Engineering Artifacts

- Problem Brief and Requirement Analysis
- Project Backlog and Milestone Plan
- Risk Register
- Context and Component Diagrams
- Entity Relationship Diagram
- Sequence Diagrams
- Technical Design Document
- RFC Document
- Security Risk Assessment
- OpenAPI Documentation
- Minimal UI/UX Prototype
- Automated Test Plan and Evidence
- Security Test Cases and Evidence
- Payment Integration Flow and Webhook Test Evidence
- Code Review Notes
- Final README and Technical Presentation

## 10. Recommended Tools & Technologies

### Development

- TypeScript
- Node.js
- NestJS
- Xendit API (Sandbox/Test Mode)
- PostgreSQL
- Prisma ORM or TypeORM
- Redis
- Jest
- Docker
- Git and GitHub

### Project Management

- GitHub Projects
- Trello or Linear

### Architecture & Documentation

- Mermaid
- Excalidraw
- diagrams.net
- Markdown
- GitHub Issues and Pull Requests

### API Documentation

- OpenAPI
- Swagger
- Scalar

### Product Design

- Figma

### Security References

- OWASP API Security Top 10
- OWASP Application Security Verification Standard (ASVS)

## 11. Guiding Principles

1. Understand the problem before selecting a technology.
2. Prioritize engineering fundamentals over framework-specific knowledge.
3. Apply proportional design based on project requirements.
4. Document important technical decisions and trade-offs.
5. Build incrementally and validate continuously.
6. Treat security as part of the development lifecycle, not as an afterthought.
7. Use AI as an engineering assistant, not as a replacement for independent reasoning.
8. Verify technical decisions through documentation, experiments, and practical implementation.
9. Focus on demonstrated competency rather than the number of completed topics.

## Final Objective

Develop a backend engineer who can independently analyze problems, design maintainable systems, implement reliable and secure backend applications, validate engineering decisions, and communicate technical reasoning effectively.

---

**End of Roadmap 4.1**