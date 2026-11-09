## Hi, I'm Mark 👋

Second-year Quantitative Finance and Computer Science student at [Stevens Institute of Technology](https://www.stevens.edu/). Mostly working on trading infrastructure: matching engines, exchange protocols, and market data pipelines. Also interested in decentralized finance and low-level systems work.

🌐 [mmednikov.com](https://mmednikov.com/)

### Current Work

- **[ZKPigeon](https://zkpigeon.com)**

  Providing liquidity to privacy markets and low latency RPC nodes for major networks.
  
- **[Stevens Student Managed Investment Fund](https://www.stevens.edu/school-business/student-managed-investment-fund)**

  Started this fall on the Development team. Building data intake, market models, and risk optimizers for Quantitative and Discretionary use.

- **[Stevens SHIFT](https://fsc.stevens.edu/high-frequency-trading-simulation-system/)**

  Researcher in Stevens' Financial Systems Lab. Currently working on SHIFT, a high frequency trading simulator that lets students and partner organizations backtest strategies against a live simulated exchange. I onboard new users, maintain the documentation, and build simulated markets with reinforcement learning agents. Internally, I'm leading the migration to Nasdaq ITCH/OUCH protocols so the simulator has an easier time handling an increased amount of agents.
- **[Stevens Student Managed Investment Fund](https://www.stevens.edu/school-business/student-managed-investment-fund)** · Python, Web Dev

  Started this fall on the Development team. Building data intake, market models, and risk optimizers for Quantitative and Discretionary use.

### Side Projects

- **Neural Network from Scratch** · C

  A neural network written from scratch in C on top of a custom matrix library, with no external dependencies. The matrix library is done, and the goal is to benchmark the network on MNIST. (in progress)
- **Bittensor Adversarial ML** · Python

  Implemented σ-zero and EAD adversarial attacks on Bittensor Subnet 26 ([Perturb](https://perturbai.io/)) to make EfficientNet-B5 misclassify images while modifying as few pixels as possible, competing for a share of the subnet's token emissions.
- **SIG Predictions Cup** · Python

  Automated strategies for Susquehanna's [prediction market competition](https://predictionscup.com/), trading 2026 midterm election contracts on live order books through the competition API. Fair value came from a logistic regression of win probability on historical polling margins. Finished top 200 out of 1,000 entrants.
- **[Kalshi Order Book Scraper](https://github.com/markm101/Kalshi-Orderbook-Scraper)** · Python, REST

  My first exploration of agentic programming. Polls Kalshi's REST API in batches of 100 markets to capture level 2 order book snapshots (up to 40 depth levels per side) on chosen or trending markets, building the historical depth data Kalshi doesn't publish. It also rebuilds full bid/ask books from Kalshi's bid-only data to measure spread and depth. Useful for backtesting and studying how prediction markets move.
- **[Low Latency Execution Simulator](https://github.com/markm101/Low-Latency-Executor)** · C++

  One of my first experiences with using low-level development in a finance environment. A trade execution simulator that fills orders against market tape with a price-time priority matching engine, handling 736k orders/sec single-threaded and computing VWAP, slippage and fill quality. A multithreaded implementation processes orders up to 6x faster.
- **[WSJ Data Aggregate](https://github.com/markm101/WSJ-Aggregator)** · Python, Beautiful Soup

  Parses Wall Street Journal RSS feeds into a regularly updated headline dataset, accessible via terminal, [web](https://mmednikov.com/wsj/), or Discord. I use it every day, and that's all that matters.

### Contributions

I hope to get more into open-source development and contributions, currently starting slow but all things start somewhere!

- **[Baretab - A Minimal MacOS Switcher](https://github.com/marcusmalloc/baretab)** · Swift, Claude

  A small swift project made by a friend, added a few finishing touches to make QOL better for more users (me).
    
- **[Drogon (1.4k Stars)](https://github.com/drogonframework/drogon)** · C++

  A high-performance C++ web framework, published an undefined behavior fix brought up by a GitHub issue.
    
