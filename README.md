# Anomaly-Detection-in-Time-Series-Data
Using LSTM and Autoencoder to detect anomalies in S&amp;P 500 dataset.

Anomaly detection (Outlier Analysis) is the task of determining when something has gone astray from the “norm”. Anomaly detection using neural networks is modeled in an unsupervised / self-supervised manner.

The presumption is that normal behavior, and hence the quantity of available “normal” data, is the norm and that anomalies are the exception to the norm to the point where the modeling of “normalcy” is possible.

We will use Long Short-Term Memory (LSTM) neural network cells in our autoencoder model. LSTM networks are a sub-type of the more general recurrent neural networks (RNN). A key attribute of recurrent neural networks is their ability to persist information, or cell state, for use later in the network. This makes them particularly well suited for analysis of temporal data that evolves over time. LSTM networks are used in tasks such as speech recognition, text translation and here, in the analysis of stock and price for anomaly detection.

## Source - Kaggle

https://www.kaggle.com/pdquant/sp500-daily-19862018

Download the dataset in .csv format and name it as 'S&P_500_Index_Data.csv' and save it where 'anomaly_detection.ipynb' file is cloned.

## Project Overview

1- Exploratory Data Analysis

2- Data Preprocessing

3- Train and Test Split

4- Build an LSTM Autoencoder

5- Plot Metrics and Evaluate the Model

6- Detect Anomalies in the data
