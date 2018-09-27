# options-screener

# Hypothesis

<b>Assumption 1:</b>

Normal market activity for future periods.

<b>Assumption 2:</b>

If a stock has exhibited a steady growth rate over the last several periods (quarters, years, seasons, etc.), then given assumption 1, we can accurately forecast the stock's price in future periods given the histrocal growth rate exhibited over previous periods.

<b>Assumption 3:</b>

An option contract’s strike and premium together at a specific expiration are an indicator of the market’s expectation of the stock’s price at that time.

<b>Hypothesis:</b>

Given the assumptions, if the forecasted price exceeds the market's expected price, a mispricing exists.

The option contracts with the greatest mispricing are thus the most undervalued options.

# Tasks

Assumption 1:

- [ ] Get sector data
- [ ] Analyze news headlines

Assumption 2:

- [x] <a href="https://github.com/santarini/historical-price-statistics">Get historical stock data</a>
- [ ] Get monthly data
- [ ] Get historical earnings release dates
- [ ] <a href="https://github.com/santarini/montecarlo">Monte Carlo forecast</a>
- [ ] Organize monthly data into seasonal data

Assumption 3:

- [ ] Get option prices
- [ ] Create option valuation model
