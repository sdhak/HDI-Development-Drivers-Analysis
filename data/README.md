## Data Overview

This project uses publicly available global development datasets to analyze factors associated with the Human Development Index (HDI).

Primary data sources:
* World Bank – World Development Indicators (WDI)
* United Nations Development Programme – Human Development Index dataset

## Folder Structure
````
external/   → Original downloaded datasets (unchanged; filenames standardized)
raw/        → Selected and merged datasets (before cleaning)
processed/  → Cleaned datasets used for modeling
````

## How to Download the Data

### 1. World Development Indicators (WDI)
Source: World Bank
* Access the World Development Indicators database:
https://databank.worldbank.org/source/world-development-indicators
* Select relevant indicators (or download bulk dataset)
* Export as CSV

Save as:
```` data/external/wdi_selected_indicators.csv ````

### 2. Human Development Index (HDI)
Source: United Nations Development Programme
* Access the HDI dataset:
https://hdr.undp.org/data-center/human-development-index
* Download the dataset (available in Excel or JSON format)

Save as:
```` data/external/hdi_undp.xlsx ````

## Data Processing Workflow
1. Raw datasets are stored in external/
2. Relevant indicators are selected and merged into raw/
3. Data is cleaned, normalized, and prepared for modeling in processed/

## Notes
* Original datasets in external/ are not modified (only filenames are standardized for clarity)
* Processed datasets can be reproduced using the notebooks in the /notebooks folder

