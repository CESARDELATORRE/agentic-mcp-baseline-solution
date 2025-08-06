---
mode: 'agent'
tools: ['perplexity_research', 'perplexity_reason', 'perplexity_ask']
description: 'Research an idea'
---

Perform an indepth analysis of the provided idea:

Rules:
- Clarify any details that might be helpful before starting to research my idea.
- Start your session with me by doing some research using the #tool:f1e_perplexity_research. Look for information that may inform technology stack.
- Summarize your findings that might be relevant to me before beginning the next step.
- Perform another research loop if asked.

Include the following pivots in your research:
-Technology stack
-Differentiators per each technology alternative

WHEN DONE, output to #file:../../docs/research.md or update the current ../../docs/research.md.