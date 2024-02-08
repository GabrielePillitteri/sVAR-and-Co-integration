# sVAR-and-Co-integration
During a week-long intensive project for the "Econometrics of Financial Markets" course at university, I delved into the application of various advanced econometric models to analyze almost random simulated financial market data. I exclusively relied on **Gretl** throughout the project for its simplicity and speed. Nevertheless, I supplemented my analysis with **Python** code as well.
## Goal of the project
### Assessing the Dynamic Impact of Oil Price Shocks on Macroeconomic Variables
Through the implementation of a structural VAR (Vector Autoregression) model, the project aims to evaluate the dynamic effects of oil price shocks on key macroeconomic indicators within a "small open economy." By examining a vector of variables encompassing oil price (in domestic currency), inflation rate, and GDP growth rate, the study seeks to specify and estimate a VAR model. Further analysis involves discussing the propagation mechanism of oil price shocks via the calculation of structural impulse response functions. Additionally, the project entails selecting one variable from the vector and estimating an appropriate ARMA (Autoregressive Moving Average) model for that variable, thereby facilitating a comparative assessment with the corresponding equation in the VAR model.

### Testing the Purchasing Power Parity (PPP) Hypothesis
The project aims to investigate the validity of the Purchasing Power Parity (PPP) hypothesis, which asserts that national price levels should equalize once converted to a common currency. From a theoretical standpoint, the PPP relation is expressed through a mathematical equation involving price indices and nominal exchange rates. Empirically, the project involves verifying the nonstationarity of the series and conducting cointegration tests to confirm the PPP hypothesis. Moreover, through an error correction model, the project seeks to examine the reaction of the three variables to potential disequilibria arising from a "possible" cointegrating relation, thereby shedding light on the dynamic interplay between these variables in the context of PPP.

## Models Utilized
### First Part
- ARMA (Autoregressive Moving Average): This analytical framework was utilized to deepen comprehension of time series dynamics and to forecast future data points, in this case of Oil prices, providing valuable insights into the underlying patterns and trends within the dataset.
- sVAR (Structural Vector Autoregression): This model was employed to uncover the underlying structural relationships and interdependencies among multiple time series variables, in this case Oil, Inflation and GDP Growth, using the Cholewski Decomposition to compute the Impulse Response Function (IRF)
### Second Part
- Cointegration Analysis: The objective of employing cointegration analysis was to investigate the validity of the Purchasing Power Parity (PPP) hypothesis, which     posits that when converted into a common currency, national price levels should ultimately equalize.
- VECM (Vector Error Correction Model): his model was harnessed to delve into the enduring connections among deeply intertwined time series, offering insights into their long-term relationships within the financial domain.

## Project Report:
The comprehensive analysis and findings of this endeavor are compiled in the "Report.pdf". This report provides detailed insights into the methodologies, analyses, and conclusions derived from the study. If you want to access and view the code, feel free to ask.

