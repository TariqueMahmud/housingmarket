# housingmarket

A work on the vancouver housing market and relation of the price. This research has been done considering a 10 years of housing price data to detect the breakpoint of the price and volatility. Also predicted the volatility for a year.

PSUDO code for the work:

#GARCH model approach
1.Checking the stationary 
  (H0 = Series is non stationary
   Ha = Series is stationary)
2.To check volatility clustering.
3.To check ARCH effect.
  (H0 = There is no ARCH effect
   Ha = There is an ARCH effect)
4.Write GARCH model
5.GARCH specification output
6.Plot
7.Volatility forecasting

=================

#Assymetric GARCH
1. Volatility clustering (beta)
2. ARCH effect (alpha)
3. Leverage effect (gamma)


================

#Structural breakpoints (SBP) detection

1. package strucchange
2. Plot time series values
3. Create a model
H0= No Structural breakpoint if p is greater than 0.05
4.Find SBP
5. SBP test
