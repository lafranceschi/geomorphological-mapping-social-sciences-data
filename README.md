# geomorphological-mapping-social-sciences-data
Supporting datasets for the qualitative review of geomorphological mapping, its applications, and its connections with social sciences.

# Supporting data for *Geomorphological Mapping and Social Sciences: A Qualitative Review*

This repository contains the supporting datasets used in the qualitative literature review published as:

> Franceschi, L., Bosino, A., La Licata, M., & De Amicis, M. (2025). Geomorphological mapping and social sciences: A qualitative review. *Geosciences, 15*(7), 271. https://doi.org/10.3390/geosciences15070271

## Purpose of the repository

This repository documents the progressive selection and qualitative coding of scientific publications dealing with geomorphological mapping, its fields of application, and its connections with social issues.

The three datasets correspond to successive levels of the review. They should therefore be interpreted together rather than as independent literature collections.

## Repository contents

```text
.
├── data/
│   ├── repository_I.csv
│   ├── repository_II.csv
│   ├── repository_III.csv
│   └── repositories.xlsx
├── LICENSE.md
└── README.md
```

The CSV files represent the primary open and machine-readable versions of the datasets. The Excel workbook is provided as a convenience copy and contains the same records and variables.

## Description of the datasets

### Repository I

Repository I contains the main literature corpus selected for the qualitative assessment. Each publication is described using basic bibliographic information and two levels of coding:

1. the general nature of the study, such as descriptive or applicative;
2. the main thematic field in which geomorphological mapping is used.

### Repository II

Repository II contains the additional publications examined during the focused assessment of the social dimension. It complements Repository I and records the studies identified through the search strategy described in the associated article.

### Repository III

Repository III contains the subset of publications classified as both applicative and related to social sciences. A third coding level identifies the main form of interaction between geomorphological information, users, public administrations, risk communication, and education.

Repository III is therefore a derived subset rather than an independent literature search. The source dataset of each publication is identified in a specific field.

## Methodological context

The datasets were created through a progressive literature-selection and qualitative-coding workflow. The coding framework was designed to identify:

- the general purpose of geomorphological mapping;
- the main fields of application;
- the presence of connections with social sciences;
- the consideration of specialist and non-specialist users;
- the ways in which geomorphological information supports education, participation, public administration, and risk awareness.

The datasets should be interpreted in relation to the search strategy, eligibility criteria, and methodological limitations reported in the associated article. Additional information is provided in [`documentation/methodological_notes.md`](documentation/methodological_notes.md).

## Data provenance and redistribution

The qualitative coding fields were produced by the authors of the associated study. Bibliographic information was initially collected through Scopus and subsequently checked and organised for the review.

The public version of the datasets contains only the bibliographic information considered suitable for redistribution. Full abstracts, proprietary database identifiers, and internal Scopus URLs are excluded unless their redistribution has been explicitly authorised.

Persistent DOI links are used where available.

## Missing values

Missing information is represented using the following conventions:

- `Not applicable`: the variable does not apply to the record according to the coding framework.

Blank cells are avoided except in optional note fields.

## Recommended citation

When using these data, please cite both the dataset and the associated article.

### Dataset

> Franceschi, L., Bosino, A., La Licata, M., & De Amicis, M. (2026). *Supporting data for “Geomorphological Mapping and Social Sciences: A Qualitative Review”* (Version 1.0.0) [Data set]. Zenodo. https://doi.org/10.5281/zenodo.XXXXXXX

The definitive Zenodo DOI will replace the placeholder after the publication of release `v1.0.0`.

### Associated article

> Franceschi, L., Bosino, A., La Licata, M., & De Amicis, M. (2025). Geomorphological mapping and social sciences: A qualitative review. *Geosciences, 15*(7), 271. https://doi.org/10.3390/geosciences15070271

## Versioning

The repository follows semantic versioning for published releases:

- `v1.0.0`: first curated public release;
- patch releases, such as `v1.0.1`, correct errors without changing the coding framework;
- minor releases, such as `v1.1.0`, add documentation or compatible data fields;
- major releases indicate substantial changes to the dataset structure or coding framework.

Zenodo assigns a DOI to each archived release and also provides a concept DOI representing all versions. The DOI of the specific version used should be cited whenever possible.

## Licence

The authors’ original qualitative coding and repository documentation are released under the Creative Commons Attribution 4.0 International licence, subject to the exclusions described in [`LICENSE.md`](LICENSE.md).

Third-party bibliographic content remains subject to the rights and terms of its respective providers and publishers.

## Contact

For questions, corrections, or suggestions concerning the datasets, please open an issue in this GitHub repository or contact the corresponding dataset creator through the institutional contact information reported in the associated article.
