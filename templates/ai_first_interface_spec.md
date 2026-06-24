# Template: AI-First SaaS Interface Spec

Use this template to produce a product-grade spec for an AI-native SaaS interface, including onboarding and activation.

## 1. Product frame

**Product / domain:**  
**Primary user types:**  
**Business context:**  
**Core jobs-to-be-done:**  
**AI-first thesis:**  
**What is not AI-first / should remain conventional UI:**  
**First verified outcome target:**  

## 2. Domain object model

| Object | Description | Key states | Key actions | Permissions | AI-relevant context |
|---|---|---|---|---|---|
| | | | | | |

## 3. Work graph

Map the user’s work as a graph, not a page sequence.

| Workflow node | Trigger | Inputs | Human judgment needed | AI capability | Output object | Risk |
|---|---|---|---|---|---|---|
| | | | | | | |

## 4. Onboarding and activation model

Use this section when the interface includes new-user onboarding, major workflow onboarding, enterprise rollout, or adoption improvement.

**Onboarding thesis:**  
**First verified outcome:**  
**Minimum viable context required:**  
**Capability contract summary:**  
**First-run artifact:**  
**Verification moment:**  
**Correction / repair rehearsal:**  
**Safe next delegation:**  

| Onboarding stage | User question | Surface / component | AI behavior | Visual proof | Success metric |
|---|---|---|---|---|---|
| Promise | Is this for me? | Outcome Picker | Maps role to use cases | Artifact preview | Outcome selected |
| Context | What does it need? | Connector cards / context chips | Explains required context | Data scope | Minimum context provided |
| Capability | What can it do? | Capability Contract | States limits and controls | Can/cannot/change/remember | Boundaries understood |
| First run | Can it help now? | Plan Preview | Proposes steps | Plan + sources + risk | Task started |
| Verification | Can I trust this? | Source Drawer / Diff | Explains evidence | Editable artifact | Verified output |
| Repair | What if it is wrong? | Correction controls | Revises and learns scope | Before/after | Correction completed |
| Delegation | What can I automate? | Autonomy ladder | Suggests bounded automation | Policy + approvals | Safe workflow saved |

## 5. Human-AI responsibility map

| Task | Human owns | AI owns | Autonomy level | Evidence needed | Approval rule | Recovery |
|---|---|---|---|---|---|---|
| | | | | | | |

Autonomy levels:
1. Inform
2. Suggest
3. Draft
4. Prepare for approval
5. Execute with confirmation
6. Execute within policy
7. Monitor and escalate

## 6. Modality map

| Workflow stage | Best modality | Why | Visual surface | AI behavior | User controls |
|---|---|---|---|---|---|
| Discover | | | | | |
| Onboard | | | | | |
| Decide | | | | | |
| Create | | | | | |
| Review | | | | | |
| Execute | | | | | |
| Monitor | | | | | |
| Recover | | | | | |

## 7. Interface architecture

Define the main surfaces.

### Command center
Purpose:  
Shows:  
AI role:  
User actions:  

### Onboarding / first mission launcher
Outcome options:  
Role or maturity routing:  
Sample data / sandbox:  
First verified outcome:  
Skip / resume behavior:  

### Intent composer
Inputs:  
Context chips:  
Constraints:  
Examples/templates:  
Output selectors:  
Permission scope:  

### Object workbench
Core objects:  
Layouts:  
Filters/sorts/groupings:  
AI overlays:  
Bulk actions:  

### Artifact canvas
Artifact types:  
Editing controls:  
Versioning:  
Collaboration:  
Export/publish:  

### Agent activity rail
Active tasks:  
Blocked tasks:  
Approvals:  
Notifications:  
History:  

### Review and approval surface
Diff type:  
Evidence shown:  
Approval granularity:  
Rollback:  
Audit:  

### Memory and governance settings
Memory controls:  
Permissions:  
Policies:  
Audit logs:  
Team instructions:  

## 8. Key screen blueprints

Repeat for each screen.

### Screen: [name]

**Purpose:**  
**Primary user intent:**  
**AI role:**  
**Core objects:**  
**Layout regions:**  
**Primary components:**  
**Empty state:**  
**Onboarding / first-use state:**  
**Loading / interpreting state:**  
**Agent-working state:**  
**Review state:**  
**Error / repair state:**  
**Accessibility notes:**  
**Telemetry:**  

## 9. Key interaction flows

Repeat for each flow.

### Flow: [name]

1. Trigger:  
2. Context captured:  
3. Intent interpretation:  
4. Plan preview:  
5. User constraint editing:  
6. Agent execution:  
7. Visual output artifact:  
8. Review / approval:  
9. Commit / publish / send:  
10. Replay / audit log:  
11. Repair / rollback:  

## 10. Failure and repair model

| Failure | Detection | User-facing state | Recovery path | Audit artifact | Metric |
|---|---|---|---|---|---|
| Ambiguous intent | | | | | |
| Missing data | | | | | |
| Stale data | | | | | |
| Conflicting sources | | | | | |
| Low confidence | | | | | |
| Tool failure | | | | | |
| Permission denial | | | | | |
| Policy conflict | | | | | |
| Prompt injection | | | | | |
| Bad autonomous action | | | | | |
| Onboarding overtrust | | | | | |
| Onboarding underuse | | | | | |

## 11. Component inventory

| Component | Purpose | States | Inputs | Outputs | Accessibility requirements |
|---|---|---|---|---|---|
| Outcome Picker | | | | | |
| AI Capability Contract | | | | | |
| Minimum Viable Context Form | | | | | |
| Guided First Outcome | | | | | |
| Evidence Inspection Drill | | | | | |
| Diff Review Drill | | | | | |
| Repair Practice Card | | | | | |
| Autonomy Ladder Reveal | | | | | |
| Intent Composer | | | | | |
| Plan Preview Card | | | | | |
| Agent Activity Rail | | | | | |
| Source Drawer | | | | | |
| Diff Review | | | | | |
| Approval Gate | | | | | |
| Memory Inspector | | | | | |

## 12. Metrics

| Metric | Definition | Target | Instrumentation |
|---|---|---|---|
| Time to first verified outcome | | | |
| First-session useful artifact rate | | | |
| Source/diff inspection before first approval | | | |
| First repair success rate | | | |
| Turns to useful artifact | | | |
| Repair success rate | | | |
| False autonomous action rate | | | |
| Human review time | | | |
| First bounded automation configured | | | |
| Second-session return after first artifact | | | |
| Accessibility task success | | | |

## 13. Open assumptions and risks

- Assumption:  
- Risk:  
- Validation needed:  
