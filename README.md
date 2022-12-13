# USD/CLP Exchange Rate Forecasting

In this repository, we develop a model to forecast the USD/CLP exchange rate under a MA(1)-eGARCH(1, 1) t-student distributed model. Also, we compute the Value-at-Risk of Chile based on the volatility of this indicator.

In regards of the model, we also create a multivariate model based on the well-known relationship between the value of the copper and the USD/CLP exchange rate under study.

This project introduces the reader into several financial statistics concepts and shows how to perform them in code with real data obtained from [Yahoo Finance](https://finance.yahoo.com/?guccounter=1&guce_referrer=aHR0cHM6Ly93d3cuZ29vZ2xlLmNvbS8&guce_referrer_sig=AQAAAEh7mz7OKyVup9Bpl6RYLSkRQqOEoP0zI0znY-ZpuYdFztxgpuw24QINiysbVHhtBH1-hWq2AE6ghh3bjHU5fbq3rk9dS-3fYfmlocIpzDEynp6TD6Yy0ah5ssxn5jt4-YY9dGrBmj8WuMwyLmJ_5EDtusXgPJp-lTN2gMLH147E) data.

The copper time-series can be found [here](http://boletin.cochilco.cl/estadisticas/grafico.asp?tipo_metal=1), while the official USD/CLP exchange rate can be found [here](https://si3.bcentral.cl/indicadoressiete/secure/Serie.aspx?gcode=PRE_TCO&param=RABmAFYAWQB3AGYAaQBuAEkALQAzADUAbgBNAGgAaAAkADUAVwBQAC4AbQBYADAARwBOAGUAYwBjACMAQQBaAHAARgBhAGcAUABTAGUAdwA1ADQAMQA0AE0AawBLAF8AdQBDACQASABzAG0AXwA2AHQAawBvAFcAZwBKAEwAegBzAF8AbgBMAHIAYgBDAC4ARQA3AFUAVwB4AFIAWQBhAEEAOABkAHkAZwAxAEEARAA%3d).
