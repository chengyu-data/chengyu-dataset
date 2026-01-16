# Chengyu dataset: Information and native speaker ratings

[![DOI](https://img.shields.io/badge/DOI-10.17605/OSF.IO/3TDA7-blue.svg)](https://doi.org/10.17605/OSF.IO/3TDA7)
[![License: CC-BY-NC 4.0](https://img.shields.io/badge/License-CC%20BY--NC%204.0-lightgrey.svg)](https://creativecommons.org/licenses/by-nc/4.0/)

This repository provides linguistic information and native speaker ratings for 1,015 *chengyu* 成语 'Chinese idiomatic expressions', compiled as part of PhD research (Davey, 2026b) investigating how first-language Chinese users understand and categorise *chengyu*.  

## Quick links

- **[Browse the dataset interactively](https://chengyu-data.github.io/chengyu-dataset/data-browser.html)** - Searchable, sortable, filterable datatable
- **[Download dataset (.xlsx)](https://doi.org/10.17605/OSF.IO/3TDA7)** - Full dataset with 67 variables × 1,015 expressions  
- **[Read the documentation](https://chengyu-data.github.io/chengyu-dataset/documentation.html)** - Complete variable descriptions and sources
- **[Project homepage](https://chengyu-data.github.io/chengyu-dataset)** - Full overview and research findings

## Citation

### How to cite this dataset

When using this dataset, please cite:

> Davey, J. (2026a). *Chengyu dataset: Information and native speaker ratings* [Data set]. Open Science Framework. [https://doi.org/10.17605/OSF.IO/3TDA7](https://doi.org/10.17605/OSF.IO/3TDA7)

### Primary research

This dataset was compiled as part of the following PhD research:

> Davey, J. (2026b). *What makes a *chengyu*? Native speaker intuitions for categorising Chinese idiomatic expressions* [Doctoral dissertation submitted for examination, Australian National University].

When reporting findings based on this dataset, please cite the dataset itself (above). The thesis citation provides theoretical and methodological context for the research design and data collection.

### Citing data subsets

When using specific subsets of data from this dataset, please acknowledge the original sources in addition to citing this dataset. Source information for all variables is provided in the documentation.

## Licence

This dataset is licensed under a [Creative Commons Attribution-NonCommercial 4.0 International Licence](https://creativecommons.org/licenses/by-nc/4.0/). You are free to share and adapt the material for non-commercial purposes, provided you give appropriate credit.

## Dataset contents

### Original empirical data (Davey, 2026b)
- Native speaker ratings (n=196 respondents) for recognition, *chengyu* acceptability, compositionality, and character engagement
- Experimental acceptability judgements (n=59 participants) with reaction times

### Published descriptive norms
- Psycholinguistic ratings from Li et al. (2016), Zhang & Ji (2016), Zheng (2019), and Zheng et al. (2022)
- Familiarity, meaningfulness, compositionality, literality, predictability, and L2 knowledge measures

### Corpus frequency data
- Raw and normalised frequencies from four major Chinese corpora (BCC, CCL, zhTenTen17, GigaWord 2)

### Linguistic information
- Semantic information: explanations, translations, synonyms, antonyms, sentiment
- Structural features: syntactic structure, structural symmetry, *xingshi* 形式 patterns
- Etymology: historical origins, dynastic periods, source texts
- Character-level data: frequency ranks, stroke counts

## Key research findings

*Chengyu* 成语 (literally 'set phrases') are conventionalised four-character expressions that often derive from classical Chinese texts, historical events, or stories. This PhD research (Davey, 2026b) provides empirical evidence that native speakers conceptualise *chengyu* differently than dictionaries suggest, revealing *chengyu* to be a culturally negotiated category with flexible boundaries.

- **Dictionary classifications don't predict native speaker judgements**: Dictionary-listed *chengyu* were rejected 40% of the time
- **Semantic opacity matters**: Transparent compositional meanings reduce *chengyu* acceptance
- **Structural irregularity is valued**: Regular AABB patterns rejected, irregular ABCD patterns preferred
- **Fast intuitive recognition**: Mean reaction time of 1,133 ms suggests predominantly intuitive categorisation

## Repository structure

```
chengyu-dataset/
├── README.md                          # This file
├── data/
│   └── Chengyu dataset.xlsx          # Full dataset (67 variables × 1,015 expressions)
├── docs/                              # GitHub Pages site files
│   ├── index.html                     # Project overview
│   ├── data-browser.html              # Interactive datatable
│   └── documentation.html             # Full documentation
└── scripts/
    └── create_github_pages.R          # R script to generate HTML files
```

## Data availability

This dataset is made freely available for non-commercial research and educational purposes.

- **Permanent repository**: Open Science Framework (OSF) -  [https://doi.org/10.17605/OSF.IO/3TDA7](https://doi.org/10.17605/OSF.IO/3TDA7)
- **Interactive browser**: GitHub Pages - https://chengyu-data.github.io/chengyu-dataset
- **Format**: Microsoft Excel (.xlsx) with 67 variables
- **Documentation**: Full variable descriptions, measurement details, source information, and references

## Contact

**Compiled by**: Janet Davey  
**Email**: main.gem4761@fastmail.com  
**Institution**: Australian National University

For questions about this dataset or to report errors, please [open an issue](../../issues) or contact main.gem4761@fastmail.com.

---

*Dataset version 1.0 | Last updated: 16/01/2026*
