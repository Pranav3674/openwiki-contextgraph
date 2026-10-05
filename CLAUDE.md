# Instructions for Claude Code

This project is a two-stage proof of concept that tests LangChain's OpenWiki CLI for building and
visualizing (1) a semantic knowledge graph of mock bank documents and (2) a context graph (agent memory)
for a LangChain Q&A agent.

- Follow `BUILD_SPEC.md`. It is the source of truth for architecture, file layout, APIs and milestones.
- The target machine is **Windows**; write PowerShell scripts and test process handling on Windows.
- Use OpenWiki for both graph generation and both visualizations; do not swap in another graph tool.
- The mock data in `data/` is final. Do not regenerate it unless asked (`generators/` can rebuild it).
- `tools/convert_corpus.py` is working; reuse it.
- Re-verify the items listed in BUILD_SPEC.md Section 10 on the installed OpenWiki version before
  relying on them, and record findings in `docs/openwiki-findings.md`.
- Work milestone by milestone (Section 12) and run each one before starting the next.
