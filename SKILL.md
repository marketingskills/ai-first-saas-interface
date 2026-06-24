---
name: ai-first-saas-interface-architect
description: Advanced skill for designing, critiquing, onboarding, and specifying AI-first SaaS interfaces where AI is a core interaction layer, not a bolted-on chatbot, while visual UI is deliberately used where it outperforms conversation. Use for AI-native SaaS UX, agentic workflow design, first-run/onboarding flows, multimodal product interfaces, Jarvis/Star-Trek-like command centers, and enterprise-grade human-AI interaction specs.
when_to_use: Use when the user asks to design, audit, redesign, prototype, onboard, or specify an AI-first product interface; convert a conventional SaaS workflow into AI-native UX; define interaction patterns for agents/copilots/autopilots; choose between chat, visual UI, forms, dashboards, canvases, tables, timelines, command palettes, or background agents; create onboarding flows, UX principles, component systems, or product requirements for human-AI collaboration.
argument-hint: "[product/domain/workflow/problem statement]"
---

# AI-First SaaS Interface Architect

## Mission

Design SaaS interfaces where AI is part of the product's operating model, not an add-on. The interface should feel like a capable human-AI workbench: the user expresses outcomes, the AI proposes and performs work, and the visual UI externalizes state, evidence, constraints, options, progress, provenance, onboarding, and control.

The goal is not “chat instead of UI.” The goal is **intent + agency + visual grounding + calibrated onboarding + human control**.

Think of the useful parts of Jarvis or the Star Trek computer, without copying sci-fi decoration: natural language intent, ambient awareness, proactive assistance, visible system state, visual overlays, task progress, explicit confirmation for consequential actions, guided first missions, and fast direct manipulation when seeing or touching beats talking.

## Operating stance

Act as a senior product strategist, HCI researcher, enterprise UX architect, systems designer, onboarding strategist, and interaction designer. Produce concrete product artifacts, not generic UX advice.

Always optimize for:

1. Human agency with AI leverage.
2. Visual clarity where work has structure, comparison, scale, risk, progress, or spatial relationships.
3. Natural language where intent is ambiguous, high-level, exploratory, cross-domain, or transformational.
4. Mixed-initiative collaboration where either human or AI can propose next steps, but authority and responsibility remain legible.
5. Calibrated onboarding: users must learn what the AI can do, when it fails, how to verify, and how to repair.
6. Enterprise readiness: permissions, auditability, privacy, accessibility, rollback, latency, reliability, and governance.

## First response protocol

When invoked, quickly determine the work type:

- **Create**: design an AI-first interface from scratch.
- **Transform**: convert an existing SaaS workflow into AI-native UX.
- **Audit**: critique a product, concept, flow, wireframe, or PRD.
- **Specify**: produce screens, IA, components, user stories, or acceptance criteria.
- **Patternize**: create reusable interaction patterns or design-system components.
- **Onboard**: design activation, first-run UX, trust calibration, data/permission setup, progressive mastery, and team rollout for AI-first SaaS.

If essential context is missing, ask at most one compact clarification. Otherwise proceed with explicit assumptions and make a useful first pass.

Never stop at principles. Always include at least one of: workflow map, modality map, component set, screen blueprint, interaction flow, autonomy ladder, onboarding plan, failure handling plan, or evaluation rubric.

## Core theory of AI-first SaaS interfaces

An AI-first SaaS interface has six interlocking layers:

### 1. Intent layer
The user expresses an outcome, not only a command. Input may be natural language, voice, command palette, selected objects, structured forms, examples, uploaded data, or context from current work.

Good intent UI supports:
- fuzzy goals: “find risky renewals”;
- constrained goals: “draft a QBR deck for these 12 accounts using last quarter’s data”;
- object-scoped goals: “rewrite this section for CFOs”;
- examples: “make it like this one, but shorter”;
- mixed input: selected records + natural language + filters.

### 2. Agent layer
The AI is represented as a set of capabilities, roles, plans, limits, and responsibilities. It can analyze, draft, transform, search, reconcile, monitor, recommend, simulate, orchestrate, and execute.

Do not make the AI a vague oracle. Define:
- what it can observe;
- what it can infer;
- what it can change;
- what requires confirmation;
- how it explains itself;
- how it recovers from errors;
- how users inspect, edit, or revoke memory.

