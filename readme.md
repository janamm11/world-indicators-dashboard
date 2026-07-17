# World Indicators Dashboard

An end-to-end data analytics project that fetches real-world development data from the World Bank API using Python and visualizes it through an interactive Power BI dashboard.

## Overview

This project analyzes global development indicators across 180+ countries covering health, economy, trade, poverty, environment, and technology. Data is fetched directly from the World Bank public API, cleaned and organized using Python, and visualized in Power BI to answer 9 analytical questions about global development trends.

## Questions Answered

1. What does the world look like overall — GDP, trade, health spending, forest coverage?
2. Which regions spend the most on healthcare?
3. How have key development indicators changed over time?
4. Does internet access lead to better immunization rates?
5. Does internet access reduce unemployment?
6. Which countries are struggling the most with poverty?
7. Which countries reduced poverty the most?
8. How do health indicators relate to each other?
9. Does government health spending actually improve life expectancy?

## Tech Stack

- **Python** — World Bank API fetching, data cleaning, correlation and regression analysis
- **Pandas** — data manipulation and reshaping
- **Seaborn / Matplotlib** — correlation heatmap and regression plot
- **Power BI** — interactive dashboard with slicers, KPI cards, and embedded Python visuals

## Note

Due to World Bank API rate limiting, pre-fetched CSV files are included. The full API fetching pipeline is documented in the notebook.

## Blog

Full project walkthrough on Medium → [link]
