# Citadel Schema Notes

Suggested core objects:

## Room

- id
- name
- type
- purpose
- mood
- canonical_details
- doors
- render_prompts
- systems

## Door

- direction
- name
- connects_to
- status
- notes
- alcoves
- symbol

## Niche

- id
- room_id
- owned_by_door_direction
- side
- suggested_use
- status

## System

- id
- name
- purpose
- interaction_rules
- render_rules
