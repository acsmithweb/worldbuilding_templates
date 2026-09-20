---
name: skill-name-lowercase
description: >-
  Clear, actionable description of what this skill does and when the agent should activate it.
  Use third-person phrasing (e.g., "Use when standardizing notes or auditing directory trees...").
tags:
  - narayah/skill
  - governance
  - template
category: Governance & Standardization
security_clearance: Public
status: Active
last_updated: 2026-08-08
---

# {Skill Title}

## Overview
**Systemic Analysis:** Brief overview explaining the skill's operational purpose, target system agents (DM Orchestrator, World Sentinel, NPC Engine), and expected output artifacts.

## Operational Constraints & Domain Scoping
*   **Target Domain:** `01_Narrative_Orchestration` | `02_World_Sentinel` | `03_Entity_Actors` | `04_Combat_and_System_Data` | `99_System_Governance`
*   **Primary Agent:** `DM Orchestrator` | `World Sentinel` | `NPC Engine` | `System Architect`
*   **Security Gate:** `Public` | `Filtered` | `Shadow State Restricted`

## Package Architecture
```text
skills/{skill_name}/
├── SKILL.md          # Primary instruction file with YAML frontmatter
├── references/       # [Optional] Deep documentation, protocols, and technical specifications
├── resources/        # [Optional] Markdown templates, JSON schemas, and static data
├── scripts/          # [Optional] Executable bash or python helper scripts
└── examples/         # [Optional] Sample inputs, expected outputs, and reference diffs
```

## Mandatory Frontmatter Schema

All AGY skills in Project Narayah MUST include the following frontmatter fields:

| Field | Type | Description | Example |
| :--- | :--- | :--- | :--- |
| `name` | String | Lowercase, hyphenated unique skill identifier. | `narayah-data-standardizer` |
| `description` | String | Multi-line trigger description used by LLM router. | `Audits and reformats campaign notes...` |
| `tags` | Array | Categorization tags for graph view and search indexing. | `[narayah/skill, governance, template]` |
| `category` | String | Standard domain category group. | `Governance & Standardization` |

## Standard Execution Protocol

### Step 1: Context Audit & Environment Check
1. Inspect the target file, directory, or dataset.
2. Confirm containment boundaries (`CONTAINMENT_ROOT`) and path permissions.

### Step 2: Core Skill Execution
1. Apply the skill's specific workflow instructions.
2. Enforce strict Markdown hierarchy: `H1` (Entity Title), `H2` (Major Category), `H3` (Sub-Category).
3. Ensure all quantitative/mechanical stats are placed in **Markdown Tables**.

### Step 3: Verification & JSON Shadow State Sync
1. Verify that output conforms to Project Narayah standards.
2. Append or update the fenced `json` Shadow State block at the bottom of generated files.

---

### JSON Shadow State

```json
{
  "skill_name": "{skill-name-lowercase}",
  "version": "1.0.0",
  "category": "{Category Name}",
  "status": "Active",
  "knowledge_gate": [
    "v2_protocol_initialization"
  ],
  "goal_stack": [
    "execute_workflow",
    "verify_compliance"
  ],
  "high_frequency_state": {
    "last_executed": "2026-08-08",
    "compliance_score": 10
  }
}
```
