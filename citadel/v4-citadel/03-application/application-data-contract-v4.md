# Application Data Contract

## Rule

JSON is authoritative.  
Markdown explains the JSON.  
The application renders the JSON.

## Data Files

- `03-application/data/citadel-v4.json`
- `03-application/data/rooms-v4.json`
- `03-application/data/door-map-v4.json`
- `03-application/data/great-hall-niches-v4.json`
- `03-application/data/key-forge-rune-gems-v4.json`

## Status Values

- known: confirmed from project context
- known_reciprocal: reciprocal of a known connection
- working_assignment: current v4 design placement, revise if stronger source appears
- reserved: intentionally open for future use
- legacy_candidate: mentioned earlier but not fully documented in loaded context

## Render Use

The application should use compass directions when deciding what wall/door/niche to render.
