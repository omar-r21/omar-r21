### Omar Rayan

Quantitative Analyst in index operations, Chicago. I build tools that turn messy financial and market data into numbers people can trust: index and iNAV production, option pricing, backtesting, and the QA/reconciliation automation around them.

Previously market data at Citadel; before that, founded and ran an e-commerce business to $40k/month.

**Working in:** Python (pandas, NumPy, SciPy) · SQL · R · TypeScript · Git

**Interested in:** index methodology · derivatives pricing & volatility · market risk · financial data engineering

---

### Projects

**[volsurf](https://github.com/omar-r21/volsurf)** — option pricing, implied volatility and arbitrage-checked SVI volatility surfaces
Takes a raw option chain and returns a smooth surface you can query: forwards from put-call parity, a
safeguarded implied-vol solver, an SVI fit per expiry, and butterfly/calendar arbitrage checks. Fits a
live SPY chain to 8–40 basis points of vol across eight expiries, with no static arbitrage in the quoted
range. Python, 43 tests, CI.

**riskkit** *(in progress)* — value-at-risk and expected-shortfall **model validation**
Four VaR/ES methods compared over ~4,000 out-of-sample days and scored with the tests that decide
whether a risk model actually works: Kupiec, Christoffersen, and the Basel traffic light. Early result
on a ten-ETF portfolio: filtered historical simulation is the only one whose breach count and expected
shortfall both hold up, while the parametric normal model breaches twice as often as advertised and
understates its own tail by a third.

---

[LinkedIn](https://www.linkedin.com/in/omar-raya/)
