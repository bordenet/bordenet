# Genesis: A Successful Experiment

> **Status**: Archived. Superseded by [DocForge AI](https://github.com/bordenet/docforge-ai).

Genesis was an experiment in deterministic AI-assisted development: could I maintain byte-for-byte consistency across 9 repositories using conformity tooling?

**The answer**: Yes, but the maintenance overhead compounds. A unified codebase with plugin architecture is simpler.

## What Genesis Proved

The 3-phase adversarial workflow produces better documents than single-pass generation:

1. **Claude drafts** from structured inputs
2. **Gemini critiques** on 5 scoring dimensions
3. **Claude synthesizes** the critique into a final version

In testing across 50+ documents, adversarial output scored 23% higher on peer review rubrics than single-pass generation.

## What Genesis Cost

| Metric | Value |
|--------|-------|
| Repositories | 9 |
| Commits to maintain consistency | 1,600+ |
| Divergent files caught by diff tools | 51 |
| PRs required per bug fix | 9 |

The conformity tooling worked. The overhead didn't scale.

## The Successor

[DocForge AI](https://github.com/bordenet/docforge-ai) keeps the adversarial workflow and drops the duplication:

- **One codebase** with plugin architecture
- **One test suite** (530+ tests, 84% coverage)
- **One PR** per bug fix

Same workflow. Zero propagation overhead.

**Try it**: [bordenet.github.io/docforge-ai](https://bordenet.github.io/docforge-ai/assistant/)

## Historical Reference

For those studying the architecture or maintaining existing Genesis projects:

| Resource | Purpose |
|----------|---------|
| [genesis](https://github.com/bordenet/genesis) | Framework and templates |
| [BACKGROUND.md](https://github.com/bordenet/genesis/blob/main/BACKGROUND.md) | Full experiment history |
| [ARCHITECTURE.md](https://github.com/bordenet/genesis/blob/main/ARCHITECTURE.md) | Paired assistant/validator model |

### Individual Projects (Archived)

| Project | Document Type |
|---------|---------------|
| [one-pager](https://github.com/bordenet/one-pager) | Executive summary |
| [pr-faq-assistant](https://github.com/bordenet/pr-faq-assistant) | Press release + FAQ |
| [product-requirements-assistant](https://github.com/bordenet/product-requirements-assistant) | PRD |
| [power-statement-assistant](https://github.com/bordenet/power-statement-assistant) | Achievement statements |
| [strategic-proposal](https://github.com/bordenet/strategic-proposal) | Initiative proposals |
| [architecture-decision-record](https://github.com/bordenet/architecture-decision-record) | ADR |
| [jd-assistant](https://github.com/bordenet/jd-assistant) | Job descriptions |
| [acceptance-criteria-assistant](https://github.com/bordenet/acceptance-criteria-assistant) | User story criteria |
| [business-justification-assistant](https://github.com/bordenet/business-justification-assistant) | ROI analysis |

All projects remain functional but receive no new features. Use DocForge AI for active development.

