🍿 PopcornAnalytics — High-Quality OHLCV Datasets (Kraken Raw Trades, 2013–2025)

Reconstructed from raw Kraken trades with zero gaps, millisecond timestamps, and true trade-derived OHLC.
Join the community on Reddit → https://www.reddit.com/r/PopcornAnalytics/


Premium datasets available on Gumroad → https://popcornanalytics.gumroad.com/
📦 Available Datasets

PopcornAnalytics provides research-grade 1-minute OHLCV datasets rebuilt directly from raw Kraken trade logs.

✔ Free Datasets
Pair	Years	Format	Download
XBTUSD (Bitcoin/USD)	2013–2025	JSON	GitHub & Kaggle
ETHUSD Sample (30 Days)	2025 (recent month)	JSON	GitHub & Kaggle
💎 Premium Datasets (Gumroad)
Pair	Years	Description	Link
ETHUSD — Full 1-Minute OHLCV Dataset	2017–2025	Fully reconstructed from raw trades, zero gaps, millisecond timestamps	https://popcornanalytics.gumroad.com/l/zzfyml
XBTUSD — Full 1-Minute OHLCV Dataset
2013–2025
Entire 12-year BTC/USD dataset rebuilt from raw trades
https://popcornanalytics.gumroad.com/l/xwnuid

If you use, test, or buy these datasets — join the community and follow updates:
👉 Reddit: /r/PopcornAnalytics

🧠 Why PopcornAnalytics Data?

Most API OHLC feeds suffer from:

Missing candles

Inaccurate open/close

Fake volume

Rounded timestamps

PopcornAnalytics datasets are:

✔ Rebuilt entirely from raw trades

Every single minute is reconstructed from underlying tick-level trade history.

✔ Zero gaps

No missing minutes — even during low-liquidity or exchange-downtime windows.

✔ Millisecond timestamps

More accurate than standard API feeds (which often round to seconds).

✔ True OHLCV

Values are derived directly from real trades, not API snapshots.

✔ Perfect 1-minute alignment

All candles align to exact UNIX boundaries.

🔥 Featured Premium Dataset: Ethereum ETHUSD (2017–2025)

👉 Download on Gumroad:
https://popcornanalytics.gumroad.com/l/zzfyml

This dataset includes:

Full ETH/USD 1-minute candles (2017 → 2025)

Clean normalized format

Verified timestamp reconstruction

Accurate OHLCV based on all Kraken ETHUSD trades

Delivered as .json (and .csv on request)

Ideal for:

Quant research

Backtesting

HFT strategy prototyping

Machine learning datasets

Long-horizon market behavior analysis

ETHUSD is a premium dataset due to high computational cost and extremely large trade history.

📊 BTC Dataset (Free + Premium)
✔ Free Samples (Included in this Repo)

xbtusd_1m_2025-11_sample.json.zip — November 2025 sample

xbtusd_1m_sample_20mb.zip — 2013–2017 historical slice

xbtusd_1m_sample_recent_20mb.zip — 2025 multi-month slice

✔ Full BTC/USD Dataset

Available on Gumroad:
https://popcornanalytics.gumroad.com/l/xwnuid

Includes:

12+ years of raw-trade-derived 1-minute candles

4.7M+ rows

Verified reconstruction accuracy

Zero gaps, perfect boundaries

📅 ETHUSD Free Sample (30 Days)

File: lsethusd_1m_recent_30d.json
Candles: ~43,000
Range: Last 30 days from most recent data processing run

This is provided so users can verify ETHUSD formatting before purchasing the full dataset.

🧩 Column Format (All Datasets)

Each 1-minute candle is:
[
  timestamp_ms,   // Unix timestamp in milliseconds (UTC)
  open,           // Opening price
  high,           // Highest trade price
  low,            // Lowest trade price
  close,          // Closing price
  volume          // Base-currency trade volume
]

⚙️ How These Datasets Are Built

Using a custom high-precision reconstruction pipeline:

Raw Kraken trades loaded from JSON logs

Sorted & aligned into 1-minute windows

Trades grouped by strict UNIX minute boundary

OHLC derived from true trade sequence

Volume sum computed from raw fills

Missing minutes filled as zero-volume flat candles

Final dataset validated against timestamp continuity tools

This process ensures identical reproducibility across all pairs.

📣 Join the Community

All updates, new dataset releases, development logs, and discussions happen here:

👉 Reddit: https://www.reddit.com/r/PopcornAnalytics/

If you want new pairs released sooner, request them there!

🛒 Support the Project

Premium datasets help fund compute costs:

ETHUSD full dataset

XBTUSD full dataset

Future pairs (ADAUSD, XRPUSD, FX pairs, etc.)

👉 Gumroad Store: https://popcornanalytics.gumroad.com/

🎉 Thank You

PopcornAnalytics is growing fast — your support helps expand the dataset catalog and maintain continuous updates.
