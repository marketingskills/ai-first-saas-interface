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

## Priority recommendations

1. Replace generic AI chat with an object-scoped intent composer.
2. Add source drawers to every risk recommendation.
3. Turn generated plans into editable task boards, not chat messages.
4. Add diff review before CRM updates.
5. Add exception inbox for background monitoring.
