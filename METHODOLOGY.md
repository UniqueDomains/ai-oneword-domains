# Methodology

## Scope

This repository represents the exact public search at `https://unique.domains/domains/tld/ai`.

The CSV and JSON files are the public extract published for that search. The live product can contain more domains, more filters, and more workflow state than the files in this repository.

## Source Of Truth

- Repository copy, links, counts, topics, and asset filenames are generated from one manifest per dataset repo.
- The README live catalog count uses the public landing response when it is available.
- The public extract size comes from the generated CSV and JSON payload for this repository.

## What Changes Over Time

- Domain statuses
- Visible prices
- Catalog counts
- Decision-support scores

## Caveats

- This dataset is decision support, not a guarantee of buyability, value, trademark clearance, or SEO outcome.
- Missing values are preserved when the upstream search does not expose a field.
- The public extract is intentionally smaller than the full live product when the live catalog exceeds the exported row count.

## Refresh Policy

This repository is refreshed on the export schedule used by the Unique Domains dataset pipeline. Stable historical references should be created through GitHub Releases rather than by relying on `main`.
