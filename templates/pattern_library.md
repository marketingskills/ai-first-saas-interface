# Template: AI-First SaaS Pattern Library

Use these patterns as reusable building blocks in specs, audits, and design systems.

## Intent Composer

**Problem:** Blank prompts require users to know what to ask.  
**Solution:** Combine natural language with context chips, selected objects, constraints, examples, and output selectors.  
**Use when:** Users need to express goals across product objects.  
**States:** idle, listening, interpreting, needs clarification, ready to run.  
**Controls:** object scope, output type, constraints, examples, permission boundary.

## Plan Preview Card

**Problem:** Users cannot trust multi-step AI work if they cannot see the plan.  
**Solution:** Show proposed steps, data sources, assumptions, tools, risk, expected artifacts, and approvals.  
**Use when:** Agent will perform multi-step or consequential work.  
**Controls:** edit plan, remove step, add constraint, approve, cancel.

## Agent Activity Rail

**Problem:** Background AI work becomes invisible.  
**Solution:** Persistent rail for active tasks, blockers, approvals, notifications, and history.  
**Use when:** AI can run tasks asynchronously or across workflows.  
**States:** running, blocked, needs review, completed, failed, reverted.

## Artifact Canvas

**Problem:** AI output trapped in chat is hard to edit or operationalize.  
**Solution:** Convert output into editable work objects: cards, tables, documents, diagrams, dashboards.  
**Use when:** Generated work must be reviewed, changed, shared, or committed.

## Source Drawer

**Problem:** Users need to inspect evidence without losing flow.  
**Solution:** Side panel with sources, timestamps, retrieval scope, quoted snippets, and linked records.  
**Use when:** AI makes factual, analytical, or compliance-relevant claims.

## Diff Review

**Problem:** AI-generated changes are risky when users cannot see exactly what changed.  
**Solution:** Before/after comparison with partial accept, reject, edit, and rollback.  
**Use when:** AI modifies documents, records, settings, code, workflows, or customer-facing content.

## Approval Gate

**Problem:** Consequential actions need explicit consent and accountability.  
**Solution:** Summarize action, affected objects, irreversible consequences, evidence, and policy status.  
**Use when:** Money, legal, deletion, privacy, customer communication, or system-of-record changes are involved.

## Exception Inbox

**Problem:** Autonomous agents should not constantly interrupt.  
**Solution:** Queue cases requiring human judgment, prioritized by severity and confidence.  
**Use when:** AI monitors ongoing workflows.

## Memory Inspector

**Problem:** Hidden personalization feels creepy and causes errors.  
**Solution:** Show remembered preferences, team rules, data scopes, and learned corrections. Allow edit/delete/expire.  
**Use when:** Product uses memory, personalization, or persistent instructions.

## Agent Replay

**Problem:** Users and teams need after-the-fact accountability.  
**Solution:** Concise replay of request, plan, sources, actions, changes, approvals, and unresolved uncertainties.  
**Use when:** Work is complex, collaborative, or auditable.

## Teach-the-Agent Flow

**Problem:** Corrections disappear or overgeneralize.  
**Solution:** After user correction, ask scope: once, this object, this workflow, this team, never.  
**Use when:** AI learns from user edits or feedback.
