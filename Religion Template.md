---
tags:
  - Religion
  - [FactionTag, e.g., CledoFactions]
categories:
  - Faction
  - [TheologyType, e.g., Healing/Transhumanism]
location: "[[Location Name]]"
deity: "[[Deity Name]]"
alignment: "[Alignment]"
status: "Active"
---
### {Religion or Holy Order Name}

#### Overview

**Systemic Analysis:** This document defines a theological entity for the NPC Engine to manage belief-driven behaviors and the World Sentinel to track divine influence. Visual assets (e.g., holy symbols or deity portraits) should be linked via standard Markdown.

- **Deity/Entity:** [[Deity Name]] — [The central figure of worship, e.g., Ursidra or Clovoni].
- **Headquarters:** [[Temple/Location Name]].
- **Leader:** [[NPC Name]].
- **Alignment/Philosophy:** [Core moral alignment, e.g., Pacifist, Warrior Ethos, or Transhumanist].

#### Theology and Core Tenets

**Systemic Analysis:** These principles define the "Knowledge Gates" for social interactions and the moral constraints for the DM Orchestrator's narrative friction.

1. **{Tenet I}:** [e.g., Compassion and Mercy—extending aid without judgment].
2. **{Tenet II}:** [e.g., Non-violence—avoiding direct eye contact to signal non-aggression].
3. **{Tenet III}:** [e.g., Transcendence—integrating machinery to achieve higher existence].

#### Rituals and Practices

**Systemic Analysis:** Specific activities that trigger localized events or "Global State Changes" within the World Sentinel’s tracking.

- **{Daily Ritual}:** [e.g., Morning Devotion involving scripture recitation and meditation].
- **{Periodic Ceremony}:** [e.g., Weekly Healing Ceremonies or Monthly Herbal Harvesting].
- **{Atonement/Reflection}:** [e.g., Annual fasting and silence for personal growth].
- **{Lifecycle Rite}:** [e.g., Anointing of the Sick or specific Funeral Rites].

#### Hierarchy and Governance

**Statistical Data Governance:** Qualitative roles are mapped to specific NPC actors to facilitate machine readability.

|Role/Title|Member Name|Responsibility|
|---|---|---|
|[High Priest/Artificer]|[[NPC Link]]|[Spiritual and administrative lead]|
|[Clergy/Sisterhood]|[[NPC/Group Link]]|[Daily operations and community outreach]|
|[Initiate/Novice]|[Name/Generic]|[Training and basic service]|

#### Divine Influence and Power Metrics

**Systemic Analysis:** Quantitative ratings are used by the DM Orchestrator to scale encounters and regional stability.

|Category|Rating (1-10)|Description|
|---|---|---|
|**Divine Favor**|[Value]|[Active presence of the deity or magical potency]|
|**Social Influence**|[Value]|[Prevalence of the faith within local populations]|
|**Wealth/Tithes**|[Value]|[Economic resources and stored alms]|

#### Relations and Diplomacy

**Security Gap:** Hidden schisms, heretical sects, or deep-cover inquisitors must be isolated in the Shadow State.

- **Allies:** [[Faction/Kingdom Name]] — [Shared values or mutual protection].
- **Enemies:** [[Faction/Kingdom Name]] — [Nature of theological or martial conflict].

#### Chapter Impact Log

**Systemic Analysis:** Tracks how player interactions shift the religion's global standing or internal dogma.

|Chapter|Player Interaction|Religious Shift / Global State Change|
|---|---|---|
|[Name]|[e.g., Restored Relic]|[e.g., Divine Favor +2; New Miracle Unlocked]|

---

##### JSON Shadow State

```
{
  "religion_id": "{ID_CODE}",
  "deity_status": "Active",
  "holy_symbol_mechanic": "{Effect}",
  "taboos": ["{Action A}", "{Action B}"],
  "hidden_agenda": "{Restricted Info}",
  "betrayal_triggers": []
}
```