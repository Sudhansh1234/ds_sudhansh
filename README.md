# Data Science Assignment - Web3 Trading Team

## 📂 Project Overview
This project analyzes the relationship between trader behavior and market sentiment using two key datasets:
1. **Bitcoin Market Sentiment Dataset** - Contains fear/greed index data
2. **Historical Trader Data from Hyperliquid** - Contains detailed trading transaction data

## 🎯 Objective
Analyze how trading behavior (profitability, risk, volume, leverage) aligns or diverges from overall market sentiment (fear vs greed). Identify hidden trends or signals that could influence smarter trading strategies.

## 📁 Project Structure
```
ds_candidate/
├── notebook_1.ipynb          # Main analysis notebook (Google Colab)
├── csv_files/                # All CSV data files
│   ├── fear_greed_index.csv  # Bitcoin market sentiment data
│   └── historical_data.csv   # Hyperliquid trading data
├── outputs/                  # Visual outputs and charts
│   └── *.png / *.jpg        # EDA charts and analysis results
├── ds_report.pdf            # Final summarized insights
└── README.md                # This file
```

## 📊 Datasets

### 1. Bitcoin Market Sentiment Dataset
- **Columns**: `timestamp`, `value`, `classification`, `date`
- **Classification Categories**: Extreme Fear, Fear, Neutral, Greed, Extreme Greed
- **Time Period**: 2018-2024

### 2. Historical Trader Data from Hyperliquid
- **Columns**: Account, Coin, Execution Price, Size Tokens, Size USD, Side, Timestamp IST, Start Position, Direction, Closed PnL, Transaction Hash, Order ID, Crossed, Fee, Trade ID, Timestamp
- **Data Type**: Individual trading transactions
- **Time Period**: Recent trading data

## 🚀 Setup Instructions

### Prerequisites
- Google Colab account
- Python 3.7+
- Required libraries (will be installed in notebook):
  - pandas
  - numpy
  - matplotlib
  - seaborn
  - plotly
  - scikit-learn

### Getting Started
1. Open the Google Colab notebook (`notebook_1.ipynb`)
2. Upload the CSV files from the `csv_files/` directory
3. Run the analysis cells sequentially
4. Download generated visualizations to the `outputs/` directory

## 📈 Analysis Plan

### Phase 1: Data Exploration
- Load and examine both datasets
- Check data quality and handle missing values
- Perform initial exploratory data analysis

### Phase 2: Data Preprocessing
- Align timestamps between datasets
- Create sentiment-based trading periods
- Calculate trading metrics (profitability, risk, volume, leverage)

### Phase 3: Analysis
- Compare trading behavior across different sentiment periods
- Identify correlations between sentiment and trading metrics
- Analyze risk-adjusted returns by sentiment

### Phase 4: Visualization & Insights
- Create comprehensive visualizations
- Generate actionable insights
- Document findings in the final report

## 📝 Deliverables
- [ ] Google Colab notebook with complete analysis
- [ ] Visual outputs in `outputs/` directory
- [ ] Final report (`ds_report.pdf`)
- [ ] GitHub repository with same structure

