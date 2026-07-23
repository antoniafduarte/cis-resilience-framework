# CIS Resilience Framework

Public spreadsheet implementation of an integrated, multi-subsystem methodology for diagnosing resilience in Mediterranean reservoir-fed collective irrigation systems.

## Framework structure

The framework represents the irrigation-service chain through six interacting subsystems:

- **A — Water-resource resilience**
- **B — Reservoir and service performance**
- **C — Pressurised irrigation-network performance**
- **D — Pumping and energy resilience**
- **E — Farm-level adaptive capacity**
- **F — Drought-management capacity**

Each subsystem has a detailed source workbook and a compact public workbook containing a documented export output, source register, formula map and quality checks. The integrated workbook applies threshold-based normalisation and dimension-balanced weighting. The analytical V2 workbook separates interannual variability, GIR ensemble uncertainty, pre/post-expansion comparison, correlation/redundancy screening and methodological sensitivity.

## Recommended workflow

1. Open the detailed source workbook for the subsystem being assessed.
2. Enter or update source data in the designated input sheets.
3. Review the calculation sheets and quality checks.
4. Use the corresponding public workbook to inspect the exported indicator values and formula provenance.
5. Transfer the approved values to the integrated tool.
6. Use the analytical V2 workbook for variability, uncertainty, weighting and sensitivity analyses.

No external workbook links are required in the public tools. Source workbook, sheet and range are documented explicitly.

## Repository folders

- `tools/subsystems/source/` — detailed subsystem calculation workbooks
- `tools/subsystems/public/` — compact public exports and audit workbooks
- `tools/integrated/` — integrated normalisation and aggregation tool
- `tools/analysis/` — V2 analytical and publication-output workbook
- `docs/` — workflow, terminology, style guide, file manifest and progress report

## Visual convention

The spreadsheets use a consistent palette:

- **Dark blue** — titles and primary headers
- **Yellow** — inputs, provenance and attention fields
- **Grey** — calculation, reference and locked areas
- **White** — outputs and reading areas

## Methodological notes

- Normalised classes use equal 0.25 intervals: Low, Moderate, Good and Excellent.
- The primary aggregation uses dimension-balanced weighting.
- Equal-indicator weighting is retained as a methodological sensitivity test.
- The four GIR variants are maintained as complete scenario chains.
- Interannual variability, GIR ensemble uncertainty and methodological sensitivity are reported separately.
- Thresholds are diagnostic and context-specific rather than universal standards.

## Current status

A draft public release is being assembled in pull request #1. The public/audit workbooks for Subsystems A–F and the analytical V2 workbook have been generated and quality-checked locally. Binary files are added to the repository only after transfer-integrity validation.

## Citation and versioning

Please cite the associated manuscript and identify the workbook version used. A formal citation and DOI will be added after publication and repository archiving.

## Licence

The code and spreadsheet implementation are released under the MIT License. Users remain responsible for checking local thresholds, service standards, data coverage and indicator applicability before transferring the framework to another irrigation system.
