# Trader Behavior Insights – Data Science Assignment
 Data Science Assignment for Primetrade.ai – Sentiment vs Trader Performance

##  Project Overview

This repository contains my completed assignment for the role of **Junior Data Scientist – Trader Behavior Insights** at Primetrade.ai.

The goal of this project is to explore the relationship between **Bitcoin market sentiment** (from the Fear/Greed Index) and **trader performance metrics** (from Hyperliquid trading data). By combining and analyzing both datasets, the objective is to uncover patterns in behavior and provide actionable insights that can inform smarter crypto trading strategies.

---

##  Datasets Used

### 1. Fear & Greed Index
- Columns: `Date`, `Sentiment` (values: "Fear" or "Greed")

### 2. Historical Trader Data
- Columns include:  
  `account`, `symbol`, `execution price`, `size`, `side`, `time`, `start position`, `event`, `closedPnL`, `leverage`, etc.

---

##  Analysis Performed

- Cleaned and preprocessed both datasets
- Merged data based on `Date` column
- Explored and visualized:
  - Distribution of sentiment
  - Closed PnL vs sentiment
  - Leverage usage vs sentiment
  - Correlation between trading features
- Derived average metrics grouped by market sentiment

---

##  Key Findings

- **Higher leverage** was used more frequently during periods of market **Greed**.
- **Average closedPnL** was significantly higher on “Greed” days than “Fear” days.
- A positive correlation between **leverage** and **PnL** was observed during Greed conditions.
- The insights suggest that traders take more aggressive positions during optimistic sentiment phases.

---

##  Technologies Used

- Python 3
- Libraries: `pandas`, `numpy`, `matplotlib`, `seaborn`, `fpdf`
- Jupyter Notebook / Google Colab


---

##  Submission Context

This work has been prepared and submitted as part of the selection process for the **Junior Data Scientist** role at **Primetrade.ai**.

---

##  Author

**Hershul Singh**  
Email: hershulsingh55@gmail.com  
GitHub: hershul12
