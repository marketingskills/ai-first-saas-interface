# Template: AI-First SaaS Pattern Library

Use these patterns as reusable building blocks in specs, audits, onboarding flows, and design systems.

## Onboarding and activation patterns

### Outcome Picker

**Problem:** “Ask me anything” creates blank-page anxiety and weak prompts.  
**Solution:** Offer high-value outcomes tailored to role, data availability, and product objects.  
**Use when:** New users need a fast path to value.  
**States:** recommended, available, blocked by missing data, admin-gated.

### Capability Map

**Problem:** Users either overtrust or underuse AI because they do not understand its role.  
**Solution:** Show capabilities by workflow and role, with “good for,” “needs review,” and “not suitable for” labels.  
**Use when:** First-run onboarding, empty states, feature launches, or admin rollout.  
**Controls:** examples, limits, required data, review requirements, permission status.

### AI Capability Contract

**Problem:** Users are asked to trust or authorize AI before understanding scope.  
**Solution:** Show what the AI can do, cannot do reliably, can see, can change, remembers, logs, and needs approval for.  
**Use when:** Before broad permissions, automation, or first consequential use.

### Minimum Viable Context Form

**Problem:** AI products often ask for broad data access too early.  
**Solution:** Request only the context needed for the chosen first outcome, with clear payoff and fallback options.  
**Use when:** The AI needs user data, integrations, documents, or workspace context.

### Guided First Outcome

**Problem:** Tours teach UI chrome but not human-AI collaboration.  
**Solution:** Guide the user through a real task: intent, plan, artifact, evidence, review, repair, replay.  
**Use when:** Activation depends on users trusting and verifying AI work.

### Evidence Inspection Drill

**Problem:** Users may accept fluent AI output without verification.  
**Solution:** During onboarding, prompt users to inspect the source drawer, freshness badge, assumptions, or conflicting evidence.  
**Use when:** The AI makes factual, analytical, or compliance-relevant claims.

### Diff Review Drill

**Problem:** Users need to learn granular review before accepting AI changes.  
**Solution:** Show before/after changes with partial accept, reject, edit, and rollback.  
**Use when:** AI modifies documents, records, settings, workflows, or customer-facing content.

### Repair Rehearsal

**Problem:** Users abandon AI when the first output is imperfect.  
**Solution:** Make correction a guided success state: edit a constraint, regenerate a section, reject a source, undo a change, or teach the agent.  
**Use when:** Iterative collaboration is core to the product.

### Autonomy Ladder Reveal

**Problem:** Users do not know what the AI is allowed to do now or later.  
**Solution:** Show current autonomy level, locked/unlocked capabilities, approval rules, rollback, and requirements for higher autonomy.  
**Use when:** The product includes agents, monitors, or automation.

### Team AI Contract

**Problem:** Team SaaS needs shared expectations and governance, not just individual onboarding.  
**Solution:** Create visible team rules for AI instructions, permissions, approvals, audit, and escalation.  
**Use when:** Multiple users approve, share, publish, or rely on AI work.

## Core interface patterns

### Intent Composer

**Problem:** Blank prompts require users to know what to ask.  
**Solution:** Combine natural language with context chips, selected objects, constraints, examples, and output selectors.  
**Use when:** Users need to express goals across product objects.  
**States:** idle, listening, interpreting, needs clarification, ready to run.  
**Controls:** object scope, output type, constraints, examples, permission boundary.

### Command Palette with Natural Language

**Problem:** Users do not know where an AI action lives.  
**Solution:** Provide a universal action surface that accepts commands, questions, and object-scoped requests.  
**Use when:** The product has many actions or workflows.

### Plan Preview Card

**Problem:** Users cannot trust multi-step AI work if they cannot see the plan.  
**Solution:** Show proposed steps, data sources, assumptions, tools, risk, expected artifacts, and approvals.  
**Use when:** Agent will perform multi-step or consequential work.  
**Controls:** edit plan, remove step, add constraint, approve, cancel.

### Agent Activity Rail

**Problem:** Background AI work becomes invisible.  
**Solution:** Persistent rail for active tasks, blockers, approvals, notifications, and history.  
**Use when:** AI can run tasks across workflows.  
**States:** running, blocked, needs review, completed, failed, reverted.

### Artifact Canvas

**Problem:** AI output trapped in chat is hard to edit or operationalize.  
**Solution:** Convert output into editable work objects: cards, tables, documents, diagrams, dashboards.  
**Use when:** Generated work must be reviewed, changed, shared, or committed.

### Source Drawer

**Problem:** Users need to inspect evidence without losing flow.  
**Solution:** Side panel with sources, timestamps, retrieval scope, cited snippets, and linked records.  
**Use when:** AI makes factual, analytical, or compliance-relevant claims.

### Diff Review

**Problem:** AI-generated changes are risky when users cannot see exactly what changed.  
**Solution:** Before/after comparison with partial accept, reject, edit, and rollback.  
**Use when:** AI modifies documents, records, settings, code, workflows, or customer-facing content.

### Approval Gate

**Problem:** Consequential actions need explicit consent and accountability.  
**Solution:** Summarize action, affected objects, irreversible consequences, evidence, and policy status.  
**Use when:** Money, legal, deletion, privacy, customer communication, or system-of-record changes are involved.

### Exception Inbox

**Problem:** Autonomous agents should not constantly interrupt.  
**Solution:** Queue cases requiring human judgment, prioritized by severity and confidence.  
**Use when:** AI monitors ongoing workflows.

### Memory Inspector

**Problem:** Hidden personalization feels creepy and causes errors.  
**Solution:** Show remembered preferences, team rules, data scopes, and learned corrections. Allow edit/delete/expire.  
**Use when:** Product uses memory, personalization, or persistent instructions.

### Agent Replay

**Problem:** Users and teams need after-the-fact accountability.  
**Solution:** Concise replay of request, plan, sources, actions, changes, approvals, and unresolved uncertainties.  
**Use when:** Work is complex, collaborative, or auditable.

### Teach-the-Agent Flow

**Problem:** Corrections disappear or overgeneralize.  
**Solution:** After user correction, ask scope: once, this object, this workflow, this team, never.  
**Use when:** AI learns from user edits or feedback.
