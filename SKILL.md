---
name: de-ai-knowledge
description: "English-focused knowledge base of AI writing tells, evidence notes, and detection checklist. Use when diagnosing AI flavor in drafts, reviewing academic papers or narratives, or needing reference lists and principles for humanizing prose."
type: knowledge
lifecycle: active
---

# De-AI Knowledge — Reference Base for Removing AI Flavor

A pure knowledge skill. Provides diagnostic lists, principles, and examples for identifying and reducing AI tells in writing. Load the relevant reference when reviewing or rewriting.

Primarily useful for academic papers and narrative in English. Chinese coverage is minimal and secondary.

## When to Load

- User asks to check for AI flavor / AI tells / 去 AI 味.
- Draft feels machine-generated and needs diagnosis before rewrite.
- Need concrete alternatives for common AI phrases.
- Comparing English vs Chinese patterns.
- Reviewing academic or narrative text for machine signals.

## How to Use

1. Identify the language and genre of the text.
2. Load the matching reference:
   - English tells → `references/english-ai-tells.md`
   - Detection checklist → `references/detection-checklist.md`
   - Evidence basis → `references/evidence-basis.md`
   - Core principles → `references/principles.md`
   - Examples → `references/examples.md`
   - Chinese (secondary) → `references/chinese-ai-tells.md`
3. Scan for clustered patterns only. Single natural occurrences are not automatic flags.
4. Apply principles: information conservation, minimal change, human interval (not anti-AI extremes).
5. Prefer genre-appropriate fixes (precision for papers, showing for stories).

## Available References

| File | Contents |
|------|----------|
| `references/english-ai-tells.md` | English lexical and structural tells with evidence levels and alternatives |
| `references/detection-checklist.md` | Step-by-step English detection checklist and quick scoring |
| `references/evidence-basis.md` | Evidence levels, sources, and limitations |
| `references/principles.md` | Information conservation, minimal change, human interval, genre notes |
| `references/examples.md` | Before/after pairs for general, academic, and narrative |
| `references/chinese-ai-tells.md` | Minimal Chinese reference (secondary) |

## Notes

- This skill does not prescribe a new style. It supplies diagnostic knowledge.
- For active rewriting workflows, pair with a workflow skill such as humanize-writing.
- Update references when new high-frequency tells are observed.
