# icPriceAction

[![Website](https://img.shields.io/badge/Website-icpriceaction.com-E6E7E8?color=111213)](https://icpriceaction.com)
[![YouTube](https://img.shields.io/badge/YouTube-@icPriceAction-red.svg)](https://youtube.com/@icPriceAction)
[![Buy Me a Coffee](https://img.shields.io/badge/Support-Buy%20Me%20a%20Coffee-FFDD00?logo=buy-me-a-coffee&logoColor=black)](https://buymeacoffee.com/icpriceaction)
[![Platform](https://img.shields.io/badge/Platform-NinjaTrader%208-black.svg)](https://ninjatrader.com)

Welcome to the official repository hub for **icPriceAction**, founded, built and implemented by **Istvan Cebrian**.

I build high-performance, native C# NinjaScript tools engineered specifically for **day trading on NinjaTrader 8**. These tools and indicators combine disciplined **Price Action Trading System (PATS)** principles (second entries, trend channels, trapped traders) with institutional **Order Flow & Volume Profile** context.

---

## ☕ Support the Project

Every indicator, drawing utility, and script published under this organization is **100% free and open-source for personal trading use**. There are no paywalls, subscriptions, or locked features and there will never be anything of the sorts!

Developing, optimizing, testing for zero latency on all charts and instruments, and maintaining documentation and releases for this catalog takes a **considerable amount of personal time and ongoing effort**. 

If these tools have saved you screen time, helped you refine your setups, or improved your chart clarity, buying a coffee is the single best way to say thank you and support continued updates:

<p align="left">
  <a href="https://buymeacoffee.com/icpriceaction" target="_blank">
    <img src="https://cdn.buymeacoffee.com/buttons/v2/default-yellow.png" alt="Buy Me A Coffee" width="200">
  </a>
</p>

> **[☕ Support Development on Buy Me a Coffee](https://buymeacoffee.com/icpriceaction)**

---

## 🛠️ The NinjaTrader 8 Suite Directory

All tools are organized into the **`icPA`** folder inside NinjaTrader 8. Below is the quick-reference index of available tools:

### 📐 Specialized Drawing Tools
Precision drawing tools calibrated for rapid chart interaction, micro-channel projection, and risk management without clunky menus.

* **[price-action-channel](https://github.com/icPriceAction/price-action-channel)** — Specialized trend channel utility with automated parallel projections and midlines.
* **[range-band](https://github.com/icPriceAction/range-band)** — Structural range and congestion band framing tool.
* **[measured-move](https://github.com/icPriceAction/measured-move)** — Quick projection of measured leg legs ($Leg 1 = Leg 2$).

---

### 📊 Price Action & Chart Utilities
Lightweight utilities designed to enforce trading discipline, highlight pattern formations, and track execution metrics.

* **[trade-limiter](https://github.com/icPriceAction/trade-limiter)** — Account protection and psychology tool to lock charts and prevent overtrading.
* **[bar-average-time](https://github.com/icPriceAction/bar-average-time)** — Dynamic pace-of-market monitor for tick charts.
* **[tick-counter-side](https://github.com/icPriceAction/tick-counter-side)** — Minimalist, unobtrusive tick countdown positioned on the price axis.
* **[dockable-drawing-toolbar](https://github.com/icPriceAction/drawing-toolbar)** — Floating WPF toolbar providing one-click access to all your favorite drawing tools.
* **[important-news](https://github.com/icPriceAction/important-news)** — Real-time high-impact economic calendar events projected directly onto chart timelines.

---

### 🌊 Order Flow & Volume Analysis
High-performance Direct2D/DirectX market mechanics engines built to confirm structural price action with real-time volume.

* **[volume-profile](https://github.com/icPriceAction/volume-profile)** — Dynamic Value Area (VAH/VAL) and Point of Control (POC) distribution.
* **[footprint](https://github.com/icPriceAction/footprint)** — Ultra-low latency bid/ask volume footprint for tick replay and live execution.
* **[volume-delta-cvd](https://github.com/icPriceAction/volume-delta-cvd)** — Real-time buyer/seller aggression and Cumulative Volume Delta.
* **[delta-profile](https://github.com/icPriceAction/delta-profile)** — Price-level delta distribution showing aggressive absorption vs. exhaustion.
* **[bubble-sweep](https://github.com/icPriceAction/bubble-sweep)** — Visual detection of stop sweeps and aggressive market order absorption.
* **[vwap](https://github.com/icPriceAction/vwap)** — Clean institutional Volume-Weighted Average Price with dynamic standard deviation bands.
* **[divergence-highlighter](https://github.com/icPriceAction/divergence-highlighter)** — Visual marker for key structural price and momentum rejections.

---

## 📥 How to Install Any Tool

1. Navigate to the repository of the tool you want.
2. Click on the **Releases** tab on the right side of the repository.
3. Download the release `.zip` file (e.g., `icPA_[ToolName]_v1.0.0.zip`).
   * *Do NOT extract or unzip the archive.*
4. Open **NinjaTrader 8** $\rightarrow$ **Tools** $\rightarrow$ **Import** $\rightarrow$ **NinjaScript Add-On...**
5. Select the `.zip` file and confirm. The tool will appear under the **icPA** category in your indicators or drawing tools list.

---

## ⚖️ Disclaimer

All software, indicators, drawing tools, and documentation provided by **icPriceAction** are strictly for educational and analytical purposes. Futures trading and any trading involves substantial financial risk and is not suitable for all investors. You may lose all or more than your initial capital. I am not a financial advisor and this is not financial advice. 

NinjaTrader® is a registered trademark of NinjaTrader, LLC. icPriceAction is an independent developer with no official affiliation to NinjaTrader, LLC.
