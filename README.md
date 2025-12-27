# TCS Stock Analysis & Prediction

### Project Overview
This project analyzes the historical stock data of Tata Consultancy Services (TCS) to understand price trends, trading volumes, and volatility patterns. It also predicts future stock prices using linear regression based on engineered features.

### Key Objectives
- Explore historical TCS stock data using EDA and visualizations.
- Identify key trends, moving averages, and volatility patterns.
- Feature engineering: lag features, date-based features, and rolling averages.
- Build and evaluate a predictive model for closing prices.
- Generate actionable insights for investment and trading decisions.

### Data Used
- `TCS_stock_history.csv`: Historical daily stock prices (Open, High, Low, Close, Volume)
- Additional stock info files as provided for context.

### Analysis Workflow
1. **Data Preprocessing**
   - Handling missing values
   - Date conversion and sorting
   - Outlier analysis and log-transformed volume
2. **Exploratory Data Analysis (EDA)**
   - Price trends, OHLC movements, trading volumes
   - Moving average trend analysis (20-day & 50-day)
3. **Feature Engineering**
   - Lag features (previous day close)
   - Date features: Year, Month, Day, Day of Week
   - Validation of features using charts
4. **Modeling**
   - Linear regression to predict closing prices
   - Train/Test split and evaluation
5. **Visualization**
   - Predicted vs Actual plots
   - Scatter plots for accuracy
6. **Insights & Conclusion**
   - Market trend analysis
   - Impact of volume on price
   - Limitations and future scope

### Key Findings
- TCS exhibits long-term growth with occasional volatility spikes.
- Lag features and moving averages improve predictive performance.
- Trading volume spikes correspond to major market events.
- Linear regression captures overall trends but not sudden shocks.

### Author
Gourab Bain

Data Analyst | Python | Jupyter |
