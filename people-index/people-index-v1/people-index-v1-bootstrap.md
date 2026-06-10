# People Index Bootstrap v1

Load this folder as the active People Index data source:

```text
/people-index/people-index-v1/
```

Required files:

- `people-index-v1-manifest.json`
- `people-index-v1-schema.json`
- `people-index-v1.json`
- `images/`

Rules:

1. Treat `id` as stable.
2. Do not invent private facts.
3. Use image references only when the user supplies or approves images.
4. When publishing to GitHub, do not overwrite older version folders.
5. Prefer the highest numbered visible `people-index-vN` folder when reloading.
6. Keep entries practical and useful for remembering names, faces, contexts, and relationships.
