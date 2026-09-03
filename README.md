# EURGBP 1m OHLCV Forex Historical Data — Free Sample

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE) [![Dataset rows](https://img.shields.io/badge/full_dataset-5_322_882_rows-blue)](https://getdata.finance/datasets/eurgbp) [![Updated](https://img.shields.io/badge/weekly_update-every_Saturday_8am_UTC-green)](https://getdata.finance) [![Full data on getdata.finance](https://img.shields.io/badge/download-getdata.finance-orange)](https://getdata.finance/datasets/eurgbp)

### -> [**Download the full EURGBP dataset on getdata.finance**](https://getdata.finance/datasets/eurgbp)

**EURGBP 1m OHLCV forex historical data** — ultra high-quality 1m OHLCV for **Euro / British Pound**. Clean `time, open, high, low, close, volume` CSV for backtesting, algorithmic trading and quantitative research.

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

- **Ultra high-quality 1m OHLCV** for **Euro / British Pound** (Forex)
- **Clean CSV schema** — `time, open, high, low, close, volume` (no gaps in formatting)
- **Free evaluation sample** on GitHub (`1m`) · **11 timeframes** on [getdata.finance](https://getdata.finance/datasets/eurgbp) · **5,322,882** `1m` rows in the full archive
- Built for **backtesting**, **algorithmic trading** and **quantitative finance** workflows
- **Weekly refresh** — [getdata.finance](https://getdata.finance) every **Saturday, 8am UTC+0**; GitHub `1m` sample updated in sync

> **Sample on GitHub** · `EURGBP_1m.csv` (55,440 rows, `2026-07-09` -> `2026-09-02`). **Full archive on [getdata.finance](https://getdata.finance/datasets/eurgbp)** — **5,322,882** `1m` rows, **11 timeframes**, `2012-05-23` -> `2026-09-02`.

## Download sample

**[EURGBP_1m.csv](https://github.com/getdata-finance/eurgbp-1m-ohlcv-forex-historical-data/blob/main/EURGBP_1m.csv)** on GitHub ([raw CSV](https://raw.githubusercontent.com/getdata-finance/eurgbp-1m-ohlcv-forex-historical-data/main/EURGBP_1m.csv))

## Sample vs full dataset

| | **Sample (this repo)** | **Full dataset ([getdata.finance](https://getdata.finance/datasets/eurgbp))** |
|---|--:|---|
| Instrument | Euro / British Pound · Forex | Euro / British Pound · Forex |
| Timeframes | `1m` (sample) | **11** — 1m · 3m · 5m · 15m · 30m · 1H · 4H · 12H · 1D · 3D · 1W |
| 1m rows | 55,440 | **5,322,882** |
| Period | `2026-07-09` -> `2026-09-02` | `2012-05-23` -> `2026-09-02` |
| File | `EURGBP_1m.csv` | ZIP on [getdata.finance](https://getdata.finance/datasets/eurgbp) |
| Coverage report | — | [EURGBP coverage](https://getdata.finance/coverage/eurgbp) |
| Updates | Weekly (Saturday, 8am UTC+0) — GitHub sample | Weekly (Saturday, 8am UTC+0) — all timeframes |

## Timeframes on GetData

This GitHub repository ships a **`1m` evaluation sample** only. On **[getdata.finance](https://getdata.finance/datasets/eurgbp)**, each full asset archive is delivered as a ZIP with **11 gap-free OHLCV timeframes**:

**1m** · **3m** · **5m** · **15m** · **30m** · **1H** · **4H** · **12H** · **1D** · **3D** · **1W**

## Weekly updates

- **[getdata.finance](https://getdata.finance)** — Full datasets updated every Saturday, 8am UTC+0.
- **GitHub (this repo)** — GitHub samples refreshed weekly, in sync with getdata.finance.

## Data preview

First and latest rows from the GitHub sample **`EURGBP_1m.csv`**:

**First rows**

| time | open | high | low | close | volume |
| --- | --- | --- | --- | --- | --- |
| 2026-07-09T13:56:00+00:00 | 0.84944 | 0.84948 | 0.84941 | 0.84941 | 147 |
| 2026-07-09T13:57:00+00:00 | 0.84941 | 0.84946 | 0.84939 | 0.84941 | 129 |
| 2026-07-09T13:58:00+00:00 | 0.84941 | 0.84948 | 0.84939 | 0.84948 | 75 |
| 2026-07-09T13:59:00+00:00 | 0.84948 | 0.8495 | 0.84944 | 0.84948 | 110 |
| 2026-07-09T14:00:00+00:00 | 0.84948 | 0.8495 | 0.8494 | 0.84941 | 172 |

**Last rows**

| time | open | high | low | close | volume |
| --- | --- | --- | --- | --- | --- |
| 2026-09-02T01:56:00+00:00 | 0.85742 | 0.85743 | 0.85738 | 0.85739 | 54 |
| 2026-09-02T01:57:00+00:00 | 0.85739 | 0.8574 | 0.85733 | 0.85734 | 46 |
| 2026-09-02T01:58:00+00:00 | 0.85734 | 0.85739 | 0.85733 | 0.85739 | 88 |
| 2026-09-02T01:59:00+00:00 | 0.85739 | 0.85739 | 0.85736 | 0.85737 | 77 |
| 2026-09-02T02:00:00+00:00 | 0.85737 | 0.8574 | 0.85736 | 0.85739 | 93 |

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

Full EURGBP archive — 11 timeframes, gap-free, updated weekly:

**[-> Get the full EURGBP dataset on getdata.finance](https://getdata.finance/datasets/eurgbp)**
