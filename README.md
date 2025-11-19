# ds_bhumika_khatwani

This folder contains the main notebook and folders expected for the Web3 Trading Team data science assignment.

## Contents

- `notebook_1.ipynb` – Full Colab-compatible notebook that:
  - Loads `fear_greed_index.csv` and `historical_data.csv`
  - Cleans and merges the datasets
  - Engineers daily trading features
  - Produces CSV outputs in `csv_files/`
  - Generates charts in `outputs/`

- `csv_files/` – This is where the notebook saves:
  - `fear_greed_cleaned.csv`
  - `trades_cleaned.csv`
  - `sentiment_trades_daily.csv`

- `outputs/` – This is where the notebook saves:
  - `sentiment_timeline.png`
  - `volume_vs_sentiment.png`
  - `pnl_vs_sentiment.png`
  - `profit_margin_vs_sentiment.png`
  - `long_short_balance.png`

## How to Use

1. Open `notebook_1.ipynb` in Google Colab.
2. Upload the raw files:
   - `fear_greed_index.csv`
   - `historical_data.csv`
3. Run all cells.

