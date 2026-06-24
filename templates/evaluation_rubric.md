# Template: AI-First SaaS Interface Evaluation Rubric

Score each dimension from 0 to 3.

0 = absent or harmful  
1 = basic  
2 = good  
3 = advanced / production-grade

| Dimension | 0 | 1 | 2 | 3 | Score | Notes |
|---|---|---|---|---|---|---|
| AI centrality | AI is decorative | AI assists minor tasks | AI changes key workflows | AI defines the operating model | | |
| Modality fit | Chat or GUI used blindly | Some reasonable choices | Strong chat/visual split | Seamless hybrid by task type | | |
| Human control | Hidden or irreversible | Basic cancel/edit | Clear approve/undo | Granular constraint, diff, rollback | | |
| Plan visibility | AI acts opaquely | Basic progress | Plan and steps visible | Plan, assumptions, tools, risk, approvals | | |
| Artifact quality | Dead prose | Some structured outputs | Editable artifacts | Full object model integration | | |
| Trust calibration | Black box | Generic confidence | Evidence/provenance shown | Calibrated by task, source, uncertainty | | |
| Failure recovery | Errors ignored | Retry only | Designed repair paths | Robust repair for ambiguity/tools/policy | | |
| Memory/context | Hidden or absent | Session-only context | Visible scoped memory | Inspectable, editable, revocable memory | | |
| Governance | None | Basic roles | Permissions and audit | Policy-aware, enterprise-ready controls | | |
| Accessibility | Exclusionary | Basic labels | WCAG-aware UI | Multimodal, keyboard, SR, cognitive support | | |
| Collaboration | Single-player | Comments only | Review/approval | Team attribution, handoff, audit | | |
| Adoption and learnability | Prompt expertise required | Examples or basic walkthrough | Scaffolds, shortcuts, contextual help | Progressive mastery and expert automation | | |
| Onboarding and trust calibration | Generic tour or blank prompt | Basic capability list | Guided first outcome with review | Verified outcome, evidence drill, repair rehearsal, autonomy ladder, team rollout | | |

## Score interpretation

- **0–13**: Not AI-first; likely chatbot veneer.
- **14–26**: AI-assisted SaaS; useful but conventional.
- **27–34**: AI-native in parts; needs stronger control, visual grounding, governance, onboarding, or repair.
- **35–39**: Advanced AI-first SaaS interface.

## Onboarding-specific scoring prompts

When evaluating onboarding, score these as part of onboarding and trust calibration:

| Question | Score 0 | Score 1 | Score 2 | Score 3 |
|---|---|---|---|---|
| First verified outcome | No real outcome | Setup completion only | Useful first artifact | Verified artifact with evidence and repair |
| Capability calibration | Hype or vague AI claims | Basic feature list | Strengths and limits shown | Can/cannot/needs/changes/remembers/approval contract |
| Prompt scaffolding | Blank prompt | Example prompts | Intent chips/templates | Outcome picker + context + constraints + artifact preview |
| Verification habit | Not taught | Sources available but hidden | Sources/diffs visible | User practices inspection in first run |
| Repair habit | Errors treated as failure | Retry | Edit/regenerate controls | Designed correction rehearsal with scoped learning |
| Autonomy progression | Immediate autopilot or none | Manual only | Approval gates | Consent ladder from draft to bounded automation |
| Team rollout | Ignored | Admin docs only | Roles/permissions visible | Team AI contract, approvals, audit, escalation |

## Recommendation format

For each weak dimension, provide:

1. Problem.
2. Why it matters.
3. Recommended UI pattern.
4. Example behavior.
5. Risk/tradeoff.
6. Metric to validate.
