# AI-CERTAIN

**Open infrastructure for AI containment, resilience, and democratic control**

> **No AI system should ever possess more power than an independent, auditable control layer can revoke.**

Frontier labs are openly warning that agentic AI will amplify cyber risk at global scale. Existing governance focuses on model behaviour; existing cybersecurity was not built for adaptive agents that plan, call tools, and move across networks. **AI-CERTAIN** proposes the missing control plane: machine-readable agent identity, capability manifests, policy enforcement, AI-aware gateways, provenance, behavioural threat signatures, and federated incident response—**outside** the model.

This repository is the **canonical technical home** for White Paper v0.1 (October 2026), proposed by Sachin Chitre / the RiskLine ecosystem. It is an **open protocol and reference-implementation effort**—not a proprietary product.

**We need builders.** Security researchers, systems engineers, protocol designers, SOC practitioners, academics, and public-interest technologists: Phase 1 is published so you can critique, fork, and help ship Phase 2.

## Why contribute now

- **Timely problem:** agent identity, runtime containment, and revocation are moving from research into urgent infrastructure.
- **Clear MVP path:** white paper ? reference **AICP gateway** ? network adapters ? AISIG test corpus ? federation.
- **Vendor-neutral by design:** compose with NIST agent-identity work, OWASP agentic security, and C2PA provenance—don’t replace them.
- **Capture-resistant governance:** multiple implementations, open specs, no single global kill-switch owner.

## Start here

| Document | Description |
|----------|-------------|
| [WHITEPAPER.md](./WHITEPAPER.md) | Full white paper (Markdown) |
| [docs/AI-CERTAIN_White_Paper_v0.1.pdf](./docs/AI-CERTAIN_White_Paper_v0.1.pdf) | Official PDF v0.1 |
| [THREAT-MODEL.md](./THREAT-MODEL.md) | Threat classes and assumptions |
| [ARCHITECTURE.md](./ARCHITECTURE.md) | Seven-layer reference architecture |
| [GOVERNANCE.md](./GOVERNANCE.md) | Open governance and capture resistance |
| [ROADMAP.md](./ROADMAP.md) | 2026–2031 conditional roadmap |
| [PROTOCOLS/](./PROTOCOLS/) | Draft protocols (AICP, AEP, ACP, AISIG, AIRP, AIRM) |
| [CONTRIBUTING.md](./CONTRIBUTING.md) | How to help (good first tasks) |

## Founding principle

**Intelligence may be powerful. Power must remain bounded, observable, attributable and revocable.**

## Project status

| Phase | Status |
|-------|--------|
| **1 — Specs & white paper** | ? In this repo |
| **2 — Reference AICP gateway** | ?? Next — *contributors welcome* |
| **3–8 — Network, sandbox, AISIG, federation, grid** | Planned — see [ROADMAP.md](./ROADMAP.md) |

Local preview of the landing page: serve `site/public/` (includes PDF download).

## Ways to help (pick one)

1. **Review the threat model** — open an issue with gaps or attack scenarios we missed.
2. **Harden a protocol draft** — AICP/ACP schemas, revocation semantics, AISIG examples in [`PROTOCOLS/`](./PROTOCOLS/).
3. **Prototype the gateway** — policy evaluation + signed evidence (Phase 2); discuss design in Issues first.
4. **Build testbed scenarios** — prompt injection, tool poisoning, credential escalation under `testbed/`.
5. **Translate / document** — clearer diagrams, deployment notes for personal vs enterprise nodes.

See [CONTRIBUTING.md](./CONTRIBUTING.md). Security reports: [SECURITY.md](./SECURITY.md).

## Topics & discoverability

GitHub topics for this repo (searchable): `ai-security`, `agentic-ai`, `ai-agents`, `cybersecurity`, `containment`, `zero-trust`, `threat-intelligence`, `provenance`, `open-source`, `protocol`, `owasp`, `nist`, `capability-based-security`, `incident-response`.

## License

Documentation and protocol drafts: **[CC BY 4.0](./LICENSE.md)**. Reference implementation code (Phase 2+) will ship under an OSI-approved license (expected Apache-2.0).

## Citation

```bibtex
@misc{aicertain2026,
  title        = {AI-CERTAIN: A Global Open Infrastructure for AI Containment, Resilience and Democratic Control},
  author       = {Chitre, Sachin},
  year         = {2026},
  month        = oct,
  note         = {White Paper v0.1},
  howpublished = {\url{https://github.com/new-world-coder/ai-certain}}
}
```

## Public messaging

> We are proposing an open infrastructure project—not launching another proprietary AI-security product.
