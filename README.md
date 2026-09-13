# Neo Genesis — Open Knowledge Format (OKF) Bundle

This repository is an [Open Knowledge Format (OKF) v0.1](https://github.com/GoogleCloudPlatform/knowledge-catalog/tree/main/okf)
bundle of **publicly available** knowledge about [Neo Genesis](https://neogenesis.app).

OKF (published by Google Cloud, 2026) represents knowledge as a directory of markdown files with
YAML frontmatter, designed to be consumable by AI agents and readable by humans. One file = one
concept; the file path is the concept ID; cross-links between files form the knowledge graph.

## Contents
- `index.md` — bundle root (progressive disclosure)
- `organization/` — company, founder, HIVE MIND pipeline, V-Score, governance, tech stack
- `sbus/` — the 11 live business units
- `datasets/` — 9 open datasets (CC-BY-4.0)
- `research/` — published research and operational assets
- `log.md` — change history
- `generate_okf_bundle.py` — reproducible generator (public sources only)

## Current public launch set (7)

The current public launch set contains seven live Neo Genesis surfaces. These links
use a scoped marker for this owned GitHub discovery source; the descriptions state
current capabilities and make no claim about traffic, popularity, income, or catalog size.

- [NeoGenesis hub](https://neogenesis.app?utm_source=github&utm_medium=owned&utm_campaign=web-sbu-20260913) — Public hub connecting six service destinations with searchable discovery.
- [KoreanLLM](https://koreanllm.org?utm_source=github&utm_medium=owned&utm_campaign=web-sbu-20260913) — LLM community for user reviews and task-based opinions.
- [DaysLeft](https://daysleft.io?utm_source=github&utm_medium=owned&utm_campaign=web-sbu-20260913) — Three-question result flow with image/JSON export and same-quiz friend comparison.
- [ToolPick](https://www.toolpick.dev?utm_source=github&utm_medium=owned&utm_campaign=web-sbu-20260913) — 27 executable tools currently exposed, with editing and workspace flows.
- [K-OTT taste test](https://kott.kr/en/taste?utm_source=github&utm_medium=owned&utm_campaign=web-sbu-20260913) — Six-question taste test with friend comparison and selective sharing.
- [UR WRONG](https://ur-wrong.com?utm_source=github&utm_medium=owned&utm_campaign=web-sbu-20260913) — Server-checked opinion flow with duplicate and change handling.
- [ReviewLab](https://review.neogenesis.app?utm_source=github&utm_medium=owned&utm_campaign=web-sbu-20260913) — Public product comparisons with source preservation and search, save, restore, and video checks.

## Source & License
All facts are sourced from public pages (https://neogenesis.app/llms-full.txt). No secrets or
internal content are included. Knowledge content is licensed **CC-BY-4.0** (see `LICENSE`).
