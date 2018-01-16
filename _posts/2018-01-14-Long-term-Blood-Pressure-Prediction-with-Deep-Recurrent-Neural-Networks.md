---
layout: post
title: "Long-term Blood Pressure Prediction with Deep Recurrent Neural Networks"
date: 2018-01-14 13:56:46
categories: arXiv_AI
tags: arXiv_AI RNN Prediction
author: Peng Su, Xiao-Rong Ding, Yuan-Ting Zhang, Jing Liu, Fen Miao, Ni Zhao
mathjax: true
---

* content
{:toc}

##### Abstract
Existing methods for arterial blood pressure (BP) estimation directly map the input physiological signals to output BP values without explicitly modeling the underlying temporal dependencies in BP dynamics. As a result, these models suffer from accuracy decay over a long time and thus require frequent calibration. In this work, we address this issue by formulating BP estimation as a sequence prediction problem in which both the input and target are temporal sequences. We propose a novel deep recurrent neural network (RNN) consisting of multilayered Long Short-Term Memory (LSTM) networks, which are incorporated with (1) a bidirectional structure to access larger-scale context information of input sequence, and (2) residual connections to allow gradients in deep RNN to propagate more effectively. The proposed deep RNN model was tested on a static BP dataset, and it achieved root mean square error (RMSE) of 3.90 and 2.66 mmHg for systolic BP (SBP) and diastolic BP (DBP) prediction respectively, surpassing the accuracy of traditional BP prediction models. On a multi-day BP dataset, the deep RNN achieved RMSE of 3.84, 5.25, 5.80 and 5.81 mmHg for the 1st day, 2nd day, 4th day and 6th month after the 1st day SBP prediction, and 1.80, 4.78, 5.0, 5.21 mmHg for corresponding DBP prediction, respectively, which outperforms all previous models with notable improvement. The experimental results suggest that modeling the temporal dependencies in BP dynamics significantly improves the long-term BP prediction accuracy.

##### Abstract (translated by Google)
用于动脉血压（BP）估计的现有方法直接将输入的生理信号映射为输出BP值，而没有明确地建模BP动力学中潜在的时间依赖性。结果，这些模型长期遭受精度衰减，因此需要频繁校准。在这项工作中，我们通过将BP估计公式化为序列预测问题来解决这个问题，其中输入和目标都是时间序列。我们提出了一个由多层长短期记忆（LSTM）网络组成的新颖的深度递归神经网络（RNN），其中包括：（1）双向结构，用于访问输入序列的大尺度上下文信息;（2）连接以允许深RNN中的梯度更有效地传播。提出的深RNN模型在静态BP数据集上进行测试，分别对收缩压（SBP）和舒张压（DBP）预测均方根误差（RMSE）分别为3.90和2.66 mmHg，超过了传统BP预测楷模。在多天的BP数据集中，深度RNN在第1天SBP预测后的第1天，第2天，第4天和第6个月的RMSE分别为3.84,5.25,5.80和5.81 mmHg，分别为1.80,4.78,5.0,5.21 mmHg分别对应相应的DBP预测值，优于以前的所有模型，有显着的改善。实验结果表明，在BP动态模型中的时间依赖性显着提高了长期BP预测精度。

##### URL
[http://arxiv.org/abs/1705.04524](http://arxiv.org/abs/1705.04524)

##### PDF
[http://arxiv.org/pdf/1705.04524](http://arxiv.org/pdf/1705.04524)

