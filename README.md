# enso-forcasting

Traditional numerical simulations build upon human expertise in defining events based on subjective thresholds of relevant physical variables. Often, multiple competing methods produce vastly different results on the same dataset. This work explores using deep learning to improve the forecast accuracy of El Niño–Southern Oscillation (ENSO) based on time series data such as sea level pressure, ocean wind, and sea surface temperature.

Specifically, the code here includes a few modules: 
* Exploratory data analysis via Fast Fourier Transformation, Wavelet analysis, and autocorrelation
* Correlation analysis between SOI and other climate variables (e.g. precipitation, PNA, ONI, Nino 3) at different lags
* Compared the results of RNN/LSTM, multiple output linear regression, and random forest

A report about this work can be found at: https://medium.com/@j.yongyao11/prediction-el-ni%C3%B1o-southern-oscillation-through-lstm-729c21a63561

