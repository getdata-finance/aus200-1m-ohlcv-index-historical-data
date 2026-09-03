# AUS200 1m OHLCV Index Historical Data — Free Sample

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE) [![Dataset rows](https://img.shields.io/badge/full_dataset-5_275_014_rows-blue)](https://getdata.finance/datasets/aus200) [![Updated](https://img.shields.io/badge/weekly_update-every_Saturday_8am_UTC-green)](https://getdata.finance) [![Full data on getdata.finance](https://img.shields.io/badge/download-getdata.finance-orange)](https://getdata.finance/datasets/aus200)

### -> [**Download the full AUS200 dataset on getdata.finance**](https://getdata.finance/datasets/aus200)

**AUS200 1m OHLCV index historical data** — ultra high-quality 1m OHLCV for **S&P/ASX 200**. Clean `time, open, high, low, close, volume` CSV for backtesting, algorithmic trading and quantitative research.

## Table of contents

- [Why this dataset?](#why-this-dataset)
- [Download sample CSV](#download-sample)
- [Sample vs full dataset](#sample-vs-full-dataset)
- [Timeframes on GetData](#timeframes-on-getdata)
- [Weekly updates](#weekly-updates)
- [Data preview](#data-preview)
- [Schema](#schema)
- [Download full data on getdata.finance](#download-full-data-on-getdata)

## Why this dataset?

- **Ultra high-quality 1m OHLCV** for **S&P/ASX 200** (Index)
- **Clean CSV schema** — `time, open, high, low, close, volume` (no gaps in formatting)
- **Free evaluation sample** on GitHub (`1m`) · **11 timeframes** on [getdata.finance](https://getdata.finance/datasets/aus200) · **5,275,014** `1m` rows in the full archive
- Built for **backtesting**, **algorithmic trading** and **quantitative finance** workflows
- **Weekly refresh** — [getdata.finance](https://getdata.finance) every **Saturday, 8am UTC+0**; GitHub `1m` sample updated in sync

> **Sample on GitHub** · `AUS200_1m.csv` (55,440 rows, `2026-07-01` -> `2026-09-02`). **Full archive on [getdata.finance](https://getdata.finance/datasets/aus200)** — **5,275,014** `1m` rows, **11 timeframes**, `2008-09-10` -> `2026-09-02`.

## Download sample

**[AUS200_1m.csv](https://github.com/getdata-finance/aus200-1m-ohlcv-index-historical-data/blob/main/AUS200_1m.csv)** on GitHub ([raw CSV](https://raw.githubusercontent.com/getdata-finance/aus200-1m-ohlcv-index-historical-data/main/AUS200_1m.csv))

## Sample vs full dataset

| | **Sample (this repo)** | **Full dataset ([getdata.finance](https://getdata.finance/datasets/aus200))** |
|---|--:|---|
| Instrument | S&P/ASX 200 · Index | S&P/ASX 200 · Index |
| Timeframes | `1m` (sample) | **11** — 1m · 3m · 5m · 15m · 30m · 1H · 4H · 12H · 1D · 3D · 1W |
| 1m rows | 55,440 | **5,275,014** |
| Period | `2026-07-01` -> `2026-09-02` | `2008-09-10` -> `2026-09-02` |
| File | `AUS200_1m.csv` | ZIP on [getdata.finance](https://getdata.finance/datasets/aus200) |
| Coverage report | — | [AUS200 coverage](https://getdata.finance/coverage/aus200) |
| Updates | Weekly (Saturday, 8am UTC+0) — GitHub sample | Weekly (Saturday, 8am UTC+0) — all timeframes |

## Timeframes on GetData

This GitHub repository ships a **`1m` evaluation sample** only. On **[getdata.finance](https://getdata.finance/datasets/aus200)**, each full asset archive is delivered as a ZIP with **11 gap-free OHLCV timeframes**:

**1m** · **3m** · **5m** · **15m** · **30m** · **1H** · **4H** · **12H** · **1D** · **3D** · **1W**

## Weekly updates

- **[getdata.finance](https://getdata.finance)** — Full datasets updated every Saturday, 8am UTC+0.
- **GitHub (this repo)** — GitHub samples refreshed weekly, in sync with getdata.finance.

## Data preview

First and latest rows from the GitHub sample **`AUS200_1m.csv`**:

**First rows**

| time | open | high | low | close | volume |
| --- | --- | --- | --- | --- | --- |
| 2026-07-01T20:49:00+00:00 | 8701.73 | 8701.73 | 8701.73 | 8701.73 | 1.31128 |
| 2026-07-01T20:50:00+00:00 | 8701.73 | 8701.73 | 8701.72 | 8701.73 | 2 |
| 2026-07-01T20:51:00+00:00 | 8701.73 | 8701.73 | 8701.73 | 8701.73 | 2.64042 |
| 2026-07-01T20:52:00+00:00 | 8701.73 | 8701.73 | 8701.22 | 8701.22 | 3 |
| 2026-07-01T20:53:00+00:00 | 8701.22 | 8701.22 | 8700.72 | 8700.72 | 1 |

**Last rows**

| time | open | high | low | close | volume |
| --- | --- | --- | --- | --- | --- |
| 2026-09-02T01:56:00+00:00 | 8962 | 8962 | 8957 | 8957 | 28 |
| 2026-09-02T01:57:00+00:00 | 8957 | 8957 | 8955 | 8955.98 | 20 |
| 2026-09-02T01:58:00+00:00 | 8955.98 | 8957.98 | 8955.48 | 8956.99 | 32 |
| 2026-09-02T01:59:00+00:00 | 8956.99 | 8958.49 | 8955.99 | 8957.99 | 18 |
| 2026-09-02T02:00:00+00:00 | 8957.99 | 8958.49 | 8956.99 | 8958.49 | 9 |

## Schema

| Column | Description |
| --- | --- |
| `time` | Bar open timestamp (UTC, ISO-8601). |
| `open` | Opening price of the candlestick bar. |
| `high` | Highest price during the bar. |
| `low` | Lowest price during the bar. |
| `close` | Closing price of the candlestick bar. |
| `volume` | Tick volume (number of price updates) during the bar. |

```text
time,open,high,low,close,volume
```

## Download full data

Full AUS200 archive — 11 timeframes, gap-free, updated weekly:

**[-> Get the full AUS200 dataset on getdata.finance](https://getdata.finance/datasets/aus200)**
