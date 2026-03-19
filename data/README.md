## Data Overview

This project uses publicly available global development datasets to analyze factors associated with the Human Development Index (HDI).

Primary data sources:
* World Bank – World Development Indicators (WDI)
* United Nations Development Programme – Human Development Index dataset

## Folder Structure
external/   → Original downloaded datasets (unchanged; filenames standardized)
raw/        → Selected and merged datasets (before cleaning)
processed/  → Cleaned datasets used for modeling

## How to Download the Data

### 1. World Development Indicators (WDI)
* Go to the World Bank data portal
* Select relevant indicators (or download bulk dataset)
* Export as CSV

Save as:
	•	data/external/wdi_selected_indicators.csv

### 2. Human Development Index (HDI)
* Download HDI dataset from UNDP website
* Export as Excel (available formats include Excel or JSON)

Save as:
	•	data/external/hdi_undp.xlsx

## Data Processing Workflow
1. Raw datasets are stored in external/
2. Relevant indicators are selected and merged into raw/
3. Data is cleaned, normalized, and prepared for modeling in processed/

## Notes
* Original datasets in external/ are not modified (only filenames are standardized for clarity)
* Processed datasets can be reproduced using the notebooks in the /notebooks folder

