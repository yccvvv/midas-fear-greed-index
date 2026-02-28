# Midas Fear & Greed Index -- Interactive Prototype

An interactive UI prototype for a proposed **BIST Fear & Greed Index** feature within the [Midas](https://getmidas.com) investment app.

## Live Demo

**[View the prototype](https://yccvvv.github.io/midas-fear-greed-index/)**

## Screens

The prototype includes four clickable screens:

1. **Home Screen** -- Fear & Greed gauge widget in its primary placement on the Midas home feed
2. **Detail View** -- All 7 sub-indicators with individual scores, AI-powered summary, and personalized portfolio comparison
3. **Historical Chart** -- Canvas-rendered line chart with timeframe toggles (1W / 1M / 3M / 1Y)
4. **Stock Detail Page** -- Contextual sentiment banner and AI Technical Consensus card integrated into a THYAO stock page

## Context

This prototype was built as part of a Product Analyst case study exploring how a Turkey-specific Fear & Greed Index could be integrated into the Midas platform. The index is composed of 7 BIST-native sub-indicators:

- BIST-100 Price Momentum
- Market Breadth (advancing vs. declining)
- 52-Week Highs vs. Lows
- Realized Volatility
- Safe Haven Demand (stocks vs. bonds & gold)
- Foreign Investor Net Flow
- USD/TRY Volatility

## Tech

Single-file HTML/CSS/JS. No dependencies. Open `index.html` in any browser.
