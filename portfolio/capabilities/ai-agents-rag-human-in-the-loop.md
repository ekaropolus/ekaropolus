# AI Agents, RAG, and Human-in-the-Loop Workflows

## Status

Current core capability.

## What it solves

AI can help institutions process large bodies of evidence, but only if the
workflow preserves sources, uncertainty, human review, and operational context.
This capability designs AI workflows that help people make decisions without
turning the system into an untraceable black box.

## Technical work

- Retrieval-augmented generation.
- Source-grounded synthesis.
- Agent workflows for research and operations.
- Prompt and context design.
- Review queues.
- Public/private sensitivity handling.
- Evidence extraction from documents, validated records, and repositories.
- Structured output generation for reports, concept notes, and case studies.

## Design rules

- AI should cite or point back to evidence.
- AI should expose uncertainty when the source is weak.
- Raw evidence should be preserved separately from generated synthesis.
- Human review should be part of the workflow.
- Sensitive information should be filtered before public export.
- The system should improve institutional memory, not only produce one text.

## Current applications

- Hadox Scientific Intelligence.
- Editorial operating-memory layer.
- Proposal and concept-note generation.
- Public opportunity radar.
- Technical portfolio candidate extraction.
- Research and fellowship preparation.
- Digital twin decision-support workflows.

## Past foundations

- Enterprise systems and compliance logic.
- Public-sector data review.
- Cloud ML and NLP training.
- Graph and knowledge modeling.

## Outputs

- AI-assisted briefs.
- Source-grounded concept notes.
- Case-study drafts.
- CRM updates.
- Public opportunity pages.
- Evidence-based reply drafts.
- Technical documentation.

## Public / anonymized evidence

- `PRD-002` - Hadox Scientific Intelligence.
- `CL-STARTUP-001` - Energy Twin application route.
- `CL-UNI-001` - Urban SAMI academic collaboration route.

## Private boundary

Prompts containing private context, email-derived claims, partner notes, and
client documents should not be published directly.
