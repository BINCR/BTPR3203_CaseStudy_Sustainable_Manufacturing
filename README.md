# BTPR3203 Case Study: Sustainable Manufacturing & Water Consumption Patterns in Malaysia

## Overview
This repository contains the Python data science analysis for the **BTPR3203 Python for Data Science Case Study (Semester B, 2026)** at Southern University College.

The study investigates long-term industrial and domestic water usage patterns across Malaysian states (2003–2022) as a proxy indicator for sustainable manufacturing and regional industrial growth.

## Research Questions (SMART)
- **Q1 (Data Preparation)**: Clean nationwide water consumption data by filtering national aggregates (`Malaysia`) and engineer a derived metric (`nondomestic_share`) to measure regional industrial/commercial water demand intensity.
- **Q2 (Data Analysis)**: Evaluate the Compound Annual Growth Rates (CAGR) and total consumption trajectories of non-domestic water across primary industrial hubs (Selangor, Johor, Penang) versus national trends from 2003 to 2022.
- **Q3 (Visualisation)**: Analyze the spatial distribution and tiering of non-domestic water share across all Malaysian states as of 2022[cite: 1].

## Repository Structure
- `analysis.ipynb`: Fully executed Jupyter Notebook containing data loading, cleaning, feature engineering, statistical analysis, and visualizations[cite: 1].
- `water_consumption.csv`: Primary dataset sourced from DOSM / SPAN via `data.gov.my`.
- `charts/`: Exported high-resolution (300 DPI) chart images (`fig1`, `fig2`, `fig3`).

## Key Dependencies
- `pandas`
- `numpy`
- `matplotlib`
- `seaborn`
