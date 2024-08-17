Options Pricing and Risk Analysis using Binomial, Trinomial Trees, and Monte Carlo Simulation
This project focuses on validating and pricing vanilla European and American options using various quantitative methods, ensuring compliance with key financial principles such as put-call parity, and computing essential risk metrics. The integration of multiple techniques enhances pricing accuracy and provides a comprehensive assessment of risk exposure through the computation of key Greeks.

Overview
Options Pricing Models:
Binomial and Trinomial Trees: Utilized binomial and trinomial tree models to price vanilla European and American options. These lattice-based methods allow for flexible and accurate pricing of options by modeling possible future stock prices at each node. The models ensure put-call parity, a critical arbitrage-free condition in options pricing.
Put-Call Parity Validation: The project validates the pricing of European options by confirming the adherence to put-call parity, preventing arbitrage opportunities. This is an essential step in ensuring that the pricing model reflects market realities.
American Options Pricing: American options, which allow for early exercise, were priced using binomial and trinomial trees, verifying that their values exceed those of European options due to the added flexibility of early exercise.
Risk Assessment via Greeks:

The project computes key Greeks, including Delta, Gamma, Theta, Vega, and Rho, to assess risk exposure for both European and American options. These sensitivities help in understanding how option prices react to changes in underlying factors such as asset prices, volatility, and time decay.

Monte Carlo Simulation:
Applied Monte Carlo simulation to accurately price European call options. This method uses random sampling to simulate a wide range of possible outcomes, leading to precise valuation, especially for complex derivatives where closed-form solutions may not exist.
Technologies and Concepts
Binomial and Trinomial Trees for lattice-based option pricing.
Monte Carlo Simulation for advanced European option valuation.
Put-Call Parity Validation to ensure arbitrage-free pricing.
Greeks Calculation for risk management and sensitivity analysis.
Python, NumPy, SciPy for numerical computations and modeling.
This project showcases the application of different quantitative models in options pricing and risk assessment, with a focus on accuracy, compliance, and risk management.
