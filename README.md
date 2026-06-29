# Prose Craft 2

A Claude skill for writing fiction and creative prose that reads as human-authored, not machine-default.

## What this is

A skill for [Claude](https://claude.ai) that teaches it to write fiction with genuine craft — rhythm, restraint, figurative language, sentence-level music — **and** to avoid the structural patterns that make AI prose detectable.

Built on research (StoryScope, Russell et al. 2026) showing AI fiction is identifiable at 93% accuracy from **narrative structure alone**, even after professional style editing. The skill keeps Claude's craft abilities and adds a calibration layer that pushes each piece off Claude's known defaults.

## What's inside

- **SKILL.md** — the core skill instructions (philosophy, anti-patterns, the Posture Board, two-pass system, four modes)
- **references/** — 9 reference files covering:
  - `human-signal.md` — the key addition: how to diverge from measured AI signatures
  - `sound-and-rhythm.md` — alliteration, vowel music, cacophony, prosodic rhythm
  - `repetition-and-structure.md` — anaphora, chiasmus, parallelism, sentence architecture
  - `figurative-language.md` — metaphor, simile, metonymy, irony, symbolism
  - `narrative-craft.md` — story structure, POV, psychic distance, temporal architecture
  - `dialogue-and-voice.md` — character voice, speech rhythm, subtext, register
  - `pacing-and-paragraphs.md` — sentence/paragraph length variation, scene vs summary
  - `effects-toolkit.md` — maps desired reader effects to specific techniques
  - `discourse-and-argument.md` — rhetorical structure, persuasive devices

## The Posture Board (the key innovation)

Before writing any piece, the skill forces Claude to take an explicit position on 9 axes where it has known defaults:

| Axis | Claude's default | Divergent pole |
|------|-----------------|----------------|
| Time order | linear, chronological | nonlinear, flashback, delayed disclosure |
| Emotion rendering | embodied only (chest, breath) | sometimes name the feeling plainly |
| Narrator-reader relationship | sealed fictive dream | direct address, fourth-wall |
| World reference | self-contained, invented | names real books, brands, places |
| Escalation | flat, quiet ending | genuine escalation, "avalanche" endings |
| Plot shape | single track | subplots, ensemble, multiple locations |
| Protagonist morality | clear, sympathetic | ambivalent, compromised |
| Sensory density | lush, smell-heavy | spare, withheld |
| Dialogue function | one register (philosophical) | mixed — gossip, logistics, comedy |

At least 3 axes must be pushed off center per piece, chosen to serve the material.

## Install

### One-click install (Claude desktop app)

1. Download `prose-craft-2.skill` from [Releases](../../releases)
2. Open Claude desktop app
3. Drag the `.skill` file into Claude, or go to **Settings > Skills** and import it

### Manual install

Copy the `prose-craft-2/` directory into your Claude skills folder:
- **Windows:** `%APPDATA%\Claude\skills\`
- **Mac:** `~/Library/Application Support/Claude/skills/`

## Usage

Once installed, the skill triggers automatically when you ask Claude to write, edit, analyze, or coach on creative prose. Examples:

- "Write me a short story about a lighthouse keeper"
- "This scene feels flat — help me fix it"
- "Why does this read like AI? Diagnose it."
- "Write something about rain"

The skill has four modes: **Write** (original creative work), **Edit** (improve existing prose), **Analyze** (break down how a piece works), and **Coach** (guidance on craft problems).

## License

MIT
