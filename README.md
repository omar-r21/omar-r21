### Omar Rayan

Quantitative analyst in index operations, Chicago. Day to day that's index and iNAV production, option
pricing, backtests, and the QA and reconciliation automation around them. Before this, market data at
Citadel, and before that I ran an e-commerce business to $40k/month.

Python, SQL, R, some TypeScript. Interested in index methodology, volatility, market risk, and the data
engineering underneath all of it.

---

### Projects

**[volsurf](https://github.com/omar-r21/volsurf)** — option pricing and SVI volatility surfaces in
Python. Takes an option chain and returns a surface you can query: forwards from put-call parity, a
bracketed implied-vol solver, an SVI fit per expiry, arbitrage checks. Fits a live SPY chain to 8–40 bp
of vol across eight expiries with no arbitrage in the quoted range.

**[property-comper case study](https://github.com/omar-r21/property-comper-case-study)** — an
after-repair-value model for Cook County, backtested against 728 real flips. The interesting part is
where it breaks: 16% median error on normal properties, 200%+ in cheap mixed neighbourhoods, and my
first cut of the data pointed at the wrong cause.

**[riskkit](https://github.com/omar-r21/riskkit)** — VaR and expected-shortfall model validation.
Four methods compared over 4,711 out-of-sample days and scored with Kupiec, Christoffersen and the Basel
traffic light. On a ten-ETF portfolio, filtered historical simulation is the only one whose breach count
and expected shortfall both hold up; the parametric normal model breaches twice as often as advertised
and understates its own tail by a third.
[See the report](https://omar-r21.github.io/riskkit/).

**[portfolio-intelligence case study](https://github.com/omar-r21/portfolio-intelligence-case-study)**
— a private dashboard and nightly digest for my own account. Three bugs worth recording, what it
actually costs to run (about three cents a month), and why the AI recommendation feature is being
replaced by riskkit.

---

[LinkedIn](https://www.linkedin.com/in/omar-raya/)
