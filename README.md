<a name="top"></a>

# A List of Prediction Market Analytics Tools You Should Use Before Losing Money

![Maintained](https://img.shields.io/badge/Maintained%3F-yes-brightgreen.svg)
![PRs Welcome](https://img.shields.io/badge/PRs-welcome-blue.svg)
[![Telegram](https://img.shields.io/badge/Telegram-Predictbook_Analysis-26A5E4?logo=telegram&logoColor=white)](https://t.me/PredictbookAnalysis)

Maintained by [Predictbook](https://predictbook.co): independent market-mechanics analysis for prediction markets, odds, volume, and timing, not headlines. Follow the breakdowns on [X](https://x.com/predictbook) or [Telegram](https://t.me/PredictbookAnalysis), or get real-time move alerts on [Telegram](https://t.me/Predictbook).

A working list of tools for trading, tracking, and researching prediction markets (Polymarket, Kalshi, and others). Each entry covers what it does, what it's best for, who's behind it (where that's actually public), pricing, and phase. Entries are added as they're found. Nothing here is guaranteed to be maintained by its creators, so vet anything you connect a wallet to.

Want all of the tools below in one place? Follow the [Prediction Market Tools X List](https://x.com/i/lists/2087458894452818184).

Every tool here gets reviewed monthly to catch dead links, pulled products, and anything that's gone quiet. Flag anything we've missed and we'll get to it.

If this list saves you some digging, a ⭐ on the repo helps more people find it (no pressure either way, the list stays free and open regardless).

## 📊 At a Glance

| Tools | Categories | Contributors | GitHub views (7 wks) |
|---|---|---|---|
| 59 (+9 this wk) | 7 | 22 (+8 this wk) | 995 |

*Updated every Sunday.*

## Contents

| Category | What it covers | Tools |
|---|---|---|
| [🌐 Cross-Platform Odds Aggregators](#cross-platform-odds-aggregators) | compare odds and volume across platforms at once. | 5 |
| [🤖 Trade Copying & Automation](#trade-copying--automation) | mirror or auto-copy other traders' positions. | 5 |
| [⚡ Trading Terminals & Execution](#trading-terminals--execution) | place and manage trades across venues from one interface. | 10 |
| [📡 Signal & Fair-Value](#signal--fair-value) | spot mispriced markets and model-vs-market gaps. | 2 |
| [🔍 Wallet & Trader Analytics](#wallet--trader-analytics) | research other traders' wallets and track records. | 15 |
| [🐋 Alerts & Whale Monitoring](#alerts--whale-monitoring) | get pinged on big trades and unusual wallet activity. | 7 |
| [🧠 Research & Market Discovery](#research--market-discovery) | find and dig into markets and data worth watching. | 14 |
| [☠️ No Longer Maintained](#no-longer-maintained) | tools that used to be here, now dead or abandoned. | 1 |

---

<a name="featured"></a>

## ⭐ Featured

- **[Predictbook](https://predictbook.co)**: Independent prediction-market intelligence, built to make Kalshi and Polymarket pricing actually legible.
  Real-time monitoring across politics, crypto, sports, tech, and economics, plus whale-move tracking and cross-platform arbitrage spotting. This is written analysis, not just alerts: every piece cites its sources and links the underlying market, explaining not just what a price is but why it got there and what trade it implies.
  - **Best for:** anyone who wants the numbers explained in writing, not just pinged at.
  - **Follow:** [X](https://x.com/predictbook) · [Substack](https://predictbook.substack.com/) · [Telegram (analysis)](https://t.me/PredictbookAnalysis) · [Telegram (alerts)](https://t.me/Predictbook)

[↑ Back to top](#top)

---

<a name="cross-platform-odds-aggregators"></a>

## 🌐 Cross-Platform Odds Aggregators

- **[Polyrama](https://polyrama.io/)**: Free real-time terminal and [open-source MCP server](https://github.com/Polyrama/mcp) for Polymarket and Kalshi.
  Combines live odds and market search with public-wallet analytics, trader leaderboards, whale and mispricing signals, dashboard snapshots, and historical backtests. Its MCP tools support research and paper orders only, not live execution.
  - **Best for:** researchers and AI agents that need one typed interface for cross-venue market and trader intelligence.
  - **Team:** independent Polyrama team. Young project — the MCP server repo has minimal commit history as of Aug 2026, worth keeping an eye on.
  - **Pricing:** free.
  - **Phase:** live.
  - **Added:** Aug 2026 · **Reviewed:** Aug 2026

- **[Predictefy](https://predictefy.com/)**: Aggregates and normalizes odds and volume across Polymarket, Kalshi, and other venues into one terminal.
  Built for spotting cross-platform arbitrage without juggling multiple tabs.
  - **Best for:** traders comparing odds across platforms instead of tab-hopping.
  - **Team:** bootstrapped, built by "Tafcir" and co-founders (per their own dev.to post). No external funding disclosed.
  - **Pricing:** not publicly listed.
  - **Phase:** live.
  - **Added:** Aug 2026 · **Reviewed:** Aug 2026

- **[PredictionHero](https://predictionhero.com/)**: Aggregates live odds across Polymarket, Kalshi, Limitless, Predict.Fun, and Opinion.
  Trending, new, and ending-soon views, plus a "War Index" for markets seeing heavy activity.
  - **Best for:** hunting the widest net for where markets on the same event disagree.
  - **Team:** not publicly listed.
  - **Pricing:** not publicly listed.
  - **Phase:** beta.
  - **Added:** Aug 2026 · **Reviewed:** Aug 2026

- **[Predictions Network](https://www.thebestpredictionmarkets.com/)**: Compares the same outcome across 12 venues side by side and highlights the best price **after fees**.
  Covers Polymarket, Kalshi, Limitless, Hyperliquid, SX Bet, Gemini, Pascal, OG, Futuur, Smarkets, Matchbook, and Predict Street, mixing crypto-native venues with sportsbook-style ones. Per-event comparison pages, a cross-venue spreads view, and prices date-stamped from the underlying data so a quote is never shown as fresher than it is. Read-only: no wallet connection, no execution. Further venues are in onboarding and will price as each clears its checks. A Spanish edition runs at [prediccioneslatam.com](https://www.prediccioneslatam.com/).
  - **Best for:** checking which venue actually prices an outcome best before you open an account there.
  - **Team:** independent, bootstrapped. No funding disclosed.
  - **Pricing:** free.
  - **Phase:** live (more venues in onboarding).
  - **Added:** Aug 2026 · **Reviewed:** Aug 2026

- **[EventTracker](https://eventtracker.podcomet.ai)**: Federated dashboard combining data from 28 prediction-market and event-contract venues, including Polymarket, Kalshi, Novig, Opinion, Limitless, Rothera, and ProphetX.
  Whale-wallet following, cross-venue arbitrage detection, resolution-status alerts, and a fair-price calculator across the aggregated venues. Display-only: no wagers taken, no execution.
  - **Best for:** arbitrage and mispricing checks across a wider venue set than most single-platform aggregators cover.
  - **Team:** six co-founders, headed by Tal Ayalon (PhD student, information science, Drexel University; prior data/information-systems work at the UN and World Bank).
  - **Pricing:** free tier; premium $22/month or $199/year.
  - **Phase:** live.
  - **Added:** Sep 2026 · **Reviewed:** Sep 2026

[↑ Back to top](#top)

---

<a name="trade-copying--automation"></a>

## 🤖 Trade Copying & Automation

- **[PolyCopy](https://polycopy.app/)**: Non-custodial Polymarket copy-trading dashboard with an algorithmic "Copy Score."
  Grades traders by category track record rather than raw follower counts, with optional auto-copy bots.
  - **Best for:** picking who to copy based on real category performance, not follower count.
  - **Team:** not publicly listed.
  - **Pricing:** free tier, Premium $30/mo.
  - **Phase:** live.
  - **Added:** Aug 2026 · **Reviewed:** Aug 2026

- **[Kreo](https://enter.kreo.app/)**: Telegram- and web-based non-custodial copy-trading tool for Polymarket and Kalshi wallets.
  Sub-3-second execution and insider-flow alerts.
  - **Best for:** traders who want fast wallet-copying without a subscription.
  - **Team:** not publicly listed.
  - **Pricing:** flat 0.5% fee, no subscription.
  - **Phase:** live.
  - **Added:** Aug 2026 · **Reviewed:** Aug 2026

- **[Polyfollow](https://www.polyfollow.com/)**: Polymarket trader discovery and copy-trading platform with public wallet profiles, rankings, performance comparisons, risk analysis, and optional automated copying.
  Lets users browse traders and compare public performance data before deciding whom to follow.
  - **Best for:** researching public wallet performance before following or copying a trader.
  - **Team:** Sebastian Legarraga (owner/operator).
  - **Pricing:** browsing and analytics are free; copied taker orders carry a 0.5% builder fee, with no subscription or performance fee.
  - **Phase:** live.
  - **Added:** Sep 2026 · **Reviewed:** Sep 2026

- **[PolyBot](https://polybot.trading/)**: Telegram-native, self-custodial Polymarket trading system that turns smart-wallet discovery into automated execution.
  Its Smart Wallets engine goes beyond raw leaderboards to surface traders by copyability, sustained 7d/30d performance, consistency, slippage, copy-capital requirements, modeled copy P&L, and risk flags. Follow a wallet through your own Safe with fixed or proportional sizing, market or limit execution, price and category filters, daily and per-position caps, plus stop-loss, take-profit, trailing-stop, and counter-trade controls. Also includes strategy automation, sponsored gas, portfolio and performance tracking, alerts, advanced orders, and 2FA.
  - **Best for:** serious Polymarket traders who want to find wallets worth copying, pressure-test the edge, and automate the trade without leaving Telegram.
  - **Team:** not publicly listed. Domain registered ~Sept 2025 and flagged low-trust by third-party scanners — self-custodial via your own Safe (not a private-key/seed-phrase model), but vet independently before connecting a wallet.
  - **Pricing:** 1% fee on successful trades.
  - **Phase:** live.
  - **Added:** Aug 2026 · **Reviewed:** Aug 2026

- **[Garnet](https://github.com/AndreySchurko/garnet-polymarket)**: Self-hosted, source-available Polymarket copy-trading engine written in Rust.
  You choose the wallets; it detects their trades three independent ways (RTDS websocket, /activity polling, Polygon logs) and mirrors them under per-event exposure caps, a daily loss stop and a database-backed killswitch, with a shadow mode that pays the same fees as live.
  - **Best for:** traders who already know which wallets they want to copy and would rather run the bot on their own server, with their own key, than hand either to a service.
  - **Team:** Andrey Schurko (author).
  - **Pricing:** free for individuals trading their own funds (BUSL-1.1, converts to Apache-2.0 in 2030); commercial license for companies and funds.
  - **Phase:** live (v0.1.0).
  - **Added:** Sep 2026 · **Reviewed:** Sep 2026

[↑ Back to top](#top)

---

<a name="trading-terminals--execution"></a>

## ⚡ Trading Terminals & Execution

- **[oracle3](https://github.com/YichengYang-Ethan/oracle3-prediction-market-agent)**: Open-source prediction-market trading engine for Kalshi, Polymarket and Solana.
  Checks fee-adjusted no-arbitrage relations across related event contracts using each venue's official fee schedule, runs cointegration and lead-lag strategies, backtests on recorded data, and trades live or on paper under pre-trade risk limits; a 13-tool MCP server exposes order books, the arbitrage checks and paper execution to AI agents.
  - **Best for:** finding cross-contract and cross-venue arbitrage net of fees, from Python or from an AI agent.
  - **Team:** Yicheng Yang (open-source maintainer).
  - **Pricing:** free, open-source (Apache-2.0).
  - **Phase:** live.
  - **Added:** Sep 2026 · **Reviewed:** Sep 2026

- **[Homerun](https://github.com/braedonsaunders/homerun)**: Open-source prediction-market trading platform for Polymarket and Kalshi.
  Write full Python strategies and data sources, backtest on L2 book replay, then paper or live trade from one self-hosted stack (25+ built-in strategies, copy trading, AI scoring, real-time dashboard).
  - **Best for:** builders who want a full Python strategy/backtest/live stack instead of a hosted terminal alone.
  - **Team:** Braedon Saunders (open-source maintainer).
  - **Pricing:** free, open-source (AGPL-3.0).
  - **Phase:** live.
  - **Added:** Sep 2026 · **Reviewed:** Sep 2026

- **[Sonist](https://sonist.tech/)**: Sonist automates live mention-market trading on Kalshi and Polymarket.
  It brings markets from both exchanges into one interface and monitors live audio, subtitle feeds, or accessibility captions for configured words. When a word is said, Sonist applies your risk limits and sends the trade through your account, letting you use the lowest-latency source available for each event.
  - **Best for:** mention-market traders who want automated execution from the lowest-latency live source available for each event.
  - **Team:** independent, founder-built.
  - **Pricing:** free tier; Plus $29/mo; Pro $49/mo.
  - **Phase:** live.
  - **Added:** Sep 2026 · **Reviewed:** Sep 2026

- **[Stand](https://www.stand.trade/)**: Trading terminal and aggregator for Kalshi and Polymarket with a "counter-trading" feature.
  Auto-fades historically unprofitable wallets instead of following the crowd.
  - **Best for:** traders who'd rather fade known losers than copy winners.
  - **Team:** co-founded by Edward Ridgely (per Finance Magnates and The Defiant coverage). ~$200M annualized volume reported, no public funding disclosed.
  - **Pricing:** not publicly listed.
  - **Phase:** live.
  - **Added:** Aug 2026 · **Reviewed:** Aug 2026

- **[Traderline](https://traderline.com/)**: Free third-party ladder-trading interface with real-time charts and hotkeys.
  Faster order execution on Polymarket and Betfair. Also covers Betfair, not just prediction markets.
  - **Best for:** execution speed over analytics.
  - **Team:** built by Mythical Technologies Lda (Portugal), operating trading software since ~2011 (self-reported).
  - **Pricing:** free.
  - **Phase:** live.
  - **Added:** Aug 2026 · **Reviewed:** Aug 2026

- **[Predict Parity](https://predictparity.com/)**: Trade across multiple platforms from one interface while tracking wallet-level PnL.
  Also tracks win rates and "smart money" wallets on Polymarket and Kalshi.
  - **Best for:** traders who want execution and wallet tracking in the same tab.
  - **Team:** not publicly listed (a third-party directory attributes it to "a small New York team," unconfirmed).
  - **Pricing:** not publicly listed.
  - **Phase:** live.
  - **Added:** Aug 2026 · **Reviewed:** Aug 2026

- **[Kairos](https://kairos.trade/)**: Trading terminal and API across Kalshi, Polymarket, Predict.fun, and Hyperliquid.
  Stacks matching contracts into a single composite order book and routes orders to the best price on any venue. Colocated feeds, sub-second streaming books, market-making and arbitrage strategy templates, backtesting against recorded books, and REST + WebSocket APIs with a free sandbox. Execution round trips in tens of milliseconds (self-reported).
  - **Best for:** heavy cross-venue traders who don't want a separate login for every platform.
  - **Team:** founded by ex-Cboe quants. Raised $2.5M led by a16z crypto with Geneva Trading participating (per a16z crypto and Fortune coverage).
  - **Pricing:** free sandbox, paid tiers not publicly listed.
  - **Phase:** live.
  - **Added:** Aug 2026 · **Reviewed:** Aug 2026

- **[Macropredict](https://macropredict.io/)**: Real-money prediction app covering politics, crypto, sports, and more, with combo betting.
  Stack calls into combos for bigger payouts. $5 minimum per prediction, odds shown in cents, instant cash-out.
  - **Best for:** casual predictors who want a mobile-first, combo-style betting interface.
  - **Team:** not publicly listed (self-disclosed builder in community discussion, not independently confirmed).
  - **Pricing:** free to browse, $5 minimum per prediction.
  - **Phase:** live.
  - **Added:** Aug 2026 · **Reviewed:** Aug 2026

- **[River Markets](https://rivermarkets.com/)**: Prime broker for prediction markets, built for professional trading firms.
  Unified execution and risk management across venues. Institutional-focused, not a retail terminal.
  - **Best for:** professional trading firms that need unified execution and risk across multiple venues.
  - **Team:** $8.5M seed round led by Haun Ventures (per River Markets' own X announcement, Aug 2026).
  - **Pricing:** not publicly listed.
  - **Phase:** live.
  - **Added:** Aug 2026 · **Reviewed:** Aug 2026

- **[Dimes Multiply](https://dimes.fi)**: Embedded leverage layer that front-ends integrate to offer up to 10x on Polymarket positions, rather than a venue you trade on yourself.
  B2B middleware: a terminal, wallet, or app calls a REST API and Dimes provisions the credit, hedges it, and settles it, so the integrator never runs margin in-house. Exposure is a contract-for-difference on Polygon settled in USDC, sized 2x-10x in 0.25x increments, and limited to binary and simple categorical markets. A "leverage decay" rule automatically cuts exposure as a market's book thins toward resolution, which is the gap-risk problem most leveraged prediction market products don't describe publicly. The TypeScript SDK is `@dimes-dot-fi/sdk` (MIT, source at [dimes-fi/dimes-sdk](https://github.com/dimes-fi/dimes-sdk)), with a reference frontend at [dimes-fi/dimes-demo-ui](https://github.com/dimes-fi/dimes-demo-ui), and sandbox mode runs without funds. An MCP server is on npm but its source repo is not currently public, and there is no longer a public Python client.
  - **Best for:** teams shipping a terminal or wallet who want margin as a feature without building a risk desk. Not directly useful to a retail trader, there is no Dimes front-end to trade on.
  - **Team:** no independent coverage found. The company states backing from Coinbase Ventures and Accel and an institutional underwriting facility with $100M+/month capacity; both are self-reported.
  - **Pricing:** not publicly listed. The protocol charges entry, time-based, and liquidation fees, and the integrating platform sets its own origination fee on the leveraged volume it generates.
  - **Phase:** live API with public docs and published packages, but no partner integrations are publicly named. The TypeScript SDK is at 2.5.0; the Python client and MCP server sources were taken private in Aug 2026.
  - **Added:** Sep 2026 · **Reviewed:** Sep 2026

[↑ Back to top](#top)

---

<a name="signal--fair-value"></a>

## 📡 Signal & Fair-Value

- **[PMIP](https://pmip.io/)**: Portfolio terminal tracking live spreads, positions, and P&L across Kalshi and Polymarket.
  Resolution-rule analysis and an AI analyst chat built in.
  - **Best for:** spotting mispricing from resolution-rule differences between venues.
  - **Team:** not publicly listed.
  - **Pricing:** not publicly listed.
  - **Phase:** pre-launch.
  - **Added:** Aug 2026 · **Reviewed:** Aug 2026

- **[Alphascope](https://www.alphascope.app/)**: AI research workspace aggregating live odds, news-impact analysis, and probability charts.
  Covers Polymarket, Kalshi, Manifold, and Opinion. Portfolio tracking and automated strategies are listed as "coming soon."
  - **Best for:** traders who want an AI read on whether the news justifies the price.
  - **Team:** not publicly listed.
  - **Pricing:** not publicly listed.
  - **Phase:** live (some features coming soon).
  - **Added:** Aug 2026 · **Reviewed:** Aug 2026

[↑ Back to top](#top)

---

<a name="wallet--trader-analytics"></a>

## 🔍 Wallet & Trader Analytics

- **[Polysights](https://www.polysights.xyz/)**: Analytics-and-execution platform for Polymarket covering market discovery and insider-wallet detection.
  Includes a trading terminal with API/CLI access.
  - **Best for:** spotting sharp wallets before the price catches up.
  - **Team:** founded by Tre Upshaw. Raised $1.5M backed by Polymarket (per CNBC, June 2026).
  - **Pricing:** not publicly listed.
  - **Phase:** beta.
  - **Added:** Aug 2026 · **Reviewed:** Aug 2026

- **[Polymarket Analytics](https://polymarketanalytics.com/)**: Searchable database of 1M+ Polymarket traders and markets.
  Trader P&L visualization and custom watchlists, refreshed every 5 minutes.
  - **Best for:** digging through the largest historical trader database out there.
  - **Team:** not publicly listed.
  - **Pricing:** not publicly listed.
  - **Phase:** live.
  - **Added:** Aug 2026 · **Reviewed:** Aug 2026

- **[PolyScalping](https://polyscalping.org/)**: Free, no-signup Polymarket scanner tracking earnings across LP rewards, maker/taker rebates, referrals, and yield.
  Leaderboards and fee calculators included.
  - **Best for:** seeing every reward stream Polymarket's own UI hides.
  - **Team:** two independent developers, "kober" and "d1namit" (per their own X posts). No institutional backing.
  - **Pricing:** free.
  - **Phase:** live.
  - **Added:** Aug 2026 · **Reviewed:** Aug 2026

- **[PredictFolio](https://predictfolio.com/)**: Free analytics platform tracking Polymarket and Kalshi trader PnL, win rates, and market volume and pricing.
  Includes a trader-discovery leaderboard.
  - **Best for:** free multi-platform trader performance tracking.
  - **Team:** operated by ClearCode B.V. (per site footer). No funding disclosed.
  - **Pricing:** free.
  - **Phase:** live.
  - **Added:** Aug 2026 · **Reviewed:** Aug 2026

- **[PolySmartWallet](https://polysmartwallet.com/)**: Real-time leaderboard scoring Polymarket traders by PnL, backtested returns, win rate, and slippage resistance.
  Per-trader profiles and live PnL charts, Polymarket only.
  - **Best for:** a quick no-login leaderboard check, narrower than PredictFolio.
  - **Team:** not publicly listed. Fully anonymous operator.
  - **Pricing:** free.
  - **Phase:** live.
  - **Added:** Aug 2026 · **Reviewed:** Aug 2026

- **[Arkham: Polymarket Profitable Traders](https://arkm.com/tags/polymarket-profitable-trader)**: Arkham Intelligence's tag/filter view of Polymarket wallets with positive all-time PnL (realized plus unrealized).
  Not a ranked leaderboard, a filter for "currently profitable" wallets on Arkham's broader on-chain analytics platform.
  - **Best for:** filtering Polymarket wallets down to the ones that are actually profitable right now.
  - **Team:** part of Arkham Intelligence, founded 2020. Raised $12M+ Series A backed by Peter Thiel and Sam Altman (per DL News, CoinCarp).
  - **Pricing:** free to browse.
  - **Phase:** live.
  - **Added:** Aug 2026 · **Reviewed:** Aug 2026

- **[Conviction Lens](https://convictionlens.com/)**: Reconstructs complete public Polymarket trader histories with realised PnL, drawdown, open positions, and category performance.
  Includes original cohort research. Research and analytics only, does not connect to wallets or execute trades.
  - **Best for:** checking whether headline PnL and win rate actually hold up across a wallet's complete history.
  - **Team:** not publicly listed.
  - **Pricing:** free profiles, additional Pro analytics.
  - **Phase:** live.
  - **Added:** Aug 2026 · **Reviewed:** Aug 2026

- **[OrcaLayer](https://orcalayer.com/)**: Polymarket analytics covering wallet lookup, smart-money leaderboards, whale alerts, and market research, built on its own index of on-chain fills from the Polygon CTF contracts.
  Farmer filter removes airdrop-farmed wallets from rankings, NegRisk correction fixes win rates on multi-outcome markets, plus side-level FIFO PnL, median hold time, category hubs, trader comparison, an ISW-based territory monitor for Ukraine markets, a Telegram signal channel, and a REST API.
  - **Best for:** telling whether a headline 90%+ win rate is real conviction or volume farmed at 95 cents and above.
  - **Team:** solo developer. Scoring methodology and weights published on the site.
  - **Pricing:** free tier, paid plans for API access and alerts.
  - **Phase:** live.
  - **Added:** Aug 2026 · **Reviewed:** Aug 2026

- **[Algomarket](https://www.algomarket.lol/)**: Free cross-venue analytics for Polymarket and Kalshi — whale holdings vs market-implied odds, trader leaderboard, live large fills, market screener, and cross-venue arbitrage scanner. Filter by category (Sports, Politics, Crypto, etc.) on the dashboard and live feed.
  - **Best for:** tracking where sharp wallets are positioned and spotting Poly/Kalshi price gaps on the same events.
  - **Team:** independent builder.
  - **Pricing:** free.
  - **Phase:** live.
  - **Added:** Sep 2026 · **Reviewed:** Sep 2026

- **[0xinsider](https://0xinsider.com)**: Grades Polymarket wallets S-to-F on settled PnL, with live sports/esports boards showing both sides of a game, large trades, open positions, and daily picks. Read-only API available for developers.
  - **Best for:** a quick gut-check on whether a wallet has a real track record before following its position.
  - **Team:** not publicly listed.
  - **Pricing:** free tier (3 followed wallets); Pro $25/week, $99/month, or $899/year.
  - **Phase:** live.
  - **Added:** Sep 2026 · **Reviewed:** Sep 2026

- **[PredictBoox](https://predictboox.com/)**: Syncs positions, trade history, and P&L from Kalshi and Polymarket into one dashboard.
  Trade journaling and tax-ready export included.
  - **Best for:** keeping tax season simple across multiple platforms.
  - **Team:** not publicly listed.
  - **Pricing:** Pro $19.99/mo, Genius $39.99/mo.
  - **Phase:** Beta.
  - **Added:** Aug 2026 · **Reviewed:** Aug 2026
- **[PolyTracer](https://polytracer.app/)**: Polymarket wallet analyzer that replays every wallet fill by fill from raw Polygon chain data.
  Win rate, ROI and P&L are recomputed rather than read off the displayed figures; 2.6M wallets are indexed and ranked by a 0-100 Copy Score, with win rates broken down per category.
  - **Best for:** checking whether a wallet is actually good before copying it.
  - **Team:** not publicly listed.
  - **Pricing:** free to browse wallets, leaderboards and stats; no account needed.
  - **Phase:** live.
  - **Added:** Oct 2026 · **Reviewed:** Oct 2026

- **[sg.tips](https://sg.tips/)**: Sports prediction-market tracker covering Polymarket, Kalshi and SX, with per-match market probabilities and the public positions and track records of accounts that pass a proprietary multi-dimensional screening.
  Also publishes a weekly CC BY 4.0 [dataset](https://github.com/tipsstats/prediction-market-pro-stats) of aggregate stats.
  - **Best for:** seeing which screened public accounts hold positions on an upcoming sports match.
  - **Team:** not publicly listed.
  - **Pricing:** free to browse; optional membership $9.99/mo or $79.99/yr for full positions and history. Dataset is free.
  - **Phase:** live.
  - **Added:** Oct 2026 · **Reviewed:** Oct 2026
- **[TrueHold](https://www.truehold.xyz/track/polymarket)**: Portfolio tracker that reads Polymarket positions and P&L from any wallet address and Kalshi positions through read-only API credentials.
  Prediction-market positions sit in one view with crypto wallets and exchange accounts, and an AI agent answers questions from that portfolio's data.
  - **Best for:** seeing a Polymarket or Kalshi book next to the rest of a crypto portfolio.
  - **Team:** Azat Tulegenov (co-founder).
  - **Pricing:** not publicly listed.
  - **Phase:** beta.
  - **Added:** Oct 2026 · **Reviewed:** Oct 2026

- **[PMWallets](https://pmwallets.com/)**: Polymarket trader leaderboard computed from its own ledger of the Polygon chain, with wallets that trade as one scored as one trader and win rates shown with 95% confidence intervals.
  Profit is also shown without each trader's single best market. Followed traders' fills are pushed over WebSocket or signed webhook for copy trading; REST API and MIT-licensed SDKs for Node.js and Python.
  - **Best for:** checking whether a trader's record holds up at the lower bound of its win-rate interval and without its best market, then following that trader's fills.
  - **Team:** not publicly listed.
  - **Pricing:** free account to browse the whole board; plans $4.99 / $14.99 / $39.99 a month (7-day free trial on the $4.99 plan); fill feed $0.01 per wallet per hour.
  - **Phase:** live.
  - **Added:** Oct 2026 · **Reviewed:** Oct 2026

[↑ Back to top](#top)

---

<a name="alerts--whale-monitoring"></a>

## 🐋 Alerts & Whale Monitoring

- **[PolymarketScan](https://polymarketscan.org/)**: Free real-time Polymarket analytics tracking whale trades and top traders.
  Alerts pushed via its @PolyWhaleAlerts feed.
  - **Best for:** getting whale alerts on Twitter instead of buried in an app.
  - **Team:** not publicly listed. Appears to be an independent or solo project.
  - **Pricing:** free.
  - **Phase:** live.
  - **Added:** Aug 2026 · **Reviewed:** Aug 2026

- **[PolyWatchDog](https://polywatchdog.com/)**: Real-time Polymarket monitoring with a live dashboard and wallet-level trader search.
  Custom smart alerts (browser and Telegram) plus copy-trade notifications.
  - **Best for:** one tool that covers alerts, trader search, and copy-trade pings.
  - **Team:** not publicly listed. Domain registered February 2026, worth independent vetting before connecting a wallet.
  - **Pricing:** not publicly listed.
  - **Phase:** live.
  - **Added:** Aug 2026 · **Reviewed:** Aug 2026

- **[PolyAlertHub](https://polyalerthub.com/)**: Real-time Polymarket monitoring delivering smart-money and whale-flow alerts.
  Fresh-wallet and bot-detection signals, plus a paper-trading terminal.
  - **Best for:** whale alerts scored by conviction and win rate, with copy-trade links.
  - **Team:** not publicly listed. (Self-reported win-rate and ROI stats are marketing claims, not verified performance.)
  - **Pricing:** not publicly listed.
  - **Phase:** live.
  - **Added:** Aug 2026 · **Reviewed:** Aug 2026

- **[yesno.pm](https://yesno.pm/)**: Telegram/Discord/X bot delivering wallet analytics (Sharpe ratio, drawdown, ROI).
  Insider-trade tracking and group leaderboards for Polymarket and Kalshi.
  - **Best for:** tracking trade calls and leaderboards right in your group chat.
  - **Team:** not publicly listed.
  - **Pricing:** not publicly listed.
  - **Phase:** live.
  - **Added:** Aug 2026 · **Reviewed:** Aug 2026

- **[Betmoar](https://www.betmoar.fun/)**: Discord-first trading edge tool: whale and trader tracking, transaction analysis, and a real-time news terminal tagged to markets.
  Describes itself as the official bot provider for Polymarket, with $1B+ in trading volume processed (both self-reported, not independently confirmed).
  - **Best for:** communities that want whale alerts and market news inside Discord instead of a separate app.
  - **Team:** operated by Betmoar Innovation Limited. No further team or funding info disclosed.
  - **Pricing:** not publicly listed.
  - **Phase:** live.
  - **Added:** Aug 2026 · **Reviewed:** Aug 2026

- **[Skewfeed](https://skewfeed.com)**: Prediction-market research dashboard monitoring unusual directional activity across Kalshi and Polymarket.
  Presents recorded price, timing, order-flow and liquidity context behind activity flags. A separate public Polymarket trade table shows completed trades, dollar size, execution time and public wallets.
  - **Best for:** investigating a market move and checking the evidence behind an unusual-activity flag.
  - **Team:** not publicly listed.
  - **Pricing:** free public trade table; full product $69.99/month, with an annual option and a five-day trial advertised on the site.
  - **Phase:** live; the homepage includes representative product previews, while the full dashboard requires subscription access.
  - **Added:** Sep 2026 · **Reviewed:** Sep 2026

- **[PolyInsider](https://polyinsider.io)**: Free real-time dashboard flagging first-time Polymarket wallets (buys over $500) and whale trades (over $5,000, reconciled against on-chain positions), with crypto up/down markets filtered out of the noise.
  - **Best for:** catching fresh-wallet and whale activity without doing manual chain analysis.
  - **Team:** not publicly listed; states it's independent and not affiliated with Polymarket.
  - **Pricing:** free.
  - **Phase:** live.
  - **Added:** Sep 2026 · **Reviewed:** Sep 2026

[↑ Back to top](#top)

---

<a name="research--market-discovery"></a>

## 🧠 Research & Market Discovery

- **[DegenHedge Kalshi Fee and Payout Calculator](https://degenhedge.com/tools/kalshi-fee-calculator/)**: Free browser calculator for Kalshi BTC 15-minute contracts that estimates taker fees, total cost, winning payout, net profit, and break-even probability. Fee estimates depend on the selected multiplier, account balance precision, and fill assumptions; no account or API key is required.
  - **Best for:** checking a BTC 15-minute contract's cost and break-even probability with explicit fee assumptions.
  - **Team:** not publicly listed.
  - **Pricing:** free calculator; DegenHedge also offers separate paid Telegram monitoring.
  - **Phase:** live.
  - **Added:** Oct 2026 · **Reviewed:** Oct 2026

- **[Poly Helper](https://polyhelper.io/)**: Free Chrome/Brave extension embedding 18+ contextual data panels directly into the Polymarket interface.
  Crypto prices, sports scores, macro data, whale tracking, and news, all in-context.
  - **Best for:** researching without leaving the Polymarket tab.
  - **Team:** not publicly listed (a third-party directory attributes it to a small team holding a Polymarket Builders Badge, unconfirmed).
  - **Pricing:** free.
  - **Phase:** live.
  - **Added:** Aug 2026 · **Reviewed:** Aug 2026

- **[METAR.ws](https://metar.ws)**: Real-time WebSocket API streaming aviation weather observations and forecast model data as structured JSON.
  The same underlying data source used to resolve weather-related contracts on Polymarket and Kalshi.
  - **Best for:** checking the real resolution data behind weather markets instead of guessing.
  - **Team:** not publicly listed.
  - **Pricing:** free sandbox tier, paid tiers from €49/mo.
  - **Phase:** live.
  - **Added:** Aug 2026 · **Reviewed:** Aug 2026

- **[Live Tennis API](https://livetennisapi.com)**: Real-time REST and WebSocket API streaming live tennis match state as structured JSON — score, sets/games/points, who's serving, a three-valued break-point flag, and retirement / walkover / completed status.
  The same kind of ground-truth result data used to resolve tennis contracts on Polymarket and Kalshi (a match completing, a retirement, or a walkover is the resolution event). Covers ATP, WTA, and ITF down to the lower tours. An MIT-licensed, observe-only [match↔market matching toolkit](https://github.com/livetennisapi/polymarket-tennis) pairs the feed against Gamma tennis markets, and there's an [MCP server](https://www.npmjs.com/package/livetennisapi-mcp) on the official MCP Registry for agent research.
  - **Best for:** checking the real resolution data behind tennis markets instead of scraping a scoreboard.
  - **Team:** independent; operated by the Live Tennis API team (livetennisapi.com).
  - **Pricing:** free tier (live scores, match state, players, fixtures; 30 req/min, 100/day, no card); paid plans above that.
  - **Phase:** live.
  - **Added:** Aug 2026 · **Reviewed:** Aug 2026

- **[TickFoundry](https://tickfoundry.com/)**: Archived Polymarket order-book data pulled straight off the live socket, not periodic snapshots.
  Every book update, full L1 and 25-level L2 depth on both sides, and trade data continuous since May 11, 2026. Live reference-price feeds and Polymarket's own sports state feed came online June 21, 2026, and a separate onchain fill layer reaches back further and carries wallet identity the socket data never had. One thing worth knowing: the feeds carry no `condition_id`, so joining scores to books is done by time, not by ID.
  - **Best for:** rebuilding exactly what the order book looked like at any past moment.
  - **Team:** built and run solo, self-disclosed rather than anonymous.
  - **Pricing:** free tier claims 5 market-days of your choosing, no card required. Paid tiers above that.
  - **Phase:** live.
  - **Added:** Aug 2026 · **Reviewed:** Aug 2026

- **[PolyOrderbooks](https://polyorderbooks.com)**: Read-only REST API and Python SDK for historical Polymarket crypto markets: discovery, bucketed prices, volume/liquidity/spread metrics, and L2 order book snapshots. Queries run against a hosted archive (not live Polymarket on the read path). Resolution down to 1s on paid plans; [developer docs](https://docs.polyorderbooks.com) and [OpenAPI](https://docs.polyorderbooks.com/openapi.json) are public.
  - **Best for:** backtests and research that need stored L2 depth and market-level time series without operating your own ingestion stack.
  - **Team:** independent product; not affiliated with Polymarket (per site).
  - **Pricing:** Starter free, Pro $19/mo, Scale $49/mo (public [pricing page](https://polyorderbooks.com/pricing)); Enterprise custom.
  - **Phase:** live.
  - **Added:** Aug 2026 · **Reviewed:** Aug 2026

- **[Resolved Markets](https://resolvedmarkets.com)**: Historical Polymarket order book API: full-depth L2 snapshots since March 2026, with trades and settlement results, over REST, WebSocket and a hosted MCP server.
  Captured at about 20 Hz for crypto up/down markets and 2 Hz for sports; also covers weather, economics, social and equities markets, plus Hyperliquid perp books. An MIT-licensed Python backtester, [resolvedkit](https://github.com/resolvedmarkets/resolvedkit), fills strategies against this depth with Polymarket's fee curve.
  - **Best for:** backtesting Polymarket crypto up/down strategies against real book depth instead of mid-prices.
  - **Team:** Elcara LLC-FZ (Dubai), per the site's terms.
  - **Pricing:** free tier (5,000 credits/month, crypto markets, no card); Pro $17/mo, Scale $49/mo, Enterprise $549/mo ([pricing](https://resolvedmarkets.com/pricing)).
  - **Phase:** live.
  - **Added:** Sep 2026 · **Reviewed:** Sep 2026

- **[Kalshi & Polymarket Markets Scraper](https://apify.com/gratified_ashram/prediction-markets-scraper)**: Pay-per-row export of Kalshi and Polymarket markets from their public APIs into JSON, CSV or a scheduled dataset, with order-book depth, price history for both exchanges (Kalshi settled markets and candlesticks back to 2021, Polymarket daily/hourly/minute series back to 2024) and Polymarket comment threads and top holders.
  Runs on Apify, so it also works as an MCP tool for AI agents and on a schedule for building your own archive. No exchange account or API key needed.
  - **Best for:** pulling a clean, filterable table of markets (by series, category, keyword, volume) with history attached, without writing API code.
  - **Team:** independent, self-disclosed (gratified_ashram on Apify).
  - **Pricing:** $1 per 1,000 records, order book +$1 per 1,000; Apify's free plan covers about 4,000 records a month.
  - **Phase:** live.
  - **Added:** Sep 2026 · **Reviewed:** Sep 2026

- **[Kalshi Weather Index](https://apify.com/gratified_ashram/kalshi-weather-index)**: Minute-by-minute temperature index Kalshi publishes for its hourly-temperature cities, as rows, plus NWS/METAR station observations and a settlement-audit row per city-day for the daily high/low markets.
  The number the hourly temperature contracts settle on, exportable and schedulable; a free CC BY 4.0 hourly archive of the index since September 2026 is linked from the page. The daily high/low contracts settle on The Weather Company data, so the audit row is a cross-check, not settlement truth.
  - **Best for:** checking the actual settlement index behind Kalshi hourly temperature markets instead of a forecast site.
  - **Team:** independent, self-disclosed (gratified_ashram on Apify).
  - **Pricing:** $0.05 per 1,000 index points; station rows $0.50 and audit rows $2 per 1,000.
  - **Phase:** live.
  - **Added:** Sep 2026 · **Reviewed:** Sep 2026

- **[PMXT](https://github.com/qoery-com/pmxt)**: Open-source unified API and SDK ("the ccxt for prediction markets") giving one consistent interface across 13+ venues including Polymarket and Kalshi, hosted or self-hosted, with Python/TypeScript SDKs and an MCP integration for agents.
  - **Best for:** developers who want one client instead of integrating each venue's API separately.
  - **Team:** maintained by the pmxt-dev org; no individual credited.
  - **Pricing:** free, open-source (MIT); hosted option needs an API key and wallet address for reads.
  - **Phase:** live, actively maintained.
  - **Added:** Sep 2026 · **Reviewed:** Sep 2026

- **[pykalshi](https://github.com/ArshKA/kalshi-client)**: Unofficial Python client for Kalshi with REST and WebSocket streaming, automatic retries, pandas integration, and typed domain objects for markets, orders, and events.
  - **Best for:** developers building research or trading systems against Kalshi's API in Python.
  - **Team:** community-maintained by GitHub user arshka; explicitly not affiliated with Kalshi.
  - **Pricing:** free, open-source.
  - **Phase:** live, actively maintained.
  - **Added:** Sep 2026 · **Reviewed:** Sep 2026

- **[Probalytics](https://probalytics.io)**: Full-depth historical order-book data for Polymarket (since Nov 2025) and Kalshi (since May 2026), queryable via ClickHouse SQL, REST APIs, or Parquet export, with markets covered back to October 2020.
  - **Best for:** quant research that needs raw historical order-book and trade data rather than a dashboard.
  - **Team:** not publicly listed.
  - **Pricing:** paid, free 3-day trial.
  - **Phase:** live.
  - **Added:** Sep 2026 · **Reviewed:** Sep 2026

- **[The Rumpus](https://therumpus.ai)**: Free daily edition that matches live Polymarket and Kalshi markets against several news sources and explains what the prices mean.
  Each morning it publishes dated, sourced stories, a market-wide analysis and a two-host podcast, Rumpus Daily.
  Content is AI-generated: Claude writes the stories, analysis and podcast script, DeepSeek writes shorter front-page copy, story illustrations are AI-generated, and the podcast uses synthetic voices.
  - **Best for:** reading the day's news through the markets that price it.
  - **Team:** Matt O'Neill (Teemo Ltd), independent.
  - **Pricing:** free.
  - **Phase:** live.
  - **Added:** Sep 2026 · **Reviewed:** Sep 2026

- **[outcometick](https://outcometick.com)**: Historical tick data for the crypto Up/Down markets on Polymarket and Predict.fun, sold by API: the Chainlink streams they settle on, order books, Polymarket trade prints and each market's strike and outcome, archived since June 2026.
  A hosted sandbox replays Python or Node.js strategies against the same archive, and the strategy SDK and `ot` CLI are MIT-licensed on npm and PyPI.
  - **Best for:** backtesting Polymarket and Predict.fun crypto Up/Down strategies and recomputing settlements from the Chainlink feed.
  - **Team:** not publicly listed.
  - **Pricing:** $10/mo per venue ($18 for both) for the newest 30 days; one-time date ranges from $0.40/day; backtest credits from $2; one free sample day per venue ([pricing](https://outcometick.com/#pricing)).
  - **Phase:** live.
  - **Added:** Oct 2026 · **Reviewed:** Oct 2026

- **[Glypse](https://glypse.ai/)**: Market screener and event research for prediction markets, with briefings, social sentiment analysis, and a custom-pair arbitrage scanner. Free to use without an account.
  - **Best for:** researching the events and social sentiment behind prediction market prices.
  - **Team:** Glypse, Inc., founded by Doruk Senkal.
  - **Pricing:** free tools and research without an account; a free account adds expanded market results, longer post feeds, and saved social queries.
  - **Phase:** live.
  - **Added:** Oct 2026 · **Reviewed:** Oct 2026

[↑ Back to top](#top)

---

<a name="no-longer-maintained"></a>

## ☠️ No Longer Maintained

- **[Poly Prediction](https://polyprediction.app/)**: Surfaced trending Polymarket markets with live odds, volume, and AI-generated analysis tied to the news driving each market.
  Site appears inactive as of August 2026 (left here for reference, not as a live recommendation).
  - **Team:** fully anonymous, never disclosed.
  - **Added:** Aug 2026 · **Removed:** Aug 2026 (site inactive).

[↑ Back to top](#top)

---

Missing a tool, or something here is out of date? This list is maintained by [Predictbook](https://predictbook.co). Reach out and we'll add or fix it.
