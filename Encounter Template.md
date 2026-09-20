
```
category: Encounter
tags: [encounter/combat, encounter/social, quest-node]
security_clearance: Secret
status: Active
last_updated: 2026-06-06
```

# {Encounter Name}

## Overview

**Systemic Analysis:** Encounters serve as the primary resolution nodes for the DM Orchestrator's narrative loop. This template bridges the gap between the World Sentinel's geographical tracking and the NPC Engine's tactical execution.

- **Type:** [Combat / Social / Stealth / Puzzle]
- **Location:** [[Specific Location or Room Name]]
- **Difficulty Rating:** [Easy / Medium / Hard / Deadly]
- **Primary Objective:** [e.g., Defeat all hostiles, Secure the artifact, Negotiate passage]

## Combat and Hazard Mechanics

**Systemic Analysis:** All mechanical and quantitative data must be isolated in tables to ensure efficient parsing by the DM Orchestrator.

### Combatants

|Entity Name|Reference Link|Initiative|HP (Current/Max)|Role/Tactics|
|:--|:--|:--|:--|:--|
|[Creature A]|[[Statblock Link]]|[Modifier]|[Value]|[e.g., Tank/Skirmisher]|
|[Creature B]|[[Statblock Link]]|[Modifier]|[Value]|[e.g., Support/Caster]|

### Environmental Hazards and Traps

**Security Gap:** Hidden traps and environmental triggers must remain in the JSON Shadow State to prevent unauthorized player meta-knowledge.

|Hazard Name|Trigger|DC/Saving Throw|Damage/Effect|
|:--|:--|:--|:--|
|[Trap Name]|[Condition]|[DC Value]|[Damage Formula/Condition]|
|[Terrain Effect]|[Condition]|[DC Value]|[Movement Penalty/Effect]|

## Narrative Friction and Dialogue

**Systemic Analysis:** Social encounters require specific "Knowledge Gates" defined in the Shadow State to determine what information the NPC Engine is permitted to release.

- **Key Dialogue Triggers:** [Event that changes NPC disposition].
- **Required Information:** [Facts the party must learn/uncover].

## Loot and Rewards

|Item/Currency|Quantity|Description|Rarity|
|:--|:--|:--|:--|
|[Item Name]|[Amount]|[Brief Description]|[Rarity Level]|
|[Currency]|[Amount]|[Type: GP/SP/CP]|N/A|

## Chapter Impact Log

**Systemic Analysis:** Tracks how the outcome of this encounter ripples through the local and global state via the World Sentinel.

|Chapter|Outcome|Global State Change|
|:--|:--|:--|
|[Name]|[Success/Failure/Partial]|[e.g., Faction Disposition -2, Town Alert Level High]|

---

### JSON Shadow State

```
{
  "encounter_state": "Inactive",
  "mood_score": 0,
  "knowledge_gate": [
    "secret_door_location",
    "commander_vulnerability"
  ],
  "goal_stack": [
    "initiate_surprise_round",
    "retreat_at_50_percent_hp"
  ],
  "high_frequency_state": {
    "current_round": 0,
    "active_threats": 0,
    "is_alarm_raised": false,
    "reinforcements_arrived": false
  }
}
```