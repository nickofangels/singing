# Compile Procedure

1. Read `wiki/_processed.md`. List `raw/` files. New = not in `_processed.md`.
2. No new files? Say so, stop.
3. Read new raw files. Read `wiki/_index.md` and all existing wiki articles.
4. For each concept in the new raw:
   - Exists in wiki? Update. Contradicts? Keep both with dates/sources.
   - New concept? Create article using template below.
5. `synthesis-` files are my analysis. Integrate under a marked section ("My Analysis" or "Notes") in relevant articles. If no relevant article exists, create one.
6. **Post-pass** — re-read every article you just wrote or modified. For each one:
   - Any sentence that reads like advice? Rewrite as fact.
   - Any single-source claim presented as consensus?
   - Any hedge words doing the work of a source label? ("likely", "may", "appears to" — replace with the source quality note)
7. Update `wiki/_index.md`. Append processed filenames to `wiki/_processed.md` (one filename per line, no bullets, no `raw/` prefix).
8. Tell me what changed.
9. Ask if I want to commit and push. Commit and push within this domain only — the parent repo's submodule pointer is updated by the daily auto-commit script.

## Article Template

    ---
    title: Article Title
    created: YYYY-MM-DD
    updated: YYYY-MM-DD
    sources:
      - raw/source-file.md
    ---

    One-sentence summary.

    ## Overview
    ## Details
    ## Open Questions
    ## Related

    - [Article](article.md) — why related

Sources field uses `raw/` prefix — this is the only place path prefixes are used.

## Index Line Format

    - [Article Title](filename.md) — one-sentence description
