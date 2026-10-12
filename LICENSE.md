# Licensing

AI-CERTAIN uses **standard OSI / Creative Commons licenses only**. No custom license.

| Material | License | Why |
|----------|---------|-----|
| **Software & reference implementations** (gateway, adapters, SDKs, tooling) | [Apache License 2.0](./LICENSE) | Permissive enough for multiple independent (including commercial) implementations; includes an **explicit patent grant**—important for security infrastructure. Preferable to MIT for this project. |
| **Documentation, white paper, and protocol drafts** (`WHITEPAPER.md`, `docs/`, `PROTOCOLS/`, architecture/threat-model/governance prose) | [CC BY 4.0](./LICENSES/CC-BY-4.0.txt) | Normal for papers and specs: free to share and adapt with attribution. |

## What we considered

- **MIT** — Fine for adoption, but weaker patent language than Apache for an identity/capability/control-plane stack.
- **GNU GPL / AGPL** — Strong copyleft can force derivatives to stay open, but it often **slows enterprise and multi-vendor adoption** of a shared protocol ecosystem. Capture resistance for AI-CERTAIN is handled in [GOVERNANCE.md](./GOVERNANCE.md), not by copyleft.
- **Custom license** — **Not recommended.** Companies and many contributors will not adopt unfamiliar terms; GitHub/OSI discoverability suffers.

## SPDX identifiers

- Code: `Apache-2.0`
- Docs/specs: `CC-BY-4.0`

Copyright (c) 2026 Sachin Chitre and AI-CERTAIN contributors.
