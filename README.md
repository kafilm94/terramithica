# Terramithica / *Shadows of the Veil: Awakening of the Emblematic*

This repository holds the novel manuscript, the story bible, and the full worldbuilding
canon for **TerraMythica**, the setting of *Shadows of the Veil: Awakening of the
Emblematic*, along with the reference/media material generated alongside it.

**Nothing from the original repository was deleted or moved.** The raw material
(`conversation-logs/`, `book-idea(2)/`, `images/`, and the loose root-level image file)
is preserved exactly as uploaded. Everything below is a **new, organized filing** of
that same material into topic-based folders, with a short frontmatter header on each
file noting exactly which original log(s) it was filed from — so you can always trace
a folder file back to its raw source.

## 📁 Directory Structure

```
.
├── manuscript/            # The actual novel — outline, drafted chapters, prose excerpts
│   ├── outline.md
│   ├── chapters/
│   └── excerpts/
├── story-bible/           # High-level story reference: summaries, themes, character roster, plot, open questions
├── worldbuilding/         # The TerraMythica canon, split by subject
│   ├── magic-system/          Emblems, power system/physics, Fractal Cognition
│   ├── characters/            Character design notes, personal arcs, individual profiles
│   ├── factions-organizations/ Order of the Emblematic, faction politics, secret societies
│   ├── geography-cartography/ Maps, spatial reference, regional geography
│   ├── culture-society/       Social strata, castes, festivals/taboos, calendars
│   ├── religion-cosmology/    Mythology, deities, cosmology
│   ├── creatures-bestiary/    Spiritwild, bestiary, the Nightmares
│   ├── language/               Tongues & scripts, dialect tables, the Language of Emotion
│   ├── history-timeline/      World-shaping events
│   ├── economy-technology/    Fiscal/economic systems
│   ├── artifacts-weapons/     Artifact & weapon concept compendium
│   └── transportation/        Flying caravans, ley-trains, memory ferries
├── media/
│   ├── images/  (see note below — original images stay in /images)
│   └── prompts/           Book-cover & character/illustration AI-art prompts
├── production/            Writing-process notes, script/adaptation material
├── other-projects/         Unrelated or tangential concepts that surfaced in the logs
│
├── conversation-logs/     ⬅ UNTOUCHED original raw ChatGPT logs (67 files)
├── book-idea(2)/          ⬅ UNTOUCHED original folder
├── images/                ⬅ UNTOUCHED original cover-art renders
└── imagesDALL·E .....webp ⬅ UNTOUCHED stray root-level file from the original upload
```

## How filing works

Every file created in the new folders starts with a frontmatter block like this:

```yaml
---
title: "The Order of the Emblematic"
tags: [faction, organization]
source_logs: [Log(11).md]
filed_on: "2026-07-27"
note: "Filed verbatim from original conversation-logs archive; originals untouched."
---
```

The body is the **full, verbatim content** of the referenced log(s) — nothing was
rewritten, trimmed, or summarized. This pass is a *filing/structuring* pass, not an
editorial rewrite. Editorial cleanup (removing chat back-and-forth filler, merging
duplicate passages, etc.) is a natural next step once you confirm the structure works
for you.

## Known duplicate logs (filed once, noted here)

A few raw logs are byte-for-byte (or near-identical) duplicates. Only one copy of each
was filed into the new structure; both originals remain untouched in `conversation-logs/`:

| Filed once as | Duplicate pair |
|---|---|
| `worldbuilding/magic-system/emblems.md` | `log(14).md` ≈ `log(15).md` |
| `worldbuilding/culture-society/cultural-textures.md` | `Log(24).md` = `Log(25).md` |
| `worldbuilding/transportation/transportation-networks.md` | `Log(37).md` = `Log(38).md` |
| `worldbuilding/culture-society/social-strata.md` | `Log(39).md` = `Log(40).md` |
| `worldbuilding/magic-system/fractal-cognition.md` | `Log(48).md` = `Log(49).md` |

## Other filing notes

- **`Log(23).mg`** had a non-standard `.mg` extension (should be `.md`). Content is
  about Luminara's political factions and the Crystal Verge clans — filed under
  `worldbuilding/factions-organizations/luminara-politics-crystal-verge.md`.
- **`Log(57).md`** is essentially empty (1 byte) in the original archive — nothing to file.
- The stray root file starting with `imagesDALL·E...` was left exactly where it was, and
  was also **copied** (not moved) into `images/` with a corrected filename so both
  cover-art renders are visible together — the original stray file is still untouched
  at the repo root.
- `other-projects/` holds three logs that are **not** TerraMythica material — a
  different novel concept ("Unveiling the Veil"), an unrelated sci-fi short ("The
  Faltering Grid"), and an off-topic technical question — kept separate so they don't
  pollute the TerraMythica canon.

## Suggested next steps

1. Skim `story-bible/overview.md` and `story-bible/character-roster.md` first — they're
   the best entry points into the whole project.
2. Where two logs cover the same topic from different angles (e.g. summaries, Emblems),
   consider merging them into one canonical file once you've reviewed both.
3. Decide whether `other-projects/` content stays in this repo or moves to its own.
