# AEP — AI Evidence and Provenance Protocol (draft v0.1)

## Purpose

Tamper-evident **evidence chains** for AI-derived actions and artefacts, composable with C2PA and existing provenance work.

## Record binding

A provenance record may bind:

- source and transformations
- model or agent identity
- tool invocations
- policy decision (allow/deny/step-up/quarantine)
- resulting artefact hash
- timestamp and signatures

## Design constraints

- Not universal surveillance or mandatory disclosure of private prompts
- Transportable through APIs and content pipelines where appropriate
- AI-origin metadata when origin materially affects trust, indexing, safety, audit, or legal accountability

## Next steps

JSON/CBOR schemas, signature suites, and interoperability tests with C2PA content credentials.