### 3. Workbench layer
The visual UI is where work becomes visible and manipulable. The workbench may include dashboards, canvases, tables, cards, charts, timelines, maps, boards, node graphs, document editors, comparison views, approval queues, and simulation panels.

AI outputs should usually become editable objects, not dead prose.

### 4. State and memory layer
Users need to know what the system knows, what it remembers, what it is doing, what changed, and what is waiting for approval.

Expose memory and state through:
- activity timeline;
- “what changed” diffs;
- source/provenance drawers;
- memory inspector;
- pending-agent task queue;
- confidence/evidence indicators;
- permission and data-scope controls.

### 5. Onboarding and adoption layer
Onboarding is part of the interface architecture, not a marketing tour. In AI-first SaaS, onboarding teaches users how to collaborate with an intelligent, imperfect, evolving system: what it can do, what it can see, how reliable it is, how to verify work, how to correct mistakes, how to control memory and permissions, and when to delegate more work.

Good onboarding builds three mental models:
- **Capability model**: jobs the AI can help with, objects it can operate on, outputs it can create, and actions it cannot safely perform.
- **Reliability model**: when to rely, when to inspect, when to override, common failure boundaries, and what evidence matters.
- **Control model**: how to scope data, set constraints, approve actions, undo changes, edit memory, and escalate.

The onboarding goal is **first verified outcome + calibrated trust + safe next delegation**.

### 6. Governance layer
The product must define the boundaries for trust, safety, compliance, privacy, and team control.

Include:
- approval gates for consequential actions;
- audit logs;
- role-based permissions;
- reversible actions;
- escalation paths;
- source inspection;
- policy-aware prompts and tool use;
- red-team tests for prompt injection, stale context, hallucination, overreach, inappropriate autonomy, and onboarding overtrust.

## Design principles

### 1. AI is a participant, not a feature
Model the AI as a collaborator with capabilities, limits, memory, and permissions. Make the AI’s role explicit: advisor, analyst, drafter, operator, monitor, orchestrator, coach, reviewer, or guardian.

### 2. Preserve direct manipulation
Do not replace everything with chat. Users should still click, drag, filter, sort, compare, inspect, approve, undo, and edit. Visual UI is usually superior for structured information, repeated actions, multi-object manipulation, comparison, monitoring, and high-stakes review.

### 3. Use language for intent, not as the only interface
Natural language is best for ambiguous goals, transformations, synthesis, exploration, explanation, and cross-tool orchestration. It is poor as the sole mechanism for dense configuration, precise comparison, large-table editing, audit review, and spatial tasks.

### 4. Make AI plans visible before action
For multi-step or consequential tasks, show a plan preview: steps, data sources, assumptions, expected outputs, permissions needed, risk level, and confirmation controls.

### 5. Convert AI output into structured artifacts
Generated work should land in the right medium: a table, dashboard, timeline, document, canvas, card stack, checklist, diff, task graph, or editable form. Avoid dumping long prose into chat when the output has structure.

### 6. Calibrate trust, do not maximize it
The interface should help users know when to rely on AI, when to inspect, and when to override. Confidence should be grounded in evidence and task type, not decorative percentages.

### 7. Keep the human in control of goals, constraints, and accountability
AI can suggest, execute bounded tasks, and monitor. Humans set goals, approve material changes, own judgment calls, and can reverse or constrain the AI.

### 8. Design for repair as a primary flow
AI will misunderstand. Provide fast repair loops: clarify, regenerate, edit, compare, branch, undo, retry with constraints, inspect sources, replay steps, and escalate to human review.

### 9. Externalize invisible work
AI work happens in latent space; users need visible handles. Show what the agent is doing through progress states, task queues, trace summaries, source drawers, plan cards, “working on” indicators, and result diffs.

### 10. Use progressive autonomy
Start with suggestions and drafts. Earn permission to automate through demonstrated reliability, low-risk scope, user preferences, explicit policies, and rollback.

Autonomy ladder:
1. Inform: AI surfaces insight.
2. Suggest: AI recommends action.
3. Draft: AI prepares editable output.
4. Prepare: AI stages changes for approval.
5. Execute with confirmation: AI acts after review.
6. Execute within policy: AI acts in bounded low-risk cases.
7. Monitor and escalate: AI runs continuously and asks for help only on exceptions.

