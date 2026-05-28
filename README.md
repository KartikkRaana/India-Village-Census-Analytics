# India Village Census — Exploratory Data Analysis
### Python EDA on 625,880 village records | 2011 Census 

---

## Project Overview
Analyzed India's 2011 Census village data across 30 states and UTs to uncover 
rural distribution patterns using Python. The goal was to identify where villages 
are concentrated and which states need priority rural investment.

## Key Findings
- Only **8 of 30 states** hold **80% of India's villages** (Pareto confirmed)
- **Uttar Pradesh** has 1,07,753 villages — 5× the national average of 20,863
- **North + East zones** account for 62% of rural India
- **21 of 30 states** fall below the national average
- Long-tail distribution — steep drop after rank 3 states (UP, MP, Odisha)

## What's in the Notebook
- Data loading and merging of 30 CSV files
- Data cleaning — null handling, deduplication, type fixing
- State-wise village count analysis
- Zone-wise geographic grouping
- Distribution analysis and outlier detection
- Visualisations — bar charts, distribution plots, zone comparisons

## Tech Stack
Python · Pandas · NumPy · Matplotlib · Seaborn · Jupyter Notebook

## Dataset
2011 Census of India · MDDS Village Directory
30 state-level files merged into one master dataset of 625,880 records

## Author
Kartik Rana · MCA · Amity University Haryana ·
