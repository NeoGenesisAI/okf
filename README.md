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

## Source & License
All facts are sourced from public pages (https://neogenesis.app/llms-full.txt). No secrets or
internal content are included. Knowledge content is licensed **CC-BY-4.0** (see `LICENSE`).
