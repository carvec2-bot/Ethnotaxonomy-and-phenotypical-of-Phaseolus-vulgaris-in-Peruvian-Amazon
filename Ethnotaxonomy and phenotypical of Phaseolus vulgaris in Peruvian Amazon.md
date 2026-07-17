# Ethnotaxonomy and phenotypic evidence for a zone of high common bean (Phaseolus vulgaris L.) diversity in northeastern Amazonian Peru

## 📝 Project description

This project documents the ethnothaxonomic and phenotypic diversity of the common bean (*Phaseolus vulgaris* L.) across three biomes of the Peruvian Amazon: the inter-Andean Marañón Valley, the Highland Rainforest, and the Amazonian lowlands.

We recorded **152 specific vernacular names** and **20 generic terms** for *P. vulgaris* across 26 ethnic groups. Our results show high diversity in the Highland Rainforest, suggesting a continuous zone of high diversity in northeastern Peruvian Amazonia.

## 📂 Project structure

Proyecto Frijol/
├── Data/
│ ├── Data base interviewed people.xlsx # Interview database (available)
│ └── Variety and locations.xlsx # Variety and location data (restricted access)
├── Scripts/
│ └── Bean vernacular names.R # Main R analysis script
├── Figures/
│ ├── Figure_2.tiff
│ ├── Figure_3.tiff
│ ├── Figure_4A.tiff
│ ├── Figure_4B.tiff
│ └── Figure_5.tiff
├── Results/
│ └── Tables_generated_by_R/ # Automatically exported .csv files
└── README.md # This file

## ⚙️ Software requirements

- **R** version 4.6.0 or higher
- **RStudio** (recommended)

# Figures
Figure_2.tiff
Figure_3.tiff
Figure_4A.tiff
Figure_4B.tiff
Figure_5.tiff

Important note:
The file Data base "Interviewed people.xlsx" is available in this repository.
The file "Variety and locations.xlsx" requires permission from the author. To request access, contact Carlos D. Vecco Giove (cdvecco@unsm.edu.pe).

### Required R packages

```r
install.packages(c(
  "cluster",
  "clValid",
  "cultevo",
  "data.table",
  "dendextend",
  "dplyr",
  "DT",
  "dynamicTreeCut",
  "ecodist",
  "factoextra",
  "ggpubr",
  "ggplot2",
  "igraph",
  "knitr",
  "MVA",
  "NbClust",
  "purrr",
  "readxl",
  "reshape2",
  "seriation",
  "vegan",
  "writexl"
))

How to cite
Vecco-Giove CD, et al. Ethnotaxonomy and phenotypic evidence for a zone of high common bean (Phaseolus vulgaris L.) diversity in northeastern Amazonian Peru. Scientific Reports. [DOI to be assigned]

@article{veccogiove2025ethnotaxonomy,
  author = {Vecco-Giove, Carlos D. and ...},
  title = {Ethnotaxonomy and phenotypic evidence for a zone of high common bean (Phaseolus vulgaris L.) diversity in northeastern Amazonian Peru},
  journal = {Scientific Reports},
  year = {2025},
  doi = {[DOI to be assigned]}
}
