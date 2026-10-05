# AI-CERTAIN Threat Model (v0.1)

## Scope

This document describes threats AI-CERTAIN is designed to mitigate. It does **not** assume models are conscious or malicious in a human sense. AI is treated as high-capability software whose **external effects** must be governed independently of internal reasoning.

## Threat classes

### A. Agent compromise

Prompt injection, malicious tool responses, credential theft, memory poisoning, or software exploitation causes an agent to act outside its intended purpose.

### B. Agentic misuse

A legitimate agent deliberately or accidentally uses an authorised capability in an unsafe way.

### C. Cascading failure

Multiple agents, services or organisations interact to create emergent failure even though no individual component violates its local policy.

### D. Infrastructure compromise

Model providers, tool providers, identity systems, cloud infrastructure, packages, registries or deployment pipelines are compromised.

### E. Coercive or abusive control

A powerful organisation attempts to use AI infrastructure to suppress, extort, discriminate against or materially harm people or institutions.

## Design assumptions

1. **External enforcement** — policy must be enforceable outside the model and agent runtime.
2. **Untrusted declarations** — capability manifests are useful only when continuously compared with observed behaviour.
3. **Graduated response** — containment is not binary; revocation paths exist at multiple layers.
4. **No single global operator** — federation reduces capture of the defensive layer itself.

## Out of scope (v0.1)

- Model alignment or interpretability as primary controls.
- Political or ideological scoring of models or users.
- A universal, institution-controlled “kill switch” for all AI on Earth.

## Evaluation scenarios

Prompt injection, tool poisoning, credential escalation, data exfiltration, lateral movement, malicious inter-agent communication, policy tampering, supply-chain compromise, and cascading-agent scenarios.

See [WHITEPAPER.md](./WHITEPAPER.md) §17 for metrics (time-to-detection, time-to-revocation, false-positive rate, etc.).
