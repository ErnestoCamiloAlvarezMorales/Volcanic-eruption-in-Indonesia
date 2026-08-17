[Volcanic Eruptions in Indonesia - Exploratory Data Analysis (EDA).md](https://github.com/user-attachments/files/31131629/Volcanic.Eruptions.in.Indonesia.-.Exploratory.Data.Analysis.EDA.md)
# Volcanic Eruptions in Indonesia - Exploratory Data Analysis (EDA)

A comprehensive statistical and visual analysis of volcanic eruptions in Indonesia (1300-2021) using R and the tidyverse ecosystem.

---
## The objective

Indonesia is the world's most volcanically active region. This project analyzes historical eruption data to understand frequency, explosivity (VEI), and the relationship between mountain elevation, eruption magnitude, and human impact over time.

## Key Analyses Included

- Data Cleaning: Handling missing values in VEI and mortality data using janitor and dplyr.
- Statistical Distribution: Histograms with Normal Density overlays and Quantile-Quantile (QQ) plots to test for normal distribution in eruption frequency and mountain elevation.
- Impact Analysis: Scatter plots using ggplot2 to correlate elevation, VEI, and total deaths over time using LOESS smoothing.
- Geospatial Visualization: A custom map of Indonesia plotting volcano locations, types, and historical impact using the maps package.
---
## Tech Stack

- R
- tidyverse (dplyr, ggplot2, tidyr, readr, lubridate)
- cowplot / maps / skimr
---
## Data Source
Data is sourced from the NCEI/WDS Global Significant Volcanic Eruptions Database and Kaggle (Public Domain).

---
## How to use 
1. Clone the repository.
2. Ensure you have R and RStudio installed.
3. Install required packages: install.packages(c("tidyverse", "janitor", "skimr", "cowplot", "maps"))
4. Open the volcano_analysis.Rmd file and knit to HTML or run chunk by chunk.

---

## Author

**Ernesto Álvarez** — Geology Student | Self-Taught Data Science Practitioner

Applying data science and statistical methods to economic geology and mineral exploration.
[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/ernesto-alvarez-1400ba190/)

