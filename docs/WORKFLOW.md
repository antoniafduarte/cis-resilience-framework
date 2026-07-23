# Operational workflow and audit trail

## Source-to-output chain

`Source data -> subsystem calculation workbook -> public export workbook -> integrated tool -> analytical V2 -> publication outputs`

The detailed A–F workbooks retain the physical, hydraulic, energy, agronomic and management calculations. Public companion workbooks expose the final values and document their workbook, sheet, range and representative formula. This avoids fragile external links while preserving auditability.

## Public workbook sheets

Depending on the subsystem, public files contain:

- `00_README`
- `01_SOURCE_REGISTER`
- `02_EXPORT_CIS` or equivalent
- annual and/or ensemble output sheets
- `FORMULA_MAP`
- `QC`

## Analytical V2

The V2 workbook includes source registration, formula mapping and a single publication-output sheet. Baseline normalisation is formula-driven. Annual, pre/post, ensemble, correlation and sensitivity outputs are kept in dedicated sheets so that different sources of variability are not mixed.

## Temporal terminology

- **Interannual variability** — variation among annual values
- **GIR ensemble uncertainty** — variation among four complete irrigation-demand variants
- **Pre-expansion period** — 2016–2020
- **Transition year** — 2021
- **Post-expansion period** — 2022–2025
- **Methodological sensitivity** — dependence on thresholds, weighting and aggregation assumptions

## Updating the tools

When a source value changes:

1. update the detailed subsystem workbook;
2. check formulas and quality controls;
3. update the public export workbook;
4. update the integrated tool values;
5. refresh the V2 analyses;
6. increment the workbook version and change log.
