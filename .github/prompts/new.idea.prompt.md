---
mode: 'agent'
description: 'Create a project idea'
---

I want to define all the details for an agentic baseline/generic solution. My idea was attached in the prompt I sent you.

Let's join forces to make this idea into a simple, yet impactful proposal.

FIRST:
- Clarify any areas of my proposal that may need more details
- Suggest new requirements based on the functionality provided
- Consider edge cases that may not be included in my original proposal.
- Organize requirements logically, and break them down into units that would make sense as user stories.
- Raise any important high-level technical considerations, like platforms, languages, frameworks, and overall architecture details

NEXT:
- Iterate with me until I tell you I am satisfied.

FINALLY:
- Once I tell you I am ready, create a plan (or update an existing plan) in #file:../../docs/project-idea.md following its current structure, as a Markdown file:

```
## Summary

## Product Overview
### Core value proposition:
### Target audience:

## Value Proposition
### Key differentiators:

## Initial Requirements

## Functional Specifications


## Architecture options summary
### Architecture option 1: Local and using stdio MCP an inprocess agents
### Architecture option 2: Dockerized and using REST API MCP and remote agents
### Architecture option 3: Cloud-Native and using Kubernetes, REST API MCP and remote agents

## Technical Specifications per Option


## Risk Assessment
### Technical Risks

## Next Steps
### Discovery Phase
### Deliverables for Next Phase


## Contact Information
## Document Control
```

When you are done, output to #file:../../docs/project-idea.md.