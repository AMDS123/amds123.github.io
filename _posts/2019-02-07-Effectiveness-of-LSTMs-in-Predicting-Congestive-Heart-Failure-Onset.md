---
layout: post
title: "Effectiveness of LSTMs in Predicting Congestive Heart Failure Onset"
date: 2019-02-07 01:47:28
categories: arXiv_AI
tags: arXiv_AI Sparse Embedding CNN RNN Deep_Learning Prediction
author: Sunil Mallya, Marc Overhage, Navneet Srivastava, Tatsuya Arai, Cole Erdman
mathjax: true
---

* content
{:toc}

##### Abstract
In this paper we present a Recurrent neural networks (RNN) based architecture that achieves an AUCROC of 0.9147 for predicting the onset of Congestive Heart Failure (CHF) 15 months in advance using a 12-month observation window on a large cohort of 216,394 patients. We believe this to be the largest study in CHF onset prediction with respect to the number of CHF case patients in the cohort and the test set (3,332 CHF patients) on which the AUC metrics are reported. We explore the extent to which LSTM (Long Short Term Memory) based model, a variant of RNNs, can accurately predict the onset of CHF when compared to known linear baselines like Logistic Regression, Random Forests and deep learning based models such as Multi-Layer Perceptron and Convolutional Neural Networks. We utilize demographics, medical diagnosis and procedure data from 21,405 CHF and 194,989 control patients to as our features. We describe our feature embedding strategy for medical diagnosis codes that accommodates the sparse, irregular, longitudinal, and high-dimensional characteristics of EHR data. We empirically show that LSTMs can capture the longitudinal aspects of EHR data better than the proposed baselines. As an attempt to interpret the model, we present a temporal data analysis-based technique on false positives to attribute feature importance. A model capable of predicting the onset of congestive heart failure months in the future with this level of accuracy and precision can support efforts of practitioners to implement risk factor reduction strategies and researchers to begin to systematically evaluate interventions to potentially delay or avert development of the disease with high mortality, morbidity and significant costs.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1902.02443](http://arxiv.org/abs/1902.02443)

##### PDF
[http://arxiv.org/pdf/1902.02443](http://arxiv.org/pdf/1902.02443)

