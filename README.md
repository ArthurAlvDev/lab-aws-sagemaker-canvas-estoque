# 📊 Previsão de Estoque Inteligente na AWS com [SageMaker Canvas](https://aws.amazon.com/pt/sagemaker/canvas/)

## 🚀 Passo a Passo

### 1. Selecionar Dataset

- Foi selecionado o Dataset: dataset-500-curso-sagemaker-canvas-dio.csv, presente no repositorio da Dio.
  ![image](https://github.com/user-attachments/assets/79e2d621-fe00-4e23-83a9-0c61a6dfe6b5)
  

### 2. Construir/Treinar

- Objective metric: Avg.wQl - default
- Algorithms: Convolutional Neural Network - Quantile Regression,  Recurrent Neural Network - DeepAR+, Prophet, Autoregressive Integrated Moving Average, Amazon Forecast Non-Parametric Time Series, Exponential Smoothing (ETS)
Statistical.
- Forecast quantiles: 0.10, 0.50, 0.90
  ![image](https://github.com/user-attachments/assets/eaade7d1-ce41-4bf5-afd1-6943bcb5daf1)


### 3. Analisar

-   Avg. wQL: 1.273; MAPE: 0.715; WAPE: 0.958; RMSE: 5.633; MASE: 0.139;
![image](https://github.com/user-attachments/assets/872432c0-d00f-44fe-bc6d-7ef69aad5b73)


### 4. Prever

![single_prediction_results](https://github.com/user-attachments/assets/46b4ffee-08a6-4385-b8ca-7bb85ee454fb)

![single_prediction_results (1)](https://github.com/user-attachments/assets/f86f0a97-de4b-470c-89f8-99cd8f5ecc8d)

