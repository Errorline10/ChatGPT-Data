# ChatGPT Data Dump v1

This package uses self-describing version folders and self-identifying filenames.

## Pattern

```text
/area/area-vN/area-vN-file-name.ext
```

## Examples

```text
/citadel/citadel-v1/citadel-v1-manifest.json
/citadel/citadel-v1/rooms/citadel-v1-room-index.json
/citadel/citadel-v1/codex/citadel-v1-codex-core.json
/people-index/people-index-v1/people-index-v1.json
/people-index/people-index-v1/people-index-v1-schema.json
```

## Rules

1. Do not overwrite old published version folders.
2. Create a new `area-vN` folder for each published version.
3. Use the highest numbered version folder unless a specific version is requested.
4. Targeted file generation is allowed when the requested file path is clear.
