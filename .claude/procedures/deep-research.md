# Deep Research Procedure

Triggered when the user asks for a deep dive, research session, or investigation into a topic.

1. Run the research (web search, deep research skill, etc.). Gather findings.
2. Save the full research output to `raw/` with a descriptive filename before any compilation. This is the source of record — conversation text is not durable.
3. When saving to raw: preserve the research output's structure and detail. Do not summarize or editorialize. Include study details, numbers, and methodology notes. The raw file is the evidence; the wiki is the interpretation layer.
4. Run the standard compile procedure (`.claude/procedures/compile.md`). The raw file is now a source like any other.
5. The compile post-pass is especially important after deep research — the research skill tends to produce confident-sounding prose that blurs data and synthesis. Scrutinize every claim.

## What Deep Research Produces vs. What the Wiki Needs

| Research output | Wiki treatment |
|----------------|---------------|
| Direct study findings with numbers | Note source quality inline |
| "This suggests..." / "The implication is..." | Extract the mechanism or inference, label it |
| "Experts recommend..." | Who? One teacher = anecdotal. Widespread pedagogy = consensus. Don't echo authority without counting sources. |
| Reasoning chains combining multiple findings | Present the chain explicitly so the reader can evaluate |
| Practical exercises or technique instructions | Rewrite as facts about what methods exist and what their reported effects are. Never as instructions. |