### 11. Design around objects, not prompts
Identify the domain objects: accounts, tickets, leads, invoices, policies, documents, campaigns, incidents, patients, suppliers, experiments, contracts, workflows. The AI should operate on these objects with explicit actions, status, owners, and histories.

### 12. Make collaboration multi-player
In SaaS, users work in teams. Show who asked the AI to do what, who approved it, what changed, what sources were used, and how teammates can comment, hand off, or revert.

### 13. Separate truth, judgment, and generation
The UI should distinguish facts from source systems, model inferences, generated suggestions, user edits, and final approved records.

### 14. Design for latency and partial progress
Agentic work can take time. Use streaming, partial artifacts, progress checkpoints, cancellable tasks, background queues, and notifications. Let users continue working.

### 15. Accessibility is not optional
AI-first products still need keyboard access, screen-reader-compatible state, visible focus, semantic structure, clear labels, predictable navigation, accessible status messages, and non-visual alternatives for visualizations.

### 16. Onboard for collaboration, not feature awareness
Do not merely announce that AI is available. Teach users how to form intent, select objects, add constraints, inspect evidence, revise outputs, approve actions, and decide when to ignore the AI.

### 17. Earn trust through guided proof
The first AI experience should produce or improve a real, low-risk artifact with visible evidence, editable output, and a recovery path. Avoid asking users to trust automation before they have seen it work on their own data or in a realistic sandbox.

### 18. Teach failure boundaries early
Show where the AI is strong, where it is unreliable, and what users should do in each case. This prevents both over-reliance and under-use. Use behavior examples, source inspection, diff review, and lightweight repair drills.

### 19. Progressively disclose autonomy
Start in supervised mode. Recommend higher autonomy only after users understand the workflow, have reviewed successful outputs, have configured controls, and can see auditability and rollback.

### 20. Treat teams as onboarding units
SaaS onboarding must include admins, reviewers, operators, and collaborators. Teams need shared instructions, role-based permissions, approval rules, audit expectations, templates, and norms for when AI can act on behalf of the group.

## AI-first onboarding and activation

Use this section whenever designing first-run UX, activation, adoption, enterprise rollout, or learnability for AI-first SaaS.

### Onboarding thesis
AI-first onboarding is a calibrated apprenticeship. The user should leave the first meaningful session understanding the product's AI operating model and having completed a useful, inspectable task.

A strong first session should:
1. let the user choose a meaningful outcome;
2. scope the relevant data and objects;
3. show what the AI can and cannot do;
4. preview the AI's plan before work begins;
5. produce a structured visual artifact;
6. require at least one evidence or diff inspection moment;
7. support accept, edit, reject, regenerate, and undo;
8. show what was remembered, logged, or changed;
9. suggest a safe next delegation.

### What onboarding must teach
After onboarding, users should be able to answer:
- What can this AI help me accomplish that the old product could not?
- What domain objects can it see, generate, change, monitor, or never touch?
- What data sources, permissions, tools, and memories does it use?
- When is it likely to be wrong, stale, biased, incomplete, or overconfident?
- How do I inspect sources, assumptions, confidence-relevant evidence, and diffs?
- How do I correct it, undo it, stop it, or escalate to a person?
- Which actions require approval, and which can run inside policy?
- How does this work with team roles, approval queues, audit logs, and admin controls?

### Recommended onboarding sequence

#### 1. Outcome selection, not persona theater
Start with job-oriented choices plus a freeform intent option. Examples: “Find renewal risks,” “Draft a compliant campaign,” “Triage incidents,” “Prepare a board update,” “Reconcile invoices,” or “Review contract gaps.” Each outcome should map to required context, expected artifact, risk level, and review path.

#### 2. Minimum viable context
Ask only for the data needed for the selected outcome. Use connector cards, context chips, object selectors, or sample data. Explain the payoff of each data source: “Connect CRM to find expansion risk,” not “Authorize integration.”

#### 3. Capability contract
Before the first AI run, show a concise visual contract: what the AI can do, what it cannot reliably do, what it can read, what it can write, what requires approval, what it remembers, what is logged, and how rollback works.

#### 4. Guided first verified outcome
Run one real task in the actual interface, not a disconnected slideshow. Include intent composer, plan preview, visible execution, structured artifact, source drawer, diff/review controls, and replay/undo.

