<!--
README for CRYPTO-MARKET-ANALYSIS
This project is a Streamlit dashboard that analyzes Bitcoin trader performance
in relation to market sentiment (Fear & Greed Index). The repository includes
data samples, analysis notebooks, and multiple Streamlit app variants.
-->

# 🚀 Bitcoin Trader Performance vs Market Sentiment Analysis

Interactive Streamlit dashboard and analysis exploring how market sentiment
(Fear & Greed Index) relates to trader performance on Hyperliquid DEX.

Key deliverables:
- Streamlit dashboard: `streamlit_app_final.py` (primary app)
- Supporting variants: `streamlit_app.py`, `streamlit_app_enhanced.py`, `streamlit_complete_integrated.py`
- Analysis notebook: `trader_sentiment_analysis.ipynb`

---

## Quick summary

- Language: Python 3.8+
- Main libs: Streamlit, Pandas, NumPy, Plotly, SciPy
- Data files (required at runtime): `fear_greed_index.csv`, `historical_data.csv`

---

## Features

- Multi-page Streamlit dashboard with:
   - Assignment details and instructions
   - Summary dashboard (metrics, distributions, timeseries)
   - Advanced analytics (statistical tests and correlations)
   - Risk analysis (Sharpe, volatility, drawdown)
   - Deep-dive trade-level views and filters
- Interactive Plotly visualizations
- Data export for filtered results

---

## Quick start (Windows / PowerShell)

1. Open PowerShell and change to the project directory:

```powershell
cd "c:/Users/amara/Downloads/CRYPTO-MARKET-ANALYSIS-main/CRYPTO-MARKET-ANALYSIS-main"
```

2. (Optional but recommended) create and activate a virtual environment:

```powershell
python -m venv .venv
.\.venv\Scripts\Activate.ps1
```

3. Install dependencies:

```powershell
python -m pip install --upgrade pip
python -m pip install -r requirements.txt
```

4. Run the Streamlit dashboard:

```powershell
python -m streamlit run streamlit_app_final.py
```

The app should open in your browser at `http://localhost:8501` (or another free port if 8501 is in use).

---

## Data files

Place the following CSV files in the same directory as the Streamlit app (they are included in this repo):

- `fear_greed_index.csv` — daily Fear & Greed index values (timestamp, value, classification, date)
- `historical_data.csv` — trade-level data (Account, Coin, Execution Price, Size Tokens, Size USD, Side, Timestamp IST, Closed PnL, Fee, ...)

The app's `load_data()` function reads these filenames directly; if you store them elsewhere, update the path in `streamlit_app_final.py`.

---

## Running tests / quick checks

- There is a helper `test_app.py` that performs basic checks (syntax, presence of pages and components).
   Run it with:

```powershell
python test_app.py
```

---

## Troubleshooting

- ModuleNotFoundError for libraries (e.g. `plotly`, `scipy`):
   - Ensure you installed requirements with `python -m pip install -r requirements.txt`.
   - You can install a missing package directly: `python -m pip install scipy`

- CSV not found error:
   - Confirm `fear_greed_index.csv` and `historical_data.csv` exist in the working directory.
   - The app reads them with `pd.read_csv('fear_greed_index.csv')` and `pd.read_csv('historical_data.csv')`.
   - If you prefer absolute paths, update `load_data()` in `streamlit_app_final.py`.

- Port already in use:
   - Run Streamlit with a different port: `python -m streamlit run streamlit_app_final.py --server.port 8502`

