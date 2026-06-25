# Open Local Digital Twin Architecture

## Status

Current core capability.

## What it solves

Cities and institutions often have maps, datasets, planning documents, service
records, and dashboards, but not a reusable operational model. This capability
turns fragmented urban evidence into a local digital twin architecture that can
support planning, services, resilience, energy, waste, participation, and public
decision-making.

## Technical thesis

A local digital twin should not be only a 3D viewer or a dashboard. It should be
a computable civic infrastructure layer with:

- source-aware base geometry;
- semantic city meaning;
- service-specific add-on packs;
- scenario logic;
- human-readable decision outputs;
- public/private data boundaries;
- reproducible evidence trails.

## Architecture pattern

```text
city sources
  -> source ledger
  -> base twin
  -> logical twin
  -> semantic seeds
  -> add-on packs
  -> scenario workflows
  -> decision surfaces
```

## Core components

- `base_twin`: boundaries, roads, buildings, parcels, public spaces,
  green-blue structure, administrative/statistical units.
- `logical_twin`: city-specific data bundles, constraints, workflows, viewer
  state, and service logic.
- `semantic_seed`: civic anchors, mobility structures, local economy, social
  meaning, critical assets, and institutional context.
- `add_on_pack`: waste, energy, planning, resilience, people-flow, environment,
  industrial assets, or sovereign deployment.
- `decision_surface`: dashboard, map, report, guided AI workflow, 3D/XR
  inspection, or partner evidence package.

## Current applications

- Polisplexity Open Local Digital Twin.
- Twin Base Studio.
- Energy Twin.
- Socio-Physical Digital Twin for Waste.
- Planning-ready city twin workflows.
- European local digital twin cohort strategy.
- City-fragment XR / analytical 3D modes.

## Current program depth

The Local Digital Twins work now includes more than product design. It has
covered a multi-city and multi-partner operating model with:

- city-specific service framing for planning, resilience, reconstruction,
  mobility, infrastructure, and continuity of services;
- work-strand interpretation for existing LDT interconnection, new LDT creation,
  and AI services for LDT toolboxes;
- technical diligence around GIS, BIM/IFC, PostGIS, 2D/3D viewers, semantic
  interoperability, data spaces, and scenario orchestration;
- partner-role mapping across city authorities, eligible European companies,
  exploitation/adoption partners, AI/simulation partners, and research support;
- budget, ownership-control, commitment-letter, and documentation workflows
  needed to make a technical architecture fundable and auditable.

## Past foundations

- Enterprise architecture and systems integration.
- Public-sector data and institutional workflows.
- Complex systems and sustainability research.
- Graph and policy modeling.

## Technical outputs

- Architecture notes.
- Concept notes.
- Repository and product documentation.
- Base twin / add-on pack decomposition.
- Partner-facing technical narratives.
- City and cohort role maps.
- Technical FAQs for city and partner conversations.
- Execution-requirement registers and budget logic.
- Public/private data-room structures.
- Work-strand one-pagers and proposal support materials.

## Public / anonymized evidence

- `PRD-001` - Polisplexity Open Local Digital Twin.
- `CL-CITY-001` - European Local Digital Twin cohort strategy.
- `CL-CITY-002` - Socio-Physical Digital Twin for Waste.
- `CL-CITY-003` - Planning-ready city twin workflow.
- `portfolio/programs/local-digital-twins.md` - consolidated program dossier.

## Private boundary

Specific city partner names, eligibility documents, ownership-control details,
and active consortium information should remain anonymized unless already public.
