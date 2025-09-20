# Data Science Assignment – Bitcoin Traders & Sentiment

This project combines **Bitcoin trader activity** with the **Fear & Greed Index** to study trading behavior and sentiment. The work includes data cleaning, aggregation, and visualization.

## 📂 Structure
```
ds_Gurdeep_Singh/
│── Notebook_1.ipynb   # Colab notebook (full workflow)
│── csv_files/         # Cleaned & aggregated CSVs
│── outputs/           # Plots & charts
│── README.md          # Project summary
```

## 🚀 Workflow
1. Load trader + sentiment datasets (via Drive or manual upload).  
2. Clean and standardize columns (dates, PnL, size, leverage).  
3. Aggregate daily metrics:  
   - Trade count  
   - Total volume  
   - Avg leverage  
   - Total PnL  
   - Avg trade size  
4. Merge with Fear & Greed sentiment labels.  
5. Generate summary plots.  

## 📊 Key Insights
- Dataset covers **1 trading day** with ~**211k trades**.  
- **Total PnL** ≈ **10.3M USD** (highly profitable).  
- **Avg leverage** unavailable (missing column).  
- Sentiment linkage limited due to short timeframe.  

## 📌 Usage
Open `Notebook_1.ipynb` in **Google Colab**, run cells in order.  
Outputs are saved in `csv_files/` and `outputs/` for submission.  
