# AIRP — AI Incident and Revocation Protocol (draft v0.1)

## Purpose

Graduated **containment and revocation** with externally enforceable, logged emergency controls.

## Quarantine levels

| Level | Action |
|-------|--------|
| 0 | Throttle compute, network, or tool calls |
| 1 | Revoke individual credentials or capabilities |
| 2 | Isolate agent in restricted sandbox |
| 3 | Sever external network and service access |
| 4 | Suspend workload or underlying compute allocation |

## Principle

“Kill switch” means a **family** of independently scoped revocation mechanisms—not one institution’s universal button.

## Next steps

Revocation propagation, incident correlation with AEP evidence, and SOC integration patterns.
