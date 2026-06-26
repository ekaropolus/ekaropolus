# Scientific Intelligence and Evidence-to-Decision Systems

## Status

Current core capability.

## What it solves

Research, public-sector, and innovation work often depends on scattered evidence:
papers, PDFs, datasets, forms, spreadsheets, websites, validated relationship
records, repositories, and expert memory. This capability turns that fragmented
material into structured intelligence that can support decisions.

## Technical thesis

The evidence base should outlive the report. A concept note, dashboard, memo, or
proposal should be generated from a source-grounded layer that can be inspected,
updated, corrected, and reused.

## Pipeline

```text
sources
  -> source ledger
  -> extraction / parsing
  -> raw evidence layer
  -> normalized entities
  -> enriched relationships
  -> review queue
  -> decision output
```

## Core objects

- `source_item`: URL, PDF, file, dataset, email, transcript, repo, or note.
- `source_claim`: extracted claim with provenance.
- `entity`: person, organization, opportunity, project, capability, place, or
  technology.
- `relationship`: typed link between entities.
- `evidence_bundle`: reusable package of claims, sources, notes, and confidence.
- `decision_output`: concept note, brief, case study, proposal, data room, or
  public page.

## Current applications

- Hadox Scientific Intelligence.
- Opportunity radar and CRM workflows.
- Research-community and fellowship applications.
- Proposal preparation.
- Public-sector concept notes.
- Research-operations evidence extraction.
- Portfolio evidence discovery.

## Outputs

- Source ledgers.
- Capability maps.
- Partner maps.
- Data rooms.
- Opportunity radars.
- Concept notes.
- Research briefs.
- Public/private intelligence surfaces.

## Public / anonymized evidence

- `PRD-002` - Hadox Scientific Intelligence.
- `PRD-003` - EVA Breast Cancer Archive Platform.
- `CL-DEV-002` - forest digital traceability and territorial intelligence.
- `CL-DEV-003` - nature-based solutions ecosystem route.

## Private boundary

Inbox content, partner discussions, proposal drafts, client evidence rooms, and
exact opportunity strategy should remain private unless intentionally published.
