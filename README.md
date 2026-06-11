# Association of the *GCH1* p.Ser80Asn variant with Parkinson’s disease in East Asian populations

`GP2 ❤️ Open Science 😍`

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT) [![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.20562807.svg)](https://doi.org/10.5281/zenodo.20562807)

**Last updated:** June 2026

## Summary

This is the online repository for the manuscript titled **"Association of the GCH1 p.Ser80Asn variant with Parkinson’s disease in East Asian populations"**. This study focuses on **investigating the association of GCH1 p.Ser80Asn variant with PD risk across ancestries**.

## Data statement
Data used in the preparation of this article were obtained from the Global Parkinson’s Genetics Program (GP2; https://gp2.org).

All GP2 data are hosted in collaboration with the Accelerating Medicines Partnership in Parkinson’s disease, and are available via application on the website (https://amp-pd.org/register-for-amp-pd). For up-to-date information on GP2 data acquisition, access, and policies, visit https://gp2.org/. Tier 1 data can be accessed by completing a form on the Accelerating Medicines Partnership in Parkinson’s Disease (AMP®-PD) website (https://amp-pd.org/register-for-amp-pd). Tier 2 data access requires approval and a Data Use Agreement signed by your institution.

In this analysis we used Tier 2 GP2 Release 11 data (https://zenodo.org/records/17753486).

### Helpful Links

- [GP2 Website](https://gp2.org/)
  - [GP2 Cohort Dashboard](https://gp2.org/cohort-dashboard-advanced/)
- [Introduction to GP2](https://movementdisorders.onlinelibrary.wiley.com/doi/10.1002/mds.28494)
  - [Other GP2 Manuscripts (PubMed)](https://pubmed.ncbi.nlm.nih.gov/?term=%22global+parkinson%27s+genetics+program%22)

## Repository Orientation
- The `analysis/` directory includes all analyses discussed in the manuscript.

## Analysis Notebooks
### Languages: Python, bash, and R
| Directory | Notebooks   | Description | 
|-----------|----------------|--------|
|`analyses/`| `00_GCH1_Ser80Asn.ipynb`         | To identify GCH1 p.Ser80Asn variant carriers across ancestries and perform halpotype analysis amongst carriers in the EAS cohort|


## Software
| **Software** | **Version(s)** | **Resource URL** | **RRID** | **Notes** |
|--------------|----------------|------------------|----------|-----------|
|ANNOVAR|d.06.08.2020|http://www.openbioinformatics.org/annovar/|RRID:SCR_012821|Used for variant annotation.|
|Beagle|v.5.4|https://faculty.washington.edu/browning/beagle/beagle.html|RRID:SCR_001789|Used for phasing.|
|GenoTools|v.1.2.3|https://github.com/GP2code/GenoTools|NA|Used for quality control and genetic ancestry inferrence.|
|gnomAD|v.4.1|http://gnomad.broadinstitute.org/|RRID:SCR_014964|Used to retrieve population frequency data.|
|PLINK|v.1.9,v. 2.0|http://www.nitrc.org/projects/plink|RRID:SCR_001757|Used for genetic analyses.|
|Python Programming Language|3.7, 3.8, 3.9, 3.10|http://www.python.org/|RRID:SCR_008394|pandas; numpy; seaborn; matplotlib; statsmodel; Used for general data wrangling/plotting/analyses|
|R Project for Statistical Computing|v.4.2.2|http://www.r-project.org/|RRID:SCR_001905|tidyverse; dplyr; tidyr; ggplot; data.table; Used for general data wrangling/plotting/analyses	|"


