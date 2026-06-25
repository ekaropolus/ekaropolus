# Urban Scaling, SAMI, and Research Software

## Status

Current core capability.

## What it solves

Digital twin and urban intelligence work needs reproducible research software.
Otherwise results remain trapped in dashboards, notebooks, or one-off app
states. This capability converts urban theory, model runs, and digital twin
outputs into inspectable research workflows.

## Technical work

- Workflow manifest design.
- Model fitting kernels.
- Urban scaling experiments.
- Support-unit comparisons.
- Monograph-to-code traceability.
- Equation-to-script mapping.
- Golden tests and parity checks.
- Reproducible reports.
- Postgres / PostGIS experiment database design.

## Theory / method questions

- Is the city the correct theory-native unit?
- What changes when the support unit is state, AGEB, manzana, hex, or geofence?
- Can a production digital twin result be replayed independently?
- Can a manuscript map to executable code and generated tables?
- Can mismatches be detected rather than hidden?

## Current applications

- `urban-sami`.
- Polisplexity matrix parity.
- Independent city and state baselines.
- OSM city-network workflows.
- INEGI / DENUE public-data experiments.

## Outputs

- Research code.
- CLI workflows.
- Data contracts.
- Database schemas.
- Monograph-to-code crosswalk.
- Equation traceability.
- Report packs.
- Reproducibility documentation.

## Public / anonymized evidence

- `RSH-001` - urban-sami.

## Private boundary

Large generated datasets, private digital twin exports, and local experiment
databases may stay out of Git while the code and documentation remain public.
