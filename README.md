# CIS Resilience Framework

Spreadsheet-based framework for diagnosing resilience in Mediterranean reservoir-fed collective irrigation systems.

## Scope

The framework integrates six interacting subsystems:

- **A** — Water-resource resilience
- **B** — Reservoir and service performance
- **C** — Pressurised irrigation-network performance
- **D** — Pumping and energy resilience
- **E** — Farm-level adaptive capacity
- **F** — Drought-management capacity

## Repository structure

```text
tools/
  subsystems/     Calculation workbooks for Subsystems A–F
  integrated/     Integrated CIS normalisation and aggregation tool
  analysis/       Variability, ensemble, pre/post-expansion and sensitivity analyses
outputs/          Publication-ready tables and machine-readable exports
docs/             Architecture, formula map, data dictionary and change log
```

## Calculation architecture

Each subsystem workbook retains its original inputs, formulas and diagnostic calculations and includes an `EXPORT_CIS` sheet with standardised outputs. The integrated and analytical tools import those outputs as embedded values, while recording the source workbook, sheet, cell and version. This avoids fragile external workbook links while preserving traceability.

The principal aggregation method is **dimension-balanced weighting**. Equal-indicator weighting is retained as a methodological sensitivity test.

## Visual identity

All spreadsheets and documentation use a consistent palette:

- dark blue — titles and primary headers;
- yellow — editable inputs and attention fields;
- grey — calculations, notes and secondary information;
- white — results and reading areas.

## Reproducibility

The public release will include:

- subsystem workbooks A–F;
- integrated resilience tool;
- analytical and sensitivity tool;
- source register and formula map;
- standardised output sheets;
- publication-ready tables;
- documentation and version history.

## Status

Repository structure under preparation. Spreadsheet tools will be added after formula, source and quality-control validation.

## License

Software and spreadsheet implementations are released under the MIT License. Data ownership and reuse conditions are documented separately where required.
