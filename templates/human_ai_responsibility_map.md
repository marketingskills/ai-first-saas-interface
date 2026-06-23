# Template: Human-AI Responsibility Map

Use this to define control, agency, approvals, and accountability.

## Autonomy ladder

1. **Inform**: AI surfaces information.
2. **Suggest**: AI recommends action.
3. **Draft**: AI creates editable output.
4. **Prepare**: AI stages changes for review.
5. **Execute with confirmation**: AI acts after explicit approval.
6. **Execute within policy**: AI acts autonomously inside bounded rules.
7. **Monitor and escalate**: AI runs in the background and surfaces exceptions.

## Responsibility table

| Workflow task | Human owns | AI owns | Autonomy level | Why this level | Evidence shown | Approval gate | Undo / rollback | Audit record |
|---|---|---|---|---|---|---|---|---|
| | | | | | | | | |

## Confirmation rules

Use explicit confirmation when:
- money, legal, customer-facing, security, privacy, deletion, or irreversible changes are involved;
- the AI changes records in a system of record;
- confidence is low or evidence is incomplete;
- user intent is ambiguous;
- policy requires human approval.

Use staged approval when:
- batch changes affect many objects;
- the AI can prepare but not safely commit;
- users need partial accept/reject controls.

Use autonomous execution only when:
- action is low-risk;
- success can be verified;
- failure is recoverable;
- scope is bounded;
- audit logging exists;
- users can opt out or adjust policy.

## Accountability questions

- Who requested the AI action?
- What data did the AI use?
- What assumptions did it make?
- What exactly changed?
- Who approved it?
- Can it be reversed?
- What policy allowed it?
- What should the AI learn from the result?
