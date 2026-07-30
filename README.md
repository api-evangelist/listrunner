# Listrunner

Listrunner was a HIPAA-compliant clinical collaboration platform for hospital care teams — shared,
living patient lists covering sign-out/handoff, rounding, discharge coordination, and task
assignment, with EHR integration, audit logs, and an offline mode across web, iOS, and Android.

**Status: defunct.** Listrunner no longer operates as an independent product. Its brand domains
redirect to Commure, the healthcare-infrastructure company that merged with Athelas:

- `listrunner.health` → 301 → `listrunnerapp.com` → 307 → `commure.com` (probed 2026-07-19)
- Last archived standalone Listrunner homepage: 2021-06-04
- `listrunner.com` is an unrelated parked GoDaddy for-sale domain

**No API surface.** Listrunner never published a public API, developer portal, API reference,
SDK, CLI, or package. Probes found nothing on npm, PyPI, or GitHub, no `.well-known` documents,
and no developer paths across 361 archived URLs. This repo is retained as a historical health-tech
identity record and a pointer to the successor surface, not as an API provider.

Successor in this network: [`all/athelas`](../athelas/) (Athelas / Commure), which carries the
real FHIR and RPM API artifacts.

Backed by: creandum
