# Airbnb Pricing Analysis in New York City

This project analyzes how neighborhood economic conditions influence Airbnb prices in New York City, with a focus on both demand and supply sides conditions. Using the NYC Airbnb 2019 dataset, combined with local economic indicators, the analysis explores spatial patterns and pricing mechanisms through both traditional econometric models and machine learning methods.

## Key Features
Descriptive Spatial Analysis
Visualizes the geographic distribution of Airbnb prices, crime rates, income, and listing density across NYC boroughs.
Regression Analysis (OLS)
Examines the relationship between Airbnb prices and neighborhood characteristics, using log-price models for interpretability.
Machine Learning Models
Applies regression trees to capture nonlinear relationships and identify key variables driving price variation.
Web Scraping Integration
Collects data on tourist attractions to measure local tourism intensity and enrich the analysis.

## Key Findings
Airbnb prices exhibit strong spatial heterogeneity, with higher prices concentrated in Manhattan and parts of Brooklyn.
Income level is a major determinant of price, reflecting stronger demand in wealthier neighborhoods.
Room type is the most important variable, with entire-home listings commanding significantly higher prices.
Machine learning results confirm that key variables such as income and room type capture most of the variation in prices.

## Limitations
Cross-sectional data limits causal interpretation.
Some datasets are not perfectly aligned in time, which may introduce measurement error.
Certain variables (e.g., amenities, transport access) are not included.

## Future Work
Incorporate panel data for causal inference (e.g., fixed effects, DiD).
Add more granular features such as transportation accessibility and host-level characteristics.
Explore advanced models (e.g., gradient boosting, causal forests).

## Tech Stack
Python (Pandas, NumPy)
Data Visualization (Matplotlib / Seaborn)
Econometrics (OLS Regression)
Machine Learning (Decision Trees)
Web Scraping (BeautifulSoup / Requests)
