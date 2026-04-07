# Phytoplankton Data Analysis: Nutrient Impacts on Chlorophyll-a

## Overview
This project analyzes how nutrient enrichment (nitrogen, phosphorus, and silicon) influences phytoplankton biomass, using chlorophyll-a concentrations. The goal is to explore treatment-based differences, temporal trends, and relationships between nutrient inputs and phytoplankton productivity.

---

## Objective
To evaluate how different nutrient treatments affect chlorophyll-a concentrations and identify patterns in phytoplankton response across time and experimental conditions.

---

## Methods

### _Part 1: Data Standardization_
- Import data
- Renamed columns for clarity and consistency  
- Converted dates to datetime format  
- Numeric cleaning 
- Data quality check

### _Part 2: Exploratory Analysis_
- Grouped data by treatment to compute summary statistics  
- Evaluated correlations between nutrient inputs and chlorophyll  
- Aggregated yearly averages to analyze temporal trends  
- Correlation heatmap  
- Time-series plot of chlorophyll observations  
- Yearly average chlorophyll trends   

---

## Dataset
- Source: https://doi.org/10.5061/dryad.4fp90  
- Contains experimental data on:
  - Nutrient treatments (N, P, Si)
  - Chlorophyll-a concentrations
  - Sampling dates and locations  
---

## Key Findings

- Combined nitrogen and phosphorus treatments resulted in the highest chlorophyll concentrations, suggesting nutrient co-limitation  
- Nitrogen-only treatments produced moderate increases, while phosphorus-only treatments showed limited impact  
- Chlorophyll concentrations exhibited high variability, indicating potential influence of additional environmental factors  
- Temporal analysis suggests variability across years, though further data would be required for strong trend conclusions  

---

## Data Quality & Limitations

### Data Quality
- Missing chlorophyll values were removed  
- Data types standardized for analysis  
- Dates converted to consistent datetime format  

### Limitations
- Dataset represents controlled experimental conditions, not full natural systems  
- Temporal sampling is uneven  
- Additional environmental drivers (e.g., temperature, light) are not included  

---

## Tools & Technologies
- Python  
- Pandas  
- Matplotlib  
- Seaborn
