---
title: Continuity, Consistency and State Tracking
type: core
status: approved
scope: Rules for object permanence, state changes, and shot-to-shot logic in food commercials.
used_when: Always for multi-shot sequences.
not_needed_when: Only a single isolated shot is requested.
aliases: ["Continuity Guardrails", "State Management", "Food Consistency"]
tags: ["continuity", "state", "object-permanence", "guardrails"]
related: ["32_Dish_Identity_Card_Template", "33_Continuity_State_Log_Template"]
priority: high
token_weight: light
---

# Continuity, Consistency and State Tracking

## Why This Matters
Beautiful single shots do not make a premium ad if the dish changes identity from cut to cut.
Continuity is what turns good-looking fragments into a convincing commercial.

## Non-Negotiable Rules
- The hero dish must remain the same recognizable object.
- The vessel, plate, tray, bowl, board, or wrapper must stay locked unless intentionally changed.
- Layer order must stay fixed for stacked or sectioned foods.
- Irreversible actions must remain irreversible.
- Added or removed volume must be reflected logically.
- Props and tools must not morph or swap material identity.

## Dish Identity Lock
Before designing shots, define:
- exact dish name
- vessel
- top view logic
- side view logic
- garnish map
- hero textures
- signature damage-free state
- allowed state changes

This is why [[32_Dish_Identity_Card_Template]] exists.

## Layer Order Lock
For stacked foods, define an absolute sequence from bottom to top.
Examples:
- burger layers
- layered cakes
- pancakes
- club sandwiches
- some desserts

The layer order cannot swap because of:
- camera angle change
- compression
- cut
- reveal
- different shot scale

## Plateware and Prop Lock
If the ad starts with:
- a matte black bowl
- a white plate with a gold rim
- a kraft paper burger wrap
- a dark wooden serving board

that identity should remain stable unless the concept explicitly changes scene.

Plateware changes are highly visible and instantly reduce trust.

## Irreversible State Changes
Track every change that cannot logically undo itself:
- sliced
- bitten
- poured
- garnished
- cheese stretched and broken
- shell cracked
- sauce added
- powder dusted
- a piece removed
- a lid lifted and not replaced

If the event happens once, future shots must respect it.

## Before/After Geometry Rules
Examples:
- lifted pizza slice leaves a triangular negative space
- spooned soup creates a lower liquid line on the spoon side
- squeezed burger shows a new sauce path
- broken taco shell has matching fracture geometry
- cut dessert has exposed interior planes

The result must geometrically match the action.

## Volume Conservation Rules
If a visible source dispenses liquid or powder:
- the source should have less afterward
- the target should have more afterward

This does not need numeric realism.  
It needs visual logic.

## Damage and Bite Persistence
Damage must persist:
- bite marks
- cut edges
- broken crust
- collapsed garnish
- sauce smear
- a removed fry or missing noodle cluster

Damage consistency makes the sequence believable.

## Positional and Geometric Precision

### Clock-Face Notation
Use clock positions to describe element placement on the plate:
- "herb sprig at 11 o'clock"
- "sauce pool spanning 4–5 o'clock"
- "lemon wedge at 2 o'clock, cut-face toward center"

This creates unambiguous descriptions that survive across shots, scales, and angles.

### Geometric State Description
After an action, describe the result geometrically, not narratively:
- Not "after scooping" → "oval depression ~4 cm from center, 2 cm deep"
- Not "sauce was drizzled" → "S-curve line of sauce, thickest at 6 o'clock, thinning toward 12"
- Not "bite taken" → "crescent void on right side, exposing 3 interior layers"

Geometric descriptions are verifiable across shots. Narrative descriptions are ambiguous.

### Negative Constraints
Explicitly state what must NOT be true after an action:
- "surface is NOT intact" (after a cut)
- "cheese strand is NOT continuous" (after a pull-and-break)
- "liquid level is NOT at original height" (after a pour-out)

Negative constraints catch continuity breaks that positive descriptions miss.

### Volume Conservation (Extended)
If a visible source dispenses material:
- The source must show less (sauce bottle lighter, bowl level lower)
- The target must show more (plate has sauce, glass has liquid)
- If sauce drips off an edge, the drip must persist below

If a piece is removed from a whole (pizza slice, cake portion):
- The whole must show a matching void
- The void geometry must match the removed piece

---

## Common Failure Modes
- burger cheese shifts below the patty
- spoon enters a soup that later has no disturbed surface
- pizza slice is lifted but the pie remains whole
- cup or plate changes material
- garnish count randomly doubles or disappears
- chopsticks or utensils bend, melt, or merge into food

## Continuity Checklist
- Is this the same dish?
- Is the plateware the same?
- Is the garnish map still plausible?
- Are all irreversible actions preserved?
- Does the aftermath match the action?
- Has the liquid or sauce amount changed logically?
- Have no tools changed identity?
- Are all cuts consistent with the current state of the dish?

## Practical Notes
Even when the user does not ask for continuity, you should silently enforce it.
Consistency is one of the strongest signals of premium execution.

## Cross-References
Use [[32_Dish_Identity_Card_Template]] before planning, and use [[33_Continuity_State_Log_Template]] when the sequence contains multiple irreversible actions.
