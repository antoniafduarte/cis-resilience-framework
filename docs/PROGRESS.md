# Public-tool operationalisation progress

Last updated: 23 July 2026

## Completed locally

The following public/audit workbooks have been generated and quality-checked with a common colour convention (dark blue, yellow, grey and white):

- Subsystem A — water availability
- Subsystem B — reservoir and service performance
- Subsystem C — conveyance and distribution performance
- Subsystem D — energy performance
- Subsystem E — on-farm performance
- Subsystem F — drought-management capacity
- Integrated analytical tool V2 with source register, formula map and publication outputs
- Complete release package with documentation and manifest

Each public subsystem workbook contains a documented export structure, source register, formula/provenance map and quality-control output appropriate to the available data.

## Uploaded to this branch

- Repository architecture and README
- Project `.gitignore`
- Workbook assembly workflow
- Public Subsystem C workbook

## Pending repository upload

The remaining binary Excel workbooks are complete locally. Their repository upload is being handled separately because binary workbook transfer requires validation to ensure that no file is corrupted during transport.

## Validation rules

- No external workbook links in public outputs
- Four GIR variants retained as complete scenario chains
- Interannual variability kept separate from GIR ensemble uncertainty and methodological sensitivity
- Dimension-balanced weighting used as the primary aggregation profile
- Equal-indicator weighting retained as a sensitivity comparator
- Final Subsystem C nomenclature: `Rnet`, `Rcov`, `RPD`, `CRPD80` and `MRPD`
