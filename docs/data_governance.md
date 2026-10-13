# Data Governance and Management

## 1. Source Data

The original forest inventory workbook is the authoritative source supplied for this project. It must remain unchanged.

## 2. Data Ownership and Permissions

Before distributing source or derived data, establish who owns the data, who collected them, what permissions apply, and whether the data may be publicly redistributed.

The public GitHub repository must not be assumed to have permission to host the original workbook.

## 3. Geographic Information

The inventory contains georeferenced observations. Assess whether exact coordinates could expose sensitive species locations, restricted sites, or information subject to institutional or conservation restrictions.

Do not publish sensitive coordinates without appropriate authorization and review.

## 4. Data Separation

- Raw data: original source files, preserved unchanged.
- Interim data: temporary or partially processed datasets.
- Processed data: validated analytical datasets.
- External data: supplementary datasets and reference resources, subject to their licences and terms.

## 5. Taxonomic Changes

Every proposed scientific-name correction must retain the original name, the proposed accepted name, the matching authority, the resolution method, and a confidence or review status.

Ambiguous names must be flagged rather than silently resolved.

## 6. Spatial Changes

Coordinate corrections must be traceable to evidence. Suspected errors must be flagged, reviewed, and documented. Original coordinate values must be preserved.

## 7. Reproducibility

Document the input version, processing date, code version, software environment, parameters, quality checks, and output version for each major transformation.

## 8. Public Release

Only authorized and appropriately licensed materials may be released. Code, documentation, and data have separate licensing considerations.

## 9. Current Status

Data ownership, collection protocol, sharing permissions, site sensitivity, and appropriate public-release conditions remain to be confirmed during the initial audit.
