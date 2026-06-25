# PRD-001 - Polisplexity Open Local Digital Twin

## Public title

Open Local Digital Twin infrastructure for cities.

## Public surfaces

- https://polisplexity.tech
- https://github.com/polisplexity

## Role

Founder, technical lead, and research/product architect.

## Problem

Cities often have fragmented geospatial layers, public records, service data,
planning documents, infrastructure datasets, and policy goals. These assets
rarely become a reusable computational layer for decisions. Most dashboards
show indicators but do not encode service logic, semantic context, simulation,
or institutional workflows.

## Technical approach

Polisplexity develops a local digital twin architecture that can start from a
base twin and expand into service-specific packs. The goal is not to build one
closed model per city, but reusable civic infrastructure that can absorb local
data and make it available for analysis, simulation, participation, and action.

The architecture separates the durable base twin from service-specific add-ons.
This avoids rewriting the whole system every time the city question changes. A
waste use case, energy use case, planning workflow, and resilience scenario can
share the same base geometry and semantic anchors while using different service
logic.

## Components

- V0 Base Twin.
- Logical Twin.
- Semantic Seeds.
- Add-On Packs.
- Interoperability route.
- Planning / Pre-BIM Pack.
- Disaster / Resilience Pack.
- People-Flow Simulation Pack.
- Municipal Operations Pack.
- Territorial / Environmental Pack.
- Industrial / Asset Pack.
- Sovereign Deployment Pack.

## Base data contract

A minimal city twin should define:

- city or project boundary;
- source catalog;
- road and street network layer;
- building or parcel layer;
- public space and green-blue infrastructure layer;
- administrative and statistical support units;
- civic anchors such as schools, clinics, markets, transit, public offices, or
  critical assets;
- source license and update status;
- validation notes and missing-data register.

## Add-on pack contract

Each add-on pack should specify:

- the operational question;
- required data layers;
- optional data layers;
- actors and workflows;
- scenario variables;
- outputs and decision criteria;
- validation method;
- public/private boundary;
- whether AI is used for synthesis, simulation support, or user interaction.

## Example pack logic

Waste / municipal operations:

- road network;
- collection zones;
- service frequency;
- transfer and disposal sites;
- vehicle constraints;
- organic/inorganic collection logic;
- route pressure;
- resident behavior assumptions;
- cost, coverage, and operational impact indicators.

Planning / pre-BIM:

- parcels or building footprints;
- zoning or planning constraints;
- candidate project geometry;
- IFC or pre-BIM intake when available;
- rule checks;
- public explanation layer;
- 3D or map-based validation surface.

Energy:

- building inventory;
- weather and climate stressors;
- mobility and occupancy proxies;
- asset records;
- energy-use signals when available;
- anomaly detection;
- scenario ranking for efficiency, flexibility, and resilience.

## Related work

- Energy Twin.
- Socio-Physical Digital Twin for Waste.
- Planning-ready city twin workflows.
- City-fragment XR / Twin Studio experiments.
- European local digital twin partner and cohort strategy.

## Evidence level

Public site, public organization profile, public/open repository direction, and
local prototype work. Some city and partner details remain private or
anonymized.

## What this demonstrates

- City systems architecture.
- Geospatial and semantic data modeling.
- AI workflow design for civic decisions.
- Translation from European LDT/data-space language into product architecture.
- Ability to design reusable infrastructure rather than one-off grant demos.

## Public status

Public / partial. Partner-specific work must use anonymized IDs unless already
public.
