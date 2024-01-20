# Predictive Maintenance of Aircraft Engine

Predictive Maintenance techniques play a crucial role in minimizing equipment downtime and optimizing maintenance schedules. In the context of aircraft engines, predicting failures and estimating the remaining useful life (RUL) is essential for efficient maintenance planning. This project aims to implement various Predictive Maintenance methods and assess their performance in two main categories: Classification and Regression.

## Data
The dataset consists of multiple multivariate time series, each representing the operational behavior of a different engine. The engines start in a normal operating state and develop faults at some point. In the training set, faults escalate until system failure, while in the test set, the time series ends before failure. The dataset is available [here](https://www.kaggle.com/datasets/behrad3d/nasa-cmaps).

- Training set: Operational data from 100 engines with varying run lengths (128 to 356 cycles).
- Test set: Operational data from 100 different engines, not overlapping with the training set.


## Models for Predictive Maintenance

1. **Exponential Degradation Model for RUL Prediction**
   - Implement a model based on exponential degradation to predict the remaining useful life of engines.

2. **LSTM Model for RUL Prediction**
   - Implement a Long Short-Term Memory (LSTM) neural network for predicting the remaining useful life.

3. **LSTM Model for Binary and Multiclass Classification**
   - Use LSTM for binary classification (normal vs. faulty) and multiclass classification (multiple fault categories).

4. **1D CNN for Binary and Multiclass Classification**
   - Utilize a 1D Convolutional Neural Network (CNN) for binary and multiclass classification of engine health.

5. **1D CNN-SVM for Binary Classification**
   - Combine a 1D CNN with Support Vector Machines (SVM) for binary classification of engine health.


