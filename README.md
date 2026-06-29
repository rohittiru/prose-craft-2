# Prose Craft 2

You've read AI fiction. You know the voice — lyrical, restrained, every emotion rendered through a tightening chest and a dimming light. The quiet ending. The earned silence. Beautiful, in its way. And now, after sixty thousand stories analyzed by StoryScope (Russell et al. 2026), identifiable as machine-written at 93% accuracy from narrative structure alone. Style didn't matter. A professional editor couldn't scrub the tell. The structure *was* the tell.

This is a [Claude](https://claude.ai) skill that fixes that.

## The problem it solves

Claude writes gorgeous prose. It also writes the *same* gorgeous prose every time — linear chronology, embodied-only emotion, sealed fictive dream, a single clean plot thread resolving through quiet acceptance. That convergence is the fingerprint. Not any one choice, but all of them at once, every time.

Prose Craft 2 keeps the craft and breaks the convergence. It teaches Claude when to fracture a timeline, when to name a feeling plainly instead of reaching for another somatic metaphor, when to let an ending *bang* instead of fade, when to let a protagonist stay compromised. Not as new rules — as live choices, made per piece, for reasons that serve the material.

## The Posture Board

The core mechanism. Before writing anything, the skill forces an explicit position on nine axes where Claude has measured defaults:

| Axis | Claude's default | The other pole |
|------|-----------------|----------------|
| Time | linear | nonlinear, flashback, delayed disclosure |
| Emotion | embodied only | sometimes just name it |
| Narrator | sealed dream | direct address, fourth wall |
| World | invented, generic | real books, real brands, real places |
| Escalation | flat, quiet fade | genuine rise, avalanche endings |
| Plot | single track | subplots, ensemble |
| Morality | clear, sympathetic | ambivalent, compromised |
| Senses | lush, smell-heavy | spare, withheld |
| Dialogue | philosophical debate | gossip, logistics, comedy, evasion |

At least three axes get pushed off center. Chosen for the material, not at random. Committed to fully, not hedged.

Across many pieces, because every piece is pushed off the *same* center, the body of work spreads out. That spread — not any single trick — is what reads as human.

## What's in the box

**`SKILL.md`** — The core instructions. Philosophy, anti-patterns, the Posture Board, a two-pass writing system, four modes (Write, Edit, Analyze, Coach).

**`references/`** — Nine files, 200+ devices across eleven families:

- **`human-signal.md`** — The new one. Nine dials mapping measured human-vs-AI differences, with guidance on when and how to diverge from Claude's defaults without performing the divergence.
- **`effects-toolkit.md`** — Organized by what you want the reader to *feel*: tension, beauty, humor, grief, speed, authority. Techniques grouped by effect, not taxonomy. Calibration warnings on the recipes that lean machine.
- **`narrative-craft.md`** — POV, psychic distance, temporal architecture, structural multiplicity, moral framing.
- **`dialogue-and-voice.md`** — Subtext, speech rhythm, register, diction. Why Claude's characters sound like philosophy professors and what to do about it.
- **`sound-and-rhythm.md`** — Alliteration, assonance, cacophony, euphony, cadence. The music under the prose.
- **`pacing-and-paragraphs.md`** — Sentence length variation, paragraph as breath, scene vs. summary, white space.
- **`repetition-and-structure.md`** — Anaphora, chiasmus, parallelism, periodic sentences. The architecture of emphasis.
- **`figurative-language.md`** — Metaphor, metonymy, irony, symbolism, synesthesia. The engine of imaginative prose.
- **`discourse-and-argument.md`** — Rhetorical devices for characters who persuade, manipulate, or argue.

## Install

**One-click** — Download [`prose-craft-2.skill`](https://github.com/rohittiru/prose-craft-2/releases/tag/v1.0.0) from Releases. Drag it into Claude, or import it under **Settings → Skills**.

**Manual** — Copy the `prose-craft-2/` directory into your skills folder:
- Windows: `%APPDATA%\Claude\skills\`
- Mac: `~/Library/Application Support/Claude/skills/`

## Usage

The skill triggers automatically. Ask Claude to write a story, edit a scene, diagnose why something reads as AI, or coach you through a craft problem. It runs in four modes:

**Write** — Discovery, then architecture (including the Posture Board), then drafting with a built-in calibration check.

**Edit** — Reads your prose, identifies what works, strengthens what doesn't, and runs the Posture Board against it to diagnose machine-default patterns.

**Analyze** — Breaks down how a piece works: devices, rhythm, psychic distance, paragraph structure. Can diagnose AI tells using the StoryScope vocabulary.

**Coach** — Direct, specific guidance on craft problems. No platitudes.

## The research behind it

Built on findings from StoryScope (Russell et al. 2026), a large-scale analysis of ~61,000 stories comparing human-authored and AI-generated fiction across multiple models. The study found that narrative structure — not style — is the primary separating signal, and that Claude specifically exhibits the flattest event escalation, most uniform voice, and strongest preference for quiet endings of any model tested. The skill's nine Posture Board axes map directly to the measured structural differences.

## License

MIT
