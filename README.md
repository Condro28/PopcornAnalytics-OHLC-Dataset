🍿 PopcornAnalytics — High-Quality OHLCV Datasets
Reconstructed from raw Kraken trades (2013–2025). Zero gaps. Millisecond timestamps. True trade-derived OHLC.

👉 Reddit Community: https://www.reddit.com/r/PopcornAnalytics/


👉 Gumroad Store (Premium Datasets): https://popcornanalytics.gumroad.com

PopcornAnalytics provides research-grade crypto OHLCV datasets, rebuilt directly from raw Kraken trade logs using a custom reconstruction pipeline.
All datasets follow the same strict accuracy rules:

Zero gaps (every minute reconstructed, including low-liquidity periods)

Millisecond timestamps (superior to standard API feeds)

True trade-derived OHLC (no API snapshot inaccuracies)

Perfect 1-minute alignment

Accurate base-currency volume

Verified using internal consistency checks

📦 Available Datasets

This repository hosts free sample datasets for XBTUSD and ETHUSD.
Full premium datasets are available on Gumroad.

🟦 Bitcoin — XBTUSD 1-Minute OHLCV Dataset
✔ Free Samples (Included in Repo)
Sample	Candles	Date Range	File
November 2025 (1 Month)	43,200	2025-11-01 → 2025-11-30	xbtusd_1m_2025-11_sample.json.zip
Historical Slice (2013–2017)	349,376	2013-10-06 → 2017-06-27	xbtusd_1m_sample_20mb.zip
Recent Multi-Month Sample (2025)	361,005	2025-03-24 → 2025-11-30	xbtusd_1m_sample_recent_20mb.zip
💎 Full XBTUSD Dataset (2013–2025)

👉 https://popcornanalytics.gumroad.com/l/xwnuid


Includes:

12+ years of 1-minute candles

4.7M+ rows

Zero gaps

Verified reconstruction

Research-grade format

🟪 Ethereum — ETHUSD 1-Minute OHLCV Dataset
✔ Free Sample (Included in Repo)
Sample	Candles	Date Range	File
Recent 30-day sample	~43,000	Latest 30 days	lsethusd_1m_recent_30d.json

This free sample allows researchers to confirm formatting, consistency, and reconstruction quality.

💎 Full ETHUSD Dataset (2017–2025)

👉 https://popcornanalytics.gumroad.com/l/zzfyml

Includes:

Full ETHUSD 1-minute OHLCV (2017 → 2025)

Clean normalized format

Accurate timestamp reconstruction

True raw-trade OHLC values

Delivered as .json

ETHUSD is offered as a premium dataset due to its size, computational cost, and high demand from trading researchers.

📘 Dataset Format

Each 1-minute candle is stored as:
[
  timestamp_ms,   // Unix timestamp in milliseconds (UTC)
  open,           // Opening price
  high,           // Highest trade price
  low,            // Lowest trade price
  close,          // Closing price
  volume          // Base-currency traded volume
]

⚙️ How These Datasets Are Built

PopcornAnalytics uses a custom high-precision reconstruction engine:

Load raw Kraken trade logs

Sort trades and align by strict UNIX minute boundary

Derive OHLC from true tick-level sequence

Sum base-currency volume from actual trades

Fill missing minutes with zero-volume flat candles

Validate timestamp continuity & format correctness

Export as clean, analysis-ready JSON (CSV on request)

This process ensures perfect reproducibility, consistent structure across all pairs, and full transparency.

🧠 Ideal For

Algo trading research

ML modeling

Backtesting engines

HFT experiments

Statistical analysis

Long-horizon behavior studies

Quant pipeline benchmarking

🛒 Support the Project

Premium datasets help fund ongoing computation, new pairs, verification tools, and future releases:

👉 Gumroad Store: https://popcornanalytics.gumroad.com

🎉 Thank You

PopcornAnalytics is rapidly becoming a trusted source for high-quality, trade-reconstructed crypto datasets.
Your support helps expand the catalog and maintain long-term updates.
