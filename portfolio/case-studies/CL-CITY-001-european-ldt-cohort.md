# CL-CITY-001 - European Local Digital Twin Cohort Strategy

## Public title

Multi-city and partner strategy for European Local Digital Twin opportunities.

## Client status

Partner-sensitive. Use anonymized IDs unless a city, company, or public program
has already been named in an approved context.

## Role

Technical strategist, product-architecture translator, concept-note author,
partner intelligence analyst, and consortium architecture support.

## Problem

European local digital twin calls require more than a generic smart-city pitch.
They require eligible partners, authority involvement, ownership/control
declarations, work-strand selection, data-space awareness, interoperability
logic, auditable budgets, co-funding or administrative readiness, and credible
technical packages that can be executed within the call rules.

## Technical approach

The strategy treats the call as a cohort-building and operating-model problem.
Instead of pitching a single city or a single product, the work identifies
combinations of:

- city or public authority needs;
- eligible European partner companies;
- technical providers;
- local digital twin use cases;
- interoperability and data-space requirements;
- governance and ownership-control requirements;
- contribution of Hadox / Polisplexity as research, coordination, and technology
  support.

The central technical pattern was a modular local digital twin that can be
deployed as separate city-controlled instances while sharing common models,
connectors, semantic rules, scenario contracts, documentation, and validation
methods.

## City and service logic

The cohort work converged around a service-oriented framing:

- territorial planning and urban intervention review;
- resilience, population, and continuity of services;
- reconstruction and restricted-data handling;
- GIS/BIM/IFC planning integration;
- disaster, heat, mobility, infrastructure, and public-service scenarios;
- evidence packages that municipal teams can inspect and approve.

The key architecture choice was to avoid a central all-city twin. The intended
pattern is a shared technical base with city-owned instances, local access
control, local data governance, and reusable cross-city service logic.

## Partner architecture

The work separated legal eligibility from technical value. The partner map
included:

- public authorities as owners of data, services, and validation;
- European integration and deployment partners;
- infrastructure, security, and systems-integration partners;
- exploitation, adoption, sustainability, and impact partners;
- training, onboarding, and documentation partners;
- AI, simulation, and scenario partners;
- Hadox / Polisplexity as product, architecture, research, and preparation
  support.

This separation mattered because the strongest technical contributor is not
always the cleanest formal beneficiary under a specific European call.

## Technology surface

The technical design and diligence covered:

- PostgreSQL/PostGIS as spatial source of truth;
- Docker-based deployment;
- authenticated city workspace and multi-city registry;
- source/provider/layer ingestion registry;
- GeoJSON, CSV, OGC API Features/WFS, STAC, CityJSON, raster/COG, HTTP JSON,
  MQTT metadata, 3D Tiles metadata, and IFC/BIM handling;
- MapLibre-style web mapping, 3D routes, and immersive/public viewer surfaces;
- BIM/IFC metadata, anchors, property sets, and mesh/package handling;
- DCAT, JSON-LD/RDF, NGSI-LD, Smart Data Models, OGC API Features, ODRL-style
  policy metadata, and FIWARE-compatible context-broker scaffolding;
- semantic packs, scenario contracts, validation workflows, and evidence
  briefs;
- human-in-the-loop AI agent workflows for data inspection, provenance checks,
  semantic binding, standards checks, scenario preparation, and reporting.

## Work products

- City authority collaboration concept notes.
- Technical architecture and integration concept notes.
- Consortium and funding support concept notes.
- Partner-by-partner message drafts.
- Ownership-control and eligibility interpretation.
- Letter of intent / commitment templates.
- Cohort role maps.
- B2Match participant intelligence.
- City and company fit notes.
- Technical FAQ for city counterparts.
- Associate FAQ for internal partner positioning.
- Public one-pagers for multiple work strands.
- Budget-scenario notes and partner budget notes.
- Itemized execution-requirements register.
- Data-room structure for public and private material.

## Technical themes

- Work Strand 1: interconnection of existing local digital twins.
- Work Strand 2: creation of new local digital twins around common needs.
- Work Strand 3: AI services and automation for local digital twin toolboxes.
- Semantic interoperability and shared service models.
- NGSI-LD / Smart Data Models readiness.
- Data-space and LDT Toolbox alignment.
- MIMs Plus interpretation.
- AI-agent workflows for city teams.
- Waste, energy, planning, resilience, mobility, housing, and reconstruction use
  cases.
- Governance for AI and digital public infrastructure.

## Architecture contribution

Polisplexity contributes the local digital twin engine, Twin Base Studio product
logic, scenario/service-pack architecture, and open-core civic-infrastructure
positioning. Hadox contributes governance, evidence, research, documentation,
and administrative support. European partners may provide eligible legal
vehicles, authority access, specialized connectors, domain tools, deployment
capacity, sustainability work, adoption, and local validation.

## What this demonstrates

- Ability to translate call rules into technical consortium design.
- Ability to map product architecture to public funding requirements.
- Ability to work with eligibility, ownership-control, and partner-risk
  constraints.
- Ability to build a reusable cohort narrative across multiple cities and use
  cases.
- Ability to transform scattered partner conversations into an executable
  technical program with roles, work packages, evidence, and budget logic.
- Ability to protect sensitive partner information while still publishing a
  coherent technical portfolio narrative.

## Related dossier

- `portfolio/programs/local-digital-twins.md` - broader program view.

## Public status

Anonymized / partner-sensitive.
