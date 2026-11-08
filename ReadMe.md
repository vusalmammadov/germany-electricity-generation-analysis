# Germany Electricity Generation Analysis

## Project Overview

This project explores Germany's electricity generation data using Python and Power BI. It analyzes electricity production by energy source, compares renewable and non-renewable generation, and identifies monthly trends in the German energy mix.

The project follows an end-to-end data analytics workflow, from data cleaning and exploratory data analysis in Python to interactive dashboard development in Power BI.

## Project Objectives

- Analyze electricity generation across different energy sources.
- Clean and prepare raw hourly electricity data.
- Calculate renewable and non-renewable generation.
- Evaluate the contribution of renewable energy to total generation.
- Explore monthly electricity generation trends.
- Compare energy sources through visualizations.
- Build an interactive Power BI dashboard.

## Dataset

- **Source:** SMARD – Germany's electricity market data platform
- **Country:** Germany
- **Period:** November 6, 2025 – November 7, 2026
- **Data frequency:** Hourly
- **Cleaned dataset:** 8,781 rows and 13 columns

The dataset contains electricity generation information for multiple energy sources, including wind, solar, biomass, hydropower, coal, and natural gas.

## Tools & Technologies

- **Python:** Data analysis and visualization
- **Pandas:** Data manipulation and cleaning
- **NumPy:** Numerical operations
- **Matplotlib:** Data visualization
- **Seaborn:** Statistical visualization
- **Power BI:** Interactive dashboard development
- **DAX:** Measures and KPI calculations
- **Power Query:** Data transformation

## Project Workflow

### 1. Data Cleaning & Preparation – Python

- Imported and inspected the raw dataset.
- Converted date columns into datetime format.
- Converted electricity generation fields into numeric values.
- Identified and handled missing values.
- Removed an empty Nuclear column and incomplete observations.
- Exported the cleaned dataset for Power BI.

### 2. Exploratory Data Analysis – Python

- Calculated total electricity generation by energy source.
- Analyzed renewable and non-renewable generation.
- Calculated energy source contribution percentages.
- Identified monthly generation patterns.
- Compared generation across complete months.
- Created bar charts, line charts, donut charts, and heatmaps.

### 3. Power BI Dashboard

Developed an interactive dashboard featuring:

- Electricity Generation KPIs
- Monthly Electricity Generation
- Monthly Energy Mix
- Generation by Energy Source
- Renewable vs. Non-Renewable Share
- Monthly Renewable Energy Trends
- Energy Generation Heatmap

### 4. Key Performance Indicators

| KPI | Result |
|---|---:|
| Total Primary Generation | 451.63 Million MWh |
| Renewable Generation | 274.20 Million MWh |
| Non-Renewable Generation | 177.43 Million MWh |
| Renewable Energy Share | 60.71% |
| Non-Renewable Energy Share | 39.29% |
| Wind & Solar Generation | 225.83 Million MWh |
| Wind & Solar Share | 50.00% |
| Pumped Storage Generation | 9.91 Million MWh |

**Note:** Pumped-storage generation is tracked separately and excluded from the primary renewable and non-renewable generation totals.

## Repository Structure

```text
germany-energy-project/
│
├── germany-electricity-generation.csv
├── germany-electricity-generation-clean.csv
├── germany-energy-analysis.ipynb
├── germany-energy-dashboard.pbix
├── screenshots/
│   └── dashboard-preview.png
│
└── README.md
```

## Key Insights

- Renewable energy accounts for approximately 60.71% of primary electricity generation in the analyzed dataset.
- Wind and solar together contribute approximately 50% of primary generation.
- Wind and solar are major contributors to Germany's electricity generation mix.
- Monthly analysis helps identify changes in generation patterns across energy sources.

## Notes & Limitations

- Monthly comparisons focus on complete months from December 2025 through October 2026.
- Partial November 2025 and November 2026 periods are excluded from complete-month comparisons.
- Pumped storage is presented separately from primary renewable and non-renewable generation.
- Results reflect the dataset's specific coverage period.

## Author

**Data Analytics Portfolio Project**

This project demonstrates practical skills in Python-based data analysis, data cleaning, visualization, Power BI dashboard development, and analytical storytelling.