# Enterprise AI Architecture Blueprint

A vendor-neutral reference architecture for designing, governing, and operating enterprise systems that use AI as one capability among many.

The repository applies TOGAF as a pragmatic architecture method and ArchiMate as the primary modelling language. It is intended to grow incrementally through small, reviewable contributions.

## Purpose

The blueprint helps enterprise and solution architects:

- frame AI-enabled systems in business and architecture terms;
- connect stakeholder concerns to capabilities, requirements, controls, and implementation choices;
- describe reusable logical architecture and integration patterns;
- govern AI use without coupling the architecture to a specific vendor or model provider;
- maintain traceability from architecture intent to implementation and evidence.

## Working Principles

1. **Architecture first** — architecture intent, boundaries, ownership, and decisions are the durable source of truth.
2. **Vendor neutral** — products and providers are implementation choices, not the architecture itself.
3. **Pragmatic TOGAF** — use TOGAF discipline where it improves traceability and decision quality; avoid process theatre.
4. **ArchiMate for governed views** — use ArchiMate to explain motivation, strategy, business, application, technology, and migration concerns.
5. **Small, coherent changes** — each pull request should deliver one logical improvement.
6. **Human accountability** — AI may assist analysis and authoring, but accountable humans approve durable architecture decisions.
7. **No confidential context** — examples and models must remain generic and safe for public use.

## Repository Structure

- [`togaf/`](togaf/) — architecture method, deliverables, principles, vision, roadmap, and governance.
- [`archimate/`](archimate/) — governed viewpoints, modelling conventions, and exchange artefacts.
- [`reference-architecture/`](reference-architecture/) — logical, information, security, and integration architecture.
- [`patterns/`](patterns/) — reusable architecture patterns for common AI-enabled system concerns.
- [`controls/`](controls/) — architecture and operational controls with expected evidence.
- [`compliance/`](compliance/) — mappings from architecture concerns to external obligations and frameworks.
- [`templates/`](templates/) — reusable templates for architecture and governance work.

Each directory contains a README that defines its purpose, expected content, and contribution rules.

## Initial Scope

The first milestone establishes a consistent repository foundation only. Detailed models, patterns, controls, and regulatory mappings will be added incrementally after the structure and working conventions are stable.

## Contribution Model

Work should be issue-driven and delivered through pull requests. The implementer must not be the only reviewer of its own change. Durable architecture decisions belong in repository artefacts, not only in issue or pull-request discussion.

See [`AGENTS.md`](AGENTS.md) for AI-assisted repository working rules.

## Status

Early foundation phase. Content is intentionally minimal and will expand through focused increments.
