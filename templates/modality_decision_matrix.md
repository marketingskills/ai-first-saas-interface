# Template: Modality Decision Matrix

Use this matrix to decide whether a workflow stage should use chat, visual UI, form controls, a canvas, dashboard, table, or background agent.

## Decision questions

1. Is the goal fuzzy or precise?
2. Is the data sparse or dense?
3. Is the task exploratory or repetitive?
4. Does the user need to compare alternatives?
5. Does the result need to be edited directly?
6. Is the action reversible?
7. Is the risk low, medium, high, or regulated?
8. Does the user need evidence or provenance?
9. Is the task synchronous or backgroundable?
10. Is accessibility better served by visual, text, keyboard, or multimodal controls?

## Matrix

| Task / stage | User need | Data shape | Risk | Best modality | Why | Required AI UI pattern | Required visual pattern |
|---|---|---|---|---|---|---|---|
| | Fuzzy / precise | Sparse / dense / relational / temporal | Low / med / high | Chat / command / form / table / canvas / dashboard / background / hybrid | | | |

## Modality rules

### Prefer natural language / command when
- intent is ambiguous;
- the user wants transformation or synthesis;
- the task spans multiple systems;
- the user does not know where to start;
- the output can be previewed before commitment.

### Prefer visual UI when
- comparison, precision, or multi-object manipulation matters;
- the user needs to see system state;
- users must review evidence, sources, or diffs;
- the task is repetitive and can be accelerated by controls;
- the output is a structured object, not just an answer.

### Prefer hybrid when
- language captures intent but visual controls refine constraints;
- AI drafts and users edit;
- agent work needs plan preview, progress, and review;
- selected objects provide context for natural language.

### Prefer background agents when
- the task is recurring and bounded;
- the agent can detect success/failure;
- risk is manageable;
- escalation rules are clear;
- actions are reversible, staged, or policy-bounded.
