---
title: How To Use This Vault
type: hub
status: approved
scope: Operational rules for loading files and applying them efficiently.
used_when: At setup and whenever a workflow needs clarification.
not_needed_when: When the agent already follows the loading logic correctly.
aliases: ["Usage Guide", "Agent Loading Rules", "Operating Instructions"]
tags: ["usage", "workflow", "loading"]
related: ["00_Master_MOC", "34_Prompt_Assembly_Rules"]
priority: high
token_weight: light
---

# How To Use This Vault

## Goal of the Vault
This vault exists to help an agent produce better food-commercial concepts without drowning the context window in unnecessary production trivia.

The correct question is not:
> "What does the entire food production industry know?"

The correct question is:
> "What rules most reliably make a short food ad look premium, appetizing, and intentional?"

## Golden Loading Rule
Start small. Expand only when the brief requires more specificity.

### Default starting stack
- [[00_Master_MOC]]
- [[10_15s_Commercial_Architecture]]
- [[11_Visual_Deliciousness_and_Appetite_Principles]]
- [[16_Continuity_Consistency_and_State_Tracking]]

This gives structure, appetite logic, and continuity control.

## When to Add Extra Core Files
### Add [[12_Food_Styling_Food_Behavior_and_Hero_Prep]] when:
- the dish appearance is delicate
- ingredients can wilt, melt, dry, or collapse
- the sequence includes prep, garnish, or plating

### Add [[13_Lighting_Gloss_Steam_and_Color]] when:
- the user wants a glossy, moody, warm, steamy, or luxurious feel
- the food depends on shine, translucency, or visible heat

### Add [[14_Camera_Angles_Movement_and_Time]] when:
- the brief calls for premium movement
- macro, slow motion, orbiting, or push-ins matter
- the dish shape needs a specific angle logic

### Add [[15_Food_Action_Physics_and_Human_Interaction]] when:
- the ad needs squish, pull, slice, pour, toss, crack, dip, or lift
- the concept risks feeling static

### Add [[17_Set_Presentation_Plateware_and_Environment]] when:
- the restaurant atmosphere matters
- the ad needs a plate, bowl, tray, board, or tabletop logic
- the environment must support the dish identity

### Add [[18_Sensory_Cues_Sound_Temperature_and_Implied_Texture]] when:
- heat, crunch, sizzle, fizz, thickness, or freshness should be immediately felt

### Add [[19_Mobile_9x16_Framing_Pacing_and_Hook_Logic]] when:
- the ad is social-first
- the video must read clearly on a phone
- the first seconds need maximum stopping power

## When to Use Playbooks
A playbook is justified when the dish has a specific physical identity that changes:
- best angles
- best actions
- best lighting traits
- failure modes
- continuity priorities

Examples:
- burgers require layer logic and compression behavior
- pizza requires crust, melt, cut, and cheese-pull behavior
- soups require steam, surface tension, and spoon logic

## When Not to Use Playbooks
Do not load a playbook just because it exists.
Skip it when:
- the user only wants a general framework
- the brief is dish-agnostic
- the concept is more about brand mood than food mechanics

## Prompt Building Logic
The vault should be used in this order:
1. Define the commercial objective.
2. Define the dish identity.
3. Define the shot functions.
4. Define the non-negotiable continuity rules.
5. Add only the visual language needed for that specific ad.

## Common Mistakes
- Loading every file at once.
- Writing prompts as long essays.
- Over-describing gear instead of describing visual result.
- Forgetting that each shot needs a clear function.
- Forgetting that the same hero dish must remain the same dish.

## Good Working Pattern
1. Fill [[30_Creative_Brief_Template]]
2. Fill [[31_Shot_Functions_Template]]
3. Fill [[32_Dish_Identity_Card_Template]]
4. If the sequence has irreversible changes, fill [[33_Continuity_State_Log_Template]]
5. Compress using [[34_Prompt_Assembly_Rules]]

## Cross-References
Return to [[00_Master_MOC]] for navigation. Use [[34_Prompt_Assembly_Rules]] when converting the vault into a final generation prompt.
