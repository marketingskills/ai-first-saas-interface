# AI-First SaaS Onboarding Playbook

Use this template to design onboarding for an AI-first SaaS product, workflow, or agentic feature. The goal is not tour completion. The goal is first verified outcome, calibrated trust, and safe next delegation.

## 1. Onboarding thesis

**Product / workflow:**

**Primary user role:**

**Workspace maturity:** new user / experienced user / team rollout / admin setup / migration from conventional SaaS

**Core onboarding promise:**

> By the end of onboarding, the user can use AI to accomplish: ________, verify it by: ________, and safely delegate next: ________.

## 2. First verified outcome

Define the smallest meaningful result the user can create, inspect, and trust.

| Candidate first outcome | User value | Required context | Risk | Verification method | Time-to-value |
|---|---:|---|---|---|---:|
| | | | Low / Med / High | Source / diff / preview / simulation / reviewer | |

Select one primary first outcome:

**Chosen first verified outcome:**

**Why this outcome proves value:**

**What makes it safe for a first run:**

## 3. User and role segmentation

| Segment | Needs to learn | Should not be burdened with | Best first outcome | Onboarding track |
|---|---|---|---|---|
| Individual contributor | | Admin controls | | Individual |
| Manager / reviewer | | Deep setup | | Team |
| Admin / owner | | Feature tour | | Admin/governance |
| Expert user | | Basic tutorials | | Accelerated |
| Skeptical / regulated user | | Hype | | Trust-first |

## 4. Minimum viable context

Ask only for the context needed for the selected first outcome.

| Context item | Why it is needed | Required now? | User-facing benefit | Privacy / permission note | Fallback |
|---|---|---:|---|---|---|
| Role / goal | | Yes / No | | | |
| Data source | | Yes / No | | | Sample data / upload / manual input |
| Preferences | | Yes / No | | | Default |
| Team policy | | Yes / No | | | Draft-only mode |
| Memory permission | | Yes / No | | | Session-only |

## 5. Capability contract

Show this before broad permissions, automation, or first consequential use.

### The AI can

- 

### The AI is not reliable for

- 

### The AI can see

- 

### The AI can change

- Nothing yet / draft only / staged changes / bounded approved actions / autonomous low-risk actions

### The AI needs approval before

- 

### The AI remembers

- Session-only / personal memory / team instructions / object-level corrections / no memory

### The user can control

- Inspect sources
- Edit or reject output
- Undo or rollback
- Limit data scope
- Change memory
- Turn off automation

## 6. First-run journey

| Step | User sees | User does | AI does | Visual UI surface | Exit condition |
|---|---|---|---|---|---|
| 1. Choose outcome | Outcome picker | Selects outcome | Maps to workflow | Cards with artifact previews | Outcome selected |
| 2. Provide context | Minimum viable context | Connects or samples data | Explains need | Connector cards + scope selector | Context sufficient |
| 3. Review contract | Capability contract | Confirms scope | Sets boundaries | Can/cannot/change/remember panel | Scope understood |
| 4. Preview plan | Plan preview | Edits constraints | Proposes steps | Step timeline + risk labels | Plan approved |
| 5. Generate artifact | Workbench | Waits / continues / cancels | Produces artifact | Progress + partial results | Artifact ready |
| 6. Verify | Source drawer / diff | Inspects evidence | Explains output | Evidence chips + editable output | User verifies |
| 7. Repair | Correction controls | Edits / rejects / constrains | Revises | Before/after diff | Correction learned or discarded |
| 8. Delegate next | Autonomy ladder | Enables safe next step | Configures monitor/draft | Approval settings | Next delegation set |

## 7. Empty-state design

For each major surface, replace blankness with safe intent and context.

| Empty state | Bad default | Better AI-first empty state | Primary action | Secondary action |
|---|---|---|---|---|
| Dashboard | “No data yet” | “Ask the analyst to find your top 5 risks. Connect data or try sample data.” | Try sample analysis | Connect source |
| Table/list | “No records” | “Import records, or let AI structure your uploaded file.” | Upload file | Use template |
| Agent activity | “No tasks” | “Start a draft-only agent task. Nothing will be changed without review.” | Start safe task | Learn controls |
| Memory/settings | “No preferences” | “Teach the AI one reusable preference.” | Add preference | Keep session-only |

