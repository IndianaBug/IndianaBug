## Pavlo Vanat

Solo developer focused on **data engineering and machine learning** for algorithmic system development.

I work primarily on **high-throughput market data pipelines**, **time-series processing**, and **ML-driven decision systems**. My background includes backend and server-side engineering, with hands-on experience operating **containerized infrastructure**.

### Tech
- Python, Rust  
- Data engineering & time-series systems  
- Machine learning for algorithmic strategies  
- Backend & infrastructure (Kubernetes)

### Current focus
- Algorithmic trading systems  
- Real-time market data ingestion & processing  
- Research-driven ML experimentation

### Collaboration / Research
If you’re interested in **training algorithmic trading bots**, I’m building a pipeline to produce **polished, ML-ready datasets** inspired by *Marcos López de Prado*’s methodology.

This work is **actively in progress** and not fully released yet, but the core components are coming together and should be usable **within the next month or so**.

The current focus is on **feature engineering and optimization** around **trades and order-book depth**, with particular emphasis on **event-based bar construction**, **labeling**, and **CUSUM-driven sampling**.

Feature development is centered on **depth- and trade-derived signals**, including:
- **Time-weighted depth** and depth persistence for bar formation  
- **Canceled vs executed depth** and **reinforced depth** (resting liquidity that repeatedly absorbs flow)  
- **Absorption metrics** capturing aggressive flow versus available liquidity  
- **Footprint-style features** (volume and delta by price, imbalance ratios, exhaustion signals)  
- **Volatility-derived microstructure signals** such as impact, intensity, bursts, exhaustion, and VPIN-style flow toxicity  
- Cross-side and cross-level interactions between trades and L2 dynamics  

These features are applied **consistently across multiple data representations** (trades, depth, bars, and events), rather than being limited to raw trade data. The pipelines are designed for **hyperparameter optimization** over bar parameters, labeling logic, CUSUM thresholds, depth decay, and feature interactions, with explicit controls for **dependence, leakage, and sample efficiency**.

For now, this work is expected to **remain proprietary**.  
Access will be limited to **research collaborators** who can contribute meaningfully through **analysis, validation, methodological feedback, or experimental work** (not financial contributions).

Funding rates and open interest features are planned, but the current effort is focused on making **depth- and trade-based representations statistically robust and optimizer-ready**.

Open to collaboration on **technically challenging, research-driven projects**.

### Contact
- Discord: https://discord.gg/wG49SpsM  
- Email: arb_van_go@outlook.com