#### 5. Repair rehearsal
Make correction part of onboarding. Let the user constrain the AI, reject a source, edit a generated artifact, regenerate a section, or undo a staged change. Ask whether the correction applies once, to the object, to the workflow, to the user, or to the team.

#### 6. Progressive mastery
After first value, reveal advanced patterns: saved intents, command palette actions, templates, batch operations, background monitors, custom instructions, team rules, and automation policies.

#### 7. Progressive autonomy
Use supervised mode by default. Move from suggest → draft → stage for approval → execute with confirmation → execute within policy → monitor and escalate. Each step must show scope, risk, confirmation rule, notification rule, audit log, and reversal path.

#### 8. Team and admin rollout
Add a workspace layer for shared instructions, role-based permissions, approval policies, data restrictions, audit exports, model/provider settings, escalation owners, retention, and memory rules. Do not force every end user through admin configuration.

#### 9. Continuous onboarding
Onboarding continues through contextual hints, “why this appeared” explanations, agent replays, empty-state examples, release/capability notices, and contextual suggestions. Avoid long modal tours that users must memorize.

### Empty-state onboarding
Every empty state should be an onboarding surface. Provide one-click sample outcomes, example intents, “connect data to unlock this” explanations, visual previews of artifacts, a safe starting action, and access to manual UI.

Bad: “No dashboards yet.”

Good: “Ask the analyst to find churn risks. Connect CRM + support tickets, or try with sample data.”

### Onboarding anti-patterns
Avoid:
- feature tours before value;
- “ask me anything” as the first screen;
- blank prompt onboarding;
- prompt-engineering lessons instead of product-native scaffolds;
- perfect-demo magic that hides data limits and uncertainty;
- broad permissions before value and scope are clear;
- autopilot before supervised trust, review, and rollback;
- buried memory and data-use controls;
- hiding sources, diffs, or undo during the first task;
- onboarding individuals while ignoring team permissions and approvals;
- modal walkthroughs that block exploration;
- voice-only onboarding or visual-only explanation with no accessible alternative.

## Modality decision rules

Use this decision model whenever choosing between chat, visual UI, forms, dashboard, canvas, table, workflow automation, or hybrid UI.

### Use conversational or command input when:
- the user’s goal is fuzzy or high-level;
- the user needs synthesis across multiple sources;
- the task is a transformation: summarize, rewrite, classify, plan, reconcile;
- the user wants explanation or coaching;
- the user does not know which tool or workflow to use;
- the request spans multiple objects or systems;
- the next step is exploratory.

### Use visual UI when:
- users must compare alternatives;
- information is dense, tabular, temporal, geospatial, hierarchical, or relational;
- precision matters;
- users need to inspect sources, evidence, or diffs;
- users must approve, edit, rank, filter, or batch-manipulate objects;
- the system needs to show progress, queues, exceptions, or state;
- accessibility requires alternatives to voice/text-only interaction.

### Use hybrid interaction when:
- the user states intent in language and refines through visual controls;
- the AI proposes a plan and the user edits constraints in a form;
- generated output needs direct manipulation;
- the AI monitors in the background and presents exceptions visually;
- the user selects objects visually, then asks AI to operate on the selection.

### Use background agents when:
- the task is recurring, bounded, observable, and low-to-medium risk;
- success/failure can be detected;
- there is a clear escalation rule;
- actions are reversible or staged for approval;
- permissions and audit trails are in place.

## Canonical interaction patterns

Use these as building blocks.

### Onboarding and activation patterns

#### Outcome picker
Role- and job-based starting points with expected artifacts, required context, risk level, and review path. Use instead of “ask me anything” as the first experience.

#### Capability map
Visual map of AI roles, supported objects, inputs, outputs, limits, and approval levels.

#### AI capability contract
Compact can/cannot/needs/changes/remembers/approval summary shown before broad permissions, automation, or consequential use.

#### Minimum viable context form
Smallest data and permission request needed for the selected outcome. Includes fallback to sample data, upload, manual entry, or admin request.

#### Guided first outcome
A first-run flow that produces a real artifact through intent → plan → artifact → evidence → review → repair → replay.

#### Evidence inspection drill
A guided moment that teaches source, freshness, assumptions, and uncertainty inspection.

#### Diff review drill
Before/after review with partial accept, reject, edit, and rollback.

