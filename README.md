# CIS Resilience Framework

A modular, indicator-based framework for assessing the resilience of pressurised collective irrigation systems (CIS) under water scarcity, operational variability and drought.

The repository provides seven autonomous Excel workbooks: six subsystem assessment tools and one integrated assessment tool. The framework combines normalised performance indicators, dimension-balanced weighting and hierarchical aggregation to support diagnosis, comparison and decision-making.

## Framework architecture

| Code | Subsystem | Assessment focus |
|---|---|---|
| A | Water availability | Inflow reliability, drought characteristics, storage context and carry-over dependence |
| B | Reservoir service | Ability of storage and operating rules to meet irrigation demand |
| C | Conveyance and distribution | Hydraulic and service performance of the delivery network |
| D | Energy performance | Energy use, pumping performance and energy-service indicators |
| E | On-farm performance | Irrigation technology, crop-service conditions and farm-level performance |
| F | Drought management capacity | Preparedness, monitoring, response and adaptive management |

The integrated workbook combines the six subsystem results into a common resilience profile while preserving the diagnostic value of individual indicators and subsystems.

## Repository contents

```text
cis-resilience-framework/
├── README.md
├── LICENSE
├── CITATION.cff
├── CHANGELOG.md
├── CONTRIBUTING.md
├── CODE_OF_CONDUCT.md
├── DISCLAIMER.md
├── docs/
├── examples/
├── paper/
└── tools/
    ├── Integrated_Framework/
    ├── Subsystem_A/
    ├── Subsystem_B/
    ├── Subsystem_C/
    ├── Subsystem_D/
    ├── Subsystem_E/
    └── Subsystem_F/
```

## Quick start

1. Download the required workbook from `tools/`.
2. Open it in a recent desktop version of Microsoft Excel.
3. Read the workbook instructions before replacing example or template values.
4. Enter the required local data, thresholds, service standards and source information.
5. Review validation messages and completeness checks.
6. Examine indicator scores, dimension scores, subsystem results and dashboards.
7. Use the integrated workbook to assemble a complete six-subsystem resilience profile.

No installation or programming environment is required.

## Local configuration and transferability

The transferable elements are the six-subsystem architecture, indicator definitions, normalisation procedure, weighting structure and hierarchical aggregation. Thresholds, service standards and calculation parameters must be configured for the local hydrological, infrastructural, agronomic, energy and management context.

Local configuration may include drought thresholds, usable reservoir capacity, minimum operating levels, pressure requirements, conveyance and distribution losses, pumping capacity, crop groups and calendars, irrigation efficiencies, energy tariffs, water-allocation rules and management-assessment criteria.

Indicators may be omitted when they are not relevant or when data are unavailable. Omissions must be documented and weights recalculated within the corresponding operational dimension. When an entire subsystem cannot be assessed, results should be reported as a partial resilience profile and should not be directly compared with a complete six-subsystem assessment.

## Main outputs

- Normalised indicator scores from 0 to 1
- Operational-dimension scores
- Subsystem resilience scores
- Integrated resilience profile
- Diagnostic dashboards and comparison charts
- Input-source, confidence and validation records

Higher scores indicate stronger performance relative to the configured assessment criteria. Results should always be interpreted together with the local thresholds, data quality and assessment scope.

## Documentation

- `docs/`: user guidance, methodology and framework diagrams
- `examples/`: example inputs and outputs
- `paper/`: figures and supplementary material associated with the scientific publication
- Each folder under `tools/` contains a dedicated README with purpose, inputs, workflow and outputs.

## Citation

Citation metadata are provided in `CITATION.cff`. A DOI and final article reference will be added when available.

## Authors

- Antónia Ferreira
- João Rolim
- Cláudia Brandão
- Maria do Rosário Cameira

## Funding

Development of the framework was supported through doctoral research funded by Fundação para a Ciência e a Tecnologia (FCT), grant PRT/BD/154133/2022.

## Licence and disclaimer

Use of the repository is governed by the included `LICENSE`. See `DISCLAIMER.md` for limitations and conditions of use.