- Streamlit command not found in PowerShell:
   - Use the Python module invocation: `python -m streamlit run streamlit_app_final.py` (works even if `streamlit` CLI isn't on PATH).

---

## Project structure (important files)

- `streamlit_app_final.py` — primary Streamlit app (entrypoint)
- `streamlit_app.py`, `streamlit_app_enhanced.py`, `streamlit_complete_integrated.py` — app variations
- `test_app.py` — lightweight checks used during development
- `historical_data.csv`, `fear_greed_index.csv` — data
- `trader_sentiment_analysis.ipynb` — exploratory analysis notebook
- `requirements.txt` — dependency list

---

## Notes for maintainers

- The `load_data()` function in `streamlit_app_final.py` is the single place to change data paths or preprocessing steps.
- Large `historical_data.csv` (~200k+ rows) can be slow to load; consider sampling or using a faster on-disk format (Parquet) for production.

---

## Contact / Author

- Amar Sharma
- Email: amarsharma358135@gmail.com
- GitHub: https://github.com/amarsharma23

---

## License

This project is provided under the MIT License. See `LICENSE` (if present) or consider adding one if you plan to publish.


---- ✅ **40+ Interactive Visualizations** using PlotlyOr install packages individually:

## ⚠️ Disclaimer### Quick Start

**For educational purposes only.** Not financial advice. Cryptocurrency trading involves substantial risk.- ✅ **Statistical Testing** (ANOVA, Chi-Square, Mann-Whitney U)

---``````bash

<div align="center"># Clone repository- ✅ **Risk Metrics** (Sharpe Ratio, Volatility, Drawdown)---

**⭐ Star this repository if you found it helpful!**git clone https://github.com/amarsharma23/CRYPTO-MARKET-ANALYSIS.git

Made with ❤️ by [Amar Sharma](https://github.com/amarsharma23)cd CRYPTO-MARKET-ANALYSIS- ✅ **Time Series Analysis** with rolling statistics

_Last Updated: November 2025_

</div># Install dependencies`````powershell

pip install -r requirements.txt

### Interactive Dashboard

# Run dashboard

streamlit run streamlit_app_final.py- 🎯 **5 Specialized Pages** for different perspectives## 🎯 Overviewpip install pandas numpy matplotlib seaborn streamlit plotly jupyter notebook ipykernel

``````

- 🔄 **Real-time Filtering** by date, sentiment, side

### Using Virtual Environment

- 📈 **Dynamic Visualizations** updating on user selection```

```bash

# Create environment- 💾 **Data Export** for filtered datasets

python -m venv venv

- 📱 **Responsive Design** for desktop and tabletThis project provides a **comprehensive analytical framework** for examining the relationship between Bitcoin trader performance on the Hyperliquid DEX and market sentiment as measured by the Fear & Greed Index. The platform combines rigorous statistical analysis with interactive visualizations to uncover actionable trading insights.

# Activate (Windows)

venv\Scripts\activate



# Activate (macOS/Linux)---## 📓 Running the Jupyter Notebook

source venv/bin/activate



# Install and run

pip install -r requirements.txt## 🌐 Live Demo### 🎓 Project Context

streamlit run streamlit_app_final.py

```

---**[Access the Dashboard](https://crypto-market-analysis.streamlit.app)**### Option 1: Using Jupyter Notebook

## 📖 Usage

### Jupyter Notebook

**Author:** Amar Sharma

For detailed statistical analysis and the full walkthrough, open the notebook:

```bash
jupyter notebook trader_sentiment_analysis.ipynb
```

````- Export functionality



**Contents:**- Mobile-responsive interface**Phone:** +91 9572549281 jupyter notebook trader_sentiment_analysis.ipynb



- Data preprocessing

- Exploratory analysis

- Statistical testing---**Purpose:** Advanced Data Analysis Assignment ```

- Correlation analysis

- Visualizations

- Key findings

## 🛠️ Installation**Domain:** Cryptocurrency Trading Analytics

### Streamlit Dashboard



For interactive exploration:

### Prerequisites### Option 2: Using Jupyter Lab

```bash

streamlit run streamlit_app_final.py- Python 3.8+

````

- pip package manager### 🔍 Research Questions

**Pages:**

- Git

1. **📋 Assignment Details** - Overview and author info

2. **🏠 Dashboard** - Metrics and distributions````powershell

3. **📊 Advanced Analytics** - Statistical tests

4. **📈 Risk Analysis** - Risk-adjusted metrics### Quick Start

5. **🔍 Deep Dive** - Trade-level analysis

6. How does market sentiment (Fear & Greed) correlate with trading profitability?jupyter lab trader_sentiment_analysis.ipynb

---

````bash

## 📁 Project Structure

# Clone repository2. Do traders exhibit different behavioral patterns during extreme market conditions?```

````

CRYPTO-MARKET-ANALYSIS/git clone https://github.com/amarsharma23/CRYPTO-MARKET-ANALYSIS.git

│

├── Data Filescd CRYPTO-MARKET-ANALYSIS3. What are the optimal sentiment conditions for maximizing risk-adjusted returns?

│ ├── fear_greed_index.csv # Fear & Greed Index

│ └── historical_data.csv # Trading data (211K+ trades)

│

├── Analysis# Install dependencies4. How do trading fees impact profitability across different sentiment regimes?### Option 3: Using VS Code

│ └── trader_sentiment_analysis.ipynb

│pip install -r requirements.txt

├── Dashboard

│ ├── streamlit_app_final.py # Main app (2,102 lines)

│ ├── streamlit_app_enhanced.py

│ ├── streamlit_continuation_part1.py# Run dashboard

│ ├── streamlit_continuation_part2.py

│ └── streamlit_continuation_part3.pystreamlit run streamlit_app_final.py---1. Open `trader_sentiment_analysis.ipynb` in VS Code

│

├── Configuration`````

│ ├── requirements.txt

│ ├── merge_streamlit_files.py2. Select Python kernel

│ └── test_app.py

│### Using Virtual Environment

└── Documentation

    ├── README.md## ✨ Key Features3. Run all cells or run cells individually

    ├── PROJECT_README.md

    ├── QUICKSTART.txt````bash

    └── FINAL_SUMMARY.md

`````# Create environment



---python -m venv venv



## 📊 Data Sources### 📊 **Comprehensive Analysis Suite**## 🌐 Running the Streamlit Dashboard



### 1. Fear & Greed Index# Activate (Windows)



**Source:** Alternative.me API  venv\Scripts\activate

**Period:** 2024

**Records:** 365 daily observations



| Column | Description |# Activate (macOS/Linux)- ✅ **15 Analysis Sections** covering all aspects of sentiment-based trading```powershell

|--------|-------------|

| `timestamp` | Unix timestamp |source venv/bin/activate

| `value` | Index (0-100) |

| `classification` | Sentiment category |- ✅ **40+ Interactive Visualizations** using Plotly and Matplotlibstreamlit run streamlit_app.py

| `date` | YYYY-MM-DD |

# Install and run

**Classifications:**

pip install -r requirements.txt- ✅ **Statistical Testing** including ANOVA, Chi-Square, Mann-Whitney U, Kruskal-Wallis```

- 🔴 Extreme Fear (0-24)

- 🟠 Fear (25-44)streamlit run streamlit_app_final.py

- 🟡 Neutral (45-55)

- 🟢 Greed (56-75)```- ✅ **Risk Metrics** including Sharpe Ratio, Volatility, Drawdown Analysis

- 🔵 Extreme Greed (76-100)



### 2. Trading Data

---- ✅ **Time Series Analysis** with rolling statistics and trend detectionThe dashboard will automatically open in your default web browser at `http://localhost:8501`

**Source:** Hyperliquid DEX

**Period:** December 2024

**Records:** 211,226 trades

## 📖 Usage

| Column | Description |

|--------|-------------|

| `Account` | Wallet address |

| `Size USD` | Position size |### Jupyter Notebook### 🎨 **Interactive Streamlit Dashboard**## 📊 Features

| `Side` | BUY/SELL |

| `Timestamp IST` | Trade time |

| `Closed PnL` | Profit/loss |

| `Fee` | Trading fee |For detailed statistical analysis:



**Derived Metrics:**



- `Net_PnL` = Closed PnL - Fee```bash- 🎯 **5 Specialized Pages** for different analytical perspectives### Jupyter Notebook Analysis

- `PnL_Percentage` = (Net_PnL / Size USD) × 100

- `is_profitable` = Net_PnL > 0jupyter notebook trader_sentiment_analysis.ipynb

- `Trading_Session` = Asian/European/American

```- 🔄 **Real-time Filtering** by date, sentiment, trade side, and profitability

---



## 🎨 Dashboard Features

**Contents:**- 📈 **Dynamic Visualizations** that update based on user selectionsThe notebook provides:

### Page 1: Assignment Details

- Data preprocessing

- Project overview

- Research objectives- Exploratory analysis- 💾 **Data Export** capabilities for filtered datasets

- Author information

- Methodology- Statistical testing

- Technology stack

- Correlation analysis- 📱 **Responsive Design** optimized for desktop and tablet viewing✅ **Data Loading & Cleaning**

### Page 2: Dashboard (4 Tabs)

- Visualizations

1. **Overview** - Metrics and pie charts

2. **Performance** - PnL by sentiment- Key findings

3. **Time Series** - Cumulative trends

4. **Distribution** - Box plots



### Page 3: Advanced Analytics (4 Tabs)### Streamlit Dashboard### 🧠 **Advanced Analytics**- Automated data preprocessing



1. **Statistical Tests** - ANOVA, Chi-Square

2. **Correlation** - Heatmaps

3. **Behavioral Patterns** - Hourly/dailyFor interactive exploration:- Date/time formatting

4. **Key Insights** - Automated findings



### Page 4: Risk Analysis (4 Tabs)

```bash- 🤖 Machine Learning feature engineering- Missing data handling

1. **Risk-Reward** - Sharpe ratios

2. **Position Sizing** - Size distributionsstreamlit run streamlit_app_final.py

3. **Time Analysis** - Session performance

4. **Insights** - Risk recommendations```- 📊 Multi-dimensional correlation analysis



### Page 5: Deep Dive (4 Tabs)



1. **Trade Explorer** - Top 10 trades**Pages:**- ⏰ Temporal pattern detection (hourly, daily, monthly)✅ **Exploratory Data Analysis**

2. **Trade Sides** - BUY vs SELL

3. **Fee Analysis** - Cost breakdown1. **📋 Assignment Details** - Overview and author info

4. **Advanced Metrics** - Custom analysis

2. **🏠 Dashboard** - Metrics and distributions- 💰 Fee impact and optimization analysis

---

3. **📊 Advanced Analytics** - Statistical tests

## 🛠️ Technologies

4. **📈 Risk Analysis** - Risk-adjusted metrics- 🎲 Monte Carlo simulations for risk assessment- Overall performance metrics

| Technology | Version | Purpose |

|-----------|---------|---------|5. **🔍 Deep Dive** - Trade-level analysis

| **Python** | 3.8+ | Core language |

| **Streamlit** | 1.28+ | Dashboard |- Sentiment distribution analysis

| **Pandas** | 2.0+ | Data manipulation |

| **NumPy** | 1.24+ | Numerical computing |---

| **Plotly** | 5.17+ | Visualizations |

| **SciPy** | 1.10+ | Statistics |---- Trade side patterns

| **scikit-learn** | 1.3+ | ML utilities |

## 📁 Project Structure

**Visualization Types:**



- 📊 Bar charts

- 📈 Line charts````

- 📉 Box plots

- 🔥 HeatmapsCRYPTO-MARKET-ANALYSIS/## 🌐 Live Demo✅ **Advanced Visualizations**

- 🥧 Pie charts

- 📐 Scatter plots│



---├── Data Files



## 🔧 Troubleshooting│ ├── fear_greed_index.csv # Fear & Greed Index



### ModuleNotFoundError: scipy│ └── historical_data.csv # Trading data (211K+ trades)**🔗 [Access the Live Dashboard](https://crypto-market-analysis.streamlit.app)**- PnL by sentiment (bar charts)



```bash│

pip install scipy>=1.10.0

# Or├── Analysis- Win rate analysis

pip install -r requirements.txt --upgrade

```│ └── trader_sentiment_analysis.ipynb



### KeyError: Column names│The interactive dashboard is deployed on Streamlit Cloud and provides:- Cumulative PnL time series



Fixed in latest version. Use:├── Dashboard



- `'Closed PnL'` instead of `'Realized Profit'`│ ├── streamlit_app_final.py # Main app (2,102 lines)- Real-time data filtering and visualization- Sentiment vs performance correlation heatmaps

- `'Fee'` instead of `'Fee USD'`

│ ├── streamlit_app_enhanced.py

### Streamlit deprecation warnings

│ ├── streamlit_continuation_part1.py- Complete assignment explanation with author details- Risk-adjusted return metrics

Already fixed - all `use_container_width` replaced with `width='stretch'`

│ ├── streamlit_continuation_part2.py

### CSV file not found

│ └── streamlit_continuation_part3.py- Export functionality for custom reports- Distribution box plots

Ensure data files are in the same directory as the script.

│

### Port already in use

├── Configuration- Mobile-responsive interface

```bash

streamlit run streamlit_app_final.py --server.port 8080│ ├── requirements.txt

`````

│ ├── merge_streamlit_files.py✅ **Behavioral Pattern Analysis**

---

│ └── test_app.py

## 👤 Author

│---

**Amar Sharma**

└── Documentation

- 📧 Email: [amarsharma358135@gmail.com](mailto:amarsharma358135@gmail.com)

- 📱 Phone: +91 9572549281 ├── README.md- Trading activity by hour

- 💼 GitHub: [@amarsharma23](https://github.com/amarsharma23)

- 🔗 Project: [CRYPTO-MARKET-ANALYSIS](https://github.com/amarsharma23/CRYPTO-MARKET-ANALYSIS) ├── PROJECT_README.md

--- ├── QUICKSTART.txt## 🛠️ Installation- Monthly performance breakdown

## 📄 License └── FINAL_SUMMARY.md

MIT License - See [LICENSE](LICENSE) file````- Buy vs Sell patterns by sentiment

**Permissions:**

- ✅ Commercial use---### Prerequisites- Risk metrics calculation

- ✅ Modification

- ✅ Distribution

- ✅ Private use

## 📊 Data Sources

---

## ⚠️ Disclaimer

### 1. Fear & Greed Index- Python 3.8 or higher✅ **Key Insights & Recommendations**

**For educational purposes only.**

This analysis should NOT be considered financial advice. Cryptocurrency trading involves substantial risk. Always conduct your own research and consult qualified financial advisors.

**Source:** Alternative.me API - pip package manager

---

**Period:** 2024

## 🙏 Acknowledgments

**Records:** 365 daily observations- Git (for cloning the repository)- Best/worst performing sentiments

- **Alternative.me** - Fear & Greed Index data

- **Hyperliquid** - DEX trading data

- **Streamlit** - Dashboard framework

- **Plotly** - Visualization library| Column | Description |- Risk-reward optimization

- **Python Community** - Data science tools

|--------|-------------|

---

| `timestamp` | Unix timestamp |### Quick Start- Strategic trading recommendations

<div align="center">

| `value` | Index (0-100) |

**⭐ Star this repository if you found it helpful!**

| `classification` | Sentiment category |- Fee impact analysis

Made with ❤️ by [Amar Sharma](https://github.com/amarsharma23)

| `date` | YYYY-MM-DD |

_Last Updated: November 2025_

````bash

</div>

**Classifications:**

- 🔴 Extreme Fear (0-24)# Clone the repository### Streamlit Dashboard Features

- 🟠 Fear (25-44)

- 🟡 Neutral (45-55)git clone https://github.com/amarsharma23/CRYPTO-MARKET-ANALYSIS.git

- 🟢 Greed (56-75)

- 🔵 Extreme Greed (76-100)cd CRYPTO-MARKET-ANALYSISThe interactive dashboard includes:



### 2. Trading Data



**Source:** Hyperliquid DEX  # Install dependencies🎯 **Interactive Filters**

**Period:** December 2024

**Records:** 211,226 tradespip install -r requirements.txt



| Column | Description |- Date range selection

|--------|-------------|

| `Account` | Wallet address |# Run the Streamlit dashboard- Sentiment category filtering

| `Size USD` | Position size |

| `Side` | BUY/SELL |streamlit run streamlit_app_final.py- Trade side filtering (BUY/SELL)

| `Timestamp IST` | Trade time |

| `Closed PnL` | Profit/loss |```- PnL filtering (All/Profitable/Unprofitable)

| `Fee` | Trading fee |



**Derived Metrics:**

- `Net_PnL` = Closed PnL - Fee### Alternative: Using Virtual Environment📊 **Multiple Analysis Tabs**

- `PnL_Percentage` = (Net_PnL / Size USD) × 100

- `is_profitable` = Net_PnL > 0

- `Trading_Session` = Asian/European/American

```bash1. **Overview Tab:**

---

# Create virtual environment

## 🎨 Dashboard Features

python -m venv venv   - Sentiment distribution pie charts

### Page 1: Assignment Details

- Project overview   - PnL contribution by sentiment

- Research objectives

- Author information# Activate virtual environment   - Comprehensive performance tables

- Methodology

- Technology stack# Windows:



### Page 2: Dashboard (4 Tabs)venv\Scripts\activate2. **PnL Analysis Tab:**

1. **Overview** - Metrics and pie charts

2. **Performance** - PnL by sentiment# macOS/Linux:

3. **Time Series** - Cumulative trends

4. **Distribution** - Box plotssource venv/bin/activate   - Win rate comparisons



### Page 3: Advanced Analytics (4 Tabs)   - Average PnL metrics

1. **Statistical Tests** - ANOVA, Chi-Square

2. **Correlation** - Heatmaps# Install dependencies   - Distribution box plots

3. **Behavioral Patterns** - Hourly/daily

4. **Key Insights** - Automated findingspip install -r requirements.txt



### Page 4: Risk Analysis (4 Tabs)3. **Time Series Tab:**

1. **Risk-Reward** - Sharpe ratios

2. **Position Sizing** - Size distributions# Run the application

3. **Time Analysis** - Session performance

4. **Insights** - Risk recommendationsstreamlit run streamlit_app_final.py   - Cumulative PnL vs sentiment index



### Page 5: Deep Dive (4 Tabs)```   - Rolling performance metrics

1. **Trade Explorer** - Top 10 trades

2. **Trade Sides** - BUY vs SELL   - Customizable moving averages

3. **Fee Analysis** - Cost breakdown

4. **Advanced Metrics** - Custom analysis---



---4. **Risk Metrics Tab:**



## 🛠️ Technologies## 📖 Usage



| Technology | Version | Purpose |   - Sharpe ratio analysis

|-----------|---------|---------|

| **Python** | 3.8+ | Core language |### 1️⃣ **Jupyter Notebook Analysis**   - Volatility metrics

| **Streamlit** | 1.28+ | Dashboard |

| **Pandas** | 2.0+ | Data manipulation |   - Risk-adjusted returns

| **NumPy** | 1.24+ | Numerical computing |

| **Plotly** | 5.17+ | Visualizations |For in-depth statistical analysis and detailed insights:

| **SciPy** | 1.10+ | Statistics |

| **scikit-learn** | 1.3+ | ML utilities |5. **Deep Dive Tab:**



**Visualization Types:**```bash

- 📊 Bar charts

- 📈 Line charts# Launch Jupyter Notebook   - Behavioral pattern analysis

- 📉 Box plots

- 🔥 Heatmapsjupyter notebook trader_sentiment_analysis.ipynb   - Correlation heatmaps

- 🥧 Pie charts

- 📐 Scatter plots   - Monthly performance breakdown



---# Or use Jupyter Lab   - Hourly trading activity



## 🔧 Troubleshootingjupyter lab trader_sentiment_analysis.ipynb



### ModuleNotFoundError: scipy```6. **Insights Tab:**



```bash   - Automated key findings

pip install scipy>=1.10.0

# Or**Notebook Contents:**   - Strategic recommendations

pip install -r requirements.txt --upgrade

```- Data loading and preprocessing   - Risk management suggestions



### KeyError: 'Realized Profit' or 'Fee USD'- Exploratory data analysis (EDA)   - Fee impact analysis



Fixed in latest version. Use:- Statistical hypothesis testing

- `'Closed PnL'` instead of `'Realized Profit'`

- `'Fee'` instead of `'Fee USD'`- Correlation and regression analysis## 📈 Data Sources



### Streamlit deprecation warnings- Visualization gallery



Already fixed - all `use_container_width` replaced with `width='stretch'`- Key findings and recommendations### 1. fear_greed_index.csv



### CSV file not found



Ensure data files are in the same directory as the script.### 2️⃣ **Streamlit Dashboard****Columns:**



### Port already in use



```bashFor interactive exploration and presentation:- `timestamp`: Unix timestamp

streamlit run streamlit_app_final.py --server.port 8080

```- `value`: Fear & Greed index value (0-100)



---```bash- `classification`: Sentiment category (Extreme Fear, Fear, Neutral, Greed, Extreme Greed)




## 👤 Author

**Amar Sharma**

- 📧 Email: [amarsharma358135@gmail.com](mailto:amarsharma358135@gmail.com)
- 📱 Phone: +91 9572549281
- 💼 GitHub: [@amarsharma23](https://github.com/amarsharma23)
- 🔗 Project: [CRYPTO-MARKET-ANALYSIS](https://github.com/amarsharma23/CRYPTO-MARKET-ANALYSIS)

Run the dashboard:

```bash
streamlit run streamlit_app_final.py --server.port 8080
```

---

- Fear: 25-44

## 📄 License

# Open in browser- Neutral: 45-55

MIT License - See [LICENSE](LICENSE) file

# Navigate to http://localhost:8501- Greed: 56-75

**Permissions:**

- ✅ Commercial use```- Extreme Greed: 76-100

- ✅ Modification

- ✅ Distribution

- ✅ Private use

**Dashboard Navigation:**### 2. historical_data.csv

---

1. **📋 Assignment Details** - Project overview and author information

## ⚠️ Disclaimer

2. **🏠 Dashboard** - High-level metrics and sentiment distribution**Key Columns:**

**For educational purposes only.**

3. **📊 Advanced Analytics** - Statistical tests and correlations

This analysis should NOT be considered financial advice. Cryptocurrency trading involves substantial risk. Always conduct your own research and consult qualified financial advisors.

4. **📈 Risk Analysis** - Risk-adjusted performance metrics- `Account`: Trader account address

---

5. **🔍 Deep Dive** - Granular trade analysis and data export- `Coin`: Trading symbol

## 🙏 Acknowledgments

- `Execution Price`: Trade execution price

- **Alternative.me** - Fear & Greed Index data

- **Hyperliquid** - DEX trading data---- `Size Tokens`: Position size in tokens

- **Streamlit** - Dashboard framework

- **Plotly** - Visualization library- `Size USD`: Position size in USD

- **Python Community** - Data science tools

## 📁 Project Structure- `Side`: Trade direction (BUY/SELL)

---

- `Timestamp IST`: Trade timestamp

<div align="center">

```- `Closed PnL`: Profit/Loss from closed positions

**⭐ Star this repository if you found it helpful!**

CRYPTO-MARKET-ANALYSIS/- `Fee`: Trading fees

Made with ❤️ by [Amar Sharma](https://github.com/amarsharma23)

│- `Leverage`: Position leverage

*Last Updated: November 2025*

├── 📊 Data Files

</div>

│   ├── fear_greed_index.csv           # Bitcoin Fear & Greed Index (2024)## 🔍 Analysis Objectives

│   └── historical_data.csv             # Hyperliquid trading data (211K+ trades)

│1. **Explore Performance Variations:**

├── 📓 Analysis

│   └── trader_sentiment_analysis.ipynb # Comprehensive Jupyter analysis   - How do PnL, leverage, and trade sides vary with market sentiment?

│

├── 🌐 Dashboard2. **Detect Correlations:**

│   ├── streamlit_app_final.py          # Main Streamlit application (2,102 lines)

│   ├── streamlit_app_enhanced.py       # Base application file   - Identify relationships between sentiment and profitability

│   ├── streamlit_continuation_part1.py # Dashboard page

│   ├── streamlit_continuation_part2.py # Advanced Analytics page3. **Identify Behavioral Patterns:**

│   └── streamlit_continuation_part3.py # Risk & Deep Dive pages

│   - Do traders use higher leverage during Greed?

├── 🔧 Configuration   - Are losses higher during Fear?

│   ├── requirements.txt                 # Python dependencies

│   ├── merge_streamlit_files.py        # File integration script4. **Generate Insights:**

│   └── test_app.py                     # Application test suite   - Clear visualizations and actionable recommendations

│   - Smarter trading strategies based on sentiment

├── 📚 Documentation

│   ├── README.md                        # This file## 📊 Key Metrics Analyzed

│   ├── PROJECT_README.md               # Detailed project documentation

│   ├── QUICKSTART.txt                  # Quick start guide- **Total Net PnL**: Overall profitability after fees

│   ├── FINAL_SUMMARY.md                # Project summary- **Win Rate**: Percentage of profitable trades

│   └── ISSUE_RESOLVED.md               # Issue tracking- **Average PnL per Trade**: Mean profit/loss per transaction

│- **Trading Volume**: Total USD traded

└── 🧪 Testing- **Sharpe Ratio**: Risk-adjusted returns (Mean PnL / Std Dev)

    └── test_app.py                     # Automated testing script- **Volatility**: Standard deviation of PnL

```- **Fee Impact**: Trading costs as percentage of PnL



---## 🎨 Visualizations



## 📊 Data SourcesThe analysis includes:



### 1. Fear & Greed Index (`fear_greed_index.csv`)- 📊 Bar charts (PnL, Win Rate, Volume)

- 📈 Time series plots (Cumulative PnL, Sentiment trends)

**Source:** Alternative.me API  - 📉 Box plots (PnL distribution)

**Period:** January 2024 - December 2024  - 🔥 Heatmaps (Correlation matrices)

**Records:** 365 daily observations- 🥧 Pie charts (Sentiment distribution)

- 📐 Stacked bars (Buy vs Sell patterns)

| Column | Type | Description |- 📉 Rolling averages (Performance trends)

|--------|------|-------------|

| `timestamp` | int | Unix timestamp |## 💡 Example Insights

| `value` | int | Index value (0-100) |

| `classification` | str | Sentiment category |The analysis can reveal:

| `date` | date | YYYY-MM-DD format |

- **Best performing sentiment periods** for maximizing profits

**Sentiment Classification:**- **Risk-adjusted optimal trading conditions** (highest Sharpe ratio)

- 🔴 **Extreme Fear** (0-24): Maximum pessimism- **Leverage usage patterns** across different market sentiments

- 🟠 **Fear** (25-44): Below-average sentiment- **Fee optimization opportunities** to reduce costs

- 🟡 **Neutral** (45-55): Balanced market- **Temporal patterns** (best hours/days for trading)

- 🟢 **Greed** (56-75): Above-average optimism- **Directional bias** in trading strategy

- 🔵 **Extreme Greed** (76-100): Maximum euphoria

## 🔧 Troubleshooting

### 2. Trading Data (`historical_data.csv`)

### Issue: Missing packages

**Source:** Hyperliquid DEX

**Period:** December 2024  ```powershell

**Records:** 211,226 tradespip install --upgrade -r requirements.txt

````

| Column | Type | Description |

|--------|------|-------------|### Issue: CSV file not found

| `Account` | str | Trader wallet address |

| `Coin` | str | Trading pair symbol |Ensure `fear_greed_index.csv` and `historical_data.csv` are in the same directory as the scripts.

| `Execution Price` | float | Trade execution price |

| `Size Tokens` | float | Position size in tokens |### Issue: Streamlit not opening

| `Size USD` | float | Position size in USD |

| `Side` | str | BUY or SELL |```powershell

| `Timestamp IST` | datetime | Trade timestamp (IST) |# Try specifying the port

| `Closed PnL` | float | Realized profit/loss |streamlit run streamlit_app.py --server.port 8501

| `Fee` | float | Trading fee (USD) |```

**Derived Metrics:**### Issue: Jupyter kernel not found

- `Net_PnL` = Closed PnL - Fee

- `PnL_Percentage` = (Net_PnL / Size USD) × 100```powershell

- `is_profitable` = Net_PnL > 0python -m ipykernel install --user --name=myenv

- `Trading_Session` = Asian / European / American```

- `sentiment_category` = Merged from Fear & Greed Index

## 📝 Usage Examples

---

### Running Complete Analysis

## 🔬 Analysis Methodology

````powershell

### Statistical Techniques# 1. Run Jupyter Notebook for detailed analysis

jupyter notebook trader_sentiment_analysis.ipynb

1. **Descriptive Statistics**

   - Mean, median, standard deviation# 2. Launch interactive dashboard

   - Percentile analysis (25th, 50th, 75th)streamlit run streamlit_app.py

   - Distribution analysis (skewness, kurtosis)```



2. **Hypothesis Testing**### Customizing the Analysis

   - ANOVA: Compare means across sentiment groups

   - Chi-Square: Test independence of categorical variables**In Jupyter Notebook:**

   - Mann-Whitney U: Non-parametric comparison

   - Kruskal-Wallis: Non-parametric multi-group test- Modify date ranges in filtering cells

- Adjust visualization parameters

3. **Correlation Analysis**- Add custom metrics and calculations

   - Pearson correlation for linear relationships

   - Spearman correlation for monotonic relationships**In Streamlit Dashboard:**

   - Feature correlation matrices

- Use sidebar filters for dynamic analysis

4. **Risk Metrics**- Adjust rolling window sizes

   - Sharpe Ratio = (Mean PnL - Risk-free rate) / Std Dev- Export filtered data views

   - Sortino Ratio = Downside deviation analysis

   - Maximum Drawdown = Peak-to-trough decline## 📤 Exporting Results

   - Value at Risk (VaR) = 5th percentile loss

The Jupyter Notebook automatically exports:

### Feature Engineering

- `sentiment_performance_summary.csv`

```python- `risk_metrics_by_sentiment.csv`

# Time-based features- `daily_performance_with_sentiment.csv`

- Hour of day (0-23)

- Day of week (0-6)The Streamlit dashboard allows:

- Month (1-12)

- Week of year (1-52)- Screenshot captures of visualizations

- Trading session (Asian/European/American)- Interactive data exploration

- Real-time filtering and analysis

# Performance features

- Net PnL (Closed PnL - Fee)## 🎯 Best Practices

- PnL Percentage ((Net PnL / Size USD) × 100)

- Is Profitable (Boolean)1. **Data Quality:**

- Fee Ratio ((Fee / Size USD) × 100)

   - Verify CSV files are properly formatted

# Sentiment features   - Check for missing or corrupted data

- Sentiment Score (1-5 ordinal)

- Sentiment Category (Categorical)2. **Analysis:**

- Previous Day Sentiment (Lag feature)

```   - Run the Jupyter Notebook first for comprehensive insights

   - Use Streamlit dashboard for interactive exploration

---

3. **Interpretation:**

## 🎨 Dashboard Features   - Consider multiple metrics together

   - Account for market conditions and external factors

### Page 1: 📋 Assignment Details   - Validate findings with statistical significance



- **Project Overview**: Complete assignment description## 📚 Additional Resources

- **Objectives**: Clear research questions and goals

- **Author Information**: Contact details and credentials- **Streamlit Documentation**: https://docs.streamlit.io/

- **Methodology**: Data sources and analytical approach- **Plotly Documentation**: https://plotly.com/python/

- **Technology Stack**: Tools and libraries used- **Pandas Documentation**: https://pandas.pydata.org/docs/

- **Fear & Greed Index**: https://alternative.me/crypto/fear-and-greed-index/

### Page 2: 🏠 Dashboard

## 🤝 Contributing

**4 Interactive Tabs:**

Feel free to:

1. **Overview**

   - Total trades, PnL, win rate metrics- Add new visualizations

   - Sentiment distribution pie chart- Enhance filtering capabilities

   - Performance summary table- Implement additional metrics

- Improve performance optimization

2. **Performance Analysis**

   - PnL by sentiment (bar chart)## 📄 License

   - Win rate by sentiment

   - Average trade size comparisonThis project is for educational and analytical purposes.



3. **Time Series**## ⚠️ Disclaimer

   - Cumulative PnL over time

   - Sentiment value trendsThis analysis is for informational purposes only and should not be considered financial advice. Always conduct your own research and consult with financial professionals before making trading decisions.

   - Rolling averages (7-day, 30-day)

---

4. **Distribution Analysis**

   - PnL distribution box plots**Built with:** Python, Pandas, NumPy, Matplotlib, Seaborn, Plotly, Streamlit, Jupyter

   - Trade size distributions

   - Statistical summaries**Author:** Data Analysis Assignment



### Page 3: 📊 Advanced Analytics**Last Updated:** November 2025

#
``````


