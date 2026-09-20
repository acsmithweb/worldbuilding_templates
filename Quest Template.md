```
category: Quest
tags: [story/arc, quest/node, progression]
security_clearance: Public
status: Active
last_updated: 2026-06-06
```

# {Quest or Arc Name}

## Overview

**Systemic Analysis:** This template serves as the primary building block for the DM Orchestrator to track the narrative hierarchy. It maps the current node within the global campaign structure: `Campaign` ➔ `Chapter` ➔ `Adventure Arc` ➔ `Quest` ➔ `Encounter`.

- **Parent Chapter/Module:** [[Chapter Name]]
- **Parent Adventure Arc:** [[Arc Name]]
- **Primary Location:** [[Location Name]]
- **Narrative Phase:** [e.g., Phase I: Local Catalyst / Phase II: Continental Expansion]

## Objectives and Hierarchy Context

**Systemic Analysis:** Quantitative progression data is isolated in this table to allow the World Sentinel to monitor state changes and trigger subsequent quest nodes.

### Quest Objectives

|Objective ID|Description|Status|Mandatory|Dependency|
|:--|:--|:--|:--|:--|
|OBJ-01|{Primary Goal}|[Open/Complete]|Yes|None|
|OBJ-02|{Secondary Goal}|[Open/Complete]|No|OBJ-01|

### Related Encounters

|ID|Encounter Name|Type|Reference|
|:--|:--|:--|:--|
|ENC-01|[[Encounter Name]]|Combat|[Ref]|
|ENC-02|[[Encounter Name]]|Social|[Ref]|

## Rewards and Incentives

**Systemic Analysis:** Mechanical rewards are delineated for NPC Engine transaction processing and player inventory updates.

|Reward Type|Item/Value|Recipient|Condition for Granting|
|:--|:--|:--|:--|
|**Experience**|[Value] XP|Party|Quest Completion|
|**Currency**|[Amount] [GP/SP/CP]|Individual|Objective OBJ-01|
|**Faction Rep**|[+/- Value] with [[Faction]]|Party|Social Resolution|
|**Legacy Item**|[[Item Name]]|[Name]|Discovery|

## Narrative Friction

**Security Gap:** Critical quest fail-states, "Timed Triggers," or "Rule of Three" revelations must be restricted to the JSON Shadow State to maintain narrative tension.

### Key Stakeholders

- **Primary Questgiver:** [[NPC Name]]
- **Antagonist Representative:** [[NPC Name]]
- **Affected Factions:** [[Faction Name]]

### Sub-Arcs and Chain Dependencies

**H3 (Sub-Category):** Used for nested quest chains and sub-objectives within an Adventure Arc.

- **Sub-Quest ({X.A}): [[Quest Name]]** — [Brief summary of dependency].
- **Sub-Quest ({X.B}): [[Quest Name]]** — [Brief summary of dependency].

## Chapter Impact Log

**Systemic Analysis:** This table tracks "Global State Changes" driven by the resolution of this quest or arc.

|Chapter|Decision Point|Global State Change|
|:--|:--|:--|
|[Current]|[Player Action/Inaction]|[World Impact / Faction Shift]|
|[Current]|[e.g., Saved Dragon]|[e.g., Reduced Boss Military Scaling]|

---

### JSON Shadow State

```
{
  "quest_priority": 5,
  "hierarchy_position": {
    "campaign": "Campaign_ID",
    "chapter": 1,
    "arc": 2,
    "quest_index": 3
  },
  "knowledge_gate": [
    "revelation_1_villain_boss",
    "hidden_timer_expiry"
  ],
  "goal_stack": [
    "escalate_to_phase_ii",
    "trigger_rival_group_encounter"
  ],
  "high_frequency_state": {
    "current_step": 1,
    "is_timed": false,
    "fail_state_active": false,
    "revelation_counter": 0
  }
}
```