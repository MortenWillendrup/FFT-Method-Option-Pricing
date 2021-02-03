# FFT-Method-Option-Pricing
This is the Python implementation of European Option Pricing using Fast Fourier Transformation (FFT) method.

In this framework, we focus on the Fourier pricing methods applied to the Black–Scholes–Merton (BSM) (1973) and Heston (1993) model (H93). To provide more insight into the differences in pricing performance, we expand the work by calibrating Heston model to Ericsson call option benchmark prices. The calibration work involves an extra step of computing the short interest rates for different time to maturity option classes using the Vasicek model.

Input:
Benchmark of 130 call options, written on Ericsson stock. Each option data, stored in file Ericsson.csv, has the following information: Maturity Date, Strike Price (K), Call Option Price, Time to Maturity (T). The initial Ericsson stock price is $S_0 = 98.36$ and dividend yield rate d= 0.0086.

Output:
Calibrated Heston parameters, including: kappa, theta, sigma, rho, initial volatility of volatility.

Simple examples to demonstrate option pricing method with different model via FT-Lewis and FT-discrete (Fast Fourier Transform)  are in the "Fourier Pricing Examples.ipynb".
