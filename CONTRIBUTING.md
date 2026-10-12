# Contributing to AI-CERTAIN

Thank you for helping build open AI containment infrastructure. Contributions of all sizes matter—especially careful critiques of the threat model and protocol drafts before we freeze Phase 2 APIs.

## Before you start

1. Read [WHITEPAPER.md](./WHITEPAPER.md), [THREAT-MODEL.md](./THREAT-MODEL.md), and [ARCHITECTURE.md](./ARCHITECTURE.md).
2. Skim [GOVERNANCE.md](./GOVERNANCE.md)—we optimize for vendor-neutral, capture-resistant controls.
3. Open an **issue** for substantial design changes before large pull requests.

## Good first contributions

| Area | Ideas |
|------|--------|
| Specs | Clarify AICP manifest fields; add YAML/JSON examples; note conflicts with existing standards |
| Threat model | New agent failure modes; maps to OWASP Agentic Top 10 |
| Architecture | Diagrams for personal / enterprise / edge deployment |
| Testbed | Scenario outlines under `testbed/` (injection, tool poisoning, cascade) |
| Docs | Fix ambiguity; improve README discoverability; translation notes |

## Protocol changes

Keep protocol edits in [`PROTOCOLS/`](./PROTOCOLS/) with a short “Status / Breaking changes” note at the top of the file. Prefer evidence-based threat descriptions; **do not** add political or ideological scoring to AISIG or reputation formats.

## Code (Phase 2+)

Reference implementations should document measurable properties where possible: policy latency, revocation time, evidence completeness, and false-positive behaviour under defined `testbed/` scenarios.

## Pull request checklist

- [ ] Linked to an issue (or explained why not)
- [ ] Scope is focused (one concern per PR when possible)
- [ ] Docs updated if behaviour or APIs change
- [ ] No secrets, proprietary model weights, or private incident data

## Code of conduct

Participation is expected to be professional, inclusive, and focused on deployable security properties. Harassment and bad-faith political scoring of contributors or models are out of scope for this project.

## Questions

Open a GitHub Issue for specification clarifications. Enable Discussions on the repo if the community wants longer design threads.
