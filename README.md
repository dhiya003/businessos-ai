# BusinessOS AI / Genesis AI

This repository contains the AI intelligence layer for Genesis AI / AI Product Factory.

## Sprint 1D status

Sprint 1D is completed with the following engineering assets committed:

- CEO AI answer-source model
- AI Product Factory agent prompt contract
- Sprint 1D completion checklist
- Sprint 2 kickoff plan

## Repo structure

```text
docs/
  answer-sources.md
  sprint-1d-completion.md
  sprint-2-kickoff.md
prompts/
  ceo-ai-system.md
  product-factory-agent.md
```

## Operating principle

Genesis AI does not guess business actions. It answers from one of four source layers:

1. Project memory and user-approved strategy
2. Repository assets and workflow state
3. Connected tools and live business data
4. Model reasoning, clearly marked as recommendation when no source exists