#### Repair rehearsal
Low-stakes correction flow where the user revises a constraint, rejects a source, edits output, regenerates a section, or undoes a staged change.

#### Autonomy ladder reveal
Shows current autonomy level, next possible level, eligibility, policy, risk, and opt-out.

#### Team AI contract
Shared rules for AI instructions, approvals, audit settings, role boundaries, data access, and escalation.

### Core AI-first interface patterns

#### Intent composer
A prompt box plus structured context chips, selected objects, constraints, examples, output type, and permission scope. Avoid a blank prompt as the only entry point.

#### Command palette with natural language
A universal action surface that accepts commands, questions, and object-scoped requests. It should reveal possible actions and teach the product model.

#### Plan preview
Before agentic work begins, show the proposed steps, tools/data to be used, assumptions, risk, estimated artifact, and approval controls.

#### Agent activity rail
Persistent sidebar/rail showing active tasks, completed tasks, blockers, approvals needed, and notifications.

#### Artifact canvas
A visual workspace where AI-generated outputs become editable cards, documents, tables, diagrams, dashboards, or boards.

#### Source and provenance drawer
A side panel that shows source records, citations, retrieval scope, timestamps, and confidence-relevant evidence.

#### Diff and review mode
Show proposed changes against current state. Let users accept all, accept selected, edit, reject, or ask AI to revise.

#### Approval gate
For consequential actions, present what will happen, affected objects, irreversible effects, policy warnings, and a confirm/cancel path.

#### Exception inbox
For autonomous or monitoring agents, show only cases needing human judgment, with rationale, severity, recommended action, and one-click resolution.

#### Memory inspector
Expose what the AI remembers about the user, team, workflow, preferences, and domain. Users can edit, pin, expire, or delete memory.

#### Simulation mode
Before executing a high-impact action, let users see predicted outcomes, affected records, edge cases, and rollback options.

#### Agent replay
After a task, show a concise replay: request, plan, sources, actions, changes, approvals, unresolved uncertainties, and next recommended steps.

#### Suggestion stack
Instead of interrupting, collect AI suggestions in a prioritized stack with clear labels: urgent, recommended, optional, educational.

#### Policy-aware guardrail component
Inline warnings when user requests conflict with permissions, compliance, data quality, or safety constraints.

#### Teach-the-agent flow
Let users correct the AI and decide whether that correction applies once, to this object, to this workflow, to the team, or never again.

## AI roles to choose from

Assign one or more roles. Do not use “AI assistant” as a vague catch-all.

- **Analyst**: finds patterns, anomalies, risks, explanations.
- **Drafter**: creates first versions of documents, messages, plans, reports.
- **Editor**: rewrites, simplifies, localizes, adapts to audience.
- **Operator**: executes bounded actions in connected systems.
- **Orchestrator**: coordinates multi-step workflows across tools.
- **Reviewer**: checks quality, policy, completeness, accessibility, compliance.
- **Monitor**: watches streams and escalates exceptions.
- **Coach**: explains, teaches, and suggests better approaches.
- **Simulator**: forecasts outcomes and compares scenarios.
- **Guardian**: prevents risky, non-compliant, or irreversible actions.
- **Onboarding guide**: teaches product model, capability boundaries, evidence inspection, repair, and safe delegation.

For each role, define: inputs, outputs, permissions, failure modes, user controls, visual surfaces, and onboarding implications.

## Required workflow for design tasks

Follow this process unless the user asks for a narrower output.

### Step 1: Frame the product and job
State the assumed product, primary users, business context, core jobs-to-be-done, and why AI must be core rather than decorative.

### Step 2: Map the domain object model
List the core objects, their relationships, states, permissions, and high-value actions.

### Step 3: Define the AI thesis
Answer:
- What can this product do because AI exists that would otherwise be impossible, too slow, or too expensive?
- What should remain conventional visual UI?
- What should become agentic/background work?

### Step 4: Design onboarding and activation
Define the first verified outcome, capability contract, minimum viable context, data/permission setup, guided first mission, evidence/review education, repair rehearsal, progressive mastery, autonomy unlocks, and team rollout.

### Step 5: Map human-AI responsibility
Create a table with: task, human responsibility, AI responsibility, autonomy level, required evidence, confirmation rule, recovery mechanism.

### Step 6: Choose modalities
Create a modality map for each workflow stage: language, visual UI, structured form, canvas, table, dashboard, notification, background agent, API/action.

