# \# Sun Belt Football Spending \& Performance Analysis

# 

# \## Overview

# 

# This project analyzes the relationship between reported football spending and on-field performance across 14 NCAA Division I Sun Belt Conference football programs.

# 

# The analysis combines an Excel dashboard with a Python companion notebook. The objective is to compare spending levels, performance outcomes, and spending-efficiency metrics during the 2023 football season using EADA Survey Year 2024 financial data.

# 

# \## Research Question

# 

# Which Sun Belt football programs achieved the strongest on-field performance relative to their reported spending during the 2023 season?

# 

# \## Files in This Repository

# 

# ```text

# sun-belt-football-analytics-project/

# ├── data/

# │   ├── Aurelien\_Schmitt\_Sun\_Belt\_Football\_Analytics\_Project.xlsx

# │   └── Sport\_Data\_2024.csv

# ├── notebooks/

# │   └── sun\_belt\_analysis.ipynb

# ├── outputs/

# │   ├── Aurelien\_Schmitt\_Sun\_Belt\_Football\_Analytics\_Dashboard.pdf

# │   ├── Sun\_Belt\_Football\_Analytics\_Notebook.html

# │   ├── Sun\_Belt\_Python\_Companion\_Summary.pdf

# │   └── assets/

# ├── README.md

# ├── requirements.txt

# └── .gitignore

# ```

# 

# \## Tools Used

# 

# \- Microsoft Excel

# \- Python

# \- pandas

# \- NumPy

# \- matplotlib

# \- Jupyter Notebook

# 

# \## Methodology

# 

# The analysis uses:

# 

# \- Football participants and football expenses from the U.S. Department of Education EADA Survey Year 2024

# \- 2023 overall and conference football records from Sun Belt Conference standings

# \- Calculated performance and efficiency metrics, including:

# &#x20; - expenses per participant

# &#x20; - overall win percentage

# &#x20; - conference win percentage

# &#x20; - wins per $1M spent

# &#x20; - conference wins per $1M spent

# 

# The Python notebook independently recalculates the key metrics from the Excel dataset, validates selected outputs, ranks programs by spending efficiency, calculates correlations, and generates visualizations.

# 

# \## Key Findings

# 

# \- The relationship between reported football expenses and conference win percentage was moderately positive, but limited.

# \- Reported football spending explained approximately 16% of the observed linear variation in conference win percentage within the sample.

# \- Troy ranked as the strongest spending-efficiency performer by wins per $1M spent.

# \- James Madison combined high spending with strong conference performance.

# \- Texas State reported the highest football expenses but did not lead the conference in win percentage.

# 

# \## Limitations

# 

# \- The analysis covers one conference and one football season only.

# \- Correlation does not establish causation.

# \- Strength of schedule, injuries, coaching changes, roster quality, and recruiting strength are not controlled.

# \- EADA expenses exclude capital expenditures, debt service, and certain indirect facility costs.

# \- Reported EADA expenses are annual actual expenditures, not a preseason budget.

# 

# \## How to Run the Notebook

# 

# The notebook is stored in the `notebooks/` folder and expects the Excel workbook to be available in the `data/` folder.

# 

# From the repository root, open:

# 

# ```text

# notebooks/sun\_belt\_analysis.ipynb

# ```

# 

# The notebook uses the following relative path:

# 

# ```python

# ../data/Aurelien\_Schmitt\_Sun\_Belt\_Football\_Analytics\_Project.xlsx

# ```

# 

# \## Author

# 

# Aurelien Schmitt  

# BBA Finance | Business Analytics Minor  

# NCAA Division 1 Tennis Student-Athlete  

# James Madison University

