# Nilgiris Rainfall and Landslide Susceptibility

This repository supports the study **“Quantifying the impact of changing rainfall patterns on landslide frequency and intensity in the Nilgiris District of Western Ghats, India.”** It is intended to provide documentation, reproducible analysis files, and shareable derived datasets associated with the published research.

## Study overview

The study examines rainfall variability in the Nilgiris District, India, from 1992 to 2022 and evaluates landslide susceptibility using the Analytical Hierarchy Process (AHP). Twelve geological, topographic, hydrological, vegetation, and anthropogenic factors were used to produce and validate a landslide susceptibility map.

## Repository contents

| Path | Description |
|---|---|
| `data/derived/` | Shareable derived tables and geospatial outputs |
| `data/metadata/` | Data sources, field definitions, units, and provenance |
| `code/rainfall/` | Rainfall-processing and analysis scripts |
| `code/susceptibility/` | AHP and susceptibility-mapping workflow files |
| `docs/` | Methods, data-access notes, and reproduction guidance |
| `results/` | Final figures and maps suitable for publication |

## Data availability

Raw daily rainfall observations are not included because they were obtained from the Tamil Nadu Public Works Department and are subject to provider restrictions. The repository may include non-reconstructable rainfall summaries, derived indicators, AHP parameters, and selected model outputs where redistribution is permitted.

Other third-party source datasets, including the landslide inventory and elevation data, should be obtained directly from their original providers. See [`data/README.md`](data/README.md) for the sharing policy and source details.

## Citation

If you use material from this repository, cite the associated article:

> Chellamuthu, S. N., & Ganapathy, G. P. (2024). Quantifying the impact of changing rainfall patterns on landslide frequency and intensity in the Nilgiris District of Western Ghats, India. *Progress in Disaster Science, 23*, 100351. https://doi.org/10.1016/j.pdisas.2024.100351

Citation metadata are also available in [`CITATION.cff`](CITATION.cff).

## Contact

For questions about the repository or eligible derived data, contact Sabari Nathan Chellamuthu at `sabarinathan070@outlook.com`.
