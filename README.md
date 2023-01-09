# Forecasting Daily Temperature using Holt Winters Seasonal Methods 

## Why is this relevant?
Being able to forecast temperatures is a useful skill to have, given its utility in in everyday life- from planning a trip to organizational level use cases such as planning
flight scheduling based on the weather. Although this use case focuses on forecasting weather, the same principle applies for other forecasting problems which present 
repetitive patterns over time.

## About this implementation
I have attempted to solve this problem using the HoltWinters exponential smoothing technique- which is a third degree exponential smoothing technique.
We can choose to give a higher weightage to the most recent values in this tehnique, which differntiates it from other forecasting techniques like ARIMA and SARIMA.
The Holt-Winters seasonal method comprises the forecast equation and three smoothing equations — one for the level ℓt, one for the trend bt, and one for the seasonal 
component st, with corresponding smoothing parameters α, β∗ and γ. We use m to denote the frequency of the seasonality, i.e., the number of seasons in a year.
