# Options-Pricing

This repository contains Python scripts and Jupyter notebooks that I have created for different methods of options pricing, for both vanilla and exotic options.

Below will contain brief descriptions of each file, within each contains a more detailed description, specifically about the types of options and the methods used to price them:

Monte_Carlo_Option_Pricing.ipynb - Prices Asian and Barrier options using Geometric Brownian Motion to simulate paths of the underlying asset's price, and then uses Monte Carlo simulation to determine a price for an Asian option and Barrier option based on properties such as strike price, barrier price, "call" or "put", or if the option is "up-and-out" or "down-and-out".
