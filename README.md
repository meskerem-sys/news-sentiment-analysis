# Financial News and Stock Price Analysis

## Project Overview
This project aims to analyze the relationship between financial news headlines and stock market movements. By leveraging data science techniques, we explore how news sentiment and volume correlate with technical indicators and daily stock returns for major companies like Apple (AAPL).

## Key Tasks Completed

### Task 1: Exploratory Data Analysis (EDA)
- **Descriptive Statistics:** Analyzed news headline lengths and publication frequencies.
- **Time-Series Analysis:** Identified "rush hours" for financial news and identified volume spikes related to market events.
- **Publisher Analysis:** Extracted and categorized news sources and domains.

### Task 2: Quantitative Analysis
- **Technical Indicators:** Calculated **SMA**, **EMA**, **RSI**, and **MACD** using `TA-Lib`.
- **Financial Metrics:** Computed daily returns and rolling volatility using `Pandas`.
- **Visualization:** Created a multi-panel dashboard syncing price action with momentum and trend indicators.

### Task 3: Correlation Analysis
- **Data Alignment:** Synchronized news publication dates with stock market trading days.
- **Sentiment Analysis:** Utilized `TextBlob` to quantify news headline sentiment.
- **Correlation Mapping:** Visualized the relationship between news volume/sentiment and daily stock returns.

## Technical Stack
- **Languages:** Python 3.13
- **Libraries:** Pandas, NumPy, Matplotlib, Seaborn, TA-Lib, YFinance, TextBlob
- **Version Control:** Git & GitHub (CI/CD via GitHub Actions)

## How to Run
1. Clone the repository.
2. Install dependencies: `pip install -r requirements.txt`
3. Run the notebooks in the `notebooks/` directory.