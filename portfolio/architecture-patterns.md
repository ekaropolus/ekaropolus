# Architecture Patterns

This page describes reusable technical patterns that appear across the portfolio.

## Evidence-to-Decision Pipeline

Used in scientific intelligence, public-sector research, proposal work, and
institutional decision systems.

```text
source collection
  -> source ledger
  -> raw evidence layer
  -> normalized entities
  -> enriched analytical layer
  -> review workspace
  -> decision brief / dashboard / product surface
```

Core objects:

- `source_item`: document, file, URL, email, spreadsheet, dataset, page, or
  interview note.
- `source_claim`: claim extracted from a source with provenance.
- `entity`: person, institution, project, technology, place, opportunity, or
  capability.
- `relationship`: typed link between entities.
- `evidence_bundle`: reusable package of sources, claims, entities, notes, and
  confidence.
- `decision_output`: memo, concept note, dashboard, case study, proposal, or
  action list.

Design rules:

- Every important claim should point back to a source.
- AI can synthesize, but it must preserve uncertainty and provenance.
- Raw evidence should not be overwritten by enriched interpretation.
- Public exports should be derived from private/source-grounded layers.

## Local Digital Twin Stack

Used in Polisplexity and city-facing research.

```text
city source data
  -> base geometry and public-data baseline
  -> semantic city layer
  -> service-specific add-on pack
  -> scenario / simulation / AI workflow
  -> decision surface
```

Core layers:

- `base_twin`: territory, roads, buildings, public spaces, green-blue structure,
  reference boundaries.
- `logical_twin`: data bundles, viewer state, constraints, workflows, and
  city-specific payloads.
- `semantic_seed`: civic anchors, mobility structures, daily-economy
  indicators, services, and meaning layers.
- `add_on_pack`: waste, planning, energy, resilience, people-flow, environment,
  or institutional operations.
- `decision_surface`: map, 3D/XR fragment, dashboard, report, or guided AI
  workflow.

Technical concerns:

- geospatial normalization;
- source and license tracking;
- support-unit consistency;
- semantic interoperability;
- scenario reproducibility;
- public/private data boundaries;
- human-readable outputs for non-technical teams.

## Socio-Physical Model Pattern

Used when infrastructure decisions depend on human behavior, service pressure,
institutional rules, and spatial constraints.

Typical model components:

- physical network: roads, buildings, assets, service zones;
- actors: residents, workers, visitors, public servants, operators;
- service logic: routes, schedules, collection rules, planning rules, capacity;
- pressure indicators: demand, risk, delay, cost, exposure, coverage;
- interventions: route changes, asset placement, schedule changes, policy
  changes, communication strategies;
- evaluation: operational benefit, equity, cost, risk, resilience, stakeholder
  impact.

This pattern is relevant to waste, housing, planning, mobility, emergency
response, energy, and institutional operations.

## Research Software Pattern

Used in `urban-sami` and reproducible technical research.

```text
theory object
  -> equation / method map
  -> executable script
  -> data contract
  -> generated report
  -> parity / regression check
```

Design rules:

- separate production app data from research replay;
- keep input manifests explicit;
- make support units visible;
- version generated outputs;
- include golden tests or parity checks;
- document the mapping from manuscript to code.

## AI-Assisted Research Operations

Used in Hadox, proposal work, sector research, and internal operating memory.

```text
session / source / document
  -> extracted actions and claims
  -> editorial block
  -> project or case classification
  -> public/private sensitivity check
  -> reusable portfolio / CRM / report output
```

This is the bridge between internal research operations and the GitHub
portfolio. Operating records can identify candidate case studies, but
publication should pass through a human editorial review and the client-ID
protocol.