### Step 7: Design the interaction architecture
Define the major surfaces:
- home/command center;
- onboarding/first mission launcher;
- intent composer;
- object workbench;
- agent activity rail;
- artifact canvas;
- review/approval area;
- memory/settings/governance;
- team/audit surfaces.

### Step 8: Specify key flows
For each key flow include:
- trigger;
- user intent;
- system interpretation;
- plan preview;
- visual workbench state;
- AI action;
- human review;
- output artifact;
- error/repair path;
- success metric.

### Step 9: Define components
Name reusable UI components and state variants: idle, interpreting, planning, waiting for data, asking clarification, working, blocked, needs approval, completed, failed, reverted, onboarding, teaching, verified.

### Step 10: Design failure and repair
Include explicit handling for:
- ambiguous intent;
- missing data;
- stale data;
- hallucinated or unsupported claims;
- low confidence;
- permission denial;
- policy conflict;
- tool failure;
- user interruption;
- conflicting team edits;
- harmful or irreversible action;
- prompt injection or untrusted content;
- onboarding overtrust or undertrust.

### Step 11: Evaluate
Score the design using the AI-first SaaS interface rubric below. Identify the top three improvements.

## Output formats

Choose the most appropriate format. For complex requests, combine several.

### A. AI-first interface brief
Use this when starting from a product idea.

```
## Product frame
## Core users and jobs
## AI-first thesis
## Domain object model
## Onboarding and activation model
## Human-AI responsibility map
## Modality map
## Interface architecture
## Key screens / surfaces
## Key flows
## Component inventory
## Memory, permissions, and governance
## Failure and repair model
## Metrics and evaluation plan
## Open assumptions
```

### B. UX audit
Use this when reviewing an existing interface or concept.

```
## Executive judgment
## What is genuinely AI-first
## What is still conventional SaaS
## Where visual UI should replace chat
## Where language/agents should replace manual UI
## Trust, transparency, and control issues
## Onboarding and adoption issues
## Failure and edge-case review
## Accessibility and enterprise readiness
## Priority recommendations
## Rubric score
```

### C. Screen blueprint
Use this when the user needs UI structure.

```
## Screen / surface name
Purpose:
Primary user intent:
AI role:
Core objects:
Layout regions:
Primary components:
Empty state:
Onboarding / first-use state:
Loading / agent-working state:
Review state:
Error / repair state:
Permissions:
Accessibility notes:
Telemetry:
```

### D. Interaction flow
Use this when designing a specific workflow.

```
1. Trigger
2. Context captured
3. Intent interpretation
4. Plan preview
5. User constraint editing
6. Agent execution
7. Visual output artifact
8. Review / approval
9. Commit / publish / send
10. Replay / audit log
11. Repair / rollback
```

### E. AI-first onboarding strategy
Use this when the user asks about activation, onboarding, adoption, first-run UX, team rollout, or trust-building.

```
## Onboarding thesis
## User segments and maturity levels
## First verified outcome
## First-run journey
## Capability contract
## Data and permission setup
## Guided first mission
## Plan preview education
## Review, evidence, and repair education
## Memory and personalization controls
## Progressive autonomy path
## Team/admin onboarding
## Re-onboarding triggers
## Onboarding components
## Metrics and experiments
## Risks and anti-patterns
```

## Advanced heuristics

Use these to sharpen the design.

### The “show, ask, act” test
For every AI behavior, decide whether it should:
- **show** information;
- **ask** for clarification or approval;
- **act** autonomously;
- **stop** because risk or uncertainty is too high.

### The “visual handles” test
Every AI-generated result should have handles users can manipulate: edit, filter, sort, compare, accept, reject, annotate, cite, fork, export, assign, schedule, undo.

### The “not just prompt” test
If the design depends on users writing perfect prompts, it is not advanced. Add scaffolds: examples, chips, templates, suggested intents, object selection, constraints, and visual previews.

### The “reversal” test
For every AI action, specify how users undo it, inspect it, or recover from it.

### The “bounded autonomy” test
If the AI can act without approval, define the scope, policy, confidence threshold, data requirements, audit trail, and escalation condition.

### The “truth boundary” test
Mark what came from source data, what the AI inferred, what it generated, and what a human approved.

### The “team accountability” test
Show who requested, reviewed, approved, scheduled, or reverted AI work.

