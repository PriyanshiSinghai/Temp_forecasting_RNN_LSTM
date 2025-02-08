# Temp_forecasting_CNN_LSTM
A project predicting US temperature using different deep-learning approaches

# Forecasting Analysis Using CNN and LSTM Models

## Abstract

The project utilizes CNN and LSTM models to predict future temperature values accurately. The proposed approach leverages the strengths of deep learning techniques to improve traditional time series forecasting methods. The accuracy of the proposed models is compared, and results indicate that LSTM outperforms other models in long-term forecasting, while CNN provides efficient feature extraction. The combination of these models enhances forecasting accuracy for real-world applications.

## Introduction

Our project aims to develop a temperature forecasting system using deep learning techniques, leveraging past temperature data to predict future values. The system integrates three predictive models—CNN, RNN, and LSTM—to analyze sequential temperature data. While RNN captures time dependencies, LSTM effectively handles long-term dependencies, and CNN efficiently extracts spatial and temporal patterns. Weather forecasting is crucial for various industries, including agriculture, construction, and disaster management, making this approach beneficial for accurate predictions.

## Objective

The objective of this report is to present the key aspects and findings of the "Forecasting Analysis Using CNN and LSTM Models" project. The report aims to highlight the importance of accurate temperature forecasting, the advantages of each model, and a comparative analysis showcasing their effectiveness in predictive modeling.

## Literature Survey

1. Reviewing different deep learning algorithms for temperature forecasting, such as CNN and LSTM.
2. Exploring time series analysis techniques, including decomposition, differencing, and feature extraction.
3. Identifying evaluation metrics like RMSE, MAE, and R-squared for model accuracy assessment.
4. Investigating the real-time accuracy and limitations of predictive models for weather forecasting.
5. Comparing deep learning-based forecasting methods with traditional models 

## Data Collection and Preprocessing

### Data Source
- Historical temperature datasets from meteorological agencies.
- Data cleaning, normalization, and feature engineering.

### The Flow of Data Analysis
1. Data Acquisition
2. Preprocessing (Handling Missing Data, Normalization)
3. Feature Selection
4. Model Training and Evaluation
5. Forecasting and Visualization

## Forecasting Analysis Using CNN

### CNN Model

- Convolutional Neural Networks (CNNs) are widely used for feature extraction from structured data.
- In this project, CNN is applied to extract meaningful patterns from historical temperature data.
- The model consists of multiple convolutional and pooling layers to capture spatial dependencies in time-series data.

### Temperature Prediction (CNN)

- CNN effectively learns local dependencies in the dataset.
- The model provides competitive forecasting accuracy for short-term predictions.

## Forecasting Analysis Using RNN

### RNN Model

- Recurrent Neural Networks (RNNs) are designed to handle sequential data.
- The model retains memory across time steps, making it suitable for time-series forecasting.
- The architecture includes recurrent layers with activation functions like Tanh and ReLU.

### Temperature Prediction (RNN)

- RNN captures temporal relationships in the dataset.
- It performs well for short-term forecasting but struggles with long-term dependencies due to vanishing gradient issues.

## Forecasting Analysis Using LSTM

### LSTM Model

- LSTM (Long Short-Term Memory) networks overcome the limitations of traditional RNNs.
- The model consists of input, forget, and output gates, allowing it to remember long-term dependencies.
- LSTM is trained on historical temperature data for forecasting future values.

### Temperature Prediction (LSTM)

- The LSTM model follows the trend of actual temperature values closely.
- It outperforms other models in long-term forecasting due to its ability to retain historical context.

## Comparative Analysis

| Model  | MSE |
|--------|------|
| CNN    | 0.57 | 
| LSTM   | 0.036 | 

- LSTM exhibits the best performance in long-term temperature prediction.
- CNN provides efficient feature extraction but lacks long-term predictive power.


## Conclusion

This project successfully demonstrates the application of CNN and LSTM models for temperature forecasting. The comparative analysis highlights that LSTM achieves the highest accuracy in long-term forecasting, while CNN efficiently extracts features. By integrating deep learning techniques, we enhance the accuracy and reliability of temperature predictions, benefiting industries reliant on weather forecasting. Future research can explore hybrid models combining CNN and LSTM for improved predictive performance.

