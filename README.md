# Crypto Premium Chart Depository

This repository contains ad-hoc data analysis Jupyter notebooks focused on cryptocurrency price analysis and arbitrage opportunities between exchanges. The notebooks explore various price data from Binance, Gate.io, and other exchanges to identify potential market inefficiencies.

## Contents

- **`btc_fex.ipynb`**:  
  Retrieves historical OHLCV (Open, High, Low, Close, Volume) price data for BTC from Binance and Gate.io for analysis.
  
- **`ckb_test.ipynb`**:  
  Analyzes arbitrage opportunities between CKB/KRW and CKB/USDT exchanges, generating charts to visualize the price differences.

- **`up_bn_test.ipynb`**:  
  Compares KRW-BTC and BTC/USDT prices, incorporating USD futures data to identify arbitrage opportunities and trends.

## Future Work

More test analysis files will be added to this repository to explore further cryptocurrency trading and arbitrage opportunities.

## Requirements

- Python 3.x
- Jupyter Notebook
- pandas
- numpy
- matplotlib
- Binance and Gate.io APIs for retrieving historical data

## Usage

1. Clone the repository:
   ```bash
     git clone https://github.com/your-github-username/kp_crypto.git
   
2.	Run the Jupyter notebooks for ad-hoc cryptocurrency price analysis:
   ```bash
     jupyter notebook <notebook_file.ipynb>
