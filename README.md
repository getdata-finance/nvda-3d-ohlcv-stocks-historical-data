# NVDA 3d OHLCV US stocks Historical Data — Free Sample

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE) [![Dataset rows](https://img.shields.io/badge/full_dataset-738_rows-blue)](https://getdata.finance/datasets/nvda) [![Updated](https://img.shields.io/badge/weekly_update-every_Saturday_8am_UTC-green)](https://getdata.finance) [![Full data on getdata.finance](https://img.shields.io/badge/download-getdata.finance-orange)](https://getdata.finance/datasets/nvda)

### -> [**Download the full NVDA dataset on getdata.finance**](https://getdata.finance/datasets/nvda)

**NVDA 3d OHLCV stocks historical data** — ultra high-quality 3d OHLCV for **NVIDIA**. Clean `datetime, open, high, low, close, volume` CSV for backtesting, algorithmic trading and quantitative research.

## Table of contents

- [Why this dataset?](#why-this-dataset)
- [Download sample CSV](#download-sample)
- [GitHub Pages preview](#github-pages)
- [Sample vs full dataset](#sample-vs-full-dataset)
- [Timeframes on GetData](#timeframes-on-getdata)
- [Weekly updates](#weekly-updates)
- [Data preview](#data-preview)
- [Schema](#schema)
- [Code examples](#code-examples)
- [Download full data on getdata.finance](#download-full-data-on-getdata)

## Why this dataset?

- **Ultra high-quality 3d OHLCV** for **NVIDIA** (US stocks)
- **Clean CSV schema** — `datetime, open, high, low, close, volume` (no gaps in formatting)
- **Free evaluation sample** on GitHub (`3d`) · **11 timeframes** on [getdata.finance](https://getdata.finance/datasets/nvda) · **738** `3d` rows in the full archive
- Built for **backtesting**, **algorithmic trading** and **quantitative finance** workflows
- **Weekly refresh** — [getdata.finance](https://getdata.finance) every **Saturday, 8am UTC+0**; GitHub `3d` sample updated in sync

> **Sample on GitHub** · `NVDA_3d.csv` (244 rows, `2024-08-27` -> `2026-09-07`, 23.75 KB). **Full archive on [getdata.finance](https://getdata.finance/datasets/nvda)** — **738** `3d` rows (full `1m`: 598,377), **11 timeframes**, `2020-07-13` -> `2026-09-07`.

## Download sample

**[NVDA_3d.csv](https://github.com/getdata-finance/nvda-3d-ohlcv-stocks-historical-data/blob/main/NVDA_3d.csv)** on GitHub ([raw CSV](https://raw.githubusercontent.com/getdata-finance/nvda-3d-ohlcv-stocks-historical-data/main/NVDA_3d.csv)) · [GitHub Releases](https://github.com/getdata-finance/nvda-3d-ohlcv-stocks-historical-data/releases)

## GitHub Pages

Interactive chart & stats: **[https://getdata-finance.github.io/nvda-3d-ohlcv-stocks-historical-data/](https://getdata-finance.github.io/nvda-3d-ohlcv-stocks-historical-data/)**

Full archive & live chart on getdata.finance: **[https://getdata.finance/datasets/nvda](https://getdata.finance/datasets/nvda)**

## Sample vs full dataset

| | **Sample (this repo)** | **Full dataset ([getdata.finance](https://getdata.finance/datasets/nvda))** |
|---|--:|---|
| Instrument | NVIDIA · US stocks | NVIDIA · US stocks |
| Timeframes | `3d` (sample) | **11** — 1m · 3m · 5m · 15m · 30m · 1H · 4H · 12H · 1D · 3D · 1W |
| 3d rows | 244 | **738** |
| Size | 23.75 KB | full ZIP on [getdata.finance](https://getdata.finance/datasets/nvda) |
| Period | `2024-08-27` -> `2026-09-07` | `2020-07-13` -> `2026-09-07` |
| File | `NVDA_3d.csv` | ZIP on [getdata.finance](https://getdata.finance/datasets/nvda) |
| Coverage report | — | [NVDA coverage](https://getdata.finance/coverage/nvda) |
| Updates | Weekly (Saturday, 8am UTC+0) — GitHub sample | Weekly (Saturday, 8am UTC+0) — all timeframes |

## Timeframes on GetData

This GitHub repository ships a **`3d` evaluation sample** only. On **[getdata.finance](https://getdata.finance/datasets/nvda)**, each full asset archive is delivered as a ZIP with **11 gap-free OHLCV timeframes** (one CSV per timeframe):

**1m · 3m · 5m · 15m · 30m · 1H · 4H · 12H · 1D · 3D · 1W**

GitHub = `3d` sample · [getdata.finance](https://getdata.finance/datasets/nvda) = all **11** timeframes above for the same instrument.

## Weekly updates

- **[getdata.finance](https://getdata.finance)** — Full datasets are updated every Saturday, 8am UTC+0.
- **GitHub (this repo)** — GitHub samples are refreshed weekly (every Saturday, 8am UTC+0), in sync with getdata.finance.

When a new `3d` sample is published on GitHub, the README, chart preview and CSV reflect the latest week of data.

## Data preview

First and latest rows from the GitHub sample **`NVDA_3d.csv`**:

**First rows**

| datetime | open | high | low | close | volume |
| --- | --- | --- | --- | --- | --- |
| 2024-08-27T00:00:00+00:00 | 126.41 | 129.13 | 116.65 | 117.52 | 429425 |
| 2024-08-30T00:00:00+00:00 | 117.52 | 121.67 | 117.15 | 119.32 | 148604 |
| 2024-09-02T00:00:00+00:00 | 119.32 | 119.32 | 104.04 | 106.11 | 267759 |
| 2024-09-05T00:00:00+00:00 | 106.11 | 109.58 | 100.88 | 102.79 | 279763 |
| 2024-09-08T00:00:00+00:00 | 102.79 | 109.27 | 102.79 | 107.97 | 277711 |

**Last rows**

| datetime | open | high | low | close | volume |
| --- | --- | --- | --- | --- | --- |
| 2026-08-26T00:00:00+00:00 | 212.82 | 230.31 | 207.88 | 217.38 | 359445 |
| 2026-08-29T00:00:00+00:00 | 217.38 | 221.11 | 216.05 | 220.5 | 84069 |
| 2026-09-01T00:00:00+00:00 | 220.5 | 230.24 | 214.93 | 228.23 | 292169 |
| 2026-09-04T00:00:00+00:00 | 228.23 | 234.59 | 228.23 | 230.19 | 95775 |
| 2026-09-07T00:00:00+00:00 | 230.19 | 233.48 | 224.68 | 225.61 | 97543 |

## Schema

| Column | Description |
| --- | --- |
| `datetime` | Bar open timestamp (UTC, ISO-8601). |
| `open` | Opening price of the candlestick bar. |
| `high` | Highest price during the bar. |
| `low` | Lowest price during the bar. |
| `close` | Closing price of the candlestick bar. |
| `volume` | Tick volume (number of price updates) during the bar. |

```text
datetime,open,high,low,close,volume
```

## Code examples

### pandas

```python
import pandas as pd

df = pd.read_csv('NVDA_3d.csv', parse_dates=['datetime'])
df.set_index('datetime', inplace=True)
print(df.describe())
```

### backtrader

```python
import backtrader as bt
import pandas as pd

df = pd.read_csv('NVDA_3d.csv', parse_dates=['datetime'])
df.set_index('datetime', inplace=True)

class PandasData(bt.feeds.PandasData):
    params = (('datetime', None), ('open', 'open'), ('high', 'high'),
              ('low', 'low'), ('close', 'close'), ('volume', 'volume'))

cerebro = bt.Cerebro()
cerebro.adddata(PandasData(dataname=df))
# cerebro.addstrategy(YourStrategy)
# cerebro.run()
```

### vectorbt

```python
import pandas as pd
import vectorbt as vbt

df = pd.read_csv('NVDA_3d.csv', parse_dates=['datetime'])
close = df.set_index('datetime')['close']
fast, slow = vbt.MA.run(close, 10), vbt.MA.run(close, 50)
entries = fast.ma_crossed_above(slow)
exits = fast.ma_crossed_below(slow)
pf = vbt.Portfolio.from_signals(close, entries, exits, init_cash=10_000, freq='3d')
print(pf.stats())
```

## Download full data

The complete **NVDA** archive on **[getdata.finance](https://getdata.finance/datasets/nvda)** includes **11 OHLCV timeframes** (1m · 3m · 5m · 15m · 30m · 1H · 4H · 12H · 1D · 3D · 1W) — **738** rows at `3d`, plus all other timeframes in the same ZIP.

**[-> Get the full NVDA dataset on getdata.finance](https://getdata.finance/datasets/nvda)**

---
*GetData · NVDA 3d OHLCV sample on GitHub · Full historical data on [getdata.finance](https://getdata.finance/datasets/nvda)*
