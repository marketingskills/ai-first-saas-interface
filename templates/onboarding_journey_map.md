# Template: AI-First SaaS Onboarding Journey Map

Use this template when designing activation, first-run experience, product education, team rollout, or progressive autonomy for an AI-first SaaS product.

## 1. Onboarding thesis

**Product / workflow:**  
**Primary user segment:**  
**Why onboarding is different because AI is core:**  
**First verified outcome:**  
**Definition of activated user:**  

A user is not onboarded until they have produced or improved a real artifact, inspected how the AI made it, and understood how to correct, approve, undo, and constrain the AI.

## 2. User maturity segments

| Segment | Starting mental model | Risk | What they need to learn | Best onboarding pattern |
|---|---|---|---|---|
| First-time user | | | | Guided first mission |
| Early user | | | | Saved workflow + review habit |
| Power user | | | | Shortcuts + custom instructions |
| Team admin | | | | Permissions + policies + audit |
| Returning after AI change | | | | Re-onboarding card |

## 3. First verified outcome

**Outcome:**  
**Real object/data used:**  
**AI role:**  
**Visual artifact produced:**  
**Review required:**  
**Evidence shown:**  
**User action to complete:**  
**Exit criterion:**  

## 4. Onboarding journey

| Stage | User question | UI pattern | AI behavior | Visual surface | User control | Success signal |
|---|---|---|---|---|---|---|
| Role/job capture | Is this for my work? | | | | | |
| Capability contract | What can this do? | | | | | |
| Data readiness | Is my data connected and usable? | | | | | |
| Permission boundary | What can it see or change? | | | | | |
| Guided first mission | Can it help me now? | | | | | |
| Plan preview | What will it do? | | | | | |
| Visible execution | Is it working? | | | | | |
| Evidence review | Can I trust it? | | | | | |
| Repair/teach | How do I fix it? | | | | | |
| Commit/replay | What changed? | | | | | |
| Autonomy progression | Can it do this next time? | | | | | |

## 5. Capability contract

### Can do
- 

### Cannot do
- 

### Good at
- 

### Weak when
- 

### Requires human approval for
- 

### Can see
- 

### Can change
- 

### User controls
- 

## 6. Data and permission setup

| Source/system | Required for first mission? | Read access | Write access | Freshness | Missing data risk | User choice |
|---|---|---|---|---|---|---|
| | | | | | | |

Permission principles:
- Ask for the minimum scope needed for the first verified outcome.
- Separate read access from write access.
- Explain why each permission is needed.
- Let users continue with sample data or limited functionality where possible.
- Make revocation obvious.

## 7. First mission design

**Mission name:**  
**User-facing promise:**  
**Trigger:**  
**Inputs:**  
**AI plan preview:**  
**Visual output:**  
**Evidence shown:**  
**Review action:**  
**Repair moment:**  
**Commit action:**  
**Replay/audit artifact:**  

## 8. Review education

Teach these behaviors before users approve important AI work:

| Review skill | UI teaches it by | Success check |
|---|---|---|
| Open source/evidence | | |
| Compare before/after | | |
| Accept selected changes | | |
| Reject or edit output | | |
| Regenerate with constraints | | |
| Undo/rollback | | |
| Teach correction scope | | |

## 9. Memory and personalization

| Memory type | Example | Default | User control | Scope options | Risk |
|---|---|---|---|---|---|
| Personal preference | | Off / ask / on | | Once / this workflow / always | |
| Team instruction | | | | Team / project / role | |
| Learned correction | | | | Object / workflow / team | |
| Sensitive inference | | Avoid or require confirmation | | Delete / never remember | |

## 10. Progressive autonomy path

| Level | User-facing label | Unlock condition | Allowed actions | Approval rule | Escalation | Rollback |
|---|---|---|---|---|---|---|
| Inform | Show me insights | | | | | |
| Suggest | Recommend next steps | | | | | |
| Draft | Prepare drafts | | | | | |
| Prepare | Stage changes | | | | | |
| Execute with confirmation | Do it after I approve | | | | | |
| Execute within policy | Handle routine cases | | | | | |
| Monitor and escalate | Watch and notify me | | | | | |

## 11. Team/admin onboarding

| Admin concern | Onboarding surface | Required decision | Audit artifact |
|---|---|---|---|
| Role-based access | | | |
| Approval routing | | | |
| Shared instructions | | | |
| Data retention | | | |
| Restricted actions | | | |
| Escalation policy | | | |
| Model/tool change management | | | |

## 12. Re-onboarding triggers

Re-onboard contextually when:
- a new model changes behavior;
- a new tool or data source is connected;
- the AI gains write access;
- a new autonomous workflow is available;
- team policy changes;
- the user repeatedly rejects or repairs outputs;
- the product detects overtrust, underuse, or misuse;
- a workflow moves from low risk to high risk.

## 13. Metrics and instrumentation

| Metric | Definition | Target | Instrumentation |
|---|---|---|---|
| Time to first verified outcome | | | |
| First mission completion | | | |
| First useful artifact rate | | | |
| Prompt abandonment rate | | | |
| Plan preview comprehension | | | |
| Source/diff inspection before acceptance | | | |
| First correction success | | | |
| Teach-the-agent adoption | | | |
| Least-privilege permission completion | | | |
| Autonomy opt-in by risk level | | | |
| Over-automation rollback rate | | | |
| Team policy setup completion | | | |

## 14. Onboarding risks and mitigations

| Risk | Symptom | Mitigation | Metric |
|---|---|---|---|
| Overtrust | User accepts without inspecting | Require review tutorial and evidence affordance | |
| Undertrust | User never runs AI task | First mission with low-risk useful artifact | |
| Permission anxiety | User abandons connector setup | Least-privilege explanation and sample mode | |
| Prompt paralysis | User stares at blank input | Suggested missions and guided composer | |
| Tour fatigue | User skips education | Teach in-context through real work | |
| Unsafe autonomy | User enables broad automation | Progressive unlock and admin policy | |
| Hidden memory discomfort | User surprised by personalization | Memory inspector and scoped learning | |
