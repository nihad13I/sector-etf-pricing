# Sector ETF Option Valuation
## Binomial Pricing of XLE, XLF, and XLY Call Options

### Overview
This project applies a high-resolution (1,000-step) Binomial Tree model to price European Call options for major sector ETFs. The model incorporates real-world parameters, including spot prices, strike prices, implied volatilities, and continuous dividend yields.

### Key Features
* **Real Market Data:** Valuation for XLE (Energy), XLF (Financials), and XLY (Consumer Discretionary).
* **Dividend Yield Integration:** Adjusts the risk-neutral probabilities to account for the impact of dividends on option premiums.
* **Convergence Accuracy:** Utilizes a 1,000-step lattice to minimize approximation error and ensure robust pricing.

### Technical Stack
* **Python** (NumPy, SciPy)
* **Quantitative Methods:** Binomial Lattice Models, Risk-Neutral Valuation.
