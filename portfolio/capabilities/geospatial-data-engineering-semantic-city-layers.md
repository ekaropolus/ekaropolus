# Geospatial Data Engineering and Semantic City Layers

## Status

Current core capability.

## What it solves

Urban projects often start with inconsistent geospatial files, public tables,
open data, incomplete building layers, mismatched boundaries, and service
records that do not align spatially. This capability creates the spatial data
foundation needed for local digital twins and territorial intelligence.

## Technical work

- Acquire and catalog public spatial sources.
- Normalize boundaries, roads, buildings, blocks, statistical units, and
  service locations.
- Preserve source metadata, licensing, extraction date, and quality notes.
- Design support-unit strategies across city, state, AGEB, manzana, hex, and
  geofence layers.
- Convert raw geospatial records into semantic city layers.
- Build derived indicators for analysis, simulation, and public explanation.

## Typical data layers

- Administrative boundaries.
- Census or statistical units.
- Road networks.
- Building footprints.
- Public facilities.
- Mobility anchors.
- Green-blue infrastructure.
- Service zones.
- Assets and critical infrastructure.
- Environmental, risk, and climate indicators.

## Methods

- Public data ingestion.
- Geospatial normalization.
- Support-unit comparison.
- OSM network extraction.
- INEGI / DENUE / CPV-style public-data baselines.
- PostGIS-ready derived tables.
- Metadata and source-ledger design.

## Current applications

- urban-sami city and state baselines.
- Polisplexity base twin and semantic seed layers.
- Civic XR fragment generation.
- Territorial decision twin concepts.
- Energy, waste, planning, and resilience add-ons.

## Outputs

- Source catalog.
- Spatial data contract.
- Derived tables.
- City network metrics.
- Geometry support documentation.
- Validation notes.
- Public/private export layer.

## Public / anonymized evidence

- `RSH-001` - urban-sami.
- `PRD-001` - Polisplexity Open Local Digital Twin.
- `CL-CITY-001` - European Local Digital Twin cohort strategy.

## Private boundary

Partner-provided GIS files, city-specific operational data, and non-public
service records should remain private or anonymized.
