# Publication strategy (from project planning)

This release implements **Phase 1** of the minimum viable open-source project: publish threat model, architecture, protocol drafts, governance model, and white paper.

## Canonical home (implemented here)

- Full Phase 1 tree is ready in this workspace: Markdown specifications and PDF in `docs/`.
- The public GitHub repository **`ai-certain`** is intended to be the **source of truth**, not the PDF alone.

## External publish attempt (2026-10-05)

Automated browser publish was attempted. **Nothing was created on GitHub or Zenodo.**

| Target | Result | Blocker |
|--------|--------|---------|
| GitHub signup / new repo | Failed | IP/network restriction: “Access is temporarily restricted” (unusual activity); no existing session |
| Zenodo via GitHub OAuth | Failed | Same GitHub restriction |
| Zenodo via ORCID / email | Failed | Needs verifiable human email / existing ORCID |

**Status update (2026-10-12):** Public repo exists at https://github.com/new-world-coder/ai-certain. Content is prepared to push; GitHub API description/topics metadata is documented in [GITHUB_META.md](./GITHUB_META.md). Push requires a GitHub credential in this environment (`gh auth login` or `GH_TOKEN` with `repo` scope).

## Secondary channels (engagement, not v0.1 upload targets)

| Channel | Role |
|---------|------|
| OWASP GenAI Security Project | Agentic security & control standards alignment |
| NIST / NCCoE ecosystem | Contribution to agent identity / authorization discussion (not endorsement) |
| IETF | Future protocol standardisation |
| arXiv | Later, with implementation and evaluation |
| ACM / IEEE | Later, with empirical results |
| C2PA community | Provenance / labelling interoperability |
| LinkedIn / RiskLine | **Distribution** — announce open infrastructure; link to GitHub |

## Public messaging

> We are proposing an open infrastructure project—not launching another proprietary AI-security product.

Avoid public framing as an “anti-counterterrorism framework”; prefer **AI containment, resilience and democratic control**.
