## Hi, I'm Mark 👋

Second-year Quantitative Finance and Computer Science student at [Stevens Institute of Technology](https://www.stevens.edu/). Mostly working on trading infrastructure: matching engines, exchange protocols, and market data pipelines. Also interested in decentralized finance and low-level systems work.

🌐 [mmednikov.com](https://mmednikov.com/)

### Current Work

- **[Stevens SHIFT](https://fsc.stevens.edu/high-frequency-trading-simulation-system/)** · C++17, Python

  Researcher in Stevens' Financial Systems Lab. Currently working on SHIFT, a high frequency trading simulator that lets students and partner organizations backtest strategies against a live simulated exchange. I onboard new users, maintain the documentation, and build simulated markets with reinforcement learning agents. Internally, I'm leading the migration to Nasdaq ITCH/OUCH protocols so the simulator has an easier time handling an increased amount of agents.
- **[Stevens Student Managed Investment Fund](https://www.stevens.edu/school-business/student-managed-investment-fund)** · Python, Web Dev

  On the Development team. Building data intake, market models, and risk optimizers for Quantitative and Discretionary use.

### Side Projects

- **[Kalshi Order Book Scraper](https://github.com/markm101/Kalshi-Orderbook-Scraper)** · Python, REST

  My first exploration of agentic programming. Polls Kalshi's REST API to capture live order book snapshots on chosen or trending markets, building the historical depth data Kalshi doesn't publish. Useful for backtesting and studying how prediction markets move.
- **[Low Latency Execution Simulator](https://github.com/markm101/Low-Latency-Executor)** · C++

  One of my first experiences with using low-level development in a finance environment. A trade execution simulator with a price-time priority matching engine that handles 736k orders/sec single-threaded, plus a multithreaded implementation for comparing throughput and contention.
- **[WSJ Data Aggregate](https://github.com/markm101/WSJ-Aggregator)** · Python, Beautiful Soup

  Parses Wall Street Journal RSS feeds into a regularly updated headline dataset, accessible via terminal, [web](https://mmednikov.com/wsj/), or Discord. I use it every day, and that's all that matters.
