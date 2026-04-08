---
title: Prompt Assembly Rules
type: template
status: approved
scope: How to convert vault decisions into a compact generation prompt.
used_when: After structure and continuity have already been defined.
not_needed_when: During research or concept development.
aliases: ["Prompt Adapter", "Prompt Compression Rules"]
tags: ["template", "prompt", "adapter"]
related: ["00_Master_MOC", "01_How_To_Use_This_Vault"]
priority: high
token_weight: light
---

# Prompt Assembly Rules

## Core Principle
Do not dump the whole vault into the prompt.  
The prompt should contain only the decisions that materially change the output.

## Core Prompt Layers
Use this order:
1. **Format and role**
2. **Dish identity**
3. **Commercial structure**
4. **Camera and light cues**
5. **Action cues**
6. **Continuity locks**
7. **Environment cues**
8. **Negative exclusions**

## What Must Always Be Present
- aspect ratio and duration
- exact dish identity
- primary emotional goal
- 3–4 shot function sequence or equivalent structure
- one or two strongest camera ideas
- one or two strongest texture cues
- non-negotiable continuity locks

## What Should Be Optional
Add only if needed:
- detailed environment language
- advanced speed-ramp language
- sound or sensory language
- fine garnish instructions
- highly specific plateware description

## How to Avoid Token Bloat
- describe **visual result**, not full production explanation
- avoid naming every piece of gear unless the look truly depends on it
- avoid listing every ingredient when only the visible hero ingredients matter
- keep continuity rules in compressed checklist form
- use one clear adjective per texture rather than five synonyms

## How to Compress Camera Language
Instead of long camera essays, use short blocks such as:
- low hero angle with macro inserts
- fast push-in to tactile slow-motion moment
- smooth 45-degree diner-view payoff
- overhead reveal, then side macro interaction

## How to Compress Styling Language
Use only the essentials:
- controlled imperfection
- ready-to-eat presentation
- premium plateware
- visible freshness
- selective gloss
- clean professional hand interaction

## How to Compress Continuity Rules
Use a compact continuity line such as:
- maintain exact layer order, same plateware, same garnish map, persistent action aftermath

## Final Prompt Order
### Recommended assembly
1. Role and goal
2. Dish and serving identity
3. Visual structure of the sequence
4. Appetite cues
5. Camera cues
6. Light cues
7. Interaction cues
8. Continuity locks
9. Negative constraints

## Final Sanity Check
Before sending a prompt, ask:
- Is the dish identity clear?
- Is the sequence easy to imagine?
- Is the strongest appetite cue obvious?
- Are continuity rules included?
- Is anything here only decorative text?

## Cross-References
Use [[30_Creative_Brief_Template]], [[31_Shot_Functions_Template]], [[32_Dish_Identity_Card_Template]], and [[33_Continuity_State_Log_Template]] before prompt compression.
