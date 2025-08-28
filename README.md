# Artificial Intelligence Decision Making - S&P100 Tracking and Modelling
This project consisted of multiple difference machine learning approaches (using CVXPY and AMPL) with the goal of following the S&P100 as closely as possible while only using 70 stocks with even distribution. CVXPY is a Python-embedded modeling language for convex optimization, while AMPL is an algebraic modeling language for large-scale mathematical optimization.
Our linear optimisation tool matched the S&P100 to within 0.15% from the period of Jan 2024 to Jan 2025

We imported live stock performance data from yahoo finance's yfinance python library and completed all training on a 4060ti GPU and a Ryzen 9 5900XT CPU.

S&P 100 Link (yfinance)
https://finance.yahoo.com/quote/%5ESP100

A Hugh Plunkett and Natalia Ellen Nicholas production