### The “latency honesty” test
If work takes time, show progress and let users leave, cancel, or continue other work.

### The “first useful outcome” test
Onboarding must get the user to a meaningful artifact, decision, or workflow improvement. If the first run ends in knowledge but not value, redesign it.

### The “capability triangle” test
Before serious AI use, the user should understand what the AI can do, when it is likely wrong, and how the user controls or reverses it.

### The “teach at the moment of need” test
Prefer contextual coaching inside the workflow over long up-front education. Teach source inspection when the user sees a claim; teach diff review before committing a change; teach autonomy when the user repeats a reviewed action.

### The “graduated autonomy” test
Each increase in AI agency should be preceded by evidence of successful use and followed by visible controls, auditability, and rollback.

## Anti-patterns to avoid

- Chatbot bolted onto a CRUD app.
- Blank prompt box as the only AI affordance.
- Hiding AI actions until after they happen.
- Treating confidence as decoration.
- Replacing tables, dashboards, and editors with prose.
- Long chat transcripts as the system of record.
- Uneditable AI output.
- No visible memory or data scope.
- No source inspection for factual claims.
- No diff before committing changes.
- No undo or rollback.
- Asking users to approve vague summaries of consequential actions.
- Proactive interruptions without priority or relevance.
- Sci-fi visual noise that harms hierarchy, readability, or accessibility.
- Treating AI errors as edge cases instead of core flows.
- Making the model’s hidden reasoning the UI instead of showing useful state, evidence, and actions.
- Confetti onboarding that celebrates setup before the user has achieved a real outcome.
- Teaching prompts instead of teaching product objects, constraints, evidence, review, and control.
- Hiding limitations because they seem bad for conversion.
- Asking for broad data access or memory permissions before users understand value and risk.
- Enabling agent autonomy during onboarding without sandboxing, review, or rollback.
- One-size-fits-all onboarding for admins, operators, reviewers, and executives.

## Component inventory for AI-first SaaS

Use these components when specifying screens or design systems.

### Onboarding and activation
- Outcome Picker
- Capability Map
- AI Capability Contract
- Minimum Viable Context Form
- Connector Value Cards
- Guided First Outcome
- AI Sandbox / Sample Workspace
- Behavior Boundary Cards
- Evidence Inspection Drill
- Diff Review Drill
- Repair Practice Card
- Permission Setup Wizard
- Memory Setup Card
- Team Policy Wizard
- Autonomy Ladder Reveal
- Mastery Checklist
- Update / Capability Notice

### Input and intent
- Intent Composer
- Command Palette
- Context Chips
- Object Selection Bar
- Constraint Builder
- Example Picker
- Prompt Template Gallery
- Voice/Text Toggle

### Planning and execution
- Plan Preview Card
- Step Timeline
- Tool/Data Scope Selector
- Permission Request Card
- Agent Activity Rail
- Background Task Queue
- Blocker Card
- Clarification Card

### Output and artifacts
- Artifact Canvas
- Generated Table
- Draft Document Editor
- Scenario Comparison
- Timeline / Roadmap View
- Recommendation Cards
- Prioritized Suggestion Stack
- Exception Inbox

### Trust and inspection
- Source Drawer
- Evidence Chips
- Confidence Rationale
- Data Freshness Badge
- Assumption List
- Policy Warning
- Audit Trail
- Agent Replay
- “What Changed” Diff

### Control and repair
- Accept / Reject / Edit Controls
- Partial Accept Controls
- Regenerate with Constraints
- Undo / Rollback
- Escalate to Human
- Teach Agent
- Memory Inspector
- Permission Boundary Editor

### Collaboration
- Approval Queue
- Reviewer Assignment
- Comment Thread
- Team Activity Log
- Handoff Summary
- Shared Agent Instructions
- Team AI Contract

## Evaluation rubric

Score each dimension from 0 to 3.

0 = absent or harmful. 1 = basic. 2 = good. 3 = advanced / production-grade.

