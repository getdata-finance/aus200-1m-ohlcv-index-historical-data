# AUS200 1m OHLCV Index Historical Data — Free Sample

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE) [![Dataset rows](https://img.shields.io/badge/full_dataset-5_292_984_rows-blue)](https://getdata.finance/datasets/aus200) [![Updated](https://img.shields.io/badge/weekly_update-every_Saturday_8am_UTC-green)](https://getdata.finance) [![Full data on getdata.finance](https://img.shields.io/badge/download-getdata.finance-orange)](https://getdata.finance/datasets/aus200)

### -> [**Download the full AUS200 dataset on getdata.finance**](https://getdata.finance/datasets/aus200)

**AUS200 1m OHLCV index historical data** — ultra high-quality 1m OHLCV for **S&P/ASX 200**. Clean `datetime, open, high, low, close, volume` CSV for backtesting, algorithmic trading and quantitative research.

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

- **Ultra high-quality 1m OHLCV** for **S&P/ASX 200** (Index)
- **Clean CSV schema** — `datetime, open, high, low, close, volume` (no gaps in formatting)
- **Free evaluation sample** on GitHub (`1m`) · **11 timeframes** on [getdata.finance](https://getdata.finance/datasets/aus200) · **5,292,984** `1m` rows in the full archive
- Built for **backtesting**, **algorithmic trading** and **quantitative finance** workflows
- **Weekly refresh** — [getdata.finance](https://getdata.finance) every **Saturday, 8am UTC+0**; GitHub `1m` sample updated in sync

> **Sample on GitHub** · `AUS200_1m.csv` (162,059 rows, `2026-03-23` -> `2026-09-23`, 10.31 MB). **Full archive on [getdata.finance](https://getdata.finance/datasets/aus200)** — **5,292,984** `1m` rows (full `1m`: 5,046,226), **11 timeframes**, `2008-09-10` -> `2026-09-23`.

## Download sample

**[AUS200_1m.csv](https://github.com/getdata-finance/aus200-1m-ohlcv-index-historical-data/blob/main/AUS200_1m.csv)** on GitHub ([raw CSV](https://raw.githubusercontent.com/getdata-finance/aus200-1m-ohlcv-index-historical-data/main/AUS200_1m.csv)) · [GitHub Releases](https://github.com/getdata-finance/aus200-1m-ohlcv-index-historical-data/releases)

## GitHub Pages

Interactive chart & stats: **[https://getdata-finance.github.io/aus200-1m-ohlcv-index-historical-data/](https://getdata-finance.github.io/aus200-1m-ohlcv-index-historical-data/)**

Full archive & live chart on getdata.finance: **[https://getdata.finance/datasets/aus200](https://getdata.finance/datasets/aus200)**

## Sample vs full dataset

| | **Sample (this repo)** | **Full dataset ([getdata.finance](https://getdata.finance/datasets/aus200))** |
|---|--:|---|
| Instrument | S&P/ASX 200 · Index | S&P/ASX 200 · Index |
| Timeframes | `1m` (sample) | **11** — 1m · 3m · 5m · 15m · 30m · 1H · 4H · 12H · 1D · 3D · 1W |
| 1m rows | 162,059 | **5,292,984** |
| Size | 10.31 MB | full ZIP on [getdata.finance](https://getdata.finance/datasets/aus200) |
| Period | `2026-03-23` -> `2026-09-23` | `2008-09-10` -> `2026-09-23` |
| File | `AUS200_1m.csv` | ZIP on [getdata.finance](https://getdata.finance/datasets/aus200) |
| Coverage report | — | [AUS200 coverage](https://getdata.finance/coverage/aus200) |
| Updates | Weekly (Saturday, 8am UTC+0) — GitHub sample | Weekly (Saturday, 8am UTC+0) — all timeframes |

## Timeframes on GetData

This GitHub repository ships a **`1m` evaluation sample** only. On **[getdata.finance](https://getdata.finance/datasets/aus200)**, each full asset archive is delivered as a ZIP with **11 gap-free OHLCV timeframes** (one CSV per timeframe):

**1m · 3m · 5m · 15m · 30m · 1H · 4H · 12H · 1D · 3D · 1W**

GitHub = `1m` sample · [getdata.finance](https://getdata.finance/datasets/aus200) = all **11** timeframes above for the same instrument.

## Weekly updates

- **[getdata.finance](https://getdata.finance)** — Full datasets are updated every Saturday, 8am UTC+0.
- **GitHub (this repo)** — GitHub samples are refreshed weekly (every Saturday, 8am UTC+0), in sync with getdata.finance.

When a new `1m` sample is published on GitHub, the README, chart preview and CSV reflect the latest week of data.

## Data preview

First and latest rows from the GitHub sample **`AUS200_1m.csv`**:

**First rows**

| datetime | open | high | low | close | volume |
| --- | --- | --- | --- | --- | --- |
| 2026-03-23T02:28:00+00:00 | 8390.01 | 8390.49 | 8385.01 | 8385.01 | 67 |
| 2026-03-23T02:29:00+00:00 | 8385.01 | 8385.5 | 8382.49 | 8384 | 58 |
| 2026-03-23T02:30:00+00:00 | 8384 | 8385.51 | 8381.5 | 8384.01 | 58 |
| 2026-03-23T02:31:00+00:00 | 8384.01 | 8385.51 | 8381.51 | 8382.5 | 94 |
| 2026-03-23T02:32:00+00:00 | 8382.5 | 8383.51 | 8380.5 | 8382.5 | 64 |

**Last rows**

| datetime | open | high | low | close | volume |
| --- | --- | --- | --- | --- | --- |
| 2026-09-23T01:56:00+00:00 | 8751.95 | 8751.95 | 8751.43 | 8751.43 | 1 |
| 2026-09-23T01:57:00+00:00 | 8751.43 | 8752.43 | 8750.95 | 8751.95 | 7 |
| 2026-09-23T01:58:00+00:00 | 8751.95 | 8754.95 | 8751.95 | 8754.95 | 8 |
| 2026-09-23T01:59:00+00:00 | 8754.95 | 8755.94 | 8753.95 | 8754.44 | 19 |
| 2026-09-23T02:00:00+00:00 | 8754.44 | 8755.45 | 8754.44 | 8754.94 | 2 |

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

df = pd.read_csv('AUS200_1m.csv', parse_dates=['datetime'])
df.set_index('datetime', inplace=True)
print(df.describe())
```

### backtrader

```python
import backtrader as bt
import pandas as pd

df = pd.read_csv('AUS200_1m.csv', parse_dates=['datetime'])
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

df = pd.read_csv('AUS200_1m.csv', parse_dates=['datetime'])
close = df.set_index('datetime')['close']
fast, slow = vbt.MA.run(close, 10), vbt.MA.run(close, 50)
entries = fast.ma_crossed_above(slow)
exits = fast.ma_crossed_below(slow)
pf = vbt.Portfolio.from_signals(close, entries, exits, init_cash=10_000, freq='1min')
print(pf.stats())
```

## Download full data

The complete **AUS200** archive on **[getdata.finance](https://getdata.finance/datasets/aus200)** includes **11 OHLCV timeframes** (1m · 3m · 5m · 15m · 30m · 1H · 4H · 12H · 1D · 3D · 1W) — **5,292,984** rows at `1m`, plus all other timeframes in the same ZIP.

**[-> Get the full AUS200 dataset on getdata.finance](https://getdata.finance/datasets/aus200)**

---
*GetData · AUS200 1m OHLCV sample on GitHub · Full historical data on [getdata.finance](https://getdata.finance/datasets/aus200)*
