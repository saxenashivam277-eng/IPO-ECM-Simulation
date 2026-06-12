# IPO-ECM-Simulation
Reddit IPO / ECM Simulation: Offer Pricing, Valuation, Bookbuilding &amp; Aftermarket Performance

# Reddit IPO / ECM Simulation: Offer Pricing, Bookbuilding & Investor Return Analysis

## Project Overview

This project simulates an Equity Capital Markets advisory analysis for Reddit Inc.’s 2024 IPO. The objective is to evaluate whether Reddit’s IPO was fairly priced, underpriced to create investor demand, or expensive relative to its fundamentals and peer group.

The project uses Python to analyse Reddit’s IPO offer price, first-day return, money left on the table, peer valuation multiples, bookbuilding demand, investor allocation, aftermarket performance, and post-IPO risk.

The study is designed from the perspective of an ECM analyst advising on IPO pricing, investor demand, allocation strategy, and final investment recommendation.

---

## Study Problem

Reddit went public at an IPO offer price of $34 per share. The stock closed its first trading day at $50.44, creating a strong first-day IPO return.

This raises a key ECM question:

**Was Reddit’s IPO priced fairly, or did the company underprice the deal to generate strong investor demand and positive aftermarket performance?**

---

## Key Questions Answered

1. Was Reddit’s IPO offer price justified by fundamentals?
2. How much first-day return did IPO allocation investors earn?
3. Did Reddit leave money on the table by pricing the IPO too low?
4. How did Reddit’s valuation compare with listed peers?
5. What fair IPO price range is implied under bear, base and bull scenarios?
6. How does oversubscription affect IPO allocation?
7. Did Reddit continue to outperform after the IPO?
8. Was Reddit’s post-IPO return worth the volatility and drawdown risk?

---

## Data Used

The project uses IPO pricing assumptions, company financials, peer market data, and Yahoo Finance price data.

### IPO Data

* IPO offer price
* First-day open price
* First-day closing price
* Shares offered
* Gross IPO proceeds
* First-day return
* Money left on the table

### Financial Data

* Revenue
* Adjusted EBITDA
* Net loss
* Cash balance
* Enterprise value
* Equity value

### Peer Group

The peer group includes major internet, advertising, social media and digital platform companies:

* Meta Platforms
* Snap
* Pinterest
* Alphabet
* Spotify
* SPY as market benchmark

---

## Methodology

### 1. IPO Return Analysis

The project first calculates Reddit’s first-day IPO return using the IPO offer price and first-day closing price.

It then compares two investor entry points:

* IPO allocation investor buying at $34
* Public-market investor buying after the first-day close at $50.44

This shows the advantage created by IPO allocation access.

---

### 2. Peer Valuation Comparison

Reddit’s IPO valuation is compared against listed peers using:

* EV / Revenue
* EV / EBITDA
* Profit margin
* Market capitalisation
* Enterprise value

This section evaluates whether Reddit was priced at a discount or premium relative to comparable digital platform companies.

---

### 3. IPO Pricing Sensitivity

A bear, base and bull case valuation range is built using EV / Revenue multiples.

The model estimates:

* Implied enterprise value
* Implied equity value
* Implied share price
* Premium or discount to the IPO offer price

This creates an investment banking-style IPO pricing range.

---

### 4. Money Left on the Table Analysis

The project calculates how much additional capital Reddit could have raised if the IPO had been priced closer to its first-day closing price.

Formula used:

Money Left on the Table = Shares Offered × First-Day Price Increase

Based on 22 million shares offered, the analysis estimates that Reddit left approximately $362 million on the table.

This indicates meaningful IPO underpricing from the issuer’s perspective.

---

### 5. Bookbuilding Simulation

A simulated investor demand curve is created across different IPO offer prices.

The model shows how investor demand changes as the offer price increases.

This section demonstrates the classic ECM trade-off:

* Lower IPO price creates stronger demand
* Higher IPO price increases issuer proceeds
* Final pricing balances demand, execution risk and aftermarket performance

---

### 6. Investor Allocation Simulation

