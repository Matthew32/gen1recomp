# full_spanish_translation

A Spanish translation of the game.

Generated with `python3 tools/modkit.py translation full_spanish_translation`. See
`TRANSLATING.md` for how to work on it.

## Status

Nothing is translated yet: 579 strings are waiting in `lang/`.

| Catalog | Entries |
|---|---|
| `lang/dialogue.lua` | 6 |
| `lang/strings.lua` | 555 |
| `lang/species_names.lua` | 3 |
| `lang/move_names.lua` | 4 |
| `lang/item_names.lua` | 5 |
| `lang/trainer_names.lua` | 1 |
| `lang/status_labels.lua` | 5 |

## Layout

- `manifest.json` - identity and the engine version range
- `main.lua` - registers whatever is filled in and skips whatever is not
- `lang/` - the catalogs; this is the whole job
- `assets/font/` - your glyph sheet
