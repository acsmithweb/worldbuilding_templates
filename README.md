
```
category: Dashboard
tags: [system/registry, orchestrator/root, meta]
security_clearance: Public
status: Active
last_updated: 2026-06-06
```

# Project Narayah: Systemic Template Registry

## Overview

**Systemic Analysis:** This dashboard serves as the central registry for the DM Orchestrator to monitor and deploy standardized "Runtime Environments". Each template link below points to a machine-readable source of truth optimized for RAG retrieval and TF-IDF search efficiency.

## Core Narrative & Orchestration

**Systemic Analysis:** These templates define the macro-narrative hierarchy, moving from campaign-wide constants to individual module triggers.

|Template Name|Level|Primary Agent|Narrative Role|
|:--|:--|:--|:--|
|[[Campaign Hub Template]]|Global|DM Orchestrator|Root node and world state tracker.|
|[[Adventure Chapter & Module Template]]|Chapter|DM Orchestrator|Top-level narrative container for arcs.|
|[[Quest & Encounter Node Template]]|Adventure|World Sentinel|Progression node tracking Saga Escalation.|
|[[Lore & Mystery Template]]|Narrative|NPC Engine|Manages the "Rule of Three Revelations".|

## World Sentinel: Geographical Entities

**Systemic Analysis:** These templates manage macro and micro-scale political and environmental logic, providing context for travel and localized events.

|Template Name|Scale|Focus|Interaction Protocol|
|:--|:--|:--|:--|
|[[Kingdom Template]]|Macro|Politics/Military|Defines regional demographics and history.|
|[[Region & Geography Template]]|Meso|Biome/Hazards|Manages weather, resources, and terrain.|
|[[City Template]]|Local|Infrastructure|Tracks districts, economic status, and laws.|
|[[Faction Template]]|Social|Power Metrics|Manages collective NPC behaviors and goals.|

## Entity Actors & Mechanics

**Security Gap:** While Public clearances allow attribute retrieval, the NPC Engine must restrict "Shadow State" variables (e.g., betrayal triggers, hidden motives) until specific Knowledge Gates are bypassed.

### Primary Actors

- **[[Player Character Template]]:** Ingests class-specific JSON for level-up and spellcasting features.
- **[[NPC Template]]:** Primary actor node for narrative friction and quest hooks.
- **[[Companion Template]]:** Streamlined actor with loyalty indexing and "Power Hooks".

### Combat & System Data

- **[[Bestiary & Entity Statblock]]:** Tactical combat node optimized for legacy JSON data ingestion.
- **[[Encounter Template]]:** Resolution node for combat, social, or puzzle friction.
- **[[Item & Legacy Item Template]]:** Manages "Statistical Data Governance" for unique equipment and evolution.
- **[[Spell & Ability Reference Template]]:** Standardized reference to prevent mechanical hallucination.

## Systemic Governance

**H3: Chronological Synchronization** The **[[Calendar and Chronology Template]]** provides the temporal framework required by the World Sentinel to trigger global state changes based on the in-game date.

**H3: Economic Nodes** Commercial transactions are facilitated through the **[[Shop Template]]**, which defines specialized merchant inventory and restricted black-market data.

---

### JSON Shadow State

```
{
  "registry_status": "Active",
  "total_templates_indexed": 15,
  "knowledge_gate": [
    "v2_protocol_initialization",
    "shadow_state_masking_active"
  ],
  "goal_stack": [
    "unify_legacy_data",
    "optimize_rag_retrieval"
  ],
  "high_frequency_state": {
    "protocol_version": "2.0",
    "last_sync": "2026-06-06",
    "hallucination_mitigation_score": 10
  }
}
```

# Development Notes (Human Selected **)
---
**Security Clearance Execution:** You have tagged the dashboard as `Public` [Dashboard Source], but the "Entity Actors" section identifies a **Security Gap** where "Shadow State" variables (like betrayal triggers) must be restricted. You will need to ensure your **Filtered Retriever** logic is robust enough to exclude "Secret" YAML-tagged notes when the system is generating content for a "Public" viewer profile- .

- **The "Rule of Three Revelations":** The "Lore & Mystery Template" mentions managing this rule. To prevent hallucination, the **World Sentinel** will require specific "Knowledge Gate" logic in the JSON blocks of mystery-related notes to ensure information is only released when specific triggers are met

- **Latency Impact Tracking:** Your "Adventure Chapter" template must account for the "Latency Impact" seen in your Tideport warehouse example, where dungeon states change based on player rest-time (e.g., Scenario 1 vs. Scenario 2)
. Ensuring this is a standardized field in the Chapter template will prevent "State Loss" during long campaigns.
