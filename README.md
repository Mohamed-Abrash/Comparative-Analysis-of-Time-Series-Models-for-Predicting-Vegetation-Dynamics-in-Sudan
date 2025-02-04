# Comparative Analysis of Time Series Models for Predicting Vegetation Dynamics in Sudan

<img src="https://github.com/user-attachments/assets/46a3d6c4-4d56-4d35-b8c5-c696c99eb69b" alt="Adaptic model" width="1000" />

This project investigates the application of time series models for analyzing vegetation index data from El-Geneina and Kassala, Sudan. The research is motivated by the need to understand and predict vegetation patterns, which are crucial for various applications, such as agriculture, environmental monitoring, and resource management.  

The aim of the project is to compare the performance of different time series models in capturing and predicting vegetation dynamics.  The models considered include:  

- Autoregressive Moving Average (ARMA) model: This model captures the autocorrelation within the vegetation index data, taking into account both autoregressive (AR) and moving average (MA) components.   

- Box-Jenkins model: This model incorporates precipitation data as an external input, recognizing the significant influence of rainfall on vegetation growth.

- Adaptive Kalman model: This model allows the coefficients of the Box-Jenkins model to dynamically vary over time, enabling it to capture changes in the relationship between vegetation and precipitation.  

The analysis involves constructing k-step linear predictors for each model and evaluating their predictive accuracy using metrics such as Mean Squared Error (MSE) and the variance of the prediction error.  The project compares the performance of these models, highlighting their strengths and weaknesses in capturing and predicting vegetation dynamics. 

<img src="https://github.com/user-attachments/assets/acd7f0e6-efa6-4975-ae61-625b0d70f16c" alt=" Model comparison" width="700" />

\
This repository includes:
- Full written report of results and mathematical modeling steps
- Matlab code
- Data
