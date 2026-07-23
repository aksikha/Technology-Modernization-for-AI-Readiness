# People and Governance

Modernization begins with accountability—not technology selection.

Before changing platforms, architecture, or introducing AI, the organization must establish clear ownership, decision rights, executive sponsorship, and sufficient knowledge coverage to operate and modernize critical services safely.

## Common Current-State Challenges

- Technology teams operate at a distance from business stakeholders.
- Incident and project work depends heavily on senior individuals for triage and direction.
- Critical knowledge is concentrated in people rather than documented in diagrams, runbooks, and systems.
- Work status and ownership are difficult for business stakeholders to see.
- Role overlap creates unclear decision rights and inconsistent accountability.
- Architecture ownership is unclear across applications, data, integrations, platforms, and business capabilities.

---

## Step 1 — Align Business Outcomes and Executive Sponsorship

### Action

Define:

- Why modernization is required.
- Which business capabilities and critical services must be protected.
- The constraints that cannot be violated.
- The outcomes leadership expects.
- The executives responsible for decisions and removing barriers.

### Technical Outputs

- Modernization charter
- Business outcome measures
- Risk boundaries
- Executive sponsor map
- Decision forum and escalation path

### Expected Outcome

A common purpose that prevents modernization from becoming a disconnected collection of technology projects.

---

## Step 2 — Define Ownership, Roles, and Decision Rights

### Action

Assign accountable business and technology owners for:

- Business services
- Applications
- Data
- Architecture decisions
- Funding
- Delivery
- Quality
- Security
- Production changes
- AI-generated or AI-assisted changes

### Technical Outputs

- Ownership registry
- Role definitions
- RACI matrix
- Architecture decision authority
- Escalation path
- Production approval model

### Expected Outcome

Faster decisions, fewer handoffs, and clear accountability for business value, technology risk, and operational outcomes.

---

## Step 3 — Distribute Knowledge and Build Modernization Capability

### Action

- Document critical operational and architecture knowledge.
- Rotate responsibilities across team members.
- Identify technical and business skill gaps.
- Pair domain experts with architects and engineers.
- Establish backup coverage for critical roles and services.
- Create a learning plan for modernization, cloud, data, security, architecture, and AI skills.

### Technical Outputs

- Skills matrix
- Critical-role backup map
- Service documentation
- Current-state architecture diagrams
- Runbooks
- Knowledge repository
- Learning and succession plan

### Expected Outcome

Reduced key-person dependency and a workforce capable of operating and modernizing the technology estate.

---

## Core Roles and Responsibilities

| Role | Primary Accountability |
|---|---|
| **Business Sponsor / Project Owner** | Owns funding, scope, business outcomes, risk acceptance, and final accountability for value realization. |
| **Product Owner** | Defines priorities and manages the backlog to maximize customer and business value. |
| **Business Analyst** | Translates business needs into clear requirements, acceptance criteria, process impacts, and data needs. |
| **Developer / Engineer** | Designs, builds, documents, and unit-tests solutions against approved requirements and architecture standards. |
| **Quality Assurance** | Validates functional, integration, performance, security, resiliency, and release readiness. |
| **Architect** | Defines current, target, and transition architectures, standards, integration patterns, nonfunctional requirements, and guardrails. |
| **Technical Lead** | Provides hands-on technical direction and maintains execution quality. |
| **Delivery Manager** | Manages people, capacity, schedules, dependencies, risks, escalation, and delivery commitments. |
| **Technology Executive** | Sets direction, secures resources, resolves enterprise tradeoffs, governs cost and risk, and ensures portfolio alignment. |

Roles may be combined in smaller teams, but accountability must remain explicit. Combining roles must not eliminate required checks and balances for security, quality, financial approval, production access, data use, or AI-generated changes.

---

## Illustrative RACI

**R** = Responsible · **A** = Accountable · **C** = Consulted · **I** = Informed

| Role | Incident | Enhancement | Major Program | Production Approval |
|---|:---:|:---:|:---:|:---:|
| Business User | C | C | C | C |
| Developer / Engineer | R | R | R | I |
| Business Analyst | C | R | R | C |
| Quality Assurance | C | C | R | C |
| Business Sponsor | I | A | A | A |
| Product Owner | I | C | R | C |
| Architect | C | C | R | C |
| Technical Lead | R | R | R | C |
| Delivery Manager | A | R | R | I |
| Technology Executive | I | I | C | I |

Each work type should have one clearly accountable owner.

---

## Production Change Approval

- **Standard, low-risk changes** may follow a preapproved path.
- **Normal changes** should receive review proportional to architecture, security, quality, data, financial, and business impact.
- **Emergency changes** may use an expedited path but must be reviewed afterward for risk, outcome, root cause, and control effectiveness.

---

## Outcomes

- Knowledge is distributed across teams instead of remaining with a few individuals.
- Employees gain broader technical experience and clearer career paths.
- Critical roles and services have succession coverage.
- Business and technology teams share accountability for outcomes.
- Architecture decisions have named owners and traceable rationale.

---

[← Back to Overview](../) | [Next: Process and Controls →](../02-process-and-controls/)
