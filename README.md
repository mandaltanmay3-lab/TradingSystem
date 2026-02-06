\# Indian Stock Trading System



An automated intraday trading system for NSE/BSE stocks.



\## Project Status

🟡 \*\*In Development\*\* - Step 1 of 30 completed



\## Features (Planned)

\- Real-time NSE/BSE data ingestion

\- Twitter sentiment analysis

\- News sentiment analysis

\- Technical indicator calculation (RSI, MACD, etc.)

\- Signal generation engine

\- Risk management

\- Broker API integration (Zerodha/Upstox)

\- Web dashboard for monitoring

\- Automated order execution



\## Tech Stack

\- \*\*Language:\*\* Python 3.10+

\- \*\*Database:\*\* SQLite

\- \*\*Web Framework:\*\* Flask

\- \*\*Data Sources:\*\* yfinance, Twitter API, News APIs

\- \*\*Broker:\*\* Zerodha Kite Connect / Upstox



\## Project Structure

```

TradingSystem/

├── src/              # Source code

├── config/           # Configuration files

├── data/             # Database and data files

├── logs/             # Application logs

├── tests/            # Test files

├── docs/             # Documentation

├── web/              # Web dashboard

└── scripts/          # Utility scripts

```



\## Setup Instructions



\### Prerequisites

\- Python 3.10 or higher

\- Anaconda (recommended)

\- Git (optional)



\### Installation

1\. Clone or download this repository

2\. Install dependencies:

```

&nbsp;  pip install -r requirements.txt

```

3\. Copy config/config.example.json to config/config.json

4\. Fill in your API keys in config/config.json

5\. Initialize database:

```

&nbsp;  python scripts/setup\_database.py

```



\## Development Progress

\- \[x] Step 1: Project structure setup

\- \[ ] Step 2: Configuration file creation

\- \[ ] Step 3: Configuration manager module

\- \[ ] Step 4: Logger module

\- \[ ] Step 5: Foundation testing

\- \[ ] ... (25 more steps)



\## Disclaimer

⚠️ \*\*This is for educational purposes only.\*\*

\- Start with paper trading

\- Never risk money you cannot afford to lose

\- Past performance does not guarantee future results

\- The creators are not responsible for any trading losses



\## License

MIT License - Free to use and modify



\## Contact

For questions or issues, please create an issue in the repository.



---

\*\*Last Updated:\*\* 2026-02-04

\*\*Version:\*\* 0.1.0-alpha

