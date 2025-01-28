# Cryptocurrency Portfolio Analysis

Analyzes different cryptocurrency portfolio strategies using Python. Compares performance of various portfolio allocations across major cryptocurrencies like Bitcoin, Ethereum, and others.

## Quick Start

1. Clone the repository:
```bash
git clone https://github.com/sergio-pestana/Crypto_Portfolio_Analysis.git
cd Crypto_Portfolio_Analysis
```

2. Set up Python environment:
```bash
python -m venv venv
source venv/bin/activate  # On Windows use: venv\Scripts\activate
pip install -r requirements.txt
```

3. Run the analysis:
```bash
jupyter notebook Analysis_BTC.ipynb
```

## Portfolio Strategies

The analysis includes these portfolio allocations:

- **Mercurius**: BTC (65%), ETH (30%), others - BNB, SOL, XRP, ADA and AVAX (5%)
- **50/30/20**: BTC (50%), ETH (30%), others - BNB, SOL, XRP, ADA and AVAX (20%)
- **BTC/ETH**: BTC (50%), ETH (50%)
- **Altcoin Heavy**: BTC (20%), ETH (30%), others - BNB, SOL, XRP, ADA and AVAX (50%)
- **DeFi Only**: Equal distribution among altcoins (LINK, UNI, AAVE, MKR and CRV)
- **Meme Coins Only**: Equal distribution among all (DOGE, SHIB, PEPE, FLOKI and BONK)

## Data

- Timeframe: January 2021 - April 2022
- Daily prices for BTC, ETH, USDC, ADA, DOT, UNI, ATOM, LINK, BNB
- Data source: Investing.com (via investpy)

## Disclaimer

For educational purposes only. Not financial advice.