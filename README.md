# Research Orchestra

A multi-agent research workflow that turns a question into a concise, source-linked brief. Each step has a clear responsibility so the process stays auditable rather than feeling like a black box.

## Workflow

```text
Question → research plan → source collection → evidence notes → synthesis → cited brief
```

## Agent roles

- **Planner** — frames the question and identifies evidence needed.
- **Researcher** — gathers relevant, credible sources.
- **Analyst** — extracts claims, caveats, and supporting evidence.
- **Writer** — produces a concise brief with citations.
- **Reviewer** — checks that conclusions are supported and uncertainties are visible.

## Design principles

- Cite sources close to every meaningful claim.
- Separate gathering, reasoning, and writing for easier inspection.
- Prefer a transparent limitation over an unsupported answer.

## Roadmap

1. Implement the orchestrated workflow locally.
2. Add structured source notes and a citation validator.
3. Publish example briefs and evaluation results.

## Status

Portfolio project in active design, focused first on transparent research traces and citation quality.