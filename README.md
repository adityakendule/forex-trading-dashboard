# Forex Trading Dashboard

## 📊 Dashboard File

The Power BI dashboard file (~150MB) is not included due to size limits.

You can download it here:  
🔗 [Download Dashboard](https://drive.google.com/file/d/1p4q0fZvgGFg8zzae--Ge35Tq1JngpqEK/view?usp=sharing)

---

An end-to-end foreign exchange market analysis project — raw Kaggle data processed in Python and visualized through an interactive Power BI dashboard covering 340 currency pairs from 1996 to 2021.

---

## Dashboard Preview

<img width="1307" height="739" alt="fx_dashboard_preview" src="https://github.com/user-attachments/assets/65287b49-76e7-47e3-902d-ed040074f2f3" />


---

## Project Overview

This project analyzes historical FX market data to identify best and worst performing currency pairs, simulate investment growth, and track year-on-year returns across 340 global currency pairs over a 25-year period.

**Key highlights from the dashboard:**
- 340 total currency pairs analyzed
- Max volatility recorded: 1,515.35K% (USD/IQD)
- Best performing pair: USD/IQD
- Worst performing pair: USD/BGN
- Date range: October 1996 – August 2021

---

## Tech Stack

| Tool | Purpose |
|---|---|
| Python (Pandas) | Data cleaning & transformation |
| VS Code | Exploratory data analysis (EDA) |
| Power BI | Interactive dashboard |
| CSV | Data storage |
| Kaggle | Data source |

---

## Project Files

```
forex-trading-dashboard/
├── forex_analysis.ipynb       # Python notebook — data cleaning & EDA
├── fx_dashboard.pbix          # Power BI dashboard file
├── data/
│   ├── forex_data.csv         # Raw data from Kaggle
│   ├── forex_processed.csv    # Cleaned & transformed data
│   └── forex_summary.csv      # Aggregated summary data
├── screenshots/
│   └── dashboard_preview.png  # Dashboard screenshot
└── README.md
```


---

## Dashboard Features

- **Investment simulator** — adjustable slider to set any starting investment value
- **Date range filter** — filter analysis between 1996 and 2021
- **Currency pair selector** — search and select any of the 340 pairs
- **Closing price trend** — historical closing value per currency pair
- **Investment value over time** — growth of simulated investment
- **Year-on-year returns (%)** — annual return comparison across pairs

---

## Data Pipeline

```
Kaggle (forex_data.csv)
        ↓
Python / Jupyter Notebook
  - Null handling & deduplication
  - Date parsing & formatting
  - Volatility & return calculations
  - Aggregation → forex_summary.csv
        ↓
Power BI (fx_dashboard.pbix)
  - Data model & relationships
  - DAX measures (volatility, returns, investment value)
  - Interactive visuals & slicers
```

---

## How to Run

### Python Script
```bash
pip install pandas
python forex_analysis.ipynb
```
### Power BI Dashboard
1. Download and install [Power BI Desktop](https://powerbi.microsoft.com/desktop/)
2. Open `fx_dashboard.pbix`
3. Refresh data source path if prompted

---

## Data Source

Raw data obtained from **Kaggle** — Historical Forex (FX) rates dataset.  
Original file: `[forex.csv](https://www.kaggle.com/datasets/dhruvildave/currency-exchange-rates)`

---

## Author

**Aditya Kendule**  
[GitHub Profile](https://github.com/adityakendule)  
[LinkedIn](https://www.linkedin.com/in/aditya-kendule-a63059199/)
