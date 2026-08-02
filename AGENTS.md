# Repository Working Rules

This repository is architecture-first and documentation-first.

## Scope

- Keep all content vendor-neutral and suitable for a public repository.
- Do not introduce confidential names, internal product references, customer details, private hosting information, secrets, or operational specifics.
- Treat repository artefacts as the durable source of architecture intent; issue and pull-request discussions are supporting context only.
- Prefer small, coherent changes over broad rewrites.

## Architecture Discipline

- Use TOGAF pragmatically to maintain traceability from stakeholder concerns to architecture outcomes, decisions, roadmap, and governance.
- Use ArchiMate as the primary language for governed architecture views.
- Keep logical architecture separate from product or vendor realization.
- Record durable decisions in repository artefacts rather than only in comments.

## AI-Assisted Work

- AI may assist research, analysis, drafting, modelling, and review.
- AI-generated content must be reviewed for correctness, consistency, confidentiality, and licensing before acceptance.
- AI does not approve architecture decisions or its own changes.
- The implementer of a change must not be the only reviewer of that change.
- Use focused prompts and only the repository context required for the task.

## Repository Workflow

- Use issues to frame meaningful work and pull requests to deliver reviewable changes.
- Keep each pull request focused on one logical outcome.
- State scope, assumptions, validation performed, and known gaps.
- Do not commit directly to the default branch once branch protection and the contribution workflow are established.

## Content Quality

- Use concise, declarative language.
- Keep terminology consistent across directories.
- Link related artefacts instead of duplicating stable rules.
- Every directory must contain a README that explains its purpose, expected content, and boundaries.
- Do not create empty placeholder documents without a defined near-term purpose.
