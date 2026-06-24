# Example: AI-Native SaaS Review Structure

## Product assumption

A B2B customer-success platform wants to become AI-first. Today it has account dashboards, health scores, notes, tasks, emails, and QBR reporting.

## Executive judgment

The product should not replace the account dashboard with chat. The AI-first opportunity is to turn scattered customer data into a proactive account operating system: monitor accounts, explain risk, draft actions, prepare QBRs, and stage customer communications for approval.

## AI-first thesis

The AI can continuously synthesize CRM, product usage, support tickets, call notes, contracts, and email sentiment into account-level recommendations. Visual UI remains essential for account comparison, health trend inspection, stakeholder maps, renewal timelines, and approval of customer-facing actions.

## Human-AI responsibility map

| Task | Human owns | AI owns | Autonomy | Approval |
|---|---|---|---|---|
| Identify renewal risk | Judgment and prioritization | Pattern detection and evidence gathering | Suggest | No approval needed |
| Draft save plan | Account strategy | Draft plan and tasks | Draft | Human edits |
| Email customer | Relationship tone and commitment | Draft email | Prepare | Explicit send approval |
| Update CRM fields | Final data correctness | Stage updates from evidence | Prepare | Diff review required |
| Monitor usage drop | Escalation threshold | Background monitoring | Monitor | Notify only on exception |

## Recommended interface architecture

1. Command center with account risk queue and agent activity rail.
2. Account workbench with health timeline, evidence drawer, stakeholder map, open tasks, and AI recommendations.
3. Intent composer scoped to selected accounts.
4. Plan preview for multi-account actions.
5. QBR artifact canvas where AI-generated slides are editable.
6. Approval queue for emails, CRM updates, and playbook actions.
7. Memory inspector for account strategy preferences and team playbook rules.



## Onboarding and activation recommendation

The first-run experience should not start with a generic chatbot. It should ask the CSM to choose a concrete outcome such as “Find renewal risks for my book of business.” The system should then connect or simulate the minimum context: CRM accounts, support tickets, product usage, call notes, and renewal dates.

First verified outcome:
1. User selects five accounts or uses sample accounts.
2. AI shows a plan for risk analysis.
3. User removes any irrelevant sources or segments.
4. AI creates an account-risk table and save-plan board.
5. User opens the evidence drawer for one risk claim.
6. User edits or rejects one recommendation.
7. System shows replay, undo, and what the agent learned.
8. Product suggests a safe next delegation: weekly monitoring that only creates exceptions for review.

Team onboarding should add shared playbook instructions, approval rules for customer emails, CRM-update diff review, and audit visibility for managers.

## Priority recommendations

1. Replace generic AI chat with an object-scoped intent composer.
2. Add source drawers to every risk recommendation.
3. Turn generated plans into editable task boards, not chat messages.
4. Add diff review before CRM updates.
5. Add exception inbox for background monitoring.


## Onboarding review

A strong AI-native review should check whether the product teaches users how to delegate and verify AI work. Look for:

- a guided first mission using real or realistic data;
- a capability contract that states what the AI can do, cannot do, and must ask approval for;
- explicit read/write permission setup;
- plan preview education before execution;
- evidence, source, and diff review during the first task;
- at least one repair or teach-the-agent moment;
- memory controls that show what is personal, team-level, or admin-enforced;
- progressive autonomy that unlocks only after reviewed successful outcomes.

A product that only shows a welcome modal and a blank prompt should score low on onboarding, even if its underlying model is powerful.