## 8. Verification and repair design

The first run must teach users how to check and fix AI work.

### Verification mechanisms

- Source drawer
- Evidence chips
- Data freshness indicator
- Assumption list
- Confidence rationale without fake precision
- Diff / before-after comparison
- Simulation or preview
- Reviewer assignment

### Repair mechanisms

- Edit directly
- Accept selected parts
- Reject selected parts
- Regenerate with constraints
- Ask a follow-up clarification
- Change source scope
- Undo / rollback
- Teach correction once / object / workflow / team

### Correction rehearsal

Design one intentional, low-stakes repair moment:

**What the user corrects:**

**How the UI makes correction easy:**

**How the AI learns from it:** once / object / workflow / team / never

## 9. Autonomy progression

Do not jump to autopilot. Define the path.

| Level | Label | During onboarding? | Required proof | User control | Example |
|---:|---|---:|---|---|---|
| 1 | Inform | Yes | Relevant insight | Dismiss / inspect | “These accounts look risky.” |
| 2 | Suggest | Yes | Rationale + source | Accept / reject | “Recommend outreach.” |
| 3 | Draft | Yes | Editable artifact | Edit / regenerate | Draft email/report |
| 4 | Prepare | Maybe | Diff + affected objects | Approve selected | Stage CRM updates |
| 5 | Execute with confirmation | Later | Policy + preview | Confirm / cancel | Send approved email |
| 6 | Execute within policy | Later | Reliability + audit | Limits / rollback | Auto-tag low-risk tickets |
| 7 | Monitor and escalate | Later | Exception accuracy | Thresholds | Alert on renewal risk |

## 10. Individual, team, and admin tracks

### Individual onboarding

- First verified outcome
- Personal preferences
- Prompt/intent scaffolds
- Source inspection habit
- Correction rehearsal
- Saved workflow

### Team onboarding

- Shared agent instructions
- Review and approval queues
- Team object model
- Collaboration norms
- Handoff summaries
- Audit visibility

### Admin onboarding

- Integrations
- RBAC and permission boundaries
- Data retention and memory policy
- Audit logging
- Model/tool/provider settings
- Compliance policies
- Autonomous action limits

## 11. Contextual help and continued onboarding

Use pull-based help rather than long upfront tutorials.

| Trigger | Help surface | Content | Dismiss / recall behavior |
|---|---|---|---|
| User hovers over new AI action | Tooltip / micro demo | What it does and risk level | Dismissible, learn more |
| User starts high-risk workflow | Approval coach mark | What will change | Recall in approval drawer |
| User ignores sources | Verification nudge | “Check the 3 source records” | Dismissible |
| User repeats manual task | Automation suggestion | “Save this as a monitored workflow” | Suggestion stack |
| AI fails | Repair guidance | How to constrain/retry/undo | Stays in error state |

## 12. Activation metrics

| Metric | Target | Instrumentation event | Risk / caveat |
|---|---:|---|---|
| Time to first verified outcome | | | |
| First-run success rate | | | |
| Source/diff inspection rate | | | |
| Correction loop completion | | | |
| Output accepted after edit | | | |
| First safe automation enabled | | | |
| Return to saved workflow | | | |
| Admin policy completion | | | |
| Trust calibration score | | | |
| Undo/rollback rate after onboarding | | | |

## 13. Red-team onboarding scenarios

Test onboarding against these situations:

1. User does not know what to ask.
2. User refuses integration permissions.
3. User connects the wrong source.
4. User overtrusts the first output.
5. User undertrusts a good output.
6. AI output is partially wrong.
7. Source data is missing or stale.
8. User tries to enable automation too early.
9. Admin policies prevent the desired action.
10. Team member disputes AI-generated work.
11. User wants to delete memory.
12. User returns after a week and forgot the workflow.

For each: detection, UI response, repair path, and metric.

## 14. Final onboarding recommendation

Summarize:

- Primary first-run flow:
- Onboarding surfaces:
- What to defer:
- What to make contextual:
- Trust-calibration mechanisms:
- Activation metric that matters most:
- Biggest onboarding risk:
