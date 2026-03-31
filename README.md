# DavidSan

`DavidSan` is a `Phi-4`-based personal narrative agent designed to turn scattered professional context into clearer, stronger, and more presentable positioning without exposing private data.

This repository is the public-facing version of the project: a clean technical foundation, early package structure, tests, documentation, and contribution scaffolding for building in the open.

## Why This Project Exists

Most AI writing tools help people write faster.

Far fewer help people represent themselves better.

`DavidSan` explores a different direction: an assistant that helps a person articulate what they do, how they think, and why they create value, while staying privacy-aware by design.

## What Problem It Tries To Solve

This project is built around a practical gap:

- people often have strong experience but weak positioning
- valuable context is usually fragmented across notes, drafts, bios, and conversations
- existing tools often optimize for generic output rather than authentic representation
- personal AI workflows can easily become privacy leaks if they depend on exposing raw context

`DavidSan` is meant to help transform context into usable professional narrative with more clarity and less overexposure.

## Recruiter-Oriented Framing

For recruiters, hiring managers, and technical reviewers, this repository shows more than a prototype idea.

It demonstrates:

- product thinking around a concrete user problem
- practical interest in privacy-aware AI workflows
- early system design around an LLM-based assistant
- willingness to publish work-in-progress transparently
- the ability to structure a project so it can grow into a usable product

Even at an early stage, the repo communicates how I think about AI tooling: not just generation, but representation, control, and trust.

## Current Scope

The public repo currently includes:

- a minimal Python package in `src/davidsan`
- reproducible project setup in `pyproject.toml`
- smoke tests for a clean baseline
- folders prepared for prompts, examples, scripts, configs, and docs
- contribution and community files for open collaboration

This is not the full agent yet. It is the public, reviewable foundation of the project.

## Core Direction

`DavidSan` is being shaped as an assistant that:

- helps express a person's value more clearly
- uses `Phi-4` as its initial generation and reformulation engine
- relies on intentionally selected context instead of indiscriminate data ingestion
- treats privacy as a design constraint, not an afterthought
- can evolve into a transparent, auditable personal AI workflow

## What Is Public And What Is Not

This repository is intentionally selective.

Public:

- project structure
- package code
- tests
- public documentation
- non-sensitive prompts and configuration patterns
- roadmap direction and open design thinking

Not public:

- real personal data
- private conversations or identifiable histories
- secrets, tokens, or `.env` files
- local usage configuration tied to a personal workflow
- any memory layer or operating context that would expose sensitive information

## Repository Layout

| Folder | Purpose |
|---|---|
| `src/` | Core package source |
| `tests/` | Baseline validation |
| `docs/` | Technical and product notes |
| `scripts/` | Project utilities |
| `prompts/` | Prompt templates and experiments |
| `configs/` | Safe public configuration |
| `examples/` | Future anonymized demos |

## Run Locally

```bash
python3.12 -m venv .venv
source .venv/bin/activate
pip install -e ".[dev]"
pytest
```

## Why It Matters As A Public Project

This repo is not meant to be performative open source.

It is meant to show:

- a real project with a specific use case
- a privacy-aware AI product direction
- a technical foundation that can be inspected and extended
- an honest early-stage build rather than a polished but shallow demo

That makes it useful both as a community-facing repository and as a signal of technical/product capability.

## Current Status

Today, the public version includes:

- package scaffold
- initial test coverage
- public documentation
- contribution standards
- basic architecture notes

Next logical steps:

- add real assistant modules
- define input and output contracts
- include safe prompt examples
- expand the `Phi-4` integration path
- add a lightweight privacy and review layer

## Open Roadmap

Feedback is especially welcome on:

- agent flow design
- prompt structure and evaluation
- privacy boundaries and sanitization
- product positioning for professional storytelling
- packaging this into a more reusable assistant workflow

## Community

Suggestions, issues, and pull requests are welcome.

Please review [CONTRIBUTING.md](CONTRIBUTING.md), [CODE_OF_CONDUCT.md](CODE_OF_CONDUCT.md), and [SECURITY.md](SECURITY.md) before contributing.

## License

Released under the MIT License. See [LICENSE](LICENSE).
