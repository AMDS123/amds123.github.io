---
layout: post
title: "Performance Estimation of Synthesis Flows cross Technologies using LSTMs and Transfer Learning"
date: 2018-11-14 19:17:14
categories: arXiv_CV
tags: arXiv_CV Transfer_Learning RNN Prediction
author: Cunxi Yu, Wang Zhou
mathjax: true
---

* content
{:toc}

##### Abstract
Due to the increasing complexity of Integrated Circuits (ICs) and System-on-Chip (SoC), developing high-quality synthesis flows within a short market time becomes more challenging. We propose a general approach that precisely estimates the Quality-of-Result (QoR), such as delay and area, of unseen synthesis flows for specific designs. The main idea is training a Recurrent Neural Network (RNN) regressor, where the flows are inputs and QoRs are ground truth. The RNN regressor is constructed with Long Short-Term Memory (LSTM) and fully-connected layers. This approach is demonstrated with 1.2 million data points collected using 14nm, 7nm regular-voltage (RVT), and 7nm low-voltage (LVT) FinFET technologies with twelve IC designs. The accuracy of predicting the QoRs (delay and area) within one technology is $\boldsymbol{\geq}$\textbf{98.0}\% over $\sim$240,000 test points. To enable accurate predictions cross different technologies and different IC designs, we propose a transfer-learning approach that utilizes the model pre-trained with 14nm datasets. Our transfer learning approach obtains estimation accuracy $\geq$96.3\% over $\sim$960,000 test points, using only 100 data points for training.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1811.06017](http://arxiv.org/abs/1811.06017)

##### PDF
[http://arxiv.org/pdf/1811.06017](http://arxiv.org/pdf/1811.06017)

