## 90 Day Operational Plan

**Objective:** Build the operational foundation to de-risk the firm, free the CIO to lead, and scale the team from 10 to 30 people without losing speed or culture.

**Days 1 to 30**

Eliminate the highest-severity risks, establish credibility with every stakeholder, and put three quick wins on the board to build trust and credibility with internal stakeholders before the end of the first month.

**Quick Win 1: Vendor Audit and Registry**

- **Goal:** Create a single source of truth system where James and David has visibility into vendor commitments and future spend, eliminating financial archaeology
- **Action plan:**
    - Pull every credit card statement and bank export from James to identify all active vendor spend
    - Locate all contracts across David's shared folder, pod lead email inboxes, and James's files
    - Build a centralized vendor registry covering every contract, monthly cost, renewal date, and internal owner
    - Flag redundant tools, orphaned contracts, and upcoming renewals
    - Establish a 30-day advance renewal alert so no contract auto-renews without a deliberate decision
- **Deliverable:** Centralized vendor registry delivered to James and David by end of week two
- **Metrics for success:**
    - Number of redundant tools identified and eliminated
    - Dollar value of spend consolidated or cancelled
    - Zero unplanned auto-renewals hitting David's desk after day 30

**Quick Win 2: Intent to Spend Process**

- **Goal:** Create a paper trail (on Slack) for James before spend actually occurs without adding frictions that may slow down the engineering team
- Action plan:
    - Launch a lightweight "Intent to Spend" Slack channel
    - Develop a SOP where any new tool, trial, or vendor commitment requires a single post in Slack including: tool name, cost, David's approval, and a PDF of terms
    - Document spending authority thresholds by role and distribute to pod leads and James
    - Create 24 -hour turnaround on standard approvals from James
- **Deliverable:** Intent to Spend channel live and spending authority thresholds documented by end of week one
- **Metrics:**
    - 100% of new vendor commitments captured before invoice hits James's desk
    - James receives context with every new commitment rather than hunting for it
    - Time from vendor request to approval reduced from two-plus weeks to 24 to 48 hours

**Quick Win 3: CIO Weekly Briefing**

- **Goal:** Give David operational visibility via a weekly structured touchpoint so David no longer serves as an escalation path for pod leads and support functions
- **Action plan:**
    - Establish a standing Monday morning briefing with David: 30 minutes maximum
        - Cover vendor spend snapshot, open compliance items, cross-pod capacity, and immediate items requiring his input
    - Only share strategic or catastrophic issues with David
- **Deliverable:** Standing Monday briefing running by end of week one*
- **Metrics:**
    - Reduction of David's operational overhead from 50-60% of his week toward a target of under 20% by day 90
    - David consistently receives the ops report in under 30 minutes on Mondays
    - Frequency of reactive fire calls between David and support partners drops measurably by day 60

**Regulatory Triage 1: MNPI Assessment**

- **Goal:** Eliminate MNPI risk as the firm’s most immediate risk
- **Action plan:**
    - Convene Sarah Kim and Priya Sharma in week one to audit which live dashboards are accessible to investment analysts before compliance clearance
    - Implement hard access controls on any dashboard flagged as MNPI-risk pending a permanent solution
- **Deliverable:** MNPI audit complete and access controls implemented by end of week one
- **Metrics:**
    - Zero live dashboards with uncleared MNPI exposure by day 30
    - Sarah has documented visibility into every analyst-facing output
    - David can confirm to firm leadership that the MNPI exposure has been addressed

**Regulatory Triage 2: Data Flow Mapping**

- **Goal:** Map data flow end to end to understand what data may be exposed to third party AI and then build guardrails
- **Action plan:**
    - Convene David and Priya in week one to map exactly what data is going where: which datasets are being sent to which third-party APIs and under what assumptions
    - Identify every instance where clinical data, physician behavioral data, or proprietary investment signals are being shared with third parties
- **Deliverable:** Complete data flow map by end of week two
- **Metrics:**
    - Every active third-party API integration identified and documented
    - Priya and David have a shared written understanding of current data exposure for the first time
    - Map serves as the evidentiary foundation for Legal review

**Regulatory Triage 3: Data Tiering Policy**

- **Goal:** Create Legal-reviewed policy that tells every engineer exactly what data can go where before they write a line of code
- **Action plan:**
    - Work with Sarah and Legal to produce a first draft of a Data Tiering Policy by end of week two
        - Policy defines three tiers: data that can flow freely to any API, data requiring a pre-approved API list only, and data that cannot be shared with a third party
    - Submit to Legal for review with a target working policy in place by day 30
- **Deliverable:** Draft Data Tiering Policy submitted to Legal by end of week two; ratified policy in place by day 30
- **Metrics:**
    - Zero instances of ungoverned sensitive data sent to third-party APIs after day 30

**Support Partner Alignment**

