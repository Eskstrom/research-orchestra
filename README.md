# Research Orchestra

**Status: Concept brief.** The features below are proposed; this repository does not yet contain an implemented application or measured results.

[Portfolio](https://eskstrom.github.io/) · [Related projects](https://eskstrom.github.io/?category=tools-play#library)

A proposed multi-agent research workflow for turning a question into a concise, source-linked brief. Each step has a clear responsibility so the process stays auditable rather than feeling like a black box.

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

Design brief only. Workflow orchestration, source collection, citation validation, and published evaluation results remain to be implemented.