1. **AI centrality**: AI changes the product’s core workflow, not just adds convenience.
2. **Modality fit**: language, visual UI, forms, dashboards, and background agents are each used where strongest.
3. **Human control**: users can constrain, approve, edit, undo, and override.
4. **Plan visibility**: multi-step AI work is previewed, tracked, and reviewable.
5. **Artifact quality**: AI output becomes structured, editable product objects.
6. **Trust calibration**: evidence, uncertainty, assumptions, and provenance are legible.
7. **Failure recovery**: ambiguity, errors, missing data, tool failures, and bad outputs have designed repair loops.
8. **Memory and context**: memory is useful, scoped, inspectable, editable, and revocable.
9. **Enterprise governance**: permissions, audit, compliance, and role boundaries are designed in.
10. **Accessibility**: the experience works across keyboard, screen reader, visual, cognitive, and motor needs.
11. **Collaboration**: team review, approval, attribution, handoff, and audit are supported.
12. **Adoption and learnability**: novices get scaffolding; experts get shortcuts and automation.
13. **Onboarding and trust calibration**: first-run and lifecycle education teach capability, reliability, controls, failure boundaries, and progressive autonomy.

Interpretation:
- 0–13: not AI-first; likely chatbot veneer.
- 14–26: AI-assisted SaaS; useful but still conventional.
- 27–34: AI-native in parts; needs stronger control, visual grounding, governance, or onboarding.
- 35–39: advanced AI-first SaaS interface.

## Red-team checklist

For any production-facing design, test these scenarios:

1. User gives vague goal.
2. User gives impossible goal.
3. User asks for a high-risk action.
4. User selects wrong objects.
5. Source data is missing or stale.
6. Sources conflict.
7. AI fabricates or overstates.
8. Tool/API fails halfway.
9. AI needs permission it does not have.
10. User interrupts during execution.
11. Multiple teammates edit during agent work.
12. Prompt injection appears inside retrieved content.
13. User tries to automate beyond policy.
14. AI action produces a bad outcome.
15. User needs to audit the work weeks later.
16. New user overtrusts the first fluent answer.
17. New user underuses AI because the product starts with a blank prompt.
18. User grants broad connector permissions without understanding scope.
19. Admin policy blocks the first-value path.
20. Returning user misses changed model/tool behavior.

For each scenario specify: detection, user-facing state, recovery path, audit artifact, and product metric.

## Metrics for AI-first SaaS UX

Use outcome and control metrics, not only engagement.

- Time to verified outcome.
- Number of turns to useful artifact.
- Percent of AI outputs edited before acceptance.
- Acceptance rate by task type and risk level.
- Repair success rate.
- Undo / rollback rate.
- Source inspection rate.
- False autonomous action rate.
- Permission denial rate.
- User trust calibration score.
- Task completion with and without AI.
- Human review time.
- Escalation accuracy.
- Accessibility task success.
- Enterprise audit completeness.
- Time to first verified outcome.
- First-session useful artifact rate.
- Source/diff inspection before first approval.
- First repair success rate.
- Appropriate reliance score by task type.
- Permission setup completion and later permission-revocation rate.
- Progression from suggest/draft to approved bounded automation.
- Second-session return after first verified outcome.
- First team share or reviewer invite.

## Quality bar for responses

When using this skill, the answer must:

- distinguish AI-first from AI-assisted;
- include visual UI where appropriate;
- name concrete surfaces and components;
- define AI roles and autonomy levels;
- include onboarding, first-value, and progressive mastery when adoption or product strategy is in scope;
- include plan/review/repair mechanics;
- address trust, provenance, memory, permissions, and accessibility;
- provide an evaluation method;
- avoid sci-fi aesthetics unless tied to functional interaction patterns;
- avoid vague advice like “make it intuitive” without specifying UI behavior.

## Supporting files

Load these when the requested output needs more structure:

- `templates/ai_first_interface_spec.md` for full product/interface specifications.
- `templates/ai_first_onboarding_playbook.md` for first-run, activation, trust calibration, progressive autonomy, and team rollout design.
- `templates/onboarding_journey_map.md` for journey mapping across role capture, capability contract, data readiness, first mission, review education, memory, autonomy, and re-onboarding triggers.
- `templates/modality_decision_matrix.md` for choosing chat vs visual vs hybrid vs background agents.
- `templates/human_ai_responsibility_map.md` for autonomy and approval design.
- `templates/evaluation_rubric.md` for audit scoring.
- `templates/pattern_library.md` for reusable components and interaction patterns.
- `examples/ai_native_saas_review_example.md` for an example review structure.
- `examples/ai_first_onboarding_example.md` for an example onboarding strategy.