- **Goal:** Establish the ops layer as the primary interface for HR, Finance, and Compliance to protect David’s time
- **Action plan:**
    - Schedule individual 30-minute kickoffs with Elena, James, and Sarah in week one
    - Establish yourself as their primary interface per David's mandate: you own the day-to-day, David sees only what is strategic or catastrophic
    - Agree on standing syncs with each partner: weekly cadence for the first 30 days, biweekly after rhythms are established
- **Deliverable:** Standing syncs established with all three support partners by end of week one
- **Metrics:**
    - Reactive fire calls to David from support partners drop by at least 50% by day 60
    - Each partner describes the relationship as proactive rather than reactive at the 90-day mark

**Days 31 to 60**

Build the core operational infrastructure: demand management, onboarding, hiring architecture, and the compliance framework in order for the team to sustainable scale from 10 to 30 people. 

**Demand Management: Cross-Pod Intake Process**

- **Goal:** Create a lightweight system that captures every request, surfaces cross-pod dependencies, and gives both pod leads a shared view of what the team has committed to
- **Action plan:**
    - Design and launch a lightweight project intake process covering both pods
    - Any new request from a portfolio company or investment partner goes through intake before a commitment is made: requester, business need, estimated scope, cross-pod dependencies, and timeline
    - Process takes under 10 minutes to complete and under 24 hours to triage
    - Marcus and Priya get a shared view of everything in the pipeline
- **Deliverable:** Intake process live and adopted by both pods by day 45
- **Metrics:**
    - 100% of new external requests entering through intake rather than hallway conversations or Slack pings
    - Cross-pod dependency conflicts identified before commitments are made rather than after
    - Marcus can show a portfolio company exactly where their request sits in the queue
    - Scope creep incidents tracked and reduced by 50% versus the prior quarter

**Demand Management: Cross-Pod Capacity Dashboard**

- **Goal:** Create two way real-time visibility into Marcus’s and Priya's pod capacity to improve planning
- **Action plan:**
    - Build a simple shared dashboard showing each pod's committed versus available capacity for the current and next two weeks
        - Marcus sees at a glance whether Priya's team is at 80% or 110% before making any commitment
        - David sees a real-time capacity snapshot in his Monday briefing
- **Deliverable:** Capacity dashboard live and visible to Priya, Marcus, and David by day 45
- **Metrics:**
    - Zero instances of Marcus committing Priya's team without a capacity check after day 45

**Demand Management: Portfolio Company Engagement Model**

- **Goal:** Give Marcus a documented framework for managing external demand so he can say no with authority instead of absorbing scope creep or escalating to David
- **Action plan:**
    - Design a formal engagement model for portfolio company requests: defined scope of work template, SLA tiers, and an intake form Marcus uses for every new request
    - Establish rules of engagement that Marcus can point to when saying no or not yet to a portfolio company
    - Prepare David for the investment partner conversation at end of month one: present the intake flow and capacity dashboard as evidence that the process works before asking partners to use it
- **Deliverable:** Engagement model and scope of work template delivered to Marcus by day 50; investment partner presentation ready for David by day 30
- **Metrics:**
    - 100% of new portfolio company engagement begins with a signed scope of work
    - Portfolio company escalations to investment partners decrease measurably after the partner conversation

**Onboarding Process**

- **Goal:** Get every new hire to full productivity in five days instead of three weeks by replacing the current oral tradition with a repeatable documented onboarding system
- **Action plan:**
    - Build a standardized onboarding process covering two tracks: HR and corporate setup owned by Elena, technical setup owned by ops
        - Technical track includes a pre-built access checklist covering every repo, tool, Slack channel, and dev environment a new hire needs on day one
    - Build a pod-specific ReadMe for each pod: how we deploy, how we handle data, how we engage with portfolio companies, and who to call when things break
    - Establish a buddy system pairing every new hire with a senior team member for their first 30 days
- **Deliverable:** DI Bootcamp documentation and access checklist complete by day 60; first full run with a new hire completed by day 90
- **Metrics:**
    - New hire time to first code commit reduced from three weeks to five days
    - Zero new hires sitting without system access past day one

**Hiring Architecture and Roadmap**

- **Goal:** Translate David's 30-person vision into an executable month-by-month hiring plan so Elena can start building the pipeline immediately
- **Action plan:**
    - Convene David, Priya, and Marcus for a two-hour session in week one to translate the 30-person vision into a role architecture: specific titles, seniority levels, and sequencing
    - Build a month-by-month hiring roadmap with 4-month lead times baked in: if a role needs to start in month five, the req opens in month one
    - Deliver the roadmap to Elena in a format she can execute against immediately
    - Build the business case for a contract technical recruiter or specialized agency partnership for Wave 1 technical roles
- **Deliverable:** Hiring roadmap delivered to Elena by end of week one; business case for dedicated recruiter delivered to David by day 30
- **Metrics:**
    - Wave 1 requisitions open on schedule per the roadmap
    - Business case approved and contract recruiter engaged by day 45
    - Time to close a technical hire reduced from four months toward a target of eight weeks by day 90

**Minimum Viable Audit Trail**

