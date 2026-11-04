# HeritageGuard — ICSH 2026

**Paper:** *HeritageGuard: Multimodal Forecasting of Structural Response for Predictive Conservation of Built Heritage*

This public repository identifies the source datasets used for the Hall I study and the retrospective Michelangelo's Cloister cross-location evaluation. Both datasets were published by the Project STORM team on Zenodo and are cited in the manuscript.

## Original FBG datasets

| Manuscript setting | Official source | Workbook | Versioned DOI |
| --- | --- | --- | --- |
| Hall I, Baths of Diocletian (primary E1–E4 study) | [Zenodo record](https://zenodo.org/records/3256111) | `Hall1_FBG_Dataset2017-2019.xlsx` | [10.5281/zenodo.3256111](https://doi.org/10.5281/zenodo.3256111) |
| Michelangelo's Cloister, Baths of Diocletian (retrospective cross-location study) | [Zenodo record](https://zenodo.org/records/3248893) | `Cloister_FBG_Dataset2018-2019.xlsx` | [10.5281/zenodo.3248893](https://doi.org/10.5281/zenodo.3248893) |

See [DATASETS.md](DATASETS.md) for source attribution, download instructions, checksums and the scientific distinction between the two datasets.

## Reproducibility status

- The **raw datasets** are available from the linked Zenodo deposits; they are **not duplicated in this repository**.
- The original Hall I E1–E4 scores are historical results from the manuscript. The original anomaly masks and exact split manifest have not been fully recovered, so this repository must **not** be described as providing exact E1–E4 reproduction.
- Later model comparisons, ablations, block-resampling exercises and Cloister evaluations are explicitly **retrospective analyses** and are not independent replications of E1.
- The Hall I and Cloister locations are within the same heritage complex. Their comparison does **not** establish generalization to an independent monument.
- **Current repository scope:** public dataset index and provenance documentation. Analysis scripts, processed features, per-origin predictions and a fully reproducible release are **not yet published here**. The accompanying manuscript should not imply otherwise.

## Data citation and license

Please cite the original Project STORM authors and their respective Zenodo records rather than citing this GitHub repository as the original data creator. The two Zenodo releases indicate a Creative Commons Attribution 4.0 International (CC BY 4.0) license; attribution remains required.

## Contact / research

This repository supports the HeritageGuard ICSH 2026 manuscript. Research conclusions, evaluation limits and author information are specified in the paper.

