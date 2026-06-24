# Example: AI-First Onboarding Strategy

## Product

AI-first customer success workspace for B2B SaaS teams.

## Onboarding thesis

New customer success managers should leave onboarding knowing that the AI can identify renewal risks across CRM, product usage, support tickets, and notes; that it drafts but does not send customer-facing work without approval; and that every recommendation can be inspected through sources, edited in a visual workbench, and rolled back before records are changed.

## First verified outcome

Produce a reviewed renewal-risk brief for one account, including evidence, recommended actions, editable customer email draft, and internal next-step tasks.

## First-run route

| Step | UI | AI behavior | Success signal |
|---|---|---|---|
| Choose role | Role/JTBD picker | Tailors examples to CSM | CSM route selected |
| Select first outcome | Outcome picker | Recommends “Find renewal risks” | Outcome selected |
| Connect/select context | Data scope walkthrough | Shows CRM, usage, support, notes; offers demo data if blocked | At least one source selected |
| Compose intent | Guided intent composer | Preloads selected account + “risk brief” output | Intent submitted |
| Preview plan | Plan preview card | Proposes sources, risk factors, artifact sections | User approves or edits plan |
| Generate artifact | Account workbench + artifact canvas | Produces risk brief and action plan | Artifact generated |
| Inspect evidence | Source drawer | Links each claim to records/tickets/usage | User opens evidence drawer |
| Review changes | Diff/review mode | Stages CRM note and task updates | User accepts selected changes |
| Repair | Teach-the-agent flow | User corrects tone or excluded source | Correction applied once/workflow/team |
| Replay | Agent replay | Shows request, sources, changes, approvals | Replay available |

## Capability calibration

| Capability | Good for | Needs review when | Not suitable for | Evidence |
|---|---|---|---|---|
| Risk analysis | Finding patterns across usage, tickets, notes | Large account, conflicting signals, stale data | Final renewal judgment without human review | Source drawer, freshness badge |
| Drafting | Renewal emails, meeting notes, exec summaries | Customer-facing tone or legal commitments | Sending without approval | Diff review, approval gate |
| Monitoring | Watching for negative trends | Custom thresholds or strategic accounts | Silent action on escalations | Exception inbox |
| Updating records | Staging notes/tasks | System-of-record updates | Autonomous account updates by default | Diff + audit log |

## Repair rehearsal

The guided task intentionally asks the user to modify the output: “Make this brief suitable for an executive review and exclude tickets older than 90 days.” The UI shows the constraint chip change, regenerated sections, source set update, and before/after diff. The user can save the correction as “this account only,” “all renewal risk briefs,” or “team rule.”

## Progressive mastery

| Stage | Unlock | Guardrail |
|---|---|---|
| First task | Guided risk brief | Draft only |
| After first review | Saved risk-brief template | Approval required |
| After three accepted briefs | Batch risk scan for portfolio | Partial accept + audit |
| Admin-approved | Weekly renewal monitor | Exception inbox, no customer sends |
| Mature team | Auto-stage low-risk tasks | Rollback + reviewer assignment |

## Team rollout

Admins configure which fields the AI may read, which CRM fields it may stage, who approves customer-facing drafts, and what account segments require manager review. The onboarding creates a visible Team AI Contract and stores it in governance settings.

## Metrics

- Time to first reviewed risk brief.
- Source inspection rate during first brief.
- First repair success rate.
- Percent of staged CRM changes partially accepted rather than blindly accepted.
- Second-session return after first brief.
- First manager/reviewer invite.
- Weekly monitor adoption after three successful manual reviews.
