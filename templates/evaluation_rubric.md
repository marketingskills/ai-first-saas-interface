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
| Learnability | Prompt expertise required | Examples | Scaffolds and shortcuts | Progressive mastery + expert automation | | |

## Score interpretation

- **0–12**: Not AI-first; likely chatbot veneer.
- **13–24**: AI-assisted SaaS; useful but conventional.
- **25–31**: AI-native in parts; needs stronger control, visual grounding, governance, or repair.
- **32–36**: Advanced AI-first SaaS interface.

## Recommendation format

For each weak dimension, provide:

1. Problem.
2. Why it matters.
3. Recommended UI pattern.
4. Example behavior.
5. Risk/tradeoff.
6. Metric to validate.
