# Economies of Scale in Artificial Intelligence Innovation

This repository contains the replication materials and analysis code for the paper:

**Economies of Scale in Artificial Intelligence Innovation**

## Project Description

This paper examines whether artificial intelligence (AI) innovation exhibits economies of scale across firms. Using firm-level financial data and AI-related patent activity, the analysis investigates how AI patent production varies with firm size.

AI innovation is measured using AI-related patents linked to firm financial information. A series of regression models are estimated, including baseline OLS, controlled specifications, industry-year fixed effects models, nonlinear scaling models, firm fixed effects models, and Poisson count models.

The results indicate a positive relationship between firm size and AI innovation output, consistent with the hypothesis that the high fixed costs and low marginal costs of AI development create scale advantages for larger firms.

## Repository Structure

### csv_creation/

Contains Python scripts used to clean, merge, and construct the final analysis dataset.

These scripts process the underlying source data and generate the variables used throughout the empirical analysis.

### data/

Contains documentation regarding data availability and access restrictions.

No proprietary source data are distributed in this repository.

### regression_code/

Contains the primary empirical analysis files used in the paper.

Files include:

* Final regression notebook (`.ipynb`)
* Exported regression notebook (`.html`)

These files reproduce the regression results reported in the paper.

## Data Sources

The analysis uses:

* Compustat firm-level financial data obtained through Wharton Research Data Services (WRDS)
* United States Patent and Trademark Office (USPTO) patent data

## Data Availability

The datasets used in this study were obtained through authorized access to WRDS and publicly available USPTO patent records.

Some underlying datasets are subject to licensing and access restrictions and therefore cannot be redistributed through this repository.

Researchers seeking to replicate the analysis should obtain the required datasets directly from their respective providers and use the scripts contained in the `csv_creation` directory to reconstruct the analysis dataset.

## Reproduction

To reproduce the analysis:

1. Obtain access to the required datasets.
2. Run the scripts contained in `csv_creation/` to generate the final analysis dataset.
3. Execute the regression notebook contained in the regression code directory.
4. Compare the resulting outputs to the results reported in the paper.

## Author

Dillon Bowes

June 2026
