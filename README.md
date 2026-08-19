# [PQ] Terra Indomita Chinese Localization

*Steam Workshop:* [Main Version](https://steamcommunity.com/sharedfiles/filedetails/?id=3766505458) | [Backup Mirror](https://steamcommunity.com/sharedfiles/filedetails/?id=3784985340)

---

## Language

[![EN](https://img.shields.io/badge/lang-English-blue)](README.md)
[![ZH](https://img.shields.io/badge/lang-简体中文-red)](README.zh.md)

---

## About

This is a Simplified Chinese localization patch for the Imperator: Rome overhaul mod **Terra Indomita**.

The patch is based on Terra Indomita's current text and cross-checks existing community Chinese localizations where suitable, including Imperator Invictus Chinese localization, TEOW-related Chinese text, and fixes from player reports.

Remaining gaps were drafted with assistance from large language models such as DeepSeek / GPT, then checked for formatting, context, terminology, and in-game display issues.

## Loading Screens

The patch ships with four Chinese-themed loading screens drawn from key historical scenes around the unification of China:

| Scene | File |
|---|---|
| Jing Ke's Assassination Attempt | `gfx/loadingscreens/load_10.dds` |
| The Grand Ceremony of Qin | `gfx/loadingscreens/load_11.dds` |
| The Feast at Hong Gate | `gfx/loadingscreens/load_12.dds` |
| Zhang Qian's Departure from Chang'an | `gfx/loadingscreens/load_13.dds` |

They rotate together with Terra Indomita's and the vanilla loading screens, overwriting nothing. The images are 1920×1080 DXT1 DDS textures; replace these files directly if you want your own art.

## Installation

Steam Workshop main version:

https://steamcommunity.com/sharedfiles/filedetails/?id=3766505458

Backup mirror:

https://steamcommunity.com/sharedfiles/filedetails/?id=3784985340

You may subscribe to both the main version and the backup mirror, but only enable one of them in your playset. Normally use the main version; switch to the backup mirror only if the main Workshop item is temporarily unavailable due to Steam automated review.

## Repository Layout

- `mod/`: the actual mod files, suitable for copying into the local Imperator: Rome mod directory.
- `workshop/`: Steam Workshop titles, descriptions, and update-note drafts.
- `docs/loading_tips.md`: notes on the newly added loading tips, selection standards, and sources. This document is intentionally kept in Chinese.
- `CHANGELOG.md`: brief update log.

## Manual Installation

Copy the `mod/` folder to:

```text
Documents\Paradox Interactive\Imperator\mod\Terra_Indomita_Chinese_Patch
```

Then place the launcher `.mod` descriptor file in the same `mod` directory. In most cases, using the Steam Workshop version is recommended.

## Quality Notice

This is an AI-assisted localization with manual review, not a guaranteed final-quality translation. Event chains, mission trees, proper names, ancient institutions, and regional context may still contain mistranslations, mismatches, inconsistent style, or display issues.

Reports are welcome, preferably with the country, event, mission, screenshot location, or localization key.
