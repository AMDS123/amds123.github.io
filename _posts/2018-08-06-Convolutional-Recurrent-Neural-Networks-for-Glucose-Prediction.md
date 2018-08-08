---
layout: post
title: "Convolutional Recurrent Neural Networks for Glucose Prediction"
date: 2018-08-06 18:05:54
categories: arXiv_CV
tags: arXiv_CV CNN RNN Deep_Learning Prediction
author: Kezhi Li, John Daniels, Pau Herrero-vi&#xf1;as, Chengyuan Liu, Pantelis Georgiou
mathjax: true
---

* content
{:toc}

##### Abstract
Glucose control serves as the primary method of diabetes management. Current digital therapeutic approaches for subjects with Type 1 diabetes mellitus (T1DM) such as the artificial pancreas and bolus calculators leverage machine learning techniques for predicting subcutaneous glucose for improved control. Deep learning has recently been applied in healthcare and medical research to achieve state-of-the-art results in a range of tasks including disease diagnosis, and patient state prediction among others. In this work, we present a deep learning model that is capable of predicting glucose levels over a 30-minute horizon with leading accuracy for simulated patient cases (RMSE = 10.02$\pm$1.28 [mg/dl] and MARD = 5.95$\pm$0.64\%) and real patient cases (RMSE = 21.23$\pm$1.15 [mg/dl] and MARD = 10.53$\pm$1.28\%). In addition, the model also provides competitive performance in forecasting adverse glycaemic events with minimal time lag both in a simulated patient dataset (MCC$_{hyperglycaemia}$ = 0.82$\pm$0.06 and MCC$_{hypoglycaemia}$ = 0.76$\pm$0.13) and in a real patient dataset (MCC$_{hyperglycaemia}$ = 0.79$\pm$0.04 and MCC$_{hypoglycaemia}$ = 0.28$\pm$0.11). This approach is evaluated on a dataset of 10 simulated cases generated from the UVa/Padova simulator and a clinical dataset of 5 real cases each containing glucose readings, insulin bolus, and meal (carbohydrate) data. Performance of the recurrent convolutional neural network is benchmarked against four state-of-the-art algorithms: support vector regression (SVR), latent variable (LVX) model, autoregressive model (ARX), and neural network for predicting glucose algorithm (NNPG).

##### Abstract (translated by Google)
葡萄糖控制是糖尿病管理的主要方法。目前用于患有1型糖尿病（T1DM）的受试者的数字治疗方法，例如人工胰腺和推注计算器，利用机器学习技术来预测皮下葡萄糖以改善控制。最近，深度学习已应用于医疗保健和医学研究，以在一系列任务中实现最先进的结果，包括疾病诊断和患者状态预测等。在这项工作中，我们提出了一个深度学习模型，能够预测30分钟内的葡萄糖水平，模拟患者病例具有领先的准确性（RMSE = 10.02 $ \ pm $ 1.28 [mg / dl]和MARD = 5.95 $ \ pm $ 0.64 \％）和真实病例（RMSE = 21.23 $ \ pm $ 1.15 [mg / dl]和MARD = 10.53 $ \ pm $ 1.28 \％）。此外，该模型还在模拟患者数据集中提供了预测不良血糖事件且具有最小时滞的竞争性能（MCC $ _ {hyperglycaemia} $ = 0.82 $ \ pm $ 0.06和MCC $ _ {hypoglycaemia} $ = 0.76 $ \ pm $ 0.13）和真实的患者数据集（MCC $ _ {hyperglycaemia} $ = 0.79 $ \ pm $ 0.04和MCC $ _ {hypoglycaemia} $ = 0.28 $ \ pm $ 0.11）。该方法在从UVa / Padova模拟器生成的10个模拟病例的数据集和5个真实病例的临床数据集上评估，每个病例包含葡萄糖读数，胰岛素推注和膳食（碳水化合物）数据。循环卷积神经网络的性能基于四种最先进的算法：支持向量回归（SVR），潜变量（LVX）模型，自回归模型（ARX）和用于预测葡萄糖算法的神经网络（NNPG） 。

##### URL
[http://arxiv.org/abs/1807.03043](http://arxiv.org/abs/1807.03043)

##### PDF
[http://arxiv.org/pdf/1807.03043](http://arxiv.org/pdf/1807.03043)

