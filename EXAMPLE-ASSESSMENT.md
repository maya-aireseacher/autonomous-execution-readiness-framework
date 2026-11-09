# Example Assessment: Mid-Stage Manufacturing Company

This example illustrates how a hypothetical organization might use the framework.

## Organization Context

- **Industry:** Discrete manufacturing (industrial equipment)
- **Size:** 8,000 employees, $2.1B revenue
- **Current AI maturity:** Workflow automation in supply chain and customer service
- **Assessment date:** October 2026
- **Assessment team:** CTO, VP Supply Chain, Chief Risk Officer, General Counsel, VP Customer Operations

## Scoring Results

### Decision Boundary Definition: 2.5 / 4.0

- Clarity of delegation rules: **2** — Boundaries defined for supply chain reordering pilot
- Granularity of decision taxonomy: **3** — Detailed taxonomy for inventory and logistics decisions
- Exception handling protocols: **2** — Defined escalation for known exceptions in pilot
- Stakeholder alignment: **3** — Business unit sign-off on supply chain boundaries

**Evidence:** Supply chain pilot has clear boundaries (reorder quantities up to $50K, lead times under 90 days). Customer service boundaries still informal.

**Gap to next level:** Extend boundary framework to customer service and establish enterprise-wide governance.

### Accountability Architecture: 1.75 / 4.0

- Assignment of responsibility: **2** — Responsibility matrix exists for supply chain pilot
- Outcome ownership: **2** — VP Supply Chain owns pilot outcomes
- Liability and insurance coverage: **1** — Risk assessment completed, insurance not yet updated
- Audit trail requirements: **2** — Decision rationale captured for review

**Evidence:** Clear ownership for pilot, but no enterprise accountability model. Insurance policies do not explicitly cover AI agent decisions.

**Gap to next level:** Update insurance coverage, define accountability for customer service agents, establish legal review of enterprise model.

### Intervention Capability: 2.25 / 4.0

- Real-time observability: **3** — Real-time monitoring with alerting for supply chain
- Override mechanisms: **2** — Can override specific supply chain decisions manually
- Response time requirements: **2** — SLA defined (4-hour response for supply chain anomalies)
- Escalation procedures: **2** — Defined escalation chain with on-call engineer

**Evidence:** Strong observability for supply chain pilot. Override is manual and requires supply chain analyst intervention. No capability to roll back customer service agent actions.

**Gap to next level:** Automate override triggers for high-risk decisions, reduce response time to under 1 hour, build rollback capability.

### Measurement Infrastructure: 2.0 / 4.0

- Outcome instrumentation: **2** — Automated tracking for inventory KPIs (stockout rate, carrying cost)
- Strategic alignment validation: **2** — Quarterly review of supply chain performance
- Causal attribution: **2** — Comparing pre-agent and post-agent metrics, no controlled testing
- Reporting and transparency: **2** — Regular reporting to VP Supply Chain, ad hoc to CFO

**Evidence:** Good tracking of operational KPIs. Cannot definitively attribute margin improvement to agents versus other supply chain initiatives launched concurrently.

**Gap to next level:** Implement statistical attribution methods, establish executive dashboard, increase review frequency to monthly.

### Regulatory Preparedness: 1.5 / 4.0

- Transparency obligations: **2** — Gap analysis completed for EU AI Act (company has EU operations)
- Explainability requirements: **1** — Post-hoc manual explanation possible for supply chain decisions
- High-risk system classification: **2** — Supply chain pilot classified as limited-risk, customer service not yet evaluated
- Documentation and record-keeping: **1** — Basic technical documentation, not to regulatory standard

**Evidence:** Legal team has reviewed transparency requirements. Explainability is weak—agent decisions are logged but rationale is not human-readable. Documentation is developer-focused, not compliance-focused.

**Gap to next level:** Build explainability capability meeting EU standards, complete high-risk classification for all agent use cases, establish documentation standards.

## Overall Score: 10.0 / 20.0

**Interpretation:** Stage 2 (Workflow Coordination) with uneven capability distribution.

## Key Findings

1. **Constraint:** Regulatory preparedness is the lowest-scoring dimension and blocks progression to Stage 3. The EU AI Act's transparency rules applied in August 2026; the organization is not yet compliant for its European operations.

2. **Strength:** Intervention capability is relatively mature for the supply chain pilot, providing confidence in the ability to halt problematic agent behavior.

3. **Risk:** Accountability architecture is underdeveloped relative to the organization's ambition to expand agents into customer service. Insurance coverage gap creates unmitigated financial risk.

4. **Misalignment:** Customer service leaders want to deploy agents for case resolution, but no decision boundaries or accountability framework exist for that function.

## Recommended Priorities

1. **Immediate (next 30 days):** Update insurance policies to cover AI agent decisions, at minimum for supply chain pilot.

2. **Short-term (next 90 days):** Build explainability capability for supply chain agents to meet EU AI Act requirements. Establish documentation standards and apply to existing pilot.

3. **Medium-term (next 6 months):** Extend decision boundary framework and accountability architecture to customer service. Complete high-risk classification for customer service use cases.

4. **Long-term (12 months):** Implement statistical attribution methods and establish executive dashboard. Build automated rollback capability across supply chain and customer service systems.

## What This Assessment Revealed

The cross-functional discussion surfaced a significant gap between the CTO's perception of readiness ("we're ready to scale") and the General Counsel's assessment ("we have material compliance risk"). The scoring process forced the team to define specific capabilities required before expanding agent authority.

The organization decided to pause customer service agent deployment until regulatory preparedness reaches a score of 3.0 across all criteria.