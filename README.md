# PopcornAnalytics-OHLC-Dataset
High-quality crypto OHLC dataset reconstructed from raw Kraken trades (2013–2025). Free samples included.
https://www.reddit.com/r/PopcornAnalytics/
---

## 🛒 Full Dataset (2013–2025)

If you want the complete **XBTUSD 1-minute OHLC dataset reconstructed from raw trades**, you can get it here:

👉 **Gumroad:** https://popcornanalytics.gumroad.com/l/xwnuid

Includes:

- 12+ years of continuous data  
- Zero gaps  
- Accurate OHLCV reconstructed from trades  
- Verified millisecond timestamps  
- Research-grade dataset
   
## 📊 Kaggle Dataset (Free Access)

The full XBTUSD 1-minute OHLCV dataset (2013–2025) is now available on Kaggle:

👉 **Kaggle (Free Download):**  
https://www.kaggle.com/datasets/popcornanalytics/xbtusd-1-minute-ohlcv-20132025-popcornanalytics

The dataset includes:
- 4.7M+ minute-candles  
- Fully reconstructed from raw Kraken trades  
- Zero gaps  
- Millisecond timestamps  
- Clean normalized OHLCV format  

---

## 📌 Overview

This repository contains multiple **XBTUSD 1-minute OHLC samples** reconstructed directly from raw Kraken trade data using a custom pipeline.

This pipeline ensures:

- Zero intentional gaps  
- Millisecond-accurate timestamps  
- True trade-derived OHLC  
- Perfect 1-minute boundaries  
- Accurate base-currency volume  
- Long-term consistency (2013 → 2025)

These samples allow traders and researchers to validate reconstruction quality before purchasing the full dataset.

---

# 📦 Free Sample Files

## 🗓 1-Month Sample — November 2025
**File:** `xbtusd_1m_2025-11_sample.json.zip`  
**Candles:** 43,200  
**Range:** 2025-11-01 → 2025-11-30  

A full month of recent XBTUSD 1-minute candles, ideal for testing continuity, timestamps, and reconstruction quality.

---

## 🕰 Historical Sample (2013–2017) — 20MB
**File:** `xbtusd_1m_sample_20mb.zip`  
**Candles:** 349,376  
**Range:** 2013-10-06 → 2017-06-27  

A historical slice showing early Kraken BTC/USD trading behavior and long-term reconstruction consistency.

---

## 📅 Recent Sample (2025) — 20MB
**File:** `xbtusd_1m_sample_recent_20mb.zip`  
**Candles:** 361,005  
**Range:** 2025-03-24 → 2025-11-30  

A larger recent sample demonstrating multi-month continuity and modern liquidity conditions.

---

# 📘 Column Definitions

Each 1-minute candle follows this structure:

```json
[
  timestamp_ms,   // Unix timestamp in milliseconds (UTC)
  open,           // Opening price of the minute
  high,           // Highest traded price during the minute
  low,            // Lowest traded price during the minute
  close,          // Closing price of the minute
  volume          // Total traded volume in BTC
]
