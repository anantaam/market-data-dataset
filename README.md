# 📊 Market Data — NIFTY Total Market + NSE Indices (5Y EOD)

Daily updated End-Of-Day (EOD) data for:

- **NIFTY Total Market** constituents (Equities)
- **All NSE Indices** (`exchange = NSE`, `segment = INDICES`)

Data is in `/data` as a ZIP file — one CSV per symbol, covering the last 5 years.

---

## 📥 Download
[➡ **Latest Data ZIP**](./)

---

## ⚡ Quick Start
```python
import pandas as pd
df = pd.read_csv("RELIANCE.csv")
print(df.head())
