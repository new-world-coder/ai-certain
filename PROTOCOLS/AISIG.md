# AISIG — AI Behaviour Signature Format (draft v0.1)

## Purpose

Machine-readable, versioned, **signed** descriptions of observable agent behaviour sequences for federated threat intelligence.

## Examples

- Repeated privilege escalation
- Unexpected network discovery
- Credential probing
- Attempted policy modification
- Anomalous agent-to-agent propagation

## Non-goals

- Universal blacklist of models or political opinions
- Ideological conformity scoring

## Exchange

Organisations share signatures and confidence through federated exchange (see AIRM). Raw private data remains local unless explicitly shared.

## Next steps

Signature schema, test corpus in `testbed/`, and registry design in `threat-intel/`.
