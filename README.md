# OMF Data Model

## Overview

This research project assesses and evaluates the data models used by geospatial data providers, with the aim of improving the **Overture GERS** (Global Entity Reference System) data model.

## Research goals

1. **Survey** existing provider data models and the alternatives proposed for them.
2. **Evaluate** how those models compare with the current Overture GERS data model.
3. **Improve** the Overture GERS data model using the evidence gathered from (1) and (2).

## Current work

| Item | Description | Status | Tracking |
| --- | --- | --- | --- |
| Literature review | Review alternative data models for providers | In Progress | Jira `OMF-1` |
| Shortlisted paper review | Data model ideas and challenges from five POI matching and data quality papers | In Progress | Jira `OMF-3` |
| Places pipeline study | Places data model, theme and type, and the blocking, matching, and clustering stages | In Progress | Jira `OMF-4` |
| DuckDB and GeoParquet queries | Query Overture release data and the GERS registry without full downloads | In Progress | Jira `OMF-5` |
| GERS evaluation metrics | Quantifiable metrics for comparing GERS data model options | In Progress | Jira `OMF-6` |

## Where things are tracked

- **Jira (`OMF`)**: planned research work and milestones.
- **Confluence (Research & Development)**: findings and experiment write-ups.
- **GitHub Issues**: code defects and engineering tasks.

## Repository contents

- `README.md`: project overview and goals (this file).
- `.gitignore`: standard Python ignores.

## Status and open questions

- The evaluation criteria used to compare data models are not yet defined in this repository. They should be settled as part of the literature review and the metrics work (`OMF-6`).
- Open questions: how Places relate to Buildings and other themes; what should keep its identity when a place changes; whether a GERS ID should be replaced for new businesses.
- Observations so far come from Overture documentation and reading only. No experiments or results are included yet.
