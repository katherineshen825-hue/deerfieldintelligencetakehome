## Operational Gap Assessment

**Executive summary**

- Deerfield Intelligence builds and deploys AI systems for Deerfield’s portfolio companies and seeks to expand from a 10 person team to a 30 person team in 18 months. The team has been lucky thus far in avoiding data and compliance violations; however, there is a lack of documentation of institutional knowledge, cross functional communication, and scalable business processes, leading to friction between teams and slow onboarding of new hires.
- The Director of Operations needs to move fast and build processes and tools to provide visibility and communication across multiple functions as well as the investment partners; this will allow the rest of the team to get out of fire fighting mode.

**Gap 1: Regulatory and legal exposure**

**Priority:** Critical; requires immediate action

- The team is building and deploying AI systems that directly inform investment decisions with no compliance infrastructure in place.
- There are 3 areas of legal exposure:
    1. **MNPI risk:** Live research dashboards aggregating physician sentiment and clinical data are accessible to investment analysts before outputs are cleared through compliance. This has been confirmed by Sarah Kim where systems have had to be stripped out after a build has already taken place. 
    2. **Lack of audit trail:** For a given deployed model, there is no versioning, no model cards, and no data lineage documentation. Both Sarah Kim and David Chen confirmed that they would not be able to pass if the SEC requested an audit trail on how a specific model influenced an investment decision based on emails and a high-level summary, putting the firm at great risk. 
    3. **Sensitive data shared with third party AI:** Clinical trial records, physician behavioral data, and proprietary investment signals  are being shared with third-party AI APIs (e.g., OpenAI, Anthropic) under a gentleman's agreement rather than a documented policy. This has been confirmed by David Chen and Sarah Kim caught it once however there are likely many instances that are flying under the radar. 
- By closing this gap, we will significantly derisk Deerfield from any SEC examination, data breach, and MNPI issue which could put the portfolio companies and the greater company in jeopardy.

**Gap 2: Lack of operational layer between pods, support functions, and CIO**

**Priority:** Critical; address within 30 days

- David Chen is spending 50-60% of his time focused on operations because there is no operational layer between the pod leads and the CIO. Everything that should be handled by systems, processes, or a dedicated Director of Operations is landing on David Chen by default.
- Priya Sharma spends 30% of her time on operational overhead. Her most senior engineer, who was hired for deep technical work on predictive models, is regularly pulled off that work to chase vendor approvals and document processes.
- Marcus Thompson has no system for managing portfolio company commitments and no capacity visibility into Priya's pod. Both leads described their prioritization process as reactive, relationship-driven, and broken.
- Elena, James, and Sarah have all described interfacing with David when an operational issue is already on fire due to lack of visibility into what is coming at them.
- By installing a Director of Operations, David will stop fighting fires and will be strategically reallocating his time as CIO again, providing the greatest leverage to the team.

This gap is the root cause of nearly every other item on this list. Remove it and the other problems become solvable. Leave it and every fix routes back through David and stalls. Freeing a CIO from 50-60% operational overhead at a $15 billion fund is not an efficiency win — it is a strategic reallocation of the organization's highest-leverage resource.

**Gap 3: Lack of demand management or intake process**

**Priority:** High; address within first 30 days

- Work enters Priya and Marcus’s pods through informal, relationship-driven channels with no intake process, no capacity check, and no prioritization mechanism. These requests come out of hallway conversations, urgent Slack messages, and pressure from investment partners.
- Portfolio companies are treating Deerfield Intelligence as a free resource with no scope of work and SLAs.
- For example, scope creep turned a six-week project into 14 weeks due to not defining the desired end state and lack of framework to push back on scope. Marcus committed a feature to a portfolio company that depended on a pipeline Priya hadn't started. Unfortunately, Priya found out a week before the deadline. Investment partners are bypassing Priya and Marcus by going directly to portfolio company executives, generating a "shadow roadmap" (coined by David) that creates unmanageable commitments and burns out the team.
- Priya and Marcus also don’t have real-time visibility into the other's capacity. They are reacting to various commitments with tight deadlines so the team absorbs the consequences.
- This gap is highly visible to portfolio companies with damage to Deerfield Intelligence’s reputation, output quality, and timeline reliability. These issues would further compound as Deerfield scales from 10 to 30 people.

**Gap 4: Lack of financial planning and visibility into vendor spend** 

**Priority:** High; address within 30 days

- The team lacks real-time financial visibility into vendor spend coupled with no documented spending authority and no procurement process.
    - The team went 40% over on cloud spend last quarter where James Okonkwo found out at month close.
    - The team was paying for 3 redundant data visualization tools, each purchased independently by different people.
    - An active vendor contract was found signed by someone who left two years ago.
- Pod leads don’t know what their budgets are, resulting in James reverse-engineering credit card statements to understand what spend the team has committed to
- There is also no approved vendor list or documentation of spending authority, for a $50 SaaS subscription and a $100,000 data contract. Procurement reviews only begin after engineers think they're ready to use a tool, leading to delays.
- Resolving this gap would allow James to focus on financial planning instead of digging and David would be freed from difficult budget conversations
- The quickest win stems from this gap which is a vendor audit that can be done in week one and then deliver immediate value across Finance, both pod leads, and the CIO simultaneously.

**Gap 5: Current hiring and onboarding processes cannot support growth plans**

**Priority:** High; address within 60 days

- The current plan to grow from 10 people to 30 requires a deep dive into role architecture, seniority breakdown, and a month-by-month timeline with dedicated recruiting and budget. This was confirmed by Elena Rodriguez.
- With a 4-month lead time per hire, Wave 1 requisitions need to open immediately. The role architecture Elena needs to build the pipeline lives entirely in David's head. The team already lost a top ML engineer to Google because the process took four months with no clear timeline.
- Currently, the team lacks career growth infrastructure (e.g., leveling frameworks, compensation bands, performance review process, career paths) for existing team members, leading to  potential lawsuits
- The onboarding process is fully manual where a recent hire couldn't access code repositories for weeks due to the lack of technical setup.
- Both pod leads described the onboarding process as entirely oral because all of the information lives in their minds. There is no documentation of an onboarding process for new hires.
    - For example, Priya's last hire took three weeks to reach productivity because she walked him through everything verbally. Her most senior engineer is regularly pulled off deep technical work to answer operational questions because no written resource exists. Marcus described onboarding as "shadow me and hope you catch on."
- If Priya or Marcus left tomorrow, the team would lose most of its institutional knowledge, creating a single point of failure risk.
- This gap will become more prevalent as hiring really ramps up and multiple people are onboarding at once; lack of career infrastructure creates retention risk that compounds with every hire.
