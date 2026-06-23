# Template: AI-First SaaS Interface Spec

Use this template to produce a product-grade spec for an AI-native SaaS interface.

## 1. Product frame

**Product / domain:**  
**Primary user types:**  
**Business context:**  
**Core jobs-to-be-done:**  
**AI-first thesis:**  
**What is not AI-first / should remain conventional UI:**  

## 2. Domain object model

| Object | Description | Key states | Key actions | Permissions | AI-relevant context |
|---|---|---|---|---|---|
| | | | | | |

## 3. Work graph

Map the user’s work as a graph, not a page sequence.

| Workflow node | Trigger | Inputs | Human judgment needed | AI capability | Output object | Risk |
|---|---|---|---|---|---|---|
| | | | | | | |

## 4. Human-AI responsibility map

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

## 5. Modality map

| Workflow stage | Best modality | Why | Visual surface | AI behavior | User controls |
|---|---|---|---|---|---|
| Discover | | | | | |
| Decide | | | | | |
| Create | | | | | |
| Review | | | | | |
| Execute | | | | | |
| Monitor | | | | | |
| Recover | | | | | |

## 6. Interface architecture

Define the main surfaces:

### Command center
Purpose:  
Shows:  
AI role:  
User actions:  

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

## 7. Key screen blueprints

Repeat for each screen.

### Screen: [name]

**Purpose:**  
**Primary user intent:**  
**AI role:**  
**Core objects:**  
**Layout regions:**  
**Primary components:**  
**Empty state:**  
**Loading / interpreting state:**  
**Agent-working state:**  
**Review state:**  
**Error / repair state:**  
**Accessibility notes:**  
**Telemetry:**  

## 8. Key interaction flows

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

## 9. Failure and repair model

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

## 10. Component inventory

| Component | Purpose | States | Inputs | Outputs | Accessibility requirements |
|---|---|---|---|---|---|
| Intent Composer | | | | | |
| Plan Preview Card | | | | | |
| Agent Activity Rail | | | | | |
| Source Drawer | | | | | |
| Diff Review | | | | | |
| Approval Gate | | | | | |
| Memory Inspector | | | | | |

## 11. Metrics

| Metric | Definition | Target | Instrumentation |
|---|---|---|---|
| Time to verified outcome | | | |
| Turns to useful artifact | | | |
| Repair success rate | | | |
| Source inspection rate | | | |
| False autonomous action rate | | | |
| Human review time | | | |
| Accessibility task success | | | |

## 12. Open assumptions and risks

- Assumption:  
- Risk:  
- Validation needed:
