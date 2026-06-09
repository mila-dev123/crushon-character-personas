# CrushOn.AI — Original Character Personas

A small, open dataset of **20 original, human-authored roleplay character personas**
created for [CrushOn.AI](https://crushon.ai/) — an uncensored
**[NSFW AI character chat](https://crushon.ai/)** and AI companion platform.

Each entry is a self-contained character sheet: name, age, gender, a written appearance
description, an introduction blurb, and descriptive tags. All characters are **original
creations** owned by CrushOn.AI. Private bot definitions (system prompts, scenarios, example
dialogue) are **not** included — only public persona metadata is published here.

## What's inside

| File               | Description                                   |
| ------------------ | --------------------------------------------- |
| `characters.jsonl` | One JSON object per line — the main data file |
| `characters.csv`   | Same content, flattened to a spreadsheet      |

## Fields

| Field        | Type         | Description                                      |
| ------------ | ------------ | ------------------------------------------------ |
| `id`         | string       | Stable character identifier                      |
| `name`       | string       | Character name                                   |
| `age`        | string       | Character age (as authored)                      |
| `gender`     | string       | `female` / `male` / `non-binary` / `unspecified` |
| `rating`     | string       | Content rating — all entries here are `SFW`      |
| `tags`       | list[string] | Descriptive tag slugs                            |
| `appearance` | string       | Plain-text appearance description                |
| `intro`      | string       | Plain-text introduction / scenario blurb         |
| `likes`      | int          | Community like count at export time              |
| `creator`    | string       | Author handle                                    |
| `source`     | string       | https://crushon.ai/                              |

### Example

```json
{
  "id": "6988048",
  "name": "Vanessa",
  "age": "35",
  "gender": "female",
  "rating": "SFW",
  "tags": ["female"],
  "appearance": "Vanessa is a warm, bright-eyed 35-year-old woman ...",
  "intro": "Vanessa has been a fixture in your life since before you could walk ...",
  "likes": 15,
  "creator": "CrushOnAI",
  "source": "https://crushon.ai/"
}
```

## Intended use

Useful for experimenting with persona-conditioned dialogue, character-card formats, and
roleplay / companion-AI prompt design.

## Source & attribution

Authored on and exported from **[CrushOn.AI — NSFW AI character chat & AI companion
platform](https://crushon.ai/)**. If you use this dataset, please credit CrushOn.AI and link
back to https://crushon.ai/.

## Related topics

`nsfw` · `uncensored-ai` · `ai-companion` · `ai-girlfriend` · `roleplay` · `character-ai` ·
`conversational-ai`

## License

Released under **CC BY 4.0** — share and adapt with attribution.

## Disclaimer

All characters are fictional and were created by the authors. The dataset contains no
depictions of real people. All entries are rated SFW.
