# Trader Behavior Analysis Under Market Sentiment

This repository contains a data science project that analyzes how trader behavior and performance vary under different Bitcoin market sentiment regimes, specifically **Fear** and **Greed**.  
The analysis combines real trade-level data with the Bitcoin Fear & Greed Index to uncover behavioral patterns, risk dynamics, and trader-level insights.

---

## 📂 Project Structure

ds_deekshith/
├── notebook_1.ipynb
├── csv_files/
│ ├── merged_trades_sentiment.csv
│ ├── trader_summary.csv
│ ├── trader_sentiment_summary.csv
│ ├── trader_consistency.csv
│ └── trader_archetype_sentiment.csv
├── outputs/
│ ├── trade_count_by_sentiment.png
│ ├── pnl_distribution_by_sentiment.png
│ ├── trade_size_distribution.png
│ └── trade_direction_by_sentiment.png
├── ds_report.pdf
└── README.md


---

## 📊 Analysis Overview

- Cleaned and standardized raw trade and sentiment datasets.
- Aligned trade-level data with daily market sentiment using timestamp normalization.
- Compared trader behavior, profitability, and risk exposure under Fear and Greed regimes.
- Performed trader-level aggregation to identify performance heterogeneity.
- Classified traders into intuitive behavioral archetypes.
- Extracted actionable insights relevant to trading strategy and platform risk management.

---

## 📘 Google Colab Notebook

All analysis was conducted in Google Colab.  
Access the main notebook here:

👉 https://colab.research.google.com/drive/1WWxPUu27y0rV5YdNc4pOKvCrE_6BMBa4?usp=sharing

---

## 📂 Outputs

- **`csv_files/`**  
  Contains cleaned datasets and trader-level summary tables generated during the analysis.

- **`outputs/`**  
  Contains all visualizations used to support exploratory data analysis and insights.

- **`ds_report.pdf`**  
  Executive summary of findings, methodology, insights, and business implications.

---

## ⚙️ Reproducibility Notes

- All analysis steps are documented within the notebook.
- Outputs are generated programmatically and saved in the corresponding directories.
- Folder structure strictly follows the submission guidelines provided in the assignment.

---

## 📌 Key Takeaway

While average profitability appears similar across Fear and Greed regimes, market sentiment significantly influences trader risk-taking behavior, downside volatility, and performance consistency. Long-term profitability is driven more by individual trader discipline and risk management than by sentiment alone.

---

## 👤 Author

**Pembula Deekshith**  
Candidate – Junior Data Scientist (Trader Behavior Insights)
