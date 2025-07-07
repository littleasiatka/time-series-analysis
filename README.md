# U.S. State Government Expenditure Time Series Analysis (2012–2023)
This project analyzes government spending patterns across U.S. states using data from the Annual Survey of State Government Finances (2012–2023). The focus is on exploring long-term expenditure trends and forecasting future values using time series analysis techniques.

---

## Project Goals
- Explore and visualize total government expenditure over time
- Identify spending trends and fluctuations
- Apply rolling averages to smooth out short-term variations
- Build an ARIMA model to forecast expenditures for the next 5 years

---

## Dataset
**Source**: U.S. Census Bureau – [Annual Survey of State Government Finances](https://www.census.gov/programs-surveys/gov-finances.html)
**File**: `state_finance_data.xlsx`  
**Years covered**: 2012-2023  
**Fields used**: `Year`, `Total.Expenditure` (summed across states)

---

## Tools & Libraries
- Python 3
- Jupyter Notebook
- pandas
- matplotlib
- seaborn
- statsmodels
- openpyxl

---

## Key Visuals
- Line chart of total expenditure over 12 years
- Smoothed trend using 3-year rolling average
- Forecast plot using ARIMA for future expenditure (next 5 years)

---

## Getting Started

### 1. Clone this repo
```bash
git clone https://github.com/littleasiatka/time-series-analysis.git
cd time-series-analysis
```

### 2. Set up virtual environment
```bash
python3 -m venv venv
source venv/bin/activate
pip install -r requirements.txt
```

### 3. Open the notebook
```bash
jupyter notebook notebooks/time_series_analysis.ipynb
```

---

## Project Structure
```
time-series-analysis/
├── data/
│   └── state_finance_data.xlsx
├── notebooks/
│   └── time_series_analysis.ipynb
├── outputs/
│   └── 5-year-forecast-of-government-expenditure.png
│   └── expenditure-trend-with-rolling-average.png
│   └── total-US-state-government-expenditure.png
├── README.md
└── requirements.txt
```
---

## Future Improvements
- Break down trends by state or function (e.g., education, healthcare)
- Add interactive dashboard using Plotly or Power BI
- Apply more advanced models (e.g., SARIMA, Facebook Prophet)

---

## Author

**Anel Naukan**  
Computer Science student with a passion for data analysis, Python development and solving real-world problems through code.

[Portfolio Website](https://yourportfolio.com) 
[LinkedIn](https://linkedin.com/in/anel-naukan)
[GitHub](https://github.com/littleasiatka)
