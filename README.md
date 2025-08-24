# Trader Behavior vs Market Sentiment Analysis

## Overview
This project explores the relationship between trader behavior (profitability, risk, leverage, trade volume) and Bitcoin market sentiment (Fear vs Greed).  
By combining historical trader data (from Hyperliquid) with a Bitcoin market sentiment dataset, the goal is to uncover hidden patterns that can guide smarter trading strategies.  

---

## Project Structure
ds_<candidate_name>/
├── notebook_1.ipynb          # Main analysis & EDA notebook (Google Colab)
├── notebook_2.ipynb          # (Optional) Additional notebook if needed
├── csv_files/                # All raw and processed CSV files
│   └── *.csv
├── outputs/                  # Saved graphs, plots, and visualizations
│   └── *.png / *.jpg
├── ds_report.pdf             # Final summarized insights & explanations
└── README.md                 # Project documentation

---

## Datasets
1. Bitcoin Market Sentiment Dataset  
   - Columns: Date, Classification (Fear/Greed)  

2. Historical Trader Data (Hyperliquid)  
   - Columns include:  
     - Account, Symbol, Execution Price, Size, Side  
     - Start Position, ClosedPnL, Leverage, Fee  
     - Timestamp, Direction, etc.  

---

## Objectives
- Analyze how trader profitability, risk exposure, and leverage align/diverge with market sentiment  
- Detect whether traders take more risks in "Greed" markets vs "Fear" markets  
- Identify hidden signals that could help in building better trading strategies  

---

## Workflow
1. Load and clean datasets (csv_files/)  
2. Perform Exploratory Data Analysis (EDA):  
   - Distribution of Closed PnL (with and without outliers)  
   - Leverage usage trends  
   - Trade volume patterns  
   - Profitability under Fear vs Greed sentiment  
3. Save all important plots in outputs/  
4. Summarize findings in ds_report.pdf  

---

## Example Visuals
- PnL Distribution (log + normal scale)  
- Leverage Distribution  
- Win Rate in Fear vs Greed markets  
- Average Trade Size under different sentiments  

All plots are available in the outputs/ folder  

---

## Report
Final analysis and conclusions are compiled in ds_report.pdf  
This includes:  
- Key insights from EDA  
- Observations on sentiment vs trader behavior  
- Possible signals for smarter strategies  

---

## Requirements
This project is designed to run in Google Colab (no local setup required).  
Key libraries used:  
- pandas  
- numpy  
- matplotlib  
- seaborn  

---

## Author
Candidate: Mobashra Eram Khan  
Project: Trader Behavior & Market Sentiment Analysis  
