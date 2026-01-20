**Depth Of Market (DOM) – PrimeVIPDemon**

Depth of Market (DOM) [PrimeVIPDemon] is an advanced TradingView Pine Script v5 indicator that visualizes real-time and historical order flow, volume distribution, imbalances, and key market levels directly on the chart. It’s a heavily optimized and extended modification of LuxAlgo’s original DOM concept, built for serious order-flow and scalping analysis.

🔧 **FEATURES**

  Full DOM Ladder

    Bid / Ask volume

    Real-time volume accumulation

    Tick or point-based mode (AUTO or MANUAL)

  Order Flow Metrics

    Total volume per price level

    Buy vs sell volume

    Intra-level imbalance (buy − sell)

    Inter-level imbalance (level-to-level delta)

    Buying pressure percentage

  Market Depth Visualization

    Cumulative demand below price

    Cumulative supply above price

    Adjustable histogram sizing

  Key Levels Engine

    Previous day & week (H/L/M/Close)

    Session open, high, low, mid

    Open Range & Initial Balance

    VWAP with ±1/2/3 standard deviations

    Point of Control (POC)

  Time & Sales Panel

    Real-time executions

    Buy/sell color coding

    Order size filtering

    Timezone offset support

⚙️ **CONFIGURATION HIGHLIGHTS**

  Period Anchoring

    DAILY or SESSIONS (RTH-aware for US markets)

  Performance Controls

    Enable/disable heavy columns (Profile, Depth, Imbalances)

    Adjustable DOM rows and update limits

    Real-time only mode for low-latency use

  Crypto Support

    Custom volume precision

    Automatic formatting for large decimal volumes


🧠 **HOW IT WORKS (HIGH LEVEL)**

    Historical bars distribute volume evenly across price levels.

    Real-time data tracks tick-by-tick volume deltas.

    Maps are capped to prevent memory overflow.

    The DOM auto-recenters when price moves outside bounds.

    Imbalances are dynamically highlighted using percentile thresholds.


📌 **INTENDED USE**

  This indicator is designed for:

    Scalping & intraday trading

    Order flow and liquidity analysis

    Futures, equities, and crypto markets


📜 **LICENSE**

    This project is licensed under:
    Creative Commons Attribution-NonCommercial-ShareAlike 4.0 (CC BY-NC-SA 4.0)
    https://creativecommons.org/licenses/by-nc-sa/4.0/

    © LuxAlgo
    Modified and extended by PrimeVIPDemon


🏷 **VERSION**

    PrimeVIPDemon DOM v1.0
