# ACP — AI Capability Policy Protocol (draft v0.1)

## Purpose

Standardise **policy evaluation** at enforcement points (AI capability firewall / gateway).

## Decision outputs

- `ALLOW`
- `DENY`
- `STEP-UP` (require additional human or institutional authority)
- `QUARANTINE`

## Inputs (non-exhaustive)

Agent identity, declared purpose, requested capability, target, data classification, transaction value, reversibility, user authority, environment, reputation, current threat signals (e.g. AISIG matches).

## Principle

A high-risk action must not become safe because an LLM produced a persuasive natural-language justification.

## Next steps

Policy language profile, obligation mapping to OWASP agent control themes, and latency benchmarks.
