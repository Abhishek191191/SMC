# SMC Mastery TradingView Indicator

This repository includes a custom Pine Script (`tradingview_smc_mastery.pine`) designed to automate the visual identification of the core Smart Money Concepts taught in this curriculum.

## How to Install
1. Open TradingView and open any chart.
2. At the bottom of the screen, click on the **Pine Editor** tab.
3. Open the `tools/tradingview_smc_mastery.pine` file from this repository, copy all the code, and paste it into the Pine Editor.
4. Click **Save** and name it "SMC Mastery".
5. Click **Add to Chart**.

## Features Included
- **Market Structure (BOS / CHoCH):** Automatically detects structural breaks and changes of character based on pivot highs and lows.
- **Fair Value Gaps (FVG):** Highlights bullish (green) and bearish (red) imbalances caused by institutional displacement.
- **Order Blocks (OB):** Identifies the last opposing candle prior to a displacement that creates an FVG, drawing a zone forward in time for potential mitigation entries.
- **Premium / Discount Arrays:** Automatically draws the 50% Equilibrium line of the current dealing range to ensure you never buy in a premium or sell in a discount.

## Curriculum Integration
This indicator is not a "buy/sell" signal generator. It is a visual aid intended to be used alongside **Module 08: Multi-Timeframe Analysis** and **Module 09: Entry Strategies**.

**Pro Tip:** Use the indicator on the 1-hour or 4-hour chart to map your structural bias and HTF Order Blocks. Then, drop down to the 5-minute or 1-minute chart to hunt for lower timeframe CHoCHs and FVGs within those HTF zones.
