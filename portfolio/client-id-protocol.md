# Client ID Protocol

This portfolio uses anonymized IDs for client, partner, city, and institutional
work when the public name should not appear in GitHub.

## ID format

Use short IDs that preserve the type of work without revealing the organization.

| Prefix | Meaning | Example |
| --- | --- | --- |
| `CL-ENT` | Enterprise or corporate client | `CL-ENT-001` |
| `CL-GOV` | Government or public-sector institution | `CL-GOV-001` |
| `CL-CITY` | City, municipality, or regional authority | `CL-CITY-001` |
| `CL-UNI` | University or academic institution | `CL-UNI-001` |
| `CL-NGO` | NGO, association, foundation, or civil society actor | `CL-NGO-001` |
| `CL-DEV` | Development bank, international agency, or cooperation actor | `CL-DEV-001` |
| `CL-STARTUP` | Startup, venture, or innovation program | `CL-STARTUP-001` |
| `PRD` | Product or platform line | `PRD-001` |
| `RSH` | Research line or research output | `RSH-001` |

## Private mapping

The private mapping should be kept in:

```text
private/client-map.csv
```

Suggested columns:

```csv
id,real_name,type,country,project_alias,public_status,confidentiality_notes,source_folder,source_drive_url,owner,last_reviewed
CL-GOV-001,,government,Mexico,,,,,,,
```

`private/` is ignored by Git. Do not commit the real mapping.

## Public writing rules

When writing public case studies:

- describe the technical challenge, method, stack, and output;
- use the anonymized ID instead of the client name;
- avoid exact budgets unless already public;
- avoid exact internal dates when they identify the client;
- do not copy private proposal text verbatim;
- cite public repositories, public websites, or public documents when available;
- mark uncertain claims as `needs verification`.

## Internal review rule

Before publishing a new case study, check:

- whether the organization has already been publicly named elsewhere;
- whether the work was under NDA or commercial confidentiality;
- whether the case mentions sensitive datasets, credentials, systems, or people;
- whether a reader could infer the client too easily from unnecessary details.
