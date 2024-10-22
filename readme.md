COVID-19 Trade Impact Analysis Project

# Overview
This project analyzes the impact of COVID-19 on international trade patterns using comprehensive trade data from 2019-2021. The analysis includes multiple visualization approaches using Python, Tableau, and interactive dashboards to understand the pandemic's effects on global commerce.

# Table of Contents
- [Features](#features)
- [Installation](#installation)
- [Data Structure](#data-structure)
- [Visualization Guide](#visualization-guide)


# Features
- Comprehensive Data Analysis
  - Time series analysis of trade volumes
  - Import/Export pattern comparison
  - Commodity impact assessment
  - Transport mode analysis
  - Geographic trade flow visualization
  - Seasonal pattern detection

- Multiple Visualization Approaches
  - Python-based visualizations using matplotlib and seaborn
  - Interactive Tableau dashboards
  - Export-ready reports and figures
  - Custom analysis functions

- Advanced Analytics
  - Year-over-year comparison
  - COVID-19 impact periods analysis
  - Recovery tracking metrics
  - Seasonal adjustment calculations

# Installation

# Prerequisites
```bash
# Python version
Python 3.8 or higher

# Required packages
pandas
numpy
matplotlib
seaborn
plotly
```

# Data Structure

# Input Data Format
The analysis expects a CSV file with the following structure:
```python
Required columns:
- Date: YYYY-MM-DD format
- Country: Country name
- Commodity: Trade commodity category
- Direction: 'Exports' or 'Imports'
- Transport_Mode: Mode of transportation
- Cumulative: Trade value
- Year: YYYY format
```

# Output Structure
```
output/
├── figures/
│   ├── overall_trend.png
│   ├── trade_direction.png
│   ├── commodity_impact.png
│   └── transport_analysis.png
├── reports/
│   ├── monthly_summary.csv
│   ├── commodity_analysis.csv
│   └── country_impact.csv
└── dashboards/
    ├── trade_dashboard.twb
    └── recovery_tracker.twb
```

# Python Analysis
```python
# Import the analyzer
from trade_analyzer import TradeAnalyzer

# Initialize analyzer
analyzer = TradeAnalyzer(
    data_path='data/trade_data.csv',
    output_dir='output'
)

# Generate all analyses
analyzer.generate_all_plots()
```

1. Fork the repository
2. Create your feature branch:
```bash
git checkout -b feature/new-analysis
```
3. Commit your changes:
```bash
git commit -m 'Add new analysis component'
```
4. Push to the branch:
```bash
git push origin feature/new-analysis
```
5. Submit a pull request


# Contact
For questions and feedback:
- Project Lead: [Sarish](chavansarish400@gmail.com)
