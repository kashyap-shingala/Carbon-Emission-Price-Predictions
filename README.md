##### **Carbon Emission Price Prediction**



**This project focuses on  forecasting carbon emission prices  using both traditional and deep learning models, including  probabilistic forecasting techniques . The objective is to build  accurate and uncertainty-aware  models to anticipate market trends in carbon pricing.**



###### **Overview**



**Carbon markets play a key role in environmental sustainability and policy enforcement. This project explores a range of models to forecast carbon emission prices with a focus on:**

**-  Predictive accuracy** 

**-  Uncertainty quantification** 

**-  Model reliability** 



###### **Key Techniques \& Models**



**| Model                  | PICP (%) | MPIW     |**

**|------------------------|----------|----------|**

**|  RNN + Quantile      | 96.72    | 10.05    |**

**|  RNN (Quantile)      | 95.05    | 9.95     |**

**|  LSTM + Quantile     | 97.81    | 9.93     |**

**|  GRU + Quantile      | 95.05    | 9.08     |**

**|  TCN + Quantile      | 96.15    | 9.61     |**



**| Hybrid Model           | R² Score |**

**|------------------------|----------|**

**|  CNN + GRU           | 0.85     |**

**|  CNN + LSTM          | 0.85     |**

**|  RNN + CNN           | 0.87     |**



**>  PICP (Prediction Interval Coverage Probability):  Measures how well the model captures the true values in prediction intervals.**  

**>  MPIW (Mean Prediction Interval Width):  Indicates the width of the uncertainty band — lower is better.**



######  **Features**

**- Forecasting weekly carbon emission prices**

**- Probabilistic deep learning (Mixture Density Networks + Quantile loss)**

**- Evaluation using  PICP ,  MPIW , and  R² score** 

**- Comparison across RNN, LSTM, GRU, TCN, and CNN-based hybrids**



######  **Files**

**- `Carbon\_price\_forcasting.ipynb` — Main notebook with all models and results**

**- `README.md` — You’re reading it!**

