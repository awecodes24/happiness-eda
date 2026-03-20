# World Happiness Report — Exploratory Data Analysis

## Overview
Analysis of the UN World Happiness Report dataset (147 countries, 2025)
to identify the key drivers of national happiness scores.

## Key Findings
- Social support is the strongest predictor (r = 0.812)
- Nepal ranks #92 — weakest factor: GDP per capita
- Western Europe leads; Sub-Saharan Africa trails
- Social support dominates the freedom

## Charts
![Correlation Heatmap](charts/correlation_heatmap.png)
![Top 20 Countries](charts/top20_countries.png)

## Tech Stack
Python · pandas · NumPy · matplotlib · seaborn · Jupyter

## How to Run
\`\`\`bash
git clone https://github.com/awecodes24/happiness-eda
cd happiness-eda
pip install -r requirements.txt
jupyter notebook notebooks/analysis.ipynb
\`\`\`
