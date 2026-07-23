# Process and Controls

Modernization requires a transparent workflow that moves routine work quickly while applying stronger controls to changes with greater business, architecture, security, data, or financial risk.

The objective is not to add more approvals. It is to apply the **right level of control based on risk**.

## Common Current-State Challenges

- Work enters through multiple channels without consistent information or ownership.
- Priorities may be determined by influence rather than measurable business impact.
- Estimates and milestones may be based on incomplete assumptions.
- Delivery dates may move without assessing customer, financial, regulatory, architecture, or operational impact.
- Business stakeholders may have limited visibility into status and decisions.
- Simple, low-risk changes may be delayed by unnecessary approval gates.
- High-risk changes may proceed without sufficient architecture, security, quality, or business review.

---

## Step 4 — Create One Transparent Intake and Classification Path

### Action

Route the following work through a common intake process:

- Incidents
- Enhancements
- Architecture requests
- Data and AI requests
- Major programs and projects

Each request should include the business outcome, impact, urgency, ownership, dependencies, data sensitivity, architecture impact, and expected value.

### Technical Outputs

- Standard intake form
- Work classification rules
- Routing logic
- Assigned ownership
- Visible enterprise backlog
- Decision and approval timestamps

### Expected Outcome

Less work is lost in email or informal channels, and business and technology teams see the same demand picture.

---

## Step 5 — Define Service Levels and Severity Using Business Impact

### Action

Set response and restoration expectations based on:

- Business criticality
- Customer impact
- Safety impact
- Financial exposure
- Regulatory impact
- Data sensitivity
- Availability of a workaround

### Technical Outputs

- Priority and severity definitions
- SLO and SLA targets
- Escalation rules
- Communication templates
- Operational dashboards

### Expected Outcome

The most damaging issues are addressed first, expectations are clear, and operational performance becomes measurable.

---

## Step 6 — Create Risk-Based Change and Delivery Paths

### Action

Separate changes into three paths:

- **Standard changes:** Repeatable, low-risk, tested, and preapproved.
- **Normal changes:** Require review proportional to business, architecture, security, data, quality, and financial impact.
- **Emergency changes:** Use an expedited path to restore service but require a post-implementation review.

### Technical Outputs

- Change-classification decision tree
- Approval matrix
- Automated quality and security checks
- Release evidence requirements
- Rollback requirements
- Post-implementation review process

### Expected Outcome

Low-risk work moves faster while high-risk work receives appropriate control.

---

## Step 7 — Govern the Investment Portfolio and Measure Outcomes

### Action

Review technology demand as one enterprise portfolio rather than as unrelated requests.

- Apply common decision criteria.
- Compare investments side by side.
- Sequence work based on value, risk, dependencies, capacity, and readiness.
- Refresh portfolio decisions quarterly.
- Track reliability, delivery, quality, financial, risk, and workforce measures.

### Technical Outputs

- Annual technology portfolio
- Quarterly portfolio rebalancing
- Capacity and resource plan
- Multiyear funding view
- Benefit-realization measures
- Executive performance dashboard

### Expected Outcome

Investment moves toward the highest-value work with transparent tradeoffs and measurable results.

---

## Risk-Based Work Intake and Delivery Flow

```mermaid
flowchart LR
    A["1. Request<br/>Business outcome, impact, urgency, owner"]
    B["2. Triage<br/>Validate and classify the work"]
    C["3. Route<br/>Incident, enhancement, architecture, data/AI, or program"]
    D["4. Deliver<br/>Design, build, test, and validate"]
    E["5. Release<br/>Risk-based approval and deployment"]
    F["6. Measure<br/>Outcome, quality, cost, and learning"]

    A --> B --> C --> D --> E --> F
