# Grid Position Calculator

A free, browser-based **grid trading position calculator** for crypto traders. No server, no data collection — just pure math in your browser.

**🔗 Live: https://nyrarolon.github.io/grid-position-calculator/**

## Features

- Calculate optimal grid levels based on budget and market volatility
- Visual grid visualization showing buy/sell levels and current price
- Fee-aware profit analysis — accounts for maker/taker fee erosion
- Expected monthly return estimates based on grid configuration
- Works entirely in your browser — nothing is sent to any server

## Why Grid Spacing Matters

Most new grid traders set spacing too tight. If your round-trip fee is 0.32% and your grid spacing is 0.5%, you're losing money on every cycle. This calculator shows you the minimum profitable spacing before you deploy capital.

## What the Numbers Tell You

| Input | What it does |
|-------|-------------|
| Budget | How much capital to deploy per pair |
| Grid Levels | Number of buy/sell order pairs |
| Grid Range | Total price range as % from current |
| Maker Fee | Your exchange maker fee (Kraken = 0.16%, Binance = 0.10%) |

## Example

Input: $200 budget, 5 levels, 15% range on SOL at $168.50
Output: 3.0% spacing, $40 per level, ~$5.40/mo estimated return at average market volatility.

## Built With

Pure HTML + CSS + JavaScript. No dependencies, no build step. Download and open locally or use the hosted version.

---

**Want the full automated trading system?** Check out [Cerberus Trading OS](https://ratefoundry.gumroad.com/l/xrtjjv) — three-layer grid trading with recursive learning engine. $97 one-time.

## License

MIT
