```
category: Shop
tags: [location/shop, economy, infrastructure]
security_clearance: Public
status: Active
last_updated: 2026-06-06
```

# {Shop Name}

## Overview

**Systemic Analysis:** This document defines a commercial node for the NPC Engine and DM Orchestrator to facilitate economic transactions. All primary geographical and personnel connections must use [[Wikilinks]].

- **Location:** [[City Name]] or [[District Name]]
- **Specialization:** [e.g., Alchemical Supplies, Blacksmith, General Store]
- **Economic Status:** [e.g., Wealthy, Struggling, Black Market]

## Description

**Systemic Analysis:** Narrative descriptions are isolated from mechanical data to prevent agent hallucination.

[Provide a physical description of the store’s exterior, interior, and general atmosphere here].

## Staff and Management

**Systemic Analysis:** Primary staff members are linked to their respective NPC actor templates.

|Role|Name|Brief Description|
|:--|:--|:--|
|**Owner**|[[NPC Name]]|[Role and personality overview]|
|**Worker**|[[NPC Name]]|[Role and personality overview]|

## Items and Services for Sale

**Systemic Analysis:** All quantitative data, including prices and itemized categories, must be placed in Markdown tables for TF-IDF search efficiency.

|Item/Service|Price|Description|
|:--|:--|:--|
|{Item 1}|{x} gp/sp/cp|[Brief mechanical or flavor description]|
|{Item 2}|{x} gp/sp/cp|[Brief mechanical or flavor description]|

**Security Gap:** Restricted inventories, stolen goods, or black-market pricing modifiers must be isolated in the JSON Shadow State to prevent unauthorized player retrieval during standard "Public" clearance interactions.

## Rumors and Plot Hooks

- **Local Rumors:** [Rumors associated with the shop or its patrons].
- **Quest Connections:** [[Quest Name]] — [How the shop relates to active narratives].

## Chapter Impact Log

**Systemic Analysis:** This table tracks player-driven "Global State Changes," such as the shop closing, changing owners, or altering its inventory based on campaign events.

|Chapter|Action Taken|Global State Change|
|:--|:--|:--|
|[Chapter Name]|[Player Interaction]|[Impact on local economy or shop status]|

---

### JSON Shadow State

```
{
  "mood_score": 0,
  "knowledge_gate": [
    "secret_backroom_password",
    "owner_debt_to_faction"
  ],
  "goal_stack": [
    "liquidate_excess_stock",
    "identify_potential_thieves"
  ],
  "high_frequency_state": {
    "current_liquidity": 100,
    "inventory_restock_in_days": 5,
    "is_open": true,
    "discount_active": false
  }
}
```