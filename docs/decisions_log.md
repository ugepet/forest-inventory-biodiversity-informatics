# Project Decisions Log

This document records important research and project-management decisions, including their rationale and implications.

## DEC-001 — Preserve the original dataset

**Decision:** The original inventory workbook will remain unchanged.

**Rationale:** Reproducibility requires a stable source against which all transformations can be checked.

**Implication:** Corrections will be applied through documented scripts or derived datasets, never by overwriting the source.

**Status:** Active.

## DEC-002 — Use GitHub for version control

**Decision:** The project will use Git and GitHub to track code, documentation, methodological decisions, and approved research outputs.

**Rationale:** A version-controlled research record supports reproducibility, collaboration, and transparent project development.

**Status:** Active.

## DEC-003 — Keep raw data out of public version control by default

**Decision:** Original and potentially sensitive datasets will not be uploaded to the public repository unless their sharing permissions and suitability for release have been established.

**Rationale:** Data ownership, licensing, confidentiality, and sensitive geographic information must be considered separately from code licensing.

**Status:** Active.

## DEC-004 — Separate ecological and informatics research questions

**Decision:** The project will evaluate ecological and forestry questions separately from biodiversity-informatics and computational questions, while permitting integrated studies where justified.

**Rationale:** This helps ensure that each manuscript makes a distinct scientific contribution rather than fragmenting one analysis into overlapping papers.

**Status:** Active.

## DEC-005 — Treat publication candidates as provisional

**Decision:** No proposed manuscript is guaranteed to proceed.

**Rationale:** Publication decisions must follow assessment of data quality, sampling design, statistical power, novelty, and analytical independence.

**Status:** Active.

## DEC-006 — Document taxonomic and spatial corrections

**Decision:** Corrections to scientific names and coordinates must retain original values and record the evidence, method, and review status.

**Rationale:** Silent corrections can introduce errors and make ecological findings difficult to reproduce.

**Status:** Active.

## DEC-007 — Establish an audited baseline before substantive analysis

**Decision:** The project will complete and document an initial data audit before freezing a publication-grade master dataset.

**Rationale:** All subsequent analyses should use a controlled, validated dataset version rather than unverified workbook contents.

**Status:** Pending completion of the data audit.
