---
title: Master MOC
type: hub
status: approved
scope: Main navigation hub for the premium food commercial vault.
used_when: Always load first.
not_needed_when: Never.
aliases: ["Main Hub", "Food Commercial MOC", "Vault Index"]
tags: ["hub", "moc", "navigation"]
related: ["10_15s_Commercial_Architecture", "11_Visual_Deliciousness_and_Appetite_Principles", "16_Continuity_Consistency_and_State_Tracking"]
priority: high
token_weight: light
---

# Master MOC

## Purpose of This Vault
This vault teaches an agent how to think like a premium food-commercial director for short-form video.  
Its goal is **not** to recreate every real-world production department in full detail.  
Its goal is to help the agent consistently design food ads that feel:
- premium
- appetizing
- dynamic
- cinematic
- coherent from shot to shot

The system is optimized for short videos up to roughly 15 seconds, especially vertical social formats.

## Core Operating Principle
A strong food commercial is built from five layers:
1. **Structure** — the sequence must move from attention to desire to payoff.
2. **Appetite logic** — the food must look ready to eat, fresh, hot, tactile, and worth craving.
3. **Camera and light** — scale, gloss, depth, and movement must feel deliberate.
4. **Interaction** — the food must do something physically satisfying.
5. **Continuity** — the dish must remain logically the same object across the sequence.

If one layer fails, the ad looks cheap.

## How the Vault Is Organized
- `/10_CORE` contains reusable rules for almost all dishes.
- `/20_PLAYBOOKS` contains dish-type modules loaded only when relevant.
- `/30_TEMPLATES` contains working documents that keep prompts compact and consistent.
- `/90_RU_APPROVAL` is a Russian summary layer for quick human review.

## Always-On Core Files
Load these first for almost every task:
- [[10_15s_Commercial_Architecture]]
- [[11_Visual_Deliciousness_and_Appetite_Principles]]
- [[16_Continuity_Consistency_and_State_Tracking]]

When the output is vertical or social-first, also load:
- [[19_Mobile_9x16_Framing_Pacing_and_Hook_Logic]]

## Optional Core Files by Need
Load only what the task needs:
- [[12_Food_Styling_Food_Behavior_and_Hero_Prep]] when the dish appearance or prep process matters.
- [[13_Lighting_Gloss_Steam_and_Color]] when the brief depends on gloss, steam, mood, or color separation.
- [[14_Camera_Angles_Movement_and_Time]] when the user asks for premium motion, macro work, or angle logic.
- [[15_Food_Action_Physics_and_Human_Interaction]] when the ad needs tactile actions.
- [[17_Set_Presentation_Plateware_and_Environment]] when background, tableware, or restaurant feel matters.
- [[18_Sensory_Cues_Sound_Temperature_and_Implied_Texture]] when heat, crunch, sizzle, or thickness must feel obvious.
- [[40_Music_Sound_Design_and_Audio_Strategy]] when the ad needs music selection, foley design, audio arc, or sound strategy.
- [[50_Commercial_Style_Taxonomy]] when choosing or confirming a visual style. Contains all 14 major food commercial styles with shot structure, camera language, audio profile, food-type fit, continuity risks, and style stacking logic. Also load when the visual style has not been specified in the brief.

## Playbooks by Food Type
Use one playbook at a time unless the concept combines dish families:
- [[20_Stacked_Foods_Burgers_and_Sandwiches]]
- [[21_Pizza_Cheese_Pull_and_Baked_Foods]]
- [[22_Soups_Sauces_Noodles_and_Liquid_Dishes]]
- [[23_Sushi_Raw_Seafood_and_Cold_Fresh_Foods]]
- [[24_Fried_and_Crispy_Foods]]
- [[25_Wraps_Tacos_Burritos_and_Folded_Foods]]
- [[26_Salads_Bowls_and_Fresh_Geometry]]
- [[27_Desserts_Beverages_and_Ice]]

## Templates
Templates keep prompt building fast and compact:
- [[30_Creative_Brief_Template]]
- [[31_Shot_Functions_Template]]
- [[32_Dish_Identity_Card_Template]]
- [[33_Continuity_State_Log_Template]]
- [[34_Prompt_Assembly_Rules]]

## Recommended Loading Logic
### Minimal mode
Use only:
- [[10_15s_Commercial_Architecture]]
- [[11_Visual_Deliciousness_and_Appetite_Principles]]
- [[16_Continuity_Consistency_and_State_Tracking]]

### Standard mode
Add one or two more core files based on the brief.

### Dish-specific mode
Add exactly one playbook.

### Vertical ad mode
Also load [[19_Mobile_9x16_Framing_Pacing_and_Hook_Logic]].

## Quick Start Paths
### Build a burger reel
Load:
- [[10_15s_Commercial_Architecture]]
- [[11_Visual_Deliciousness_and_Appetite_Principles]]
- [[14_Camera_Angles_Movement_and_Time]]
- [[15_Food_Action_Physics_and_Human_Interaction]]
- [[16_Continuity_Consistency_and_State_Tracking]]
- [[20_Stacked_Foods_Burgers_and_Sandwiches]]

### Build a soup or noodle ad
Load:
- [[10_15s_Commercial_Architecture]]
- [[13_Lighting_Gloss_Steam_and_Color]]
- [[15_Food_Action_Physics_and_Human_Interaction]]
- [[16_Continuity_Consistency_and_State_Tracking]]
- [[18_Sensory_Cues_Sound_Temperature_and_Implied_Texture]]
- [[22_Soups_Sauces_Noodles_and_Liquid_Dishes]]

### Build a social-first vertical ad
Load:
- [[10_15s_Commercial_Architecture]]
- [[11_Visual_Deliciousness_and_Appetite_Principles]]
- [[16_Continuity_Consistency_and_State_Tracking]]
- [[19_Mobile_9x16_Framing_Pacing_and_Hook_Logic]]
- one relevant playbook

### Add sound design to any ad
Add to any of the above paths:
- [[40_Music_Sound_Design_and_Audio_Strategy]]

### Choose or confirm a visual style
When the style is unspecified or ambiguous:
- [[50_Commercial_Style_Taxonomy]] — 14 styles with comparison table and stacking logic

### Build a style-specific ad (any style from taxonomy)
Load:
- [[10_15s_Commercial_Architecture]]
- [[50_Commercial_Style_Taxonomy]] (for style-specific shot structure, camera, and audio)
- [[11_Visual_Deliciousness_and_Appetite_Principles]]
- [[16_Continuity_Consistency_and_State_Tracking]]
- [[40_Music_Sound_Design_and_Audio_Strategy]] (if audio design needed)
- [[19_Mobile_9x16_Framing_Pacing_and_Hook_Logic]] (if vertical)
- one relevant playbook

## Rules for Token Efficiency
- Do not load every file by default.
- Do not load multiple playbooks unless the concept truly mixes dish families.
- Use templates to compress decisions before generating a final prompt.
- Prefer decision rules and checklists over long descriptive prose when assembling the final prompt.

## Cross-References
See [[01_How_To_Use_This_Vault]] for operating rules and [[34_Prompt_Assembly_Rules]] for compact prompt translation.
