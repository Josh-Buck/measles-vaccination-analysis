# Global Measles Vaccination Coverage Analysis

Analysis of 45 years of WHO vaccination data (1980-2024) across 190 countries to identify dropout trends between first and second measles vaccine doses and evaluate the impact of COVID-19 on global vaccination programs.

## Project Overview

This project analyzes measles vaccination coverage data to understand:
- Dropout rates between MCV1 (first dose) and MCV2 (second dose)
- Regional disparities in vaccination program effectiveness
- Impact of the COVID-19 pandemic on vaccination rates
- Differences between UNICEF-supported and non-program countries

## Key Findings

- **COVID-19 Impact:** Global dropout rates increased by 1.23 percentage points post-pandemic (10.09% to 11.32%)
- **Regional Disparities:** West/Central Africa (WCAR) experienced 32.25% dropout vs. 1.58% in Europe/Central Asia (ECAR)
- **Program Effectiveness:** UNICEF program countries showed 6.56 percentage points higher dropout rates than non-program countries (10.93% vs 4.37%)
- **2024 Extremes:** Somalia (50% dropout) vs. Montenegro (-195% - indicating strong catch-up campaigns)

## Technologies Used

- **Python 3.x**
- **pandas** - Data manipulation and analysis
- **NumPy** - Numerical computations
- **matplotlib** - Data visualization
- **seaborn** - Statistical visualizations
- **scipy** - Statistical analysis

## Project Structure
```
measles-vaccination-analysis/
│
├── Measles_Data.xlsx               # WHO/UNICEF vaccination data
├── Buck_Schultz_Measles_pynb.ipynb # Main analysis notebook
└── README.md                        # Project documentation
```

## Getting Started

### Prerequisites
```bash
pip install pandas numpy matplotlib seaborn scipy openpyxl
```

### Running the Analysis
1. Clone this repository
2. Ensure `Measles_Data.xlsx` is in the main directory
3. Open and run `Buck_Schultz_Measles_pynb.ipynb` in Jupyter Notebook or Google Colab

## Analysis Methodology

1. **Data Loading & Cleaning:** Loaded MCV1 and MCV2 data from separate Excel sheets, handling missing values and merging datasets
2. **Metric Engineering:** Calculated dropout rates and completion rates for each country-year combination
3. **Exploratory Data Analysis:** Generated descriptive statistics and identified patterns across regions and time periods
4. **Time Series Analysis:** Analyzed trends from 1980-2024, with focus on pre/post-COVID comparison (2015-2019 vs 2020-2024)
5. **Visualization:** Created multi-series line plots, box plots, histograms, and bar charts to communicate findings

## 🔗 Data Source

World Health Organization (WHO) and UNICEF immunization coverage estimates

## 👤 Author

**Josh Buck**  
MS Data Science Student, Lehigh University  
[LinkedIn](https://www.linkedin.com/in/josh-buck) | [GitHub](https://github.com/Josh-Buck)

##  Course Information

Created as part of DSCI 431: Introduction to Statistical Modeling, Fall 2025

---

*This project demonstrates skills in data cleaning, exploratory data analysis, statistical analysis, time series analysis, and data visualization using Python.*