- **Goal:** Build the minimum documentation infrastructure required to make Deerfield Intelligence's AI models defensible to a regulator, starting with what is already in production
- **Action plan:**
    - With Sarah and Priya, design the minimum viable audit trail for deployed models: what gets logged, where it lives, and how it is accessed
    - Implement version control for all active models and prompts
    - Build a model inventory: every model in production, what it does, who owns it, what data it ingests, and which version is live
    - Bake audit logging into the next sprint so new deployments are compliant from the start
- **Deliverable:** Model inventory complete and version control implemented for all active models by day 60
- **Metrics:**
    - 100% of deployed models have a documented owner, version history, and data lineage
    - 100% of new model deployments include audit logging as a standard requirement

**Minimum Viable Performance Framework**

- **Goal:** Put the minimum legal and cultural infrastructure in place for performance management before the team hits 20 people so the firm can act on underperformance
- **Action plan:**
    - With Elena, design a lightweight performance framework with three components: quarterly check-ins with a simple recorded format, role-specific competencies with three to five bullet points per level, and a three-goal quarterly goal-setting process
    - Own the schedule: ensure David and the pod leads complete reviews
    - Elena provides templates and legal guardrails; ops drives execution and scheduling
- **Deliverable:** Performance framework designed and first quarterly check-ins scheduled by day 60
- **Metrics:**
    - 100% of team members have documented goals and a Q1 check-in on record before the team hits 20 people
    - 100% of team member have performance paper trail (shared with Elena)
    - Zero informal performance conversations replacing documented reviews after day 60

**Days 61 to 90**

Shift from reactive fixes to a proactive operational systems where every system built in days one to 60 gets pressure-tested, refined, and handed off to the people who will own it long-term.

**Compliance Infrastructure**

- **Goal:** Make compliance a feature of how the team builds so Sarah never receives a finished product she has to hold up at the finish line
- **Action plan:**
    - Design and implement a mandatory compliance intake process for every new project, dashboard, or model before any code is written
        - Use Sarah's five-field spec: data source and provenance, PII and PHI check, intended use case, external API dependencies, and access list
    - Integrate the intake form into the existing workflow so it is completed at project kickoff not at deployment
    - Every deployed output gets a compliance sign-off logged before going live
- **Deliverable:** Compliance intake process live and adopted across both pods by day 75
- **Metrics:**
    - 100% of new projects have a completed compliance intake form before code is written
    - Sarah's review time reduced from weeks to days because she receives complete documentation upfront
    - Zero products reaching deployment without a documented compliance sign-off

**Knowledge Infrastructure: Pod ReadMe and Documentation Sprint**

- **Goal:** Eliminate the single point of failure risk by capturing the institutional knowledge currently living in Priya and Marcus's heads into written documentation that any team member can access
- **Action plan:**
    - Run a structured documentation sprint with each pod: two focused sessions to capture codebase architecture, deployment processes, data handling norms, and key contacts
    - Publish a ReadMe for each pod covering everything a new hire needs to know to be productive without pulling Priya or Marcus off deep work
    - Establish a lightweight documentation norm: every new process gets a one-page written record before it is considered complete
- **Deliverable:** Pod ReadMe published for both pods by day 90
- **Metrics:**
    - Documentation sprint completed without requiring more than four hours of either pod lead's time

**Operational Processes: Consistent Channels of Communication**

- **Goal:** Replace ad hoc fire calls with a predictable operating cadence that keeps every stakeholder informed, aligned, and unblocked without requiring David to be in the room
- **Action plan:**
    - Biweekly Cross-Pod Sync: Priya and Marcus review shared capacity, flag upcoming dependencies, and surface anything needing ops support
    - Monthly Pre-Close Sync with James: ops reviews AWS spend, new tools in trial, and upcoming contract renewals before month close so James can defend DI's spend to firm partners
    - Quarterly Performance Check-Ins: performed with all employees, owned by ops, templates from Elena
    - Monthly Compliance Review with Sarah: review any new data sources, model deployments, or API integrations from the prior month against the Data Tiering Policy and compliance intake log
- **Deliverable:** All meeting cadences are occurring on a consistent basis by day 90

**Investment Partner Engagement**

- **Goal:** Reset how senior investment partners engage with DI so the team is no longer reactive to a shadow roadmap problem
- **Action plan:**
    - Prepare David for the investment partner conversation at end of month one: present the intake flow, capacity dashboard, and portfolio company engagement model as a functioning system
    - Support David’s narrative in presenting the new engagement model to senior investment leadership: we are scaling to 30 people to support you, but if you bypass the system you are deprioritizing your own fund's returns
    - Design a concierge intake experience for investment partner requests so the process feels like prioritization support rather than a bureaucratic gate
- **Deliverable:** Investment partner presentation ready for David by day 30; partner conversation completed by day 45
- **Metrics:**
    - 100% of investment partner requests entering through formal intake
    - Zero investment partner requests coming from direct calls to pod leads
