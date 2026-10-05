# AICP — AI Identity and Capability Protocol (draft v0.1)

**Status:** Draft for public comment. Names are provisional.

## Purpose

Machine-readable **agent identity** and **capability manifests** that enforcement points can verify and compare against observed behaviour.

## Core objects

- `agent_id` — stable identifier
- `publisher` — accountable entity (e.g. organisation domain)
- `purpose` — declared operational scope
- `model_ref` — model or agent package identifier
- `capabilities` — network, data read/write, actions
- `restrictions` — hard denies (shell, arbitrary network, credential access, self-replication, policy modification, autonomous deployment)

## Example manifest

```yaml
agent_id: hospital-agent-042
publisher: example.org
purpose: appointment-scheduling
model_ref: model-identifier
capabilities:
  network: [api.hospital.example]
  data_read: [appointments]
  data_write: [appointments]
  actions: [create_appointment, cancel_appointment]
restrictions:
  arbitrary_network: false
  shell_access: false
  credential_access: false
  self_replication: false
  policy_modification: false
  autonomous_deployment: false
```

## Security properties

Use established cryptographic identity, signed assertions, short-lived credentials, policy versioning, replay protection, timestamps, nonces, and explicit audit semantics—**no novel cryptography**.

## Next steps

Define wire format, revocation lists, and conformance tests in `conformance/`.
