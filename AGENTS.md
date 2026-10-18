# Makerstown Superfrog ESP32 — AGENTS.md

## Project role
Public showcase and documentation for **Makerstown Superfrog Arcade Edition on ESP32-P4**, v1.0.0. It is **not** the private universal Makerstown Amiga Porting Tool repository.

## Operating model
- **ChatGPT:** project decisions, milestone documentation, review before publication.
- **Codex (if explicitly used in the future):** scoped repository changes only, with a concise report.
- Project-specific instructions, documented baselines and the current task take priority over general templates.
- Do not expand the project scope without an explicit decision.

## Baseline
- v1.0.0: FULL STORY and DIRECT GAME validated on ESP32-P4 (2026-10-18).
- Known issue: Frog sprite blinking/phase presentation; not fixed in v1.0.0.
- ESP32-S3: future separate port, **not** a validated target.

## Safety and IP constraints
- Never publish game ADF/IPF, Amiga ROMs, extracted stage2/loaders, unlicensed game assets, private engine source, credentials or private project ZIPs.
- Do not infer an open-source license or claim firmware availability from this showcase.
- Do not alter, reveal or mirror `Makerstown/amiga-porting-tool` (private) or the separate `Makerstown/amiga500-esp32` project.
- Stop before any source upload, binary upload, release attachment or change of repository visibility; request explicit review first.

## Existing structure
- `README.md` and `README.it.md`: public presentation.
- `docs/`: release notes and HUB draft.
- `media/`: approved preview artwork only.
- Existing structure always overrides general Makerstown templates. Do not rename or migrate folders just to satisfy a generic template.

## Mandatory stop and milestone reports
Before each public milestone, check that all tracked files are safe, known limitations are accurately stated, and no private media/source is present. Report the commit, what changed, what was validated on hardware and what remains pending.
