# 01: Entry Mechanics: Limit vs Market Orders

## The Problem
Traders often find the perfect setup, but they execute poorly. They hit "market buy" during a fast-moving spike, get 5 pips of slippage, and instantly find themselves in drawdown. Or, they place a limit order exactly at the 50% line of an Order Block, but the spread causes them to miss the fill by a fraction of a pip.

## The Story: The Sniper vs The Machine Gunner
A retail trader with FOMO is like a machine gunner firing blindly into the bushes. They waste ammunition (capital) and reveal their position. A professional is a sniper. They calculate wind speed (volatility), distance (risk/reward), and wait for the target to walk precisely into the crosshairs before squeezing the trigger once.

## The Concept
Execution mechanics dictate the difference between a theoretical edge and a realized edge. Understanding how to use Limit vs Market orders is critical.
- **Limit Orders:** Guarantee price, but do not guarantee execution. You provide liquidity.
- **Market Orders:** Guarantee execution, but do not guarantee price (Slippage). You consume liquidity.

### Why It Works
Institutions utilize complex algorithms (TWAP, VWAP) to execute massive orders without showing their hand. As retail SMC traders, we use Limit orders to ride their coattails precisely at the mitigation of their structural footprints (OBs/FVGs).

## How It Works: The Execution Models
1. **The Risk Entry (Limit):** You identify a HTF Order Block. You place a Limit Order at the proximal line (top) of the block. Stop loss goes below the distal line (bottom). *Pro: You rarely miss the trade. Con: You can catch a falling knife if the HTF bias was wrong.*
2. **The Confirmation Entry (Market/Limit):** Price taps the HTF OB. You zoom into the 1m chart. You wait for a 1m CHoCH. You then enter on the mitigation of the 1m OB that caused the CHoCH. *Pro: Much higher win rate and tighter stop. Con: You will sometimes miss the trade if it runs away without pulling back.*

## Key Takeaways
- **Slippage is real.** If you market execute during high-impact news, you will be slipped. Always use limit orders for structured SMC setups.
- **The Spread is the cost of doing business.** Always account for the broker's spread when placing your stop loss and limit entry.
