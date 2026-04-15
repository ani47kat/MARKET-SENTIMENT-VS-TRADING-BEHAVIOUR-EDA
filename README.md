# 📊 Crypto Sentiment & Trading Risk EDA

**Exploratory Data Analysis** of how **market emotion** shapes **risk appetite** and **trading volume** in crypto markets.

---

## 📁 Datasets  
| File                  | Rows     | Period     | Description                                      |
|-----------------------|----------|------------|--------------------------------------------------|
| `historical_data.csv` | **1.2M+**| Dec 2024   | High-frequency trades: price, size, PnL, fees    |
| `fear_greed_index.csv`| **2,644**| 2018–2025  | Daily Fear & Greed Index (0–100)                 |

---

## 🔍 Core Findings  
| **Sentiment**       | **Avg Risk Exposure**      | **Trade Behavior**                          |
|---------------------|----------------------------|---------------------------------------------|
| **Neutral**         | **$140 M** *(Highest)*     | Largest, most confident positions            |
| Greed               | $120 M                    | Optimistic, aggressive sizing                |
| Fear                | $100 M                    | Cautious, moderate exposure                  |
| Extreme Fear        | $80 M                     | Defensive, minimal risk                      |
| **Extreme Greed**   | **$60 M** *(Lowest)*       | *Surprising caution — reversal fear?*        |

> **Key Insight:**  
> ✅ **Neutral markets drive the biggest bets.**  
> ❗ **Extreme Greed = Lowest risk** (traders get nervous at the top!)

---

## 📂 Project Files  
- `notebook_1.ipynb` : Full analysis (Jupyter / Colab)  
- `ds_Report.pdf`     : Professional PDF report  
- `historical_data.csv`: Raw trading data  
- `fear_greed_index.csv`: Daily sentiment scores  

---

## 🧭 How to Use  
1. **Read** `ds_Report.pdf` → Instant insights  
2. **Run** `notebook_1.ipynb` in **Colab** → Reproduce everything  
3. **Add your data** → Merge & analyze in minutes  

---

## 🎯 Trading Strategy Signals  
| Market Mood             | Recommended Action                            |
|--------------------------|-----------------------------------------------|
| **Neutral**             | **Increase size** — optimal confidence zone   |
| **Extreme Greed**       | **Reduce exposure** — potential market top    |
| **Fear / Extreme Fear** | **Buy the dip** — accumulation opportunity    |

---

*Designed for traders, quants, and algo developers*  
**Updated: November 2025**  
