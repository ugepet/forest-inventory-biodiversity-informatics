# Forest Inventory and Biodiversity Informatics

## Project Overview

This project investigates the ecological value and informatics potential of a georeferenced forest inventory dataset. It aims to develop a reproducible workflow that connects forest ecology, forestry, biodiversity data quality, taxonomic harmonization, spatial analysis, and computational methods.

The study area, inventory design, and data provenance will be formally documented during the initial data audit.

## Research Vision

To transform a legacy forest inventory into a quality-controlled, spatially explicit, reproducible biodiversity resource that can support ecological research, forest management, conservation, and biodiversity informatics.

## Research Strands

### 1. Ecology and Forestry

Potential research areas include:

- Floristic composition and tree diversity.
- Species abundance, dominance, and community structure.
- Spatial patterns and species co-occurrence.
- Forest disturbance and compositional variation.
- Conservation significance and priority areas.
- Relationships between tree vegetation and ground flora, where data support them.

### 2. Computer Science and Biodiversity Informatics

Potential research areas include:

- Automated scientific-name normalization and taxonomic reconciliation.
- Biodiversity data quality assessment.
- Geospatial data validation.
- Interoperable biodiversity data and Darwin Core-compatible outputs.
- Reproducible ecological data-processing workflows.
- Explainable machine learning and GeoAI, subject to suitable supplementary data.

These topics are provisional. Final research questions and publication decisions will follow the data audit and methodological assessment.

## Reproducibility Principles

1. Preserve the original source data without modification.
2. Record data provenance, permissions, and applicable restrictions.
3. Make data transformations reproducible through documented code.
4. Record methodological decisions and their justifications.
5. Validate scientific names and coordinates before ecological analysis.
6. Keep raw data separate from intermediate and processed data.
7. Track code and documentation changes through Git.
8. Record software versions, dependencies, parameters, and quality-control results.
9. Avoid treating individual observations as independent replicates when the sampling design does not justify it.
10. Ensure that each manuscript addresses a distinct scientific question.

## Repository Structure

- `docs/` — project scope, research questions, data governance, publication planning, and decisions.
- `data/raw/` — reserved for original source data; excluded from public version control by default.
- `data/interim/` — intermediate datasets produced during processing.
- `data/processed/` — validated datasets approved for analysis.
- `data/external/` — supplementary data, subject to source licensing and attribution.
- `notebooks/` — exploratory and analytical notebooks.
- `scripts/` — reusable processing and analysis code.
- `tests/` — automated checks for data-processing functions.
- `outputs/figures/` — generated figures.
- `outputs/tables/` — generated tables.
- `manuscripts/` — manuscript drafts and supporting materials.

## Data Governance

The original inventory is treated as immutable source material.

Raw data will not be published or uploaded to GitHub until ownership, authorization, confidentiality, and appropriate treatment of precise coordinates have been assessed. Public releases will contain only material that can legitimately be shared.

Derived datasets will have documented processing histories and quality-control checks.

## Project Status

**Current stage:** Project setup and data-audit preparation.

No ecological findings or model-performance claims should be considered final until the corresponding analyses have been executed and validated.

## Citation

Citation information and a recommended scholarly citation will be added when the project identity, authorship, and release details have been confirmed.

## License

The repository's code license does not automatically grant permission to redistribute source datasets or third-party materials. Data permissions and licensing will be documented separately.
