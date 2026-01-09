# Guarding Minds at Work Analysis
This repository contains code, outputs, and data related to the analysis of workplace psychological dimensions in the Guarding Minds at Work survey.

## Repository Contents
- `GM@W_Code.Rmd` – R Markdown file with all analysis code.
- `weighted_regression_cleaned.xlsx` – Weighted regression results.
- `weighted_regression_heatmap.png` – Heatmap of regression estimates.
- `weighted_ttests_by_union.xlsx` – T-tests comparing unionized vs non-unionized groups.
- `Guarding minds 2023_weighted_15.6.2023.csv` – Anonymized raw dataset used.

## Analysis Overview
- Weighted regressions were performed using `svyglm` to account for survey design.
- Psychological dimensions analyzed include Workload, Recognition, Psychological Protection, etc.
- Analyses stratified by Union Status to examine differences between unionized and non-unionized employees.
- Variables were coded consistently (e.g., female = 0, male/other = 1).

## Reproducibility
1. Clone the repository:
   git clone https://github.com/ThinuriSW/GuardingMindsAtWork_Analysis.git

2. Open `GM@W_Code.Rmd` in RStudio.

3. Install required packages:
   install.packages(c("survey", "broom", "dplyr", "ggplot2", "openxlsx"))

4. Run the R Markdown file to reproduce tables and figures.

## Notes
- All data have been anonymized to protect participants' privacy.
- Code and results are shared for reproducibility.

## License
This repository is shared under an MIT License. Use freely with proper citation.

