# TechnPortfolio 360

**Independent enterprise technology portfolio, project delivery and governance demonstration.**

TechnPortfolio 360 models the practical work of a Senior IT Project Manager working with portfolio leadership, solution architects, development and QA teams, DevOps, security, data teams, and external/offshore delivery partners. It is not a representation of any employer's or customer's actual operations.

## What to explore

- **Command Center:** portfolio health, exceptions, next decisions, and accountable work queues.
- **Strategic Portfolio:** initiatives, sponsor, investment, execution phase and release gates.
- **Project Execution:** milestone updates, ownership, dependencies and evidence notes.
- **RAID & Decisions:** risks, issues, dependencies, follow-up actions and approvals.
- **Architecture Compliance:** standard review with named architectural sign-off.
- **Partner Performance:** production defect trends, SLA, vendor scorecards and corrective actions.
- **DevOps & QA:** automation adoption, pipeline progress and test evidence.
- **AI & Data Governance:** AI review controls and Microsoft Fabric semantic layer standards.
- **Executive Governance:** steering agendas, meeting outcomes that create assigned actions, explicit decisions and audit trail.
- **Scenario Lab:** guided end-to-end blocker-to-release simulation.
- **Demo Guide & QA:** walkthrough, scope/limitations, manual acceptance checks.

## Five-minute walkthrough

1. Start in **Command Center** as **Senior IT Project Manager** to see cross-team delivery exposure.
2. Open **Scenario Lab**, review the four pending evidence gates, and switch to the **Solution Architect** role.
3. Go to **Architecture Compliance** and accept compliance evidence. This also closes the linked issue and improves the affected vendor scorecard.
4. Switch to **QA / DevOps Lead** in **DevOps & QA** and record passing regression evidence. Automation coverage and release gates update together.
5. Switch to **Security & AI Governance Lead** in **Scenario Lab** and record security sign-off.
6. Switch to **Portfolio Director** in **Executive Governance** and approve the remediation decision. The first project's release readiness becomes **Ready**.
7. Return to **Strategic Portfolio**, open the initiative, inspect its controls, and review the audit history under **Executive Governance**.

## Industry examples

Choose Technology, Retail, Insurance, Banking, Healthcare or Manufacturing in the header. Each has its own portfolio scenario, projects, records, changes and approvals. Selecting an industry does not clear another industry's demo state.

## Role and data behavior

Roles are illustrative. The interface restricts specialist controls and decisions to the specified accountable role. This is **not** real authentication, authorization, or enterprise IAM.

This is a **front-end-only simulation**. Information is seeded and fictional, and updates persist only in the current browser's `localStorage`. No server, paid provider, external partner feeds, identity provider, AI model, Microsoft Fabric platform or email integration is connected. The Mira assistant is a rules-based, page-aware explainer rather than an LLM.

You can create an initiative, register risks/dependencies, assign work, update milestones, complete role-owned actions and record decisions. These changes affect relevant portfolio and project views, while the recorded audit trail shows what changed.

## Local preview

Clone or download the repository, then serve the folder with any static web server. For example:

```bash
python3 -m http.server 8000
```

Then open http://localhost:8000 . The published app is a self-contained `index.html`; there is no build step, package installation, or backend required. It is compatible with static hosting such as GitHub Pages or Render static sites.

## Demonstration boundaries

- Financial and KPI values are synthetic and illustrative.
- Workflow approvals and evidence updates are simulated; real document validation and identity checks are not implemented.
- Project schedules are simplified demonstration plans, not production-grade scheduling or critical-path calculations.
- The browser data store is not a multi-user database. There is no simultaneous collaboration or actual audit immutability.
- This demo illustrates delivery-management concepts, not actual implementation of vendor compliance enforcement, production DevOps integrations or Microsoft Fabric governance APIs.
## GitHub Pages

For the live demo, open **Settings → Pages** in this GitHub repository, choose **Deploy from a branch**, select **main** and **/(root)**, and save. The site address will be `https://sachintechpro.github.io/technportfolio360/` after GitHub completes the deployment.
