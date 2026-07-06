# NGAS 8h OHLCV Commodities Historical Data — Free Sample

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE) [![Dataset rows](https://img.shields.io/badge/full_dataset-11_861_rows-blue)](https://ork.ad/) [![Updated](https://img.shields.io/badge/weekly_update-every_Sunday-green)](https://ork.ad/) [![Full data on ork.ad](https://img.shields.io/badge/download-ork.ad-orange)](https://ork.ad/)

### → [**Download the full NGAS dataset on ork.ad**](https://ork.ad/)

**NGAS 8h OHLCV Commodities historical data** — ultra high-quality 8h OHLCV for **Natural Gas**. Extended-session energy and industrial metals — beyond US cash hours. Clean `time, open, high, low, close, volume` CSV for backtesting, algorithmic trading and quantitative research.

## Table of contents

- [Why this dataset?](#why-this-dataset)
- [Download sample CSV](#download-sample)
- [GitHub Pages preview](#github-pages)
- [Sample vs full dataset](#sample-vs-full-dataset)
- [Timeframes on ork.ad](#timeframes-on-orkad)
- [Weekly updates](#weekly-updates)
- [Data preview](#data-preview)
- [Schema](#schema)
- [Code examples](#code-examples)
- [Download full data on ork.ad](#download-full-data)

## Why this dataset?

- **Ultra high-quality 8h OHLCV** for **Natural Gas** (Commodities)
- **Extended-session energy and industrial metals — beyond US cash hours**
- **Clean CSV schema** — `time, open, high, low, close, volume` (no gaps in formatting)
- **Free evaluation sample** on GitHub (`8h`) · **13 timeframes** on [ork.ad](https://ork.ad/) · **11,861** `8h` rows in the full archive
- Built for **backtesting**, **algorithmic trading** and **quantitative finance** workflows
- **Weekly refresh** — [ork.ad](https://ork.ad/) every **Sunday**; GitHub `8h` sample updated in sync

> **Sample on GitHub** · `NGAS_8h.csv` (613 rows, `2025-10-03` → `2026-07-03`). **Full archive on [ork.ad](https://ork.ad/)** — **11,861** `8h` rows (~0.61 MB), **13 timeframes** (``1m`, `3m`, `5m`, `15m`, `30m`, `1H`, `2H`, `4H`, `8H`, `12H`, `16H`, `1D`, `1W``), `2011-12-05` → `2026-07-03`.

## Download sample

**[NGAS_8h.csv](https://github.com/ork-ad/ngas-8h-ohlcv-commodities-historical-data/blob/main/NGAS_8h.csv)** on GitHub ([raw CSV](https://raw.githubusercontent.com/ork-ad/ngas-8h-ohlcv-commodities-historical-data/main/NGAS_8h.csv)) · [GitHub Releases](https://github.com/ork-ad/ngas-8h-ohlcv-commodities-historical-data/releases) when the release workflow is active.

## GitHub Pages

Interactive chart & stats: **[https://ork-ad.github.io/ngas-8h-ohlcv-commodities-historical-data/](https://ork-ad.github.io/ngas-8h-ohlcv-commodities-historical-data/)**

## Sample vs full dataset

| | **Sample (this repo)** | **Full dataset ([ork.ad](https://ork.ad/))** |
|---|--:|---|
| Instrument | Natural Gas · Commodities | Natural Gas · Commodities |
| Timeframes | `8h` (sample) | **13** — `1m`, `3m`, `5m`, `15m`, `30m`, `1H`, `2H`, `4H`, `8H`, `12H`, `16H`, `1D`, `1W` |
| 8h rows | 613 | **11,861** |
| Size | 0.03 MB | ~0.61 MB |
| Period | `2025-10-03` → `2026-07-03` | `2011-12-05` → `2026-07-03` |
| File | `NGAS_8h.csv` | ZIP on [ork.ad](https://ork.ad/) |
| Updates | Weekly (Sunday) — GitHub sample | Weekly (Sunday) — all timeframes |

## Timeframes on ork.ad

This GitHub repository ships a **`8h` evaluation sample** only. On **[ork.ad](https://ork.ad/)**, each full asset archive is delivered as a ZIP with **13 gap-free OHLCV timeframes** (one CSV per timeframe):

**1m** · **3m** · **5m** · **15m** · **30m** · **1H** · **2H** · **4H** · **8H** · **12H** · **16H** · **1D** · **1W**

GitHub = `8h` sample · [ork.ad](https://ork.ad/) = all **13** timeframes above for the same instrument.

## Weekly updates

- **[ork.ad](https://ork.ad/)** — Full datasets on ork.ad are updated every Sunday.
- **GitHub (this repo)** — GitHub samples are refreshed weekly (every Sunday), in sync with ork.ad.

When a new `8h` sample is published on GitHub, the README, chart preview and CSV reflect the latest week of data.

## Data preview

First and latest rows from the GitHub sample **`NGAS_8h.csv`**:

**First rows**

| time | open | high | low | close | volume |
| --- | --- | --- | --- | --- | --- |
| 2025-10-03T08:00:00Z | 3.4194 | 3.4449 | 3.3272 | 3.35 | 20901.0 |
| 2025-10-03T16:00:00Z | 3.35 | 3.3608 | 3.3007 | 3.3299 | 2981.0 |
| 2025-10-05T16:00:00Z | 3.3299 | 3.4189 | 3.29 | 3.4089 | 2175.0 |
| 2025-10-06T00:00:00Z | 3.4089 | 3.479 | 3.392 | 3.4469 | 5116.0 |
| 2025-10-06T08:00:00Z | 3.4469 | 3.4649 | 3.3357 | 3.3618 | 19574.0 |

**Last rows**

| time | open | high | low | close | volume |
| --- | --- | --- | --- | --- | --- |
| time | open | high | low | close | volume |
| 2026-07-02T00:00:00Z | 3.1928 | 3.2029 | 3.1627 | 3.1827 | 2352.0 |
| 2026-07-02T08:00:00Z | 3.1827 | 3.2064 | 3.147 | 3.2049 | 12189.0 |
| 2026-07-02T16:00:00Z | 3.2049 | 3.2139 | 3.182 | 3.2099 | 2805.0 |
| 2026-07-03T00:00:00Z | 3.2099 | 3.2608 | 3.1998 | 3.2339 | 2533.0 |

## Schema

```text
time,open,high,low,close,volume
```

## Code examples

### pandas

```python
import pandas as pd

df = pd.read_csv('NGAS_8h.csv', parse_dates=['time'])
df.set_index('time', inplace=True)
print(df.describe())
print(df.resample('1h').agg({'open': 'first', 'high': 'max',
                              'low': 'min', 'close': 'last', 'volume': 'sum'}).head())
```

### backtrader

```python
import backtrader as bt
import pandas as pd

df = pd.read_csv('NGAS_8h.csv', parse_dates=['time'])
df.set_index('time', inplace=True)

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

df = pd.read_csv('NGAS_8h.csv', parse_dates=['time'])
close = df.set_index('time')['close']
fast, slow = vbt.MA.run(close, 10), vbt.MA.run(close, 50)
entries = fast.ma_crossed_above(slow)
exits = fast.ma_crossed_below(slow)
pf = vbt.Portfolio.from_signals(close, entries, exits, init_cash=10_000, freq='8h')
print(pf.stats())
```

## Download full data

The complete **NGAS** archive on **[ork.ad](https://ork.ad/)** includes **13 OHLCV timeframes** (`1m`, `3m`, `5m`, `15m`, `30m`, `1H`, `2H`, `4H`, `8H`, `12H`, `16H`, `1D`, `1W`) — **11,861** rows at `8h`, plus all other timeframes in the same ZIP.

**[→ Get the full NGAS dataset on ork.ad](https://ork.ad/)**

---
*GetData · NGAS 8h OHLCV sample on GitHub · Full historical data on [ork.ad](https://ork.ad/) · 2026-07-06 UTC*