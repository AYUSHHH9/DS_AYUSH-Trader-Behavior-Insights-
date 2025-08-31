
# Trader Behavior Insights – DS_AYUSH

## 📌 Overview
This project analyzes the relationship between **trader performance** and **Bitcoin market sentiment** (Fear/Greed Index).  
It is part of a Data Science assignment for the Junior Data Scientist role.

## 📂 Project Structure
ds_ayush/
├── notebook_1.ipynb           # Main Colab notebook
├── csv_files/                 # Original + processed CSVs
│   ├── historical_data.csv
│   ├── fear_greed_index.csv
│   └── merged_trades_sentiment.csv
├── outputs/                   # Plots and visual outputs
│   ├── avg_pnl_by_sentiment.png
│   ├── winrate_by_sentiment.png
│   └── trades_by_sentiment.png
├── ds_report.pdf              # Summarized report
└── README.md                  # Instructions & summary

## 🚀 Steps Performed
1. Data loading (historical trades + sentiment datasets)  
2. Data cleaning & preprocessing  
3. Merging datasets by date  
4. Exploratory data analysis (EDA) with charts  
5. Insights on trader behavior under different sentiments  
6. Baseline predictive model (logistic regression)  
7. Final conclusions and recommendations  

## 📊 Key Insights
- Trader win rates are **higher in GREED** periods compared to FEAR.  
- **Long trades** perform better in GREED, while **Short trades** are safer in FEAR.  
- BTC and ETH showed more stable results across sentiments; altcoins were more volatile.  
- A baseline predictive model achieved ~57% accuracy, showing sentiment adds modest predictive power.  

## 🛠️ How to Run
- Open `notebook_1.ipynb` in Google Colab or Jupyter.  
- Ensure all datasets are inside `csv_files/`.  
- Run cells step by step to reproduce the results.  

## 📌 Deliverables
- `notebook_1.ipynb` – main analysis  
- `csv_files/` – datasets (original + merged)  
- `outputs/` – charts and visualizations  
- `ds_report.pdf` – summary report  
- `README.md` – this file  

### 📂 Datasets
- `historical_data_sample.csv` → Contains 5,000 rows (uploaded here due to GitHub’s 25MB file size limit).  
- `fear_greed_index.csv` → Full dataset included.  
- `merged_trades_sentiment.csv` → Processed dataset included.  

🔗 [Full historical_data.csv (Google Drive Link)](https://drive.google.com/file/d/1Cmkxw2GHMcdusHCYbvaTufqMPV8LxS1y/view?usp=sharing)


## 👤 Author
**Ayush Barad**  
Junior Data Scientist Assignment – Trader Behavior Insights
