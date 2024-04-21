# Data Analytics Project

## Bilal Boulbarss
- Email: bilalboulbarss@gmail.com
- Date: 31-01-2024

---

## Overview

This project explores the relationship between unemployment and causes of death in the United States. It involves data preparation in a Jupyter Notebook and visualization in Power BI.

---

## Requirements

- Python Version: 3.9.7
- Required Modules: pandas

**To run the notebook:**
1. Place the provided CSV files in the same directory:
    - leading_cause_death.csv
    - Unemployment in America Per US State.csv
2. If running in Google Colab, add code to import the files.
3. Install the 'pandas' module for Python.

---

## Data Sources and Datasets

The project utilizes two raw datasets from Kaggle:
- [Leading Causes of Death USA](https://www.kaggle.com/datasets/kingburrito666/leading-causes-of-death-usa/data)
- [Unemployment in America Per US State](https://www.kaggle.com/code/ilyai332/unemployment-in-america-per-us-state/input)

The included CSV file 'death_work.csv' is generated after running the Jupyter Notebook, containing cleaned data for use in the Power BI dashboard.

---

## Navigation Guide and Dashboard Features

### Page 1:
Upon opening the PBIX file, you'll land on this page, featuring multiple visualizations, slicers, and cards:

- **Slicers**: Adjust graphs by state or year. (Note: Year slicer does not affect line plots.)
- **Reset Bookmark**: Removes all applied filters.
- **Donut Diagram**: Displays all causes of death.
- **Maps**: Show unemployment and deaths (all causes) in the US.
- **Cards**: Display states with the highest and lowest unemployment rates.
- **Line Plots**: Illustrate interesting trends over time.

### Page 2:
Dedicated visualization showing causes of death related to unemployment. Please note that these are relationships, not correlations. No causation conclusions are drawn.

