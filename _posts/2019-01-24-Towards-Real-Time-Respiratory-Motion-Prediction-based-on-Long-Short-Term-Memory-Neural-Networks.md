---
layout: post
title: "Towards Real-Time Respiratory Motion Prediction based on Long Short-Term Memory Neural Networks"
date: 2019-01-24 20:34:56
categories: arXiv_CV
tags: arXiv_CV RNN Prediction
author: Hui Lin, Chengyu Shi, Brian Wang, Maria F. Chan, Xiaoli Tang, Wei Ji
mathjax: true
---

* content
{:toc}

##### Abstract
Radiation therapy of thoracic and abdominal tumors requires incorporating the respiratory motion into treatments. To precisely account for the patient respiratory motions and predict the respiratory signals, a generalized model for predictions of different types of respiratory motions is desired. The aim of this study is to explore the feasibility of developing a Long Short-Term Memory (LSTM)-based model for the respiratory signal prediction. To achieve that, 1703 sets of Real-Time Position Management data were collected from retrospective studies across three clinical institutions. These datasets were separated as the training, internal validity and external validity groups. 1187 datasets were used for model development and the remaining 516 datasets were used to test the generality power of the model. Furthermore, an exhaustive grid search was implemented to find the optimal hyper-parameters of the LSTM model. The hyper-parameters are the number of LSTM layers, the number of hidden units, the optimizer, the learning rate, the number of epochs, and the length of time lags. Our model achieved superior accuracy over conventional artificial neural network models: with a prediction window of 500ms, the LSTM model achieved an average relative Mean Absolute Error (MAE) of 0.037, an average Root Mean Square Error (RMSE) of 0.048, and a Maximum Error (ME) of 1.687 in the internal validity data, and an average relative MAE of 0.112, an average RMSE of 0.139 and an ME of 1.811 in the external validity data. Compared to the LSTM model trained with default hyper-parameters, the MAE of the optimized model results decreased by 20%, indicating the importance of tuning the hyper-parameters of LSTM models to obtain superior accuracy. This study demonstrates the potential of deep LSTM models for the respiratory signal prediction and illustrates the impacts of major hyper-parameters in LSTM models.

##### Abstract (translated by Google)


##### URL
[https://arxiv.org/abs/1901.08638](https://arxiv.org/abs/1901.08638)

##### PDF
[https://arxiv.org/pdf/1901.08638](https://arxiv.org/pdf/1901.08638)

