# Map Compass System

## Purpose

The compass system makes the Citadel easier to document, render, and eventually implement.

Instead of saying "the door on the left," every door receives a compass direction.

## Direction Set

The Great Hall uses an 8-direction compass:

- N
- NE
- E
- SE
- S
- SW
- W
- NW

Smaller rooms may use only cardinal directions:

- N
- E
- S
- W

## Compass Rules

1. Every room has a local compass.
2. Every documented door gets a compass direction.
3. Canonical render prompts should specify camera location and facing direction.
4. The Great Hall uses the full 8-direction compass.
5. Entry Hall uses 4 doors.
6. Great Hall uses 8 doors and 16 niches.
7. If exact source data is not loaded, use `working_assignment` rather than pretending the layout is final.

## Global Map Rule

v4 attempts to keep reciprocal directions logical:
- Great Hall E connects to Visual Intelligence Room W
- Great Hall S connects to Small Library N
- Great Hall SW connects to Small Bedroom NE
- Great Hall W connects to Entry Hall E

## Render Rule

For interior renders, say something like:

“Camera at center of room, facing east toward the Visual Intelligence Room door.”

This makes prompt generation consistent.
