# 📊 Analysis of Dialog Axiata PLC Stock Trends and World Oil Prices (2009–2023)

This project includes a comprehensive analysis of:

1. 📈 **Dialog Axiata PLC stock trends** (2009–2023)
2. 🛢️ **Global oil price movements** during the same period
3. 🔍 **Statistical tests and model interpretations** to explore relationships and behavioral insights using advanced statistical methods

---

## 🧾 Dataset Summary

### 📈 Dialog Axiata PLC Stock Data

- **Source**: Colombo Stock Exchange (CSE)
- **Fields**: Date, Open, High, Low, Close, Volume
- **Range**: 2009–2023 (Daily)

### 🛢️ Global Oil Price Data

- **Source**: Open-source global oil price databases
- **Fields**: Date, Crude Oil Price (USD)
- **Range**: 2009–2023 (Daily/Weekly)

---

## 📊 Part 1: Dialog Axiata PLC Stock Trends

### 🔍 Objective

To visualize and interpret the stock performance of Dialog Axiata PLC over 14 years.

### 📌 Key Analyses

- Trend analysis with time-series plots
- Moving averages and volatility tracking
- Volume and price relationship study
- Event annotations (e.g., COVID-19, national crises)

### 📈 Insights

- Clear impact of external events on stock prices
- Periodic recoveries post-crisis
- Stock is moderately volatile with growth periods between 2013–2016 and post-2021

---

## 🛢️ Part 2: World Oil Price Trends

### 🔍 Objective

To understand global oil price fluctuations from 2009 to 2023 and their potential macroeconomic implications.

### 📌 Key Analyses

- Time series visualization
- Rolling averages and trendline smoothing
- Event-based disruptions (e.g., 2014 price crash, 2020 pandemic shock)

### 📈 Insights

- Major shocks observed: 2014 crash, 2020 collapse, and 2022 surge
- Post-COVID period marked by rapid price recovery

---

## 🔗 Part 3: Relationship Between Oil Prices & Dialog Stock

### 🔍 Objective

To explore whether global oil prices influence Dialog Axiata PLC’s stock performance.

### 🧪 Methodology

- Data merged by date
- Pearson correlation coefficient
- Simple linear regression using `scikit-learn`
- Comparative visualizations (scatter & dual-line plots)

### 📈 Findings

- Weak but positive correlation
- Global oil prices may reflect broader economic shifts but are not sole influencers of Dialog stock behavior

---

## 📊 Part 4: Extended Statistical Analysis

**Notebook**: `isaramadunika_Advanced_Statistics_for_Data_Science_01 (4).ipynb`

### 🔍 Objective

To apply formal statistical hypothesis testing to verify relationships within and between datasets.

### 🧪 Tests Performed

- **T-tests**: Mean differences in stock performance between periods
- **Chi-Square Tests**: Independence between categorical events (e.g., price categories vs volume)
- **Correlation Matrix**: Multivariate comparison of oil price, Dialog price, and volume metrics

### 📈 Results

- Significant differences observed in certain timeframes (e.g., COVID vs pre-COVID)
- Some variables (e.g., volume & closing price) show moderate correlation
- Chi-square indicates non-random relationships in price-volume interactions

---

## 🛠️ Tools Used

- **Languages**: Python (Jupyter Notebook)
- **Libraries**:
  - `pandas`, `numpy`
  - `matplotlib`, `seaborn`
  - `scikit-learn`, `scipy`
- Visual summaries exported as `.pdf` and `.ipynb`

---

## 🚀 How to Run

1. Clone or download the repository
2. Open and run the following notebooks:
   - `STAT_F (1).ipynb`
   - `isaramadunika_Advanced_Statistics_for_Data_Science_01 (4).ipynb`
3. Ensure required libraries are installed:
   ```bash
   pip install pandas numpy matplotlib seaborn scikit-learn scipy

---

## 📚 Acknowledgments
### This project was completed by Group E for the Advanced Statistics for Data Science module at NSBM Green University.
