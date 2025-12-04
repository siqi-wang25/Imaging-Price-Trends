# Reproducing "Re-Imagining Price Trends"

This repository contains a faithful reproduction of the core results from  
**Jiang, Kelly, and Xiu — *Re-Imagining Price Trends* (2020)**,  
a seminal study demonstrating that lightweight convolutional neural networks (CNNs) 
can extract predictive signals from price–image representations.

Our reproduction rebuilds the full experimental pipeline using CRSP-like data from  
**2000–2019**, following the original I20/R20 (20-day input, 20-day horizon) setting.

---

## 📈 Key Reproduced Results

Our implementation matches the main findings of the paper:

| Metric | Reproduced | Original |
|--------|------------|----------|
| Decile monotonicity | ✓ Strictly monotonic | ✓ |
| H–L Sharpe (I20/R20) | **2.49** | 2.2–2.5 |
| Turnover | 1.74 | 1.73 |
| Cumulative H–L curve | ✓ Similar trajectory | ✓ |
| Rolling Sharpe | ✓ Declining trend post-2012 | ✓ |

---

## 📊 Example Figures

- Distribution of predicted probabilities  
- Decile return curves  
- Cumulative H–L performance  
- 36-month rolling Sharpe ratio  
- Turnover time-series  
- Grad-CAM visualizations (optional)

---
