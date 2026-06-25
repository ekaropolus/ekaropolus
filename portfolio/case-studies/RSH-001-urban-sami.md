# RSH-001 - urban-sami

## Public title

Headless research workflow engine for urban scaling and SAMI experiments.

## Public repository

https://github.com/ekaropolus/urban-sami

## Role

Research software author / integrator.

## Problem

Digital twin and urban-scaling work can become difficult to audit when results
live only inside an application database, notebook, or dashboard. The research
question was how to make Polisplexity-style urban matrix experiments
reproducible, inspectable, and portable enough for academic review.

## Technical approach

The project separates research execution from the production application. It
loads workflow manifests, runs fitting kernels, replays summary matrices from
frozen outputs, and checks parity against preserved Polisplexity artifacts.

The important technical move is that the city, state, AGEB, and manzana levels
are not treated as interchangeable. Each support level is explicit. The
workflow can therefore ask whether a result is a city-scale urban scaling result,
an aggregation experiment, or an intra-urban support experiment.

## Methods and stack

- Python package and CLI.
- Workflow manifests.
- OLS, robust, Poisson, negative binomial, and automatic fitting kernels.
- Postgres / PostGIS experiment database.
- INEGI CPV 2020, DENUE, OSM, city, state, AGEB, and manzana data workflows.
- Monograph-to-code traceability.
- Golden tests and parity checks.

## Data model direction

The independent experiment database is organized around schemas such as:

- `raw`: source data as acquired;
- `staging`: parsed and normalized intermediate tables;
- `derived`: city, state, network, and indicator artifacts used for modeling;
- `experiments`: run state, model outputs, checks, and generated bundles.

Representative entities:

- support unit;
- population unit;
- economic activity record;
- city network geometry;
- city network metrics;
- model run;
- fit result;
- parity report.

## Reproducibility contract

The repository is designed around a practical contract:

1. Run or preserve a Polisplexity matrix experiment.
2. Export the relevant unit tables.
3. Feed those tables into `urban-sami`.
4. Regenerate the same summary outputs within fixed tolerance.
5. Treat mismatch reports as a research or implementation failure to investigate.

That contract matters because it prevents the digital twin from becoming a black
box. The model output can be checked outside the production app.

## Outputs

- `PROJECT_MAP.md`.
- Monograph-to-code crosswalk.
- Equation traceability files.
- Reproducibility documentation.
- Independent state and city baselines.
- OSM city-network persistence workflows.
- Parity workflows with `mismatch_count = 0` for preserved exports.

## Research value

This work turns digital twin experimentation into research software. It creates a
bridge between theory, code, data support units, and generated evidence.

## What this demonstrates

- Ability to convert a theoretical monograph into executable research code.
- Ability to maintain equation-to-script traceability.
- Ability to separate product infrastructure from academic validation.
- Ability to use public Mexican datasets in reproducible computational workflows.
- Ability to build a reviewable bridge between urban theory and civic technology.

## Public status

Public repository.
