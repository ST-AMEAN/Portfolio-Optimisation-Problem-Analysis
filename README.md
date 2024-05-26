# Portfolio-Optimisation-Problem-Analysis
## Overview

This project aims to optimise an investment portfolio with an initial £20,000, incorporating stock ABC, European call options, and zero-coupon bonds. The goal is to maximise expected profit while ensuring a minimum profit of £2,000 across three scenarios for the stock price in six months.

## Problem Description

**An investor can:**
- Buy stock ABC at £20 per share.
- Purchase European call options at £1,000 each (for 100 shares) with a strike price of £15.
- Invest in zero-coupon bonds priced at £90 with a £100 face value.
- The number of call options to buy or sell is capped at 50.
**Scenarios (Equally Likely):**
- Stock price remains at £20.
- Stock price increases to £40.
- Stock price drops to £12.
**Objectives**
- Maximise expected profit.
- Ensure a minimum profit of £2,000 in all scenarios.

## Conclusion / Key Insights

Using Excel Solver, VBA, and Python's PuLP, we found the following key insights from the initial problem and further analysis:

**Investment Strategy:**
- The investor allocates £18,000 in zero-coupon bonds and £2,000 in European call options, avoiding purchasing any shares of stock ABC.
- This allocation maximises expected profit while ensuring a minimum profit of £2,000 in each scenario.

**Risk Management:**
- Buying 2 call options and avoiding selling options reduces potential losses if the stock price falls.
- Investing heavily in zero-coupon bonds ensures a stable return, reducing overall portfolio risk.

**Profit Stability:**
- The strategy ensures profits across all three scenarios, with profits ranging from £2,000 to £7,000.
- The expected profit of £4,000 is achieved by equally weighting the possible outcomes.

**Role of Zero-Coupon Bonds:**
- Zero-coupon bonds provide stable returns unaffected by stock price changes.
- Significant investment in zero-coupon bonds is crucial to meet the minimum profit requirement under all conditions.

**Optimal Allocation:**
- A mix of stocks, call options, and bonds, with a notable emphasis on bonds as the initial investment increases, is optimal.
- Stocks and call options are crucial up to a critical investment point (£68,000), beyond which bonds dominate the strategy.

**Diminishing Returns:**
- Beyond the £68,000 investment, additional investments yield lower incremental returns, highlighting the need for a balance between risk and return.

**Balanced Strategy:**
- Consistent allocation towards call options and gradual increase in shares suggest a balanced and diversified investment approach, optimizing both risk and return.

**Efficiency of Investments:**
- The ROI analysis indicates that the investment strategy is most efficient up to the £68,000 mark. Beyond this point, additional investments result in diminishing efficiency.

By understanding these trends, investors can tailor their strategies based on available capital and desired outcomes, ensuring optimised and informed investment decision-making. This comprehensive analysis demonstrates that strategic investment in call options and zero-coupon bonds can significantly enhance returns while effectively managing risk.
