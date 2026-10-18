# European Football Analytics

A personal data engineering learning project for analysing European football data with Google Cloud.

## Status

Day 1: repository and cloud setup in progress. No pipeline has been deployed, and no analytics results are claimed yet.

## Planned scope

- Select a football dataset and document its source, licence, and limitations before ingestion.
- Ingest a small sample into Cloud Storage.
- Transform and analyse the data in BigQuery.
- Add reproducible code, validation checks, and evidence of completed work.

The design may change as the project develops.

## Personal cloud environment

Use a separate personal Google account, GCP project, and personal billing account. Do not use employer accounts, training credits, lab projects, datasets, or internal material.

The total personal spending target is INR 1,000–2,000 for the whole project, not per month. Configure billing safeguards before running workloads. Alerts-only budgets do not stop spending automatically.

## Configuration and secrets

`.env.example` contains empty configuration fields only. If needed, copy it to `.env` and fill it locally. Never commit `.env`, access tokens, API keys, service-account keys, billing details, or unredacted account screenshots. Use Cloud Shell's authenticated identity; do not download service-account keys for this setup.

`.gitignore` helps prevent accidental commits but is not a secret scanner. Review every change before pushing. If a secret is exposed, revoke it immediately; deleting the file alone is insufficient.

## Evidence of work

Record completed steps, design choices, validation results, and cleanup instructions as they happen. Publish only sanitised evidence. Keep raw third-party data out of Git until redistribution rights have been verified.
