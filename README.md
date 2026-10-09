### Omar Rayan

Quant analyst in index operations in Chicago. Most of my day is index and iNAV production, option
pricing, backtests, and the QA and reconciliation tooling around them. Before that I was in market data
at Citadel, and before that I ran an e-commerce business that got to $40k a month.

I mostly write Python, SQL and R, plus some TypeScript. I'm interested in index methodology, volatility,
market risk, and the data engineering those depend on.

---

### Projects

**[volsurf](https://github.com/omar-r21/volsurf)**: option pricing and SVI vol surfaces in Python. You
give it an option chain and get back a surface you can query. Forwards come from put-call parity, vols
from a bracketed Newton solver, then an SVI fit per expiry and arbitrage checks on the result. On a live
SPY chain it fits eight expiries to within 8 to 41 bp of vol, with no arbitrage in the quoted range.

**[riskkit](https://github.com/omar-r21/riskkit)**: VaR and expected shortfall model validation. It runs
four methods over 4,711 out-of-sample days and scores them with Kupiec, Christoffersen and the Basel
traffic light. On a ten-ETF portfolio, filtered historical simulation was the only one where both the
breach count and the ES held up. The normal model breached twice as often as it should have and
understated its own tail by about a third. [The report is here](https://omar-r21.github.io/riskkit/).
I also run it every weeknight on my own account, through the private app below.

**[property-comper case study](https://github.com/omar-r21/property-comper-case-study)**: an
after-repair value model for Cook County, backtested against 728 real flips. It's 16% median error on
normal properties and over 200% in cheap mixed neighbourhoods, and my first read of the data blamed the
wrong thing.

**[portfolio-intelligence case study](https://github.com/omar-r21/portfolio-intelligence-case-study)**:
a private dashboard and nightly email for my own brokerage account. Covers the bug that kept the email
silently broken for months, what it costs to run (about three cents a month), and why I pulled the AI trade
recommendations and put riskkit in their place.

---

[LinkedIn](https://www.linkedin.com/in/omar-raya/)
