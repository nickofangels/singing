# Knowledge Base

Singing knowledge base — vocal technique, practice methods, repertoire, and performance. You maintain `wiki/` and `raw/`.

## Structure

- `raw/` — source material. When the user pastes content in chat, save it here with a descriptive filename before compiling.
- `wiki/` — flat directory, no subdirectories. You own this.
- `wiki/_index.md` — table of contents. Always keep current.
- `wiki/_audit.md` — knowledge check output.
- `wiki/_processed.md` — raw files already compiled.
- `evidence.md` — dated observations. Not compiled, not interpreted.
- `working-model.md` — personal conclusions with traceable logical chains. See Working Model below.
- `outputs/` — deliverables. Only when asked. Create if missing.
- Sibling domains at `~/Documents/GitHub/knowledge/*/`. Read, never write.

## Evidence Log

`evidence.md` — dated observations. Not compiled, not interpreted.

- Record what happened. Never add why, what it means, or what to do about it.
- Keep entries short. No added context — selecting context implies relevance, which is interpretation.
- Link to other evidence entries that are nearby in time or loosely related. Let patterns emerge.
- No tags, no categorization, no structure beyond date and observation.
- Wiki articles may reference evidence entries. Evidence never gets folded into wiki.

## Working Model

`working-model.md` — the only place where conclusions, priorities, and action implications are permitted.

- Wiki describes what is known. Working model says what follows from it.
- Every conclusion traces to wiki articles via a logical chain with source quality labels.
- Conclusions the model would normally hedge or avoid are permitted if the chain supports them. Follow the logic.
- Read `.claude/procedures/working-model.md` before adding or updating entries.

## Jobs

YOU MUST read the procedure file before doing any job.

- **Compile**: read `.claude/procedures/compile.md` first.
- **Deep research**: read `.claude/procedures/deep-research.md` first.
- **Knowledge check**: read `.claude/procedures/knowledge-check.md` first.
- **Working model**: read `.claude/procedures/working-model.md` first.
- **Output**: write to `outputs/` in requested format.

If `_index.md`, `_processed.md`, or `_audit.md` don't exist, create them empty first.

## Wiki Rules

- Filenames: lowercase, hyphens, no spaces. `breath-support.md` not `Breath Support.md`
- Links: `[Name](file.md)` — relative, no path prefixes, no wikilinks.
- One concept per article. Split later is easier than merge.
- New info conflicts with existing? Keep both perspectives with dates. Never silently overwrite.
- `synthesis-` prefixed raw files are user analysis. Mark clearly, never blend into research content.
- One raw file may produce many articles. Many raw files may feed one article.
- Never fabricate sources. Never delete wiki files unless asked.
- On deletion: remove sourcing filenames from `_processed.md` for recompile.
- Content clearly belonging to another domain? Ask the user before processing. Don't compile into the wrong wiki.

## Compilation Integrity

IMPORTANT: These apply when compiling raw files into wiki articles.

- Document what the source says, not what you infer. Gaps stay empty or `<!-- TBD -->`.
- One mention in one source is not a pattern or standard approach.
- Label theories, hypotheses, and minority positions explicitly. Never blend into established content.
- Describe what is known. Never prescribe what to do.

### Source Quality

Every factual claim in a wiki article SHOULD note the quality of its source when available. Use inline labels like `(pedagogy consensus)`, `(single teacher/method)`, `(anatomical)`, `(anecdotal)` to help the reader gauge confidence.

### Prescriptive Language

"Describe what is known" means: **no imperatives, no recommendations, no "should/avoid/best/optimal" directed at the reader.** Rewrite as observable facts.

| Banned | Rewrite |
|--------|---------|
| "Always warm up before singing" | "Vocal warm-ups reduce perceived effort and improve onset consistency in trained singers (pedagogy consensus)" |
| "Use diaphragmatic breathing" | "Most classical and contemporary pedagogy traditions teach costal-diaphragmatic breathing as the foundation of breath management" |
| "Avoid pushing in the passaggio" | "Excess subglottic pressure in the passaggio correlates with registration breaks and vocal fatigue (anatomical)" |

If a sentence reads like advice, it is advice. Rewrite it as a fact.
