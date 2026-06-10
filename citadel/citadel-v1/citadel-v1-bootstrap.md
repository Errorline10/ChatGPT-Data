# Great Citadel Bootstrap — citadel-v1

Load this folder as the active Citadel data source:

```text
/citadel/citadel-v1/
```

Source Codex release:

```text
Codex v3.2
```

Required files:

- `citadel-v1-manifest.json`
- `codex/citadel-v1-codex-core.json`
- `rooms/citadel-v1-room-index.json`
- `rooms/citadel-v1-room-render-definitions.json`
- `maps/citadel-v1-map-core.json`
- `renders/citadel-v1-render-core.json`
- `renders/citadel-v1-render-continuity-rules.json`
- `references/citadel-v1-image-reference-index.json`
- `exterior/citadel-v1-exterior-index.json`

Core activation rules:

1. Load all files in manifest order.
2. Confirm all Citadel files identify `sourceCodexVersion: v3.2`.
3. Activate all rules, protocols, definitions, checklists, topology constraints, render constraints, reference rules, exterior rules, 360 rules, and save rules.
4. Do not answer Citadel requests from generic fantasy assumptions.
5. Compile every Citadel image/map/render/exterior/360/blueprint/door prompt from the active Codex before generation.
6. Before any Citadel image generation, display the compiled prompt and ask: “Is this the correct prompt?”
7. Only generate after explicit approval.
8. After generation, perform the post-render compliance audit.
9. For GitHub saves, create the next self-describing version folder instead of overwriting this one.
