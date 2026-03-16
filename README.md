# Identifying Drivers of Human Development Using Machine Learning

## Project Overview

The Human Development Index (HDI), developed by the United Nations Development Programme, is one of the most widely used measures for comparing development outcomes across countries. It summarizes human development using three key dimensions: health, education, and standard of living.

Although HDI provides a useful snapshot of development, it captures only a limited number of indicators. In practice, many other structural factors—such as infrastructure access, technology adoption, and social development indicators—may also influence a country’s overall level of human development.

This project explores how data science and machine learning techniques can be used to analyze global development indicators and identify additional variables that are strongly associated with HDI outcomes. By examining relationships between HDI and a broader set of development indicators, this analysis aims to generate insights that may help inform development policy discussions and resource allocation decisions.

The project uses data from the World Bank World Development Indicators dataset and applies a combination of statistical and machine learning methods to identify key patterns in global development data.

⸻

## Research Questions

This project explores the following research questions:

**1. Which development indicators outside of the traditional HDI components are most strongly associated with human development outcomes?**

While HDI includes life expectancy, education, and income, other variables—such as internet access, energy availability, and infrastructure indicators—may also play important roles in shaping development outcomes.

**2. Can machine learning models identify the relative importance of these indicators in predicting HDI levels across countries?**

Regression and tree-based models are used to evaluate which variables contribute most strongly to HDI prediction.

**3. Are there distinct clusters of countries that share similar development patterns?**

Cluster analysis is used to group countries based on development indicators in order to explore similarities in development structures.

**4. How can data-driven insights support development prioritization?**

By identifying indicators that are strongly associated with HDI outcomes, this project explores how data analysis can help organizations prioritize development interventions when resources are limited.

⸻

## Data Sources

The analysis uses publicly available global development datasets:
	* World Bank World Development Indicators
	* United Nations Development Programme Human Development Index dataset

The dataset includes 26 development indicators that are not directly used in the HDI formula but may influence human development outcomes.

Examples of indicators examined include:
	-	internet usage
	-	energy access
	-	education indicators
	-	infrastructure indicators
	-	population and demographic variables

⸻

## Methods

The project applies several statistical and machine learning techniques to analyze relationships between development indicators and HDI.

### Data Preprocessing
	-	Handling missing values
	-	Data normalization and standardization
	-	Variable selection and dimensionality reduction

### Modeling Approaches

**Linear Regression Models**

Used to evaluate relationships between individual indicators and HDI.

**Regression Tree Models**

Tree-based models help identify non-linear relationships and rank variable importance.

**Cluster Analysis**

Countries are grouped based on development indicators to explore structural similarities and differences in development patterns.

⸻

## Key Outputs

The analysis produces several types of outputs:
	-	Correlation analysis between indicators and HDI
	-	Feature importance rankings
	-	Regression model comparisons
	-	Country development clusters
	-	Data visualizations highlighting key development indicators

These outputs help identify variables that may be strongly associated with human development outcomes.

⸻

## Potential Applications

Although this project is exploratory in nature, the results illustrate how data-driven analysis could assist development organizations in prioritizing interventions.

Possible applications include:
	-	helping development organizations identify high-impact areas for investment
	-	supporting evidence-based policy discussions
	-	assisting international organizations in evaluating development priorities
	-	improving communication with donors through data-driven insights and visualization

Organizations involved in global development—such as the World Bank and the United Nations Development Programme—frequently rely on large datasets to guide development strategies, making analytical approaches like this increasingly valuable.

## Repository Structure
```
hdi-development-drivers/
│
├── data/
│   ├── raw/
│   ├── processed/
│   └── external/
│
├── notebooks/
│   ├── 01_data_exploration.ipynb
│   ├── 02_data_preprocessing.ipynb
│   ├── 03_modeling_regression.ipynb
│   ├── 04_tree_models.ipynb
│   └── 05_clustering_analysis.ipynb
│
├── src/
│   ├── data_processing.py
│   ├── feature_engineering.py
│   ├── modeling.py
│   └── visualization.py
│
├── outputs/
│   ├── figures/
│   ├── tables/
│   └── models/
│
└── reports/
    └── project_summary.md
```

## Tools and Technologies

Programming Language:
	-	Python

Libraries:
	-	Pandas
	-	NumPy
	-	Scikit-learn
	-	Matplotlib / Seaborn

⸻

## Limitations

Several limitations should be considered when interpreting the results of this analysis:
	-	Not all countries have complete data for all indicators.
	-	Statistical relationships identified in the models do not necessarily imply causal relationships.
	-	Development outcomes are influenced by complex political, institutional, and economic factors that may not be fully captured in quantitative datasets.

Future work could incorporate additional indicators, time-series analysis, or causal inference methods to further explore the drivers of human development.

⸻

## Author

Shristi Dhakal

MS in Data Science | Data Scientist
Interested in AI for social impact, development economics, and data-driven policy analysis.