The project simulates allocation across different investor types, including:

* Long-only funds
* Hedge funds
* Sovereign wealth funds
* Mutual funds
* Retail allocation
* Private wealth
* Index funds

Because the simulated IPO is oversubscribed, investors receive only a portion of their requested shares. The model then calculates each investor’s first-day profit based on the IPO price and first-day closing price.

---

### 7. Aftermarket Performance Analysis

Reddit’s post-IPO stock performance is compared against peers and SPY.

The model normalises all prices to 100 from Reddit’s IPO date and tracks relative performance over time.

This helps determine whether Reddit’s IPO success was limited to the first-day pop or continued into the aftermarket period.

---

### 8. Risk Analysis

The project evaluates Reddit’s post-IPO risk using:

* Daily returns
* Annualised volatility
* Maximum drawdown
* Sharpe ratio
* Risk-return scatter plot
* Drawdown comparison against peers

This section shows that Reddit behaved like a high-beta growth stock, offering strong upside but also meaningful downside risk.

---

## Key Findings

### 1. Reddit’s IPO was attractive for allocated IPO investors

Investors who received shares at the $34 IPO offer price benefited from a strong first-day return. The IPO allocation entry price created a clear advantage compared with buying after the stock had already listed.

### 2. Reddit likely left money on the table

The stock’s large first-day pop suggests that the IPO was meaningfully underpriced. Based on 22 million shares sold, Reddit left approximately $362 million on the table by not pricing closer to the first-day closing price.

### 3. The IPO was successful from an ECM execution perspective

The deal priced at the top of the range, generated strong demand, and delivered positive aftermarket performance. This supports the view that the IPO was well executed by underwriters.

### 4. The issuer and investor perspectives differ

From Reddit’s perspective, the IPO was successful but underpriced. From the investor’s perspective, the underpricing created attractive immediate gains for allocated IPO investors.

### 5. Public-market buyers faced higher risk

Investors who bought after the first-day pop entered at a much higher valuation. The drawdown analysis shows that Reddit experienced meaningful volatility after listing, making it a higher-risk growth investment.

---

## Final Recommendation

Reddit’s IPO should be viewed as a strong ECM transaction. The deal successfully generated investor demand, priced at the top of the range, and produced strong first-day trading performance.

However, the large first-day return also indicates that the IPO was underpriced. This benefited IPO allocation investors but reduced the amount of capital Reddit could have raised.

For allocated IPO investors, Reddit was highly attractive. For public-market buyers after listing, the investment case was more cautious because the IPO discount had already disappeared and the stock carried higher volatility and drawdown risk.

Overall, the project concludes that Reddit’s IPO was successful for ECM execution and IPO investors, but less optimal for the issuer from a proceeds-maximisation perspective.

---

## Tools & Libraries

* Python
* Pandas
* NumPy
* Yahoo Finance
* Matplotlib
* Jupyter Notebook / Google Colab

---

## Project Outputs

The project produces:

* IPO return analysis table
* Peer valuation comparison
* EV / Revenue and EV / EBITDA charts
* Bear, base and bull IPO pricing sensitivity
* Gross proceeds vs money-left-on-the-table chart
* Bookbuilding demand curve
* Investor allocation simulation
* Investor first-day profit analysis
* Aftermarket performance chart
* Risk-return scatter plot
* Drawdown analysis chart
* Final IPO recommendation scorecard

---

## Skills Demonstrated

* Equity Capital Markets analysis
* IPO pricing and valuation
* Comparable company analysis
* Investor demand simulation
* Bookbuilding logic
* Allocation modelling
* Aftermarket performance analysis
* Risk-adjusted return analysis
* Python financial modelling
* Investment banking-style recommendation writing

---

## Conclusion

This project demonstrates how IPO pricing can be analysed from both issuer and investor perspectives. Reddit’s IPO created strong investor returns and positive market momentum, but the first-day pop suggests the company accepted underpricing to reduce execution risk and support aftermarket performance.

The study highlights the core ECM trade-off between maximising issuer proceeds and ensuring strong investor demand.
